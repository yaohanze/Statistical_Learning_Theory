There are 6 datasets in total. Full players info from FIFA 15 to FIFA 20. 
Want to investigate whether there is a overall rating advantage on England Premier League over other 4 major European league players (Spain Laliga, German Bundesliga, France Ligue 1, Italy Seria A).
Also want to investigate whether the overall rating model is defferent for players from england than palyers with other natinality.
This project is based on the long-existing claim in FIFA community that the game has an overall rating advange for EPL players and England players.
The main goal of this project is to investagate whether this overall rating advange really exists. And if it exsits, whether this unfairness is getting worse or better over the years.
1.Data cleaning (Handle missing values, get rid of goalkeepers, add necessary columns)
fifa15:
EPL team: Leicester City, Arsenal, Tottenham Hotspur, Manchester City, Manchester United, Southampton, West Ham United, Liverpool, Stoke City, Chelsea, Everton, Swansea City, West Bromwich Albion, Burnley
Crystal Palace, Sunderland, Newcastle United, Aston Villa, Hull City, Queens Park Rangers
Laliga team: FC Barcelona, Real Madrid, Atlético Madrid, Villarreal CF, Athletic Club de Bilbao, RC Celta, Sevilla FC, Málaga CF, Real Sociedad, Valencia CF, SD Eibar, RCD Espanyol,
Deportivo de La Coruña, Granada CF, Rayo Vallecano, Getafe CF, Levante UD, UD Almería, Córdoba CF
Bundesliga team: FC Bayern München, Borussia Dortmund, Bayer 04 Leverkusen, Borussia Mönchengladbach, FC Schalke 04, 1. FSV Mainz 05, Hertha BSC, VfL Wolfsburg, 1. FC Köln, Hamburger SV, FC Augsburg,
SV Werder Bremen, TSG 1899 Hoffenheim, Eintracht Frankfurt, VfB Stuttgart, Hannover 96, SC Freiburg, SC Paderborn 07
Seria A team: Juventus, Napoli, Roma, Inter, Fiorentina, Sassuolo, Milan, Lazio, Chievo Verona, Genoa, Empoli, Torino, Atalanta, Sampdoria, Udinese, Carpi, Hellas Verona, Palermo, Cagliari, Cesena, Parma
League 1 team: Paris Saint-Germain, Olympique Lyonnais, AS Monaco, OGC Nice, LOSC Lille, AS Saint-Étienne, Stade Malherbe Caen, Stade Rennais FC, FC Girondins de Bordeaux, Montpellier HSC, Olympique de Marseille,
FC Nantes, FC Lorient, En Avant de Guingamp, Toulouse Football Club, Stade de Reims, Évian Thonon Gaillard FC, Racing Club de Lens, FC Metz
fifa16:
EPL team: Leicester City, Arsenal, Tottenham Hotspur, Manchester City, Manchester United, Southampton, West Ham United, Liverpool, Stoke City, Chelsea, Everton, Swansea City, Watford, West Bromwich Albion,
Crystal Palace, Bournemouth, Sunderland, Newcastle United, Norwich City, Aston Villa
Laliga team: FC Barcelona, Real Madrid, Atlético Madrid, Villarreal CF, Athletic Club de Bilbao, RC Celta, Sevilla FC, Málaga CF, Real Sociedad, Real Betis, UD Las Palmas, Valencia CF, SD Eibar, RCD Espanyol,
Deportivo de La Coruña, Granada CF, Real Sporting de Gijón, Rayo Vallecano, Getafe CF, Levante UD
Bundesliga team: FC Bayern München, Borussia Dortmund, Bayer 04 Leverkusen, Borussia Mönchengladbach, FC Schalke 04, 1. FSV Mainz 05, Hertha BSC, VfL Wolfsburg, 1. FC Köln, Hamburger SV, FC Ingolstadt 04, FC Augsburg,
SV Werder Bremen, SV Darmstadt 98, TSG 1899 Hoffenheim, Eintracht Frankfurt, VfB Stuttgart, Hannover 96
Seria A team: Juventus, Napoli, Roma, Inter, Fiorentina, Sassuolo, Milan, Lazio, Chievo Verona, Genoa, Empoli, Torino, Atalanta, Bologna, Sampdoria, Palermo, Udinese, Carpi, Frosinone, Hellas Verona
League 1 team: Paris Saint-Germain, Olympique Lyonnais, AS Monaco, OGC Nice, LOSC Lille, AS Saint-Étienne, Stade Malherbe Caen, Stade Rennais FC, Angers SCO, FC Girondins de Bordeaux, Montpellier HSC, Olympique de Marseille,
FC Nantes, FC Lorient, En Avant de Guingamp, Toulouse Football Club, Stade de Reims, GFC Ajaccio, ESTAC Troyes
fifa17:
EPL team: Leicester City, Arsenal, Tottenham Hotspur, Manchester City, Manchester United, Southampton, West Ham United, Liverpool, Stoke City, Chelsea, Everton, Swansea City, Watford, West Bromwich Albion,
Crystal Palace, Bournemouth, Sunderland, Burnley, Hull City, Middlesbrough
Laliga team: FC Barcelona, Real Madrid, Atlético Madrid, Villarreal CF, Athletic Club de Bilbao, RC Celta, Sevilla FC, Málaga CF, Real Sociedad, Real Betis, UD Las Palmas, Valencia CF, SD Eibar, RCD Espanyol,
Deportivo de La Coruña, Granada CF, Real Sporting de Gijón, CD Leganés, Deportivo Alavés, CA Osasuna
Bundesliga team: FC Bayern München, Borussia Dortmund, Bayer 04 Leverkusen, Borussia Mönchengladbach, FC Schalke 04, 1. FSV Mainz 05, Hertha BSC, VfL Wolfsburg, 1. FC Köln, Hamburger SV, FC Ingolstadt 04, FC Augsburg,
SV Werder Bremen, SV Darmstadt 98, TSG 1899 Hoffenheim, Eintracht Frankfurt, RB Leipzig, SC Freiburg
Seria A team: Juventus, Napoli, Roma, Inter, Fiorentina, Sassuolo, Milan, Lazio, Chievo Verona, Genoa, Empoli, Torino, Atalanta, Bologna, Sampdoria, Palermo, Udinese, Cagliari, Crotone, Pescara
League 1 team: Paris Saint-Germain, Olympique Lyonnais, AS Monaco, OGC Nice, LOSC Lille, AS Saint-Étienne, Stade Malherbe Caen, Stade Rennais FC, Angers SCO, FC Girondins de Bordeaux, Montpellier HSC, Olympique de Marseille,
FC Nantes, FC Lorient, En Avant de Guingamp, Toulouse Football Club, FC Metz, Dijon FCO, AS Nancy Lorraine
fifa18: 
EPL team: Leicester City, Arsenal, Tottenham Hotspur, Manchester City, Manchester United, Southampton, West Ham United, Liverpool, Stoke City, Chelsea, Everton, Swansea City, Watford, West Bromwich Albion,
Crystal Palace, Bournemouth, Burnley, Newcastle United, Brighton & Hove Albion, Huddersfield Town
Laliga team: FC Barcelona, Real Madrid, Atlético Madrid, Villarreal CF, Athletic Club de Bilbao, RC Celta, Sevilla FC, Málaga CF, Real Sociedad, Real Betis, UD Las Palmas, Valencia CF, SD Eibar, RCD Espanyol,
Deportivo de La Coruña, CD Leganés, Deportivo Alavés, Getafe CF, Girona FC, Levante UD
Bundesliga team: FC Bayern München, Borussia Dortmund, Bayer 04 Leverkusen, Borussia Mönchengladbach, FC Schalke 04, 1. FSV Mainz 05, Hertha BSC, VfL Wolfsburg, 1. FC Köln, Hamburger SV, FC Augsburg,
SV Werder Bremen, TSG 1899 Hoffenheim, Eintracht Frankfurt, RB Leipzig, SC Freiburg, VfB Stuttgart, Hannover 96
Seria A team: Juventus, Napoli, Roma, Inter, Fiorentina, Sassuolo, Milan, Lazio, Chievo Verona, Genoa, Torino, Atalanta, Bologna, Sampdoria, Udinese, Cagliari, Crotone, SPAL, Hellas Verona, Benevento
League 1 team: Paris Saint-Germain, Olympique Lyonnais, AS Monaco, OGC Nice, LOSC Lille, AS Saint-Étienne, Stade Malherbe Caen, Stade Rennais FC, Angers SCO, FC Girondins de Bordeaux, Montpellier HSC, Olympique de Marseille,
FC Nantes, En Avant de Guingamp, Toulouse Football Club, FC Metz, Dijon FCO, Amiens SC, RC Strasbourg Alsace,  ESTAC Troyes
fifa19:
EPL team: Leicester City, Arsenal, Tottenham Hotspur, Manchester City, Manchester United, Southampton, West Ham United, Liverpool, Chelsea, Everton, Watford,Crystal Palace, Bournemouth, Burnley, Newcastle United, 
Brighton & Hove Albion, Huddersfield Town, Wolverhampton Wanderers, Cardiff City, Fulham
Laliga team: FC Barcelona, Real Madrid, Atlético Madrid, Villarreal CF, Athletic Club de Bilbao, RC Celta, Sevilla FC, Real Sociedad, Real Betis, Valencia CF, SD Eibar, RCD Espanyol, CD Leganés, Deportivo Alavés, 
Getafe CF, Girona FC, Levante UD, Real Valladolid CF, SD Huesca, Rayo Vallecano
Bundesliga team: FC Bayern München, Borussia Dortmund, Bayer 04 Leverkusen, Borussia Mönchengladbach, FC Schalke 04, 1. FSV Mainz 05, Hertha BSC, VfL Wolfsburg, FC Augsburg, SV Werder Bremen, TSG 1899 Hoffenheim, 
Eintracht Frankfurt, RB Leipzig, SC Freiburg, VfB Stuttgart, Hannover 96, Fortuna Düsseldorf, 1. FC Nürnberg
Seria A team: Juventus, Napoli, Roma, Inter, Fiorentina, Sassuolo, Milan, Lazio, Chievo Verona, Genoa, Torino, Atalanta, Bologna, Sampdoria, Udinese, Cagliari, SPAL, Parma, Empoli, Frosinone
League 1 team: Paris Saint-Germain, Olympique Lyonnais, AS Monaco, OGC Nice, LOSC Lille, AS Saint-Étienne, Stade Malherbe Caen, Stade Rennais FC, Angers SCO, FC Girondins de Bordeaux, Montpellier HSC, Olympique de Marseille,
FC Nantes, En Avant de Guingamp, Dijon FCO, Amiens SC, RC Strasbourg Alsace, Toulouse Football Club,  Stade de Reims, Nîmes Olympique
fifa20:
EPL team: Leicester City, Arsenal, Tottenham Hotspur, Manchester City, Manchester United, Southampton, West Ham United, Liverpool, Chelsea, Everton, Watford, Crystal Palace, Burnley, Newcastle United, Sheffield United,
Brighton & Hove Albion, Wolverhampton Wanderers, Bournemouth, Norwich City, Aston Villa
Laliga team: FC Barcelona, Real Madrid, Atlético Madrid, Villarreal CF, Athletic Club de Bilbao, RC Celta, Sevilla FC, Real Sociedad, Real Betis, Valencia CF, SD Eibar, RCD Espanyol, CD Leganés, Deportivo Alavés, 
Getafe CF, Levante UD, Real Valladolid CF, Granada CF, CA Osasuna, RCD Mallorca
Bundesliga team: FC Bayern München, Borussia Dortmund, Bayer 04 Leverkusen, Borussia Mönchengladbach, FC Schalke 04, 1. FSV Mainz 05, Hertha BSC, VfL Wolfsburg, FC Augsburg, SV Werder Bremen, TSG 1899 Hoffenheim, 
Eintracht Frankfurt, RB Leipzig, SC Freiburg, Fortuna Düsseldorf, 1. FC Union Berlin, 1. FC Köln, SC Paderborn 07
Seria A team: Juventus, Napoli, Roma, Inter, Fiorentina, Sassuolo, Milan, Lazio, Genoa, Torino, Atalanta, Bologna, Sampdoria, Udinese, Cagliari, SPAL, Parma, Hellas Verona, Lecce, Brescia
League 1 team: Paris Saint-Germain, Olympique Lyonnais, AS Monaco, OGC Nice, LOSC Lille, AS Saint-Étienne, Stade Rennais FC, Angers SCO, FC Girondins de Bordeaux, Montpellier HSC, Olympique de Marseille,
FC Nantes, Dijon FCO, Amiens SC, RC Strasbourg Alsace, Toulouse Football Club,  Stade de Reims, Nîmes Olympique, Stade Brestois 29, FC Metz

