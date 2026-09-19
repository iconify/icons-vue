<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gq4nsy2sh"/><path class="dqa3mrb6s"/><g class="d2kvgvbvc"><path class="mrqzt38ql"/><path class="d5zs6nbgk"/><path class="n5_dy5ttw"/><path class="cul4o_bld"/><path class="h48xiwyht"/><path class="wkv1r9bhb"/><path class="w-1_kvnza"/><path class="rykw3l1bp"/><path class="gnah2keth"/><path class="aa69oeb3t"/><path class="xmvdk1bcg"/><path class="ntjo5bbzf"/><path class="r4bei3qlz"/><path class="k--oml4mp"/><path class="pv4eiyb5r"/><path class="tkl4wt1yi"/><path class="z1psxacmy"/><path class="w5dywxbbr"/><path class="lnt1ylwma"/><path class="ugnt9eaos"/><path class="ltwskuh9x"/><path class="nxonwh37z"/><path class="w_2geub3x"/><path class="ig2x4eyed"/><path class="ushvxcbix"/><path class="q9h587j4v"/><path class="z5bmk-b2y"/><path class="omo-k5-_u"/><path class="w4geblv-c"/><path class="hnzhdjc2e"/><path class="aicqw8eqe"/><path class="ki-h0bc6f"/><path class="mylawqbrs"/><path class="r8eqyoy_r"/><path class="pfrc4v-0q"/><path class="ch_13xbzw"/><path class="l0sg5dgub"/><path class="z-shwx6wr"/><path class="v3qpysyoo"/><path class="rr3wt9brq"/><path class="jwym5i4tt"/><path class="ugq9e5a6q"/><path class="qx-8cdbku"/><path class="o1g_wzwlr"/><path class="v0pq0cblu"/><path class="ftpoz9awz"/><path class="pyod10oei"/><path class="xd5vwzbqs"/><path class="f0ssesb7c"/><path class="i2o9s4bnd"/><path class="c_r1_ab9e"/><path class="lhav9tb2f"/><path class="x20xusb3x"/><path class="dg62vccdl"/><path class="vozai_3hk"/><path class="jz5ucwbwb"/><path class="mcq6br_ck"/><path class="r24uaybjl"/><path class="zk131nb4b"/><path class="ks1vnybrn"/><path class="gxzgt_65i"/><path class="hrfzv1-3u"/><path class="t8zk3pcvy"/><path class="qhe-m8bkd"/><path class="rsxcak-ev"/><path class="ck0slqbei"/><path class="wy60pt04s"/><path class="hkxhdccqi"/><path class="q3e9-2pzw"/><path class="s9kyy6i7i"/><path class="t3v2jqbzn"/><path class="l4u51zb9f"/><path class="m0cg1ltac"/><path class="rd6pw3b6f"/><path class="g-u07bb5u"/><path class="cfjphubye"/><path class="g0g5amcuw"/><path class="ht4tcht3q"/><path class="veycj7bfv"/><path class="aedpz0j1y"/><path class="tj88cxbiv"/><path class="ct99vls8m"/><path class="tbp2icc6i"/><path class="dts5m6_dv"/><path class="w_31h4bvj"/><path class="l4806vo2r"/><path class="q5kyaachb"/><path class="s8ajs9tua"/><path class="dzjabcbbz"/><path class="ar7a0cbln"/><path class="se_thcbes"/><path class="wgx8aab0s"/><path class="xi_73q-fc"/><path class="jas9qubuv"/><path class="n-2-c_bwz"/><path class="iw9tqdbeq"/><path class="gqw0zeb8s"/><path class="y_9sfpbfn"/><path class="rwoq_4bmg"/><path class="uxmf5cxdr"/><path class="o73w2ibia"/><path class="p76_eybtp"/><path class="x64f7qgrk"/><path class="y-5gkeb7h"/><path class="itcd0u_we"/><path class="q8sjonbkw"/><path class="mb52o4b5p"/><path class="qm8_ccckk"/><path class="hvgqi0lza"/><path class="bu0lehrgz"/><path class="nbqle0b6f"/><path class="bypgllb9a"/><path class="ggt9q8b_c"/><path class="gr8wbra3w"/><path class="zvmydpbnm"/><path class="ullyp8mqu"/><path class="im3qm2bek"/><path class="fymomnbqb"/><path class="j31a1-b_o"/><path class="shufelbox"/><path class="vfaa4eb5t"/><path class="t-9bwxbre"/><path class="wdpt3c5kt"/><path class="bg5hyflvg"/><path class="iz6huebdy"/><path class="ornw-mygp"/><path class="hi335db-x"/><path class="tor7-cc7l"/><path class="peo5drbyq"/><path class="a-4zf0b1t"/><path class="xfe80wy7k"/><path class="ubue6-tza"/><path class="rxw9_8hpv"/><path class="yf3c7m3-k"/><path class="pal4s2ybs"/><path class="dy57j5bun"/><path class="glmg6ziqz"/><path class="pxwk1bbzq"/><path class="nvl54keir"/><path class="fqnsk5bjy"/><path class="s0kwctb2p"/><path class="lqak0db-z"/><path class="jg0qkubxh"/><path class="i7o8zry3n"/><path class="c2n4xxbyf"/><path class="lnjopoe4p"/><path class="tlyy3tbxs"/><path class="rd2sopq7t"/><path class="h80qf2avz"/><path class="f4dv14uqu"/><path class="m5na1acjw"/><path class="l4a_uq91o"/><path class="i-7q1fbwd"/><path class="w1g-a8kpj"/><path class="qwohugcks"/><path class="evmbwib6t"/><path class="c91dl22by"/><path class="p3p0322xw"/><path class="u4ohbl-qa"/><path class="hnscxtbzo"/><path class="qgya2iyuf"/><path class="vffcvvbew"/><path class="tm03ulbde"/><path class="lxt7y2yli"/><path class="ktwev-btn"/><path class="qwkaofjqh"/><path class="kegs2ndcc"/><path class="ubyf6wbhu"/><path class="r8_r26b4e"/><path class="b2z5bhggj"/><path class="qa7eiq08f"/><path class="i1mv624kw"/><path class="bm-d3kbei"/><path class="wqr7nibuk"/><path class="tenkm8bzd"/><path class="bkk_50lqg"/><path class="yf9k3y7qm"/><path class="jotzt5blg"/><path class="bk7zqac2n"/><path class="dkupljp2l"/><path class="t0z7-m0pi"/><path class="euwldccpx"/><path class="loisktbku"/><path class="qsgvg2hub"/><path class="mu4ez21vl"/><path class="kit7k5kne"/><path class="nt7doctwd"/><path class="hgvpwfybx"/><path class="f8xcf4--e"/><path class="cq0ur2b0l"/><path class="zoonxhbdp"/><path class="fam0rr-ra"/><path class="wknbhetjf"/><path class="y1hyu_ben"/><path class="zqkg9hbtg"/><path class="jcvo5bcir"/><path class="uzcpmssrf"/><path class="buxmyab-g"/><path class="xzs5s4bpv"/><path class="h_zeadcdk"/><path class="wo_fkybrs"/><path class="gee9vhmbg"/><path class="jly6tacaa"/><path class="iqrl4ye8o"/><path class="ag_i-zlgo"/><path class="gfv1xrbaj"/><path class="e8kajabvj"/><path class="q0wm-bbqp"/><path class="qrthxee9n"/><path class="tkuizxbmx"/><path class="kb_2s943r"/><path class="lbxx21rir"/><path class="dyua5fzdx"/><path class="gx5g4uxeh"/><path class="nfbnxmb8f"/><path class="tnms_6bav"/><path class="afdej5qyw"/><path class="h9zppubkl"/><path class="bew0jb_rg"/><path class="a4t-gm3qr"/><path class="dvr07yctg"/><path class="xpfyjlbwo"/><path class="uikcmf-hc"/><path class="q-kci1-ox"/><path class="k6edmcbsa"/><path class="tkot8pb-f"/><path class="cnnjb4bwq"/><path class="a85a_5kgv"/><path class="fwz1hvbyt"/><path class="wx5vfffgy"/><path class="abs8gutyo"/><path class="leocf4s-i"/><path class="j2ofndv0o"/><path class="zt58yaczq"/><path class="qcnd7gb2d"/><path class="az6234o6b"/><path class="b8qcs8bas"/><path class="sa08j0pyh"/><path class="j5ds9bbtb"/><path class="nud9glb1o"/><path class="jjnahwizo"/><path class="c6hqs_3fy"/><path class="u70p2abpg"/><path class="ehrgpybvp"/><path class="hsv4mybpk"/><path class="kwnm7fz9l"/><path class="tuhadebap"/><path class="gncd5gbyi"/><path class="dpw-l-bis"/><path class="q7e7pxpnt"/><path class="liv_zh8be"/><path class="y5tyzgbab"/><path class="zz6v-sbxv"/><path class="ldo0sgk8k"/><path class="psz8ufbrz"/><path class="pucdy5bsq"/><path class="ej9zyna8s"/><path class="e70ojoplf"/><path class="vnt45sb6x"/><path class="ll4kc7j2u"/><path class="yr42lkbzw"/><path class="lw4t0bbgb"/><path class="p2o__8j9m"/><path class="nbd-feb9i"/><path class="jxpp2ub_g"/><path class="bwp9db_2u"/><path class="a5ceoobxx"/><path class="c868vek5q"/><path class="a3g5gpb6j"/><path class="z9gt93uaf"/><path class="p3c673bax"/><path class="yg-e5ubjq"/><path class="q_t9j5b7c"/><path class="l5umebb5u"/><path class="m1st8bbll"/><path class="kws_y618f"/><path class="gg79i5inz"/><path class="vl_swvb1g"/><path class="ywq33ccdi"/><path class="t_wz7qbqn"/><path class="td7upkbmn"/><path class="v8jrmmiwd"/><path class="ul_bz4men"/><path class="hnnjcqbcs"/><path class="c5xm41blo"/><path class="f5fav6k5g"/><path class="zytt8jbst"/><path class="fg4t4vbpy"/><path class="mggtumshu"/><path class="hrkrm3bwo"/><path class="fkwdkjn2m"/><path class="eni-fr_wr"/><path class="exkb_w2jo"/><path class="gwq1c137m"/><path class="j420qlbhk"/><path class="tzyz41b2f"/><path class="ny73zac7b"/><path class="ojrd02gjg"/><path class="z-f6eydjh"/><path class="mquoj-apb"/><path class="r6n1_r_1m"/><path class="n6v9ujule"/><path class="k9htqtbqv"/><path class="m4fe-zbql"/><path class="wok0c0b-k"/><path class="por3g4b0q"/><path class="o778ovjzm"/><path class="o3nq33bbr"/><path class="v5klsm7pz"/><path class="j8opehdjn"/><path class="ychvjpqxs"/><path class="v334k4b0f"/><path class="xp2cb5-nv"/><path class="o19nplbab"/><path class="p2pbifb9c"/><path class="bqk56-koj"/><path class="zx-3cybdz"/><path class="dpo8h6qom"/><path class="wbx7msbws"/><path class="d_j70abxz"/><path class="zignzcbrq"/><path class="qdk2w9gkc"/><path class="ng--nnbdb"/><path class="mxjsy0jay"/><path class="cy-z_-5dq"/><path class="x1pyx3bkp"/><path class="u5w_ngb_x"/><path class="g96tk5bbj"/><path class="ids84txtt"/><path class="p3ab5wifo"/><path class="d_y63gbou"/><path class="j7tct8bqa"/><path class="xwghwqbho"/><path class="n5mok3bco"/><path class="qg16sm3tm"/><path class="fbg2fxmjm"/><path class="hmidmp8ie"/><path class="ig70v6b1p"/><path class="d27pkdgfd"/><path class="hav91za5i"/><path class="o40oj7bxy"/><path class="zd6qhzzqp"/><path class="ul7a65mhy"/><path class="mhpmg8lvz"/><path class="aqd-shbnc"/><path class="l6dl-bbgk"/><path class="i6d59tbvm"/><path class="bwk9bbc8f"/><path class="xzsallbkc"/><path class="yg-k8bsov"/><path class="eg560nrcu"/><path class="g-zfni8da"/><path class="j0v4gpb9d"/><path class="b5okfhswt"/><path class="teyaoq5-u"/><path class="onfy21lrx"/><path class="vux51zb3t"/><path class="cynyr7b8s"/><path class="e3rrtvbfr"/><path class="i5qdjt20q"/><path class="n7b6iib7s"/><path class="i0l-98byu"/><path class="zdxwivbxd"/><path class="mm4lv_bqr"/><path class="h0w-icbbk"/><path class="syhp5-wkn"/><path class="yavujeqzr"/><path class="desrn3b7c"/><path class="vofvbcbcm"/><path class="bxtlyy_mb"/><path class="tu-f4acsj"/><path class="rj3m_wd9x"/><path class="nly46hbwt"/><path class="tzaqnjb2k"/><path class="szlkakb5i"/><path class="learl5bcb"/><path class="w9ofi8vgl"/><path class="pk52-zbyo"/><path class="a5xdqqieb"/><path class="weqer3buy"/><path class="l6z56lbke"/><path class="xcdo7ccjb"/><path class="v_srvrnzc"/><path class="csidll8oh"/><path class="eq2ntwbvg"/><path class="mg_44ug6y"/><path class="g6nv-3cou"/><path class="si6s-wbeh"/><path class="xamr67vaw"/><path class="li-papbzu"/><path class="cc0vdnbci"/><path class="re82c-bpw"/><path class="utj48nbuu"/><path class="icyf0hdkc"/><path class="xepvxxbhk"/><path class="i6mpxybcf"/><path class="tc4h_4blz"/><path class="dvcp_bsmc"/><path class="k2s-eyb9v"/><path class="xfs60ab8k"/><path class="cc3orfbmx"/><path class="sz79jnuoy"/><path class="pa11hxb2t"/><path class="x10zodbal"/><path class="by3jg9b6j"/><path class="dea8n3_ly"/><path class="ojjh2pb7l"/><path class="vioukkblp"/><path class="aqesdl8te"/><path class="w7pxklhzn"/><path class="uwis12g3i"/><path class="m5fy-omtt"/><path class="oe6ov9bmr"/><path class="pckc5pb6k"/><path class="dzq1-najq"/><path class="jcoeunbdq"/><path class="w0u5macsn"/><path class="blcholb5q"/><path class="epkjlri-o"/><path class="rcvfodzze"/><path class="xfzfgvbod"/><path class="heaa_8ber"/><path class="th2i30qom"/><path class="sg52v8rwk"/><path class="iiy5die8r"/><path class="czrf91blx"/><path class="tbq_vxbpo"/><path class="i5z4erbks"/><path class="w9h-fobrh"/><path class="v81l_ybvn"/><path class="jk7k4-bjq"/><path class="j6nqwrzxo"/><path class="nzyyfw5rf"/><path class="zsgwtcbda"/><path class="dubvqcc2r"/><path class="va55kepqn"/><path class="z_3tg_82b"/><path class="l5ja5-17d"/><path class="h286y-hgg"/><path class="k9sdg_l6x"/><path class="u30fjwnqn"/><path class="n2ayz6bau"/><path class="oz9q58bpt"/><path class="moqusfohm"/><path class="wpr1gljnf"/><path class="jm6fvub1x"/><path class="ecw2pcbcc"/><path class="nm6sl8b-r"/><path class="h5eqn7dwo"/><path class="cns6cu5ug"/><path class="ut2uc9bpo"/><path class="w_dpt3bkv"/><path class="b3p4ieb-x"/><path class="v4794dbem"/><path class="yg8uyq_ir"/><path class="hnyq82b1q"/><path class="a3t9x-d3h"/><path class="m0wahvbbs"/><path class="ijfczsbrl"/><path class="vkql6bkjg"/><path class="mluf5cijp"/><path class="w7ompabjh"/><path class="jk05edc5p"/><path class="w8lkwybgy"/><path class="m_ftqvn5e"/><path class="y_c00d0xu"/><path class="wftbadbpk"/><path class="xxbsdeboz"/><path class="xj5xy3bxm"/><path class="neiqhwvup"/><path class="eaxo80bev"/><path class="ghyxwebtp"/><path class="f3k729bhh"/><path class="w6l4zrbmk"/><path class="zy431wkly"/><path class="oxw581idy"/><path class="b9roqt-fs"/><path class="qcg7865uy"/><path class="vlm-txb7z"/><path class="ju9-n0rcc"/><path class="ugetau70r"/><path class="s_dc0bclp"/><path class="frjbhwbim"/><path class="ygzzu-b7x"/><path class="ekxtt3bif"/><path class="rpwj8ib3x"/><path class="u2q85dois"/><path class="tbgcdj_fm"/><path class="f-5sombff"/><path class="w3e3bqb5y"/><path class="umemzwbga"/><path class="wmyhjuu9w"/><path class="gpw72ib_h"/><path class="y23qnebec"/><path class="urpn2e4ay"/><path class="k_6_rrbys"/><path class="ohjovpqbn"/><path class="xucu3cb6n"/><path class="a-emgnbyv"/><path class="zlulpubwz"/><path class="rva-fgb7b"/><path class="vnwgael6c"/><path class="llw3_wb7e"/><path class="lt7v68b3a"/><path class="qkvwnsbjr"/><path class="mpxekrbuz"/><path class="f7_ls6b8t"/><path class="aicd4o09r"/><path class="jrye_48ii"/><path class="b1rnxflue"/><path class="lonmyqbpd"/><path class="gmdad7afl"/><path class="swhztidag"/><path class="vejbrwbul"/><path class="bz_e48aon"/><path class="v3iv-92ry"/><path class="ni3e26ind"/><path class="ebi6nvpnr"/><path class="uy407tbdz"/><path class="j2xep-bmy"/><path class="iwa8ybb5v"/><path class="mebl5j3zb"/><path class="kjsl2j77p"/><path class="q1l2necdr"/><path class="xy41i7b1e"/><path class="iu27bkbbn"/><path class="xpf2_xgfh"/><path class="tn9kx2b8b"/><path class="sq52lmb_w"/><path class="peq2gqbtb"/><path class="vfg_izpic"/><path class="nu7020b6x"/><path class="otd-evm2t"/><path class="tob-0lb3i"/><path class="dj8c-odet"/><path class="op68_vbgu"/><path class="i-j94t26b"/><path class="cj7j7_7ru"/><path class="mq34wz7nt"/><path class="y6ljy5bvz"/><path class="le9xd_5jm"/><path class="g99nayb9g"/><path class="gq3mdgbht"/><path class="yy1ceeb9n"/><path class="s26_2ibeu"/><path class="kifo2ltpy"/><path class="ifw3wybuw"/><path class="faa78wx_n"/><path class="o2ud-qbzu"/><path class="td_6g3bsa"/><path class="pe9cmimds"/><path class="zb2cpksco"/><path class="eb6t7x1pf"/><path class="v061jg11f"/><path class="q_djwt-ov"/><path class="sjq3lbc_n"/><path class="hnhw9_3tj"/><path class="hv7u_ac6q"/><path class="un6_qz8py"/><path class="q0138eblq"/><path class="vj1w_ibfh"/><path class="u88fc7bkn"/><path class="ctwnnpb2m"/><path class="u1gld9dow"/><path class="usf5fcbjs"/><path class="ucmhn_f3r"/><path class="x_90pw7gj"/><path class="ibyj1dkfo"/><path class="nevhe-e7g"/><path class="r0q4ehbvp"/><path class="w472smdbu"/><path class="pyhyip-0o"/><path class="aj4k49b_x"/><path class="ptti7-bpw"/><path class="qeox7ubzh"/><path class="xykb855qe"/><path class="w-5x4o20i"/><path class="r3nbu3iax"/><path class="hutziioqz"/><path class="mgk0ry_mn"/><path class="jnqmbnjvw"/><path class="mbkg-7yeo"/><path class="ghwdxob8d"/><path class="prpsz7tab"/><path class="vysvay14y"/><path class="fw70_vchw"/><path class="fqe8t2bxp"/><path class="h8a-m4bzq"/><path class="erhbitd8d"/><path class="a2k3exnil"/><path class="it6c1lbwt"/><path class="iu1-6_blh"/><path class="d8m-1eriu"/><path class="xohbhibbk"/><path class="kpth1i2zv"/><path class="vnve8mbft"/><path class="wqwr0bbfy"/><path class="wwlgwdbxi"/><path class="kf655wbib"/><path class="lhrlv-b7w"/><path class="qddsuob9s"/><path class="v-ssyfzbe"/><path class="ae6-csbai"/><path class="w5wl4ym6f"/><path class="l0ceprb4i"/><path class="e6enb8b5j"/><path class="ia5d3biyv"/><path class="i3mhi1bns"/><path class="u--4oqeca"/><path class="msxo78bet"/><path class="uz_7ftb8h"/><path class="pnzcgvbyb"/><path class="okh6exiib"/><path class="vo-4lsbss"/><path class="g6xgp0bjn"/><path class="yp2956-hi"/><path class="vwr5zwbwc"/><path class="yo6lywege"/><path class="q5bi8n_ha"/><path class="sb9x9fblt"/><path class="e53zpkb2r"/><path class="padw24b0o"/><path class="wi5m5fb6h"/><path class="gxrwh6bdd"/><path class="vrtfp4b0t"/><path class="tc851ggkp"/><path class="jpk8gub8n"/><path class="t7txer11l"/><path class="sur5ow26r"/><path class="kka3jqjwl"/><path class="rvc8tjdsp"/><path class="wui37ebut"/><path class="syktxr09l"/><path class="bm3t5qbbm"/><path class="kjkdyfbfd"/><path class="znvnkpwkv"/><path class="jj7h9zbdh"/><path class="r3yl35uli"/><path class="xeeve54gz"/><path class="c-9ltji_a"/><path class="spuwnjb_k"/><path class="psbvhx0ix"/><path class="eekgsfbor"/><path class="gvj33l0ol"/><path class="xx5x1-bcj"/><path class="mq4qllbov"/><path class="samr2jbmr"/><path class="cp6prge7r"/><path class="j3difobyg"/><path class="sxiecgbxr"/><path class="ed_jjs00e"/><path class="f7lxv_oyk"/><path class="th_s67bzp"/><path class="h70n50bdl"/><path class="pz25ukgdq"/><path class="bx9ib-8rk"/><path class="m-3147awi"/><path class="qjxp2yfxx"/><path class="jkqhvbo4m"/><path class="z2dd-kbzx"/><path class="nz5g-ccor"/><path class="sc7artbdi"/><path class="d1qwjhbea"/><path class="qqvngyzey"/><path class="dc190ev2h"/><path class="fyb92nhfl"/><path class="atyotlb-g"/><path class="muy_x4xkb"/><path class="a7xwohdrz"/><path class="ifdj3qmgk"/><path class="wq8gtkbwi"/><path class="j9uweybxe"/><path class="yn_l2fb-k"/><path class="i-sumibei"/><path class="etc6r0d3d"/><path class="wuxnd1bpv"/><path class="culn5hc0n"/><path class="mgvfkf_wb"/><path class="jo7woacbz"/><path class="l4ff8jb9w"/><path class="mkl7bwbkk"/><path class="v9o5qobfe"/><path class="z9s3mpx1c"/><path class="c2i239bff"/><path class="k2itl2buh"/><path class="z2_vn2pfe"/><path class="us6at4f1w"/><path class="i4atue2ux"/><path class="x-u73lnda"/><path class="dtmgbhw-m"/><path class="k8mwurbzf"/><path class="x-gx8nn5g"/><path class="hatic1biu"/><path class="sd3sbxufp"/><path class="r3ccu7baf"/><path class="mgkmfzv7o"/><path class="gjk6h8bch"/><path class="yz1im81ue"/><path class="q252yih8i"/><path class="zm82g-wxt"/><path class="rgv9wbcbb"/><path class="f-hfcmbwh"/><path class="zf2aq6b6e"/><path class="ca4g-61zh"/><path class="n091g2bfd"/><path class="x40z9yb-z"/><path class="f0ns6deey"/><path class="nvklpcmvi"/><path class="r4b7px2gt"/><path class="str-odbcj"/><path class="nvdz45bbx"/><path class="zpix7vpwg"/><path class="v466zjb5b"/><path class="df1cq-rzw"/><path class="upc9jdcxy"/><path class="mwbgcwb9k"/><path class="lnwury9wy"/><path class="fp09i6q_m"/><path class="bscgvhamu"/><path class="tohje-f2n"/><path class="horu612dl"/><path class="o88xnet_d"/><path class="d_g98ybmb"/><path class="ojcvv252j"/><path class="uvpd8wn7c"/><path class="cvbk8u71e"/><path class="grfmqqx4g"/><path class="isu0sbcyd"/><path class="qqzum9b0a"/><path class="dy14d0czc"/><path class="wdq3_zv-b"/><path class="lkfcg4b_g"/><path class="q1idjo50h"/><path class="n8pb3te_s"/><path class="hokuq-b7m"/><path class="tbstdss9q"/><path class="k7gxh6_wl"/><path class="bsrgi_buw"/><path class="x67fquzrg"/><path class="icludy12a"/><path class="o-akqlb5i"/><path class="e4aeisb6e"/><path class="flai8_aef"/><path class="ttk_0olej"/><path class="vfyrixlap"/><path class="mvkabvb0v"/><path class="vqel62b9b"/><path class="t_0v-1_am"/><path class="k47yssb0y"/><path class="veq0awb_v"/><path class="icrc-x5mo"/><path class="y8lu7k7rs"/><path class="v5hbbzbna"/><path class="c8zut-ffm"/><path class="ni018-bap"/><path class="c3xi2cb4n"/><path class="m2dlb1bmx"/><path class="u03s3803d"/><path class="yj2fvbcmm"/><path class="b7f72jj9f"/><path class="j7w8k7b2i"/><path class="x0xykcc_s"/><path class="h4alrqb7g"/><path class="fddoedcut"/><path class="rcaycihbe"/><path class="jelxq1bnu"/><path class="n0ozep0ee"/><path class="xwd3job7w"/><path class="v96tr1b6y"/><path class="cgphdtbms"/><path class="j4puxouiu"/><path class="zx5wx7b2i"/><path class="xce_xy08e"/><path class="t_fmi_bty"/><path class="r4i-15gws"/><path class="ts0mp9chz"/><path class="in6z_gb0g"/><path class="zpby_1bxe"/><path class="u8s1yvlia"/><path class="qj27q9bse"/><path class="f-316br4p"/><path class="x01aszb4d"/><path class="u3ue6ub8l"/><path class="ifpdnnbbr"/><path class="vddlq7hyi"/><path class="pr_d8mjuf"/><path class="tdu_zibdm"/><path class="mks4ih3yl"/><path class="jv377sfdr"/><path class="rploq3lcx"/><path class="hvwkr_0wa"/><path class="s5alv_wbd"/><path class="bjye9vvfl"/><path class="hz4bctb8n"/><path class="hzdadbbuw"/><path class="j3944qa7t"/><path class="vwodytnru"/><path class="v7r-uztld"/><path class="as80s9g9l"/><path class="yczkv-35y"/><path class="ile721k_t"/><path class="l3lpogity"/><path class="yq-pnv5aj"/><path class="fqsc17byp"/><path class="m76duqboy"/><path class="vlqrb8vxj"/><path class="unv0ab3ud"/><path class="wfy7or33k"/><path class="mjjd7vjxg"/><path class="biidwwb5q"/><path class="ebhwnw5-h"/><path class="pyell0blu"/><path class="safi0abgl"/><path class="cc8arob7u"/><path class="kstea_2aq"/><path class="yqa1bx25r"/><path class="mi8h6g5go"/><path class="tfm_cfpue"/><path class="irhc8vbvy"/><path class="rwrpwmicm"/><path class="lak5y2bfi"/><path class="d28hnmb9w"/><path class="bb2eum-8c"/><path class="ay71ay7lx"/><path class="ngnbctb1d"/><path class="p5ddo5bpd"/><path class="mdndqhbje"/><path class="lxjypg22p"/><path class="uq-57ec8i"/><path class="xa1352j4v"/><path class="p966grlob"/><path class="kt3wwjold"/><path class="wtt98llps"/><path class="w0ctqibfl"/><path class="eruuv-bxr"/><path class="y3d_2v9fy"/><path class="kes7w7bxk"/><path class="nkd-enorl"/><path class="kwwi0cbch"/><path class="bgj44ls8s"/><path class="x481yf02g"/><path class="f4gnx0ecw"/><path class="on6ecvumw"/><path class="a_-ug2bsa"/><path class="etmvwbbkl"/><path class="k-06hlb7i"/><path class="i67m2qblm"/><path class="eofz0nqgd"/><path class="wfgsj28zs"/><path class="o-lw9cb2n"/><path class="b8pluxm6k"/><path class="dk7l-ubxt"/><path class="o4hcnccjv"/><path class="vf-1qobyc"/><path class="be-e1f07n"/><path class="dvxnesbpc"/><path class="t9_02clmd"/><path class="gy9pai8fl"/><path class="qe63u6z3l"/><path class="vkcg_fbaw"/><path class="eqm5w7-es"/><path class="cy99v7bvm"/><path class="sp_h5obyp"/><path class="uq7twrbez"/><path class="b0ymgmbwl"/><path class="rybtm8bsh"/><path class="ma_ioz80o"/><path class="g3lsaob2o"/><path class="gb31lvb2o"/><path class="eiizq8bhx"/><path class="t38y6qq6w"/><path class="v9a9tvbgc"/><path class="n6r_3mbte"/><path class="skuluetnl"/><path class="qgajtfbba"/><path class="qra2yubpk"/><path class="ymc5xzboc"/><path class="knyq49rfj"/><path class="rxhktixel"/><path class="njyo8ubau"/><path class="cezrjcu2y"/><path class="q5fv3ctxb"/><path class="sh-qmvb-q"/><path class="v1s9tnb0t"/><path class="nx_lvccvs"/><path class="r9lc-qbjt"/><path class="f28luccdr"/><path class="a_em3wb6s"/><path class="q261-1hxw"/><path class="ymv5xz-gh"/><path class="tdwihkb8i"/><path class="l6_dtzbkd"/><path class="dun2ktbfv"/><path class="rqd8icbar"/><path class="s32kmhs8b"/><path class="ns1nh9b0s"/><path class="afg1g1bzj"/><path class="gk_j_7bav"/><path class="o5doqv04g"/><path class="d7jafuhiu"/><path class="u19m_9b5e"/><path class="s21rlgd8t"/><path class="moabe_b3d"/><path class="i_72aubmq"/><path class="we7xwjknp"/><path class="aktcqvclq"/><path class="otw36q9fl"/><path class="g65j5jh0l"/><path class="r-mld_woi"/><path class="u0fw1dbtv"/><path class="mxq_d9bhu"/><path class="oa7ygmbjs"/><path class="jmc4y4bhf"/><path class="zduxq3bor"/><path class="x--3r0bog"/><path class="fjvo1ubvf"/><path class="mvp8fm3bd"/><path class="npz9rgbyy"/><path class="kzr68za9e"/><path class="eh83h76xj"/><path class="e6irzrkcu"/><path class="htplotx4d"/><path class="jahvrhbxh"/><path class="dl9u4cb0z"/><path class="w3lcpt_ax"/><path class="mpf7-fb_x"/><path class="de96vycwy"/><path class="fzhicm_rr"/><path class="en842-9uv"/><path class="aw06yfbgr"/><path class="ckzxyac0f"/><path class="ouzg2xzry"/><path class="e1yu0gevo"/><path class="qfh5dvbpx"/><path class="sckp32sbj"/><path class="l5xfmnpqd"/><path class="uaom-pcfw"/><path class="vdm2tbc_d"/><path class="tpnx04bpe"/><path class="voli3j76f"/><path class="y4cfxjbpy"/><path class="mukslstlk"/><path class="u9zk21amd"/><path class="itrsje3kw"/><path class="c5wrqx26b"/><path class="nglskcakn"/><path class="lpx_d3nui"/><path class="my07aitic"/><path class="y_5b-83es"/><path class="pf8gg5yfy"/><path class="o_94tibex"/><path class="m1v7qqbuk"/><path class="ks0crhb8y"/><path class="symwg_bjg"/><path class="ad3zzkb4i"/><path class="r9304nx3q"/><path class="xh5-vabqc"/><path class="h440rypqo"/><path class="sjh2di6kv"/><path class="wr5hgxb5c"/><path class="rcc-78b7n"/><path class="amb84o86t"/><path class="nfptjcd8k"/><path class="m_p637m0y"/><path class="m7nqx7ipr"/><path class="jt9ecobos"/><path class="zkm1321xu"/><path class="sxnrdhadd"/><path class="dodpsl1pw"/><path class="aw6soi4zk"/><path class="y2ygvnzyu"/><path class="pjlu02ann"/><path class="ryuc65bvv"/><path class="ea6lv4buh"/><path class="t222kqbvo"/><path class="mxql2jvbp"/><path class="wfr7youms"/><path class="fof2cdbnk"/><path class="aijsys7cg"/><path class="mru_t7wnh"/><path class="hpb1be6_i"/><path class="stx3h-buo"/><path class="g1-hd2b0c"/><path class="i62xrxpsy"/><path class="blm7npxzw"/><path class="ielgsdcjn"/><path class="zqg8bmbox"/><path class="zate2svto"/><path class="k8vj8bcyg"/><path class="m3af7lbjg"/><path class="pb1vly6xv"/><path class="iaskijbsa"/><path class="j3yhwtbkh"/><path class="su1iu2b8n"/><path class="vx0nyxbfp"/><path class="gnsw1m43m"/><path class="ou0pzpb3e"/><path class="ng9-kdbak"/><path class="h9zbesbtm"/><path class="t2vnkpc6g"/><path class="j11e1obnr"/><path class="br7kfabkp"/><path class="i3rnbko1z"/><path class="q-e2zsalv"/><path class="lmt54bc4f"/><path class="k3q570bsz"/><path class="orqn45bwq"/><path class="nsgclnb3x"/><path class="coyuwh1dg"/><path class="r4lqpzzyi"/><path class="fjfwpipqr"/><path class="m_4o91b6w"/><path class="urpxzt-zi"/><path class="k16xzcb-d"/><path class="iivsp0b8i"/><path class="ov4lw44wx"/><path class="vkwx-g_ja"/><path class="y1-thkbva"/><path class="bfu-50e7k"/><path class="h46no5bxt"/><path class="c9k0fhbzc"/><path class="lgjxcq8bl"/><path class="f47w_hhgu"/><path class="twxc8ofqk"/><path class="zoa_ld_nw"/><path class="ve7_r0rgv"/><path class="ffi8nxble"/><path class="z05owvb7j"/><path class="yqgdz6rha"/><path class="i2jex4xye"/><path class="a1ln-nbrc"/><path class="kc18uobsh"/><path class="b_8nlgqgn"/><path class="bx-3hbb7u"/><path class="z1a46qbbv"/><path class="raw1rvb5y"/><path class="h06ou8bqo"/><path class="g7wvivbgl"/><path class="lyxai9b0l"/><path class="h5ty81bqw"/><path class="e8lum9u2d"/><path class="tkat80paf"/><path class="a4lxqp41c"/><path class="kp29nr3uq"/><path class="gvmv2urfu"/><path class="h8o4hjb1m"/><path class="p7vyrabnr"/><path class="kupb_mb3x"/><path class="w2xbo-boh"/><path class="ufwn_pvsg"/><path class="x-tmulyom"/><path class="bnufn6bgy"/><path class="ukrdxwrir"/><path class="btsb2fbxq"/><path class="y__hw3baa"/><path class="w-yms8cxe"/><path class="gaa9nacil"/><path class="mvq83dbxm"/><path class="hgwfo-_pf"/><path class="ia2ke2bko"/><path class="zk7gnbp7q"/><path class="w5uy2hbpa"/><path class="yd_4zobrk"/><path class="ds7elwmqm"/><path class="gwwoq1yqg"/><path class="ovf32dntx"/><path class="nm0g2rg9a"/><path class="rb7tty0ry"/><path class="cxnte9bla"/><path class="r40jhmihb"/><path class="a01se4b9k"/><path class="q0w7b5d3m"/><path class="j_vob_bzh"/><path class="lt58xpypt"/><path class="fhg7shb9r"/><path class="u4oicrbot"/><path class="eyytpbbfx"/><path class="zhg01mbes"/><path class="hm10g474x"/><path class="he2jdebdo"/><path class="x4pipacvd"/><path class="ovoo0dsvf"/><path class="wpm170fmc"/><path class="zzjrivv-v"/><path class="ktblyu61g"/><path class="e4hba-b1c"/><path class="lmcbacb2d"/><path class="tkysypb-w"/><path class="k-obc279v"/><path class="mmtom2bth"/><path class="n967jbbfx"/><path class="n3-jch-ij"/><path class="g3pm8-bnx"/><path class="qtpk3tbyc"/><path class="b7x4lkbqm"/><path class="q38picikp"/><path class="xv264-b8b"/><path class="i9sorvbmz"/><path class="vnd2sdtod"/><path class="z4-pqccjm"/><path class="s3bvj-78i"/><path class="yllixzb-a"/><path class="zemtv85jy"/><path class="bv942obrp"/><path class="i0o7trb_w"/><path class="mf97ien2z"/><path class="q-uhp2b6t"/><path class="exhjhhzme"/><path class="j9-3m4vna"/><path class="umh_d_9-r"/><path class="m9xdjdbcf"/><path class="enk_88uzw"/><path class="g76ft_b5e"/><path class="i65t8tgfa"/><path class="qd-g32b4d"/><path class="gr6xlybih"/><path class="gn19ybx3u"/><path class="qw10oinbt"/><path class="byza8v8jl"/><path class="ij5026bag"/><path class="xsgs0v-9q"/><path class="onlxp2pne"/><path class="ll0ss1b1o"/><path class="a1w5651_l"/><path class="rdeo07b2x"/><path class="wknbcbbbu"/><path class="oh1o3ib_e"/><path class="tjec-p6xw"/><path class="djuocebiz"/><path class="lvsd224zr"/><path class="i0uabmbgy"/><path class="pl5bzacbp"/><path class="vo9lhf-cz"/><path class="x3_6ohb1j"/><path class="grqv35bze"/><path class="ke9xteb9l"/><path class="bfri8mbre"/><path class="fky-xcbay"/><path class="tirutlbtw"/><path class="a3y9dcx0b"/><path class="ruqcs6fch"/><path class="i-km4dbkh"/><path class="j3kb3tsaz"/><path class="z2dq_3tix"/><path class="macvaw2-f"/><path class="gujk4p89k"/><path class="k0nitkbad"/><path class="ugm1u2tlk"/><path class="p-gr18b6r"/><path class="tsi9skbsu"/><path class="rmcvilp0x"/><path class="zuzq3cb1h"/><path class="h7nox2m4i"/><path class="mk7c0jbrp"/><path class="dy64reb_s"/><path class="igsu42p2n"/><path class="tj8_3sepc"/><path class="y-dxpzibo"/><path class="c95_92bwx"/><path class="fh0-bd_ru"/><path class="u9z9t8-td"/><path class="uc-4ucc-f"/><path class="oiste8b4s"/><path class="c2y9wgble"/><path class="qicm6mbsy"/><path class="pc-perbww"/><path class="v9svuemiw"/><path class="id34y3b6h"/><path class="yc3_iabnl"/><path class="a1ojgbc7h"/><path class="o_i9dpbre"/><path class="tdtnysb5t"/><path class="z_u_0xx3i"/><path class="r6k_kqb9c"/><path class="atxm8btdf"/><path class="py12ucbpo"/><path class="m578zbbgt"/><path class="haimd5t8s"/><path class="o2fbiibrg"/><path class="uikr5pb2j"/><path class="p2lsb6g2g"/><path class="b1jh96bna"/><path class="g3jido9wu"/><path class="y1r9v9twl"/><path class="omz95xb2j"/><path class="fz3y7pece"/><path class="g3fi1mbmq"/><path class="foqx_8wia"/><path class="gv0ll5bld"/><path class="lkrn7vrqw"/><path class="jnex5xbjs"/><path class="qrbfaisod"/><path class="wzue76btq"/><path class="wh8wlgbvx"/><path class="hwljoccox"/><path class="sggnlw5tm"/><path class="vavn1-qhe"/><path class="awmq6wn4p"/><path class="iikzhjueq"/><path class="ds2_vrb0i"/><path class="w5w07bb_c"/><path class="mdwf4ac2q"/><path class="riop4yz2m"/><path class="yensxztfi"/><path class="eyegp5b8o"/><path class="wk-4q6blg"/><path class="n85qf5bfk"/><path class="zb-xjbbix"/><path class="mubyie-rf"/><path class="kkqbytb4c"/><path class="k0v2atbcr"/><path class="eziu4cy4f"/><path class="e2u-we6nq"/><path class="u851chb8d"/><path class="mqu813ble"/><path class="h4aakoztt"/><path class="friyo6nyr"/><path class="epr-958js"/><path class="map-ptb9v"/><path class="r0mwcbb5z"/><path class="gk611sbie"/><path class="teha-84an"/><path class="ds9b5qrxv"/><path class="b5lyrxmye"/><path class="euv4itbwb"/><path class="zlp6tlnde"/><path class="olda0rb5m"/><path class="x49989bew"/><path class="eb0vc1h9y"/><path class="tpjz_ogvu"/><path class="q-sz056cx"/><path class="rzpk7mbmp"/><path class="k_4dh1zwx"/><path class="wcqd_qhbj"/><path class="cwkj5sghy"/><path class="mrzrfzgzm"/><path class="imr8hubvl"/><path class="lzmcmcb6c"/><path class="ks1au7bay"/><path class="w4011ucbw"/><path class="mt9rxlbck"/><path class="ulxh9f_mi"/><path class="kmozguqzg"/><path class="hq62elbuk"/><path class="kijj8zbfa"/><path class="b8sqt561y"/><path class="bxrnhubnw"/><path class="q3-gvac9l"/><path class="i9aw6ebpt"/><path class="m65__c_zs"/><path class="u-k7tlbzl"/><path class="w8ll72bso"/><path class="kxxjzwpsu"/><path class="n83lpq-wc"/><path class="uwjzk7pyc"/><path class="lxq7iwrzp"/><path class="hhdks9bia"/><path class="h2pdxvbuy"/><path class="ntdhkk8wk"/><path class="n1wzrtbzw"/><path class="z1f8lkavt"/><path class="h7x4hbc1k"/><path class="cqw4c2zti"/><path class="x-b_aqbjr"/><path class="z24zj6y8u"/><path class="jh7wahbxf"/><path class="eglsolbjn"/><path class="gimp8vbbo"/><path class="gjsksab7w"/><path class="x3cyd6odr"/><path class="gq-7srb-y"/><path class="s2lpufb4h"/><path class="ix9su_bto"/><path class="gssw16brj"/><path class="ncdfyrnvz"/><path class="cyerltstq"/><path class="kmpbx690f"/><path class="i884k43-d"/><path class="u_wfpdo4j"/><path class="l7j212w-o"/><path class="c731pnb9c"/><path class="qcyhf7h6n"/><path class="pw-6_gbsp"/><path class="a1k46jbiv"/><path class="v0j_1dbpa"/><path class="bnftygnmt"/><path class="xyjnm03zl"/><path class="al404vmbf"/><path class="gm6l9nlyo"/><path class="te8mlqh8k"/><path class="yxoparbae"/><path class="eyf_j5brr"/><path class="o288qbgov"/><path class="gx5dp-72n"/><path class="fnc_6qbni"/><path class="htirczbbm"/><path class="a12iiab4q"/><path class="hfo6eu_3o"/><path class="p1bal_bbd"/><path class="abtf6sbig"/><path class="ni2uprbsg"/><path class="j3nxc8q_q"/><path class="gyerdqsmb"/><path class="qcrv5ab0p"/><path class="l132kvb8t"/><path class="ln5lo9cqx"/><path class="r7l2f5bmt"/><path class="j9lvhxlif"/><path class="gs7bppdlb"/><path class="pg5kddtul"/><path class="iryuz0ppw"/><path class="kky7labnb"/><path class="qhvbtqgvd"/><path class="v-thf5b_p"/><path class="hfxhxjt2x"/><path class="g-n1gdc4p"/><path class="fbg4hacal"/><path class="ixj99obhy"/><path class="o3a53hbkq"/><path class="b6p646ioz"/><path class="qkht-5bnh"/><path class="wqoyhfygr"/><path class="zkli6v3_s"/><path class="d--1u0b4k"/><path class="s7ly94b4x"/><path class="s50r52m7o"/><path class="emzqz_bow"/><path class="rkchkobai"/><path class="vav2s_f-h"/><path class="w8ydt5b5o"/><path class="inb12lbet"/><path class="rfl3o5g1b"/><path class="rfcm5jybp"/><path class="crvxk7bjy"/><path class="hpl38xb2m"/><path class="bu2wkjiiv"/><path class="dato3cb9k"/><path class="dhfhj7bhh"/><path class="c6t1aqujg"/><path class="u2vhfab-g"/><path class="lws-3sbne"/><path class="b6xtgp6oo"/><path class="ak3wg6bdz"/><path class="ziy3d2bsw"/><path class="zvb8bw-yl"/><path class="on7sz0b9f"/><path class="we50plbap"/><path class="fs1oiacpj"/><path class="qny86ir5k"/><path class="l879lzbep"/><path class="s1lwflb-h"/><path class="ekn_ecchu"/><path class="b9sc-7bza"/><path class="oaq1zpv4q"/><path class="gmfzb3bua"/><path class="jxh4fdbnr"/><path class="aocukkvxj"/><path class="ybz502bbt"/><path class="na0mso9_q"/><path class="uurp0wn-z"/><path class="dbnkg6b8r"/><path class="q1c8hq8jd"/><path class="d6tnt27co"/><path class="s04vw6bcv"/><path class="a2z7mmbth"/><path class="wpyurgb3x"/><path class="l5m9kcb_m"/><path class="o5g0jg_4g"/><path class="oifqxubgf"/><path class="j3bd5rbfi"/><path class="dz_i0acfz"/><path class="or7l-9b3o"/><path class="b2cil-bdn"/><path class="d9hpr3boi"/><path class="ttmrjwu8v"/><path class="vg5y1xbcf"/><path class="vfzyusj7u"/><path class="sybn4vjed"/><path class="ux8y0sbro"/><path class="ssh14fj4u"/><path class="i2sd7-_ws"/><path class="ugs-vcbvw"/><path class="qayy6ab2u"/><path class="tl41bwbhx"/><path class="e-id8hbja"/><path class="w-jl0-b_p"/><path class="gwxdpcorh"/><path class="evqin1wot"/><path class="b_o4s8bxc"/><path class="ihpn6acgx"/><path class="iri-78_hh"/><path class="k_ov9rx9j"/><path class="gcjoq_12a"/><path class="rj6gvpbdx"/><path class="ayejqmkcb"/><path class="u7_c0gb2c"/><path class="r6_hhzi1e"/><path class="f0ahkvb0d"/><path class="jhwlxgbxt"/><path class="q94aosxaf"/><path class="u30y38bgb"/><path class="xv6xwhw7f"/><path class="ahn4adcsh"/><path class="ykhmlvvmz"/><path class="c_swqy-5h"/><path class="to6uzwbyx"/><path class="f7l1qobbb"/><path class="jo7rsdipk"/><path class="j30azmbmw"/><path class="uqsy2mb_u"/><path class="riabt9bnk"/><path class="agrm-uu5c"/><path class="lfvl22b7i"/><path class="lyh4i3h_w"/><path class="x0zccvbde"/><path class="i9okw4b6a"/><path class="mtgw3tbnn"/><path class="xwk6gupxh"/><path class="ck532ybds"/><path class="zx--lgb4r"/><path class="u9muyjsmx"/><path class="a1-bh54iv"/><path class="jd_obebwf"/><path class="kt6hmtbyq"/><path class="xpv-b-b0z"/><path class="r89xtz-ui"/><path class="p7taz0bif"/><path class="zv_u4nbbo"/><path class="dlcjw3bbj"/><path class="p_1zeyb0g"/><path class="rg4yb7bup"/><path class="ygra0bbxi"/><path class="p39on-jhb"/><path class="amzwb_sld"/><path class="ctupxn4ws"/><path class="xo9zdluql"/><path class="a6j2s-b_w"/><path class="u51sudl_h"/><path class="i2eiesfru"/><path class="fmc2me2tm"/><path class="xp7jknayi"/><path class="dd6a4lp5b"/><path class="z747wh5yw"/><path class="r_jee-j5u"/><path class="yq2c24-1c"/><path class="iazgcchhs"/><path class="j-upue-0i"/><path class="nst8uibhv"/><path class="emchikbgb"/><path class="safjg7bsh"/><path class="xz1iec_nj"/><path class="lzxxctb3i"/><path class="ch2xcs5-w"/><path class="weu7i0bss"/><path class="nhd8tjbfe"/><path class="pr4gmnbki"/><path class="a7v0eov0t"/><path class="pk80tou1t"/><path class="bgh1lnbdl"/><path class="i73mgvzrz"/><path class="w-6vtijmv"/><path class="lkew52uxq"/><path class="v5kfh2b_o"/><path class="z7tpto08m"/><path class="qiym7ob0x"/><path class="l4jk2ib8b"/><path class="unw38ozkn"/><path class="gp0_r8dmb"/><path class="fdauw0b_h"/><path class="vnap1qhzd"/><path class="m3sffcl7i"/><path class="zqf76qghn"/><path class="d7sg32hsr"/><path class="lvy_18cmg"/><path class="osxsrlwcs"/><path class="v47mbxqgr"/><path class="khx0g4b6m"/><path class="q56yht9gh"/><path class="dvnqcedop"/><path class="e3m3iubji"/><path class="lghb61a1x"/><path class="fdxt4xb9g"/><path class="yilhdlwzo"/><path class="yult2f2-h"/><path class="blgk_67rz"/><path class="ss-gbqfqh"/><path class="qrgcnbb0s"/><path class="tqbhkviwv"/><path class="fa8t-ozgp"/><path class="nlenm-7px"/><path class="a9xbhvely"/><path class="sibhawb8r"/><path class="speca1_kn"/><path class="lu34ltb7x"/><path class="qvdzaybqb"/><path class="l-unu_b3n"/><path class="i_ruwhbix"/><path class="e_gqfla8k"/><path class="dfmplcbqq"/><path class="r5p5_ybxq"/><path class="l5ky36byh"/><path class="qz9_3tx-o"/><path class="nq_ja3bse"/><path class="k884mzsnr"/><path class="v3t9lgb0p"/><path class="ucrzxisnn"/><path class="mleuy-ulc"/><path class="yts446a2o"/><path class="t547dcbzq"/><path class="nd2_lcbla"/><path class="cp1slsbzt"/><path class="zbfrr7aec"/><path class="l47kf0bqh"/><path class="gywp1xbvo"/><path class="cg6az_d6k"/><path class="c9s-0ibmw"/><path class="vp185jbvu"/><path class="mxw19vbzc"/><path class="ruibl3lkx"/><path class="qfpmy0_xt"/><path class="c5o004bnx"/><path class="n58o3db7a"/><path class="dez406hmo"/><path class="js7gvtbbi"/><path class="ncnp_0bys"/><path class="qhkiucigd"/><path class="aov9vpb0h"/><path class="woe55bbiv"/><path class="rwj-y7b0z"/><path class="qf_dcn-rf"/><path class="y0nzxbbil"/><path class="j1hu8o2lc"/><path class="m3b1kba6t"/><path class="zpkavphrz"/><path class="mobzxlbwf"/><path class="qsf8wnbce"/><path class="ud5ul0lud"/><path class="bm73-154u"/><path class="a9de2j0sf"/><path class="wxy3wuarw"/><path class="ub2l8cbka"/><path class="xmis3gv3f"/><path class="pzliixduf"/><path class="jdduk8u6m"/><path class="ax_u39b8z"/><path class="gzh7pkm9s"/><path class="nmi_0-b0c"/><path class="cqhy3bcdh"/><path class="dah5h4b-a"/><path class="nx6p4-wea"/><path class="gp_x519ah"/><path class="dysr8sg7u"/><path class="dgjcvkbbp"/><path class="pb-firbwu"/><path class="uyr66hbfk"/><path class="yekqd6abk"/><path class="k0fb3jtea"/><path class="gei513b2d"/><path class="edc06pb0q"/><path class="yflbk5ehz"/><path class="oi0q002ws"/><path class="t6x1zcboq"/><path class="i3twambtg"/><path class="jjzi_jbst"/><path class="yzk8_lbqr"/><path class="u0v_zqbxm"/><path class="yiv9lkbuy"/><path class="w66f4abwa"/><path class="a5cew9jdo"/><path class="johg6ebij"/><path class="jff4oebhm"/><path class="z-g1x0bbz"/><path class="o8pnmzc_g"/><path class="nko_f774w"/><path class="qgcrkxbpd"/><path class="yw3r8q3xb"/><path class="lwgbbs75i"/><path class="eglq965de"/><path class="tu6wqug9s"/><path class="t6i9drbja"/><path class="zd1sbkb-g"/><path class="ikx7ute8q"/><path class="hiy2rvbhf"/><path class="bwiadsb3r"/><path class="m--rs7b1p"/><path class="mbm0g9-ti"/><path class="b0qa6sq6s"/><path class="byfpkc9kl"/><path class="q0cepvskt"/><path class="ieln3ccbs"/><path class="yuhwapbri"/><path class="w0y2r5r1i"/><path class="vs100fbfq"/><path class="tkomizblj"/><path class="od5godb0u"/><path class="lhue_ob1h"/><path class="ckmvh9m8l"/><path class="f0r-9736a"/><path class="mxejnf01m"/><path class="txobbdcfs"/><path class="lw317kbii"/><path class="ctmlhzb9i"/><path class="s2t1cgvyy"/><path class="gutp4vbts"/><path class="dvnscbb_h"/><path class="cwh728cwp"/><path class="gz-9s-bnc"/><path class="y_7mevbzp"/><path class="u9ye6c-8k"/><path class="y8io6w_cv"/><path class="xa0sjdb1k"/><path class="cwx0f-0hq"/><path class="ip5rm4c0i"/><path class="yon1occ-i"/><path class="xweqgj0rx"/><path class="hejiek-sa"/><path class="ewn154gcw"/><path class="bl2b9gmxf"/><path class="d7ozqhlnx"/><path class="dz8f39bza"/><path class="ba3b8rdos"/><path class="szwwqnfgb"/><path class="mn7b9xgso"/><path class="z7uojdfzl"/><path class="j_zc74ber"/><path class="l6yhnkilm"/><path class="ibssz7uzd"/><path class="igflrcb2f"/><path class="qxswdvbrz"/><path class="hh7n6oall"/><path class="i40292bnb"/><path class="dwd7s3-8l"/><path class="yxq938bts"/><path class="r1j2q6beh"/><path class="jd7ril6oo"/><path class="fih8j-bom"/><path class="iccvrjogu"/><path class="eqkt5bc9w"/><path class="cmbkg9bxw"/><path class="mx7e_h_ry"/><path class="tpdz3fojl"/><path class="jg-mxkb4x"/><path class="cmwuzsbwd"/><path class="ejpj2yz_u"/><path class="tv9hgcz9e"/><path class="yjy09yb0d"/><path class="rwq0jdbmj"/><path class="tt2a5sa2s"/><path class="kc-o46bdq"/><path class="cx95vubdg"/><path class="o2d6wiwop"/><path class="nrqhceo8v"/><path class="jjhfrcwze"/><path class="kxbngpb1b"/><path class="yhfw7obfr"/><path class="gqoo_1bjy"/><path class="yo07teb8d"/><path class="s2wl_sn_x"/><path class="g2ik-7t8r"/><path class="ml1f46bfx"/><path class="nnqpln1mk"/><path class="vtiso1bxy"/><path class="rfion-bdh"/><path class="w_31u2bwf"/><path class="ck9o35t5i"/><path class="ou-fh34uv"/><path class="t6owtpb0h"/><path class="nvp4jobuj"/><path class="dehnn1bnh"/><path class="ajxv5d55a"/><path class="mg1x_tb8y"/><path class="fyatlbcrl"/><path class="yx-emhbim"/><path class="ex5jjt2yk"/><path class="ss-fttp4d"/><path class="xl6i_ye-n"/><path class="xkgulpcjl"/><path class="elw39pb5o"/><path class="e2ahsdblx"/><path class="f2jq5l4aa"/><path class="punrmbcea"/><path class="tt75hvbqh"/><path class="eqx5nrbuf"/><path class="z14sautfh"/><path class="bso90ebai"/><path class="f3hbtgbhv"/><path class="encanjb5y"/><path class="r5f3l8b4w"/><path class="psdmzfbfs"/><path class="hb9dgzuaj"/><path class="ybkxt1_rw"/><path class="c2bx0-b-x"/><path class="ii32fzbhj"/><path class="i7__5b-oy"/><path class="sjs5xkblr"/><path class="aa1-ww6qc"/><path class="a0m5r9b7f"/><path class="m6j-hebbc"/><path class="gzuza0i7j"/><path class="o-xtlbcel"/><path class="tixruff7z"/><path class="t9z77ibtp"/><path class="hmfk-k7-m"/><path class="y5w_vbyqf"/><path class="vkadm8btw"/><path class="pla0plqyn"/><path class="lq1v43lui"/><path class="gd3u26b_u"/><path class="ln27vkurp"/><path class="qjzlnobxw"/><path class="x5me6db7m"/><path class="irae4fz9q"/><path class="sn6jazbtt"/><path class="iy9c-ybld"/><path class="ilgopw0za"/><path class="fk_-d5geb"/><path class="ijl1k4n1u"/><path class="n92ioac_s"/><path class="x-gul3pnt"/><path class="p-q2wtbgh"/><path class="x-acaqbpt"/><path class="vd9w2bchv"/><path class="yb2d7b_hp"/><path class="ia5bpxbmb"/><path class="br3cauwxi"/><path class="fephwhbad"/><path class="owe5yebol"/><path class="qe0iuezeo"/><path class="pmk02ibez"/><path class="bwtwwbbgq"/><path class="da17pdb4r"/><path class="uu7rtcb9u"/><path class="a70fj0bks"/><path class="o212jei5r"/><path class="bfzn7jbge"/><path class="mnmw62orq"/><path class="i6-_ost1c"/><path class="movnhm8io"/><path class="g6yuzkbvu"/><path class="c6ci_lb6q"/><path class="caavccclu"/><path class="btriv46hc"/><path class="mxjq4o1mh"/><path class="tkk-iib9t"/><path class="flv4dacat"/><path class="hc792fi_s"/><path class="ymaan_bqy"/><path class="aw1qywboy"/><path class="a8ded3f9z"/><path class="x--rsv84v"/><path class="ku7s52jer"/><path class="ul4i6uxsl"/><path class="iotk3-brc"/><path class="cra2wmb6x"/><path class="ahaf8ubrb"/><path class="qls_mmpyj"/><path class="wngqhvb-g"/><path class="m19fv0mlu"/><path class="m7-akhp5u"/><path class="p_qbk242d"/><path class="hxfrgbrex"/><path class="x0f513bbh"/><path class="g26rapbdv"/><path class="og2pp4bet"/><path class="q40mb_blg"/><path class="vgje1nk2f"/><path class="ghj6w-brf"/><path class="sn2xf232h"/><path class="fr3deccbw"/><path class="ap-q4elbu"/><path class="md3zn8x5x"/><path class="cmttbebna"/><path class="z9wxxr8xx"/><path class="lk0p_te4q"/><path class="aa5rs1bji"/><path class="xxw20ocxy"/><path class="tmtqqm6hs"/><path class="ryowhqbav"/><path class="lg8r4ablm"/><path class="g58jvpskq"/><path class="w31p75p-u"/><path class="pc7qm4bsz"/><path class="xux7tackt"/><path class="eat60w-4t"/><path class="ptjzvacfi"/><path class="zikq0l54x"/><path class="f6yc7cczq"/><path class="fhnpgry8k"/><path class="es418xnwv"/><path class="spvdfef5t"/><path class="c1hf91qca"/><path class="k_0q4pbmm"/><path class="g60urbb7c"/><path class="q6w7gq2gx"/><path class="csz1b8bzz"/><path class="a4bb7wbeh"/><path class="c365o03dx"/><path class="mb60ebb-w"/><path class="tq4ujpoij"/><path class="b_ikglf-c"/><path class="sbevwqvmh"/><path class="zaaksxf9t"/><path class="cjdenligf"/><path class="vvj0lig3l"/><path class="v8wb-wl2f"/><path class="yyt9czb_u"/><path class="hijbwzbzw"/><path class="bsz8c642m"/><path class="l67avqb8d"/><path class="ezso-y93w"/><path class="r5xrwtbhd"/><path class="hf_r1bcsy"/><path class="p1b8aflqb"/><path class="bjpxkibcq"/><path class="ek78imbbu"/><path class="y_0hwi55z"/><path class="o326yhy0p"/><path class="iuas6y-7z"/><path class="gmcrerb1c"/><path class="fi1tifvgn"/><path class="voa4sabuh"/><path class="nmuavtquy"/><path class="re74qj_vt"/><path class="sb8y-gtjm"/><path class="uyxo67amk"/><path class="ee1ieceyy"/><path class="graarob7s"/><path class="j0pc73r_x"/><path class="c6z3ambqe"/><path class="ltu2cgfeg"/><path class="s_1k18r8m"/><path class="h4co75lps"/><path class="ewimd15fp"/><path class="k92n9dznc"/><path class="cjgo9ob2f"/><path class="j1vh4dvvj"/><path class="iapwy3bxj"/><path class="plgaksbwf"/><path class="d44s53baa"/><path class="cl90v6bgw"/><path class="eljhsbcuu"/><path class="z7egizbtp"/><path class="nllcv2cgb"/><path class="ek22dnbxw"/><path class="q-2c-abrz"/><path class="y51rlqbdp"/><path class="xklk57brl"/><path class="mus6t7bhb"/><path class="m_vag5bom"/><path class="vw0a-f3mw"/><path class="efnv_bijy"/><path class="zc5ssbvrp"/><path class="xcqkbhx1k"/><path class="y-xzbobkx"/><path class="oz2k8ybjg"/><path class="f1cuqmbtl"/><path class="nk4rkev_n"/><path class="bwgwc5xab"/><path class="wpvgr1piu"/><path class="pt1-uqb4i"/><path class="vtlr869ho"/><path class="e4ykz3bsm"/><path class="twnkrm_ll"/><path class="s-octnb_w"/><path class="vvl4rubeb"/><path class="jl_r1hmqe"/><path class="k1j5spbvb"/><path class="xc9elmrxs"/><path class="z2dld5nlg"/><path class="to5a-yrtm"/><path class="wx39_sgmh"/><path class="vcdalsn0x"/><path class="ubric5b5h"/><path class="c6ociabuo"/><path class="isphtkblw"/><path class="gvpt9_b_c"/><path class="rt_srpwtm"/><path class="c0tbodjhl"/><path class="h2oiiyb5h"/><path class="eeis7vb4n"/><path class="fxajvwb2g"/><path class="s-a32r5dy"/><path class="o2l8p6b7q"/><path class="mr2x2wbos"/><path class="owh90fv_d"/><path class="bmxco-mmo"/><path class="f06-5q0aq"/><path class="fnu7wcn-k"/><path class="hz_q6cdol"/><path class="zl16jpb6z"/><path class="mtzrhqbop"/><path class="ngeqc4bzo"/><path class="ku5_5nb2e"/><path class="rqpma_9_g"/><path class="cr9343bos"/><path class="gsq8k0b3e"/><path class="tzk7ycc9b"/><path class="s05smxbog"/><path class="z6pznodfr"/><path class="f0x3c81wb"/><path class="aqv4ou-vz"/><path class="wnlp91b2y"/><path class="o3rz4x0ym"/><path class="b-4zdep1h"/><path class="afl5-db7y"/><path class="wlw7ls07h"/><path class="opgd7hbiy"/><path class="xk5cqkbmc"/><path class="ulelctn6r"/><path class="cv245e38i"/><path class="qonjywbra"/><path class="sghe2ob7a"/><path class="yhrfujd7a"/><path class="hqgc44quv"/><path class="mr6artbwa"/><path class="pb_qfzbny"/><path class="n32kdfb5q"/><path class="wsjhh-qoi"/><path class="tvmuz7bwp"/><path class="r_r5msb8p"/><path class="f80xl8bdv"/><path class="v-8t-60nc"/><path class="vc1jipopa"/><path class="nphc91b_p"/><path class="jxgnoacpo"/><path class="pxe33dhch"/><path class="rwwzjtt0m"/><path class="f0auo_a5l"/><path class="ketr6bcmo"/><path class="rjtjr_bar"/><path class="g9q9-3bao"/><path class="u4dnd8b6c"/><path class="i9iujjbbq"/><path class="ei6dv1cwm"/><path class="tj82s8jsp"/><path class="u_f032bml"/><path class="v8pdqkekz"/><path class="dc3et_b2e"/><path class="gs1l3bbqh"/><path class="mv96spqqv"/><path class="etjn8cbhg"/><path class="zo6usob4b"/><path class="dv9e5s-3h"/><path class="br-fm27fy"/><path class="oqx4acced"/><path class="td_8icbmt"/><path class="u4p1rm1qh"/><path class="juy31g0rs"/><path class="dd_lpybgs"/><path class="oglu7tyca"/><path class="wkq7sfuez"/><path class="kj-a6zbjl"/><path class="n-zz3wa2s"/><path class="aj5p2jbkm"/><path class="qm7j98w0n"/><path class="hni6d2b-n"/><path class="p2zbyhbpt"/><path class="k1pu5nbck"/><path class="v_8z4inzh"/><path class="xbkm_9uwo"/><path class="wv52sobxj"/><g class="n1mjunbsu"><ellipse class="unlj9mb-i"/><path class="bnqgkgivl"/></g><path class="tlq41rx6x"/><path class="g5yqo-_am"/><path class="dwn802d4a"/><path class="hqo08y2ql"/><path class="q8_s-3b4n"/><path class="i8o3fqbfi"/><path class="ijyfeibbk"/><path class="eqvhdnb6l"/><path class="k6nmsdj4n"/><path class="d6ys1ybvo"/><path class="vw69a4a3p"/><path class="w-7ew3b6x"/><path class="si4641blq"/><path class="l8i_5iery"/><path class="menkr6bzh"/><path class="mm3r48h3w"/><path class="irpm1zbsp"/><path class="c3pj0xbqf"/><path class="ymz5veyto"/><path class="v51io8bmq"/><path class="pjaxklbhj"/><path class="h4s5v4jft"/><path class="rk258fphd"/><path class="l3xdj7bqw"/><path class="z334klbnk"/><path class="b1e_1ib7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-portugal" /></template>
<style>
.a_-ug2bsa {
  fill: var(--svg-color--232000, #232000);
  d: path("M14.275 27.07c-.159.142-.198-.068-.301-.1a.53.53 0 0 1 .301.1");
}

.a_em3wb6s {
  fill: var(--svg-color--0e1105, #0e1105);
  d: path("m12.798 29.439l.045.102a.1.1 0 0 0 0 .039q.041.053-.004.101l-.102.056a.07.07 0 0 0-.002-.049c.06-.073.046-.166.063-.249");
}

.a-4zf0b1t {
  fill: var(--svg-color--143007, #143007);
  d: path("M21.452 41.03c-.29-.117-.6-.033-.898-.096c-.493-.102-.988-.186-1.46-.366a.1.1 0 0 1 .06-.074a.2.2 0 0 1 .065-.002q.08.018.161.041q.15.04.301.072q.137.038.274.069c.048.013.094.026.143.028c.063.005.125.01.188.024c.101.034.207.022.31.05c.13.045.271.013.404.047c.146.063.317-.012.457.086c.026.04.028.081-.005.121");
}

.a-emgnbyv {
  fill: var(--svg-color--5a5c08, #5a5c08);
  d: path("M30.892 27.943c-.13-.045-.161-.129-.104-.25z");
}

.a01se4b9k {
  fill: var(--svg-color--711409, #711409);
  d: path("M30.538 30.57c-.094.063-.176.084-.211-.063c.082-.019.145.03.211.063");
}

.a0m5r9b7f {
  fill: var(--svg-color--f5f408, #f5f408);
  d: path("M25.815 34.928c-.238-.057-.265-.217-.207-.42c.104.03.172-.025.233-.097c.063-.075.131-.125.229-.052c.084-.016.123.013.097.102l.018.102c-.001.168-.155.223-.238.33c-.04.03-.081.051-.132.035");
}

.a1-bh54iv {
  fill: var(--svg-color--eeea51, #eeea51);
  d: path("m16.589 36.403l.046-.015l.225.061l-.275.009q0-.027.004-.055");
}

.a12iiab4q {
  fill: var(--svg-color--202020, #202020);
  d: path("m25.36 32.818l.042-.006c-.026.095.087.254-.121.263z");
}

.a1k46jbiv {
  fill: var(--svg-color--552c02, #552c02);
  d: path("m26.08 35.559l-.015-.077l.018-.022q.022-.017.048-.031c.034-.014.07-.031.105.003c.031.005.07.003.073.048c.004.039-.022.057-.059.061q-.086.008-.17.018");
}

.a1ln-nbrc {
  fill: var(--svg-color--272300, #272300);
  d: path("M30.931 28.964c-.145-.043-.077-.159-.084-.25c.072.069.071.163.084.25");
}

.a1ojgbc7h {
  fill: var(--svg-color--181800, #181800);
  d: path("M25.811 30.1q-.01-.022-.014-.041c-.001-.007.009-.013.014-.02c.1-.069.215-.048.323-.044c.452.011.904-.037 1.354.025c.06.058.01.084-.029.115c-.521.06-1.042.036-1.563.014a.3.3 0 0 1-.085-.049");
}

.a1w5651_l {
  fill: var(--svg-color--0b0d01, #0b0d01);
  d: path("M31.05 31.08q.024.05.046.102l.005.305q.027.04-.015.067a.07.07 0 0 1-.068-.028c-.05-.085-.04-.179-.04-.271q0-.059.02-.116a.13.13 0 0 1 .052-.059");
}

.a2k3exnil {
  fill: var(--svg-color--f3f211, #f3f211);
  d: path("M28.13 29.07c-.009-.051-.004-.096.053-.12c.145-.094.287.009.432.002a.6.6 0 0 1 .113.022c.084.025.163.06.249.076c.108.01.217.023.32.063q.068.023.135.051c.043.023.089.043.084.104l-.055.111a2.2 2.2 0 0 0-.57-.052c-.069-.117-.189-.086-.293-.103a.4.4 0 0 1-.067-.008a.5.5 0 0 1-.09-.046c-.076-.064-.171-.038-.257-.06a.13.13 0 0 1-.054-.04");
}

.a2z7mmbth {
  fill: var(--svg-color--edeb59, #edeb59);
  d: path("m26.836 37.32l-.194.023l-.104-.01c.098-.075.196-.071.298-.013");
}

.a3g5gpb6j {
  fill: var(--svg-color--3b3d14, #3b3d14);
  d: path("M22.597 21.52a.1.1 0 0 0 .036-.023c.145.033.293.002.438.019c.073.075.002.09-.049.111c-.046.009-.086-.013-.128-.026l-.306-.006z");
}

.a3t9x-d3h {
  fill: var(--svg-color--6f700c, #6f700c);
  d: path("M21.2 40.76h-.25q-.03-.005-.029-.036c.014-.026.041-.036.064-.051c.108-.01.217-.021.317.036z");
}

.a3y9dcx0b {
  fill: var(--svg-color--fcfa03, #fcfa03);
  d: path("M16.522 30.614v-.051c.011-.097-.013-.2.064-.283c.164-.072.334-.052.503-.021q.038.015.063.051c.024.075-.031.125-.063.182c-.049.079-.075.172-.128.249c-.081.147-.212.164-.354.124c-.138-.037-.105-.15-.085-.251");
}

.a4bb7wbeh {
  fill: var(--svg-color--ecec5c, #ecec5c);
  d: path("M14.539 32.15c-.028-.079-.127-.032-.165-.092c.069.032.218-.113.208.094q-.02-.003-.043-.002");
}

.a4lxqp41c {
  fill: var(--svg-color--1e0e00, #1e0e00);
  d: path("m28.28 37.28l.154-.074c.01.11-.096.128-.151.188z");
}

.a4t-gm3qr {
  fill: var(--svg-color--0b0601, #0b0601);
  d: path("m32.06 29.541l.054-.043c-.015.096.043.201-.036.288q-.008-.123-.018-.245");
}

.a5ceoobxx {
  fill: var(--svg-color--faf905, #faf905);
  d: path("m22.59 21.686l-.001-.091c.088-.085.19-.061.296-.039c.049.039.095.079.049.149c-.119.065-.231.024-.344-.019");
}

.a5cew9jdo {
  fill: var(--svg-color--5f5d09, #5f5d09);
  d: path("M19.402 35.23a.2.2 0 0 1 .026.051l-.208.046a.24.24 0 0 1-.062-.247c.12-.01.153.119.244.15");
}

.a5xdqqieb {
  fill: var(--svg-color--6a6e11, #6a6e11);
  d: path("M12.634 33.951c.07.084.067.19.096.287c-.172-.032-.109-.154-.099-.256z");
}

.a6j2s-b_w {
  fill: var(--svg-color--252400, #252400);
  d: path("M15.764 28.954c-.13.012-.265-.003-.387.06c-.032.056-.08.031-.125.022q-.02-.02-.013-.039q.005-.022.01-.021c.166-.065.342-.071.515-.097z");
}

.a70fj0bks {
  fill: var(--svg-color--6d6e14, #6d6e14);
  d: path("M17.71 30.665c-.06-.058-.071-.126-.045-.202c.064.035.064.104.084.161z");
}

.a7v0eov0t {
  fill: var(--svg-color--decf5d, #decf5d);
  d: path("m28.51 25.446l-.081.001c-.067-.025-.149-.001-.207-.059l.308.002z");
}

.a7xwohdrz {
  fill: var(--svg-color--525400, #525400);
  d: path("M28.24 34.92c-.012.035-.008.082-.063.088c.014-.1-.19-.106-.104-.24q.084.075.167.152");
}

.a85a_5kgv {
  fill: var(--svg-color--5c5c08, #5c5c08);
  d: path("m29.651 37.17l-.051.104a.34.34 0 0 1-.188.153c-.026-.184.113-.213.239-.257");
}

.a8ded3f9z {
  fill: var(--svg-color--e6e60b, #e6e60b);
  d: path("m24.954 35.568l-.062-.108c-.067-.12.023-.184.093-.257a.3.3 0 0 1 .246-.01c.118.084.069.191.043.297q-.045.152-.204.147a2 2 0 0 1-.116-.069");
}

.a9de2j0sf {
  fill: var(--svg-color--293347, #293347);
  d: path("M23.554 29.975c-.125.04-.098.145-.098.233q-.004.563-.003 1.123c-.12-.426-.033-.861-.05-1.292c-.005-.11.086-.076.151-.064");
}

.a9xbhvely {
  fill: var(--svg-color--f0f247, #f0f247);
  d: path("M16.07 36.3c.049.02.118-.01.152.056c-.085-.007-.179.034-.25-.048z");
}

.aa1-ww6qc {
  fill: var(--svg-color--89882a, #89882a);
  d: path("M21.21 25.382a.2.2 0 0 1 .001-.049a9.6 9.6 0 0 1 1.623.001l.003.053z");
}

.aa5rs1bji {
  fill: var(--svg-color--f3ec6f, #f3ec6f);
  d: path("M26.694 36.518q.163-.008.329-.014c-.102.11-.23.038-.347.048z");
}

.aa69oeb3t {
  fill: var(--svg-color--f0ee0c, #f0ee0c);
  d: path("m29.764 24.327l.074.08c.095.089.213.158.229.306q-.001.114-.11.146a.2.2 0 0 1-.112-.005a.14.14 0 0 1-.056-.044a.4.4 0 0 1-.034-.062l-.033-.059l-.02-.026c-.065-.132-.235-.197-.23-.373a.16.16 0 0 1 .096-.109c.099.005.179.029.196.146");
}

.abs8gutyo {
  fill: var(--svg-color--fdfd01, #fdfd01);
  d: path("M25.577 21.544a.2.2 0 0 0-.185-.013a.15.15 0 0 1-.027-.064c0-.038.01-.069.042-.092c.064.032.156-.037.204.054q-.003.057-.002.112q-.016 0-.032.003");
}

.abtf6sbig {
  fill: var(--svg-color--544e40, #544e40);
  d: path("M27.55 25.944q-.043-.027-.086-.051q-.05-.046-.007-.099c.04-.021.05-.06.051-.101c.079.074.043.166.042.251");
}

.ad3zzkb4i {
  fill: var(--svg-color--6c6c0d, #6c6c0d);
  d: path("m17.04 22.953l.009.054c-.06.043-.104.108-.188.108c-.004-.123.111-.12.179-.162");
}

.ae6-csbai {
  fill: var(--svg-color--4c4f00, #4c4f00);
  d: path("M31.499 30.713c-.083-.036-.215.007-.231-.14c.091.023.194.027.231.14");
}

.aedpz0j1y {
  fill: var(--svg-color--4c180b, #4c180b);
  d: path("M27.711 39.19c.093-.059.149-.182.285-.162a.4.4 0 0 1-.231.207c-.044.016-.056-.006-.054-.045");
}

.afdej5qyw {
  fill: var(--svg-color--666607, #666607);
  d: path("m31.28 27.29l-.013-.004c-.086-.068-.139-.146-.071-.256c.05.081.101.161.084.26");
}

.afg1g1bzj {
  fill: var(--svg-color--f1f308, #f1f308);
  d: path("m16.483 38.09l-.055.108l-.128-.103c-.094-.004-.125-.084-.169-.147l-.067-.05a.11.11 0 0 1-.004-.118c.091-.061.16-.029.216.055l.063.056c.048.067.209.05.144.199");
}

.afl5-db7y {
  fill: var(--svg-color--353507, #353507);
  d: path("M18.02 34.66c.032-.048-.069-.191.1-.144c.066.051.146.104-.005.149z");
}

.ag_i-zlgo {
  fill: var(--svg-color--082401, #082401);
  d: path("M17.15 39.746a.2.2 0 0 0 .05-.006l.154.069q-.003.017-.004.036c-.084.005-.16-.013-.2-.099");
}

.agrm-uu5c {
  fill: var(--svg-color--535506, #535506);
  d: path("M26.838 35.943a.1.1 0 0 1 .008-.041c.084.024.181.033.199.149v-.005c-.081.066-.146.02-.209-.031q-.027-.038.002-.072");
}

.ahaf8ubrb {
  fill: var(--svg-color--c9c645, #c9c645);
  d: path("M17.862 34.878a2 2 0 0 1-.116-.075a2 2 0 0 1-.026-.139c.111.004.137.105.19.173l.017.021l-.021.013a.1.1 0 0 0-.044.007");
}

.ahn4adcsh {
  fill: var(--svg-color--e1e14f, #e1e14f);
  d: path("m16.38 36.617l.084-.01q.06-.02.12-.043l.051.096c-.087-.002-.181.033-.255-.043");
}

.aicd4o09r {
  fill: var(--svg-color--f7f804, #f7f804);
  d: path("M23.09 39.946a.1.1 0 0 0-.002-.05c.057-.168.183-.085.286-.08c.096-.004.194.021.286-.017v-.013c.082-.103.197-.1.313-.1l.147-.001c.077-.021.081.036.091.087c0 .059-.041.092-.084.12h-.255c-.058.061-.137.075-.212.097a4 4 0 0 1-.354.01h-.116c-.051.018-.081-.009-.1-.053");
}

.aicqw8eqe {
  fill: var(--svg-color--71170c, #71170c);
  d: path("m23.35 40.965l-.26-.001c-.034-.028-.105-.002-.113-.074a.1.1 0 0 1 .046-.056c.097-.043.202-.025.303-.038c.077-.015.154-.041.229.005a.1.1 0 0 1 .028.07c-.038.132-.166.038-.233.094");
}

.aijsys7cg {
  fill: var(--svg-color--f7f704, #f7f704);
  d: path("m20.222 21.784l.099-.05c.044.023.058.063.059.108c-.104.074-.227.05-.342.062c-.046-.019-.065-.057-.072-.104q.127-.006.256-.016");
}

.aj4k49b_x {
  fill: var(--svg-color--151a00, #151a00);
  d: path("M25.919 22.386c-.115.021-.216.015-.247-.127a.5.5 0 0 1 .245.118z");
}

.aj5p2jbkm {
  fill: var(--svg-color--fbf822, #fbf822);
  d: path("M18.788 34.508q.027.003.053.002v.053h-.053z");
}

.ajxv5d55a {
  fill: var(--svg-color--726a06, #726a06);
  d: path("m27.346 29.89l-.014-.201q0-.025.014-.048l.058.004l-.005.246z");
}

.ak3wg6bdz {
  fill: var(--svg-color--a4a608, #a4a608);
  d: path("m25.919 24.877l.054-.001c.071.087.06.169-.006.253l-.052-.014z");
}

.aktcqvclq {
  fill: var(--svg-color--2b2c00, #2b2c00);
  d: path("M17.813 39.13c.136-.021.248.011.304.151c-.089-.076-.253 0-.304-.151");
}

.al404vmbf {
  fill: var(--svg-color--48391a, #48391a);
  d: path("M18.221 30.881q0-.032.004-.064c.082.01.104.066.099.139c-.005.066-.055.066-.105.065l.003-.053q-.042-.044-.001-.087");
}

.amb84o86t {
  fill: var(--svg-color--212100, #212100);
  d: path("m20.948 20.979l-.051-.049l-.006-.012a.46.46 0 0 1 .307-.002a.2.2 0 0 0 0 .046z");
}

.amzwb_sld {
  fill: var(--svg-color--ecec0b, #ecec0b);
  d: path("m28.13 32.467l.137-.02c.091-.039.214.036.281-.081a.24.24 0 0 1 .101-.061c.13-.031.265-.001.393-.043a.22.22 0 0 1 .159.023q.045.048.028.115a.2.2 0 0 1-.082.087c-.099.041-.209.003-.31.043a.46.46 0 0 0-.263.061a.27.27 0 0 1-.197-.004c-.065-.013-.139.021-.197-.029z");
}

.aocukkvxj {
  fill: var(--svg-color--f1ef65, #f1ef65);
  d: path("M26.27 36.771c.068.104.167.018.25.038c-.101.111-.229.044-.346.056q-.03-.023-.015-.056c.029-.038.062-.067.111-.038");
}

.aov9vpb0h {
  fill: var(--svg-color--f9f907, #f9f907);
  d: path("m29.2 32.406l-.011-.117q-.003-.041.03-.064c.084-.035.172-.014.26-.024c.095-.021.181-.07.275-.092c.074-.012.146-.034.218-.039c.111-.06.236-.062.358-.073l-.006.003c.13-.076.272-.094.417-.107l-.003.004c.081.002.164-.092.235-.029c.058.049-.002.121-.041.176c-.079.012-.166-.007-.235.053l-.053.015a.58.58 0 0 1-.36.089l-.072.01c-.099.089-.217.096-.338.092l-.072.012c-.117.111-.274.08-.413.116c-.065-.007-.133.036-.189-.025");
}

.ap-q4elbu {
  fill: var(--svg-color--969600, #969600);
  d: path("M21.308 25.12h.346l.001.054l-.352-.005a.1.1 0 0 1 .005-.049");
}

.aqd-shbnc {
  fill: var(--svg-color--666909, #666909);
  d: path("M14.688 27.01c-.104.025-.188-.016-.262-.084a.07.07 0 0 1 .048-.041c.074.028.168.012.216.098q0 .014-.002.027");
}

.aqesdl8te {
  fill: var(--svg-color--6a6719, #6a6719);
  d: path("M17.256 39.489q.08.046.161.097c-.111.062-.171.039-.161-.097");
}

.aqv4ou-vz {
  fill: var(--svg-color--5b5914, #5b5914);
  d: path("M17.754 25.941c-.12.001-.067-.131-.133-.172q-.03-.011-.029-.044a.05.05 0 0 1 .046-.032q.037.024.075.045z");
}

.ar7a0cbln {
  fill: var(--svg-color--793b37, #793b37);
  d: path("M32.23 30.72q.022-.008.044-.012c-.02.164.06.341-.049.496l-.01-.017c-.052-.157-.111-.315.015-.467");
}

.as80s9g9l {
  fill: var(--svg-color--433030, #433030);
  d: path("M20.379 37.495q0 .04-.003.077c-.079-.023-.169-.018-.23-.087z");
}

.atxm8btdf {
  fill: var(--svg-color--dfde60, #dfde60);
  d: path("M27.507 30.04h-1.696a.06.06 0 0 1 .006-.043c.55-.063 1.102-.015 1.65-.026q.06.012.04.069");
}

.atyotlb-g {
  fill: var(--svg-color--4c4d1d, #4c4d1d);
  d: path("M27.97 33.3c-.135-.108.016-.216.002-.322c.048-.01.071.003.055.056c-.007.09.024.19-.057.266");
}

.aw06yfbgr {
  fill: var(--svg-color--e1e266, #e1e266);
  d: path("m14.481 35.937l-.094.112c-.069-.048-.045-.099-.007-.15c.036.011.083-.014.101.038");
}

.aw1qywboy {
  fill: var(--svg-color--3a390a, #3a390a);
  d: path("M18.841 35.635c.14-.047.169-.26.354-.238a.1.1 0 0 0-.001.044l-.094.132c-.056.077-.196.046-.217.167l-.045-.049q-.023-.019-.015-.036q.008-.02.018-.02");
}

.aw6soi4zk {
  fill: var(--svg-color--293400, #293400);
  d: path("M16.327 23.74q.108-.1.221-.197a.1.1 0 0 1 .039.002c.036.02.077.035.046.09c-.041.008-.094.008-.105.058c-.013.046.031.048.063.048q.064.002.129.002l4.732-.002c-.066.082-.158.049-.238.051H16.6c-.095-.001-.189-.001-.273-.052");
}

.awmq6wn4p {
  fill: var(--svg-color--1f1b01, #1f1b01);
  d: path("M26.326 34.967q.025.007.051.012l.03.017c.061.048.046.123.067.186c-.036.069-.098.05-.154.044c-.035-.052-.06-.111-.124-.136q-.047-.017-.092-.038a.23.23 0 0 1-.104-.094c-.019-.118.06-.146.151-.161c.102.013.124.105.175.17");
}

.ax_u39b8z {
  fill: var(--svg-color--e7e65a, #e7e65a);
  d: path("M26.554 25.548c.067-.01.138-.036.198.021c.021.062-.008.104-.053.14a.17.17 0 0 1-.118.017a.14.14 0 0 1-.065-.046c-.019-.053-.038-.108.038-.132");
}

.ay71ay7lx {
  fill: var(--svg-color--f2f116, #f2f116);
  d: path("M29.26 25.434q.125.05.249.104q.062.07.011.15a.2.2 0 0 1-.106.058a.35.35 0 0 1-.192-.02c-.077-.06-.181-.074-.243-.154q-.012-.034-.008-.071a.14.14 0 0 1 .063-.08c.076-.018.149.026.226.013");
}

.ayejqmkcb {
  fill: var(--svg-color--dcdf5d, #dcdf5d);
  d: path("M18.331 37.538q.046-.002.096-.007l.108-.041c.006.064.079.048.106.086c-.105.003-.216.044-.31-.038");
}

.az6234o6b {
  fill: var(--svg-color--f3f308, #f3f308);
  d: path("M30.02 29.537c-.204-.001-.382-.097-.569-.156c-.024-.062.01-.098.055-.131a.3.3 0 0 1 .111-.033a.55.55 0 0 1 .296.053c.061.039.13.05.199.061c.067.016.133.037.2.048q.035.005.065.017q.125.049.254.084l.063.021c.082.033.164.059.244.097c.067.034.15.046.196.118l.006.033c-.044.058-.113.041-.171.058a.12.12 0 0 1-.102.017c-.105-.053-.227-.057-.325-.125l-.214-.06c-.117.012-.215-.04-.308-.102");
}

.b_8nlgqgn {
  fill: var(--svg-color--636410, #636410);
  d: path("m30.06 26.69l.016-.085l.088.166l-.144.041c-.022-.025-.013-.053-.002-.081a.2.2 0 0 1 .042-.041");
}

.b_ikglf-c {
  fill: var(--svg-color--f9f905, #f9f905);
  d: path("m29.16 31.547l-.275-.011l-.016-.054c.073-.079.174-.035.261-.058a.65.65 0 0 1 .317 0q.002.033.007.065c-.074.155-.186.099-.294.058");
}

.b_o4s8bxc {
  fill: var(--svg-color--f5f507, #f5f507);
  d: path("M17.708 37.43c-.003-.066-.077-.053-.104-.094q-.025-.022-.015-.038c.01-.016.013-.017.018-.017c.081.007.187-.036.207.098l-.006.006c-.025.038-.042.084-.1.045");
}

.b-4zdep1h {
  fill: var(--svg-color--582e07, #582e07);
  d: path("m18.642 34.705l-.003.063v.002l-.04.033a.2.2 0 0 1-.068.036a.1.1 0 0 1-.052-.005l-.051-.326q.104.029.207.053a.1.1 0 0 1 .021.021a.1.1 0 0 1 .014.051c-.009.023-.009.053-.028.072");
}

.b0qa6sq6s {
  fill: var(--svg-color--392a0f, #392a0f);
  d: path("m26.07 24.654l-.001-.084q.131.004.263.006v.019c-.065.113-.173.041-.262.059");
}

.b0ymgmbwl {
  fill: var(--svg-color--f2f204, #f2f204);
  d: path("M13.692 34.926c.013-.094-.029-.164-.091-.229c-.058-.116-.136-.225-.156-.359c-.099-.068-.039-.199-.108-.279c-.068-.06-.059-.148-.089-.223l-.051-.099c-.031-.08-.077-.157-.075-.25c-.036-.12-.084-.238-.077-.366a1.2 1.2 0 0 1-.105-.464c-.061-.061-.043-.147-.072-.218c-.002-.078-.043-.155-.007-.234a.5.5 0 0 0-.059-.27c-.086-.154-.004-.328-.053-.488c-.025-.108.003-.222-.033-.33c.012-.117-.069-.263.108-.324a.13.13 0 0 1 .081.021c.072.098.044.223.09.326c.023.126.015.253.019.379a1 1 0 0 0 .036.369c-.004.138.012.274.021.412c.089.243.075.508.171.751c.049.291.162.563.256.841c.033.095.066.188.086.287c.085.212.272.385.243.64c-.028.056-.064.102-.135.107");
}

.b1e_1ib7z {
  fill: var(--svg-color--ecf4fa, #ecf4fa);
  d: path("M21.706 33.994c-.084.01-.17.029-.218-.076c-.025-.056-.013-.105.021-.14c.083-.083.168-.044.247.015c.063.088.037.151-.05.201");
}

.b1jh96bna {
  fill: var(--svg-color--670000, #670000);
  d: path("M21.557 35.431q.438-.002.874-.007q.03-.022.036.014c-.304.137-.609.146-.91-.007");
}

.b1rnxflue {
  fill: var(--svg-color--efee0a, #efee0a);
  d: path("M25.09 39.38c.065.003.104.034.105.104a.16.16 0 0 1-.038.096l-.17.01a.34.34 0 0 1-.263.102l-.145.049a.28.28 0 0 1-.104-.154c.192-.113.399-.173.615-.207");
}

.b2cil-bdn {
  fill: var(--svg-color--192802, #192802);
  d: path("m17.251 36.458l-.113.008q-.139-.007-.278-.017c-.072-.031-.155 0-.228-.034c-.011-.048-.002-.077.056-.061c.192.008.392-.03.563.104");
}

.b2z5bhggj {
  fill: var(--svg-color--193807, #193807);
  d: path("M12.177 33.27c.061.116.085.243.101.371c-.157-.089-.096-.239-.101-.371");
}

.b3p4ieb-x {
  fill: var(--svg-color--052605, #052605);
  d: path("M21.608 38.04c-.15.014-.099.132-.1.211q-.006.796-.01 1.594l-.052-.005c.002-.516-.001-1.032.011-1.548c.003-.142-.058-.221-.16-.289q.016-.035.055-.038l.255.031q.025.015.018.029c-.007.014-.01.015-.017.015");
}

.b5lyrxmye {
  fill: var(--svg-color--dddd1d, #dddd1d);
  d: path("m25.417 35.936l.093.063c.044.045.087.091.08.161a.3.3 0 0 1-.034.067c-.151-.001-.17-.154-.26-.227c.026-.049.07-.063.121-.064");
}

.b5okfhswt {
  fill: var(--svg-color--f8fa04, #f8fa04);
  d: path("M14.994 35.434c.039.099.127.104.214.107c.003.09-.076.09-.128.119q-.031.013-.063.019c-.045.005-.088.002-.119-.036c-.087-.005-.174-.007-.212-.107q.155-.05.308-.102");
}

.b6p646ioz {
  fill: var(--svg-color--3a3200, #3a3200);
  d: path("m27.403 29.645l.054-.056l.004.302h-.063c-.062-.084-.064-.166.005-.246");
}

.b6xtgp6oo {
  fill: var(--svg-color--6d2323, #6d2323);
  d: path("M19.247 34.03c.041.056.116.092.104.179c-.096-.025-.14-.079-.104-.179");
}

.b7f72jj9f {
  fill: var(--svg-color--474539, #474539);
  d: path("M24.983 37.23c-.01.125-.106.135-.199.149c.016-.115.108-.133.199-.149");
}

.b7x4lkbqm {
  fill: var(--svg-color--e3e063, #e3e063);
  d: path("m25.45 37.753l-.092-.011c.126-.096.27-.037.404-.043a.1.1 0 0 0-.01.034z");
}

.b8pluxm6k {
  fill: var(--svg-color--5b5b13, #5b5b13);
  d: path("m15.35 25.437l-.15-.056c-.037-.086-.207.01-.195-.144c.128-.084.253-.021.378.009c.04.022.051.059.045.102l-.021.033q-.03.027-.057.056");
}

.b8qcs8bas {
  fill: var(--svg-color--292a00, #292a00);
  d: path("M32.02 31.02c.156-.101.158-.4.002-.609c.092-.054.123.142.224.057c.065.105-.056.161-.067.246c.026.145.051.289-.012.433c-.054-.04-.131-.049-.147-.127");
}

.b8sqt561y {
  fill: var(--svg-color--151300, #151300);
  d: path("M18.12 29.938h-.613l-.019-.021l.015-.023h.11a.25.25 0 0 1 .107-.058a.9.9 0 0 1 .325.014a.2.2 0 0 1 .067.046q.01.017.008.042");
}

.b9roqt-fs {
  fill: var(--svg-color--545506, #545506);
  d: path("m17.913 21.833l.002-.087l.051-.023c.04.004.091-.065.117.019c-.043.055-.107.071-.17.091");
}

.b9sc-7bza {
  fill: var(--svg-color--252700, #252700);
  d: path("M28.749 36.403c.043-.126.156-.082.245-.099c.04.023.05.062.051.103c-.099-.033-.198.082-.296-.004");
}

.ba3b8rdos {
  fill: var(--svg-color--e1d9c7, #e1d9c7);
  d: path("M26.532 29.3c-.019.127.037.262-.043.379q-.01-.075-.017-.148c-.017-.083-.044-.166.017-.244a.06.06 0 0 1 .043.013");
}

.bb2eum-8c {
  fill: var(--svg-color--262600, #262600);
  d: path("M30.27 25.2q-.016.016-.036.029c-.091-.047-.207-.045-.267-.148q.127.037.253.07z");
}

.be-e1f07n {
  fill: var(--svg-color--dcd94e, #dcd94e);
  d: path("m15.03 25.476l-.191-.087l.203-.007q-.007.045-.012.094");
}

.bew0jb_rg {
  fill: var(--svg-color--2e2c00, #2e2c00);
  d: path("M31.674 28.612h.027c.055.075.058.164.069.253c.017.053-.007.063-.053.051c.01-.105-.078-.195-.043-.304");
}

.bfri8mbre {
  fill: var(--svg-color--fafa04, #fafa04);
  d: path("m25.811 35.864l-.084.086c-.061.039-.112.099-.195.091a.2.2 0 0 1-.134-.062a.34.34 0 0 1-.087-.232a.2.2 0 0 1 .017-.069a1 1 0 0 1 .058-.091c.106-.102 0-.291.149-.374c.104.01.163.09.24.145c.059.072.12.142.166.22c.048.139-.116.18-.13.286");
}

.bfu-50e7k {
  fill: var(--svg-color--dadf5d, #dadf5d);
  d: path("M16.325 37.37a.3.3 0 0 1-.047.021l-.048-.012c-.019-.087-.122-.036-.156-.097c.075-.079.166-.08.255-.038c.07.037.075.087-.004.126");
}

.bfzn7jbge {
  fill: var(--svg-color--f0f345, #f0f345);
  d: path("M22.485 26.04a.2.2 0 0 1 .005-.044l.342-.001l.049.051z");
}

.bg5hyflvg {
  fill: var(--svg-color--f2f10b, #f2f10b);
  d: path("M16.942 39.33q-.05.099-.103.197q-.084-.049-.171-.096c-.053-.052-.147-.032-.186-.111l-.298-.197c-.075-.026-.118-.093-.169-.148l-.002-.003c-.084-.051-.192-.069-.239-.171l.003.003q-.041-.015-.036-.059c.029-.084.099-.112.179-.125c.025-.002.055-.007.074.008c.319.232.674.411.948.702");
}

.bgh1lnbdl {
  fill: var(--svg-color--a5a627, #a5a627);
  d: path("M29.651 25.884c-.075-.083.06-.084.055-.142l.105.007l.003.032c-.046.021-.069.057-.053.109z");
}

.bgj44ls8s {
  fill: var(--svg-color--ebe95e, #ebe95e);
  d: path("m28.992 25.338l-.15-.051c.085.003.181-.051.246.051z");
}

.biidwwb5q {
  fill: var(--svg-color--e1d158, #e1d158);
  d: path("M24.524 22.05c-.036.009-.078.002-.097.046h-.021l-.021-.002l-.053-.095q.125-.003.25-.003z");
}

.bjpxkibcq {
  fill: var(--svg-color--292700, #292700);
  d: path("M29.2 32.25q-.003-.022-.002-.044c.024-.045.079-.025.111-.053l.197-.002c.031.031.028.061 0 .092z");
}

.bjye9vvfl {
  fill: var(--svg-color--692422, #692422);
  d: path("M26.734 35.397c-.036-.099.005-.156.102-.181c.014.088-.061.126-.102.181");
}

.bk7zqac2n {
  fill: var(--svg-color--1d3d15, #1d3d15);
  d: path("M13.235 25.735a.8.8 0 0 1-.188.269c.017-.124.047-.235.188-.269");
}

.bkk_50lqg {
  fill: var(--svg-color--163209, #163209);
  d: path("M17.675 21.69c-.029.075-.13.041-.167.104l-.094.012c.02-.19.166-.095.261-.116");
}

.bl2b9gmxf {
  fill: var(--svg-color--f9f70d, #f9f70d);
  d: path("M26.28 29.886q-.155 0-.308.002c-.038-.238-.038-.238.296-.247l.02.048c.053.067.045.133-.008.197");
}

.blcholb5q {
  fill: var(--svg-color--1f2300, #1f2300);
  d: path("M13.247 35.18a.2.2 0 0 1 .192-.147c.01.144-.119.111-.192.147");
}

.blgk_67rz {
  fill: var(--svg-color--1f2904, #1f2904);
  d: path("m13.673 29.385l-.637.25q-.098.024-.197.046l.004-.101c.1.031.151-.005.179-.106c.02-.065-.01-.154.072-.2l.03.02c.059.099.141.102.239.067c.104-.036.214-.073.31.024");
}

.blm7npxzw {
  fill: var(--svg-color--e8e913, #e8e913);
  d: path("m15.461 29.14l-.01-.068c-.039-.019-.07-.043-.048-.093c.118-.029.237-.069.36-.02c.063.017.125.034.104.123l-.149.048l-.074.005c-.061.054-.123.048-.183.005");
}

.bm-d3kbei {
  fill: var(--svg-color--0b2709, #0b2709);
  d: path("m12.896 26.314l-.007.077c-.01.046.037.094-.006.138a.13.13 0 0 1-.094.015a.1.1 0 0 1-.051-.039c.052-.085.042-.206.15-.257q.037.03.008.066");
}

.bm3t5qbbm {
  fill: var(--svg-color--b80d0b, #b80d0b);
  d: path("M22.64 38.1c.012-.154.123-.091.202-.096c-.025.122-.127.082-.202.096");
}

.bm73-154u {
  fill: var(--svg-color--14316b, #14316b);
  d: path("m22.784 32.661l-1.478.005q-.025-.013-.021-.028q.005-.018.014-.019l1.413-.01c.038-.001.065.01.072.052");
}

.bmxco-mmo {
  fill: var(--svg-color--eeed04, #eeed04);
  d: path("m26.834 25.08l-.296-.005c-.034-.135.045-.281-.049-.407l-.007-.103l.354.007l.012.146z");
}

.bnftygnmt {
  fill: var(--svg-color--202102, #202102);
  d: path("M26.24 35.431q-.054.025-.108.053a.16.16 0 0 1-.076-.148a.2.2 0 0 1 .029-.051a.08.08 0 0 1 .057-.017c.044.009.087.017.104.066z");
}

.bnqgkgivl {
  d: path("M18.533 26.426h6.938v5.706h-6.938z");
}

.bnufn6bgy {
  fill: var(--svg-color--f3f30f, #f3f30f);
  d: path("M28.583 24.565c-.104.013-.22-.05-.311.049l-.063.005c-.042-.065-.127-.113-.083-.212c.071-.063.15-.07.235-.032c.064.049.159.032.219.095q0 .019.005.034z");
}

.bqk56-koj {
  fill: var(--svg-color--f3f30d, #f3f30d);
  d: path("M30.08 37.02c-.007-.039.005-.087-.055-.095l-.01-.064c-.085-.048-.143-.105-.089-.211a.2.2 0 0 1 .108-.031c.098.006.118.081.142.155l.031.051q.008.099.019.198c-.051.081-.1.074-.146-.003");
}

.br-fm27fy {
  fill: var(--svg-color--636320, #636320);
  d: path("m18.12 35.23l.052.002v.051h-.052z");
}

.br3cauwxi {
  fill: var(--svg-color--d01e04, #d01e04);
  d: path("m21.821 25.13l-.104.044c-.099-.101-.082-.204-.005-.308h.104c.071.088.054.175.005.264");
}

.br7kfabkp {
  fill: var(--svg-color--323000, #323000);
  d: path("m13.04 30.717l-.05-.042c.055-.011.112-.013.153-.063h.1q.05-.03.071.021c-.043.191-.154.15-.274.084");
}

.bscgvhamu {
  fill: var(--svg-color--4c4d1d, #4c4d1d);
  d: path("M28.13 32.914c-.097.018-.111-.051-.125-.12l.056-.493c.036.041-.006.11.055.142l.029.011q.037.032.046.079a.16.16 0 0 1-.026.089q-.019.022-.044.043c-.078.085-.037.167.009.249");
}

.bso90ebai {
  fill: var(--svg-color--eced0d, #eced0d);
  d: path("m25.611 34.512l-.053.005c-.115.01-.255.089-.292-.106q.117-.029.238-.053q.044.007.052.051q.029.05.055.103");
}

.bsrgi_buw {
  fill: var(--svg-color--434221, #434221);
  d: path("m24.02 37.648l.05.084c-.071.082-.164.052-.253.056c-.004-.151.133-.098.203-.14");
}

.bsz8c642m {
  fill: var(--svg-color--183900, #183900);
  d: path("M14.693 28.971c-.102.012-.169-.02-.163-.139l.038-.006q.063.07.125.145");
}

.btriv46hc {
  fill: var(--svg-color--c8c810, #c8c810);
  d: path("m18.523 34.26l.007-.044c.005-.045.015-.086.068-.094c.046.095.16.072.228.13c.022.046.008.124.097.111l.058.064a.2.2 0 0 1-.038.029l-.043.022l-.022.011l-.023.007l-.026-.004a.05.05 0 0 1-.037-.029c-.04-.134-.22-.085-.269-.203");
}

.btsb2fbxq {
  fill: var(--svg-color--301c0a, #301c0a);
  d: path("m28.356 24.417l-.23-.01c-.006-.061-.006-.12.057-.156c.109-.024.172.053.243.112q.008.083-.07.054");
}

.bu0lehrgz {
  fill: var(--svg-color--5b4340, #5b4340);
  d: path("m32.12 32.18l.003-.232l.04-.005l-.004.238c0 .005-.01.017-.011.017z");
}

.bu2wkjiiv {
  fill: var(--svg-color--211e18, #211e18);
  d: path("m22.733 35.37l.001.06l-.268.01a.1.1 0 0 0-.036-.014c.092-.068.203-.036.303-.056");
}

.buxmyab-g {
  fill: var(--svg-color--203f11, #203f11);
  d: path("M12.791 35.02q.085.088.105.211c-.139-.019-.103-.126-.105-.211");
}

.bv942obrp {
  fill: var(--svg-color--504700, #504700);
  d: path("M24.278 37.849q.104.003.207.008l.002.026l-.306.01z");
}

.bwgwc5xab {
  fill: var(--svg-color--dedd98, #dedd98);
  d: path("M25.1 34.615a.1.1 0 0 1-.007.049l-.046-.042z");
}

.bwiadsb3r {
  fill: var(--svg-color--362702, #362702);
  d: path("M26.43 24.458q.232.005.462.007c.012.061-.015.104-.067.132a.47.47 0 0 1-.315.003c-.039-.018-.058-.055-.075-.09z");
}

.bwk9bbc8f {
  fill: var(--svg-color--252500, #252500);
  d: path("M14.475 26.881q-.025.023-.048.041c-.075-.02-.169-.006-.203-.104c.093-.021.164.055.251.063");
}

.bwp9db_2u {
  fill: var(--svg-color--0c0d00, #0c0d00);
  d: path("M22.479 23.746q.025-.005.05-.013l.003.106h-1.025q-.02-.02-.017-.042q.001-.023.007-.023c.038-.056.092-.074.157-.067c.037.004.073.012.109.015l.078.002c.156.017.326-.048.471.061l.072.002c.028-.024.064-.025.095-.041");
}

.bwtwwbbgq {
  fill: var(--svg-color--575805, #575805);
  d: path("M17.607 26.14h-.511v-.094q.025-.008.051-.013c.086-.072.2-.038.296-.079a.2.2 0 0 1 .099-.031a.14.14 0 0 1 .086.058a.2.2 0 0 1 .021.065a.12.12 0 0 1-.042.094");
}

.bx-3hbb7u {
  fill: var(--svg-color--881110, #881110);
  d: path("M30.534 27.684c-.095-.048-.149-.105-.059-.205c.028.065.073.125.059.205");
}

.bx9ib-8rk {
  fill: var(--svg-color--f4f50a, #f4f50a);
  d: path("M28.746 33.34c-.111-.003-.173-.086-.241-.158c-.079-.008-.124-.072-.182-.115l-.164-.097a.2.2 0 0 0-.049-.045c-.091-.085-.093-.177-.021-.273c.088-.025.156.025.233.049a.3.3 0 0 1 .052.045q.06.08.143.138c.053.031.077.095.142.115a.2.2 0 0 1 .059.022c.063.043.12.092.185.132a.5.5 0 0 1 .075.065a.6.6 0 0 0 .196.17c.087.054.159.125.246.176a1 1 0 0 1 .125.121c.051.067.115.129.113.224a.16.16 0 0 1-.043.103c-.073.015-.118-.03-.162-.076l-.483-.393a.43.43 0 0 1-.224-.203");
}

.bxrnhubnw {
  fill: var(--svg-color--2d2600, #2d2600);
  d: path("m17.1 29.938l-.61.01c.005-.06.057-.05.094-.063q.026-.017.055-.031a.3.3 0 0 1 .063-.012q.047-.005.095-.004h.124a1 1 0 0 1 .126.012a.3.3 0 0 1 .058.029c.007.02.009.038-.005.059");
}

.bxtlyy_mb {
  fill: var(--svg-color--4f4e00, #4f4e00);
  d: path("m13.865 35.18l.001-.048c.066-.08.16-.094.257-.102q-.002.02-.002.041z");
}

.by3jg9b6j {
  fill: var(--svg-color--62610f, #62610f);
  d: path("M13.858 36.1c.048.108-.074.138-.097.214q-.013-.012-.002-.026a.1.1 0 0 1-.041-.034l-.014.008l-.013-.01a.33.33 0 0 1 .167-.152");
}

.byfpkc9kl {
  fill: var(--svg-color--3b2b01, #3b2b01);
  d: path("M26.328 24.595v-.019l.097-.022l.005.313q-.034.026-.046-.016l-.013-.096c.001-.057.018-.117-.043-.16");
}

.bypgllb9a {
  fill: var(--svg-color--2b1100, #2b1100);
  d: path("M23.663 40.878q-.05-.005-.104-.013v-.035c.046-.057.099-.059.157-.02q.047.028.093.051z");
}

.byza8v8jl {
  fill: var(--svg-color--4e4c0e, #4e4c0e);
  d: path("M27.755 34.887a.1.1 0 0 0 .007-.045c.113.016.157.122.234.183c-.114.014-.177-.064-.241-.138");
}

.bz_e48aon {
  fill: var(--svg-color--f8f805, #f8f805);
  d: path("M24.48 39.586c.101.008.106.079.104.154l-.064.058c-.073.038-.138-.013-.207-.02q-.073-.037-.061-.118c.019-.058.07-.053.115-.064z");
}

.c_r1_ab9e {
  fill: var(--svg-color--672808, #672808);
  d: path("M31.57 27.532c-.033-.122-.117-.226-.113-.358c.111.097.227.192.202.366c-.033.024-.062.024-.089-.008");
}

.c_swqy-5h {
  fill: var(--svg-color--202100, #202100);
  d: path("m17.654 36.726l-.05.046l-.197-.011l.051-.048z");
}

.c-9ltji_a {
  fill: var(--svg-color--261900, #261900);
  d: path("M25.753 37.733q.028.027.056.051q-.177.008-.356.014q-.026-.04.012-.072c.096-.011.192-.024.288.007");
}

.c0tbodjhl {
  fill: var(--svg-color--f9f905, #f9f905);
  d: path("M26.841 30.564a.1.1 0 0 0-.007.028c-.029.082.079.247-.128.224c-.096-.012-.262.074-.229-.146c.007-.105.077-.161.156-.212c.075.026.15.051.208.106");
}

.c1hf91qca {
  fill: var(--svg-color--edeb1b, #edeb1b);
  d: path("m13.352 31.895l-.051.146c-.095.02-.14-.058-.202-.1q-.003-.023-.008-.045l.054-.055q.126-.06.207.054");
}

.c2bx0-b-x {
  fill: var(--svg-color--c4ab46, #c4ab46);
  d: path("m16.481 26.26l-.041-.066c.503-.016 1-.087 1.508-.065a.6.6 0 0 1 .266.069q.008.025.009.049z");
}

.c2i239bff {
  fill: var(--svg-color--363600, #363600);
  d: path("M31.764 32.766c.002.093.007.185-.052.264c-.105-.091.016-.175.008-.262q.021-.038.044-.002");
}

.c2n4xxbyf {
  fill: var(--svg-color--1c3607, #1c3607);
  d: path("M17.612 39.99c.202-.023.343.154.534.168c.055.021.141-.005.141.096q-.031.035-.064.003c-.239-.009-.419-.152-.611-.267");
}

.c2y9wgble {
  fill: var(--svg-color--3a2a0b, #3a2a0b);
  d: path("M18.02 34.1c.086-.029.105.055.151.091q.03-.02.064-.008c.06.075.174.061.23.143c.022.064.02.123-.021.179c-.067.062-.14.047-.214.018c-.104-.05-.178-.16-.308-.155a.08.08 0 0 1-.022-.063a.45.45 0 0 1 .12-.205");
}

.c365o03dx {
  fill: var(--svg-color--b2b404, #b2b404);
  d: path("m12.982 31.535l.02-.104c.06.084.046.176.031.268c-.054-.043-.034-.108-.051-.164");
}

.c3pj0xbqf {
  fill: var(--svg-color--e2ecf9, #e2ecf9);
  d: path("M24.589 31.08c.089.01.144.051.148.142c.006.092-.055.145-.134.149c-.084.005-.145-.053-.147-.139c-.004-.086.051-.135.133-.152");
}

.c3xi2cb4n {
  fill: var(--svg-color--692221, #692221);
  d: path("M25.294 36.762c.058-.125.161-.184.293-.2c-.082.086-.163.18-.293.2");
}

.c5o004bnx {
  fill: var(--svg-color--ede66c, #ede66c);
  d: path("M28.556 31.531c.067-.067.162-.029.238-.065l.077.017q.036-.012.036.026l-.017.026q-.167 0-.334-.004");
}

.c5wrqx26b {
  fill: var(--svg-color--404405, #404405);
  d: path("M19.965 21.736c.053-.061.128-.048.197-.058c.097.002.092.058.067.125c-.089.056-.176.046-.265-.003l.007-.019q-.03-.013-.023-.028q.007-.017.017-.017");
}

.c5xm41blo {
  fill: var(--svg-color--111500, #111500);
  d: path("m29.821 24.861l-.007-.047l.097.006a.04.04 0 0 1 0 .047c-.031.026-.062.027-.09-.006");
}

.c6ci_lb6q {
  fill: var(--svg-color--e0e008, #e0e008);
  d: path("M26.987 30.448q.027.107.058.212q-.003.076-.002.151c-.225.074-.104-.179-.209-.219a.14.14 0 0 1-.044-.043c-.015-.027-.023-.056-.01-.087l.063-.064c.062-.022.095.038.144.05");
}

.c6hqs_3fy {
  fill: var(--svg-color--fefd01, #fefd01);
  d: path("m22.522 38.08l.01 2.872c0 .05.014.104-.051.13c-.123-.029-.115-.143-.116-.226c-.014-.856-.012-1.714-.004-2.57c.002-.1.01-.216.161-.206");
}

.c6ociabuo {
  fill: var(--svg-color--7d7a00, #7d7a00);
  d: path("m18.839 34.56l-.051.054l.002.002q-.012-.013-.021-.026l.008-.032l.033-.014z");
}

.c6t1aqujg {
  fill: var(--svg-color--3b3303, #3b3303);
  d: path("m17.606 34.36l.006-.055c.042-.014.083-.026.098-.076c.032.041.054.081.006.129c-.037.041-.073.013-.11.002");
}

.c6z3ambqe {
  fill: var(--svg-color--f2f110, #f2f110);
  d: path("m26.533 25.688l-.047.096l-.006.061c-.046-.022-.049-.067-.052-.111c.02-.051.066-.043.105-.046");
}

.c731pnb9c {
  fill: var(--svg-color--510302, #510302);
  d: path("m26.432 29.12l-.051.112c-.053-.099-.142-.204.051-.254q.06.073 0 .142");
}

.c868vek5q {
  fill: var(--svg-color--bfbfc0, #bfbfc0);
  d: path("m22.638 20.974l.007.515q.017.03-.007.057q-.037.012-.041-.025l-.008-.555q.029-.018.049.008");
}

.c8zut-ffm {
  fill: var(--svg-color--862221, #862221);
  d: path("M23.463 37.592c.058-.104.151-.113.257-.097c-.045.144-.165.084-.257.097");
}

.c91dl22by {
  fill: var(--svg-color--153407, #153407);
  d: path("M16.382 22.408c-.079.107-.171.192-.31.213c.023-.142.139-.178.252-.216q.033-.03.058.003");
}

.c95_92bwx {
  fill: var(--svg-color--372200, #372200);
  d: path("M27.563 26.291q-.844.008-1.689.012c-.086 0-.211.008-.113-.146l.041.01q.04.01.083.014c.447.006.895 0 1.342.003c.101 0 .202-.013.298.033c.03.015.04.041.038.074");
}

.c9k0fhbzc {
  fill: var(--svg-color--f6f605, #f6f605);
  d: path("M20.225 39.889q-.053.008-.105.013c-.09.005-.157-.085-.253-.059c-.089-.079-.214-.056-.309-.112l.003-.096c.24-.049.438.122.667.125c.098.047.066.09-.003.129");
}

.c9s-0ibmw {
  fill: var(--svg-color--f0ef1a, #f0ef1a);
  d: path("M29.2 26.859c.026-.039.066-.039.105-.032v.142l-.102.039z");
}

.ca4g-61zh {
  fill: var(--svg-color--003201, #003201);
  d: path("M15.913 29.938c.065.021.055.079.055.127l-.009 1.47c-.033.037-.065.074-.118.084c-.081.006-.148-.017-.192-.09c.002-.095.133-.102.133-.2c.02-.289.007-.578.007-.869c0-.265-.051-.304-.325-.272c-.144.016-.283.062-.425.088c-.108.019-.217.058-.326.01a.07.07 0 0 1-.042-.068c.101-.153.275-.137.421-.185c.272-.043.537-.165.821-.095");
}

.caavccclu {
  fill: var(--svg-color--150902, #150902);
  d: path("m27.466 30.764l-.031-.248c.053.012.07.046.073.096c-.006.052.007.111-.042.152");
}

.cc0vdnbci {
  fill: var(--svg-color--5d5e05, #5d5e05);
  d: path("m12.533 27.997l-.044-.048c-.007-.116.056-.21.097-.311c.048-.008.077 0 .053.058z");
}

.cc3orfbmx {
  fill: var(--svg-color--fdfd01, #fdfd01);
  d: path("m13.921 36.562l-.159-.243c-.012-.092.063-.145.097-.214c.128.024.202-.106.32-.11c.087-.027.149.021.217.061a.2.2 0 0 1 .063.079c.025.066.081.103.132.146c.046.047.079.104.12.154q.04.049.058.111c.021.079.094.108.149.154a.3.3 0 0 1 .074.113c.053.182.222.256.34.373c.146.104.278.221.365.379c.07.104.154.195.265.256l.063.023q.031.01.062.029a.3.3 0 0 1 .072.07c.034.053.07.107.136.125c.063.021.112.062.161.101a1 1 0 0 1 .119.106c.036.049.075.094.14.107c.077.023.125.08.171.139a.18.18 0 0 0 .133.065a.4.4 0 0 1 .156.056c.143.108.308.186.45.299c.043.05.089.098.158.109a.3.3 0 0 1 .084.051c.083.082.197.082.301.113a.9.9 0 0 1 .32.138a.33.33 0 0 0 .256.137c.096.036.183.089.285.106c.082.026.161.069.253.057c.072 0 .137.025.197.059c.132.076.282.102.417.164c.072.007.146.004.216.021q.05.015.101.045c.094.063.2.036.302.043q.072.001.14-.004c.047-.005.093-.014.139 0c.051.029.097.066.152.086c.148.041.303-.009.447.043a.2.2 0 0 1 .06.049c0 .14-.007.281.001.421c.009.116-.047.142-.146.13c-.104-.05-.197.046-.3.021a.54.54 0 0 1-.256-.071c-.104-.049-.216-.024-.324-.029h-.188q-.076 0-.151-.005l-.072-.01c-.093-.026-.188-.039-.281-.061a3 3 0 0 1-.165-.055l-.092-.041c-.061-.028-.125-.046-.188-.066a1.3 1.3 0 0 0-.328-.059c-.088-.021-.168-.061-.252-.09l-.058-.033a.33.33 0 0 0-.234-.082a.1.1 0 0 1-.057-.033c-.034-.122-.179-.067-.239-.149c-.135-.062-.254-.163-.413-.158c-.046-.104-.188-.091-.236-.19l-.055-.012c-.075.004-.126-.033-.161-.097c-.142.022-.207-.11-.313-.156a5.6 5.6 0 0 1-.871-.595c-.047-.038-.091-.076-.155-.074q-.063-.078-.128-.154c-.105-.007-.142-.12-.23-.151a.45.45 0 0 0-.208-.207c-.132-.086-.229-.209-.348-.312q-.005-.027-.013-.052c-.117-.079-.233-.159-.293-.296c-.109-.036-.14-.156-.227-.217c-.069-.076-.14-.148-.188-.24c-.112-.166-.212-.339-.363-.473");
}

.cc8arob7u {
  fill: var(--svg-color--4c1600, #4c1600);
  d: path("M25.659 22.518a.23.23 0 0 1 .21.095c-.092.016-.166-.01-.21-.095");
}

.cezrjcu2y {
  fill: var(--svg-color--50530d, #50530d);
  d: path("M13.04 28.509a1.3 1.3 0 0 1-.1.423c-.112-.16.021-.285.063-.423l.018-.015z");
}

.cfjphubye {
  fill: var(--svg-color--e30604, #e30604);
  d: path("M22.587 41.03c.094-.071.199-.063.304-.05c-.068.127-.19.086-.299.096q-.008-.022-.005-.046");
}

.cg6az_d6k {
  fill: var(--svg-color--e2db64, #e2db64);
  d: path("m28.28 26.15l.205.002c-.074.074-.164.041-.248.039z");
}

.cgphdtbms {
  fill: var(--svg-color--171500, #171500);
  d: path("M15.865 29.693c.033.063.063.004.094-.003c.031.067-.029.103-.051.153c-.046-.026-.087-.066-.146-.051q-.018-.017-.01-.031q.006-.015.013-.016c.033-.015.067-.035.1-.052");
}

.ch_13xbzw {
  fill: var(--svg-color--473610, #473610);
  d: path("m30.439 36.574l-.168.494c-.058-.057-.049-.142-.092-.204a.2.2 0 0 1-.031-.093a.1.1 0 0 1 .051-.08c.072-.033.108-.111.184-.14a.05.05 0 0 1 .056.023");
}

.ch2xcs5-w {
  fill: var(--svg-color--891b17, #891b17);
  d: path("M29.386 25.891q.008-.095.013-.191l.108-.015v.019c.036.068.12.131.031.217c-.058.02-.109.018-.152-.03");
}

.cj7j7_7ru {
  fill: var(--svg-color--eaeb60, #eaeb60);
  d: path("M23.352 40.719v.048l-.301-.005l.011-.045l.129-.054c.045.039.122-.011.161.056");
}

.cjdenligf {
  fill: var(--svg-color--5a5c07, #5a5c07);
  d: path("M30.674 31.28c-.119.074-.258.076-.393.098c0-.066.06-.078.099-.107c.097.014.199-.101.294.009");
}

.cjgo9ob2f {
  fill: var(--svg-color--161600, #161600);
  d: path("m18.42 35.07l-.021.003h-.021h.002l-.02-.024l.01-.029q.016-.007.027-.014l.03.012z");
}

.ck0slqbei {
  fill: var(--svg-color--500000, #500000);
  d: path("m22.325 20.555l-.006.121c-.094.069-.191.061-.29.012q-.054-.05-.026-.117l.021-.008z");
}

.ck532ybds {
  fill: var(--svg-color--e9ea10, #e9ea10);
  d: path("M14.289 31.26c.188 0 .356.122.549.103c.148 0 .291.032.434.072c.127.048.276-.009.392.091l.202.059l-.005.015c.061.077.012.101-.056.115l-.067-.005a.8.8 0 0 0-.233.008a1 1 0 0 0-.233.01c-.122-.003-.226-.072-.344-.087c-.104-.039-.214-.036-.322-.046a.4.4 0 0 1-.072-.015c-.07-.021-.143-.034-.214-.058a.6.6 0 0 0-.317-.07a.64.64 0 0 1-.4-.102a1.3 1.3 0 0 0-.311-.109a1 1 0 0 1-.25-.085a.2.2 0 0 1-.077-.087c-.017-.057-.014-.105.036-.144l.713.188c.193.04.402.021.575.147");
}

.ck9o35t5i {
  fill: var(--svg-color--fefc04, #fefc04);
  d: path("m27.26 29.688l.068.001c.081.062.055.13.014.201c-.053-.005-.118.032-.149-.046c.004-.062.004-.122.067-.156");
}

.ckmvh9m8l {
  fill: var(--svg-color--a69f1e, #a69f1e);
  d: path("M17.72 29.424c-.048.017-.061.057-.065.101c-.068-.051-.063-.125-.011-.166c.046-.037.062.029.076.065");
}

.ckzxyac0f {
  fill: var(--svg-color--f0f00e, #f0f00e);
  d: path("M18.607 22.403c-.04.074-.123.028-.176.064c-.221.146-.44.288-.712.317c-.051-.029-.067-.076-.067-.13q.02-.049.043-.097c.088.022.162-.03.243-.052a.1.1 0 0 1 .032-.001c.062-.048.117-.101.192-.123a.35.35 0 0 0 .148-.122q.095-.008.193-.019c.041-.039.083-.078.146-.043a.2.2 0 0 1 .055.124c-.008.058-.051.072-.097.082");
}

.cl90v6bgw {
  fill: var(--svg-color--1a1600, #1a1600);
  d: path("M18.275 35.18a.2.2 0 0 1-.002.043q-.026.004-.053.006l.005.004l-.021-.026l.014-.031q.032-.022.059.007z");
}

.cmbkg9bxw {
  fill: var(--svg-color--9d2723, #9d2723);
  d: path("m17.05 29.883l.002-.289l.039-.002l.002.296h-.022z");
}

.cmttbebna {
  fill: var(--svg-color--c2c008, #c2c008);
  d: path("m24.981 34.564l.023-.067l.077.028a.05.05 0 0 0 .031.035l-.003.033v.035a.1.1 0 0 1-.067-.007l-.052-.009a.2.2 0 0 0-.009-.048");
}

.cmwuzsbwd {
  fill: var(--svg-color--eaec4f, #eaec4f);
  d: path("m22.17 25.541l.007.033v.029a.2.2 0 0 1-.033.083a.1.1 0 0 1-.049.032q-.05.01-.084-.025c.024-.09-.064-.103-.099-.15z");
}

.cnnjb4bwq {
  fill: var(--svg-color--4e4d00, #4e4d00);
  d: path("M28.3 38.459c.091-.114.154-.26.334-.257c-.007.145-.197.156-.216.294c-.044.005-.089.005-.118-.037");
}

.cns6cu5ug {
  fill: var(--svg-color--ebec13, #ebec13);
  d: path("M12.184 30.16c-.072.139-.211.21-.322.307c-.122.004-.099-.08-.092-.154c.075-.064.159-.118.203-.212l.043-.056q.051.026.104.056a.08.08 0 0 1 .064.059");
}

.coyuwh1dg {
  fill: var(--svg-color--213c0d, #213c0d);
  d: path("M17.353 37.545v.044c-.21-.003-.425.029-.614-.104q-.03-.037.008-.069c.135-.043.265.01.396.023c.074.027.161.03.21.106");
}

.cp1slsbzt {
  fill: var(--svg-color--f2f402, #f2f402);
  d: path("M29.66 25.936c-.053.063-.094.146-.201.115l-.062-.063c-.023-.014-.052-.023-.063-.052q0-.03.029-.041l.021-.004l.169-.021l.105.023q.003.02.002.043");
}

.cp6prge7r {
  fill: var(--svg-color--632b16, #632b16);
  d: path("M26.507 38.715c-.054.055-.108.11-.195.099c.024-.113.108-.111.195-.099");
}

.cq0ur2b0l {
  fill: var(--svg-color--1a3b0d, #1a3b0d);
  d: path("M12.688 34.801a.44.44 0 0 1 .104.221c-.148-.02-.096-.135-.104-.221");
}

.cqhy3bcdh {
  fill: var(--svg-color--c5c619, #c5c619);
  d: path("M18.526 35.24q-.061-.03-.125-.058q-.012.035-.047.018a.1.1 0 0 1-.036-.046a.1.1 0 0 1 .021-.054l.06-.066a.2.2 0 0 1 .046-.041a.2.2 0 0 1 .125-.017a.12.12 0 0 1 .081.053c.027.062.001.112-.035.159a.14.14 0 0 1-.09.052");
}

.cqw4c2zti {
  fill: var(--svg-color--bd110e, #bd110e);
  d: path("m18.17 30.04l-.007-.039a.1.1 0 0 0 .007-.045c.048-.015.104-.09.143.002c.029.07.01.135-.084.148q-.03-.03-.059-.066");
}

.cr9343bos {
  fill: var(--svg-color--f2f261, #f2f261);
  d: path("M21.921 25.07q-.004.024-.003.049a.2.2 0 0 1-.05.007l.007-.257q.018 0 .034-.003z");
}

.cra2wmb6x {
  fill: var(--svg-color--fbf81d, #fbf81d);
  d: path("M19.08 34.507h-.032l-.021-.025l.019-.026q.018.01.041.008a.04.04 0 0 1-.007.042");
}

.crvxk7bjy {
  fill: var(--svg-color--250c0b, #250c0b);
  d: path("m18.538 32.35l.038.01l.02.203c-.019.001-.031.09-.051.01c-.017-.072-.007-.149-.007-.223");
}

.csidll8oh {
  fill: var(--svg-color--0a0a02, #0a0a02);
  d: path("M12.07 31.28h.037c.055.044.033.099.019.152l-.009.156c-.1-.09-.039-.204-.047-.308");
}

.csz1b8bzz {
  fill: var(--svg-color--eef15b, #eef15b);
  d: path("M15.656 32.3c-.056.008-.125-.025-.159.049l-.106-.005l-.005-.089c.092.003.192-.041.27.045");
}

.ct99vls8m {
  fill: var(--svg-color--444506, #444506);
  d: path("M31.15 35.463c-.058-.109-.143-.208-.149-.34q.018-.005.034-.013a.17.17 0 0 1 .13.059a.07.07 0 0 1-.006.069q-.003.113-.009.225");
}

.ctmlhzb9i {
  fill: var(--svg-color--dbdb02, #dbdb02);
  d: path("m17.919 24.877l-.007.05c-.046.05-.038.132-.105.168c-.034.011-.065.008-.091-.021v-.2z");
}

.ctupxn4ws {
  fill: var(--svg-color--dada12, #dada12);
  d: path("m28.18 32.559l.212.007l.008.024l-.022.012l-.23.002z");
}

.ctwnnpb2m {
  fill: var(--svg-color--535400, #535400);
  d: path("m29.31 24.7l-.052-.084c.13.017.271.007.346.147c-.111.031-.201-.024-.294-.063");
}

.cul4o_bld {
  fill: var(--svg-color--e3e40e, #e3e40e);
  d: path("m31.965 30.1l.059.004c.079.041.096.131.148.192l.061.028c.036.011.06.034.064.075a.2.2 0 0 1-.046.095c-.107.072-.175-.025-.257-.059c-.199-.139-.419-.24-.633-.352c-.067-.055-.133-.113-.222-.134q-.033-.012-.064-.026c-.048-.032-.104-.059-.09-.133c.039-.048.095-.061.15-.076c.076-.018.151.004.229 0a.3.3 0 0 1 .119.053a.37.37 0 0 0 .195.103q.067.016.12.06c.064.049.111.113.167.17");
}

.culn5hc0n {
  fill: var(--svg-color--5d5d1f, #5d5d1f);
  d: path("M31.05 32.917c.038-.157.002-.339.144-.465c.039.029.032.065.015.104c-.062.115-.026.257-.107.364q-.03.04-.052-.003");
}

.cv245e38i {
  fill: var(--svg-color--fdfc21, #fdfc21);
  d: path("m18.428 34.918l.051-.05l.021.021v.027l-.021.02a.05.05 0 0 1-.05-.016z");
}

.cvbk8u71e {
  fill: var(--svg-color--1c2a16, #1c2a16);
  d: path("M17.04 35.438c-.106-.041-.12-.193-.248-.21q-.024-.012-.017-.026t.013-.013a.4.4 0 0 0 .043-.052q-.027-.038.01-.065l.243.361q-.019.04-.044.005");
}

.cwh728cwp {
  fill: var(--svg-color--4b4502, #4b4502);
  d: path("m17.703 25.17l.012-.05c.113-.06.231-.026.349-.013c-.103.126-.241.044-.361.063");
}

.cwkj5sghy {
  fill: var(--svg-color--d7d51c, #d7d51c);
  d: path("m25.21 35.785l-.115.012a.65.65 0 0 1-.205-.207a.1.1 0 0 1 .058-.037c.063-.014.116.013.167.045c.04.025.079.05.105.09q.023.053-.01.097");
}

.cwx0f-0hq {
  fill: var(--svg-color--2d2d00, #2d2d00);
  d: path("m21.717 25.793l-.063.086c-.039-.101-.011-.161.099-.176z");
}

.cx95vubdg {
  fill: var(--svg-color--9f0807, #9f0807);
  d: path("m26.384 24.852l.046.016l.009.151c-.031.041.029.185-.112.104c-.072-.083-.054-.171 0-.255a.4.4 0 0 1 .057-.016");
}

.cxnte9bla {
  fill: var(--svg-color--f4f15d, #f4f15d);
  d: path("M28.375 29.13c-.071-.025-.16.019-.219-.057c.106.02.231-.053.32.059z");
}

.cy-z_-5dq {
  fill: var(--svg-color--fcfc01, #fcfc01);
  d: path("m22.309 38.1l.016 2.868q-.02.016-.045.01c-.017.007-.031.019-.048.021c-.484.034-.489.031-.489-.452q-.003-1.05 0-2.103c0-.11-.015-.224.044-.327c.17-.104.345-.085.522-.017");
}

.cy99v7bvm {
  fill: var(--svg-color--1c4e12, #1c4e12);
  d: path("M15.764 35.434q.027 0 .056.004c-.06.121-.135.131-.37.053c.105-.022.201-.079.314-.057");
}

.cyerltstq {
  fill: var(--svg-color--413c06, #413c06);
  d: path("m18.216 25.894l.014.198a.05.05 0 0 1 .015.038q-.003.023-.009.023a.1.1 0 0 1-.063.015a.17.17 0 0 1-.087-.102a.3.3 0 0 1-.012-.068q0-.053.026-.098a.1.1 0 0 1 .058-.033q.033 0 .058.027");
}

.cynyr7b8s {
  fill: var(--svg-color--2f3200, #2f3200);
  d: path("M16.688 35.02q-.225.088-.464.094v-.021c.118-.112.322-.014.421-.169q.032-.021.06.006c.014.034.012.065-.017.09");
}

.czrf91blx {
  fill: var(--svg-color--282b00, #282b00);
  d: path("m15.05 23.798l-.002-.056a.1.1 0 0 0 .01-.038q.016-.042.03 0v-.002c.005.04.016.081-.038.096");
}

.d_g98ybmb {
  fill: var(--svg-color--252322, #252322);
  d: path("M16.27 32.672c.014.168-.01.339.055.5q-.017.03-.045.005c-.078-.163-.092-.34-.097-.518c.034-.024.064-.026.087.013");
}

.d_j70abxz {
  fill: var(--svg-color--e8e11f, #e8e11f);
  d: path("m24.48 40.476l.002.133l-.104.04l-.005-.139l.005-.033c.033-.056.068-.053.102-.001");
}

.d_y63gbou {
  fill: var(--svg-color--eded10, #eded10);
  d: path("m14.634 27.17l.105-.103c.055-.044.104.009.156.007l.864.358c.041.05.117.06.139.129q.031.141-.11.174c-.097.014-.171-.038-.245-.089a.7.7 0 0 0-.26-.102c-.125-.038-.234-.105-.349-.161c-.068-.043-.147-.066-.218-.105c-.041-.026-.077-.055-.082-.108");
}

.d--1u0b4k {
  fill: var(--svg-color--371106, #371106);
  d: path("m16.476 26.09l.003.051q.002.03.007.06q0 .03-.004.06v.029c-.082.008-.099-.046-.102-.11c-.005-.069.043-.083.096-.09");
}

.d1qwjhbea {
  fill: var(--svg-color--434327, #434327);
  d: path("M27.865 33.708c-.071-.156-.033-.286.102-.39a.9.9 0 0 1-.102.39");
}

.d27pkdgfd {
  fill: var(--svg-color--3f3f06, #3f3f06);
  d: path("M13.798 26.669c-.153.096-.243-.008-.337-.104a.4.4 0 0 1 .337.104");
}

.d28hnmb9w {
  fill: var(--svg-color--6d0702, #6d0702);
  d: path("M30.845 30.711c-.087.006-.159-.016-.203-.1c.082.005.178-.023.203.1");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d44s53baa {
  fill: var(--svg-color--c9c589, #c9c589);
  d: path("m18.275 35.18l.054.005l-.056.038q-.015-.015-.01-.029q.006-.014.012-.014");
}

.d5zs6nbgk {
  fill: var(--svg-color--f3f006, #f3f006);
  d: path("m29.25 37.943l-.154.119c-.127.15-.27.284-.413.421c-.072.067-.143.14-.256.093a.13.13 0 0 1-.038-.062c-.008-.156.137-.216.204-.324a2.5 2.5 0 0 1 .271-.268a.6.6 0 0 0 .236-.224c.084-.108.171-.214.271-.31c.08-.046.145-.118.231-.151a.2.2 0 0 1 .137.012c.077.092-.007.16-.036.235l.003-.005c-.16.148-.323.292-.456.464");
}

.d6tnt27co {
  fill: var(--svg-color--efee66, #efee66);
  d: path("M28.13 36.552c.076-.06.166-.033.25-.043c.015.013.084.026.021.043c-.086.021-.18.001-.271 0");
}

.d6ys1ybvo {
  fill: var(--svg-color--ecf4f9, #ecf4f9);
  d: path("M21.711 30.506c-.086.012-.17.036-.221-.067c-.032-.067-.012-.127.033-.161c.079-.058.161-.029.231.029c.061.084.041.148-.043.199");
}

.d7jafuhiu {
  fill: var(--svg-color--5c5e08, #5c5e08);
  d: path("m19.459 39.742l.099-.012c.133-.043.246-.022.335.092a.13.13 0 0 1-.026.119c-.111-.119-.314-.043-.408-.199");
}

.d7ozqhlnx {
  fill: var(--svg-color--dbdb15, #dbdb15);
  d: path("M26.27 29.641c-.123 0-.055.146-.137.178c-.095-.006-.034-.121-.118-.154c-.069.061-.031.148-.041.224q-.025-.002-.051-.002l.007-.274c.114-.009.233-.067.34.028");
}

.d7sg32hsr {
  fill: var(--svg-color--4e510d, #4e510d);
  d: path("M14.732 24.907a.2.2 0 0 1 .002-.048q-.007-.02.003-.041c.088.029.175-.12.264-.002c-.058.079-.166.038-.229.104c-.019.017-.033.016-.04-.013");
}

.d8m-1eriu {
  fill: var(--svg-color--fdfc01, #fdfc01);
  d: path("M29.711 30.16c-.002.042-.013.08-.056.1a.2.2 0 0 1-.064.043a.3.3 0 0 1-.154 0c-.065-.02-.128-.046-.163-.111c-.008-.066-.032-.144.081-.139h.043c.114.007.241-.022.313.107");
}

.d9hpr3boi {
  fill: var(--svg-color--143500, #143500);
  d: path("m16.688 36.35l-.053.034q-.007.057-.046.015c-.115-.068-.242-.037-.365-.049c-.039-.05-.118.005-.152-.056l.001-.047c.211-.002.418.01.615.103");
}

.da17pdb4r {
  fill: var(--svg-color--fafa02, #fafa02);
  d: path("m17.562 30.424l.051-.072c.099-.192.271-.061.406-.092q.044.01.074.039l.031.162l.005.103c.018.176-.007.282-.238.263c-.173-.015-.108-.127-.142-.202c-.043-.031-.08-.069-.121-.101a.3.3 0 0 1-.05-.041a.07.07 0 0 1-.016-.059");
}

.dah5h4b-a {
  fill: var(--svg-color--c5c619, #c5c619);
  d: path("m18.339 35.17l.063.014c.048.157-.118.168-.174.253c-.044.02-.074-.002-.102-.033a.1.1 0 0 1-.017-.052a.14.14 0 0 1 .026-.047q.028-.026.053-.056a.2.2 0 0 1 .077-.067a.2.2 0 0 1 .049-.015z");
}

.dato3cb9k {
  fill: var(--svg-color--211816, #211816);
  d: path("M21.303 35.428a.2.2 0 0 1 .004-.05c.085.01.182-.024.256.053q-.13 0-.26-.003");
}

.dbnkg6b8r {
  fill: var(--svg-color--e7e862, #e7e862);
  d: path("M27.507 36.653c.059-.056.135-.029.202-.046q.073-.057.145.005c-.107.091-.229.044-.347.041");
}

.dc190ev2h {
  fill: var(--svg-color--807f1a, #807f1a);
  d: path("m27.635 34.454l.003-.002c.099.048.208.084.232.212c-.112-.032-.26-.024-.235-.21");
}

.dc3et_b2e {
  fill: var(--svg-color--171700, #171700);
  d: path("M18.523 34.971h-.044h.002q-.02-.016-.013-.034q.005-.018.013-.018h-.002q.03-.027.055.001l-.003-.003l-.008.053");
}

.dd_lpybgs {
  fill: var(--svg-color--171700, #171700);
  d: path("m18.625 34.867l-.021.003l-.021-.002l.001.002l-.02-.036q.013-.017.028-.031l.034.021a.05.05 0 0 1-.001.043");
}

.dd6a4lp5b {
  fill: var(--svg-color--f6f60a, #f6f60a);
  d: path("M30.529 31.08a.07.07 0 0 0 .048-.017c.06-.003.104-.072.173-.041c.036.041.044.091.043.144a.3.3 0 0 1-.017.073a.13.13 0 0 1-.082.072c-.108-.007-.218.015-.327.004c-.066-.03-.156-.033-.15-.142c.069-.148.216-.038.312-.093");
}

.de96vycwy {
  fill: var(--svg-color--202000, #202000);
  d: path("m15.969 37.839l.061.058l-.059-.014a.1.1 0 0 0-.002-.044");
}

.dea8n3_ly {
  fill: var(--svg-color--f3f315, #f3f315);
  d: path("M18.38 40.1a.45.45 0 0 1 .295.097l.015.01c.029.065-.008.106-.055.144l-.099.006l-.248-.106l-.142-.089q.092-.032.183-.066q.029-.031.051.004");
}

.dehnn1bnh {
  fill: var(--svg-color--434409, #434409);
  d: path("M27.26 29.688c-.021.053.003.125-.067.156q-.017.003-.036.001c-.006-.079-.053-.183.103-.157");
}

.desrn3b7c {
  fill: var(--svg-color--2f2d00, #2f2d00);
  d: path("m14.996 34.768l-.051-.042l.15-.063l.146.003c-.061.084-.161.074-.245.102");
}

.dez406hmo {
  fill: var(--svg-color--747300, #747300);
  d: path("M28.897 31.589c.049-.003.092.005.115.056q.004.03-.023.043c-.054-.006-.121.025-.154-.048z");
}

.df1cq-rzw {
  fill: var(--svg-color--414101, #414101);
  d: path("M15.865 29.693c.005-.092-.002-.186.015-.275c.028-.148-.027-.24-.162-.293c.02-.069.067-.089.135-.079c.063.021.078.079.106.13v.515c-.015.029-.033.061-.07.056c-.027-.004-.034-.027-.024-.054");
}

.dfmplcbqq {
  fill: var(--svg-color--ebef63, #ebef63);
  d: path("M19.459 37.829c.171-.05.34-.077.504.018z");
}

.dg62vccdl {
  fill: var(--svg-color--5c1a09, #5c1a09);
  d: path("m27.05 22.1l-.214-.156q-.032-.034.005-.062c.159.01.263.113.37.212a.1.1 0 0 1-.06.044c-.041.005-.075-.005-.101-.038");
}

.dgjcvkbbp {
  fill: var(--svg-color--cdcf14, #cdcf14);
  d: path("m18.14 35.38l.092.06a.3.3 0 0 1-.138.145l-.117-.046l-.007-.004a.05.05 0 0 1-.013-.052a.15.15 0 0 1 .053-.064a.2.2 0 0 1 .049-.028a.1.1 0 0 1 .055-.013z");
}

.dhfhj7bhh {
  fill: var(--svg-color--6c0904, #6c0904);
  d: path("m22.929 26.17l.013-.063c.035-.005.074-.005.084.033c.017.061-.036.087-.077.115l-.017-.065z");
}

.dj8c-odet {
  fill: var(--svg-color--1b1900, #1b1900);
  d: path("M25.672 39.38c.055-.096.124-.164.245-.138l-.005.024a.45.45 0 0 1-.24.114");
}

.djuocebiz {
  fill: var(--svg-color--3f3b08, #3f3b08);
  d: path("M30.847 32.727q.03.041.056.084c-.015.053-.006.115-.056.154z");
}

.dk7l-ubxt {
  fill: var(--svg-color--232400, #232400);
  d: path("m15.765 25.541l-.001.031c-.122-.057-.274-.061-.358-.191l-.002.003c.11-.075.217-.02.324.013c.053.037.079.082.037.144");
}

.dkupljp2l {
  fill: var(--svg-color--274114, #274114);
  d: path("M14.13 24.467c-.053.068-.028.199-.161.203c.016-.097.019-.203.161-.203");
}

.dl9u4cb0z {
  fill: var(--svg-color--545008, #545008);
  d: path("M16.529 38.29a.24.24 0 0 1 .175.118c-.109.036-.151-.026-.175-.118");
}

.dlcjw3bbj {
  fill: var(--svg-color--c4c311, #c4c311);
  d: path("M15.764 31.735a.1.1 0 0 0-.007-.038c.058-.008.104-.027.104-.099c.06.115.049.129-.097.137");
}

.dodpsl1pw {
  fill: var(--svg-color--dee15c, #dee15c);
  d: path("m20.751 40.705l.188.016l.016.039c-.088 0-.184.034-.263-.038q.029-.01.059-.017");
}

.dpo8h6qom {
  fill: var(--svg-color--fcfb03, #fcfb03);
  d: path("m24.07 40.711l-.009-.11a.06.06 0 0 1 .014-.058c.056-.045.123-.012.183-.026q.058-.002.115-.007c.049.045.044.091.005.139c-.066.032-.156-.01-.206.066z");
}

.dpw-l-bis {
  fill: var(--svg-color--f1f35d, #f1f35d);
  d: path("M23.07 39.954a25 25 0 0 1-.474-.007c-.002-.072.063-.044.097-.063q.128.004.255.004c.04-.031.082-.043.132-.023a.08.08 0 0 1 .038.055q-.008.037-.048.034");
}

.dqa3mrb6s {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 10H22v44h32c6.627 0 10-4.925 10-11V21c0-6.075-3.373-11-10-11");
}

.ds2_vrb0i {
  fill: var(--svg-color--666506, #666506);
  d: path("m16.476 26.09l.058-.054c.119-.033.243-.007.364-.015c.076.008.166-.038.222.054c.007.046-.005.086-.051.108c-.192.021-.385.038-.577-.013q-.04-.034-.016-.08");
}

.ds7elwmqm {
  fill: var(--svg-color--ecda66, #ecda66);
  d: path("M23.601 21.884c-.049-.07-.128-.029-.19-.046l-.017-.037c.093.015.216-.076.264.08z");
}

.ds9b5qrxv {
  fill: var(--svg-color--501f06, #501f06);
  d: path("m26.23 34.26l.056-.062c.097-.016.142.06.199.113c.021.088-.026.129-.103.15l-.042-.004c-.081-.041-.178-.074-.11-.197");
}

.dtmgbhw-m {
  fill: var(--svg-color--757405, #757405);
  d: path("M31.912 31.949c.01.061.003.118-.046.162c-.093-.072-.045-.149-.009-.227q.053.013.055.065");
}

.dts5m6_dv {
  fill: var(--svg-color--561e0a, #561e0a);
  d: path("m27.13 22.11l.084-.018c.106 0 .152.056.147.159c-.07-.019-.13-.075-.21-.05q-.05-.035-.021-.091");
}

.dubvqcc2r {
  fill: var(--svg-color--e4e920, #e4e920);
  d: path("M20.07 40.663v.093c-.04.009-.076.002-.103-.032l.052-.161l.056.002q.042.051-.005.098");
}

.dun2ktbfv {
  fill: var(--svg-color--f1f108, #f1f108);
  d: path("M14.893 36.37c.063.161.225.248.307.396c.042.07.114.128.084.225a.1.1 0 0 1-.048.052c-.162.011-.21-.129-.292-.225l-.058-.113c-.061-.047-.144-.077-.149-.174l-.05-.077c-.02-.064.014-.104.066-.132c.056-.013.108-.015.14.048");
}

.dv9e5s-3h {
  fill: var(--svg-color--636425, #636425);
  d: path("M18.48 34.92v.052h-.051l-.002-.052z");
}

.dvcp_bsmc {
  fill: var(--svg-color--737909, #737909);
  d: path("m12.215 29.12l.051.053c.01.063.02.124-.041.169c-.096-.07-.058-.146-.01-.222");
}

.dvnqcedop {
  fill: var(--svg-color--162b01, #162b01);
  d: path("m13.865 32.21l.001.044c-.272-.007-.52-.105-.766-.2c-.033-.03-.034-.064-.019-.103c.093-.056.163.033.249.036c.138.057.299.051.41.171c.028.05.084.034.125.052");
}

.dvnscbb_h {
  fill: var(--svg-color--451502, #451502);
  d: path("m17.15 24.563l-.013.202c-.127-.045-.079-.127-.041-.205q.003-.052.003-.104l.098.01q-.022.05-.047.097");
}

.dvr07yctg {
  fill: var(--svg-color--d8dac1, #d8dac1);
  d: path("M31.96 30c-.055-.095-.033-.202-.038-.304c.087.092.033.202.038.304");
}

.dvxnesbpc {
  fill: var(--svg-color--193605, #193605);
  d: path("M16.33 35.33c-.14.186-.342.067-.511.105q-.03.022-.056-.004l.007-.037l.443-.069c.04-.023.08-.026.117.005");
}

.dwd7s3-8l {
  fill: var(--svg-color--743e2e, #743e2e);
  d: path("M22.274 25.02c.008-.054-.012-.116.051-.149q0 .089-.003.178c-.002.008-.021.013-.033.02z");
}

.dwn802d4a {
  fill: var(--svg-color--e7f0fa, #e7f0fa);
  d: path("M21.878 28.12c.025-.099.069-.142.166-.13c.084.01.127.059.124.131c-.004.083-.057.139-.151.136c-.098-.004-.119-.074-.139-.137");
}

.dy14d0czc {
  fill: var(--svg-color--6b0909, #6b0909);
  d: path("M25.799 36.35a.75.75 0 0 1 .34-.31a.6.6 0 0 1-.34.31");
}

.dy57j5bun {
  fill: var(--svg-color--0d2c03, #0d2c03);
  d: path("M18.836 21.17c.32-.181.684-.217 1.032-.304c.041-.01.082.015.106.053c-.01.11-.1.095-.171.114a.3.3 0 0 0-.138.043a.64.64 0 0 1-.288.063c-.049 0-.097.017-.143.031c-.11.033-.219.079-.339.048a.14.14 0 0 1-.059-.048");
}

.dy64reb_s {
  fill: var(--svg-color--555501, #555501);
  d: path("M17.16 25.569c-.172-.151-.378-.041-.565-.067a.06.06 0 0 1-.063-.008l.007-.016q-.023-.052.027-.078c.508-.07 1.016-.05 1.525-.015c.048.021.081.054.091.106l-.012.104q-.005.017-.013.031a.07.07 0 0 1-.063.024a.2.2 0 0 1-.084-.058c-.165-.078-.332-.044-.498-.016a1 1 0 0 1-.178.022c-.059.005-.122.017-.174-.029");
}

.dysr8sg7u {
  fill: var(--svg-color--dadc25, #dadc25);
  d: path("m18.675 35.38l-.091.117l-.007-.019c-.083-.058-.088-.132-.044-.217l-.007-.02l.058-.071c.108-.006.103.082.123.146a.08.08 0 0 1-.032.064");
}

.dyua5fzdx {
  fill: var(--svg-color--52521d, #52521d);
  d: path("M31.815 29.398c-.084-.09-.048-.206-.064-.31c0-.044-.048-.113.053-.108c-.019.138.105.277.011.418");
}

.dz_i0acfz {
  fill: var(--svg-color--ebec44, #ebec44);
  d: path("M29.04 36.463q.014.018.012.038l-.029-.023z");
}

.dz8f39bza {
  fill: var(--svg-color--c20101, #c20101);
  d: path("m26.28 29.886l.008-.197c.122-.203.137-.015.186.05l.004.102c-.062.037-.124.066-.198.045");
}

.dzjabcbbz {
  fill: var(--svg-color--63300a, #63300a);
  d: path("M30.834 35.893q.007.04.011.079c0 .08.002.162-.104.183q-.058-.013-.072-.069c.02-.095.05-.182.165-.193");
}

.dzq1-najq {
  fill: var(--svg-color--eef445, #eef445);
  d: path("m14.999 23.746l-.051.052z");
}

.e_gqfla8k {
  fill: var(--svg-color--002900, #002900);
  d: path("M14.289 31.26c-.186-.073-.396-.049-.577-.147l.003-.036l.564.094c.116.017.023.058.01.089");
}

.e-id8hbja {
  fill: var(--svg-color--807f19, #807f19);
  d: path("M17.16 36.719c.097-.09.194-.072.294-.006a.1.1 0 0 1-.051.048c-.084.005-.171.027-.243-.042");
}

.e1yu0gevo {
  fill: var(--svg-color--eeee13, #eeee13);
  d: path("M20.04 21.904c-.034.073-.14.015-.173.092l-.051.013a2 2 0 0 1-.391.112c-.067-.051-.036-.113-.023-.173l.048-.102l.277-.007c.076.002.127-.072.202-.072a.2.2 0 0 1 .062.02q.046.048.049.117");
}

.e2ahsdblx {
  fill: var(--svg-color--ded90f, #ded90f);
  d: path("M18.221 34.469a.26.26 0 0 0 .212.043l.025.023c.047.077.054.166.061.253a.2.2 0 0 1-.012.065a.2.2 0 0 1-.058.077a.3.3 0 0 1-.053.034a.3.3 0 0 1-.092.033a.3.3 0 0 1-.067-.008c-.14-.041-.245-.115-.246-.281a.1.1 0 0 1 .024-.058c.026-.02.058-.026.09-.034c.045-.017.06-.058.076-.098a.2.2 0 0 1 .04-.049");
}

.e2u-we6nq {
  fill: var(--svg-color--332809, #332809);
  d: path("m26.07 34.26l-.072-.062c.089-.034.02-.204.154-.188c.107.01.05.147.125.191c.015.05-.015.074-.054.093a.16.16 0 0 1-.153-.034");
}

.e3m3iubji {
  fill: var(--svg-color--173a02, #173a02);
  d: path("m15.35 32.563l.058-.003c.136.005.279-.024.404.061c-.166.076-.322.071-.462-.058");
}

.e3rrtvbfr {
  fill: var(--svg-color--2b2c00, #2b2c00);
  d: path("M16.224 35.09v.021c-.113.034-.202.202-.347.063c.102-.086.224-.091.347-.084");
}

.e4aeisb6e {
  fill: var(--svg-color--523432, #523432);
  d: path("M18.783 36.831c.143-.044.238-.003.262.156c-.091-.048-.192-.077-.262-.156");
}

.e4hba-b1c {
  fill: var(--svg-color--61630e, #61630e);
  d: path("m24.372 37.574l.106-.028c.072.099.176.019.262.048q.022.035-.002.069a.53.53 0 0 1-.263.02c-.039-.06-.132.001-.161-.075c0-.004.039-.022.058-.034");
}

.e4ykz3bsm {
  fill: var(--svg-color--5d5f00, #5d5f00);
  d: path("m25.25 35.23l.058-.003l.05.051a.27.27 0 0 1-.063.202l-.014.002h-.013c-.009-.086.037-.172-.018-.252");
}

.e53zpkb2r {
  fill: var(--svg-color--762309, #762309);
  d: path("M23.391 39.836c-.102.02-.216-.028-.303.061l-.145-.008c.118-.207.284-.171.46-.092q.023.023.011.032q-.01.006-.023.007");
}

.e6enb8b5j {
  fill: var(--svg-color--131200, #131200);
  d: path("M31.771 30.814c-.138.122-.138-.051-.197-.092q.098.047.197.092");
}

.e6irzrkcu {
  fill: var(--svg-color--726f00, #726f00);
  d: path("m20.284 39.987l-.105.01l-.058-.053l-.002-.043c.023-.036.062-.049.104-.052c.057.006.11.018.11.092z");
}

.e70ojoplf {
  fill: var(--svg-color--333407, #333407);
  d: path("M30.893 34.955c.064.025.101-.041.154-.047c.062.092.017.159-.054.219l.005-.004c-.074-.033-.144-.065-.105-.168");
}

.e8kajabvj {
  fill: var(--svg-color--132f05, #132f05);
  d: path("M15.67 22.928c-.043.058-.091.113-.164.133c.015-.094.061-.148.164-.133");
}

.e8lum9u2d {
  fill: var(--svg-color--4f4e0d, #4f4e0d);
  d: path("M28.475 37.02a.65.65 0 0 1 .362-.199a1 1 0 0 1-.298.3z");
}

.ea6lv4buh {
  fill: var(--svg-color--001e00, #001e00);
  d: path("m16.998 23.24l.25-.171q.022.016.017.039q-.005.02-.012.021c-.043.087-.139.104-.209.153c-.044.017-.055-.003-.046-.042");
}

.eat60w-4t {
  fill: var(--svg-color--262700, #262700);
  d: path("M14.318 31.48c-.102-.014-.231.056-.289-.096c.106.008.214 0 .289.096");
}

.eaxo80bev {
  fill: var(--svg-color--f3f823, #f3f823);
  d: path("M20.897 20.93q-.079 0-.153.003l-.007-.063l.05-.045c.044-.005.082.002.106.045l.019.029z");
}

.eb0vc1h9y {
  fill: var(--svg-color--620606, #620606);
  d: path("M17.606 34.36c-.05.205.116.131.203.157c.045.118-.006.135-.106.099c-.245-.199-.245-.199-.091-.313q.024.023.014.039q-.01.019-.02.018");
}

.eb6t7x1pf {
  fill: var(--svg-color--e7e815, #e7e815);
  d: path("m28.633 24.715l-.105-.005c-.039-.06-.022-.115.009-.171a.3.3 0 0 1 .047-.055c.066-.036.134-.059.207-.027l-.001-.002c.049.113.192.069.26.151l.151.005c.005.131-.134.106-.189.172a.12.12 0 0 1-.099.009a.56.56 0 0 0-.28-.077");
}

.ebhwnw5-h {
  fill: var(--svg-color--711a15, #711a15);
  d: path("M25.11 22.305c.074-.01.146-.018.199.051c-.095.097-.143.009-.199-.051");
}

.ebi6nvpnr {
  fill: var(--svg-color--5c5e07, #5c5e07);
  d: path("m24.339 39.747l.181.051c-.123.067-.258.081-.393.096q.025-.047.051-.091c.035-.075.112-.027.161-.056");
}

.ecw2pcbcc {
  fill: var(--svg-color--454600, #454600);
  d: path("m20.896 21.534l.151.008v.053l-.06.048c-.048.029-.097.023-.146.008q-.02-.022-.015-.044q.008-.022.014-.021z");
}

.ed_jjs00e {
  fill: var(--svg-color--0b0c00, #0b0c00);
  d: path("m21.608 38.04l-.001-.044l.823-.002a.2.2 0 0 0 0 .048a.2.2 0 0 1-.048.012l-.065.001a2.2 2.2 0 0 1-.594.007l-.067-.003z");
}

.edc06pb0q {
  fill: var(--svg-color--4c4b04, #4c4b04);
  d: path("m25.19 34.77l.004.04c-.084.022-.113-.042-.149-.094a.08.08 0 0 1 .047-.03a.14.14 0 0 1 .058.009c.028.017.033.047.04.075");
}

.ee1ieceyy {
  fill: var(--svg-color--e1e20b, #e1e20b);
  d: path("M27.1 25.997q-.002.022-.007.044l-.149.026c-.048-.022-.058-.063-.053-.108l.01-.118c.005-.058.009-.118.096-.099c.037.084.108.154.103.255");
}

.eeis7vb4n {
  fill: var(--svg-color--575508, #575508);
  d: path("M26.987 30.448c-.061.021-.097-.028-.144-.05l-.059-.087q.002-.018.02-.013c.072-.038.105.006.133.063z");
}

.eekgsfbor {
  fill: var(--svg-color--491f03, #491f03);
  d: path("M25.858 39.07c-.058.052-.127.056-.199.056c.039-.094.113-.116.207-.104l.017.028z");
}

.efnv_bijy {
  fill: var(--svg-color--d7d900, #d7d900);
  d: path("M25.311 34.808q.05.028.101.054q.022.031-.005.059c-.045 0-.093.004-.119-.047z");
}

.eg560nrcu {
  fill: var(--svg-color--fcfb02, #fcfb02);
  d: path("m15.713 35.23l.058.168a.06.06 0 0 1-.021.063c-.084.046-.181.054-.268.09a.64.64 0 0 1-.3.049c-.096-.016-.197-.025-.188-.164a.44.44 0 0 1 .26-.053a.43.43 0 0 1 .313-.102z");
}

.eglq965de {
  fill: var(--svg-color--efef6a, #efef6a);
  d: path("M25.922 30.26c.183.024.375-.066.548.047l-.548.004z");
}

.eglsolbjn {
  fill: var(--svg-color--762009, #762009);
  d: path("m17.973 35.539l-.056.099c-.197-.036-.071-.153-.06-.24q.03-.007.058-.011a.1.1 0 0 1 .04.041a.3.3 0 0 1 .02.083z");
}

.eh83h76xj {
  fill: var(--svg-color--545212, #545212);
  d: path("m14.427 36.13l.148.168c-.141.026-.173-.046-.148-.168");
}

.ehrgpybvp {
  fill: var(--svg-color--e5e5c5, #e5e5c5);
  d: path("M22.431 38.04q.046.004.096.012q.001.013-.004.027c-.111.017-.092.104-.092.178v2.691c0 .049-.005.104.051.133c-.012.034-.034.051-.07.039c-.05-.015-.028-.064-.041-.097a.7.7 0 0 1-.064-.271q-.002-1.237.002-2.479c0-.067.003-.137.037-.197q.028-.05.085-.036");
}

.ei6dv1cwm {
  fill: var(--svg-color--fbfb1e, #fbfb1e);
  d: path("M18.94 34.457a.1.1 0 0 1-.047-.008l.041-.041q.008.015.012.033c.001.005-.004.011-.006.016m-.101.057a.1.1 0 0 1 .012-.043a.1.1 0 0 0 .029-.01q.007.024.012.053z");
}

.eiizq8bhx {
  fill: var(--svg-color--4e4f02, #4e4f02);
  d: path("m12.88 32.19l.019.265c.012.05.046.11-.051.105c.02-.125-.115-.251.001-.376z");
}

.ej9zyna8s {
  fill: var(--svg-color--48490d, #48490d);
  d: path("M30.73 35.19c-.098-.077-.202-.148-.199-.293c.082.093.192.163.246.281q-.016.032-.047.012");
}

.ejpj2yz_u {
  fill: var(--svg-color--191200, #191200);
  d: path("M17.1 24.561c.005.07-.021.147.041.205q.01.153.018.309q.022.017.012.035q-.009.017-.017.015l-.063.046a.3.3 0 0 1-.041-.07a.26.26 0 0 1 .043-.235l-.048-.101q-.06-.08.004-.154l.005-.033q.018-.017.046-.017");
}

.ek22dnbxw {
  fill: var(--svg-color--3e3e00, #3e3e00);
  d: path("M18.673 35.33c.019-.055-.007-.125.06-.163c.053-.034.104-.044.161-.007l.141.019l.017.05c-.123.037-.366-.109-.311.203q-.025.026-.051-.002q-.006-.024-.015-.049q0-.026-.002-.051");
}

.ek78imbbu {
  fill: var(--svg-color--292c00, #292c00);
  d: path("M29.507 32.25v-.092l.202-.056c.053-.031.057 0 .053.041z");
}

.ekn_ecchu {
  fill: var(--svg-color--f6f509, #f6f509);
  d: path("m28.946 36.1l.255-.018c.055.021.06.072.069.118c-.067.1-.2.027-.276.104c-.065.072-.164.063-.245.099c-.126.011-.256-.015-.373.056c-.099.081-.217.04-.325.05c-.091-.003-.186-.043-.265.034c-.06.027-.122.043-.183.062c-.061.01-.121.007-.183.008c-.079.005-.157-.013-.233.021c-.043.028-.102.033-.135.079l-.131.01c-.072.002-.142-.02-.213-.029c-.095.022-.195.027-.289.063a.3.3 0 0 1-.08.003c-.124-.046-.278.019-.382-.104c.043-.056.108-.031.161-.051c.065-.053.145-.072.224-.093c.105-.022.211-.018.317-.02c.11-.006.222.023.327-.029q.032-.02.065-.035a.5.5 0 0 1 .181-.032q.035-.002.071-.002c.08.002.159.005.236-.026c.043-.016.086-.036.132-.044c.058.008.115-.012.174-.007c.123.043.224-.017.326-.07a.4.4 0 0 1 .251-.036c.087.031.169.024.241-.038c.081-.085.184-.07.283-.073");
}

.ekxtt3bif {
  fill: var(--svg-color--a7a601, #a7a601);
  d: path("M21.721 23.781q-.006-1.555-.009-3.113l.055.003c.049.245.021.493.02.738c-.007.776.028 1.55-.02 2.324l-.02.044l-.014.007z");
}

.eljhsbcuu {
  fill: var(--svg-color--161600, #161600);
  d: path("M18.12 35.33q.007.023.012.047l-.01.006q-.017.007-.03.016l-.032-.013q-.021-.031.006-.06v-.002q.015-.007.028-.016z");
}

.elw39pb5o {
  fill: var(--svg-color--89892a, #89892a);
  d: path("M18.12 25.377q-.794.005-1.588.007c.034-.067.099-.053.156-.053h1.269c.058 0 .122-.012.163.046");
}

.emchikbgb {
  fill: var(--svg-color--2a1e00, #2a1e00);
  d: path("m29.35 31.32l.054.014a.1.1 0 0 1-.008.039c-.077.079-.158.072-.242.01q-.026-.026-.052-.048z");
}

.emzqz_bow {
  fill: var(--svg-color--171615, #171615);
  d: path("M25.16 33.384q.02.004.041.002c-.015.079.041.194-.108.2q.035-.101.067-.202");
}

.en842-9uv {
  fill: var(--svg-color--132d01, #132d01);
  d: path("M15.974 36.31c-.106-.084-.248-.056-.364-.11q0-.025-.002-.046c.164-.003.32.02.465.102q.018.02.014.043q-.006.021-.01.021c-.037.014-.072.018-.103-.01");
}

.encanjb5y {
  fill: var(--svg-color--1c1900, #1c1900);
  d: path("m25.14 34.561l.063.063q.005.015.013.031l-.024.025c-.038 0-.064-.021-.089-.048a.1.1 0 0 1-.018-.064q.023-.03.055-.007");
}

.eni-fr_wr {
  fill: var(--svg-color--6b6d02, #6b6d02);
  d: path("M31.961 31.28v.364a.06.06 0 0 1-.044.023a.06.06 0 0 1-.041-.028l-.002-.445z");
}

.enk_88uzw {
  fill: var(--svg-color--262000, #262000);
  d: path("M28.483 32.909v-.051c.111 0 .136.093.179.167c-.115.047-.106-.096-.179-.116");
}

.eofz0nqgd {
  fill: var(--svg-color--575700, #575700);
  d: path("M15.862 27.795c-.045-.021-.092-.043-.094-.104c.128.002.106-.085.101-.164l.046-.043c.008.109.01.214-.053.311");
}

.epkjlri-o {
  fill: var(--svg-color--545500, #545500);
  d: path("M16.37 22.678c-.031.12-.118.168-.233.183c-.027-.195.141-.142.233-.183");
}

.epr-958js {
  fill: var(--svg-color--e0de12, #e0de12);
  d: path("M25.27 34.41c-.002-.041-.062-.064-.033-.113l.054-.103c.052-.031.105-.044.163-.021c.069.041.101.097.076.178c-.075.075-.157.115-.26.059");
}

.eq2ntwbvg {
  fill: var(--svg-color--121200, #121200);
  d: path("m13.14 35.18l.112-.004c-.026.076-.101.086-.158.117l.007-.115q.022-.032.039.002");
}

.eqkt5bc9w {
  fill: var(--svg-color--790401, #790401);
  d: path("m17.05 29.883l-.054.007c-.073-.084-.069-.168-.004-.253l.06-.043a.46.46 0 0 1-.002.289");
}

.eqm5w7-es {
  fill: var(--svg-color--e8e913, #e8e913);
  d: path("m14.2 34.811l.137-.082l.092-.005c-.051.095-.137.098-.229.087");
}

.eqvhdnb6l {
  fill: var(--svg-color--e2ebf7, #e2ebf7);
  d: path("M22.457 31.363c-.069-.022-.137-.057-.132-.15c.007-.089.063-.137.148-.135s.138.054.128.143c-.007.08-.045.141-.144.142");
}

.eqx5nrbuf {
  fill: var(--svg-color--393900, #393900);
  d: path("m22.272 26.1l.002.042h-.459l-.001-.039c.153-.099.304-.116.458-.003");
}

.erhbitd8d {
  fill: var(--svg-color--878600, #878600);
  d: path("M23.09 21.542q.032-.005.065-.013q.027.025.055.047l-.061.064l-.158-.046q.05-.025.099-.052");
}

.eruuv-bxr {
  fill: var(--svg-color--626209, #626209);
  d: path("M29.913 25.678q.049-.04.099-.078l.227.082c-.005.036-.034.037-.061.046l-.024.001l-.024-.001c-.082.021-.161.034-.217-.05");
}

.es418xnwv {
  fill: var(--svg-color--e9e90b, #e9e90b);
  d: path("M13.741 32.16c-.157.004-.296-.073-.44-.118c-.051-.072-.017-.115.051-.146l.214.005c.127.045.245.125.392.103l.065.053c-.046.165-.189.062-.282.103");
}

.etc6r0d3d {
  fill: var(--svg-color--f6f605, #f6f605);
  d: path("M30.584 34.512c-.079-.007-.132-.058-.183-.11c-.065-.051-.033-.116-.029-.179c.136-.314.205-.652.378-.952c.027-.008.044.009.056.031c.031-.02-.002-.036-.005-.05c-.02-.055-.023-.113-.02-.172a.4.4 0 0 1 .018-.107q.028-.086.052-.174c.036-.096.02-.195.039-.293c.026-.108.036-.22.049-.332c.007-.049.023-.095.033-.143c.01-.061.017-.12.039-.176l.033-.063c.067-.108.033-.221.003-.33a.6.6 0 0 1 0-.26c.037-.096.03-.201.063-.296a.1.1 0 0 1 .058-.053q.089.009.122.089c.024.131.008.263.013.395q0 .052-.005.104c-.047.101-.01.209-.022.313a.8.8 0 0 0-.02.27l-.005.13c-.064.081-.058.171-.031.262a.12.12 0 0 1-.016.067c-.092.132-.077.294-.13.437a1.7 1.7 0 0 0-.08.415l.003-.007c-.07.097-.041.233-.13.322c-.022.105-.078.197-.104.301c-.031.089-.074.176-.093.27c-.034.064-.046.139-.087.199a1 1 0 0 0 .001.092");
}

.etjn8cbhg {
  fill: var(--svg-color--636327, #636327);
  d: path("M18.321 35.02h.056l.002.052l-.04.007l-.02-.015q-.017-.022.002-.044");
}

.etmvwbbkl {
  fill: var(--svg-color--5a5b0a, #5a5b0a);
  d: path("M14.734 27.29c-.101-.063-.265-.004-.309-.166l.208.044l.103.065q.023.02.013.038q-.008.019-.015.019");
}

.euv4itbwb {
  fill: var(--svg-color--660301, #660301);
  d: path("m18.826 34.25l.005-.023c.104.015.243-.108.302.077a.26.26 0 0 1-.217.094c-.079-.02-.125-.059-.09-.148");
}

.euwldccpx {
  fill: var(--svg-color--1a3a0d, #1a3a0d);
  d: path("M12.49 27.383a.55.55 0 0 1-.108.279c-.005-.11-.031-.226.108-.279");
}

.evmbwib6t {
  fill: var(--svg-color--f1f105, #f1f105);
  d: path("M20.02 20.93c.036.047.025.097 0 .146q.018.02.012.04q-.005.022-.012.021a.13.13 0 0 1-.067.011a.5.5 0 0 1-.169-.048c-.039-.034-.064-.072-.021-.121c.064-.046.163.039.212-.056q.023-.005.045.007");
}

.evqin1wot {
  fill: var(--svg-color--e5e34b, #e5e34b);
  d: path("M16.993 37.28a.2.2 0 0 1 .048 0h.111c.014.082.11.039.142.094c-.106-.015-.245.077-.301-.094");
}

.ewimd15fp {
  fill: var(--svg-color--c4c488, #c4c488);
  d: path("m18.42 35.07l-.038.059q-.022-.01-.02-.027q0-.018.005-.018q.023-.023.053-.014");
}

.ewn154gcw {
  fill: var(--svg-color--e0dc5b, #e0dc5b);
  d: path("M25.823 29.533c.166-.201.368 0 .485-.168c.015-.023.046.029.048.061c.005.053 0 .105-.069.107c-.139.003-.274 0-.464 0");
}

.ex5jjt2yk {
  fill: var(--svg-color--f5f351, #f5f351);
  d: path("M27.556 26.16a.05.05 0 0 1-.008.039c-.474.072-.95.017-1.425.03c-.117.003-.239.032-.351-.03a.1.1 0 0 1-.007-.042l.666-.011c.159-.106.342-.049.513-.065c.189.012.385-.032.563.065a.3.3 0 0 0 .049.014");
}

.exhjhhzme {
  fill: var(--svg-color--201d00, #201d00);
  d: path("m28.378 32.654l-.06.07c-.095.076-.128-.046-.195-.061l.02-.061c.071-.038.144-.061.221-.016q.036.03.014.068");
}

.exkb_w2jo {
  fill: var(--svg-color--3e1305, #3e1305);
  d: path("m32.16 31.14l.012-.433l.053.009l-.015.468z");
}

.eyegp5b8o {
  fill: var(--svg-color--626101, #626101);
  d: path("M22.929 26.17q-.328-.013-.654-.028l-.013-.032a.13.13 0 0 1 .047-.048c.067-.026.137-.041.204-.061a.8.8 0 0 1 .334 0q.036.015.061.044c-.012.033.01.05.034.063q.027.036-.013.062");
}

.eyf_j5brr {
  fill: var(--svg-color--f1f302, #f1f302);
  d: path("M26.386 34.98c.092.003.161.025.133.141l-.044.06c-.055-.056-.098-.117-.089-.201");
}

.eyytpbbfx {
  fill: var(--svg-color--433200, #433200);
  d: path("m29.2 30.2l-.107.009l-.193-.012l.059-.055q.113.014.224.021z");
}

.eziu4cy4f {
  fill: var(--svg-color--605b07, #605b07);
  d: path("M21.711 24.764q-.003.026-.002.053c-.018.035-.036.071-.074.091a.52.52 0 0 1-.315.005a.2.2 0 0 1-.063-.049c0-.031-.069-.063-.003-.098a.395.395 0 0 1 .457-.002");
}

.ezso-y93w {
  fill: var(--svg-color--1d440d, #1d440d);
  d: path("M13.709 28.25q.03 0 .059-.004l.104.103c-.079.006-.151.006-.163-.099");
}

.f-316br4p {
  fill: var(--svg-color--404207, #404207);
  d: path("M15.959 24.05q-.017 0-.033.006q-.119-.087-.065-.222c.019-.017.036-.03.055-.048l.061.063z");
}

.f-5sombff {
  fill: var(--svg-color--f2f454, #f2f454);
  d: path("M12.775 26.549c.092.101.212.048.32.062l-.005.097l-.148.005c-.089-.097-.203-.024-.306-.05c.01-.083.068-.105.139-.114");
}

.f-hfcmbwh {
  fill: var(--svg-color--ab0000, #ab0000);
  d: path("M27.808 24.16q.025-.006.049-.005q.008 2.531.009 5.062c0 1.015-.007 2.026-.01 3.041c-.025.028 0 .08-.046.099c-.119-.13.01-.257.01-.387c-.01-2.604-.01-5.205-.012-7.81");
}

.f06-5q0aq {
  fill: var(--svg-color--232400, #232400);
  d: path("M17.327 29.682c-.093-.065-.099-.145-.06-.228c.003-.012.051-.017.063-.007c.08.068.074.143-.003.235");
}

.f0ahkvb0d {
  fill: var(--svg-color--ecec5c, #ecec5c);
  d: path("m16.02 37.07l-.147-.046c-.053.029-.06-.002-.055-.045c.067.029.205-.101.202.091");
}

.f0auo_a5l {
  fill: var(--svg-color--f3f62f, #f3f62f);
  d: path("m22.22 25.951l.051.094c-.132-.05-.317.125-.404-.101c.116.075.234.066.353.007");
}

.f0ns6deey {
  fill: var(--svg-color--f4f50c, #f4f50c);
  d: path("M15.913 29.938q-.409.079-.818.155c-.062-.031-.105-.069-.051-.144l.061-.009c.063-.131.2-.032.286-.092l.174-.008c.058-.049.133-.045.2-.069c.067-.018.12-.005.144.071z");
}

.f0r-9736a {
  fill: var(--svg-color--f4f406, #f4f406);
  d: path("m17.514 24.97l-.015.104c-.118.045-.238.027-.358.01c-.097-.092.002-.208-.039-.307c-.019-.079-.012-.153.049-.214q.177.003.353.002c.049.099.032.198.013.299z");
}

.f0ssesb7c {
  fill: var(--svg-color--2f210b, #2f210b);
  d: path("m31.16 26.1l-.089.054c-.036.009-.067-.003-.097-.022c-.058-.053-.143-.086-.146-.183a.13.13 0 0 1 .074-.075q.054-.01.102.021c.043.075.142.107.156.205");
}

.f0x3c81wb {
  fill: var(--svg-color--f9f82e, #f9f82e);
  d: path("m17.763 26l-.002.036l-.153.01l-.006-.053a.4.4 0 0 1-.014-.188c.14-.063.097.105.166.134z");
}

.f1cuqmbtl {
  fill: var(--svg-color--ddde95, #ddde95);
  d: path("m25.19 34.77l-.041-.046q.023-.046.063-.017l.005-.003z");
}

.f28luccdr {
  fill: var(--svg-color--858504, #858504);
  d: path("M12.942 28.966c.004.08.009.159-.053.224c-.087-.101-.092-.18.053-.224");
}

.f2jq5l4aa {
  fill: var(--svg-color--f8f805, #f8f805);
  d: path("M18.221 34.469a.1.1 0 0 0 .002.036a.2.2 0 0 1-.074.062a.3.3 0 0 0-.126.094l-.004.003q-.016.036-.051.011c-.067-.032-.108-.085-.108-.164l.056-.159c.136-.047.23.007.305.117");
}

.f3hbtgbhv {
  fill: var(--svg-color--1b1b00, #1b1b00);
  d: path("m25.397 34.773l.01.056l.01.036l-.032.02a.1.1 0 0 1-.074-.077l.005-.003l.005-.038h.024q.027.002.052.006");
}

.f3k729bhh {
  fill: var(--svg-color--5f6012, #5f6012);
  d: path("M17.652 21.948c-.041.072-.12.072-.188.089c-.003-.076.069-.091.108-.132z");
}

.f47w_hhgu {
  fill: var(--svg-color--dee11e, #dee11e);
  d: path("M20.378 39.843v.089a.1.1 0 0 1-.045.01l-.108-.053c.033-.041.039-.084.003-.129l.155.033q.024.02.013.036q-.01.014-.018.014");
}

.f4dv14uqu {
  fill: var(--svg-color--0f3109, #0f3109);
  d: path("m13.352 25.281l-.051-.003q-.026-.335.308-.308l-.002.094c-.016.041-.056.051-.092.066a.16.16 0 0 0-.075.077c-.021.035-.045.064-.088.074");
}

.f4gnx0ecw {
  fill: var(--svg-color--fefd01, #fefd01);
  d: path("m15.857 28.863l-.094.016c-.14.125-.325.094-.488.141c-.108.019-.2-.02-.288-.08c-.079-.048-.14-.122-.227-.158a1 1 0 0 1-.094-.043c-.113-.09-.235-.169-.352-.258c-.051-.053-.087-.123-.163-.147a.3.3 0 0 1-.08-.06a.8.8 0 0 0-.197-.178q-.03-.019-.056-.039c-.084-.082-.172-.158-.24-.252a.4.4 0 0 1-.064-.162a.3.3 0 0 1 .01-.104c.035-.067.076-.134.099-.207a1.4 1.4 0 0 0 .087-.213a.3.3 0 0 1 .028-.059c.036-.05.075-.087.142-.086l.095-.001c.101.032.183.118.301.1q.076.025.15.052c.085.073.203.072.294.129a.4.4 0 0 0 .238.079l.347.155c.079.059.161.104.265.098c.063.043.113.109.199.105c.039.028.077.057.094.104c.021.357.032.712-.006 1.068");
}

.f5fav6k5g {
  fill: var(--svg-color--202100, #202100);
  d: path("M29.808 24.708q-.019-.017-.041-.032c.033-.014.043.003.041.032");
}

.f6yc7cczq {
  fill: var(--svg-color--e8ea44, #e8ea44);
  d: path("M14.59 31.545c.046.08.161.003.204.088c-.093-.013-.219.066-.259-.092z");
}

.f7_ls6b8t {
  fill: var(--svg-color--f6f606, #f6f606);
  d: path("m30.01 36.516l.021.145q-.062.002-.122.007c-.085.022-.108-.05-.146-.097c-.041-.073-.143-.09-.166-.18a.4.4 0 0 1-.167-.104q-.037-.033-.071-.069c-.061-.067-.138-.123-.143-.224a.14.14 0 0 1 .02-.064c.038-.041.069-.088.135-.086l.133.154c.185.156.369.314.506.518");
}

.f7l1qobbb {
  fill: var(--svg-color--2b2a00, #2b2a00);
  d: path("M28.443 36.24c-.097.005-.193.002-.281.053c-.063.053-.128.048-.192.003l.11-.087c.091-.08.209 0 .305-.053c.037.007.082-.006.1.045a.1.1 0 0 1-.042.039");
}

.f7lxv_oyk {
  fill: var(--svg-color--948541, #948541);
  d: path("M23.591 37.902q-.047.025-.092.052l-.181-.017c-.026-.107.075-.048.105-.084c.063.001.143-.072.168.049");
}

.f80xl8bdv {
  fill: var(--svg-color--292c0c, #292c0c);
  d: path("M25.825 34.67c.038-.091.067-.148.204-.168c-.064.086-.076.152-.204.168");
}

.f8xcf4--e {
  fill: var(--svg-color--1c3608, #1c3608);
  d: path("M16.876 22.1c-.042.069-.114.099-.186.129c-.007-.146.097-.125.186-.129");
}

.fa8t-ozgp {
  fill: var(--svg-color--122305, #122305);
  d: path("m13.408 28.05l-.046-.001l.046-.153a.1.1 0 0 1 .041 0c.063.039.089.089.063.161c-.036.021-.072.023-.104-.007");
}

.faa78wx_n {
  fill: var(--svg-color--020202, #020202);
  d: path("m28.06 32.3l.007-8.211c0-.077-.007-.152-.008-.23q-.028-.076.053-.063l.059.048c.026.026.031.061.035.096c-.023.104.025.203.003.307c-.012.055-.024.108-.02.166c-.014.076.1.148.01.227c-.115.172-.036.359-.045.538c.03.065.036.135.036.204c.002.243-.01.488.009.731c.005.082.01.164.044.241a.15.15 0 0 1-.005.069l-.029.063c-.045.155-.014.313-.021.469c0 .036 0 .076.002.111c.001.068.02.132.036.196l.017.085c.011.5.016.998-.002 1.498l-.012.086c-.013.055-.034.106-.046.162c-.013.038-.034.074-.038.117c.014.174-.029.35.025.522a.1.1 0 0 0 .044.017c.031.043.005.082-.002.125c-.013.066.005.138-.008.205c-.015.284-.041.567.02.848c.029.17.023.339.017.509a1 1 0 0 1-.017.118c-.029.084-.021.169-.022.256c-.019.101-.014.201-.014.303c-.002.094.008.189-.023.279a.13.13 0 0 1-.051.064c-.117-.018-.061-.096-.054-.156");
}

.fam0rr-ra {
  fill: var(--svg-color--213c0b, #213c0b);
  d: path("M16.998 39.621q.099.061.199.119q-.023.033-.05.006c-.082-.002-.159-.012-.149-.125");
}

.fbg2fxmjm {
  fill: var(--svg-color--fcfc02, #fcfc02);
  d: path("m15.04 25.382l.155-.001c.078-.053.117-.012.15.056a4 4 0 0 0-.158.101l-.156-.009a.2.2 0 0 1-.028-.06a.11.11 0 0 1 .037-.087");
}

.fbg4hacal {
  fill: var(--svg-color--1f1205, #1f1205);
  d: path("m25.863 25.793l.008.255q-.032.025-.065.048c.031-.099-.038-.216.057-.303");
}

.fdauw0b_h {
  fill: var(--svg-color--5e5f05, #5e5f05);
  d: path("m13.613 27.33l.051.002c-.001.088-.011.172-.108.212c-.023-.083.028-.146.057-.214");
}

.fddoedcut {
  fill: var(--svg-color--161600, #161600);
  d: path("M18.896 37.18c-.091-.049-.202-.072-.238-.19c.104.033.219.054.238.19");
}

.fdxt4xb9g {
  fill: var(--svg-color--3b3900, #3b3900);
  d: path("m13.09 31.896l-.096-.002a.65.65 0 0 1-.044-.359q.03-.02.058.003c.017.053.001.11.024.161c-.024.097.094.082.111.143q-.006.048-.053.054");
}

.fephwhbad {
  fill: var(--svg-color--808004, #808004);
  d: path("M21.821 25.13q-.004-.131-.006-.264l.043-.106c.038.029.03.074.033.115c-.01.082.02.167-.023.248l-.02.017q-.011-.006-.027-.01");
}

.ffi8nxble {
  fill: var(--svg-color--fcfc02, #fcfc02);
  d: path("M28.17 26.423q.026-.014.053-.023a.23.23 0 0 1 .135-.053c.089-.007.178 0 .265.011c.003 0 .01-.007.01-.011l-.012-.021a.14.14 0 0 1 .082-.11c.253-.046.498-.132.753-.17c.135-.02.262-.005.361.104q.043.046.047.105l.111.171c.015.098.017.189-.102.23q-.031.01-.066.016a.6.6 0 0 0-.312.129a.5.5 0 0 1-.142.031a1 1 0 0 0-.253.039c-.098.016-.194.016-.288.047a.5.5 0 0 0-.231.08q-.055.02-.112.013c-.104-.041-.243.076-.32-.075c.009-.171-.027-.344.021-.513");
}

.fg4t4vbpy {
  fill: var(--svg-color--fefd04, #fefd04);
  d: path("m28.736 23.485l-.148-.113l.052-.094c.046.054.166.026.155.142q.02.079-.059.065");
}

.fh0-bd_ru {
  fill: var(--svg-color--191900, #191900);
  d: path("m18.23 30.1l-.017.094c-.044.018-.083.001-.124-.014c-.51-.024-1.018-.012-1.525-.005a.13.13 0 0 1-.083-.029l.002-.108a.22.22 0 0 1 .138-.058c.507 0 1.015-.035 1.521.02c.051.014.092.037.088.1");
}

.fhg7shb9r {
  fill: var(--svg-color--e1d75c, #e1d75c);
  d: path("m28.956 30.14l-.016-.036h.256l-.017.058c-.076.023-.152.038-.223-.022");
}

.fhnpgry8k {
  fill: var(--svg-color--2b2d00, #2b2d00);
  d: path("M13.3 31.18v.049c-.093.007-.173-.036-.255-.066l-.002-.034c.096-.032.166.056.257.051");
}

.fi1tifvgn {
  fill: var(--svg-color--263960, #263960);
  d: path("M21.707 27.84c.043-.061.066-.125.05-.199c.09.09.098.163-.05.199");
}

.fih8j-bom {
  fill: var(--svg-color--fdfc09, #fdfc09);
  d: path("m16.787 29.886l-.104.002a.38.38 0 0 1 .003-.278c.091-.004.183-.042.265.028q-.008.014-.017.024c-.027.026-.061.045-.089.071c-.029.029-.031.065-.031.104a.06.06 0 0 1-.027.049");
}

.fjfwpipqr {
  fill: var(--svg-color--0c3300, #0c3300);
  d: path("M19.866 37.898q.06-.008.118-.012q.167 0 .332-.004l.122-.039c.01.089.082.09.145.106v.045l-.153.001c-.182-.068-.379.019-.562-.051q-.002-.022-.002-.046");
}

.fjvo1ubvf {
  fill: var(--svg-color--2b2a00, #2b2a00);
  d: path("M19.303 40.454v-.103c.074-.011.135.028.197.059c-.051.083-.135.016-.197.044");
}

.fk_-d5geb {
  fill: var(--svg-color--fcfd02, #fcfd02);
  d: path("m17.358 30.46l.044.001l.034.006q.031.014.062.037l.026.026c.041.05.068.105.054.173c-.039.161-.152.158-.277.123c-.052-.021-.125.023-.156-.056l.003-.165c.067-.051.098-.157.21-.145");
}

.fkwdkjn2m {
  fill: var(--svg-color--e9e515, #e9e515);
  d: path("M31.816 31.07c-.171-.023-.302-.137-.453-.206l-.03.002c-.063-.005-.119-.036-.182-.039c-.055-.007-.109-.012-.161-.027a.7.7 0 0 1-.156-.062c-.06-.056-.146-.067-.209-.12a.13.13 0 0 1-.015-.071c.029-.087.092-.116.179-.099l.269.016a.14.14 0 0 0 .146.095l.064.012c.065.065.164.077.231.14l.074.01c.061.039.112.104.197.092q.075.055.148.105z");
}

.fky-xcbay {
  fill: var(--svg-color--fbfa03, #fbfa03);
  d: path("M19.245 34.622c.048.118.171.128.263.186c.026.036.076.056.079.108c0 .074-.046.127-.079.186c-.027.05-.051.102-.097.137c-.113.024-.171-.087-.268-.108l-.06-.03a1 1 0 0 1-.076-.063c-.052-.068-.169-.061-.195-.16c-.003-.079.046-.13.094-.183a.6.6 0 0 1 .14-.112a.2.2 0 0 1 .071-.018c.052-.002.099.007.128.057");
}

.flai8_aef {
  fill: var(--svg-color--700000, #700000);
  d: path("M20.79 37.599c.092-.001.192-.028.247.084q-.01.039-.047.017l-.203-.021c-.025-.028-.028-.054.003-.08");
}

.flv4dacat {
  fill: var(--svg-color--1d1e02, #1d1e02);
  d: path("m16.579 30.21l1.545-.007l-.031.096l-.021.002c-.169-.004-.35-.103-.496.063c-.139-.057-.274-.125-.43-.068c-.182-.09-.373-.024-.561-.032z");
}

.fmc2me2tm {
  fill: var(--svg-color--fdfc03, #fdfc03);
  d: path("M26.19 36.819c-.039-.073-.106-.041-.166-.044c-.059-.01-.108-.029-.11-.102c.011-.018.025-.021.043-.019c.145.026.301-.021.435.067c-.026.048-.079.034-.12.048q-.041.027-.082.05");
}

.fnc_6qbni {
  fill: var(--svg-color--f3f646, #f3f646);
  d: path("m16.943 26.04l-.41-.005a.1.1 0 0 1 .006-.04l.404-.001q.015.016.01.031t-.01.015");
}

.fnu7wcn-k {
  fill: var(--svg-color--e3dbd0, #e3dbd0);
  d: path("m17.195 29.886l-.023.009l-.022-.005l.008-.298c.076.089.021.197.037.294");
}

.fof2cdbnk {
  fill: var(--svg-color--0a2203, #0a2203);
  d: path("M16.736 23.433q.027 0 .055.003l-.158.199l-.046-.09z");
}

.foqx_8wia {
  fill: var(--svg-color--180f0e, #180f0e);
  d: path("M21.403 26.452v-.036h1.333v.038q-.664-.002-1.333-.002");
}

.fp09i6q_m {
  fill: var(--svg-color--313316, #313316);
  d: path("M18.23 36.703c-.126-.057-.289-.01-.391-.139c.224.021.085-.111.08-.188c.116.099.268.163.311.327");
}

.fqe8t2bxp {
  fill: var(--svg-color--dedf68, #dedf68);
  d: path("M27.753 23.743c.076-.007.161.019.223-.054l.044.046c-.087.094-.176.083-.267.008");
}

.fqnsk5bjy {
  fill: var(--svg-color--ebec10, #ebec10);
  d: path("M13.921 36.562c-.112-.01-.094.108-.151.153l-.034-.055a.44.44 0 0 1-.158-.139c-.026-.054-.06-.107-.02-.169c.026-.058.069-.094.135-.097q.015-.004.031-.004a.2.2 0 0 1 .061.027l.024.021c.061.078.146.144.112.263");
}

.fqsc17byp {
  fill: var(--svg-color--82130e, #82130e);
  d: path("M23.657 21.881c.108.018.227-.024.318.067c-.152.092-.289.048-.421-.05a.07.07 0 0 1 .046-.034q.032 0 .057.017");
}

.fr3deccbw {
  fill: var(--svg-color--edeb25, #edeb25);
  d: path("M21.308 25.07c.115.059.23-.107.346-.003a.06.06 0 0 1 0 .05a.45.45 0 0 1-.346 0a.06.06 0 0 1 0-.047");
}

.friyo6nyr {
  fill: var(--svg-color--e1e217, #e1e217);
  d: path("m21.711 24.764l-.457.002c-.007-.041 0-.077.036-.104a.39.39 0 0 1 .371-.01c.063.017.056.065.05.112");
}

.frjbhwbim {
  fill: var(--svg-color--e7e565, #e7e565);
  d: path("M19.958 21.17a.1.1 0 0 1 .021-.041a.1.1 0 0 0 .039-.009l.19.005c-.065.102-.164.036-.25.045");
}

.fs1oiacpj {
  fill: var(--svg-color--bebb1b, #bebb1b);
  d: path("m24.938 34.422l.065.037q.012.027-.005.055a.1.1 0 0 1-.051.024a.07.07 0 0 1-.049-.026c-.006-.039-.018-.08.04-.09");
}

.ftpoz9awz {
  fill: var(--svg-color--3e2c0f, #3e2c0f);
  d: path("M31.768 33.539q.018 0 .034-.004c-.048.158.036.352-.137.472a.13.13 0 0 1-.047-.067c-.002-.153-.011-.309.15-.401");
}

.fw70_vchw {
  fill: var(--svg-color--181b00, #181b00);
  d: path("m23.14 20.933l-.049.046l-.25-.017q.001-.022-.005-.043l.003-.024c.101.014.207-.026.306.026z");
}

.fwz1hvbyt {
  fill: var(--svg-color--49470a, #49470a);
  d: path("M28.893 37.945c.063-.09.106-.21.251-.197c-.069.086-.122.192-.251.197");
}

.fxajvwb2g {
  fill: var(--svg-color--eaeb6c, #eaeb6c);
  d: path("m26.938 30.361l-.133-.063a.8.8 0 0 1 .594.005c-.152.027-.32-.055-.461.058");
}

.fyatlbcrl {
  fill: var(--svg-color--494401, #494401);
  d: path("m27.04 25.17l.003-.038c.089-.069.189-.038.288-.029q.016.013.034.024c-.1.084-.216.038-.325.043");
}

.fyb92nhfl {
  fill: var(--svg-color--4c4c38, #4c4c38);
  d: path("M27.758 34.02c-.067-.133-.029-.229.105-.294a.56.56 0 0 1-.105.294");
}

.fymomnbqb {
  fill: var(--svg-color--fefe01, #fefe01);
  d: path("M13.02 26.1q.018-.05.033-.1c.053-.098.102-.196.188-.269a.1.1 0 0 0 0-.041c.069-.116.033-.263.104-.382a.36.36 0 0 1 .189-.093c.155-.019.315-.009.473-.012c.096.001.192-.003.286.022q.17.082.355.131q.051.01.104.029q.15.049.306.077a.5.5 0 0 1 .137.036q.03.017.056.041c.065.096.183.075.271.115c.073.046.157.068.236.102a.36.36 0 0 1 .166.188c.041.429.013.858.017 1.289c0 .084-.012.167-.094.222c-.171.063-.311-.038-.454-.101c-.162-.068-.322-.151-.479-.229c-.076-.041-.149-.084-.229-.116a2 2 0 0 0-.231-.083a2 2 0 0 0-.242-.063c-.145-.034-.296-.051-.424-.144a.56.56 0 0 0-.351-.094c-.089-.001-.179.004-.261-.041c-.043-.141-.191-.111-.286-.17a.11.11 0 0 1-.015-.104c.065-.057.045-.175.145-.21");
}

.fz3y7pece {
  fill: var(--svg-color--b7b512, #b7b512);
  d: path("M27.521 24.738c-.189.08-.385.034-.579.027c-.049-.104-.052-.18.098-.164l.063-.004c.12-.021.232.014.344.04z");
}

.fzhicm_rr {
  fill: var(--svg-color--f6f708, #f6f708);
  d: path("M14.737 36.2a.18.18 0 0 0-.108-.107c.185-.145.357.029.539.023c.146-.005.295.049.441.075c.133-.026.254.026.378.056c.077.071.172.05.261.053c.12.014.247-.005.353.076a.08.08 0 0 1-.017.077l.001.104l-.015.031c-.026.026-.054.041-.092.032c-.06-.054-.14-.07-.204-.114l-.258.001q-.125.07-.204-.053c-.059-.128-.159-.062-.248-.052l-.051.003c-.087-.01-.183.018-.262-.049c-.085-.098-.2-.04-.302-.057c-.09.008-.155-.035-.212-.099");
}

.g-n1gdc4p {
  fill: var(--svg-color--620000, #620000);
  d: path("m18.546 33.906l-.088-.016c.068-.058.147-.176.174.029l.002.051c-.05.008-.07-.027-.088-.064");
}

.g-u07bb5u {
  fill: var(--svg-color--7a210a, #7a210a);
  d: path("m26.843 39.697l.219-.107c.001.149-.101.184-.221.198c-.033-.031-.029-.06.002-.091");
}

.g-zfni8da {
  fill: var(--svg-color--fcfb01, #fcfb01);
  d: path("M16.23 34.457h-.311q-.032.03-.066.01a.18.18 0 0 1-.063-.131a.1.1 0 0 1 .04-.061c.125-.058.26-.078.391-.11q.06-.009.11.02c.164.166.005.209-.101.272");
}

.g0g5amcuw {
  fill: var(--svg-color--622e09, #622e09);
  d: path("M27.14 39.58q.012-.038.021-.074c.026-.076.082-.104.158-.104a.1.1 0 0 1 .056.037c-.057.082-.089.209-.235.141");
}

.g1-hd2b0c {
  fill: var(--svg-color--fbfb05, #fbfb05);
  d: path("m14.845 29.332l-.664.153c-.103-.036-.113-.108-.082-.199c.041-.058.106-.075.167-.099c.084-.028.168-.056.255-.069q.072-.009.144-.007c.072-.016.159.05.224-.032a.14.14 0 0 1 .085-.056c.063-.02.127 0 .189 0c.094.01.192-.03.281.022q.036.026.046.069a.13.13 0 0 1-.04.115c-.135.006-.276-.035-.399.053c-.057.073-.122.096-.206.05");
}

.g26rapbdv {
  fill: var(--svg-color--f4f649, #f4f649);
  d: path("M27.451 26.04h-.362q-.015-.024.007-.044l.352.001a.05.05 0 0 1 .003.043");
}

.g2ik-7t8r {
  fill: var(--svg-color--faf902, #faf902);
  d: path("m18.13 25.894l-.012.102c-.104.089-.219.081-.337.036a.2.2 0 0 1-.064-.064a.5.5 0 0 1-.061-.264c.077-.252.248-.176.414-.119l.048.057c.051.081.033.166.012.252");
}

.g3fi1mbmq {
  fill: var(--svg-color--646402, #646402);
  d: path("m25.76 26.16l.046-.061c.031-.019.042-.058.077-.072a.4.4 0 0 1 .072 0h.287c.086-.009.135-.113.233-.089a.1.1 0 0 1 .036.067a.2.2 0 0 1-.013.08c-.024.055-.06.098-.12.112c-.205-.007-.414.054-.613-.041z");
}

.g3jido9wu {
  fill: var(--svg-color--615f03, #615f03);
  d: path("M21.815 26.14q-.334.012-.667.021c-.036-.095.058-.119.097-.176l.016.009c.1.044.202.034.306.008q.047-.03.094-.056a.4.4 0 0 1 .149.074a.1.1 0 0 1 .032.059a.1.1 0 0 1-.027.061");
}

.g3lsaob2o {
  fill: var(--svg-color--646501, #646501);
  d: path("m12.778 31.438l-.048.053c-.059-.118-.043-.243-.036-.368q.021 0 .041.003c.089.093.046.206.043.312");
}

.g3pm8-bnx {
  fill: var(--svg-color--e4e643, #e4e643);
  d: path("M28.07 37.07c.059-.148.151-.125.253-.05c-.075.057-.163.057-.253.05");
}

.g58jvpskq {
  fill: var(--svg-color--4b2004, #4b2004);
  d: path("m26.79 36.15l.205.06a.1.1 0 0 1 .005.039l-.006.01q-.023.033-.055.01a.35.35 0 0 1-.2-.115z");
}

.g5yqo-_am {
  fill: var(--svg-color--c9d5e8, #c9d5e8);
  d: path("M21.767 28.557c-.014.092-.07.143-.151.141c-.096-.003-.156-.07-.143-.166c.011-.077.067-.136.159-.125c.085.011.13.066.135.15");
}

.g60urbb7c {
  fill: var(--svg-color--201f00, #201f00);
  d: path("M14.539 32.15q-.192.077-.308-.097l.143.005c.045.051.165-.037.165.092");
}

.g65j5jh0l {
  fill: var(--svg-color--878500, #878500);
  d: path("M20.547 40.671a.33.33 0 0 1 .233-.06l.064.048c-.019.043-.058.056-.098.069q-.03.013-.056-.007z");
}

.g6nv-3cou {
  fill: var(--svg-color--121800, #121800);
  d: path("m12.942 34.815l.096.146c-.106.001-.125-.059-.096-.146");
}

.g6xgp0bjn {
  fill: var(--svg-color--77290a, #77290a);
  d: path("M29.708 29.18c.104-.013.202-.014.268.088q-.01.045-.056.044l-.305-.051c-.019-.085.07-.044.093-.081");
}

.g6yuzkbvu {
  fill: var(--svg-color--fcfc01, #fcfc01);
  d: path("M27.409 30.3c0 .073-.037.149.025.215c.09.072.036.164.031.248c-.173.094-.324.105-.421-.104c-.074-.044-.097-.12-.12-.195c-.015-.055-.021-.108.013-.16a.93.93 0 0 1 .461-.001z");
}

.g76ft_b5e {
  fill: var(--svg-color--56240b, #56240b);
  d: path("M29.685 33.843c.164-.043.219.053.235.192a.5.5 0 0 1-.235-.192");
}

.g7wvivbgl {
  fill: var(--svg-color--2d2f06, #2d2f06);
  d: path("M29.814 25.781c.081.004.128.05.166.112q-.005.03-.012.056c-.085.036-.125-.087-.207-.059c-.031-.061-.029-.105.053-.109");
}

.g96tk5bbj {
  fill: var(--svg-color--4a4b00, #4a4b00);
  d: path("M30.464 25.314c-.081-.024-.173-.012-.231-.09q.007-.03.036-.029l.161.041z");
}

.g99nayb9g {
  fill: var(--svg-color--5b5d0b, #5b5d0b);
  d: path("m26.12 39.16l.003-.013c-.001-.146.074-.157.185-.106l.018.034a.23.23 0 0 1-.206.085");
}

.g9q9-3bao {
  fill: var(--svg-color--cecd6d, #cecd6d);
  d: path("m17.513 25.756l.099-.03q.01.023.01.044q-.011.113-.019.226l-.056-.053l-.002-.075z");
}

.gaa9nacil {
  fill: var(--svg-color--989897, #989897);
  d: path("m28.17 26.423l.005.544q-.022.032-.051.003c.022-.183-.062-.373.046-.547");
}

.gb31lvb2o {
  fill: var(--svg-color--2d3200, #2d3200);
  d: path("m13.04 33.12l.095.365q-.023.032-.042-.002c-.036-.118-.149-.226-.053-.363");
}

.gcjoq_12a {
  fill: var(--svg-color--554d00, #554d00);
  d: path("M16.897 36.615c.084.006.176-.006.211.101c-.133.098-.16-.028-.211-.101");
}

.gd3u26b_u {
  fill: var(--svg-color--f1f003, #f1f003);
  d: path("m25.503 34.16l.064-.063a1 1 0 0 0 .092.008l.048.199l-.096-.003c-.056-.01-.08-.051-.097-.099z");
}

.gee9vhmbg {
  fill: var(--svg-color--003200, #003200);
  d: path("m11.955 31.998l.017.257c-.084-.081-.075-.168-.017-.257");
}

.gei513b2d {
  fill: var(--svg-color--b0b00d, #b0b00d);
  d: path("m25.27 34.811l-.08-.001a.08.08 0 0 1-.019-.06a.1.1 0 0 1 .04-.053c.032-.008.063-.006.087.025l-.005-.006q.022.015.029.04q.009.027-.008.049l-.021.015z");
}

.gfv1xrbaj {
  fill: var(--svg-color--1d350e, #1d350e);
  d: path("M14.263 24.303c-.02.075-.075.121-.133.166c-.014-.103.039-.151.133-.166");
}

.gg79i5inz {
  fill: var(--svg-color--686909, #686909);
  d: path("M27.21 39.23c.017.063-.017.104-.064.136l-.08.012c-.007-.104.077-.117.144-.148");
}

.ggt9q8b_c {
  fill: var(--svg-color--545200, #545200);
  d: path("m31.57 27.532l.089.008q.002.046.006.087l-.008.115z");
}

.ghj6w-brf {
  fill: var(--svg-color--171704, #171704);
  d: path("M26.07 35.33q-.023-.005-.048-.008l-.02-.016a.1.1 0 0 1-.008-.051q.006-.025.029-.037l.051.014l.05.05z");
}

.ghwdxob8d {
  fill: var(--svg-color--565800, #565800);
  d: path("m27.355 23.324l.01-.139c.058.041.123.074.154.144c-.055.043-.11-.01-.164-.005");
}

.ghyxwebtp {
  fill: var(--svg-color--5d5d0b, #5d5d0b);
  d: path("M17.44 22.06c-.082.045-.145.145-.264.096c.082-.051.118-.226.264-.096");
}

.gimp8vbbo {
  fill: var(--svg-color--b2b303, #b2b303);
  d: path("M17.516 24.26c.058-.004.115-.012.153.049l-.01.096l-.057.048l-.024.003l-.024-.003c-.033-.031-.067-.062-.077-.108c-.004-.036.002-.068.039-.085");
}

.gjk6h8bch {
  fill: var(--svg-color--3d3208, #3d3208);
  d: path("m30.439 34.23l-.038.173q-.013.048-.024.101c-.063-.064-.148-.107-.176-.201c.064-.073.146-.091.238-.073");
}

.gjsksab7w {
  fill: var(--svg-color--7c1a1c, #7c1a1c);
  d: path("M22.733 35.37c.051-.058.121-.04.186-.048q.05-.025.082.019c-.065.099-.163.104-.267.089q-.024-.018-.016-.038q.009-.022.015-.022");
}

.gk_j_7bav {
  fill: var(--svg-color--4a4a00, #4a4a00);
  d: path("M15.634 37.589c.102-.067.166.118.27.041c.074.007.11.058.135.122c.003.032-.01.059-.024.088a.4.4 0 0 1-.043.043c-.167-.036-.248-.172-.338-.294");
}

.gk611sbie {
  fill: var(--svg-color--c41512, #c41512);
  d: path("M17.309 24.25c.096-.204.272-.055.406-.094c-.007.053.005.111-.046.15a1 1 0 0 1-.17.007a.4.4 0 0 1-.138-.02a.1.1 0 0 1-.052-.043");
}

.glmg6ziqz {
  fill: var(--svg-color--2c2d00, #2c2d00);
  d: path("m13.87 24.864l.198-.003l.063.024c.084.036.189.008.259.089c.01.058-.021.097-.063.127c-.245.066-.487.041-.729-.023c-.02-.036-.02-.074.01-.107l.053-.001c.065-.045.145-.06.209-.106");
}

.gm6l9nlyo {
  fill: var(--svg-color--68413a, #68413a);
  d: path("m27.551 30.894l.01-.072c.107.019.115.094.083.168c-.023.053-.069.02-.098-.015z");
}

.gmcrerb1c {
  fill: var(--svg-color--eaea62, #eaea62);
  d: path("M29.25 31.629c.077-.06.169-.04.256-.047c-.07.096-.167.047-.256.047");
}

.gmdad7afl {
  fill: var(--svg-color--f4f308, #f4f308);
  d: path("m27.711 37.945l.054.057c.045.045.033.095.007.145c-.089 0-.142.075-.214.108c-.055.049-.111.094-.192.079a.15.15 0 0 1-.079-.072c-.017-.096.06-.121.122-.155l.152-.095c.031-.069.092-.065.15-.067");
}

.gmfzb3bua {
  fill: var(--svg-color--dcde5e, #dcde5e);
  d: path("m25.765 36.773l.102-.094q.022-.01.049-.006c.038.039.107.045.119.113c-.012.037-.026.063-.071.034l-.152.053c-.083-.002-.083-.042-.047-.1");
}

.gn19ybx3u {
  fill: var(--svg-color--575700, #575700);
  d: path("m27.553 34.736l.002-.061c.09.028.143.105.207.166q.02.019.01.031q-.009.014-.017.014c-.091-.019-.185-.032-.202-.15");
}

.gnah2keth {
  fill: var(--svg-color--262700, #262700);
  d: path("M22.325 20.555a.2.2 0 0 1 .01-.04c.066-.005.083.045.101.091c.033 1.01.012 2.02.012 3.03a.3.3 0 0 1-.031.122q-.028.05-.084.043a.2.2 0 0 1-.06-.081c-.032-.099-.029-.2-.029-.302c.01-.911-.021-1.82.017-2.73a.3.3 0 0 1 .064-.135");
}

.gncd5gbyi {
  fill: var(--svg-color--b9b6b2, #b9b6b2);
  d: path("M22.636 40.15q.002.202-.001.403c-.002.075.02.13.104.14l-.021.027c-.11.016-.142-.037-.135-.143c.007-.142.002-.283.003-.424q.023-.023.05-.003");
}

.gnsw1m43m {
  fill: var(--svg-color--858900, #858900);
  d: path("m15.461 29.14l.183-.005c-.005.149-.118.087-.194.101q.004-.05.011-.096");
}

.gp_x519ah {
  fill: var(--svg-color--46470d, #46470d);
  d: path("M18.687 35.69q.028-.025.052-.05c.043-.034.074-.003.105.02c.023.021.026.053.04.079l.034.055c-.072.012-.154-.005-.195.08l-.076.009z");
}

.gp0_r8dmb {
  fill: var(--svg-color--4e4e0f, #4e4e0f);
  d: path("M13.613 27.33c.023-.082.038-.168.142-.19a.3.3 0 0 1-.091.192q-.026.037-.051-.002");
}

.gpw72ib_h {
  fill: var(--svg-color--565605, #565605);
  d: path("M31.1 28.717c-.154-.107-.15-.256-.106-.415c.069.13.079.274.106.415");
}

.gq-7srb-y {
  fill: var(--svg-color--e9e715, #e9e715);
  d: path("M24.639 35.17c-.045.027-.055.072-.058.119l-.103-.104l.009-.166z");
}

.gq3mdgbht {
  fill: var(--svg-color--61620b, #61620b);
  d: path("M26.341 38.988c.058-.011.115-.076.171 0c-.049.056-.118.068-.186.085l.002.003c-.029-.034-.034-.065.013-.088");
}

.gq4nsy2sh {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M10 10C3.373 10 0 14.925 0 21v22c0 6.075 3.373 11 10 11h12V10z");
}

.gqoo_1bjy {
  fill: var(--svg-color--4a4332, #4a4332);
  d: path("m26.891 25.07l.003-.255l.049-.004l.002.053q0 .128-.003.254z");
}

.gqw0zeb8s {
  fill: var(--svg-color--b80c0a, #b80c0a);
  d: path("M23.35 40.965c.054-.067.163-.018.209-.1q.058-.039.104.013c-.067.165-.205.071-.313.087");
}

.gr6xlybih {
  fill: var(--svg-color--323400, #323400);
  d: path("M29.2 36.01q-.003.034-.002.072c-.061.098-.146.078-.234.049q-.044-.027-.023-.074l.202-.068q.028.009.057.021");
}

.gr8wbra3w {
  fill: var(--svg-color--100b02, #100b02);
  d: path("m30.23 37.09l-.005-.068c-.06-.061-.058-.128-.019-.198c.117.056.058.161.067.247z");
}

.graarob7s {
  fill: var(--svg-color--e0e009, #e0e009);
  d: path("m26.992 25.742l-.096.099c-.051-.017-.092-.044-.109-.097q.05-.053.104-.105a.14.14 0 0 1 .101.103");
}

.grfmqqx4g {
  fill: var(--svg-color--2f312d, #2f312d);
  d: path("m16.279 33.18l.045-.005c.111.094.005.25.102.349c.031.054.012.07-.044.063a.8.8 0 0 1-.103-.407");
}

.grqv35bze {
  fill: var(--svg-color--dd100f, #dd100f);
  d: path("m16.271 32.26l-.024-.002l-.023.007l.003-.023c-.052-.089-.025-.185-.025-.276q-.002-1.894-.002-3.789c.002-.271-.004-.544.003-.816q.018-.057.071-.031z");
}

.gs1l3bbqh {
  fill: var(--svg-color--676227, #676227);
  d: path("m18.226 35.17l.045-.044a.3.3 0 0 1 .006.051z");
}

.gs7bppdlb {
  fill: var(--svg-color--363332, #363332);
  d: path("M25.16 33.384c.026-.061.023-.133.084-.177c.064.078.091.147-.043.179q-.02.032-.041-.002");
}

.gsq8k0b3e {
  fill: var(--svg-color--4f4e00, #4f4e00);
  d: path("M16.839 29.681c.003.063.016.126-.052.166c-.052-.077-.121-.159.052-.166");
}

.gssw16brj {
  fill: var(--svg-color--412b07, #412b07);
  d: path("m19.15 34.401l-.065.063a.1.1 0 0 1-.055.007q-.027-.009-.053-.021a.2.2 0 0 1-.044-.034a.1.1 0 0 1-.012-.055l.21-.058z");
}

.gujk4p89k {
  fill: var(--svg-color--f9f802, #f9f802);
  d: path("m21.245 25.988l.002-.088a.38.38 0 0 0 .014-.262l-.017-.061l.031-.026c.162-.046.32-.063.472.034a.15.15 0 0 1 .036.064c-.01.092-.107.15-.092.251a.2.2 0 0 1-.021.067a.22.22 0 0 1-.12.076a.5.5 0 0 1-.253-.007a.1.1 0 0 1-.052-.048");
}

.gutp4vbts {
  fill: var(--svg-color--0e0801, #0e0801);
  d: path("M17.516 24.864q-.005-.148-.013-.299c.113.095.054.198.013.299");
}

.gv0ll5bld {
  fill: var(--svg-color--a9170b, #a9170b);
  d: path("M17.759 24.607c-.046-.059-.162-.047-.156-.157c0-.04.015-.06.057-.048c.104.133.248.076.376.074c.084-.002.173-.045.181.09q-.022.023-.048.045a.2.2 0 0 1-.092.026a.7.7 0 0 0-.227.008c-.037.002-.07-.006-.091-.038");
}

.gvj33l0ol {
  fill: var(--svg-color--4b1a05, #4b1a05);
  d: path("M26.07 38.914q0 .021.008.041c-.037.118-.114.121-.21.068c.039-.087.113-.111.202-.109");
}

.gvmv2urfu {
  fill: var(--svg-color--f8fb0a, #f8fb0a);
  d: path("M25.866 39.02c.082.01.152-.01.21-.068l.134-.04c.053.007.102.021.131.073l-.013.088c-.082-.022-.164-.043-.204.069l-.154-.017q-.055-.03-.111-.058a.1.1 0 0 0 .007-.047");
}

.gvpt9_b_c {
  fill: var(--svg-color--7a7a00, #7a7a00);
  d: path("m18.94 34.457l.009.047q-.03.002-.058.006v.004q-.02-.014-.02-.033q.001-.02.008-.02l.014-.012q.027-.012.047.008");
}

.gwq1c137m {
  fill: var(--svg-color--f6f409, #f6f409);
  d: path("M27.409 39.34c-.041-.021-.054-.056-.054-.099q.005-.038.041-.051c.038-.097.132-.12.212-.163l.104.139l-.21.164z");
}

.gwwoq1yqg {
  fill: var(--svg-color--383b14, #383b14);
  d: path("m28.356 24.417l.069-.054c.051.018.097.057.156.037q0 .035-.002.069c-.074-.012-.157.008-.223-.052");
}

.gwxdpcorh {
  fill: var(--svg-color--e8e863, #e8e863);
  d: path("m18.05 37.477l.002-.087q.157.001.315.007c.003 0 .01.014.01.018c-.002.009-.01.014-.015.021c-.048.072-.129.02-.188.046z");
}

.gx5dp-72n {
  fill: var(--svg-color--46391e, #46391e);
  d: path("M18.223 26.16q.002-.031.007-.064c.052.009.1.021.095.091c-.005.064-.018.12-.104.106l.002-.041a.07.07 0 0 1-.028-.046a.07.07 0 0 1 .028-.046");
}

.gx5g4uxeh {
  fill: var(--svg-color--323200, #323200);
  d: path("M31.607 28.2q-.194-.134-.102-.353z");
}

.gxrwh6bdd {
  fill: var(--svg-color--6b1604, #6b1604);
  d: path("M26.384 37.635q.184-.042.367-.087c.021-.048.057-.034.093-.023q.024.035-.001.066c-.086.102-.201.1-.317.089c-.042-.035-.107.009-.142-.045");
}

.gxzgt_65i {
  fill: var(--svg-color--282800, #282800);
  d: path("m22.334 41.03l-.01.053l-.301-.005l-.307.003q-.008-.018-.013-.036a.12.12 0 0 1 .087-.07c.153-.031.308-.003.462-.03a.14.14 0 0 1 .074.017q.034.031.008.068");
}

.gy9pai8fl {
  fill: var(--svg-color--27420d, #27420d);
  d: path("M15.36 34.418c-.094.065-.207.077-.315.102l-.396.109q-.037-.032-.016-.072c.228-.125.445-.308.727-.139");
}

.gyerdqsmb {
  fill: var(--svg-color--e00706, #e00706);
  d: path("M17.965 34.06q-.02-.003-.04-.013l-.059-.057c.034-.041.063-.119.13-.057c.046.042.008.09-.031.127");
}

.gywp1xbvo {
  fill: var(--svg-color--e6d859, #e6d859);
  d: path("m29.14 25.992l.021-.04c.052-.054.111-.034.172-.013q.03.026.062.048z");
}

.gz-9s-bnc {
  fill: var(--svg-color--eef146, #eef146);
  d: path("m18.06 25.11l-.349.013l.001-.051l.117-.01c.029-.019.056-.019.08.008q.07 0 .137.003q.014.016.014.037");
}

.gzh7pkm9s {
  fill: var(--svg-color--615c00, #615c00);
  d: path("M26.554 25.548a2 2 0 0 0-.021.144l-.017.024a.2.2 0 0 1-.107.056q-.05.008-.082-.029q.003-.047.004-.096l.133-.115q.044.006.09.016");
}

.gzuza0i7j {
  fill: var(--svg-color--f4f050, #f4f050);
  d: path("M26.17 34.461c-.02-.045-.043-.089-.097-.102l.003-.104q.077 0 .151.003c-.023.099.082.128.11.198c-.054.08-.111-.017-.167.005");
}

.h_zeadcdk {
  fill: var(--svg-color--072301, #072301);
  d: path("M17.41 21.797c-.051.076-.138.087-.212.122c.027-.118.111-.135.212-.122");
}

.h06ou8bqo {
  fill: var(--svg-color--fafa03, #fafa03);
  d: path("M29.913 25.678c.074.007.151.002.216.05l-.007.167c-.048-.027-.094-.042-.142-.001c-.069-.003-.12-.045-.169-.086q-.021-.03 0-.059l.01-.076z");
}

.h0w-icbbk {
  fill: var(--svg-color--272900, #272900);
  d: path("M14.379 35.65a.1.1 0 0 0 .002-.049c.084-.028.159-.082.253-.066c-.049.117-.164.09-.255.115");
}

.h286y-hgg {
  fill: var(--svg-color--fdfd01, #fdfd01);
  d: path("m21.66 23.735l-.151.051a.13.13 0 0 1-.026-.093c.01-.633-.021-1.267.017-1.901l.01-1.226h.145c.063.113.08.236.08.364l-.001 2.519c-.002.1.011.207-.074.286");
}

.h2oiiyb5h {
  fill: var(--svg-color--656402, #656402);
  d: path("M26.841 30.564a.24.24 0 0 1-.207-.106c.051-.036.099-.028.146.005q.032.05.061.101");
}

.h2pdxvbuy {
  fill: var(--svg-color--302a03, #302a03);
  d: path("m25.72 34.05l-.061.059a.11.11 0 0 1-.113.014c-.067-.045-.074-.108-.063-.18c.024-.063.059-.088.12-.041c-.001.082.097.083.117.148");
}

.h440rypqo {
  fill: var(--svg-color--2c2f00, #2c2f00);
  d: path("M19.965 21.736q0 .023.007.046c-.096-.028-.145.125-.247.058c.049-.104.146-.099.24-.104");
}

.h46no5bxt {
  fill: var(--svg-color--175114, #175114);
  d: path("M18.02 37.742c.104.015.217-.04.308.049c-.104-.014-.219.043-.308-.049");
}

.h48xiwyht {
  fill: var(--svg-color--070501, #070501);
  d: path("m22.329 41.17l-.005-.09q-.019-.016-.017-.036q0-.02.005-.02a.08.08 0 0 1 .056-.021c.072.02.089-.024.091-.084c.008-.934-.012-1.864.01-2.796a.3.3 0 0 1 .031-.088c.171-.092.141.069.147.135c.02.214.004.428.009.642c.008.308-.021.614.018.921a.5.5 0 0 1 .029.115c.007.052-.029.088-.046.133a1 1 0 0 0-.01.1q.002.05.002.103c.033.159-.076.345.094.479c.029.02.053.045.059.082c-.02.074-.109.068-.143.127q-.009.03-.015.06a1 1 0 0 1-.02.09c-.01.021-.021.036-.033.055v.051c-.062.155-.16.103-.262.042");
}

.h4aakoztt {
  fill: var(--svg-color--373508, #373508);
  d: path("M26.377 34.979c-.013-.11.03-.169.146-.158c.012.101.311.207-.005.301c-.044-.047-.084-.098-.133-.141z");
}

.h4alrqb7g {
  fill: var(--svg-color--b20a0c, #b20a0c);
  d: path("M27.719 33.19c-.092-.123.002-.22.048-.322c-.002.11.027.224-.048.322");
}

.h4co75lps {
  fill: var(--svg-color--1a1600, #1a1600);
  d: path("M18.329 35.13a.2.2 0 0 1 .01.046l-.01.007l-.029.017l-.031-.012l-.012-.031l.012-.033l.033-.01z");
}

.h4s5v4jft {
  fill: var(--svg-color--dfe9f5, #dfe9f5);
  d: path("M21.622 32.875c.082.025.146.066.138.157c-.008.085-.063.142-.151.137c-.085-.005-.138-.067-.133-.153c.004-.084.067-.128.146-.141");
}

.h5eqn7dwo {
  fill: var(--svg-color--edef13, #edef13);
  d: path("M11.96 30.976c.296-.177.59-.361.94-.419c.022-.043.052-.074.106-.056c.055.039.127.06.153.13c-.016.07-.076.082-.13.1a2 2 0 0 0-.224.072c-.084.052-.191.045-.267.114l-.072.01c-.074.06-.181.065-.242.147c-.046 0-.085.012-.108.058l-.203.048c.004-.071-.016-.147.047-.204");
}

.h5ty81bqw {
  fill: var(--svg-color--2e2f0c, #2e2f0c);
  d: path("m29.04 36.463l.005-.056c-.034-.036-.072-.069-.067-.125c.06-.106.168-.087.262-.105a.1.1 0 0 1 .065.03c-.015.124-.128.174-.202.254q-.025.023-.051.041q-.02-.009-.02-.022q.003-.017.008-.017");
}

.h70n50bdl {
  fill: var(--svg-color--b6b961, #b6b961);
  d: path("m21.724 38.06l.594-.007a.04.04 0 0 1-.009.043l-.489.007l-.056.002q-.027.033-.033-.01z");
}

.h7nox2m4i {
  fill: var(--svg-color--4b4502, #4b4502);
  d: path("m17.659 25.18l.003.042c-.026.034-.061.063-.104.065c-.36.002-.722.076-1.075-.048c-.01-.075.082-.065.099-.118l.06-.038a.4.4 0 0 1 .067-.013q.101-.007.203.003a.4.4 0 0 1 .063.013c.038.011.077.023.119.019q.045-.013.092-.024c.082-.023.176.003.25-.055a.2.2 0 0 1 .078-.054h.083c.083.051.073.13.062.208");
}

.h7x4hbc1k {
  fill: var(--svg-color--655908, #655908);
  d: path("m19.14 35.66l-.041-.088c-.014-.076.027-.112.094-.132l.118.044c-.05.065-.068.163-.171.176");
}

.h80qf2avz {
  fill: var(--svg-color--0c3703, #0c3703);
  d: path("M14.619 37.646c-.012.039-.053.082.015.111q.021.013.014.025t-.015.012a.9.9 0 0 1-.408-.473c.156.08.206.286.394.325");
}

.h8a-m4bzq {
  fill: var(--svg-color--eaf05d, #eaf05d);
  d: path("m23.91 21.02l-.209.003l-.018-.001h-.019l-.058-.024c.099-.053.204-.027.306-.021a.1.1 0 0 1-.002.043");
}

.h8o4hjb1m {
  fill: var(--svg-color--fafa07, #fafa07);
  d: path("M29.459 26.1c-.259.055-.508.166-.778.156c-.134.118-.298.103-.457.11c-.051-.048-.166-.077-.057-.176a.14.14 0 0 1 .057-.033c.072-.017.149-.007.22-.034l.06-.024q.126-.049.251-.093a1 1 0 0 1 .104-.022c.099-.007.191-.048.29-.05c.077-.001.152-.003.227.021a.2.2 0 0 1 .091.071a.07.07 0 0 1-.008.074");
}

.h9zbesbtm {
  fill: var(--svg-color--232200, #232200);
  d: path("M15.391 29.85c-.076.091-.211 0-.286.092c.039-.202.193-.051.286-.092");
}

.h9zppubkl {
  fill: var(--svg-color--d6d41c, #d6d41c);
  d: path("M31.04 26.27a.1.1 0 0 1 0 .039q-.074.027-.149.052l-.027-.021c-.043-.051-.076-.102-.007-.157c.086-.027.142.012.183.087");
}

.haimd5t8s {
  fill: var(--svg-color--98953f, #98953f);
  d: path("m27.502 30l-1.686-.001l.002-.052l1.687-.001q.022.02.014.037q-.01.016-.017.017");
}

.hatic1biu {
  fill: var(--svg-color--f6f605, #f6f605);
  d: path("M30.949 33.588c-.006-.058 0-.111.044-.154c.082.078.063.129-.044.154");
}

.hav91za5i {
  fill: var(--svg-color--222100, #222100);
  d: path("M14.02 25.27c-.023-.044-.101-.022-.106-.087c.152-.101.285-.046.412.056l-.002.041z");
}

.hb9dgzuaj {
  fill: var(--svg-color--1c1900, #1c1900);
  d: path("M25.14 34.561h-.027q-.035-.002-.031-.035l.008-.007z");
}

.hc792fi_s {
  fill: var(--svg-color--cdccae, #cdccae);
  d: path("M26.07 35.23a.2.2 0 0 1 .046-.006l.019.039l-.015.017c-.05.017-.06-.007-.05-.05");
}

.he2jdebdo {
  fill: var(--svg-color--c70a0a, #c70a0a);
  d: path("M28.998 27.13c-.084.108-.201.099-.317.092c-.017-.094.083-.056.109-.102h-.006c.073-.048.146-.064.214.01");
}

.heaa_8ber {
  fill: var(--svg-color--4e4c00, #4e4c00);
  d: path("M14.696 37.492c.12.077.212.181.293.296c-.151.051-.179-.132-.293-.156z");
}

.hejiek-sa {
  fill: var(--svg-color--faf91f, #faf91f);
  d: path("M26.532 29.3c.087-.004.179-.05.255.031c.065.131-.005.275.044.409c-.023.179-.111.202-.356.097q-.04-.05-.004-.1l.019-.059c.069-.118-.077-.263.042-.378");
}

.hf_r1bcsy {
  fill: var(--svg-color--5a5c07, #5a5c07);
  d: path("M30.741 31.893a.86.86 0 0 1-.417.107q.168-.216.417-.107");
}

.hfo6eu_3o {
  fill: var(--svg-color--a20201, #a20201);
  d: path("m21.257 24.863l.046.01c.046.045.058.104.057.167a.4.4 0 0 1-.007.072a.3.3 0 0 1-.031.064a.09.09 0 0 1-.101.017l-.022-.028z");
}

.hfxhxjt2x {
  fill: var(--svg-color--3f3508, #3f3508);
  d: path("m18.17 29.577l.001-.289q.118.145-.001.289");
}

.hgvpwfybx {
  fill: var(--svg-color--0b2e0a, #0b2e0a);
  d: path("M13.87 24.864c-.041.091-.118.112-.209.105a.16.16 0 0 1 .146-.105q.031-.037.063.002z");
}

.hgwfo-_pf {
  fill: var(--svg-color--2e2500, #2e2500);
  d: path("m28.549 27.14l.033.015q.03.034.001.069q-.203.036-.402.075l-.01-.058l.12-.048c.072-.082.178-.004.258-.053");
}

.hh7n6oall {
  fill: var(--svg-color--454203, #454203);
  d: path("m22.434 25.12l.303-.002c-.115.097-.233.089-.352.007q.02-.038.049-.005");
}

.hhdks9bia {
  fill: var(--svg-color--492826, #492826);
  d: path("M24.688 34.2c.015-.138.137-.202.204-.304c.05.18-.087.235-.204.304");
}

.hi335db-x {
  fill: var(--svg-color--f5f509, #f5f509);
  d: path("M15.954 22.713q.059-.044.118-.092c.087-.093.204-.146.3-.229c.09-.043.171-.109.268-.137l.051-.029c.024-.098.133-.072.186-.129c.021-.033.048-.049.086-.026c.074.012.171-.049.21.069c.005.051-.017.089-.056.12a.4.4 0 0 0-.181.126a3 3 0 0 1-.529.307c-.101.042-.197.09-.257.188a.4.4 0 0 1-.171.112a.2.2 0 0 1-.067-.004a.2.2 0 0 1-.115-.123c-.001-.104.114-.091.157-.153");
}

.hijbwzbzw {
  fill: var(--svg-color--1d440d, #1d440d);
  d: path("M14.161 28.566c-.15-.002-.23-.099-.293-.217c.122.04.224.105.293.217");
}

.hiy2rvbhf {
  fill: var(--svg-color--ded209, #ded209);
  d: path("M26.639 24.26a.06.06 0 0 0 .033-.009c.058.024.113.074.174.005q.025-.004.053-.006c.065.059.101.125.041.208l.002-.005a.3.3 0 0 1-.074.053c-.149.026-.301.056-.438-.048c-.018-.072-.026-.145.033-.205c.058.05.115.048.176.007");
}

.hkxhdccqi {
  fill: var(--svg-color--7e1a0a, #7e1a0a);
  d: path("M25.1 21.22c-.055-.075-.17-.01-.218-.097c.115-.043.235-.117.322.046a.09.09 0 0 1-.054.075q-.036.01-.05-.024");
}

.hm10g474x {
  fill: var(--svg-color--782a0b, #782a0b);
  d: path("m29.05 27.03l.148-.021c.022-.015.037-.039.063-.053a.1.1 0 0 1 .054.007a.09.09 0 0 1 .041.069c-.064.098-.161.1-.263.088c-.023-.016-.051-.025-.067-.051q-.008-.031.024-.039");
}

.hmfk-k7-m {
  fill: var(--svg-color--f9fa1e, #f9fa1e);
  d: path("m17.912 35.457l.003-.07l.053-.006l.019.021v.028l-.021.02a.07.07 0 0 1-.054.007");
}

.hmidmp8ie {
  fill: var(--svg-color--f4f354, #f4f354);
  d: path("M12.892 26.508c.009-.039-.094-.075-.002-.115c.079.066.312-.102.257.168l-.002-.002c-.092.021-.182.031-.253-.051");
}

.hnhw9_3tj {
  fill: var(--svg-color--4e4f09, #4e4f09);
  d: path("M24.08 21.739c-.156.104-.291.05-.419-.054c.041-.117.115-.081.19-.041c.063.064.174.015.229.095");
}

.hni6d2b-n {
  fill: var(--svg-color--fafb1e, #fafb1e);
  d: path("M18.572 34.774a.1.1 0 0 1 .011.041v.002q-.029.029-.053-.002l.003.005z");
}

.hnnjcqbcs {
  fill: var(--svg-color--717503, #717503);
  d: path("m29.752 24.775l.056-.006q.011.021.007.045q.02.016.019.037q-.003.02-.009.02c-.039.017-.063 0-.082-.033a.08.08 0 0 1 .009-.063");
}

.hnscxtbzo {
  fill: var(--svg-color--274c10, #274c10);
  d: path("M15.15 38.26q.138.124.275.253c-.151.012-.231-.072-.277-.202q-.019-.019-.012-.034q.01-.017.014-.017");
}

.hnyq82b1q {
  fill: var(--svg-color--e4ec61, #e4ec61);
  d: path("m21.438 39.946l-.443.026a.06.06 0 0 1-.023-.045q.006-.03.033-.034q.099-.003.197-.009c.073.041.18-.043.236.062");
}

.hnzhdjc2e {
  fill: var(--svg-color--482d0d, #482d0d);
  d: path("m31.458 27.18l-.253-.565q.024-.047.055-.003c.172.151.223.346.198.568");
}

.hokuq-b7m {
  fill: var(--svg-color--586628, #586628);
  d: path("m20.53 37.798l.159.054c.045.096-.013.115-.09.12c-.079 0-.158 0-.185-.101c.011-.07.083-.041.116-.073");
}

.horu612dl {
  fill: var(--svg-color--1c1d00, #1c1d00);
  d: path("M15.959 29.18q-.044-.049-.092-.099c-.035-.048-.104-.058-.128-.115a.11.11 0 0 1 .016-.104c.035-.02.069-.021.103.005c.059-.003.063-.067.102-.094z");
}

.hpb1be6_i {
  fill: var(--svg-color--ebeb5e, #ebeb5e);
  d: path("m21.2 20.916l-.307.002l.002-.048l.324.008a.1.1 0 0 0-.019.038");
}

.hpl38xb2m {
  fill: var(--svg-color--373431, #373431);
  d: path("m24.06 34.765l.007.034c-.044.096-.115.142-.224.115z");
}

.hq62elbuk {
  fill: var(--svg-color--6d1f0f, #6d1f0f);
  d: path("M19.758 34.992q-.1-.035-.204-.068q-.022-.059-.046-.116c.105.032.289-.044.25.184");
}

.hqgc44quv {
  fill: var(--svg-color--aba475, #aba475);
  d: path("m18.79 34.461l.061.01q.013.027-.012.043l.003-.004q-.027.029-.054-.002v.002q.002-.024.002-.049");
}

.hqo08y2ql {
  fill: var(--svg-color--eef3f9, #eef3f9);
  d: path("M21.707 27.84c-.082.01-.167.034-.217-.072c-.026-.057-.017-.105.019-.142c.084-.086.167-.044.248.015c.058.084.038.149-.05.199");
}

.hrfzv1-3u {
  fill: var(--svg-color--ee0403, #ee0403);
  d: path("M22.329 41.17c.089-.008.188.047.263-.044c.053.063.06.13-.034.144c-.086.012-.206.055-.229-.1");
}

.hrkrm3bwo {
  fill: var(--svg-color--f8f804, #f8f804);
  d: path("M30.993 35.13c-.019-.083.085-.134.054-.219v-.043c.058-.066.084-.153.136-.224c.029-.096.063-.189.116-.276c.002-.09-.002-.183.055-.263c.075-.096.095-.212.131-.324c.063-.104.03-.239.12-.333l.107-.416c-.009-.089.031-.175.027-.264c.021-.084.036-.171.074-.251v-.058c-.053-.087.01-.145.054-.207l-.001-.139c.003-.054-.002-.109.017-.162l.027-.064c.014-.097.005-.193.009-.293c.011-.104-.033-.217.042-.312l.115.001c.072.204-.013.41.004.615l-.047.306c.014.171-.118.335-.02.51c-.142.104-.102.272-.142.412c-.052.134-.106.267-.104.415l-.113.395a.5.5 0 0 0-.098.268a.6.6 0 0 0-.111.304a.5.5 0 0 0-.099.25a.4.4 0 0 0-.099.216a.33.33 0 0 0-.103.208c-.066.031-.098-.041-.151-.052");
}

.hsv4mybpk {
  fill: var(--svg-color--201f00, #201f00);
  d: path("m22.383 38.05l-.013 2.972a.1.1 0 0 0-.036.005l-.01-.064c-.067-.063-.078-.149-.078-.234c.004-.856-.02-1.713.014-2.568a.3.3 0 0 1 .038-.092q.033-.047.085-.019");
}

.ht4tcht3q {
  fill: var(--svg-color--511306, #511306);
  d: path("m24.952 40.572l-.063-.048c.064-.104.146-.14.257-.067l.077.009c-.054.124-.172.089-.271.106");
}

.htirczbbm {
  fill: var(--svg-color--3a3000, #3a3000);
  d: path("m27.553 30.2l-.101.006l-.02-.021a.07.07 0 0 1 .019-.078l.056-.06a.1.1 0 0 0-.005-.043l.003-.054v-.041c.108.082.04.192.048.291");
}

.htplotx4d {
  fill: var(--svg-color--535313, #535313);
  d: path("M14.736 36.535q.075.09.149.174c-.136.017-.182-.044-.149-.174");
}

.hutziioqz {
  fill: var(--svg-color--535405, #535405);
  d: path("M29.05 24.606c-.088-.05-.248.028-.26-.151c.065.087.236-.008.26.151");
}

.hv7u_ac6q {
  fill: var(--svg-color--f7f610, #f7f610);
  d: path("M25.2 22.15c-.043.063-.112.049-.172.063c-.068.034-.126.029-.166-.045a.14.14 0 0 1 .006-.109c.075-.094.157-.015.236-.01q.097.005.096.101");
}

.hvgqi0lza {
  fill: var(--svg-color--4a0000, #4a0000);
  d: path("m27.502 39.33l.077.008c-.038.098-.118.112-.211.105q-.009-.012-.024-.012c-.012-.056.015-.09.06-.118a.09.09 0 0 1 .098.017");
}

.hvwkr_0wa {
  fill: var(--svg-color--393a32, #393a32);
  d: path("M25.866 36.615v.064c.007.066-.034.096-.087.115a.1.1 0 0 1-.072-.023l-.036-.001a.43.43 0 0 1 .195-.155");
}

.hwljoccox {
  fill: var(--svg-color--d5d34c, #d5d34c);
  d: path("M26.891 29.22q-.205.006-.411.015q-.022.025-.046.002q-.026-.01-.053-.017v.007c-.031-.057.005-.092.039-.129a.6.6 0 0 1 .173-.063c.072-.015.106.047.156.076l.13-.046c.059.046.053.099.012.155");
}

.hxfrgbrex {
  fill: var(--svg-color--f6f547, #f6f547);
  d: path("M18.12 26.05q-.18-.006-.36-.008l-.014-.02l.016-.017l.354-.007z");
}

.hz_q6cdol {
  fill: var(--svg-color--100b00, #100b00);
  d: path("M17.896 29.832c-.028-.036-.05-.053-.051-.072c-.004-.02.006-.05.021-.061c.022-.019.044 0 .046.025c.001.029-.009.057-.016.108");
}

.hz4bctb8n {
  fill: var(--svg-color--312c30, #312c30);
  d: path("M17.27 35.38a.1.1 0 0 0 .041-.009c.077.035.115.091.09.18a.35.35 0 0 1-.131-.171");
}

.hzdadbbuw {
  fill: var(--svg-color--11060a, #11060a);
  d: path("M27.358 34.3c.004-.072-.026-.163.088-.181a4 4 0 0 1-.088.181");
}

.i_72aubmq {
  fill: var(--svg-color--55560c, #55560c);
  d: path("M18.738 39.525V39.5c.115-.004.213.047.31.1q.02.012.012.025q-.008.011-.015.012a.4.4 0 0 1-.307-.112");
}

.i_ruwhbix {
  fill: var(--svg-color--e4e45e, #e4e45e);
  d: path("M14.67 29.17c.063-.056.141-.043.213-.048c-.048.115-.142.031-.213.048");
}

.i-7q1fbwd {
  fill: var(--svg-color--082f01, #082f01);
  d: path("M15.324 23.23c-.092.121-.181.246-.328.306q-.03.027-.058-.002c.112-.123.189-.287.386-.304");
}

.i-j94t26b {
  fill: var(--svg-color--eaeb6b, #eaeb6b);
  d: path("M23.513 40.04c.072-.06.162-.028.241-.053q.055-.036.104.01c-.106.092-.227.043-.345.043");
}

.i-km4dbkh {
  fill: var(--svg-color--d4d241, #d4d241);
  d: path("M25.763 30.963q.007-.043.017-.086c.157-.087.34.016.501-.063c.252-.035.503-.009.756-.017c.171.017.349-.041.512.055c.039.042.041.083-.002.123q-.017 0-.032.006c-.585.016-1.169.047-1.752-.018");
}

.i-sumibei {
  fill: var(--svg-color--4a4a02, #4a4a02);
  d: path("M28.323 33.06a.27.27 0 0 1 .182.115c-.109.038-.155-.023-.182-.115");
}

.i0l-98byu {
  fill: var(--svg-color--4e5000, #4e5000);
  d: path("M14.379 35.65c-.067.079-.155.098-.254.084c.049-.115.172-.087.256-.133q.023.018.015.033q-.007.017-.017.016");
}

.i0o7trb_w {
  fill: var(--svg-color--e7e74e, #e7e74e);
  d: path("M27.612 37.39c-.076.058-.166.043-.254.05c.07-.098.166-.046.254-.05");
}

.i0uabmbgy {
  fill: var(--svg-color--d10101, #d10101);
  d: path("M18.54 26.471v3.826c.018.671.049 1.342-.017 2.01c-.067-.082-.041-.181-.041-.271q-.003-2.684 0-5.367c0-.087-.04-.19.056-.26q.021.017.015.04q-.006.02-.013.02");
}

.i1mv624kw {
  fill: var(--svg-color--1c3409, #1c3409);
  d: path("m18.271 21.379l.074.012c-.049.139-.173.146-.289.166l-.034-.01q-.02-.019-.016-.041q.006-.02.01-.021c.067-.083.156-.107.255-.106");
}

.i2eiesfru {
  fill: var(--svg-color--1b3c0c, #1b3c0c);
  d: path("M15.765 25.541c-.005-.049-.016-.092-.065-.114c.031-.101.094-.089.164-.048l.009.021c-.004.073-.02.135-.108.141");
}

.i2jex4xye {
  fill: var(--svg-color--434210, #434210);
  d: path("M29.865 26.617c.105-.025.079-.125.11-.191a.3.3 0 0 1 .102.18q.021.03.005.063c-.08.02-.174.086-.217-.052");
}

.i2o9s4bnd {
  fill: var(--svg-color--361700, #361700);
  d: path("M24.43 21.07q0-.065.053-.099c.138.012.289-.008.368.149l-.062.012c-.13.039-.254.041-.359-.062");
}

.i2sd7-_ws {
  fill: var(--svg-color--514f00, #514f00);
  d: path("m16.533 37.17l.001.099c-.095-.105-.25-.059-.352-.142c.119.007.244-.049.351.043");
}

.i3mhi1bns {
  fill: var(--svg-color--727300, #727300);
  d: path("m28.477 29.14l.049.043c-.006.135-.085.063-.143.049l-.061-.044c.006-.038.029-.061.063-.077c.036-.004.072-.01.092.029");
}

.i3rnbko1z {
  fill: var(--svg-color--21400d, #21400d);
  d: path("M16.07 37.795a.1.1 0 0 0-.048-.011l-.116-.154c-.038-.19-.219-.253-.336-.371c-.003-.004-.001-.019.004-.023a.2.2 0 0 1 .036-.026c.154-.08.299.004.447.023c.072.033.171.036.178.147c-.074.003-.148.009-.237.014c.029.2.294.236.281.445c-.074.007-.125-.097-.209-.044");
}

.i3twambtg {
  fill: var(--svg-color--ced10f, #ced10f);
  d: path("m17.208 25.764l-.054-.123l.001-.071l.151-.031q.036.045.043.103q.001.059-.034.106a.11.11 0 0 1-.107.016");
}

.i40292bnb {
  fill: var(--svg-color--878800, #878800);
  d: path("M22.21 25.17c-.122-.007-.248.031-.365-.033q.013-.018.021-.033q.036-.01.074-.006c.075.004.151-.014.225.014q.021.002.045.002z");
}

.i4atue2ux {
  fill: var(--svg-color--424309, #424309);
  d: path("m31.764 32.766l-.044.002c.007-.094-.012-.197.094-.253c.004.087.002.173-.05.251");
}

.i5qdjt20q {
  fill: var(--svg-color--54530a, #54530a);
  d: path("M15.566 35.28c-.089.08-.209.065-.313.102c.066-.151.177-.167.313-.102");
}

.i5z4erbks {
  fill: var(--svg-color--f8f807, #f8f807);
  d: path("M21.2 40.76c.076.045.229-.077.237.11a1 1 0 0 1-.454.007c-.14-.016-.282.018-.414-.052c-.021-.049-.076-.026-.108-.049c-.038-.03-.06-.064-.045-.113a.1.1 0 0 1 .06-.031a.2.2 0 0 1 .069.005l.169.044a.6.6 0 0 0 .257.036c.078.004.161-.015.229.043");
}

.i6-_ost1c {
  fill: var(--svg-color--191900, #191900);
  d: path("m26.02 35.472l-.002-.038q.027-.03.06-.008q.022.032-.005.058l-.008-.002a.06.06 0 0 1-.045-.01");
}

.i62xrxpsy {
  fill: var(--svg-color--ebeb0a, #ebeb0a);
  d: path("M14.12 29.29a.27.27 0 0 0 .058.192c-.033.044-.081.054-.132.056c-.143-.023-.256.08-.39.097h-.092a.7.7 0 0 1-.243.101c-.076-.012-.142.058-.219.018c-.008-.049-.019-.095-.069-.121c.16-.185.401-.199.604-.293q.038-.011.075-.018c.139.022.266-.101.408-.032");
}

.i65t8tgfa {
  fill: var(--svg-color--550, #550);
  d: path("M28.652 35.535c-.01.03-.034.084-.048.063c-.046-.065-.192-.082-.121-.213q.015.01.032.006q.07.072.137.144");
}

.i67m2qblm {
  fill: var(--svg-color--5a5b0b, #5a5b0b);
  d: path("M15.569 27.586c-.126.068-.199-.004-.265-.098c.096.013.19.033.265.098");
}

.i6d59tbvm {
  fill: var(--svg-color--48470a, #48470a);
  d: path("M14.688 27.01a.04.04 0 0 0 0-.027c.084 0 .159.016.207.095c-.055.05-.104-.015-.156-.007q-.024-.031-.051-.061");
}

.i6mpxybcf {
  fill: var(--svg-color--c2c0a5, #c2c0a5);
  d: path("m12.01 30.02l.005.023c.039.059-.003.058-.043.058c-.108-.112-.046-.233-.017-.354c.026.089-.019.195.055.273");
}

.i7__5b-oy {
  fill: var(--svg-color--d3d041, #d3d041);
  d: path("M16.477 30.986c-.072-.047-.058-.086.007-.124q.409.003.818.009c.135-.1.271-.096.411-.009l.508.019v.087q-.873.007-1.744.018");
}

.i73mgvzrz {
  fill: var(--svg-color--f5f408, #f5f408);
  d: path("M14.342 28.461c.14.051.27.115.345.253q0 .102-.097.138a.2.2 0 0 1-.07.006c-.156-.035-.264-.148-.377-.248c-.07-.09-.168-.144-.262-.203a.7.7 0 0 1-.156-.14a.24.24 0 0 1-.057-.138c.004-.041.017-.077.052-.102a.14.14 0 0 1 .147.022l-.005-.003c.074.087.176.143.262.217a.2.2 0 0 0 .022.039c.097.017.117.126.196.159");
}

.i7o8zry3n {
  fill: var(--svg-color--143104, #143104);
  d: path("m21.2 20.668l.109.056c-.138.199-.342.084-.516.106c-.072-.022-.159.002-.221-.063c.197-.118.412-.108.628-.099");
}

.i884k43-d {
  fill: var(--svg-color--c00909, #c00909);
  d: path("M17.16 29.11c-.064.012-.072.053-.063.106l-.015.053l-.096.002l.009-.105c.056-.036-.036-.176.106-.151q.03.046.059.095");
}

.i8o3fqbfi {
  fill: var(--svg-color--eff4f9, #eff4f9);
  d: path("M22.587 28.566c.012.072-.053.121-.132.125c-.08.003-.143-.047-.142-.142c.002-.077.042-.128.119-.137c.09-.009.143.032.155.154");
}

.i9aw6ebpt {
  fill: var(--svg-color--831c03, #831c03);
  d: path("m17.628 34.83l-.117-.003c.031-.095.122-.12.194-.167q.016.004.034.011q.084.067.036.163c-.05.046-.1.079-.147-.004");
}

.i9iujjbbq {
  fill: var(--svg-color--d6d297, #d6d297);
  d: path("m25.97 35.38l-.002-.042q.022-.04.057-.011l-.004-.004l-.008.059l-.021-.002z");
}

.i9okw4b6a {
  fill: var(--svg-color--eae940, #eae940);
  d: path("M28.854 36.05c-.063.057-.142.04-.214.047c.051-.11.142-.034.214-.047");
}

.i9sorvbmz {
  fill: var(--svg-color--54541d, #54541d);
  d: path("m25.04 37.635l-.263.045l-.04-.017l.002-.069l.24-.017c.056-.019.073.003.061.058");
}

.ia2ke2bko {
  fill: var(--svg-color--252600, #252600);
  d: path("M28.12 32.442a.2.2 0 0 1 .01-.045c.021-.032.039-.065.079-.082a.35.35 0 0 1 .229.003c.038.021.063.047.054.093c-.059.061-.14.065-.213.087c-.055.012-.104-.007-.15-.031z");
}

.ia5bpxbmb {
  fill: var(--svg-color--454312, #454312);
  d: path("M26.12 35.23c-.077-.077.015-.138.02-.209l.081.004c-.016.077.007.173-.101.205");
}

.ia5d3biyv {
  fill: var(--svg-color--504f00, #504f00);
  d: path("M31.2 30.562c-.143.113-.14 0-.146-.095c.043.041.124.022.146.095");
}

.iapwy3bxj {
  fill: var(--svg-color--181900, #181900);
  d: path("M18.479 34.971a.1.1 0 0 1 0 .042l-.052.007l.003.005q-.01-.015-.021-.026l.01-.033l.033-.011z");
}

.iaskijbsa {
  fill: var(--svg-color--494900, #494900);
  d: path("m12.841 29.947l-.048-.05c.094-.058.185-.143.305-.054c-.07.073-.177.057-.257.104");
}

.iazgcchhs {
  fill: var(--svg-color--87240e, #87240e);
  d: path("m30.23 31.17l-.061-.01c.082-.192.225-.136.364-.087c-.085.084-.215.028-.303.097");
}

.ibssz7uzd {
  fill: var(--svg-color--464300, #464300);
  d: path("M22.327 25.22h-.616l-.014-.029l.019-.029a.2.2 0 0 1 .123-.056q.035.001.067.014c.101.023.214-.011.308.059q.056.018.113.041");
}

.ibyj1dkfo {
  fill: var(--svg-color--54520e, #54520e);
  d: path("m25.1 21.472l.047-.084c.093.013.176.05.252.101a.1.1 0 0 1-.007.043c-.112.051-.184-.094-.292-.06");
}

.iccvrjogu {
  fill: var(--svg-color--e5e574, #e5e574);
  d: path("m16.686 29.609l-.003.278l-.02.007l-.021-.004l.005-.289a.06.06 0 0 1 .039.008");
}

.icludy12a {
  fill: var(--svg-color--7a2424, #7a2424);
  d: path("M23.04 37.692c.063-.151.162-.125.268-.05c-.08.073-.176.047-.268.05");
}

.icrc-x5mo {
  fill: var(--svg-color--151600, #151600);
  d: path("m16.84 35.07l-.01.065c-.053-.034-.063-.116-.143-.121v-.104l.031-.042z");
}

.icyf0hdkc {
  fill: var(--svg-color--585809, #585809);
  d: path("m12.639 27.696l-.053-.058c.034-.092.023-.209.146-.246c.02.118-.045.208-.093.304");
}

.id34y3b6h {
  fill: var(--svg-color--0e0908, #0e0908);
  d: path("m21.403 26.452l-1.793-.001l-.002-.035h1.795q.026.013.018.023q-.008.014-.018.013");
}

.ids84txtt {
  fill: var(--svg-color--f4f529, #f4f529);
  d: path("M29.908 25.02c-.159.01-.298-.069-.445-.108c-.086.003-.166-.002-.197-.103a.14.14 0 0 1 .031-.113c.113-.032.209.019.306.063l.046.002q.012.015.026.004c.024.025.065.021.087.051c.009.029.026.046.06.041l.09.006c.043.021.055.06.053.105z");
}

.ielgsdcjn {
  fill: var(--svg-color--2a2b00, #2a2b00);
  d: path("M13.659 29.638c.118-.079.232-.174.39-.097c-.135.013-.23.188-.39.097");
}

.ieln3ccbs {
  fill: var(--svg-color--281200, #281200);
  d: path("M26.639 24.26c-.061.067-.123.171-.176-.007z");
}

.ifdj3qmgk {
  fill: var(--svg-color--494c03, #494c03);
  d: path("M29.814 34.25c.125.015.19.102.253.197c-.134-.003-.197-.095-.253-.197");
}

.ifpdnnbbr {
  fill: var(--svg-color--3e2b2c, #3e2b2c);
  d: path("m20.523 37.598l.063-.018q.1.011.204.019l-.003.079c-.086-.03-.187-.015-.264-.08");
}

.ifw3wybuw {
  fill: var(--svg-color--6a690c, #6a690c);
  d: path("m27.396 39.19l-.041.051c-.043 0-.092.058-.128-.011c.043-.072.099-.094.169-.04");
}

.ig2x4eyed {
  fill: var(--svg-color--323008, #323008);
  d: path("M31.1 26.354q-.035-.024-.066-.048a.3.3 0 0 1-.032-.065a.2.2 0 0 1 .024-.107c.034-.035.072-.068.128-.037c.101.034.105.146.17.212c.059.063.006.105-.067.112c-.064.002-.118-.017-.157-.067");
}

.ig70v6b1p {
  fill: var(--svg-color--efee60, #efee60);
  d: path("m14.02 25.27l-.543.01c.004-.056.042-.08.088-.097q.145-.028.296-.035q.032.002.063.011c.047.026.101.041.096.111");
}

.igflrcb2f {
  fill: var(--svg-color--fdfe01, #fdfe01);
  d: path("m22.532 24.92l-.006.105c.006.096-.052.072-.105.053c-.02-.066-.029-.133.007-.199c.044-.01.089-.023.104.041");
}

.igsu42p2n {
  fill: var(--svg-color--292400, #292400);
  d: path("m25.818 29.948l.045-.061a.4.4 0 0 1 .065-.039a.3.3 0 0 1 .072-.017c.087-.005.173-.002.26-.005c.07-.002.142-.015.214-.015c.106-.007.248.085.297-.101c.007-.061.012-.12.052-.169c.036-.028.063-.016.09.013c.051.075.024.168.063.247c.015.01.031.02.05.022c.039.007.077 0 .114-.008a.3.3 0 0 1 .06 0q.076.018.151.024q.03.003.061.013q.026.017.05.036a.2.2 0 0 1 .044.016a.066.066 0 0 1-.039.078c-.512.067-1.024.031-1.537.02c-.044.002-.078-.027-.112-.054");
}

.ihpn6acgx {
  fill: var(--svg-color--3c3a00, #3c3a00);
  d: path("M18.77 37.495c.025.029.076.036.071.089l-.199-.008c-.034-.031-.13.016-.106-.086z");
}

.ii32fzbhj {
  fill: var(--svg-color--e7e602, #e7e602);
  d: path("m27.452 30.2l-1.584.001l-.019-.095l1.602-.003z");
}

.iikzhjueq {
  fill: var(--svg-color--542b07, #542b07);
  d: path("M21.757 24.416q.029.026.061.051c.034.033.072.063.087.111a.3.3 0 0 1-.075.301a.12.12 0 0 1-.102.015a.12.12 0 0 1-.05-.049a.3.3 0 0 1-.021-.064q-.016-.065-.029-.132a.11.11 0 0 1 .034-.09a3 3 0 0 1 .095-.143");
}

.iivsp0b8i {
  fill: var(--svg-color--193a00, #193a00);
  d: path("m18.02 37.692l.108-.003c.111-.091.236-.078.363-.043a.12.12 0 0 1 .059.056c.004.084-.083.048-.114.087q-.052.003-.104.002c-.096-.064-.213.014-.308-.049a.2.2 0 0 0-.004-.05");
}

.iiy5die8r {
  fill: var(--svg-color--d6d935, #d6d935);
  d: path("m15.677 23.23l-.03-.051c.087 0 .118-.115.212-.104c.021.15-.081.152-.182.155");
}

.ij5026bag {
  fill: var(--svg-color--51530a, #51530a);
  d: path("m28.22 35.24l.005-.036c.089 0 .128.072.183.123c-.105.061-.137-.033-.188-.087");
}

.ijfczsbrl {
  fill: var(--svg-color--e3e405, #e3e405);
  d: path("m19.659 21.18l-.072.052c-.084-.031-.181.069-.258-.023c-.025-.049-.014-.092.022-.13c.101-.027.221.021.306-.072c.035.028.045.064.041.105a.14.14 0 0 1-.039.068");
}

.ijl1k4n1u {
  fill: var(--svg-color--393a05, #393a05);
  d: path("M17.301 30.826c.128.007.231-.023.253-.174c.121-.012.089.123.156.162l.003.048a1.2 1.2 0 0 1-.411.009z");
}

.ijyfeibbk {
  fill: var(--svg-color--cad6e8, #cad6e8);
  d: path("M21.624 31.07c.077.006.136.052.14.14c.003.099-.063.156-.156.152a.14.14 0 0 1-.137-.149c.005-.081.054-.138.153-.143");
}

.ikx7ute8q {
  fill: var(--svg-color--faf900, #faf900);
  d: path("m17.15 30.354l.053.058c.046.077.015.123-.064.148q-.044-.054-.092-.107z");
}

.ile721k_t {
  fill: var(--svg-color--7a150f, #7a150f);
  d: path("M23.03 21.753c.113.073.243.018.361.048q.031.005.03.035c-.017.027-.045.035-.066.052a.97.97 0 0 1-.522-.089l.108-.043z");
}

.ilgopw0za {
  fill: var(--svg-color--231a00, #231a00);
  d: path("m22.12 24.25l.101.015c-.046.14-.122.118-.211.041c.023-.05.067-.051.11-.056");
}

.im3qm2bek {
  fill: var(--svg-color--2f1f10, #2f1f10);
  d: path("m30.699 36.1l.042.055q-.001.1-.102.116c-.002-.022-.003-.048-.007-.07c-.016-.058.011-.09.067-.101");
}

.imr8hubvl {
  fill: var(--svg-color--601f00, #601f00);
  d: path("m25.1 34.29l-.01.171q-.017.024-.048.017c-.017.008-.013-.05-.039-.013a.07.07 0 0 1-.053.006q-.024-.02-.015-.047c.02-.071-.003-.162.082-.197c.053-.024.075.017.083.063");
}

.in6z_gb0g {
  fill: var(--svg-color--601e1e, #601e1e);
  d: path("M24.967 36.976c.041-.113.137-.142.24-.154a.35.35 0 0 1-.24.154");
}

.inb12lbet {
  fill: var(--svg-color--59463b, #59463b);
  d: path("M18.216 25.894h-.04c-.091-.093-.063-.19-.017-.29l.005-.008c.097.087.052.195.052.298");
}

.iotk3-brc {
  fill: var(--svg-color--fafb1d, #fafb1d);
  d: path("M16.919 29.635a.5.5 0 0 1 .019.256l-.15-.005v-.039c0-.061.005-.12.052-.166z");
}

.ip5rm4c0i {
  fill: var(--svg-color--f9f706, #f9f706);
  d: path("m26.326 25.742l.103-.01c.047.026.07.068.083.118c.006.04-.001.075-.032.102c-.079.002-.094.146-.199.089q-.03-.013-.022-.027q.01-.019.02-.019l-.004-.056a.4.4 0 0 1 .057-.201z");
}

.iqrl4ye8o {
  fill: var(--svg-color--15320a, #15320a);
  d: path("M14.03 37.06c.058.047.111.094.132.17c-.093-.02-.151-.063-.132-.17");
}

.irae4fz9q {
  fill: var(--svg-color--f6f933, #f6f933);
  d: path("M26.834 25.997a.05.05 0 0 1 .002.046a.47.47 0 0 1-.35.003l-.007.002l.01-.051z");
}

.irhc8vbvy {
  fill: var(--svg-color--d3d4c4, #d3d4c4);
  d: path("m31.924 31.941l.001-.3l.036.003c-.015.1.052.208-.037.297");
}

.iri-78_hh {
  fill: var(--svg-color--5a5900, #5a5900);
  d: path("M18.18 37.48c.043-.091.126-.021.188-.046c.029.027.068.048.063.097c-.031.036-.063.035-.096.007z");
}

.irpm1zbsp {
  fill: var(--svg-color--c8d5e7, #c8d5e7);
  d: path("M23.915 31.21c-.007.092-.06.148-.143.154c-.088.006-.148-.053-.153-.141c-.005-.087.051-.146.14-.15c.092-.005.137.056.156.137");
}

.iryuz0ppw {
  fill: var(--svg-color--b6211f, #b6211f);
  d: path("M26.935 29.23c.094-.069.05-.171.06-.26c.099.089.029.204.047.306c-.043.004-.084-.002-.107-.046");
}

.isphtkblw {
  fill: var(--svg-color--666826, #666826);
  d: path("M18.892 34.51q-.004.024-.012.047l-.041.003l.002.003l-.023-.026l.014-.031q.016-.008.031-.013q.014.007.029.017");
}

.isu0sbcyd {
  fill: var(--svg-color--20220b, #20220b);
  d: path("m18.229 36.778l.063-.042c.106-.012.161.062.217.135c-.112.059-.221-.023-.331-.011c-.016-.048.01-.07.051-.082");
}

.it6c1lbwt {
  fill: var(--svg-color--f3f308, #f3f308);
  d: path("M30.789 30.451q-.078.06-.159.117a.14.14 0 0 1-.089.034c-.065-.005-.125-.031-.188-.048q-.03-.008-.059-.021a1 1 0 0 0-.211-.061c-.053-.006-.108-.012-.159-.027c-.045-.016-.084-.035-.127-.053c-.061-.031-.138-.046-.156-.13a.2.2 0 0 1 .064-.128c.034-.021.069-.01.105-.002c.099.027.202.037.301.068c.072.019.14.059.219.053l.108.055c.073.049.154.07.245.049a.16.16 0 0 1 .106.094");
}

.itcd0u_we {
  fill: var(--svg-color--4c1209, #4c1209);
  d: path("M27.702 22.448c-.079-.024-.157-.05-.195-.134c.111-.024.188.002.195.134");
}

.itrsje3kw {
  fill: var(--svg-color--4b4900, #4b4900);
  d: path("M19.14 22.03c-.081.017-.151.077-.24.061c.034-.173.195-.099.294-.149q.018.02.016.041q-.003.024-.007.023a.1.1 0 0 1-.063.024");
}

.iu1-6_blh {
  fill: var(--svg-color--f6f701, #f6f701);
  d: path("M28.838 29.943c.12.021.252-.041.363.051q.04.056.005.117c-.07.059-.156.055-.239.056a.34.34 0 0 1-.158-.034c-.069-.055-.058-.112-.005-.171z");
}

.iu27bkbbn {
  fill: var(--svg-color--9b9b26, #9b9b26);
  d: path("m27.353 38.46l.001-.157l.204-.048c-.01.128-.114.161-.205.205");
}

.iuas6y-7z {
  fill: var(--svg-color--eef04d, #eef04d);
  d: path("m28.739 32.26l-.104.053l-.15-.008c.074-.081.167-.041.254-.045");
}

.iw9tqdbeq {
  fill: var(--svg-color--260a00, #260a00);
  d: path("m23.348 20.771l.112-.015l.244.02l-.1.049c-.072.06-.153.062-.238.035a.12.12 0 0 1-.06-.056a.3.3 0 0 0 .042-.033");
}

.iwa8ybb5v {
  fill: var(--svg-color--484905, #484905);
  d: path("M28.07 37.844c.067-.132.19-.207.296-.301c-.019.178-.144.252-.296.301");
}

.ix9su_bto {
  fill: var(--svg-color--dfe10d, #dfe10d);
  d: path("M17.908 34.18c.023-.042-.063-.1.017-.136q.029-.019.04.013l.052.044c.035.103-.027.156-.098.207z");
}

.ixj99obhy {
  fill: var(--svg-color--353600, #353600);
  d: path("m18.11 29.895l-.053-.005c-.058-.077-.061-.156 0-.235l.069-.064z");
}

.iy9c-ybld {
  fill: var(--svg-color--2b1202, #2b1202);
  d: path("m18.12 24.66l-.008-.051l.061-.041c-.017.084.033.18-.053.248l-.003-.053q.003-.05.003-.103");
}

.iz6huebdy {
  fill: var(--svg-color--f3f308, #f3f308);
  d: path("m14.263 24.303l.163-.16c.077-.169.233-.272.347-.412c.054-.048.115-.082.192-.069a.08.08 0 0 1 .049.046l.004.035a.3.3 0 0 1-.009.07q-.006.034-.015.068c-.051.155-.176.249-.291.349a.8.8 0 0 0-.282.284c-.042.066-.072.139-.114.204a.3.3 0 0 1-.07.072c-.056.036-.108.079-.169.11a.25.25 0 0 1-.17.004a.1.1 0 0 1-.048-.045c.012-.084.081-.132.125-.193l-.003.004c.061-.063.079-.157.161-.203l-.003.002c.017-.078.085-.115.133-.166");
}

.j_vob_bzh {
  fill: var(--svg-color--382b00, #382b00);
  d: path("m30.12 30.498l.003-.066c.065.036.154.004.204.077z");
}

.j_zc74ber {
  fill: var(--svg-color--d0ce0d, #d0ce0d);
  d: path("M22.832 24.669v.087c-.168.041-.336.023-.503.017c-.012-.087-.036-.188.114-.108c.036.018.078-.01.093-.055c.082.103.205.001.296.059");
}

.j-upue-0i {
  fill: var(--svg-color--710e08, #710e08);
  d: path("M29.655 31.29c-.072.074-.168.033-.252.05q-.034.017-.054-.014c.089-.115.193-.123.306-.036");
}

.j0pc73r_x {
  fill: var(--svg-color--686606, #686606);
  d: path("M26.607 25.694c-.015.064-.041.113-.121.089c-.031-.056.024-.067.047-.096l-.001.004z");
}

.j0v4gpb9d {
  fill: var(--svg-color--f3f407, #f3f407);
  d: path("m15.1 34.663l-.051-.144c.066-.1.183-.095.276-.138a.2.2 0 0 1 .072-.01c.041.005.074.02.094.058c.026.067.007.127-.031.183a.4.4 0 0 1-.215.054c-.05.029-.097.035-.145-.003");
}

.j11e1obnr {
  fill: var(--svg-color--2a3203, #2a3203);
  d: path("M12.838 30.802a.04.04 0 0 0-.026-.026l.184-.101a.2.2 0 0 1 .086.056c.102.148.286.119.424.194c.082.044.207.026.23.158a.1.1 0 0 1-.036.063c-.255.016-.485-.068-.712-.167c-.064-.033-.055-.115-.101-.159z");
}

.j1hu8o2lc {
  fill: var(--svg-color--68300f, #68300f);
  d: path("M28.84 32.508c.094-.079.207-.037.311-.055l.01.033c-.008.035-.034.055-.067.066h-.154c-.03-.027-.079-.005-.1-.044");
}

.j1vh4dvvj {
  fill: var(--svg-color--c5c587, #c5c587);
  d: path("m18.523 34.971l.008.053l-.053-.011q-.019-.023.004-.042q.02-.021.041 0");
}

.j2ofndv0o {
  fill: var(--svg-color--565501, #565501);
  d: path("M26.642 22.05c-.145.118-.145-.055-.205-.103c.085 0 .156.027.205.103");
}

.j2xep-bmy {
  fill: var(--svg-color--f4f504, #f4f504);
  d: path("m26.593 38.873l-.063-.161c.017-.055.063-.046.102-.05c.033.053.115.076.099.158z");
}

.j30azmbmw {
  fill: var(--svg-color--505109, #505109);
  d: path("M28.946 36.1c-.065.086-.184.029-.253.101q-.05-.004-.058-.053a.06.06 0 0 1 .005-.046c.063-.053.148-.004.214-.047l.089.002z");
}

.j31a1-b_o {
  fill: var(--svg-color--fdfd02, #fdfd02);
  d: path("m13.201 35.886l-.064-.094q-.062-.085-.041-.19a.39.39 0 0 1 .291-.276c.075-.017.151-.034.222-.069l.056-.031c.064-.035.137-.057.199-.098c.075-.048.163-.072.241-.112c.086-.036.173-.065.26-.095c.098-.035.199-.053.298-.09a.4.4 0 0 1 .063-.025c.084-.035.176-.045.26-.081q.126-.05.255-.095c.063-.021.13-.043.192-.068a.3.3 0 0 1 .135-.025c.149.042.263-.035.375-.115c.083-.031.171-.028.258-.029c.11.004.235-.04.309.09c.038.065.081.128.117.193c.031.086.068.172.041.267c-.091.17-.273.132-.416.185c-.12.015-.24.037-.354.087l-.163.071a.35.35 0 0 1-.172.034c-.122-.031-.217.026-.311.094c-.074.036-.156.046-.232.082c-.1.041-.205.063-.309.091l-.069.011a1 1 0 0 0-.231.056c-.099.028-.194.06-.264.145c-.198.121-.394.25-.607.35c-.103.02-.188.006-.233-.103l.003.003c-.062-.039-.075-.109-.109-.163");
}

.j3944qa7t {
  fill: var(--svg-color--1a1714, #1a1714);
  d: path("M19.459 37.22a.1.1 0 0 0 0-.036c.097-.007.181.006.197.127z");
}

.j3bd5rbfi {
  fill: var(--svg-color--eced54, #eced54);
  d: path("M27.26 36.667c-.014-.062-.064-.05-.106-.056c.08-.084.179-.041.271-.038c-.026.044-.106.018-.115.089a.3.3 0 0 1-.05.005");
}

.j3difobyg {
  fill: var(--svg-color--eaea67, #eaea67);
  d: path("M23.391 39.836q.008-.02.013-.039q.13 0 .257.003c-.081.075-.179.036-.27.036");
}

.j3kb3tsaz {
  fill: var(--svg-color--373205, #373205);
  d: path("m17.705 29.28l.111.017c.033.01.065.021.065.065q-.03.107-.14.105q-.028-.015-.022.017q0 .002.021.003c.089-.048.266.081.266-.137a.06.06 0 0 1 .016-.059h.15a.38.38 0 0 1-.001.289a.1.1 0 0 1-.041.013c-.031.019-.043.06-.081.069c-.102.012-.205-.021-.309.005c-.108.048-.043.199-.145.252a.11.11 0 0 1-.104-.026c-.057-.072-.064-.159-.055-.243c.029-.214-.056-.319-.272-.314a.15.15 0 0 1-.069-.039a.07.07 0 0 1-.003-.074c.129-.074.277-.048.417-.067a.15.15 0 0 1 .105.02c.04.029.058.073.091.104");
}

.j3nxc8q_q {
  fill: var(--svg-color--8d0000, #8d0000);
  d: path("m25.501 33.949l-.049.019c-.026-.072-.023-.13.065-.153c.076-.02.082.029.086.082c-.042-.001-.079.013-.102.052");
}

.j3yhwtbkh {
  fill: var(--svg-color--7b7b17, #7b7b17);
  d: path("M13.406 30.31v.042c-.067.085-.174.072-.262.107c.026-.159.156-.135.262-.149");
}

.j420qlbhk {
  fill: var(--svg-color--e3e356, #e3e356);
  d: path("m27.969 38.768l.092-.06l.008.108c-.043.004-.081-.003-.1-.048");
}

.j4puxouiu {
  fill: var(--svg-color--560b0c, #560b0c);
  d: path("m16.17 32.521l.015-.269l.028-.013l.015.026c-.02.114.046.239-.046.345z");
}

.j5ds9bbtb {
  fill: var(--svg-color--54520e, #54520e);
  d: path("M30.892 29.799q.042.005.083.007q.067.047.135.092c-.104.051-.188-.003-.274-.053c.004-.032.034-.034.056-.046");
}

.j6nqwrzxo {
  fill: var(--svg-color--fcfc00, #fcfc00);
  d: path("m19.2 40.514l.055-.057a.2.2 0 0 1 .054-.039c.064-.025.132.018.196-.008l.058.049c.017.209-.115.117-.207.104c-.055-.01-.122.024-.156-.049");
}

.j7tct8bqa {
  fill: var(--svg-color--414101, #414101);
  d: path("M15.959 25.588v3.182c-.029.058-.036.175-.137.053c-.063-.337-.042-.676-.015-1.014a.4.4 0 0 0 .069-.352c.01-.52.051-1.041-.02-1.561c-.094.01-.089-.092-.145-.125q-.014-.03.011-.049c.033-.017.071-.026.094-.06l.035-.046c.033-.025.065-.05.108-.028");
}

.j7w8k7b2i {
  fill: var(--svg-color--8d8e3d, #8d8e3d);
  d: path("M25.276 37.07c-.045.111-.124.168-.247.148c.045-.112.13-.154.247-.148");
}

.j8opehdjn {
  fill: var(--svg-color--e6e506, #e6e506);
  d: path("M23.24 20.924c.043-.005.087-.013.112-.056c.085-.041.172-.029.261-.008c.103.032.245-.053.303.106l-.007.014c-.085.098-.209-.028-.299.051c-.117-.014-.236.01-.352-.036a.056.056 0 0 1-.018-.071");
}

.j9-3m4vna {
  fill: var(--svg-color--4a340c, #4a340c);
  d: path("M28.657 33.02c.168-.055.219.039.231.181a.64.64 0 0 1-.231-.181");
}

.j9lvhxlif {
  fill: var(--svg-color--7d3934, #7d3934);
  d: path("M17.611 29.23c.075-.074.041-.169.048-.259c.104.088.025.201.046.3c-.04.003-.074-.003-.094-.041");
}

.j9uweybxe {
  fill: var(--svg-color--515049, #515049);
  d: path("m28.03 33.03l-.055-.056a.3.3 0 0 1 .036-.183c.045.038.058.108.125.12l.026.051c-.066-.024-.091.037-.132.068");
}

.jahvrhbxh {
  fill: var(--svg-color--66690c, #66690c);
  d: path("M16.847 38.573c.074-.054.128-.029.171.041c-.08.084-.119-.01-.171-.041");
}

.jas9qubuv {
  fill: var(--svg-color--410b00, #410b00);
  d: path("M26.23 40.07q0-.03-.003-.057c-.009-.045.032-.049.056-.068q.074-.02.147-.042q.042.027.009.063c-.033.11-.136.075-.209.104");
}

.jcoeunbdq {
  fill: var(--svg-color--2a2c00, #2a2c00);
  d: path("m14.12 34.811l-.068.05c-.129.039-.249.11-.389.095c-.011-.037.01-.061.033-.084q.047-.043.097-.083a.25.25 0 0 1 .124-.05c.065.002.135-.02.198.014q.021.018.015.037q-.004.022-.01.021");
}

.jcvo5bcir {
  fill: var(--svg-color--1c2a0e, #1c2a0e);
  d: path("M13.87 24.866q-.032-.003-.063-.002a.25.25 0 0 1 .167-.198z");
}

.jd_obebwf {
  fill: var(--svg-color--292a00, #292a00);
  d: path("m18.06 36.778l-.053.048l-.195-.015q-.003-.025-.002-.053z");
}

.jd7ril6oo {
  fill: var(--svg-color--110a01, #110a01);
  d: path("m17.04 29.534l-.007-.202c.08.02.053.117.108.153l.02.106c.029.089.009.183.015.274a.1.1 0 0 1-.026.072l-.024.003l-.024-.004q-.001-.025-.005-.05c-.081-.099-.071-.197-.002-.296z");
}

.jdduk8u6m {
  fill: var(--svg-color--f2f25a, #f2f25a);
  d: path("M27.435 25.417h-1.544v-.03h1.544z");
}

.jelxq1bnu {
  fill: var(--svg-color--5a3837, #5a3837);
  d: path("M16.479 33.894q.002-.052.007-.102c.125.051.13.126.046.222z");
}

.jff4oebhm {
  fill: var(--svg-color--c6c619, #c6c619);
  d: path("m18.961 34.723l-.112.15a.1.1 0 0 1-.063.025c-.065-.012-.095-.059-.116-.115a.13.13 0 0 1 .003-.069a.16.16 0 0 1 .074-.072a.15.15 0 0 1 .069-.01c.059.012.115.029.145.091");
}

.jg-mxkb4x {
  fill: var(--svg-color--b4af43, #b4af43);
  d: path("M21.813 25.559c-.181-.06-.368-.014-.552-.03a.84.84 0 0 1 .611.002q-.03.013-.059.028");
}

.jg0qkubxh {
  fill: var(--svg-color--133406, #133406);
  d: path("m18.836 21.17l.059.005a.08.08 0 0 1 .017.072c-.058.11-.183.079-.27.13c-.099.036-.199.076-.308.045a.13.13 0 0 1-.063-.047c.166-.133.359-.184.565-.205");
}

.jh7wahbxf {
  fill: var(--svg-color--150e01, #150e01);
  d: path("m26.07 24.654l-.192-.002l-.047-.08l.238-.002c.038.028.035.054.001.084");
}

.jhwlxgbxt {
  fill: var(--svg-color--2b2d00, #2b2d00);
  d: path("m15.814 36.98l.055.045c-.017.059-.066.037-.104.043c-.042-.043-.119.011-.154-.057l-.001-.043q.101.01.204.012");
}

.jj7h9zbdh {
  fill: var(--svg-color--f2f11e, #f2f11e);
  d: path("M24.339 39.747c-.041.054-.105.043-.161.056c-.005-.046-.013-.092-.058-.116l.04-.05q.061-.046.115.01c.003.044.02.081.064.1");
}

.jjhfrcwze {
  fill: var(--svg-color--e7decb, #e7decb);
  d: path("M26.473 25.02q.01-.177.017-.354c.176.097.104.25.09.39a.3.3 0 0 1-.051.072c-.064-.013-.037-.072-.056-.108");
}

.jjnahwizo {
  fill: var(--svg-color--190d00, #190d00);
  d: path("m31.47 29.799l.195.094c-.095.035-.152-.015-.195-.094");
}

.jjzi_jbst {
  fill: var(--svg-color--f2f20b, #f2f20b);
  d: path("M25.442 35.23c.044.142-.023.273-.038.409l-.046.05c-.055-.01-.081-.05-.097-.097a.24.24 0 0 1-.007-.107a1 1 0 0 1 .067-.202c.031-.041.065-.069.121-.053");
}

.jk05edc5p {
  fill: var(--svg-color--cbca0b, #cbca0b);
  d: path("M14.07 24.917c.043-.061.196-.01.153-.153c.056.051.104.145.194.041c.032.007.061.021.078.052a.1.1 0 0 1 0 .063a.11.11 0 0 1-.115.045c-.104-.002-.224.082-.31-.048");
}

.jk7k4-bjq {
  fill: var(--svg-color--f6f705, #f6f705);
  d: path("m20.43 40.673l.052.092c-.074.048-.151.031-.228.007l-.184-.016q-.043-.058.007-.111c.077-.046.162-.026.246-.027c.043.002.082.015.107.055");
}

.jkqhvbo4m {
  fill: var(--svg-color--f5f609, #f5f609);
  d: path("m27.55 34.507l.049-.063q.03.012.051.038c.058.078.148.119.221.182l.204.104c.027.091.138.135.136.242a.11.11 0 0 1-.061.086c-.05.016-.097.003-.143-.017a.4.4 0 0 1-.063-.035c-.073-.056-.132-.126-.211-.176a2 2 0 0 1-.212-.174c-.059-.072-.006-.13.029-.187");
}

.jl_r1hmqe {
  fill: var(--svg-color--1c1400, #1c1400);
  d: path("M25.765 35.18h-.043q-.005-.025-.007-.053l.021-.017q.029.001.046.023c.007.022-.002.037-.017.047");
}

.jly6tacaa {
  fill: var(--svg-color--152c02, #152c02);
  d: path("M15.607 38.677q.079.046.156.087a.1.1 0 0 1 .015.043c-.106.021-.154-.034-.171-.13");
}

.jm6fvub1x {
  fill: var(--svg-color--f0f152, #f0f152);
  d: path("M21.349 21.483a.1.1 0 0 0 .014.032q-.158.015-.315.026c-.053.033-.104.04-.151-.008c.14-.101.301-.029.452-.05");
}

.jmc4y4bhf {
  fill: var(--svg-color--717000, #717000);
  d: path("m20.78 40l.195-.006l.028.042l-.06.054l-.056.012c-.047-.02-.104-.034-.107-.102");
}

.jnex5xbjs {
  fill: var(--svg-color--eee508, #eee508);
  d: path("m22.284 24.399l-.059.069c-.124.076-.255.066-.387.041c-.044-.017-.082-.04-.082-.094q.002-.035.007-.071c.044-.038.088-.075.15-.084a.4.4 0 0 1 .099.005a.24.24 0 0 0 .211-.027a.05.05 0 0 1 .053.026z");
}

.jnqmbnjvw {
  fill: var(--svg-color--6c6c0e, #6c6c0e);
  d: path("M26.583 22.766a.1.1 0 0 0 .002-.045c.102 0 .166.055.207.143c-.088.005-.151-.04-.209-.098");
}

.jo7rsdipk {
  fill: var(--svg-color--312f09, #312f09);
  d: path("m27.878 36.34l-.214.018c-.108.033-.15.002-.106-.113c.118.04.252-.02.361.06a.1.1 0 0 1-.041.035");
}

.jo7woacbz {
  fill: var(--svg-color--5b5a0b, #5b5a0b);
  d: path("M31.3 34.37c.017.117-.048.209-.096.305c-.032-.006-.037-.035-.052-.057c.035-.092.021-.212.148-.248");
}

.johg6ebij {
  fill: var(--svg-color--eaeb18, #eaeb18);
  d: path("M19.16 35.08c.038.079.117.145.062.247a.1.1 0 0 0-.031.003c-.086.021-.125-.036-.166-.094a.14.14 0 0 1-.01-.067c.011-.049.034-.087.087-.097z");
}

.jotzt5blg {
  fill: var(--svg-color--213b0d, #213b0d);
  d: path("M17.352 39.81c.085.038.184.051.243.138c-.099.004-.195.004-.247-.102q0-.02.004-.036");
}

.jpk8gub8n {
  fill: var(--svg-color--6d0602, #6d0602);
  d: path("m27.07 37.492l.281-.016q.033-.019.056.012c-.076.127-.197.092-.311.091c-.023-.015-.053-.023-.063-.053a.04.04 0 0 1 .037-.034");
}

.jrye_48ii {
  fill: var(--svg-color--eaea15, #eaea15);
  d: path("M25.09 39.38q.003-.017.01-.029c.046-.11.154-.05.229-.084c.115-.038.219-.103.332-.142h-.005c.059-.047.132-.057.2-.078c.056-.005.092.021.12.065c.019.054-.015.089-.049.122a.7.7 0 0 0-.259.143c-.104-.043-.159.135-.27.058c-.042.077-.115.081-.19.074a.22.22 0 0 1-.118-.13");
}

.js7gvtbbi {
  fill: var(--svg-color--fdfd02, #fdfd02);
  d: path("M28.989 31.688a.2.2 0 0 0 .023-.043l.036-.006c.051-.036.115-.033.169-.058c.079-.01.158-.002.235-.024a.4.4 0 0 1 .063-.021c.135-.102.317-.001.452-.104c.099-.06.207-.05.313-.051a.7.7 0 0 1 .393-.098l.062-.039c.099-.105.202-.098.309-.012l.003.303l-.046.209c-.097.034-.215.034-.263.152l-.029.017a.67.67 0 0 0-.346.095a.2.2 0 0 1-.063.017c-.126-.018-.238.031-.354.067c-.078.02-.161.023-.236.053c-.07.021-.14.046-.212.061c-.061.012-.122.012-.185.014c-.094.005-.19-.019-.277.036a.3.3 0 0 1-.063.038c-.07.018-.144.01-.214.012c-.08.001-.161-.006-.238.024c-.033.008-.067.005-.099.021l-.245.01q-.005-.132-.013-.266c.013-.102-.009-.211.058-.305c.172.141.296-.131.46-.054c.107-.006.218.047.307-.048");
}

.jt9ecobos {
  fill: var(--svg-color--6d6d0e, #6d6d0e);
  d: path("m17.445 22.776l-.142.091c-.016-.13.037-.151.142-.091");
}

.ju9-n0rcc {
  fill: var(--svg-color--dbdd16, #dbdd16);
  d: path("M13.461 25.08c.136.103.321-.039.453.093a.7.7 0 0 1-.309.05c-.045-.105-.135-.028-.201-.05c-.003-.044-.001-.084.057-.093");
}

.juy31g0rs {
  fill: var(--svg-color--dad39d, #dad39d);
  d: path("M25.763 35.13q.025-.007.049-.005a.1.1 0 0 1-.003.05l-.023-.002h-.021q0-.022-.002-.043");
}

.jv377sfdr {
  fill: var(--svg-color--1c2e1b, #1c2e1b);
  d: path("M17.195 35.645q0-.03.003-.058q.08.101.154.205H17.3c-.062-.029-.102-.075-.105-.147");
}

.jwym5i4tt {
  fill: var(--svg-color--881a08, #881a08);
  d: path("M24.587 40.615c-.094.202-.246.178-.412.105l-.002-.006c-.007-.113.089-.09.149-.114c.047-.007.093-.021.139-.026a.17.17 0 0 1 .104.015z");
}

.jxgnoacpo {
  fill: var(--svg-color--747500, #747500);
  d: path("m18.02 35.434l-.055-.002q.002-.025.002-.051a.2.2 0 0 0 .049 0z");
}

.jxh4fdbnr {
  fill: var(--svg-color--444200, #444200);
  d: path("M26.393 36.723a.06.06 0 0 0 .047-.005c.058-.019.132-.084.139.048l-.056.044c-.088.048-.175.063-.255-.013c.005-.082.083-.048.125-.074");
}

.jxpp2ub_g {
  fill: var(--svg-color--eae60f, #eae60f);
  d: path("M22.638 20.748c.202.031.416-.029.611.069c-.021.044-.061.067-.104.085c-.089.028-.182.007-.271.023a.2.2 0 0 1-.067.01c-.071-.027-.163.007-.217-.072c-.015-.05-.005-.092.048-.115");
}

.jz5ucwbwb {
  fill: var(--svg-color--552209, #552209);
  d: path("M28.07 38.871q.106-.045.209-.094c-.019.154-.097.23-.257.207c-.002-.046 0-.088.048-.113");
}

.k_0q4pbmm {
  fill: var(--svg-color--262700, #262700);
  d: path("M13.957 32c-.171.116-.278-.006-.392-.103c.144-.016.267.046.392.103");
}

.k_4dh1zwx {
  fill: var(--svg-color--cac510, #cac510);
  d: path("M19.445 35.29c.01.104-.075.142-.133.197c-.05.037-.086.007-.122-.025a.14.14 0 0 1-.024-.064l.002-.035a.1.1 0 0 1 .037-.054a.4.4 0 0 1 .191-.051q.038 0 .049.032");
}

.k_6_rrbys {
  fill: var(--svg-color--232200, #232200);
  d: path("m30.533 25.992l.053.056c-.146.132-.18-.021-.244-.096l.086.004c.044-.012.075.01.105.036");
}

.k_ov9rx9j {
  fill: var(--svg-color--dfe258, #dfe258);
  d: path("M15.564 36.407c.096-.04.206-.151.248.052c-.072-.068-.173.006-.248-.052");
}

.k--oml4mp {
  fill: var(--svg-color--efee0a, #efee0a);
  d: path("m28.02 38.984l-.026.038c-.095.038-.154.125-.243.169a.1.1 0 0 1-.067-.006c-.061-.047-.109-.096-.089-.18c.093-.123.188-.242.354-.27a.23.23 0 0 1 .125.064a.1.1 0 0 1 .019.066c-.005.054-.042.083-.073.119");
}

.k-06hlb7i {
  fill: var(--svg-color--606000, #606000);
  d: path("M13.758 26.936v-.058c.071-.005.082.064.122.097q-.06.055-.117.112c-.133-.046-.041-.101-.005-.151");
}

.k-obc279v {
  fill: var(--svg-color--535400, #535400);
  d: path("M27.1 37.28c.125-.077.263-.056.399-.049c-.064.09-.186.016-.255.09c-.064.04-.126.078-.144-.041");
}

.k0fb3jtea {
  fill: var(--svg-color--dad835, #dad835);
  d: path("m24.88 35.07l.031.109c.029.121-.048.146-.143.154q-.015 0-.026.003l-.063-.161c.091.011.14-.056.201-.105");
}

.k0nitkbad {
  fill: var(--svg-color--f9f804, #f9f804);
  d: path("M25.907 25.703q.01-.058.017-.115c.13-.079.263-.069.397-.017a.15.15 0 0 1 .048.106a.3.3 0 0 1-.012.074c-.041.077-.048.164-.068.246a.2.2 0 0 1-.066.047c-.111.025-.224.036-.323-.043c-.06-.101-.012-.198.007-.298");
}

.k0v2atbcr {
  fill: var(--svg-color--d4d24d, #d4d24d);
  d: path("m17.26 29.12l.296.007q.02.014.016.033l-.003.018c-.148.105-.313.031-.467.046c-.034-.067-.034-.114.063-.106z");
}

.k16xzcb-d {
  fill: var(--svg-color--103204, #103204);
  d: path("M16.735 37.441q0 .023.003.044c-.161.005-.32.001-.46-.094a.14.14 0 0 1 .063-.054c.149-.029.287-.024.394.104");
}

.k1j5spbvb {
  fill: var(--svg-color--1a1a00, #1a1a00);
  d: path("M25.661 35.12v-.044q.025-.028.057-.009q.022.029-.003.056v.002z");
}

.k1pu5nbck {
  fill: var(--svg-color--777600, #777600);
  d: path("m18.533 34.921l-.055-.001a.2.2 0 0 0 0-.052h.052z");
}

.k2itl2buh {
  fill: var(--svg-color--2f2d00, #2f2d00);
  d: path("M31.465 33.792h.029c-.021.114-.013.245-.141.311c.008-.114.063-.212.112-.311");
}

.k2s-eyb9v {
  fill: var(--svg-color--2a2d0d, #2a2d0d);
  d: path("m12.307 28.865l-.031-.048c.007-.08-.039-.186.099-.198a8 8 0 0 0-.068.246");
}

.k3q570bsz {
  fill: var(--svg-color--25440a, #25440a);
  d: path("M18.02 37.692c-.224-.012-.459.04-.663-.104q-.029-.034.002-.067a.17.17 0 0 1 .113-.021c.099.023.202.02.303.045c.11.042.238.003.344.075q.03.032.015.072q-.058.042-.114 0");
}

.k47yssb0y {
  fill: var(--svg-color--062000, #062000);
  d: path("M15.916 25.387c.002.053-.006.109.043.148v.053l-.084.046l-.111-.062q-.02-.027-.005-.059c.031-.046.058-.094.099-.132q.031-.018.058.006");
}

.k6edmcbsa {
  fill: var(--svg-color--fdfd02, #fdfd02);
  d: path("m26.02 39.896l-.091.047c-.06.039-.128.051-.195.068c-.093.064-.204.092-.293.161a.4.4 0 0 1-.087.051a.3.3 0 0 1-.066.014c-.102-.004-.187.059-.284.075a.5.5 0 0 0-.215.086l-.06.036a.2.2 0 0 1-.067.01c-.09-.003-.188-.038-.265.044a.1.1 0 0 1-.038.048a.17.17 0 0 1-.093.017c-.045-.005-.086-.019-.13-.025c-.073-.003-.146-.022-.208.038a.4.4 0 0 1-.068.071a.2.2 0 0 1-.066.021c-.082.003-.157-.031-.238-.03c-.087 0-.176-.017-.256.031a1 1 0 0 1-.086.055a.3.3 0 0 1-.169.039c-.127.005-.238-.063-.363-.065c-.166-.14-.034-.326-.074-.483a.1.1 0 0 1 .026-.072c.138-.087.303-.015.444-.072c.041-.026.075-.06.116-.084a.2.2 0 0 1 .106-.015a1 1 0 0 0 .208.023c.099-.011.203.029.289-.052a.3.3 0 0 1 .079-.07c.07-.033.145-.033.218-.036a1.6 1.6 0 0 0 .382-.07l.092-.048a.4.4 0 0 1 .165-.046c.109.024.182-.045.261-.103a.4.4 0 0 1 .128-.036a.6.6 0 0 0 .271-.105c.093-.005.152-.097.246-.098c.091-.011.168-.053.247-.093c.07-.032.14-.07.213-.097q.11-.036.214-.091a.5.5 0 0 0 .164-.104c.03-.033.058-.068.094-.094c.047-.031.098-.055.146-.081c.132-.061.243-.151.363-.231c.077-.048.153-.099.237-.133a.55.55 0 0 0 .212-.166a.5.5 0 0 1 .197-.141c.092-.025.149-.092.205-.164a1 1 0 0 1 .128-.117c.122-.072.211-.179.296-.289c.132-.092.232-.213.341-.33c.11-.089.214-.183.294-.299a1.2 1.2 0 0 1 .183-.207a.43.43 0 0 0 .147-.182a.3.3 0 0 1 .069-.082a.22.22 0 0 1 .211-.044c.077.038.147.082.186.166c.003.121.115.21.102.339c-.031.131-.125.22-.21.316c-.113.048-.216.113-.27.232q-.133.16-.269.318c-.099.048-.157.145-.251.197a1 1 0 0 1-.255.257c-.13.061-.19.214-.334.257l-.243.249c-.018.04-.028.093-.092.06c-.153.039-.23.184-.36.256c-.036.089-.115.129-.19.172c-.05.018-.101.031-.146.059l-.054.029c-.052.03-.115.043-.156.091c-.151.024-.249.144-.372.214c-.065.005-.116.044-.171.074c-.085.02-.161.063-.238.104c-.061.027-.121.057-.154.123l-.009.01q-.047.04-.094-.003");
}

.k6nmsdj4n {
  fill: var(--svg-color--eef4f9, #eef4f9);
  d: path("M22.526 30.522c-.146-.009-.201-.058-.197-.146c.003-.089.063-.134.152-.132c.086.002.132.063.127.13s-.031.153-.082.148");
}

.k7gxh6_wl {
  fill: var(--svg-color--670a0b, #670a0b);
  d: path("M26.22 36.01c-.01-.165.098-.23.233-.27q-.115.136-.233.27");
}

.k884mzsnr {
  fill: var(--svg-color--313200, #313200);
  d: path("M29.459 26.1a.05.05 0 0 1 0-.048c.053-.065.11-.119.201-.115c.108.06.132.166.156.271c-.093-.119-.228-.106-.357-.108");
}

.k8mwurbzf {
  fill: var(--svg-color--636518, #636518);
  d: path("m31.15 34.613l.052.057c-.027.085-.063.162-.156.195z");
}

.k8vj8bcyg {
  fill: var(--svg-color--646508, #646508);
  d: path("m13.11 29.756l.205-.051c.03.019.076-.003.099.039c-.092.074-.213.059-.315.103z");
}

.k92n9dznc {
  fill: var(--svg-color--181700, #181700);
  d: path("m18.377 35.07l.005.057l-.053-.003h-.001q-.018-.015-.014-.031q.003-.019.009-.019q.015-.006.026-.013l.028.01");
}

.k9htqtbqv {
  fill: var(--svg-color--f2e525, #f2e525);
  d: path("M23.15 20.87c.023-.041.061-.052.104-.053l.058-.013a.2.2 0 0 1 .046.014a.08.08 0 0 1 .026.059c-.012.051-.046.073-.092.085a.24.24 0 0 1-.097-.003a.2.2 0 0 1-.057-.033q-.015-.032.012-.056");
}

.k9sdg_l6x {
  fill: var(--svg-color--e6e606, #e6e606);
  d: path("M21.05 21.595c.017-.003.034-.01.049-.007c.103.03.27-.084.3.058c.039.188-.201.024-.249.142c-.229.099-.478.048-.715.094c-.063-.01-.095-.051-.12-.104a.15.15 0 0 1-.006-.077c.02-.051.061-.072.113-.079c.089.031.179.008.268.002a.4.4 0 0 0 .262-.016a.2.2 0 0 1 .098-.013");
}

.kb_2s943r {
  fill: var(--svg-color--fdfd02, #fdfd02);
  d: path("m31.773 29.952l-.108-.06a.5.5 0 0 1-.195-.094q-.07-.025-.14-.053c-.199-.095-.115-.303-.183-.45a1 1 0 0 1-.013-.151c.008-.13-.033-.253-.064-.378l-.021-.063c-.038-.117-.056-.237-.082-.355l-.02-.063a2 2 0 0 0-.089-.274l-.021-.063c-.02-.084-.064-.159-.096-.24l-.021-.061c-.028-.083-.038-.171-.081-.249c-.044-.075-.07-.16-.106-.241q-.048-.106-.101-.208l-.105-.208a1 1 0 0 0-.1-.173c-.078-.133-.171-.258-.185-.419c.015-.085.021-.174.101-.231a.2.2 0 0 1 .072-.021a.3.3 0 0 1 .105.015c.088.041.152.14.27.101q.054-.007.104.015a.23.23 0 0 1 .087.105c.026.073.063.145.085.22c.014.079.057.145.096.213c.033.07.048.154.128.191l.108.27c-.02.103.06.176.076.269c.053.108.07.229.128.339q.051.108.104.213a.48.48 0 0 0 .102.353q0 .03.002.059c0 .128.045.249.076.372c.005.099.061.184.068.281c.012.063.01.126.033.186c-.007.102.036.2.028.303a.25.25 0 0 1 .051.179c-.009.077.048.142.046.216c-.003.084.01.191-.139.155");
}

.kc-o46bdq {
  fill: var(--svg-color--efed7c, #efed7c);
  d: path("m16.69 25.07l-.01.058l-.024.005l-.023-.008l.007-.253a.07.07 0 0 1 .046.004q.08.096.004.194");
}

.kc18uobsh {
  fill: var(--svg-color--cbb9a1, #cbb9a1);
  d: path("M30.832 28.55c-.058-.056-.034-.135-.055-.2c.016-.014.031-.083.05-.014c.018.066.005.142.005.214");
}

.ke9xteb9l {
  fill: var(--svg-color--f3f205, #f3f205);
  d: path("m16.539 25.998l-.005-.26c.02-.095-.008-.201.067-.284c.201-.039.408-.118.579.073q.012.041.005.086c-.086.144-.132.313-.27.423c-.129.038-.259.058-.376-.038");
}

.kegs2ndcc {
  fill: var(--svg-color--0a2902, #0a2902);
  d: path("m16.382 22.408l-.058-.003a.33.33 0 0 1 .315-.149c-.09.041-.124.181-.257.152");
}

.kes7w7bxk {
  fill: var(--svg-color--282b00, #282b00);
  d: path("M28.893 24.764v.051q-.13-.048-.26-.1c.106-.091.178.008.26.049");
}

.ketr6bcmo {
  fill: var(--svg-color--919407, #919407);
  d: path("m26.486 26.05l.35-.003c-.115.09-.233.087-.35.003");
}

.kf655wbib {
  fill: var(--svg-color--51510b, #51510b);
  d: path("M29.814 30.15v-.047l.31.057q.039.041 0 .082c-.099-.044-.218-.019-.31-.092");
}

.khx0g4b6m {
  fill: var(--svg-color--35430d, #35430d);
  d: path("m13.616 34.2l-.039.007c-.147-.369-.293-.738-.368-1.13q.045-.043.091.002c.077.265.133.539.244.789c.052.115.052.222.072.332");
}

.ki-h0bc6f {
  fill: var(--svg-color--f0ed1d, #f0ed1d);
  d: path("M27.334 22.463c.043-.055.128-.076.125-.164l.048.016c.07.037.156.05.195.134l.009.017l-.053.156c-.046.02-.088 0-.129-.018c-.058-.03-.12-.051-.179-.08a.08.08 0 0 1-.016-.061");
}

.kifo2ltpy {
  fill: var(--svg-color--737100, #737100);
  d: path("m23.857 39.997l-.104-.01l-.097-.046c.063-.057.141-.043.215-.048z");
}

.kijj8zbfa {
  fill: var(--svg-color--5a140f, #5a140f);
  d: path("M17.908 34.18c-.056.064-.138.011-.2.045c-.01-.12.104-.159.158-.237c.041-.015.058.01.068.043c-.026.045.034.108-.026.149");
}

.kit7k5kne {
  fill: var(--svg-color--cacbb1, #cacbb1);
  d: path("M12.03 29.03c.048.115.075.229-.023.334l-.006-.083c0-.083-.043-.173.029-.251");
}

.kj-a6zbjl {
  fill: var(--svg-color--fcfa1f, #fcfa1f);
  d: path("m18.685 34.656l.002-.037l.008-.025l.024-.002l.017.021l.005.054z");
}

.kjkdyfbfd {
  fill: var(--svg-color--1d1900, #1d1900);
  d: path("M24.888 37.887q-.203.005-.405.013l.005-.017q-.03-.039.017-.061c.104-.007.208-.002.313-.003c.042.003.078.011.07.068");
}

.kjsl2j77p {
  fill: var(--svg-color--4e4f0b, #4e4f0b);
  d: path("m24.48 40.476l-.102.001q.116-.178.296-.065c-.051.065-.133.033-.194.064");
}

.kka3jqjwl {
  fill: var(--svg-color--61360c, #61360c);
  d: path("M23.864 37.945v.04l-.36.003l-.005-.034c.017-.045.053-.067.089-.091c.039-.023.075-.046.122-.021l.056.063c.027.025.075.004.098.04");
}

.kkqbytb4c {
  fill: var(--svg-color--393200, #393200);
  d: path("M17.26 29.12c-.007-.272.193-.089.29-.135c.055.053.052.105.002.158c-.102.042-.202.066-.292-.023");
}

.kky7labnb {
  fill: var(--svg-color--5d3e3f, #5d3e3f);
  d: path("M20.83 35.28c.104-.06.187-.007.27.052c-.094.002-.195.037-.27-.052");
}

.kmozguqzg {
  fill: var(--svg-color--d8d61b, #d8d61b);
  d: path("M24.954 35.568q-.034.012-.067.021a.6.6 0 0 1-.206-.205a.1.1 0 0 1 .058-.072a.1.1 0 0 1 .063.003a.4.4 0 0 1 .123.105c.03.045.061.09.029.148");
}

.kmpbx690f {
  fill: var(--svg-color--41370e, #41370e);
  d: path("M27.55 25.944c.018.054-.011.126.057.164c.017.043-.011.058-.044.071a.2.2 0 0 1-.067-.012a.2.2 0 0 1-.079-.11a.2.2 0 0 1-.008-.069a.15.15 0 0 1 .036-.097c.057-.028.083.007.105.053");
}

.knyq49rfj {
  fill: var(--svg-color--e0ddd7, #e0ddd7);
  d: path("m12.13 31.433l-.019-.152l.017-.104q.1.125.002.256");
}

.kp29nr3uq {
  fill: var(--svg-color--181d00, #181d00);
  d: path("m29.3 36.21l-.017-.007h-.018c-.058-.004-.079-.048-.097-.094c-.009-.038-.004-.072.029-.097l.048-.063c-.035.143.131.157.164.256z");
}

.kpth1i2zv {
  fill: var(--svg-color--626107, #626107);
  d: path("m30.892 29.799l-.057.046c-.085-.07-.249.015-.287-.147a.7.7 0 0 1 .344.101");
}

.ks0crhb8y {
  fill: var(--svg-color--585700, #585700);
  d: path("m14.736 24.613l-.007.085c-.026.072-.063.12-.145.063q-.027-.044-.051-.089z");
}

.ks1au7bay {
  fill: var(--svg-color--e7ea15, #e7ea15);
  d: path("m24.426 34.913l.062.104c.027.058.044.113-.009.166q-.068-.054-.131-.113c-.139-.136-.053-.159.078-.157");
}

.ks1vnybrn {
  fill: var(--svg-color--474204, #474204);
  d: path("M31.956 33.12h-.084c-.075-.181-.077-.333.142-.412h.004z");
}

.kstea_2aq {
  fill: var(--svg-color--490e02, #490e02);
  d: path("m26.02 22.655l.058.06c-.096.016-.168-.014-.211-.104z");
}

.kt3wwjold {
  fill: var(--svg-color--2c2c00, #2c2c00);
  d: path("M29.2 24.857v-.024l.101-.008c.038.059.132.017.161.092c-.127.154-.175-.041-.262-.06");
}

.kt6hmtbyq {
  fill: var(--svg-color--eaec5a, #eaec5a);
  d: path("M17.203 36.512c.093.004.187-.011.27.041c-.092-.001-.191.047-.27-.041");
}

.ktblyu61g {
  fill: var(--svg-color--2b2000, #2b2000);
  d: path("m29.698 26.922l-.028-.006c.036-.154.142-.123.246-.089l-.001.082q-.108.008-.217.013");
}

.ktwev-btn {
  fill: var(--svg-color--223b08, #223b08);
  d: path("M12.07 32.863c.052.133.108.266.108.414c-.151-.108-.112-.266-.108-.414");
}

.ku5_5nb2e {
  fill: var(--svg-color--28240d, #28240d);
  d: path("M22.03 24.677c.054.075.069.155.022.18c-.07.034-.07-.042-.068-.089c.001-.022.02-.043.046-.091");
}

.ku7s52jer {
  fill: var(--svg-color--1a1800, #1a1800);
  d: path("M25.04 34.457h-.021c.009-.041.016-.017.021.001");
}

.kupb_mb3x {
  fill: var(--svg-color--e8e70d, #e8e70d);
  d: path("M28.18 31.793c-.038-.074-.128-.148.002-.221c.097-.082.212-.095.33-.087h.079c.089.009.181-.021.268.019q.035.023.048.063a.16.16 0 0 1-.05.104a.3.3 0 0 1-.174.078a2 2 0 0 0-.433.063a.14.14 0 0 1-.07-.019");
}

.kwnm7fz9l {
  fill: var(--svg-color--f2ef08, #f2ef08);
  d: path("M23.353 40.861q-.179.007-.358.017a.85.85 0 0 1-.402-.007c-.024-.186.128-.072.19-.113c.082-.063.171-.016.257-.018c.1.016.203-.061.302.003q.06.054.011.118");
}

.kws_y618f {
  fill: var(--svg-color--4d4c00, #4d4c00);
  d: path("m26.28 39.742l.052.031l-.204.115c-.014-.115.048-.154.152-.146");
}

.kwwi0cbch {
  fill: var(--svg-color--545400, #545400);
  d: path("M30.632 25.801q-.053.024-.105.045c-.036.024-.067.031-.089-.018l-.008-.033v-.05q.1.03.202.056");
}

.kxbngpb1b {
  fill: var(--svg-color--f0f32b, #f0f32b);
  d: path("M26.18 25.02c.077-.003.106.035.1.108a.6.6 0 0 1-.263.002q-.028-.034-.003-.07c.044-.061.096-.086.166-.04");
}

.kxxjzwpsu {
  fill: var(--svg-color--3a240a, #3a240a);
  d: path("M27.447 24.638c-.121.059-.227-.034-.344-.04c.122-.051.24-.068.355.017q-.006.01-.011.023");
}

.kzr68za9e {
  fill: var(--svg-color--62640e, #62640e);
  d: path("M17.617 38.977c.058.022.134.018.153.1c-.096.035-.149.006-.153-.1");
}

.l-unu_b3n {
  fill: var(--svg-color--e2e453, #e2e453);
  d: path("m15.13 29.07l.123-.054h.128l.074.054z");
}

.l0ceprb4i {
  fill: var(--svg-color--414506, #414506);
  d: path("M30.12 30.24v-.082l.207.094c-.074.091-.139-.015-.207-.012");
}

.l0sg5dgub {
  fill: var(--svg-color--63220a, #63220a);
  d: path("m28.677 38.438l.009.061c-.057.156-.156.246-.334.22l.082-.147a.4.4 0 0 0 .243-.134");
}

.l132kvb8t {
  fill: var(--svg-color--272100, #272100);
  d: path("M18.17 25.28a.06.06 0 0 0 .014-.048c.087.091.051.176-.01.26q-.027-.03-.056-.056a.06.06 0 0 1 .044-.043z");
}

.l3lpogity {
  fill: var(--svg-color--f5f305, #f5f305);
  d: path("m24.892 21.998l.005.037l-.01.13c-.033.019-.066.012-.099.002a.06.06 0 0 0-.046-.015c-.081-.009-.17.008-.224-.078c-.002-.044.037-.054.063-.076l.012-.01z");
}

.l3xdj7bqw {
  fill: var(--svg-color--e9f0f6, #e9f0f6);
  d: path("M22.602 33.02c0 .089-.048.15-.135.153c-.086.003-.142-.05-.145-.144c-.002-.082.049-.128.121-.14c.089-.012.142.042.159.131");
}

.l47kf0bqh {
  fill: var(--svg-color--6b190a, #6b190a);
  d: path("M28.837 26.04a.32.32 0 0 1 .268-.129q.03.013.056.031q.014.034-.017.055z");
}

.l4806vo2r {
  fill: var(--svg-color--66220a, #66220a);
  d: path("m27.711 39.19l.054.045c-.018.11-.106.101-.186.104q-.032.037-.069.009c-.013-.149.091-.171.202-.181z");
}

.l4a_uq91o {
  fill: var(--svg-color--022100, #022100);
  d: path("M11.759 31.17q.028.026.053.053c.043.048.025.105.03.159a.2.2 0 0 1-.047.127l-.025.021c-.17-.117-.149-.236-.011-.36");
}

.l4ff8jb9w {
  fill: var(--svg-color--5b5c09, #5b5c09);
  d: path("M30.752 33.946c-.014-.116.054-.209.095-.31q.027-.03.048.006c.005.118-.053.213-.12.304z");
}

.l4jk2ib8b {
  fill: var(--svg-color--525301, #525301);
  d: path("M14.342 28.461c-.105-.002-.173-.051-.194-.158c.144-.046.172.052.194.158");
}

.l4u51zb9f {
  fill: var(--svg-color--4d3a0b, #4d3a0b);
  d: path("M30.17 37.26c-.007-.102-.083-.079-.144-.082c-.063-.066-.026-.115.028-.161a.4.4 0 0 0 .181 0a.06.06 0 0 1-.008.069c-.006.062.025.136-.057.174");
}

.l5ja5-17d {
  fill: var(--svg-color--4c4d08, #4c4d08);
  d: path("M15.558 38.36c.11 0 .163.087.23.151c-.151.064-.166-.08-.23-.151");
}

.l5ky36byh {
  fill: var(--svg-color--edf05b, #edf05b);
  d: path("m17.15 37.488l.301.01c.003 0 .01.016.008.021c-.001.007-.01.014-.015.02l-.091.006z");
}

.l5m9kcb_m {
  fill: var(--svg-color--f3f34e, #f3f34e);
  d: path("M26.02 37.445q-.051-.005-.104-.013c.094-.092.209-.039.313-.043c-.069.021-.139.037-.209.056");
}

.l5umebb5u {
  fill: var(--svg-color--fefc02, #fefc02);
  d: path("m26.02 39.896l.093.002c.043.056.105.046.165.049l-.056.068l-.142.042c-.066-.036-.065-.098-.06-.161");
}

.l5xfmnpqd {
  fill: var(--svg-color--e3e519, #e3e519);
  d: path("M15.819 24.1c-.005.139-.137.178-.205.265c-.076.062-.146.043-.213-.011l.18-.254c.079-.032.159-.071.238 0");
}

.l6_dtzbkd {
  fill: var(--svg-color--f4f50d, #f4f50d);
  d: path("M18.566 39.39c.048-.019.063-.058.07-.104l.028-.02c.102.011.202.024.279.104a.1.1 0 0 0 .046.015c.154.065.349.032.467.19c.043.005.091 0 .104.059q.04.053.008.111c-.037.027-.073.022-.109-.004l-.207-.053c-.078-.023-.158-.034-.228-.079c-.104-.011-.195-.072-.296-.102c-.065-.021-.149-.021-.162-.117");
}

.l67avqb8d {
  fill: var(--svg-color--274415, #274415);
  d: path("m13.616 28.13l.088.034l.063.085q-.028.03-.059.004c-.075-.007-.102-.051-.092-.123");
}

.l6dl-bbgk {
  fill: var(--svg-color--484608, #484608);
  d: path("M15.506 25.699a.07.07 0 0 1-.002-.046l.162.04c.021.02.057.031.045.07l.002.008c-.083.014-.16.014-.207-.072");
}

.l6yhnkilm {
  fill: var(--svg-color--dcdc17, #dcdc17);
  d: path("M22.532 24.92c.207-.126.226-.013.199.158c-.086.059-.156.034-.215-.043a.11.11 0 0 1 .016-.115");
}

.l6z56lbke {
  fill: var(--svg-color--51501a, #51501a);
  d: path("M12.788 34.452c.089.043.097.125.102.209c-.141-.017-.128-.11-.102-.209");
}

.l7j212w-o {
  fill: var(--svg-color--201900, #201900);
  d: path("m26.749 29.11l-.168-.036c-.077.003-.077-.034-.049-.089c.102-.008.239-.076.217.125");
}

.l879lzbep {
  fill: var(--svg-color--eae8a5, #eae8a5);
  d: path("m18.514 36.09l.018.054q.028.037-.018.047c-.041-.025-.033-.062-.021-.098z");
}

.l8i_5iery {
  fill: var(--svg-color--eaf4f9, #eaf4f9);
  d: path("M20.409 30.26c.026.005.078.054.068.145c-.011.089-.073.128-.162.12a.127.127 0 0 1-.12-.139c.007-.079.053-.145.214-.126");
}

.lak5y2bfi {
  fill: var(--svg-color--636409, #636409);
  d: path("m31.15 30.864l.041-.084c.055.024.13.013.151.091c-.038 0-.07.012-.089.049z");
}

.lbxx21rir {
  fill: var(--svg-color--3b3e20, #3b3e20);
  d: path("M31.773 29.952c.114.005.074-.079.084-.14c.012-.079-.078-.161.009-.235l.056.12c.049.097-.007.207.038.304l.005.097c-.096-.004-.154-.063-.192-.146");
}

.ldo0sgk8k {
  fill: var(--svg-color--fdfd02, #fdfd02);
  d: path("m31.816 31.07l.058.121c.079.132.061.276.063.419c-.002.081 0 .163-.018.242c-.023.08-.043.162-.012.246a.26.26 0 0 1-.01.141c-.041.063-.076.131-.053.213a.2.2 0 0 1-.005.066c-.029.084-.066.166-.071.258c-.018.089-.042.176-.018.268c-.003.139-.058.262-.102.387c-.076.111-.096.246-.139.371a9 9 0 0 0-.102.306c-.028.077-.043.159-.069.237c-.048.092-.113.174-.14.275c-.034.088-.074.172-.106.259a.2.2 0 0 1-.041.061c-.052.024-.101.081-.16.013l-.077-.085c-.092-.115-.248-.176-.282-.341a.3.3 0 0 1 .015-.109c.026-.066.074-.12.099-.188c.039-.096.053-.201.089-.298q.06-.14.118-.286a.4.4 0 0 1 .058-.078c.038-.037.063-.076.049-.132a.4.4 0 0 1 .01-.161a3 3 0 0 1 .086-.373c.034-.115.041-.238.094-.351c.038-.079.034-.163.034-.248q0-.076.005-.149a.6.6 0 0 1 .019-.113a.7.7 0 0 0 .024-.229c.002-.122 0-.243.003-.365a.6.6 0 0 1 .019-.121c.061-.139-.003-.3.075-.435c.211-.08.345.064.487.179");
}

.le9xd_5jm {
  fill: var(--svg-color--535406, #535406);
  d: path("M25.912 39.27q-.01-.016.005-.024l.053-.112c.036-.046.082-.046.132-.029q.033.022.02.059c-.054.069-.119.111-.21.106");
}

.learl5bcb {
  fill: var(--svg-color--585800, #585800);
  d: path("M12.43 33.33c.076.09.071.207.103.313c-.154-.067-.151-.181-.103-.313");
}

.leocf4s-i {
  fill: var(--svg-color--f8f10a, #f8f10a);
  d: path("M27.04 22.256a.16.16 0 0 1-.149-.104l.163-.057l.077.012l.021.092c-.045.004-.087.012-.112.057");
}

.lfvl22b7i {
  fill: var(--svg-color--dfe066, #dfe066);
  d: path("M27.878 36.34q.021-.017.041-.036l.051-.009q.097 0 .192-.003c-.082.097-.183.064-.284.048");
}

.lg8r4ablm {
  fill: var(--svg-color--f1ed22, #f1ed22);
  d: path("m26.79 36.15l-.055-.055l.112-.106l.197.061l.125.099l-.175.062c-.088.046-.143-.019-.204-.061");
}

.lghb61a1x {
  fill: var(--svg-color--111403, #111403);
  d: path("m13.1 31.941l.002.113l-.007.25l-.039.001c-.026-.137-.077-.268-.06-.411c.026-.031.06-.031.094-.016a.05.05 0 0 1 .019.039q-.005.024-.009.024");
}

.lgjxcq8bl {
  fill: var(--svg-color--f7f707, #f7f707);
  d: path("M20.996 39.967c-.122-.032-.245-.02-.367-.01l-.251-.025c-.028-.04-.028-.076.013-.105c.082-.007.166-.021.245.012c.125.015.253-.012.368.056z");
}

.lhav9tb2f {
  fill: var(--svg-color--3c240e, #3c240e);
  d: path("m30.02 24.707l-.188-.3c.176.051.28.163.299.351c-.065.046-.088-.007-.111-.051");
}

.lhrlv-b7w {
  fill: var(--svg-color--484a06, #484a06);
  d: path("M28.59 29.18c.11.024.257-.023.296.146q-.12-.03-.241-.056c-.037-.02-.089-.03-.055-.09");
}

.lhue_ob1h {
  fill: var(--svg-color--b00303, #b00303);
  d: path("m17.72 29.609l-.01.28l-.096.003c.048-.089-.127-.261.106-.283");
}

.li-papbzu {
  fill: var(--svg-color--2f3300, #2f3300);
  d: path("M12.533 27.997c-.007.125-.058.237-.106.351c-.063-.146.031-.267.063-.398c.042-.011.067-.005.043.047");
}

.liv_zh8be {
  fill: var(--svg-color--f8e868, #f8e868);
  d: path("m22.592 40.871l.402.007l-.015.033l-.395.005a.1.1 0 0 1 .008-.045");
}

.lk0p_te4q {
  fill: var(--svg-color--301e00, #301e00);
  d: path("m26.694 36.518l-.054-.052q.099-.006.198-.015c.069-.02.139-.049.204.007h-.002a.2.2 0 0 0-.018.045c-.105.058-.217.035-.328.014");
}

.lkew52uxq {
  fill: var(--svg-color--191800, #191800);
  d: path("M15.249 28.976v.038c-.028.047-.082.034-.123.054l-.185.005q-.025-.023-.015-.056c.023-.02.041-.043.043-.075q-.003-.033.029-.047c.083.03.155.095.251.081");
}

.lkfcg4b_g {
  fill: var(--svg-color--21221a, #21221a);
  d: path("M27.553 34.736c-.065-.044-.101.025-.148.042c-.034-.135.04-.212.146-.271c.039.054-.083.115.005.169q.023.021.013.041q-.009.02-.016.019");
}

.lkrn7vrqw {
  fill: var(--svg-color--d5d22c, #d5d22c);
  d: path("m17.919 34.31l-.004.04c.04.074.004.126-.043.179a.2.2 0 0 1-.072.03c-.115-.026-.266-.012-.246-.202c.032-.064.217.051.156-.129h-.002c.067-.094.145-.067.226-.021a.1.1 0 0 1-.015.104");
}

.ll0ss1b1o {
  fill: var(--svg-color--60200d, #60200d);
  d: path("m30.933 32.04l.104.005l-.051.104c-.095-.022-.207.035-.287-.057c.046-.151.138-.109.234-.052");
}

.ll4kc7j2u {
  fill: var(--svg-color--232300, #232300);
  d: path("m30.96 35.688l-.018-.203c.072.028.059.105.094.156q-.038.022-.076.047");
}

.llw3_wb7e {
  fill: var(--svg-color--202000, #202000);
  d: path("m30.567 27.12l-.015-.003l-.015.005c-.069-.05-.094-.122-.098-.202l.025.005z");
}

.lmcbacb2d {
  fill: var(--svg-color--440, #440);
  d: path("M25.417 37.492c.081.036.183-.061.25.043c-.013.031-.042.035-.07.042q-.198.005-.395.014c-.053.007-.074-.014-.055-.066c.088-.033.185.008.27-.033");
}

.lmt54bc4f {
  fill: var(--svg-color--1b2f06, #1b2f06);
  d: path("M19.962 37.849q.013.018.022.038q-.054.059-.118.012c-.342-.028-.698.066-1.025-.104a.14.14 0 0 1 .063-.05a.4.4 0 0 1 .083-.019c.166-.006.332-.012.493.04c.149.024.309-.023.453.051z");
}

.ln27vkurp {
  fill: var(--svg-color--3c3c03, #3c3c03);
  d: path("M25.515 34.2q.07.027.097.099c-.002.044-.008.087-.055.108l-.052-.051c.022-.064-.025-.105-.05-.154z");
}

.ln5lo9cqx {
  fill: var(--svg-color--4c3f2b, #4c3f2b);
  d: path("m18.18 24.568l.041-.002c-.012.107.074.24-.09.301l-.007-.049a.31.31 0 0 1 .056-.25");
}

.lnjopoe4p {
  fill: var(--svg-color--334b13, #334b13);
  d: path("M20.576 20.767q.11.001.221.007a.08.08 0 0 1-.036.065c-.12.015-.242-.017-.358.026l-.289.002c-.021-.078.01-.104.089-.101c.123.005.248.001.373.001");
}

.lnt1ylwma {
  fill: var(--svg-color--7b1e0d, #7b1e0d);
  d: path("M28.893 23.342a.1.1 0 0 1 .001.043c-.022.041-.054.069-.104.061a.34.34 0 0 1-.149-.167q-.067-.101-.134-.206c.232-.059.295.124.386.269");
}

.lnwury9wy {
  fill: var(--svg-color--101109, #101109);
  d: path("M24.476 37.683c-.138-.017-.263.092-.404.05q-.065-.021-.05-.084l.354-.122a.06.06 0 0 1 .021.046c-.017.067.122.023.079.11");
}

.loisktbku {
  fill: var(--svg-color--26300b, #26300b);
  d: path("m12.739 26.505l.052.007q.024.03.004.063a.34.34 0 0 1-.14.097q-.032.017-.064-.002l-.013-.01c-.007-.114.053-.162.161-.155");
}

.lonmyqbpd {
  fill: var(--svg-color--e6e517, #e6e517);
  d: path("M26.632 38.662c.019-.108.107-.131.194-.158c.07-.047.128-.119.229-.104c.051.047.079.101.048.17c-.105.111-.233.19-.372.25c-.046-.045-.128-.066-.099-.158");
}

.lpx_d3nui {
  fill: var(--svg-color--6c6c0c, #6c6c0c);
  d: path("m18.783 22.16l-.148.06l-.13.024c.036-.212.175-.092.278-.084");
}

.lq1v43lui {
  fill: var(--svg-color--2b2402, #2b2402);
  d: path("M22.18 24.562h-.26q-.025.036-.054.002c-.041-.02-.052-.056-.05-.097q.204.003.408.002q-.023.046-.044.093");
}

.lqak0db-z {
  fill: var(--svg-color--fefc00, #fefc00);
  d: path("M17.573 21.905c-.048-.021-.064-.061-.065-.11c.02-.094.115-.066.167-.104l.142-.062h.031c.063.017.133.023.132.112a.2.2 0 0 1-.045.048c-.063.037-.128.072-.176.131a.17.17 0 0 1-.084.051c-.049.002-.087-.014-.102-.066");
}

.lt58xpypt {
  fill: var(--svg-color--8c1e0d, #8c1e0d);
  d: path("m28.693 30.07l.097.011q.076.013.15.021q.028.012.021.041c-.015.024-.042.033-.063.05c-.082-.002-.183.041-.214-.089q-.028-.02-.015-.028z");
}

.lt7v68b3a {
  fill: var(--svg-color--484713, #484713);
  d: path("m30.466 26.926l-.014.002l-.012-.007c-.08-.045-.097-.125-.109-.206q.019-.03.036 0c.042.066.095.127.099.211");
}

.ltu2cgfeg {
  fill: var(--svg-color--fefd05, #fefd05);
  d: path("m18.673 35.33l-.089-.158q.028-.073.053-.146l.02-.022c.031-.012.058-.01.079.019h.002a.13.13 0 0 1 .027.146c-.056.038-.033.123-.092.161");
}

.ltwskuh9x {
  fill: var(--svg-color--1f1f04, #1f1f04);
  d: path("M31.04 35.641c.106.154.084-.08.149-.049c-.019.21-.112.355-.341.38a.1.1 0 0 1-.037-.06c-.005-.092.041-.162.097-.23c.038-.035.077-.061.132-.041");
}

.lu34ltb7x {
  fill: var(--svg-color--1d3803, #1d3803);
  d: path("M13.709 29.377a.66.66 0 0 1 .568-.145c-.031.072-.106.031-.154.061c-.137.032-.263.118-.414.084");
}

.lvsd224zr {
  fill: var(--svg-color--504908, #504908);
  d: path("M27.508 25.26c.127.145-.095.289 0 .434c.035.058.026.097-.046.11c-.241-.291-.289-.306-.607-.194q-.053.02-.11.014q-.113-.02-.227-.033l-.079-.017c-.17-.051-.353.017-.52-.056c-.135-.041-.115-.147-.104-.25a.43.43 0 0 1 .245-.06c.482.021.968-.063 1.448.052");
}

.lvy_18cmg {
  fill: var(--svg-color--f0ee28, #f0ee28);
  d: path("M15.15 24.578q0 .094.003.188l-.104.051l-.003-.2z");
}

.lw317kbii {
  fill: var(--svg-color--f7f906, #f7f906);
  d: path("M17.919 24.877c.152-.008.141.096.131.197c-.043.045-.09.041-.142.014a.16.16 0 0 1-.032-.146a.15.15 0 0 1 .043-.065");
}

.lw4t0bbgb {
  fill: var(--svg-color--fefd01, #fefd01);
  d: path("m22.431 20.567l.099-.001v3.167a.08.08 0 0 1-.092.013c-.04-.041-.033-.094-.033-.145v-2.912c-.001-.043-.001-.085.026-.122");
}

.lwgbbs75i {
  fill: var(--svg-color--212203, #212203);
  d: path("M26.785 30.31c-.105-.059-.2-.056-.288.035a.1.1 0 0 0-.027-.042c-.178-.07-.368.016-.548-.047q-.027-.027-.054-.057c.07-.061.159-.049.243-.049q.547-.003 1.096 0c.086 0 .173-.012.245.048v.003c.005.041.005.079-.043.098q-.017.004-.036.006a3 3 0 0 1-.552.004z");
}

.lws-3sbne {
  fill: var(--svg-color--6f0500, #6f0500);
  d: path("m22.832 24.669l.001-.11c.093.082.079.171.012.262l-.013-.064q-.034-.044 0-.088");
}

.lxjypg22p {
  fill: var(--svg-color--222300, #222300);
  d: path("m28.578 25.328l-.044-.004a.43.43 0 0 1-.258-.01c-.053-.033-.125-.049-.103-.138l.007-.003c.131.056.321-.039.398.155");
}

.lxq7iwrzp {
  fill: var(--svg-color--575900, #575900);
  d: path("M22.536 24.607q-.004-.022-.002-.044l.299-.005c.035.027.033.063.021.101c-.116.054-.233.1-.318-.052");
}

.lxt7y2yli {
  fill: var(--svg-color--122902, #122902);
  d: path("M18.842 40.51c-.1-.061-.236-.048-.313-.154q.015-.013.026-.025a.2.2 0 0 1 .105-.011a.9.9 0 0 1 .265.102a.1.1 0 0 1 .031.063q-.042.082-.114.025");
}

.lyh4i3h_w {
  fill: var(--svg-color--8e9000, #8e9000);
  d: path("M27.558 36.25c-.005.075.044.101.106.113q-.05.027-.104.053q-.03.019-.059.007q-.048-.022-.055-.072l.064-.143z");
}

.lyxai9b0l {
  fill: var(--svg-color--f1f01e, #f1f01e);
  d: path("m30.438 25.828l.089.018a.1.1 0 0 1 .015.034q-.006.058-.008.112c-.041.003-.081.006-.105-.036z");
}

.lzmcmcb6c {
  fill: var(--svg-color--3f3f00, #3f3f00);
  d: path("M25.869 34.19c-.032.067-.102.082-.162.108c-.062-.059-.104-.125-.079-.213c.02-.04.043-.069.092-.045q.075.077.149.15");
}

.lzxxctb3i {
  fill: var(--svg-color--7c1c0f, #7c1c0f);
  d: path("M29.21 25.687c-.122.013-.235-.005-.326-.096a.09.09 0 0 1 .048-.069q.035-.01.038.026c.062.076.218-.011.24.139");
}

.m_4o91b6w {
  fill: var(--svg-color--293506, #293506);
  d: path("m16.678 38.05l-.096.046l-.099-.006c.01-.108-.133-.107-.145-.199c.141-.005.232.091.34.159");
}

.m_ftqvn5e {
  fill: var(--svg-color--e7e460, #e7e460);
  d: path("m20.415 21.07l-.131.005c-.031-.028-.082-.011-.105-.054c.069-.082.163-.038.246-.043c.033.035.04.066-.01.092");
}

.m_p637m0y {
  fill: var(--svg-color--565608, #565608);
  d: path("m16.16 23.676l-.069.015c.033-.101.064-.2.207-.156z");
}

.m_vag5bom {
  fill: var(--svg-color--e7eb2c, #e7eb2c);
  d: path("m25.03 35.13l.116-.124l.154.111q.03.042-.01.075c-.088-.013-.201.074-.26-.062");
}

.m--rs7b1p {
  fill: var(--svg-color--2a1103, #2a1103);
  d: path("M26.836 24.568q.029-.05.056-.104l.05-.012c-.01.079.059.104.099.148c-.13-.004-.098.09-.098.164v.049q-.027.03-.063.012a.25.25 0 0 1-.075-.123a.14.14 0 0 1 .031-.134");
}

.m-3147awi {
  fill: var(--svg-color--f4f407, #f4f407);
  d: path("m29.607 34.01l.01-.129c.02-.022.036-.053.072-.056a.2.2 0 0 1 .063.02c.07.052.128.12.211.153c.121.067.19.188.285.284c.063.063.093.145.129.224c.054.017.049.067.063.108l-.178.007c-.069-.051-.164-.072-.194-.168c-.099-.048-.159-.145-.253-.197l-.108-.104c-.04-.043-.123-.057-.1-.142");
}

.m0cg1ltac {
  fill: var(--svg-color--343102, #343102);
  d: path("m31.26 26.61l-.055.003a.5.5 0 0 1-.102-.26c.061.004.123 0 .156.066z");
}

.m0wahvbbs {
  fill: var(--svg-color--fbfb02, #fbfb02);
  d: path("M19.306 21.277c-.097.061-.207.055-.315.055q-.023.024-.053.01c-.036-.029-.018-.079-.043-.111v-.052l.355-.059c.039.021.06.058.072.099a.07.07 0 0 1-.016.058");
}

.m19fv0mlu {
  fill: var(--svg-color--191900, #191900);
  d: path("m18.992 34.5l-.021.005h-.021q-.033-.008-.031-.041a.1.1 0 0 1 .017-.055l.046.017l.013.008l.021.034l-.024.033");
}

.m1st8bbll {
  fill: var(--svg-color--161800, #161800);
  d: path("M26.28 39.742c.072-.07.15-.121.257-.084l-.003.007l-.202.108q-.036.003-.052-.031");
}

.m1v7qqbuk {
  fill: var(--svg-color--62610f, #62610f);
  d: path("M17.938 22.507c-.071.071-.14.144-.243.052c.078-.024.138-.146.243-.052");
}

.m2dlb1bmx {
  fill: var(--svg-color--050203, #050203);
  d: path("M26.01 36.492c.013.048.048.069.094.074q.034.013.024.051c-.038.043-.094.057-.146.074a.2.2 0 0 1-.065.008a.2.2 0 0 1-.063-.025q-.02-.035.01-.059z");
}

.m3af7lbjg {
  fill: var(--svg-color--232200, #232200);
  d: path("m14.687 30.04l-.063-.045c.104-.037.2-.136.323-.047q-.131.045-.26.092");
}

.m3b1kba6t {
  fill: var(--svg-color--241f00, #241f00);
  d: path("m28.84 32.508l.099.045l-.257.013l-.085-.007c.07-.068.161-.037.243-.051");
}

.m3sffcl7i {
  fill: var(--svg-color--fdfc01, #fdfc01);
  d: path("m15.453 24.504l.008.071q.057.074-.01.142c-.104-.004-.209-.012-.301.049c-.061-.061-.051-.123-.003-.188l.104-.026c.08.031.141-.01.202-.048");
}

.m4fe-zbql {
  fill: var(--svg-color--2e2e12, #2e2e12);
  d: path("M29.903 37.18c.026-.092.118-.15.118-.254c.079-.006.079.037.055.095c-.021.053-.064.101-.05.163c-.043.049-.082.006-.123-.004");
}

.m578zbbgt {
  fill: var(--svg-color--eff06c, #eff06c);
  d: path("m16.485 30.01l1.68-.013q.02.01.017.024t-.01.015l-1.688.004a.1.1 0 0 1 .001-.03");
}

.m5fy-omtt {
  fill: var(--svg-color--494809, #494809);
  d: path("M14.682 24.21c-.089.115-.174.231-.309.3c.064-.141.128-.281.309-.3");
}

.m5na1acjw {
  fill: var(--svg-color--1c2512, #1c2512);
  d: path("M11.953 29.688q0 .029.003.056a.5.5 0 0 0 .035.354c-.024.123-.077.215-.222.212l-.007-.005a.85.85 0 0 0 .104-.481c-.005-.066.012-.121.087-.136");
}

.m65__c_zs {
  fill: var(--svg-color--421d05, #421d05);
  d: path("M17.703 34.615c.063-.005.106-.027.106-.099a.06.06 0 0 1 .05-.007c.07.031.105.091.13.16a.18.18 0 0 1-.065.157c-.124.015-.115-.135-.204-.163l-.015-.004a.1.1 0 0 1-.002-.044");
}

.m6j-hebbc {
  fill: var(--svg-color--461404, #461404);
  d: path("m25.915 34.865l.27-.303l.088.16c-.035.031-.057.078-.105.093c-.06.043-.151.058-.145.16q-.018.008-.034.018c-.092-.007-.12-.046-.074-.128");
}

.m7-akhp5u {
  fill: var(--svg-color--191900, #191900);
  d: path("M18.993 34.456v-.023l.052.023l.003.011q-.033.018-.055-.011");
}

.m76duqboy {
  fill: var(--svg-color--6e1009, #6e1009);
  d: path("M24.17 21.958c.046.05.108.034.164.043c.03.024.073.043.053.095c-.126.006-.253.012-.315-.133z");
}

.m7nqx7ipr {
  fill: var(--svg-color--48490b, #48490b);
  d: path("M18.12 21.643c.053.007.104-.053.158-.005c-.023.075-.104.061-.151.099q-.002-.048-.007-.094");
}

.m9xdjdbcf {
  fill: var(--svg-color--4e3307, #4e3307);
  d: path("M28.327 32.754c.063.021.157-.011.156.104q.024.016.016.034t-.016.017c-.061-.043-.153-.053-.156-.155");
}

.ma_ioz80o {
  fill: var(--svg-color--242400, #242400);
  d: path("M12.778 31.438c.026.172-.021.351.063.515c.033.058.036.101-.05.099a1.6 1.6 0 0 1-.061-.561c-.022-.054.004-.063.048-.053");
}

.macvaw2-f {
  fill: var(--svg-color--3d340b, #3d340b);
  d: path("m18.13 24.867l.006.354c-.13.119-.277.078-.424.053a.13.13 0 0 1-.061-.056a.06.06 0 0 1 .027-.067c.093-.056.204-.018.298-.06a.1.1 0 0 0 .023-.056c0-.067-.043-.09-.101-.099a.6.6 0 0 0-.158 0c-.056.003-.095.046-.146.063a.12.12 0 0 1-.099-.022a.16.16 0 0 1-.023-.104c.017-.081.02-.165.034-.245c.021-.103-.036-.009-.049-.021c-.105.023-.211.033-.306-.034c-.033-.063.003-.104.048-.142c.102-.053.212-.043.321-.034q.038.007.073.022c.061.052.118.107.182.155c.016.049-.022.097 0 .145c.103.074.24-.002.339.084q.025.027.016.064");
}

.map-ptb9v {
  fill: var(--svg-color--49480e, #49480e);
  d: path("M18.632 33.92c.149.048.128.205.199.306c.01.026-.002.041-.028.046c-.105-.003-.19-.034-.217-.151a.3.3 0 0 1 .005-.143a.13.13 0 0 1 .041-.058");
}

.mb52o4b5p {
  fill: var(--svg-color--6b2a09, #6b2a09);
  d: path("m26.02 40.11l.01.061c-.026.104-.107.077-.18.075c.002-.114.109-.097.17-.136");
}

.mb60ebb-w {
  fill: var(--svg-color--262500, #262500);
  d: path("M28.638 32.35a.06.06 0 0 1-.003-.039c.021-.044.077-.021.104-.053l.25-.01q.073-.017.058.058c-.128.095-.275.012-.409.044");
}

.mbkg-7yeo {
  fill: var(--svg-color--6e6e0d, #6e6e0d);
  d: path("M27.18 23.12h-.137l.002-.146c.058.038.151.043.135.146");
}

.mbm0g9-ti {
  fill: var(--svg-color--190b02, #190b02);
  d: path("m26.434 24.51l.049.052a.3.3 0 0 1 .061.118c.002.119.038.245-.07.339l-.017.002l-.018-.002c-.057-.042-.055-.101-.036-.159c.017-.102-.021-.205.022-.306z");
}

.mcq6br_ck {
  fill: var(--svg-color--64360a, #64360a);
  d: path("m31.647 34.2l-.127.315q-.039.032-.075 0c-.065-.135-.026-.245.085-.335c.041-.014.083-.011.117.02");
}

.md3zn8x5x {
  fill: var(--svg-color--dddf9d, #dddf9d);
  d: path("m24.981 34.564l-.042-.045l.067-.022h-.002q.024.045-.023.067");
}

.mdndqhbje {
  fill: var(--svg-color--97968f, #97968f);
  d: path("m28.14 25.18l-.014-.447c-.001-.061-.003-.123.088-.113q.011-.03.042-.027l.021.021c-.188.16-.065.373-.092.561l-.02.018z");
}

.mdwf4ac2q {
  fill: var(--svg-color--242103, #242103);
  d: path("m18.214 30.662l.011.154q.024.045-.016.076a1.1 1.1 0 0 1-.477.01a.14.14 0 0 1-.059-.062a.25.25 0 0 1-.005-.167c.015-.04.039-.068.083-.072c.204.203.214.203.354-.035c.109-.048.079.058.109.096");
}

.mebl5j3zb {
  fill: var(--svg-color--484808, #484808);
  d: path("M28.748 37.22c.047-.148.121-.27.294-.295c-.082.113-.171.22-.294.295");
}

.menkr6bzh {
  fill: var(--svg-color--ecf4f9, #ecf4f9);
  d: path("M20.05 30.783c-.03.063-.031.153-.137.15c-.091-.004-.148-.053-.146-.139c0-.085.056-.138.148-.137c.083.001.118.056.135.126");
}

.mf97ien2z {
  fill: var(--svg-color--464100, #464100);
  d: path("M28.934 33.24c.104.015.22.005.258.142q-.005.032-.039.037a.35.35 0 0 1-.219-.179");
}

.mg_44ug6y {
  fill: var(--svg-color--161800, #161800);
  d: path("M13.14 35.18q-.02 0-.039-.002c-.05-.041-.117-.076-.056-.156z");
}

.mg1x_tb8y {
  fill: var(--svg-color--fefd02, #fefd02);
  d: path("m27.04 25.06l.01-.186l.296-.003c.056.054.024.123.027.186c-.018.036-.049.049-.088.048c-.055-.034-.11-.046-.166-.003c-.036.002-.066-.004-.079-.042");
}

.mggtumshu {
  fill: var(--svg-color--565800, #565800);
  d: path("M28.14 23.02c-.03.121-.073.005-.108.002c-.102-.016-.067-.088-.052-.148c.061.038.124.077.16.146");
}

.mgk0ry_mn {
  fill: var(--svg-color--5b5900, #5b5900);
  d: path("m24.892 21.998l-.002-.045c.082.008.161.021.214.096c-.074.074-.137-.023-.207-.014q-.022-.01-.019-.022q.007-.016.014-.015");
}

.mgkmfzv7o {
  fill: var(--svg-color--dcdbbe, #dcdbbe);
  d: path("m31.19 32.416l.049-.108c.002.085.048.174-.032.248l-.015-.104a.06.06 0 0 0-.002-.036");
}

.mgvfkf_wb {
  fill: var(--svg-color--575706, #575706);
  d: path("m31.05 32.917l.051.003c-.027.141-.036.287-.106.415c-.071-.151.002-.283.055-.418");
}

.mhpmg8lvz {
  fill: var(--svg-color--434300, #434300);
  d: path("m15.03 25.476l.003.053c-.099-.038-.217-.022-.306-.095c.023-.052.069-.041.111-.045c.058.041.159-.008.192.087");
}

.mi8h6g5go {
  fill: var(--svg-color--ebec6a, #ebec6a);
  d: path("m23.15 20.921l-.306-.026l.306-.024z");
}

.mjjd7vjxg {
  fill: var(--svg-color--603107, #603107);
  d: path("M25.356 22.377c.077.007.158.007.209.081c-.117.095-.148-.031-.209-.081");
}

.mk7c0jbrp {
  fill: var(--svg-color--494401, #494401);
  d: path("M25.813 25.24c-.034-.098.099-.055.102-.121l.062-.034a.3.3 0 0 1 .067-.013a1.3 1.3 0 0 1 .203.002l.063.004c.045-.003.074-.029.104-.056a.1.1 0 0 1 .062-.013c.039.013.072.043.113.051c.079.015.154.002.231-.008q.037-.004.074.005a.23.23 0 0 1 .092.07c.024.036.035.074.01.115a.2.2 0 0 1-.085.013c-.366-.009-.732.022-1.098-.015");
}

.mkl7bwbkk {
  fill: var(--svg-color--343300, #343300);
  d: path("M31.604 33.445c-.021.119-.038.243-.11.347h-.029c.034-.12.002-.269.139-.347");
}

.mks4ih3yl {
  fill: var(--svg-color--2e191a, #2e191a);
  d: path("M27.767 32.876c.02-.104-.063-.224.054-.311c-.008.106.021.217-.054.311");
}

.ml1f46bfx {
  fill: var(--svg-color--f1f15b, #f1f15b);
  d: path("M18.16 25.394q-.022.02-.044.043h-1.59l.005-.053c.529-.05 1.059-.036 1.588-.007q.019.015.041.017");
}

.mleuy-ulc {
  fill: var(--svg-color--dbdb54, #dbdb54);
  d: path("m29.8 26.705l.017-.088a.1.1 0 0 1 .049 0c.045.076.151-.009.196.073a.1.1 0 0 0-.009.03z");
}

.mluf5cijp {
  fill: var(--svg-color--e7eb22, #e7eb22);
  d: path("M19.352 21.08v.144q-.018.036-.044.007c-.048-.023-.056-.064-.058-.11c.024-.037.061-.046.102-.041");
}

.mm3r48h3w {
  fill: var(--svg-color--e8f1f9, #e8f1f9);
  d: path("M19.49 31.08c.092.005.147.056.156.14c.006.078-.048.134-.119.146c-.09.017-.15-.041-.166-.123c-.014-.09.05-.137.129-.163");
}

.mm4lv_bqr {
  fill: var(--svg-color--4f5000, #4f5000);
  d: path("M14.378 34.921v.043l-.257.104q-.026-.015-.018-.028q.01-.013.02-.013l.008-.036c.079-.032.153-.09.247-.07");
}

.mmtom2bth {
  fill: var(--svg-color--252900, #252900);
  d: path("M26.23 37.39c.048.021.117-.036.148.042c-.009.034-.038.035-.064.041l-.246.013c-.057.017-.062-.017-.057-.06c.07-.037.151.004.219-.036");
}

.mn7b9xgso {
  fill: var(--svg-color--e4e304, #e4e304);
  d: path("m22.18 24.562l.046.462q-.008.045-.013.094a.1.1 0 0 1-.069.029c-.092-.013-.19-.003-.258-.087c-.04-.067-.031-.138-.019-.21c.041-.098-.003-.211.051-.306c.091-.043.18-.051.262.018");
}

.mnmw62orq {
  fill: var(--svg-color--1c1900, #1c1900);
  d: path("m25.975 35.483l-.048-.05q-.035-.01-.024-.047a.1.1 0 0 1 .053-.035a.14.14 0 0 1 .063.01a.1.1 0 0 1 .031.057a.1.1 0 0 1-.028.054a.1.1 0 0 0-.047.011");
}

.moabe_b3d {
  fill: var(--svg-color--646400, #646400);
  d: path("m18.566 39.39l.172.109v.025c-.104 0-.244.064-.238-.135z");
}

.mobzxlbwf {
  fill: var(--svg-color--ac0f0c, #ac0f0c);
  d: path("m29.15 32.459l.154.01c-.034.121-.13.09-.214.084z");
}

.moqusfohm {
  fill: var(--svg-color--e2e204, #e2e204);
  d: path("M21.349 21.483c.112-.159.03-.341.055-.509q.025-.03.049.002l.002.428c0 .061-.003.121-.092.111q-.032 0-.028-.015q.005-.016.014-.017");
}

.movnhm8io {
  fill: var(--svg-color--eaeb06, #eaeb06);
  d: path("m21.654 24.876l-.001.195c-.115-.013-.23.127-.346.003l-.005-.201z");
}

.mpf7-fb_x {
  fill: var(--svg-color--d2d15b, #d2d15b);
  d: path("m15.969 37.839l.051-.055q.028-.015.048.011l-.003.107a.1.1 0 0 1-.035-.006a.2.2 0 0 1-.061-.057");
}

.mpxekrbuz {
  fill: var(--svg-color--f4f408, #f4f408);
  d: path("M27.83 37.791c.146-.063.228-.197.343-.293c.029-.046.042-.1.078-.143c.043-.048.089-.092.122-.148l.038-.054a.6.6 0 0 1 .102-.085q.16-.119.277-.281c.071-.103.163-.188.232-.291a.17.17 0 0 1 .089-.055c.082.01.118.064.128.14c.005.056-.048.096-.039.151l-.158.195a.9.9 0 0 0-.294.295c-.122.113-.185.295-.382.32a1 1 0 0 1-.296.301a.17.17 0 0 1-.095.102c-.064.033-.115.101-.201.079a.13.13 0 0 1-.079-.075c-.007-.099.073-.12.135-.158");
}

.mq34wz7nt {
  fill: var(--svg-color--696a00, #696a00);
  d: path("M23.352 40.719c-.057-.014-.129.023-.161-.056l.07-.05c.053.012.123-.029.149.053z");
}

.mq4qllbov {
  fill: var(--svg-color--873000, #873000);
  d: path("M25.45 37.753a.2.2 0 0 1 .002.045l-.149.048l-.052-.053l.109-.051c.033-.03.064-.037.09.011");
}

.mqu813ble {
  fill: var(--svg-color--ad1f0f, #ad1f0f);
  d: path("M27.553 30.621a.1.1 0 0 0-.045-.01a.3.3 0 0 1-.109-.086a.23.23 0 0 1-.031-.207a.3.3 0 0 1 .08-.123c.036-.02.071-.025.105.002z");
}

.mquoj-apb {
  fill: var(--svg-color--faf902, #faf902);
  d: path("m25.508 40.16l.2-.069l.007.125c-.034.05-.092.036-.142.05c-.092.007-.096-.037-.065-.106");
}

.mr2x2wbos {
  fill: var(--svg-color--dbdf5a, #dbdf5a);
  d: path("M17.513 30.511q-.03.01-.06.017l-.002-.02q-.02-.023-.042-.045l-.007-.002c.023-.047.065-.053.111-.051c.021.035.024.068 0 .101");
}

.mr6artbwa {
  fill: var(--svg-color--462f06, #462f06);
  d: path("M26.02 34.976q-.032.048-.063.099q-.047.047-.096 0l-.051-.146l.1-.063q.007.102.11.11");
}

.mrqzt38ql {
  fill: var(--svg-color--f9f804, #f9f804);
  d: path("M31.898 28.507a.1.1 0 0 1 .019.044q.013.184.087.354c.017.151.04.305.043.457c.017.064.058.119.069.185c.01.081.005.161.006.24q0 .102-.003.204c-.003.057-.02.106-.079.131a.1.1 0 0 1-.077-.01a.2.2 0 0 1-.051-.104c-.017-.098.003-.195-.033-.289l-.053-.134a.7.7 0 0 1-.044-.207c.015-.13-.041-.253-.034-.381a.5.5 0 0 0-.03-.135c-.022-.079-.049-.158-.068-.237a7 7 0 0 0-.089-.347q-.01-.034-.017-.069c-.026-.113-.046-.229-.094-.336c-.033-.078-.074-.152-.097-.23c-.023-.115-.063-.227-.101-.339a1.3 1.3 0 0 0-.107-.253c-.037-.082-.078-.163-.108-.25c-.024-.076-.061-.145-.095-.215c-.033-.076-.086-.146-.058-.235q.05-.094.154-.072a.2.2 0 0 1 .087.067c.063.08.074.179.105.27c.133.164.178.365.227.563l-.001-.005c.058.107.133.207.152.332a.5.5 0 0 0 .089.235c.014.108.046.212.086.312c.026.155.067.306.115.454");
}

.mru_t7wnh {
  fill: var(--svg-color--eceb6c, #eceb6c);
  d: path("m20.685 21.66l.155-.031l.147.014c-.096.077-.2.052-.302.017");
}

.mrzrfzgzm {
  fill: var(--svg-color--8c2b13, #8c2b13);
  d: path("M18.09 35.585q.078.128.154.257c-.147-.005-.188-.185-.328-.204c-.026-.06.012-.085.054-.11q.08-.013.12.057");
}

.msxo78bet {
  fill: var(--svg-color--232200, #232200);
  d: path("m28.375 29.13l-.053.05h-.145l-.053-.005v-.105q.015.005.031.004c.065.051.16-.013.22.056");
}

.mt9rxlbck {
  fill: var(--svg-color--b9b715, #b9b715);
  d: path("m19.445 35.29l-.017-.006q-.061 0-.026-.051l.052-.156c.082-.009.104.068.152.106c-.026.078-.093.094-.161.107");
}

.mtgw3tbnn {
  fill: var(--svg-color--c00101, #c00101);
  d: path("M16.226 24.16v3.171l-.002.822q-.02.032-.043 0l-.017-1.488l.019-2.507a.2.2 0 0 1 .043.002");
}

.mtzrhqbop {
  fill: var(--svg-color--151300, #151300);
  d: path("m17.913 25.07l-.08-.008c.012-.055-.017-.132.079-.137z");
}

.mu4ez21vl {
  fill: var(--svg-color--002500, #002500);
  d: path("m18.223 40.26l.065-.01c.113-.038.209-.033.248.106l-.008.002c-.117.012-.223-.006-.305-.098");
}

.mubyie-rf {
  fill: var(--svg-color--211e03, #211e03);
  d: path("m26.27 30.862l-.496.015a.5.5 0 0 1 .077-.263c.039.064-.065.179.099.21c.199.037.265-.075.328-.215c.055.055.053.12.037.188a.2.2 0 0 1-.045.065");
}

.mukslstlk {
  fill: var(--svg-color--2a2900, #2a2900);
  d: path("M20.84 21.585q-.002.022 0 .044c-.043.055-.103.027-.155.031c-.085-.015-.177.078-.256-.016c.007-.04.041-.041.07-.05z");
}

.mus6t7bhb {
  fill: var(--svg-color--161600, #161600);
  d: path("m17.966 35.475l.005-.034l-.005-.009q.03-.026.055.002l-.004-.003q-.002.05-.051.044");
}

.muy_x4xkb {
  fill: var(--svg-color--4f5000, #4f5000);
  d: path("m29.607 34.01l.099.143c-.138-.01-.226-.08-.253-.219q.076.036.154.076");
}

.mv96spqqv {
  fill: var(--svg-color--747800, #747800);
  d: path("m18.276 35.12l.007-.051l.035-.01q.009.014.021.027a.1.1 0 0 0-.011.045z");
}

.mvkabvb0v {
  fill: var(--svg-color--132c02, #132c02);
  d: path("M20.583 37.95c.063-.005.104-.031.106-.099c.038-.003.074-.003.101.031l.051.112h-.258q-.026-.016-.017-.03c.009-.014.012-.014.017-.014");
}

.mvp8fm3bd {
  fill: var(--svg-color--2b2900, #2b2900);
  d: path("M19.05 39.637a.1.1 0 0 0 .003-.037c.053.063.161.003.204.09c-.086.047-.146-.008-.207-.053");
}

.mvq83dbxm {
  fill: var(--svg-color--292800, #292800);
  d: path("m28.13 26.97l.051-.003c.102.055.207-.118.309.005c-.104.089-.251.022-.358.104z");
}

.mwbgcwb9k {
  fill: var(--svg-color--161600, #161600);
  d: path("M19.304 37.594c.079-.051.23.082.257-.101c.106-.022.171.064.255.101c.048.029.094.061.034.121c-.089.05-.181.04-.275.023c-.084-.033-.182-.026-.26-.077q-.037-.028-.011-.067");
}

.mx7e_h_ry {
  fill: var(--svg-color--888900, #888900);
  d: path("m16.991 29.637l.004.253l-.058.001c-.071-.082-.057-.167-.019-.256q.017-.01.031.003a.1.1 0 0 1 .042-.001");
}

.mxejnf01m {
  fill: var(--svg-color--e0e013, #e0e013);
  d: path("m17.759 24.607l.099.009c.098-.003.196-.015.279.053c.01.044.017.085-.027.116c-.148-.027-.322.096-.44-.085z");
}

.mxjq4o1mh {
  fill: var(--svg-color--c9c90c, #c9c90c);
  d: path("m18.599 34.12l-.068.094l-.007-.002c-.084-.108-.007-.204.022-.305l.088.064z");
}

.mxjsy0jay {
  fill: var(--svg-color--f7f524, #f7f524);
  d: path("m25.455 40.31l-.101-.104l.053-.053l.101.01c.002.048.019.086.065.105a.2.2 0 0 1-.015.042z");
}

.mxq_d9bhu {
  fill: var(--svg-color--2d2c00, #2d2c00);
  d: path("M19.866 39.941v-.099c.092-.074.175-.036.252.029q.028.033.003.072z");
}

.mxql2jvbp {
  fill: var(--svg-color--263f08, #263f08);
  d: path("M17.4 22.963q.105-.043.211-.084c.01.149-.094.147-.197.147q-.051-.023-.014-.063");
}

.mxw19vbzc {
  fill: var(--svg-color--e4e04a, #e4e04a);
  d: path("m29.04 27.06l-.238.021c.063-.106.166-.048.253-.056z");
}

.my07aitic {
  fill: var(--svg-color--5e5e01, #5e5e01);
  d: path("M17.265 22.869q-.054.049-.109.102c-.025.043-.065.048-.109.036q-.029-.015-.023-.034t.015-.02c.077-.016.089-.219.226-.084");
}

.mylawqbrs {
  fill: var(--svg-color--831e0b, #831e0b);
  d: path("M23.704 20.776c.144-.005.302-.051.37.14l-.018.029c-.048.036-.099.053-.158.029c-.084-.057-.192-.032-.279-.082a.07.07 0 0 1-.026-.059c.018-.054.077-.032.111-.057");
}

.n-2-c_bwz {
  fill: var(--svg-color--504a00, #504a00);
  d: path("m31.347 34.755l.012.075c-.012.081.029.187-.103.204a.12.12 0 0 1-.044-.065c-.002-.101.015-.19.135-.214");
}

.n-zz3wa2s {
  fill: var(--svg-color--fbf822, #fbf822);
  d: path("m18.738 34.557l.053.004l-.001.055l-.055-.003h.003q-.023-.014-.02-.032q.006-.019.014-.019z");
}

.n091g2bfd {
  fill: var(--svg-color--f7f706, #f7f706);
  d: path("m17.16 36.719l-.056-.003c-.082-.008-.142-.063-.211-.101l-.105-.001c-.077-.007-.162.015-.222-.063q-.027-.062.019-.113c.075-.048.161-.023.241-.03c.094.004.189-.011.281.023a.3.3 0 0 1 .108.048c.086.053.181.022.271.031c.095.008.197-.024.277.053l.071.001c.121.072.292 0 .391.139l.062.033q.004.048-.04.065c-.056.018-.113.015-.169.017c-.081 0-.161.003-.243-.007c-.063-.01-.117-.048-.183-.053c-.058-.022-.118-.017-.18-.02c-.1-.037-.206-.017-.312-.019");
}

.n0ozep0ee {
  fill: var(--svg-color--8a1d20, #8a1d20);
  d: path("M24.08 37.38c.066-.086.154-.107.257-.094c-.058.106-.149.123-.257.094");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n1wzrtbzw {
  fill: var(--svg-color--d4d20b, #d4d20b);
  d: path("m18.918 35.794l.01.008c.013.072-.026.112-.086.139c-.049-.004-.1-.004-.119-.066c.032-.104.093-.143.195-.081");
}

.n2ayz6bau {
  fill: var(--svg-color--002300, #002300);
  d: path("M21.499 21.792v1.948q-.023.024-.045 0l-.007-1.943z");
}

.n3-jch-ij {
  fill: var(--svg-color--edec67, #edec67);
  d: path("M25.763 37.488c.067.103.166.016.246.041c-.126.11-.274.038-.412.048l.07-.042z");
}

.n32kdfb5q {
  fill: var(--svg-color--f4f70a, #f4f70a);
  d: path("m25.864 35.13l.056.097l-.015.021a.1.1 0 0 1-.049.012a.07.07 0 0 1-.041-.029a.1.1 0 0 0-.007-.051q-.01-.015-.018-.031l.024-.025q.026.005.05.006");
}

.n5_dy5ttw {
  fill: var(--svg-color--f4ee11, #f4ee11);
  d: path("m25.727 21.424l.026.008c.077.033.174-.01.24.066c.234.087.456.205.68.322c.072.013.125.065.187.102c.09.035.188.061.195.184c-.041.055-.099.078-.163.093c-.106.017-.192-.033-.271-.097a.5.5 0 0 0-.221-.101c-.219-.104-.438-.204-.649-.322c-.065-.04-.137-.075-.168-.153a.11.11 0 0 1 .028-.108c.039-.021.077-.016.116.006");
}

.n58o3db7a {
  fill: var(--svg-color--e2e349, #e2e349);
  d: path("M28.897 31.589q-.005-.027-.007-.054l-.002.001c.069-.061.146-.058.228-.036c.089.069.02.107-.028.148a.2.2 0 0 1-.072.015c-.044-.017-.092-.028-.119-.074");
}

.n5mok3bco {
  fill: var(--svg-color--e5e60f, #e5e60f);
  d: path("M15.875 25.634q0 .03-.003.056c-.058.049-.133.01-.194.038c-.073.02-.125-.03-.183-.062c-.1-.02-.207-.02-.296-.078l-.008-.051c.02-.069.082-.101.132-.144a.12.12 0 0 1 .095-.021c.129.048.252.105.377.156c.043.024.085.046.08.106");
}

.n6r_3mbte {
  fill: var(--svg-color--f5f504, #f5f504);
  d: path("M12.331 32.816a.5.5 0 0 1-.048-.256c.149.061.111.157.048.256");
}

.n6v9ujule {
  fill: var(--svg-color--52530a, #52530a);
  d: path("M31.04 26.27q-.095-.027-.188-.051a.11.11 0 0 1-.074-.069c.05-.152.154-.034.233-.049l.061.052z");
}

.n7b6iib7s {
  fill: var(--svg-color--5f5f05, #5f5f05);
  d: path("M14.378 34.921c.085-.113.197-.058.303-.05c-.089.069-.201.069-.303.093q-.027-.015-.019-.03q.01-.013.019-.013");
}

.n83lpq-wc {
  fill: var(--svg-color--6b2905, #6b2905);
  d: path("m18.319 34.05l.108.084c-.029.113-.068.2-.195.082q-.032-.007-.064-.017z");
}

.n85qf5bfk {
  fill: var(--svg-color--533d08, #533d08);
  d: path("M25.811 35.864c-.055-.125.126-.157.104-.271c-.039-.053-.027-.096.023-.132q.036-.017.077-.012a.14.14 0 0 1 .067.038q.028.036-.003.07c-.008.175-.165.218-.268.307");
}

.n8pb3te_s {
  fill: var(--svg-color--3b3c22, #3b3c22);
  d: path("m23.453 37.89l.002-.074c.1-.024.197-.101.304-.018l-.049.044l-.119.061c-.042-.043-.089-.038-.138-.013");
}

.n92ioac_s {
  fill: var(--svg-color--f6f601, #f6f601);
  d: path("m26.02 25.07l-.004-.193c.097-.037.092.079.151.101q.002.022.007.041q-.076.027-.154.051");
}

.n967jbbfx {
  fill: var(--svg-color--454200, #454200);
  d: path("m26.02 37.445l.048.04l-.063.044c-.088.021-.185.101-.245-.041q.077-.026.156-.056c.039-.028.075-.032.104.013");
}

.na0mso9_q {
  fill: var(--svg-color--666508, #666508);
  d: path("M26.19 36.819a.2.2 0 0 0-.015.045c-.07-.017-.159.052-.214-.043l.063-.046c.077-.057.134-.059.166.044");
}

.nbd-feb9i {
  fill: var(--svg-color--404140, #404140);
  d: path("M22.64 21.801v1.942q.023.019.013.033c-.01.014-.012.015-.018.015l-.005.003c-.071-.07-.045-.159-.045-.241q-.004-.759 0-1.521c.002-.077-.039-.173.055-.231");
}

.nbqle0b6f {
  fill: var(--svg-color--594a3c, #594a3c);
  d: path("M32.33 31.526v-.298q.118.15 0 .298");
}

.ncdfyrnvz {
  fill: var(--svg-color--532b0a, #532b0a);
  d: path("M26.377 34.461q.05-.076.103-.15c.087.09.095.162-.043.203z");
}

.ncnp_0bys {
  fill: var(--svg-color--eaea5a, #eaea5a);
  d: path("M28.573 32.396c-.087.116-.203.047-.311.051c.061-.063.145-.023.212-.05q.051-.036.099-.001");
}

.nd2_lcbla {
  fill: var(--svg-color--e3e469, #e3e469);
  d: path("M28.37 26.395c.073-.063.162-.031.244-.043c-.063.117-.162.031-.244.043");
}

.neiqhwvup {
  fill: var(--svg-color--ecec60, #ecec60);
  d: path("M20.737 20.975c.04.053.099.041.153.052c-.081.08-.181.041-.274.041a.05.05 0 0 0 0-.038z");
}

.nevhe-e7g {
  fill: var(--svg-color--6b6b0c, #6b6b0c);
  d: path("M25.546 22.249c-.098-.029-.204-.026-.288-.097c.13-.067.233-.056.288.097");
}

.nfbnxmb8f {
  fill: var(--svg-color--333400, #333400);
  d: path("M31.674 28.612c-.045-.113-.148-.217-.064-.355c.05.114.086.23.092.355z");
}

.nfptjcd8k {
  fill: var(--svg-color--545506, #545506);
  d: path("m16.531 23.354l-.005-.039c.049-.053.08-.145.183-.089c-.046.06-.096.118-.178.128");
}

.ng--nnbdb {
  fill: var(--svg-color--f4ed04, #f4ed04);
  d: path("m25.2 40.4l-.003-.135c.022-.05.065-.06.113-.062l.042-.001c.094-.023.091.049.101.104c-.072.064-.163.079-.253.094");
}

.ng9-kdbak {
  fill: var(--svg-color--504f00, #504f00);
  d: path("m15.765 29.746l-.003.047c-.053.065-.13.039-.197.049c.024-.12.118-.094.2-.096");
}

.ngeqc4bzo {
  fill: var(--svg-color--eeed08, #eeed08);
  d: path("M21.87 25.944a.1.1 0 0 1-.007-.044c.002-.021.002-.038.002-.059a.34.34 0 0 1 .146-.148l.104-.007q.184.082.124.274c-.128.081-.252.11-.369-.016");
}

.nglskcakn {
  fill: var(--svg-color--3e4002, #3e4002);
  d: path("M19.2 21.986q.001-.022-.004-.043c.066-.079.175-.048.252-.097q.004.046.005.092c-.065.111-.146.148-.253.048");
}

.ngnbctb1d {
  fill: var(--svg-color--fafa01, #fafa01);
  d: path("m29.05 25.437l-.058.053c-.067.063-.149.063-.231.063c-.082-.002-.163-.004-.23-.062a.2.2 0 0 1-.031-.072a.2.2 0 0 1 .017-.075q.027-.034.067-.015h.115c.097-.002.194-.004.289.02a.11.11 0 0 1 .062.088");
}

.nhd8tjbfe {
  fill: var(--svg-color--fcfb01, #fcfb01);
  d: path("M28.18 25.377c-.012-.075.035-.105.098-.121c.082.043.187-.012.258.068l-.005.066a.55.55 0 0 1-.308-.002a.04.04 0 0 1-.043-.011");
}

.ni018-bap {
  fill: var(--svg-color--3d3e21, #3d3e21);
  d: path("m20.316 37.883l-.041-.137l.255.052c-.017.042-.053.046-.09.046c-.033.039-.061.09-.124.039");
}

.ni2uprbsg {
  fill: var(--svg-color--e1d2c3, #e1d2c3);
  d: path("M25.919 26.04q-.021.011-.048.007c-.051-.082-.038-.168-.008-.255l.044-.09l.019.289q.02.02.011.034q-.008.015-.018.015");
}

.ni3e26ind {
  fill: var(--svg-color--5e600d, #5e600d);
  d: path("M29.767 36.57q.073.046.146.097l.099.19l-.147.023c-.014-.109-.13-.187-.098-.31");
}

.njyo8ubau {
  fill: var(--svg-color--f9f80a, #f9f80a);
  d: path("m12.184 30.16l-.064-.06l.11-.151q.135-.056.271-.11c.063-.07.157-.072.231-.118c.039-.026.069-.063.118-.072c.072.003.14-.039.216-.029c.054.022.073.068.077.125a.17.17 0 0 1-.05.106l.004-.003c-.107.008-.214.013-.305.085c-.07.026-.149.036-.212.086c-.085.042-.184.065-.255.136z");
}

.nk4rkev_n {
  fill: var(--svg-color--d8d804, #d8d804);
  d: path("m25.21 34.707l-.063.017l-.047-.01q-.004-.025-.012-.05q-.018-.027.007-.049l.015-.021l.09.069q.015.02.01.044");
}

.nkd-enorl {
  fill: var(--svg-color--5b5d0a, #5b5d0a);
  d: path("M30.741 25.935c-.059-.051-.131-.043-.2-.055q-.02-.015-.013-.036q.004-.019.01-.018c.031-.01.065-.005.094-.025c.063.038.192 0 .159.142z");
}

.nko_f774w {
  fill: var(--svg-color--eff365, #eff365);
  d: path("m19.01 35.03l.031-.002l.058.048l-.066.108q-.07.059-.145.007c-.028-.105.031-.144.122-.161");
}

.nlenm-7px {
  fill: var(--svg-color--dbdb38, #dbdb38);
  d: path("M15.61 37.01q.078.03.154.057c-.068.022-.159-.021-.205.068q-.03-.035-.063-.068c.021-.057.071-.048.114-.057");
}

.nllcv2cgb {
  fill: var(--svg-color--181700, #181700);
  d: path("m18.17 35.28l.003.06a.2.2 0 0 1-.051-.003l-.002-.002l-.022-.028l.015-.031q.032-.021.059.007z");
}

.nly46hbwt {
  fill: var(--svg-color--48480d, #48480d);
  d: path("m11.907 31.487l-.031.005c-.056-.017-.034-.074-.058-.108c-.111-.05-.02-.105-.007-.158l.104-.046q.043.049.005.102q-.005.102-.013.205");
}

.nm0g2rg9a {
  fill: var(--svg-color--403400, #403400);
  d: path("m28.946 29.11l.158-.039l.199.018c.024.026.029.053-.002.077q-.176-.026-.355-.056");
}

.nm6sl8b-r {
  fill: var(--svg-color--fdfd02, #fdfd02);
  d: path("M11.96 30.976c-.153.005-.092-.111-.099-.181c-.009-.109 0-.222 0-.332c.046-.164.2-.229.308-.337a.4.4 0 0 1 .136-.039c.093-.007.171-.055.253-.093c.079-.041.172-.049.25-.088c.077-.047.165-.064.247-.091a.4.4 0 0 1 .061-.026c.087-.041.188-.049.276-.087c.061-.028.113-.071.174-.097a.3.3 0 0 1 .101-.014c.145.018.262-.067.393-.101a2 2 0 0 0 .125-.068c.204-.071.408-.132.627-.139c.041.005.078.021.119.026c.058.009.16.088.122-.07c.105-.104.24-.076.368-.082a.43.43 0 0 0 .255-.06a.3.3 0 0 1 .08.003c.15.038.168.15.161.278c-.003.092.005.186-.01.278a.2.2 0 0 1-.106.117c-.082.03-.166.059-.243.103a.4.4 0 0 1-.144.028c-.102.004-.209-.012-.297.059a.3.3 0 0 1-.067.025a.4.4 0 0 1-.104-.002c-.12-.04-.223.026-.329.054c-.102.028-.214.01-.31.071c-.159.095-.338.136-.516.179a.8.8 0 0 0-.365.062a.7.7 0 0 0-.241.106a.2.2 0 0 1-.061.024c-.109-.008-.178.065-.26.118a8 8 0 0 0-.673.305c-.07.039-.136.111-.231.071");
}

.nmi_0-b0c {
  fill: var(--svg-color--dbd90c, #dbd90c);
  d: path("m26.678 25.689l.074-.12l.086.017l.053.053c0 .068-.03.115-.101.13a.12.12 0 0 1-.112-.08");
}

.nmuavtquy {
  fill: var(--svg-color--3c3f41, #3c3f41);
  d: path("M22.14 30.913a.32.32 0 0 0 .036-.196c.058.078.087.152-.036.196");
}

.nnqpln1mk {
  fill: var(--svg-color--f6f629, #f6f629);
  d: path("M18.07 25.584c-.118.053-.335-.121-.356.154c-.034.027-.059.007-.084-.014a.7.7 0 0 1-.116-.156l-.005-.031c.19-.031.388-.119.561.047");
}

.nphc91b_p {
  fill: var(--svg-color--f9fb21, #f9fb21);
  d: path("M18.12 35.2a.06.06 0 0 1 .04-.01q.028.007.022.023q-.005.018-.013.018l.001.002q-.028.028-.052-.002a.03.03 0 0 0 .002-.031");
}

.npz9rgbyy {
  fill: var(--svg-color--55530a, #55530a);
  d: path("m16.13 37.952l.169.147c-.121.029-.196-.002-.169-.147");
}

.nq_ja3bse {
  fill: var(--svg-color--f7f60c, #f7f60c);
  d: path("M29.916 26.827c-.082.028-.177.022-.246.089q-.083.015-.164.026q-.104.024-.207.051l.003-.024c-.041-.035-.046-.079-.033-.129c.015-.036.05-.049.077-.07l.166-.005c.076-.11.194-.091.303-.096c.076.038.169-.013.238.052l-.031.092z");
}

.nrqhceo8v {
  fill: var(--svg-color--636000, #636000);
  d: path("M26.326 24.867v.255a.2.2 0 0 1-.048.005c-.031-.039-.083-.053-.114-.094c-.009-.021-.005-.037.008-.056c.048-.04.069-.12.154-.11");
}

.ns1nh9b0s {
  fill: var(--svg-color--e7e70f, #e7e70f);
  d: path("m14.742 36.34l-.056.116c-.073-.03-.104-.087-.111-.163c-.063-.044-.14-.075-.148-.168l-.02-.011l-.02-.067c.02-.046-.002-.129.094-.112l.147.161c.088-.029.117.033.148.094c.013.056.009.107-.034.15");
}

.nsgclnb3x {
  fill: var(--svg-color--243200, #243200);
  d: path("m18.18 39.07l.051-.044c.163.017.311.063.409.205q.027.017.017.031t-.02.012l.005.017a28 28 0 0 1-.462-.221");
}

.nst8uibhv {
  fill: var(--svg-color--7b1e09, #7b1e09);
  d: path("M30.738 31.04q-.081.013-.161.021a.32.32 0 0 1 .319-.133a.2.2 0 0 0 0 .048c-.02.104-.083.095-.158.064");
}

.nt7doctwd {
  fill: var(--svg-color--2f3506, #2f3506);
  d: path("M12.372 27.688c-.024.106-.031.219-.094.313c.002-.112-.039-.239.094-.313");
}

.ntdhkk8wk {
  fill: var(--svg-color--2c2c04, #2c2c04);
  d: path("m25.455 34.2l-.168-.009c.021-.065-.02-.153.071-.192c.061.038.13.064.162.135a.1.1 0 0 1-.005.07q-.03.028-.06-.004");
}

.ntjo5bbzf {
  fill: var(--svg-color--383801, #383801);
  d: path("M32.33 31.526c-.172.093-.157.259-.162.416a.06.06 0 0 1-.069.009a.16.16 0 0 1-.069-.09c-.034-.182.043-.361.012-.543c.031-.086.142-.042.183-.11l.106.021a.43.43 0 0 1-.001.297");
}

.nu7020b6x {
  fill: var(--svg-color--888700, #888700);
  d: path("m24.08 40.567l-.014.033c-.061.073-.133.01-.2.015l.01-.098c.036-.049.087-.027.135-.027c.036.015.06.037.069.077");
}

.nud9glb1o {
  fill: var(--svg-color--4a4b0d, #4a4b0d);
  d: path("M31.35 30.05c-.061-.047-.188-.008-.184-.141c.073.03.179.02.184.141");
}

.nvdz45bbx {
  fill: var(--svg-color--123314, #123314);
  d: path("m16.401 34.2l-.086.012l-.08.003c-.019.009-.045.009-.045 0c-.02-.422-.241-.804-.258-1.228c.014-.055.038-.102.092-.127c.098.454.214.905.377 1.34");
}

.nvklpcmvi {
  fill: var(--svg-color--801312, #801312);
  d: path("M21.396 37.701q.647-.003 1.293-.002q.025.014.019.029q-.006.02-.014.018c-.465.084-.93.081-1.396.004c.015-.049.071-.021.098-.049");
}

.nvl54keir {
  fill: var(--svg-color--edef0e, #edef0e);
  d: path("M17.15 22.16c-.036-.085-.139-.028-.188-.084l.236-.152c.046-.084.137-.091.212-.122l.004.01c.012-.046.046-.044.082-.036c.044.023.064.063.079.108c.01.079-.048.122-.094.17a.2.2 0 0 1-.062.027c-.08 0-.14.057-.207.089a.07.07 0 0 1-.062-.01");
}

.nvp4jobuj {
  fill: var(--svg-color--524a42, #524a42);
  d: path("m26.938 29.589l.005.299c-.093-.087-.031-.197-.049-.296q.021-.005.044-.003");
}

.nx_lvccvs {
  fill: var(--svg-color--171900, #171900);
  d: path("M13.445 27.27q-.018.001-.037.005c-.019-.11.063-.176.116-.255l.017-.003c.014.102-.061.17-.096.253");
}

.nx6p4-wea {
  fill: var(--svg-color--fdfd05, #fdfd05);
  d: path("M18.687 35.69c-.086-.036-.109-.105-.103-.19c0-.068.015-.124.098-.129a.2.2 0 0 1 .051.053c.029.069.056.14.037.217c-.016.037-.038.064-.083.049");
}

.nxonwh37z {
  fill: var(--svg-color--f6f20b, #f6f20b);
  d: path("M27.363 22.249c.031.015.081-.003.096.05c.058.095-.008.136-.075.176a.2.2 0 0 1-.074.008c-.091-.038-.159-.106-.245-.151a.1.1 0 0 1-.039-.102c.024-.056.072-.074.128-.081c.089-.008.156.035.209.1");
}

.ny73zac7b {
  fill: var(--svg-color--eeea0b, #eeea0b);
  d: path("m28.736 23.485l.059-.065l.099-.035c.151.236.399.387.56.615a.04.04 0 0 0 .003.047l-.106.053c-.127.02-.145-.097-.204-.162l-.246-.245q-.084-.104-.165-.208");
}

.nz5g-ccor {
  fill: var(--svg-color--434507, #434507);
  d: path("M30.01 36.516a4 4 0 0 1-.507-.518c.248.097.392.306.543.506a.05.05 0 0 0-.036.012");
}

.nzyyfw5rf {
  fill: var(--svg-color--e7ea22, #e7ea22);
  d: path("M19.351 40.563c.075-.021.19.039.207-.104c.058.003.118-.008.157.051l-.054.145c-.105-.025-.219-.027-.31-.092");
}

.o_94tibex {
  fill: var(--svg-color--2a2800, #2a2800);
  d: path("M19.308 21.23a.1.1 0 0 0 .044-.007c.077.027.161-.087.235.01c-.086.07-.186.041-.281.044a.05.05 0 0 1 .002-.047");
}

.o_i9dpbre {
  fill: var(--svg-color--6c6800, #6c6800);
  d: path("m18.218 31.02l-1.737-.002q-.02-.054.029-.082a7.6 7.6 0 0 1 1.687.001q.049.031.021.083");
}

.o-akqlb5i {
  fill: var(--svg-color--464743, #464743);
  d: path("M19.211 37.07c.093.01.208-.031.248.107q.023.013.017.024q-.01.013-.017.012c-.088-.039-.192-.049-.248-.143");
}

.o-lw9cb2n {
  fill: var(--svg-color--dad850, #dad850);
  d: path("m15.711 25.764l-.045-.07q.103 0 .206-.004c.007.158-.122.016-.161.074");
}

.o-xtlbcel {
  fill: var(--svg-color--eced02, #eced02);
  d: path("M26.17 34.815c.008-.061.024-.113.105-.093c-.01.087.092.148.054.244c-.077-.024-.121-.083-.159-.151");
}

.o19nplbab {
  fill: var(--svg-color--616207, #616207);
  d: path("M25.09 21.345q.027.023.054.043c.016.046-.01.069-.047.084c-.112-.082-.278-.06-.362-.192c.128-.029.237.05.355.065");
}

.o1g_wzwlr {
  fill: var(--svg-color--393603, #393603);
  d: path("m32.03 29.378l-.066-.506q.029-.03.063-.009c.098.166.025.351.058.521q-.03.023-.055-.006");
}

.o212jei5r {
  fill: var(--svg-color--838510, #838510);
  d: path("M22.274 26.09q-.002-.016.002-.032c.032-.076.039-.175.156-.171l.058.106q.019.02.011.031q-.008.013-.016.013c-.054.078-.133.063-.211.053");
}

.o288qbgov {
  fill: var(--svg-color--221201, #221201);
  d: path("m17.866 29.332l-.05-.039q.101-.005.206-.005q0 .023.005.048c.022.049.018.097-.041.111c-.09.022-.095-.059-.12-.115");
}

.o2d6wiwop {
  fill: var(--svg-color--920203, #920203);
  d: path("M27.04 25.17h-.021l-.02.003l-.053-.054c-.046-.086-.081-.17.003-.254q.054.006.105.007c.041.043.049.093.038.148c-.014.036-.028.072-.021.111q0 .032-.031.039");
}

.o2fbiibrg {
  fill: var(--svg-color--f1f35b, #f1f35b);
  d: path("m22.84 25.434l-1.639-.009q0-.015-.007-.028l.029-.039c.161-.082.336-.049.502-.046c.363.013.729-.05 1.09.039q.047.03.025.083");
}

.o2l8p6b7q {
  fill: var(--svg-color--edee69, #edee69);
  d: path("M17.575 30.363c.003-.037-.104-.098-.007-.101c.166-.005.342-.062.503.038c-.151.032-.315-.048-.459.051q-.02.003-.037.012");
}

.o2ud-qbzu {
  fill: var(--svg-color--f5f410, #f5f410);
  d: path("M23.03 21.753c-.007-.053-.049-.058-.091-.066l-.047-.087l.092-.005c.056.038.123-.007.183.02c.121.046.25.014.373.024q.057 0 .113.009c.133.06.268.115.421.092q.107.004.152.103c.023.059-.01.094-.052.126a.13.13 0 0 1-.107-.005l-.094-.015c-.102-.012-.21.017-.309-.029c-.082-.086-.189-.079-.295-.076c-.113-.028-.258.061-.339-.091");
}

.o326yhy0p {
  fill: var(--svg-color--f0f146, #f0f146);
  d: path("M29.31 32.16c-.02.055-.072.039-.111.053l-.194.003c.085-.107.201-.051.305-.056");
}

.o3a53hbkq {
  fill: var(--svg-color--c60000, #c60000);
  d: path("M25.919 29.886q-.029 0-.056.002l-.002-.292l.064.016c.073.091.066.184-.006.274");
}

.o3nq33bbr {
  fill: var(--svg-color--5d5f04, #5d5f04);
  d: path("m27.56 22.581l-.01.051q-.094-.051-.185-.106c.091-.077.137.012.195.055");
}

.o3rz4x0ym {
  fill: var(--svg-color--232600, #232600);
  d: path("M27.25 25.07h-.094c.005-.052-.03-.137.049-.135c.081.002.036.087.045.135");
}

.o40oj7bxy {
  fill: var(--svg-color--212100, #212100);
  d: path("M15.199 25.588c.115-.045.201.053.305.065q.023.015.015.029q-.005.017-.013.017c-.105-.034-.247.039-.307-.111");
}

.o4hcnccjv {
  fill: var(--svg-color--fcfc03, #fcfc03);
  d: path("m15.4 25.281l-.396-.045l-.059-.009c-.096.015-.178-.034-.269-.051l-.046-.003c-.034-.055-.118-.04-.146-.105l-.005-.105a.3.3 0 0 1 .094-.046c.065-.024.146.032.204-.036c.046-.069.126-.067.192-.098a.4.4 0 0 1 .061-.025l.122-.06a.64.64 0 0 1 .277-.048a.4.4 0 0 0 .235-.058a.2.2 0 0 1 .077.004c.268.123.121.343.127.529l-.002.001c-.033.078-.097.115-.171.142c-.096.02-.195.06-.295.013");
}

.o5doqv04g {
  fill: var(--svg-color--555505, #555505);
  d: path("M15.251 37.02c.022.076.065.15.051.233c-.12-.145-.339-.207-.358-.433c.124.033.154.214.307.2");
}

.o5g0jg_4g {
  fill: var(--svg-color--6c6c04, #6c6c04);
  d: path("M25.765 36.773c-.004.041-.011.086.046.101c-.036.053-.099.039-.148.053l.045-.155a.4.4 0 0 1 .057.001");
}

.o73w2ibia {
  fill: var(--svg-color--450d02, #450d02);
  d: path("M26.636 39.803v.096c-.051.065-.13.049-.197.07l-.009-.063q.102-.054.206-.103");
}

.o778ovjzm {
  fill: var(--svg-color--efea13, #efea13);
  d: path("m23.353 40.861l-.001-.095a.07.07 0 0 1-.016-.062a.2.2 0 0 1 .071-.073c.053-.019.104-.042.162-.03c.076 0 .146.058.226.019l.067-.005c.074-.06.149-.041.222.002c.017.034.017.065-.013.094c-.103.09-.25.018-.355.1l-.157.02z");
}

.o88xnet_d {
  fill: var(--svg-color--0b1009, #0b1009);
  d: path("M21.353 37.964q-.027.017-.055.038a23 23 0 0 0-.457-.007c-.041-.026-.087-.05-.051-.112z");
}

.o8pnmzc_g {
  fill: var(--svg-color--d0d012, #d0d012);
  d: path("m18.961 34.723l-.185-.063a.1.1 0 0 1 .007-.064a.16.16 0 0 1 .079-.061a.2.2 0 0 1 .067-.004c.056.015.109.031.131.096z");
}

.oa7ygmbjs {
  fill: var(--svg-color--eeee5d, #eeee5d);
  d: path("m20.07 40.663l.005-.099q.076 0 .151-.002c.018.046.13-.002.095.096z");
}

.oaq1zpv4q {
  fill: var(--svg-color--292900, #292900);
  d: path("M28.02 36.466q.177-.001.354-.007a.05.05 0 0 1 .002.05c-.076.06-.173 0-.25.043c-.07-.021-.156.056-.214-.036c.023-.045.078-.02.108-.05m-.599.107q.094-.009.186-.015c.055-.03.101-.033.117.042c-.06.076-.149.012-.217.053l-.201.009c-.02-.105.076-.061.115-.089");
}

.od5godb0u {
  fill: var(--svg-color--d8d356, #d8d356);
  d: path("M17.866 29.332c.054 0 .104.24.161.004c.106-.011.095.065.094.133c-.004.077-.064.067-.112.067a14 14 0 0 1-.354-.012c-.023-.063-.021-.11.065-.101c.08.02.121-.022.146-.091");
}

.oe6ov9bmr {
  fill: var(--svg-color--363a0a, #363a0a);
  d: path("M14.07 24.917v-.056c.033-.063.063-.132.155-.099l-.002.001c.065.166-.05.154-.153.154");
}

.og2pp4bet {
  fill: var(--svg-color--363500, #363500);
  d: path("m22.832 25.334l-1.623-.001a.1.1 0 0 1-.003-.045q.841-.007 1.682-.017z");
}

.oglu7tyca {
  fill: var(--svg-color--787900, #787900);
  d: path("m18.627 34.824l-.044-.009q-.022-.01-.019-.024q.003-.018.008-.017l.066-.005z");
}

.oh1o3ib_e {
  fill: var(--svg-color--a10000, #a10000);
  d: path("m30.847 32.727l.096-.235a.6.6 0 0 1-.04.317c-.054-.003-.023-.065-.056-.082");
}

.ohjovpqbn {
  fill: var(--svg-color--565511, #565511);
  d: path("M30.786 27.633c-.164-.014-.127-.151-.156-.25c.018-.021.036-.025.06-.004q.046.127.096.254");
}

.oi0q002ws {
  fill: var(--svg-color--dddd95, #dddd95);
  d: path("M25.27 34.811q.023.006.043-.006l.008.029a.045.045 0 0 1-.036.039l-.025-.003a.4.4 0 0 0 .01-.059");
}

.oifqxubgf {
  fill: var(--svg-color--efee4f, #efee4f);
  d: path("m27.863 36.559l-.099-.057c.077-.07.169-.036.257-.036l-.107.05z");
}

.oiste8b4s {
  fill: var(--svg-color--382200, #382200);
  d: path("M22.948 26.26c-.031.056-.085.048-.135.048q-.815 0-1.631-.004a.06.06 0 0 1-.042-.02c-.005-.003.008-.023.011-.034c.096-.083.211-.064.319-.064c.454-.007.905.005 1.357-.007a.2.2 0 0 1 .093.005q.05.025.028.076");
}

.ojcvv252j {
  fill: var(--svg-color--2e100d, #2e100d);
  d: path("M26.01 36.492a1 1 0 0 1 .258-.24q.03-.03.064-.003c.022.099-.045.161-.093.233c-.044.045-.085.096-.154.105c-.051-.009-.109-.016-.075-.095");
}

.ojjh2pb7l {
  fill: var(--svg-color--52540e, #52540e);
  d: path("m18.38 40.1l-.051-.006c-.049-.075-.205-.003-.208-.146c.104.021.234-.005.259.152");
}

.ojrd02gjg {
  fill: var(--svg-color--6c6c0d, #6c6c0d);
  d: path("M27.306 22.456c-.099-.005-.184-.029-.205-.145c.1.003.164.058.205.145");
}

.okh6exiib {
  fill: var(--svg-color--75280e, #75280e);
  d: path("M30.686 29.537c.084-.082.217-.02.301-.106l.056.156c-.024.041-.063.048-.104.048c-.099 0-.174-.05-.253-.098");
}

.olda0rb5m {
  fill: var(--svg-color--141414, #141414);
  d: path("m25.5 32.459l-.052-.06l.016-.708l.037-.002z");
}

.omo-k5-_u {
  fill: var(--svg-color--461c0b, #461c0b);
  d: path("M29.25 37.943c.102-.203.222-.391.457-.463a1.3 1.3 0 0 1-.457.463");
}

.omz95xb2j {
  fill: var(--svg-color--311503, #311503);
  d: path("M25.869 34.19h.132c.046-.026.072 0 .096.034a.14.14 0 0 1 0 .109c-.155.047-.259.198-.43.213a.2.2 0 0 1-.065-.022c-.026-.038-.065-.067-.064-.12a.23.23 0 0 1 .063-.12a.3.3 0 0 1 .087-.044c.058-.019.118-.045.181-.05");
}

.on6ecvumw {
  fill: var(--svg-color--2d2f03, #2d2f03);
  d: path("M13.524 27.02c.017-.13-.1-.176-.164-.255c.145-.005.263.084.397.108q.021.017.017.038q-.005.02-.012.02a.6.6 0 0 1-.174.106a.08.08 0 0 1-.064-.017");
}

.on7sz0b9f {
  fill: var(--svg-color--7a7807, #7a7807);
  d: path("M16.589 24.873a.2.2 0 0 1 .051 0c.069.087.061.17-.007.253l-.051-.007z");
}

.onfy21lrx {
  fill: var(--svg-color--4e4f12, #4e4f12);
  d: path("M16.23 34.457c.015-.087.224-.106.085-.246q.04-.044.086-.012l.118.258a.07.07 0 0 1-.041.055c-.064-.104-.164-.043-.248-.055");
}

.onlxp2pne {
  fill: var(--svg-color--373602, #373602);
  d: path("m31.05 31.854l-.014.194q-.045.042-.095.013c-.005-.138-.16-.109-.212-.193c.047-.141.147-.18.284-.153c.056.033.073.08.037.139");
}

.op68_vbgu {
  fill: var(--svg-color--545600, #545600);
  d: path("m29.2 36.622l.162-.11c.002.119-.077.175-.167.221c-.059-.04 0-.075.005-.111");
}

.opgd7hbiy {
  fill: var(--svg-color--fafc1c, #fafc1c);
  d: path("m18.28 35.02l.027-.041l.004-.004a.2.2 0 0 1 .056-.02l.024.019q.012.03-.015.051v.002a.07.07 0 0 1-.051.025l-.029-.006z");
}

.oqx4acced {
  fill: var(--svg-color--717400, #717400);
  d: path("M18.17 35.23a.1.1 0 0 0-.01-.041l.051-.008l.013.051z");
}

.or7l-9b3o {
  fill: var(--svg-color--3b430f, #3b430f);
  d: path("m17.769 36.563l-.296-.011c-.085-.041-.186.012-.27-.041l-.065-.046c.034-.039.072-.038.113-.008c.144.001.288.007.433.001c.08 0 .11.024.085.105");
}

.ornw-mygp {
  fill: var(--svg-color--ecec0a, #ecec0a);
  d: path("m12.985 35.33l.108-.043c.036-.043.066-.089.112-.123a.4.4 0 0 1 .056-.037c.07-.032.13-.08.186-.135a.5.5 0 0 1 .159-.073q.035-.01.072-.017c.135-.007.257-.101.399-.072c.055.021.079.061.083.118a.14.14 0 0 1-.023.069c-.075.064-.179.065-.26.115c-.072.051-.178.053-.219.146l.004-.006c-.062.047-.171-.01-.202.101c-.163-.003-.249.105-.326.227c-.061.05-.12.105-.19.015c-.033-.101.044-.187.041-.285");
}

.orqn45bwq {
  fill: var(--svg-color--1f3401, #1f3401);
  d: path("M19.457 39.576c-.146-.087-.339-.061-.467-.19c.215-.046.395.046.57.149q-.05.022-.103.041");
}

.osxsrlwcs {
  fill: var(--svg-color--e2e170, #e2e170);
  d: path("M14.732 24.907q.02.008.04.013c-.035.105-.115.028-.171.041z");
}

.otd-evm2t {
  fill: var(--svg-color--eceb5e, #eceb5e);
  d: path("m23.559 40.567l-.014.044l-.135.055c-.054-.002-.111.002-.149-.053c.089-.087.197-.039.298-.046");
}

.otw36q9fl {
  fill: var(--svg-color--efed6a, #efed6a);
  d: path("m20.547 40.671l-.061-.012c-.031-.021-.084-.032-.051-.09c.114.007.239-.048.345.042c-.062.077-.154.048-.233.06");
}

.ou-fh34uv {
  fill: var(--svg-color--e4df01, #e4df01);
  d: path("M26.831 29.743c-.082-.13-.029-.272-.044-.409c.085.047.029.138.059.202z");
}

.ou0pzpb3e {
  fill: var(--svg-color--e2e266, #e2e266);
  d: path("m14.845 29.332l.204-.049l.044.08c-.086.017-.174.053-.248-.031");
}

.ouzg2xzry {
  fill: var(--svg-color--e7e810, #e7e810);
  d: path("M16.709 23.23c.02-.077.072-.11.149-.11c.053-.049.106-.099.179-.118c.043-.013.077-.043.122-.048a.13.13 0 0 1 .108.07a.1.1 0 0 1-.007.066c-.07.072-.164.113-.243.174c-.094.055-.171.137-.268.186c-.051.045-.089.105-.158.127a.2.2 0 0 1-.072 0c-.048-.015-.087-.041-.106-.089c-.004-.072.046-.102.102-.126c.077-.026.1-.131.194-.132");
}

.ov4lw44wx {
  fill: var(--svg-color--194d12, #194d12);
  d: path("M19.868 37.945c.186.026.383-.054.562.051c-.187-.024-.383.058-.562-.051");
}

.ovf32dntx {
  fill: var(--svg-color--5e1904, #5e1904);
  d: path("M28.731 29.02c.14-.104.258-.033.373.05c-.043.053-.108.015-.158.039z");
}

.ovoo0dsvf {
  fill: var(--svg-color--393400, #393400);
  d: path("m28.998 27.13l-.214-.01l.017-.038c.073-.067.155-.034.238-.021l.056.056z");
}

.owe5yebol {
  fill: var(--svg-color--1f2000, #1f2000);
  d: path("m21.712 24.867l.005.308l-.01.002q-.028.03-.063.003a.2.2 0 0 1-.032-.064q-.006-.034-.01-.07c0-.063.008-.121.052-.169l.055-.06z");
}

.owh90fv_d {
  fill: var(--svg-color--fdfd00, #fdfd00);
  d: path("m17.513 30.511l.001-.101l.048.014l.045.036c-.019.039-.055.048-.094.051");
}

.oxw581idy {
  fill: var(--svg-color--262900, #262900);
  d: path("m17.913 21.833l-.203.089c.003-.135.131-.123.205-.176q.049.044-.002.087");
}

.oz2k8ybjg {
  fill: var(--svg-color--2f3100, #2f3100);
  d: path("M25.301 35.18q.013.022.003.05q-.027.028-.058.003q-.122 0-.244.003l-.045-.057l.076-.048c.077.077.179.029.268.049");
}

.oz9q58bpt {
  fill: var(--svg-color--e8ea0e, #e8ea0e);
  d: path("M20.773 20.808a.2.2 0 0 1 .023-.036c.171-.019.349.018.516-.048c.096-.005.161.02.137.137c-.061.077-.146.054-.226.059c-.09 0-.181.002-.27-.003a.3.3 0 0 1-.138-.051a.2.2 0 0 1-.042-.058");
}

.p_1zeyb0g {
  fill: var(--svg-color--3c3b03, #3c3b03);
  d: path("m15.91 32.07l-.043-.231c.113.059.022.154.043.231");
}

.p_qbk242d {
  fill: var(--svg-color--666501, #666501);
  d: path("M17.607 26.14v-.097a.16.16 0 0 1 .166-.026c.115.015.233-.023.348.024l.054.096z");
}

.p-gr18b6r {
  fill: var(--svg-color--251414, #251414);
  d: path("M25.503 26.512q-.022-.003-.041-.002c-.077-.082-.178-.038-.267-.039c-.818-.009-1.639-.012-2.459-.017q-.024-.015-.017-.024q.01-.014.017-.014q1.306-.006 2.613-.007c.068 0 .169-.032.154.103");
}

.p-q2wtbgh {
  fill: var(--svg-color--3f4000, #3f4000);
  d: path("m16.886 25.07l-.145.005c-.029-.063-.072-.13.041-.154l.108.003q0 .075-.004.146");
}

.p1b8aflqb {
  fill: var(--svg-color--5b5e07, #5b5e07);
  d: path("M30.331 31.996c-.108.083-.247.052-.363.098q-.027-.02-.019-.036q.01-.018.019-.019c.114-.062.229-.128.363-.043");
}

.p1bal_bbd {
  fill: var(--svg-color--ebea11, #ebea11);
  d: path("M25.503 34.16c-.06-.041-.12-.082-.145-.156l.094-.034q.005-.065.049-.019c-.012.064.031.104.066.146q-.013.052-.064.063");
}

.p2lsb6g2g {
  fill: var(--svg-color--d6d512, #d6d512);
  d: path("m17.857 35.397l-.157-.163c-.021-.037-.071-.061-.069-.113a.2.2 0 0 1 .063-.125c.039-.029.08-.052.132-.032c.083.084.167.166.218.274a.2.2 0 0 1 .004.069a.2.2 0 0 1-.061.083a.2.2 0 0 1-.064.025a.2.2 0 0 1-.066-.018");
}

.p2o__8j9m {
  fill: var(--svg-color--590000, #590000);
  d: path("M27.658 23.846q-1.577.006-3.149.008c-.625 0-1.248-.008-1.871-.014l-.008-.046l.044-.024c1.652-.007 3.304-.002 4.956-.003q.055.024.028.079");
}

.p2pbifb9c {
  fill: var(--svg-color--fcfc02, #fcfc02);
  d: path("m29.908 25.02l.058.051c.075.07.184.066.265.123c.075.045.159.066.233.115l.085.023l.185.251l.158.305l-.063.049q-.03.023-.062.005c-.053-.036-.104-.077-.167-.095l-.188-.063q-.1-.034-.196-.063c-.077-.026-.152-.055-.231-.071c-.095-.016-.184-.056-.282-.053a1 1 0 0 1-.183-.015c-.098-.021-.183-.07-.271-.11a1.3 1.3 0 0 1-.186-.093c-.067-.05-.145-.043-.221-.042c-.059 0-.115.016-.172.023a.2.2 0 0 1-.109-.02c-.123-.098-.309-.063-.417-.192c-.009-.188-.101-.388.082-.548c.11-.046.209.004.311.033a1 1 0 0 1 .108.033c.091.031.186.047.271.094s.183.029.272.051c.098.027.187.099.298.063c.151.021.3.043.422.146");
}

.p2zbyhbpt {
  fill: var(--svg-color--f9fc1b, #f9fc1b);
  d: path("M18.321 35.02a.06.06 0 0 1-.002.044l-.018.003l-.019-.006q-.004-.025.014-.041z");
}

.p39on-jhb {
  fill: var(--svg-color--eff05d, #eff05d);
  d: path("m19.2 37.646l.102-.015c.082.026.18-.028.252.051c-.12-.002-.244.045-.354-.036");
}

.p3ab5wifo {
  fill: var(--svg-color--f0f20a, #f0f20a);
  d: path("M13.798 26.669c.125.097.291.081.426.148c.068.036.143.058.215.087q.124.06.257.094q.06.014.067.075c-.009.073-.06.104-.12.125c-.074.012-.144-.01-.216-.022c-.056-.016-.109-.04-.164-.061a1 1 0 0 0-.293-.084a.5.5 0 0 1-.1-.025c-.053-.024-.099-.059-.155-.077c-.118-.041-.233-.089-.359-.102a.5.5 0 0 1-.104-.021c-.056-.019-.113-.036-.161-.074a.13.13 0 0 1-.023-.104a.14.14 0 0 1 .045-.058l.034-.01q.159 0 .314.004c.113.03.208.122.337.105");
}

.p3c673bax {
  fill: var(--svg-color--e0d34f, #e0d34f);
  d: path("m22.59 21.686l.352.001c.064-.03.11-.027.109.06a.16.16 0 0 1-.117.041c-.082-.02-.168-.017-.25-.036c-.037-.016-.099.009-.094-.066");
}

.p3p0322xw {
  fill: var(--svg-color--173608, #173608);
  d: path("M15.817 22.869c-.034.057-.099.043-.147.063c.024-.164.147-.202.284-.22c.002.095-.111.086-.137.157");
}

.p5ddo5bpd {
  fill: var(--svg-color--ebeb0a, #ebeb0a);
  d: path("m29.507 25.685l-.001-.149l.215.005c.064.031.145.046.133.146a.2.2 0 0 1-.029.067a.2.2 0 0 1-.104.041c-.077.003-.151-.005-.202-.076q-.007-.016-.012-.034");
}

.p76_eybtp {
  fill: var(--svg-color--530000, #530000);
  d: path("m29.813 37.28l.004.105q-.018.091-.108.101c-.062-.094.034-.138.063-.2q.019-.029.041-.006");
}

.p7taz0bif {
  fill: var(--svg-color--eaeb41, #eaeb41);
  d: path("M14.582 32.15c.095.06.202.063.309.061a.9.9 0 0 0 .493.094q.053 0 .106.009c.066.022.14.032.189.088l.101.009q.07.048.136.099l-.053.099l-.052.013c-.135-.013-.276.009-.408-.044c-.401-.096-.809-.155-1.208-.252a1.7 1.7 0 0 1-.315-.095c-.05-.007-.112.012-.128-.063c.062-.105.181-.076.271-.113q.105 0 .209-.002c.089.061.192.056.291.067a.1.1 0 0 1 .059.03");
}

.p7vyrabnr {
  fill: var(--svg-color--f5f507, #f5f507);
  d: path("M28.484 26.972h.098c.059-.058.14-.06.213-.075a1 1 0 0 1 .271-.028c.05.003.103-.038.149.007q.045.076.002.15c-.038.041-.087.045-.138.048a.5.5 0 0 0-.232.043l-.027.02a.2.2 0 0 1-.062.03c-.056.013-.113.01-.171.01h-.067c-.075.006-.159-.02-.224.046c-.039.028-.08.042-.126.015c-.074-.038-.045-.104-.045-.161c.094-.128.238-.079.359-.105");
}

.p966grlob {
  fill: var(--svg-color--565500, #565500);
  d: path("m29.05 25.437l-.053-.05q-.02-.02-.015-.043t.01-.022c.038-.017.072-.024.101.017c.041.058.144.012.169.096c-.069.106-.141.034-.212.002");
}

.pa11hxb2t {
  fill: var(--svg-color--2c2d00, #2c2d00);
  d: path("m14.407 36.12l-.229-.123c.028-.1.108-.106.19-.108l.012.013c.02.05.02.104.038.155a.1.1 0 0 1-.011.063");
}

.padw24b0o {
  fill: var(--svg-color--6c1d07, #6c1d07);
  d: path("m25.763 37.699l.457-.043q.032.009.024.023c-.008.014-.012.015-.017.015c-.12.126-.272.095-.419.09l-.053-.031q-.016-.03.008-.054");
}

.pal4s2ybs {
  fill: var(--svg-color--f5f512, #f5f512);
  d: path("M15.15 38.09q-.005.06-.008.121c-.089-.008-.148-.059-.192-.131q-.098-.1-.196-.196c-.067-.017-.072-.1-.135-.123c-.077-.039-.046-.079 0-.118q.039-.009.077-.015c.134-.021.199.097.303.138a.2.2 0 0 1 .046.051c.031.091.168.144.105.273");
}

.pb_qfzbny {
  fill: var(--svg-color--262702, #262702);
  d: path("M25.866 35.07h.096l.061.146l-.004.063c-.051.025-.087-.004-.121-.033c-.026-.036-.06-.071-.033-.122z");
}

.pb-firbwu {
  fill: var(--svg-color--676700, #676700);
  d: path("m18.533 35.27l.044.217c-.155-.044-.118-.127-.044-.217");
}

.pb1vly6xv {
  fill: var(--svg-color--464500, #464500);
  d: path("M12.584 30c.057-.063.115-.116.209-.104c.051-.017.063.003.048.05c-.074.063-.169.065-.257.092q-.027-.012-.02-.024q.01-.014.02-.014");
}

.pc-perbww {
  fill: var(--svg-color--6b6801, #6b6801);
  d: path("m25.763 30.963l1.751.018c-.031.053-.084.05-.135.05q-.794-.002-1.588-.007a.06.06 0 0 1-.042-.023c-.005-.007.009-.025.014-.038");
}

.pc7qm4bsz {
  fill: var(--svg-color--535600, #535600);
  d: path("M13.597 31.28c-.113.068-.224.117-.297-.049q-.025-.015-.019-.033q.01-.016.019-.016z");
}

.pckc5pb6k {
  fill: var(--svg-color--505600, #505600);
  d: path("M15.05 23.798c-.019.059-.061.042-.102.036q0-.019.003-.036a.12.12 0 0 1 .051-.052h.002a.2.2 0 0 1 .044-.004q.021.019.014.037q-.007.02-.012.019");
}

.pe9cmimds {
  fill: var(--svg-color--f1f10f, #f1f10f);
  d: path("M26.826 23.13c-.115-.01-.168-.113-.253-.166c-.04-.033-.12-.02-.11-.105c.018-.058.044-.108.116-.11c.083.017.141.079.213.113l.258.11c.027.048.048.098.033.153a.13.13 0 0 1-.083.08c-.075.014-.121-.039-.174-.075");
}

.peo5drbyq {
  fill: var(--svg-color--f0f007, #f0f007);
  d: path("M15.817 22.869q.075.034.103.109q.02.028.008.06a.3.3 0 0 1-.063.074a.8.8 0 0 1-.186.132a1 1 0 0 0-.271.264c-.063.084-.125.172-.229.209a.2.2 0 0 1-.063 0c-.021.014-.014-.051-.043-.018q-.002.03-.021.049a.05.05 0 0 1-.051-.002q-.01-.038-.017-.077c-.036-.044-.029-.09-.005-.136c.115-.101.202-.234.345-.303c.062-.056.12-.113.182-.17c.051-.049.087-.116.164-.133v.005c.029-.069.09-.062.147-.063");
}

.peq2gqbtb {
  fill: var(--svg-color--666500, #666500);
  d: path("m23.15 40.1l-.108-.012a.1.1 0 0 1-.053-.045l.076-.093a.02.02 0 0 0 .024-.008l.101.054c.02.047 0 .079-.04.104");
}

.pf8gg5yfy {
  fill: var(--svg-color--555805, #555805);
  d: path("m16.431 23.483l-.113.051c-.012-.149.122-.162.209-.22q.02.012.017.024q-.005.015-.012.015z");
}

.pfrc4v-0q {
  fill: var(--svg-color--1e160e, #1e160e);
  d: path("M30.827 25.389q.03.053.063.107c.044.045.024.076-.02.104c-.055-.001-.108.017-.163.007c-.097-.072-.194-.143-.179-.284c.056-.042.114-.024.176-.007c.046.015.095.025.123.073");
}

.pg5kddtul {
  fill: var(--svg-color--1e1c00, #1e1c00);
  d: path("M26.432 29.12v-.142l.101.014l.049.089c-.039.056-.103.019-.15.039");
}

.pjaxklbhj {
  fill: var(--svg-color--d4dce6, #d4dce6);
  d: path("M24.594 30.25c.091-.003.146.041.148.132c.001.087-.052.138-.14.143c-.093.005-.146-.055-.146-.137c-.002-.077.037-.147.138-.138");
}

.pjlu02ann {
  fill: var(--svg-color--1e2f02, #1e2f02);
  d: path("m17.718 22.822l-.005-.051c.26-.054.467-.231.719-.304c-.18.237-.445.3-.714.355");
}

.pk52-zbyo {
  fill: var(--svg-color--2b2c00, #2b2c00);
  d: path("m12.269 32.513l.015.048c.041.08.084.161.048.256a.2.2 0 0 0-.007.047c-.145-.061-.077-.195-.104-.298c-.021-.053.002-.063.048-.053");
}

.pk80tou1t {
  fill: var(--svg-color--352f07, #352f07);
  d: path("M29.555 25.87c-.051-.046-.054-.104-.048-.167l.199.039c.039.068-.026.099-.055.142l.009.01c-.045.031-.081.034-.105-.024");
}

.pl5bzacbp {
  fill: var(--svg-color--f9f904, #f9f904);
  d: path("M18.492 36.1c-.11-.059-.163-.172-.247-.256a.6.6 0 0 1-.193-.238c.018-.086.085-.139.132-.206c.075-.07.155-.138.2-.236c.064-.028.113-.005.156.044q.018.028.02.063c-.003.063-.019.127.029.182q.02.024.033.054c.026.072.072.135.101.207a.26.26 0 0 1-.035.197q-.067.096-.136.19q-.03.021-.06-.001");
}

.pla0plqyn {
  fill: var(--svg-color--959903, #959903);
  d: path("m22.272 26.1l-.458.003a.1.1 0 0 1 .001-.041c-.021-.065-.063-.138.048-.162q.031.012.058.035c.092.084.217.03.319.076q.034.015.049.048l-.015.032z");
}

.plgaksbwf {
  fill: var(--svg-color--191700, #191700);
  d: path("M18.221 35.23q-.003.027-.008.053l-.024.021l-.028-.016l-.01-.03q.005-.017.012-.031l.031-.01q.013.008.027.013");
}

.pmk02ibez {
  fill: var(--svg-color--f5f44f, #f5f44f);
  d: path("m18.214 26.2l-1.773-.004c-.01-.032.012-.044.038-.053l.618.002c.159-.106.342-.051.513-.067c.189.012.385-.032.565.064l.048.015a.07.07 0 0 1-.009.043");
}

.pnzcgvbyb {
  fill: var(--svg-color--e6e464, #e6e464);
  d: path("M29.74 30.05c-.078-.015-.167.017-.234-.048c.083-.004.169-.022.251.014c.004.002.005.015.002.02q-.007.008-.019.014");
}

.por3g4b0q {
  fill: var(--svg-color--d3d50b, #d3d50b);
  d: path("m30.22 25.15l.01-.078c.079-.02.139.018.197.059q.004.054.004.109c-.066.045-.122.016-.177-.023a.12.12 0 0 1-.034-.067");
}

.pr_d8mjuf {
  fill: var(--svg-color--552727, #552727);
  d: path("M17.192 35.2c.078.031.124.086.118.176q-.015.032-.041.009c-.044-.055-.138-.086-.077-.185");
}

.pr4gmnbki {
  fill: var(--svg-color--834009, #834009);
  d: path("M28.733 25.487q.008.018.013.038c-.005.036-.036.039-.06.051a.24.24 0 0 1-.256-.087a.1.1 0 0 1-.002-.042c.026-.047.053-.051.081-.001z");
}

.prpsz7tab {
  fill: var(--svg-color--1b1c00, #1b1c00);
  d: path("m25.919 22.386l-.002-.009c.081.002.142.045.199.096q-.008.016.007.026c-.093.005-.182.005-.204-.113");
}

.psbvhx0ix {
  fill: var(--svg-color--693618, #693618);
  d: path("m27.09 38.36l-.041.053c-.081.017-.129.105-.221.092c.043-.128.147-.145.262-.145");
}

.psdmzfbfs {
  fill: var(--svg-color--1c1900, #1c1900);
  d: path("M25.01 34.497q.005-.02-.004-.038l.015-.003h.021l.054.002l-.003.06l-.021.017a.1.1 0 0 1-.055 0q-.022-.01-.016-.023q.001-.016.009-.016");
}

.psz8ufbrz {
  fill: var(--svg-color--4b4b04, #4b4b04);
  d: path("M30.584 34.512c.007.164.195.212.231.358c-.106-.007-.146-.112-.227-.156c-.061-.028-.133-.036-.18-.091a.3.3 0 0 1-.063-.125a.12.12 0 0 1 .028-.1c.106-.025.151.056.211.114");
}

.pt1-uqb4i {
  fill: var(--svg-color--f6f932, #f6f932);
  d: path("m17.15 26l.35-.005c-.104.128-.231.056-.352.043z");
}

.ptjzvacfi {
  fill: var(--svg-color--454700, #454700);
  d: path("M15.507 31.738c-.072-.005-.149.017-.209-.049c.063-.094.139-.017.208-.019q.031.034.001.068");
}

.ptti7-bpw {
  fill: var(--svg-color--f1ee6b, #f1ee6b);
  d: path("m23.56 21.682l-.056-.084c.117.002.242-.061.344.047c-.064.016-.144-.045-.19.041q-.051-.004-.098-.004");
}

.pucdy5bsq {
  fill: var(--svg-color--e5e421, #e5e421);
  d: path("M30.439 34.61c.075-.003.118.043.149.104c-.071.04-.05.112-.061.173a1 1 0 0 1-.267-.27c.059-.056.12-.045.179-.007");
}

.punrmbcea {
  fill: var(--svg-color--d8d80b, #d8d80b);
  d: path("m18.433 34.512l.009-.211c.018-.051.051-.075.104-.063c.098.056.226.07.269.198a.13.13 0 0 1-.012.068a.2.2 0 0 1-.053.046a.4.4 0 0 1-.136.034c-.073 0-.137-.018-.187-.076z");
}

.pv4eiyb5r {
  fill: var(--svg-color--ede90b, #ede90b);
  d: path("m28.07 38.871l-.002-.055a.14.14 0 0 1-.036-.099c.036-.142.148-.21.265-.276c.053-.008.089.023.125.055l.012.074c.02.075-.021.117-.082.147l-.072.06c-.06.055-.094.166-.21.094");
}

.pw-6_gbsp {
  fill: var(--svg-color--1e1401, #1e1401);
  d: path("M22.84 25.434a.05.05 0 0 0-.005-.047a.05.05 0 0 1-.02-.046q.006-.037.02-.072q.007-.024.007-.051c0-.027.001-.036.003-.054c.168.076.103.191.048.305q-.027-.02-.053-.035");
}

.pxe33dhch {
  fill: var(--svg-color--606127, #606127);
  d: path("M18.07 35.38h-.051v-.051h.051z");
}

.pxwk1bbzq {
  fill: var(--svg-color--eff10a, #eff10a);
  d: path("m20.02 20.93l.093-.063c.089-.074.193-.042.292-.05c.098.008.197-.017.295.01a.14.14 0 0 1 .061.054q.013.04.003.081a.15.15 0 0 1-.12.092c-.072.009-.143-.018-.215-.018c-.076-.002-.153-.009-.226.029c-.051.023-.1.05-.157.034c-.08-.045-.046-.109-.026-.169");
}

.py12ucbpo {
  fill: var(--svg-color--f4f25c, #f4f25c);
  d: path("M26.994 25.22q.236 0 .472.003l.042.038l-1.692.008a.1.1 0 0 1-.002-.032z");
}

.pyell0blu {
  fill: var(--svg-color--861f06, #861f06);
  d: path("m27.2 23.387l.084.006l.084.093c-.135.101-.12-.053-.168-.099");
}

.pyhyip-0o {
  fill: var(--svg-color--535406, #535406);
  d: path("m26.14 22.605l-.016-.106l-.007-.026c.097.008.188.024.21.143q-.015.011-.026.023c-.061.023-.116.026-.161-.034");
}

.pyod10oei {
  fill: var(--svg-color--151500, #151500);
  d: path("M32.17 30.29c-.082-.038-.158-.082-.148-.192c.06-.012.045-.067.063-.102c.026-.033-.02-.124.079-.101z");
}

.pz25ukgdq {
  fill: var(--svg-color--131400, #131400);
  d: path("m22.989 40.05l.053.045l-.253.007v-.041q.102-.007.2-.011");
}

.pzliixduf {
  fill: var(--svg-color--f4f407, #f4f407);
  d: path("m27.457 25.795l.007.099q-.01.051-.017.104c-.094.083-.202.072-.311.043c-.102-.044-.13-.145-.176-.231a.6.6 0 0 0-.086-.138a.15.15 0 0 1-.037-.086c.102-.176.27-.065.404-.087c.246-.036.143.197.216.296");
}

.q_djwt-ov {
  fill: var(--svg-color--e5e306, #e5e306);
  d: path("m27.355 23.324l-.072.068c-.029.019-.058.014-.084-.006c-.021-.077-.077-.105-.149-.11c-.034-.022-.077-.038-.069-.092l.067-.064c.046-.032.091-.039.137 0l.181.065c.021.048.032.096-.011.139");
}

.q_t9j5b7c {
  fill: var(--svg-color--f3ef1a, #f3ef1a);
  d: path("m27.21 39.23l.021-.002c.047.013.092-.029.14-.004a.14.14 0 0 1 .042.115l-.065.092l-.188.078l-.015-.144c-.006-.059.035-.094.065-.135");
}

.q-2c-abrz {
  fill: var(--svg-color--797a0a, #797a0a);
  d: path("M18.689 35.432a.2.2 0 0 0 .051.002a.32.32 0 0 1 .101.201q0 .029-.002.056l-.101-.05z");
}

.q-e2zsalv {
  fill: var(--svg-color--264009, #264009);
  d: path("M18.18 39.07c-.27-.131-.563-.224-.784-.441c.32.044.587.2.835.397a.07.07 0 0 1-.051.044");
}

.q-kci1-ox {
  fill: var(--svg-color--848404, #848404);
  d: path("m31.718 28.916l.053-.051q.049.046.033.115q-.028.054-.053.108a.2.2 0 0 1-.033-.172");
}

.q-sz056cx {
  fill: var(--svg-color--dfe013, #dfe013);
  d: path("M26.22 35.02c.092.039.169.085.099.203l-.078.109c-.047.001-.09-.009-.121-.048c-.007-.01-.01-.021-.017-.031v-.033a.4.4 0 0 1 .117-.2");
}

.q-uhp2b6t {
  fill: var(--svg-color--1a2000, #1a2000);
  d: path("m29.15 33.42l.039-.037c.091.042.183.084.204.198c-.113-.003-.164-.103-.243-.161");
}

.q0138eblq {
  fill: var(--svg-color--242500, #242500);
  d: path("M23.56 21.682c-.136-.039-.287.067-.415-.041q-.02-.078.061-.064q.149.014.299.021c.04.013.066.035.055.084");
}

.q0cepvskt {
  fill: var(--svg-color--430000, #430000);
  d: path("M26.846 24.26c-.008.038 0 .084-.058.092c-.077.014-.094-.045-.116-.097z");
}

.q0w7b5d3m {
  fill: var(--svg-color--4e0000, #4e0000);
  d: path("M30.12 30.498a.21.21 0 0 1-.201-.105l.206.039a.06.06 0 0 1-.005.066");
}

.q0wm-bbqp {
  fill: var(--svg-color--22421e, #22421e);
  d: path("m14.633 37.795l.001-.037q.09.035.12.13c-.07.008-.113-.02-.121-.093");
}

.q1c8hq8jd {
  fill: var(--svg-color--565700, #565700);
  d: path("M27.05 36.713c-.012-.076.05-.082.098-.102c.063-.033.106-.03.106.056a.33.33 0 0 1-.204.046");
}

.q1idjo50h {
  fill: var(--svg-color--493f43, #493f43);
  d: path("m16.382 33.584l.044-.063c.099.074.036.181.06.271q.038.053-.007.102a.45.45 0 0 1-.097-.31");
}

.q1l2necdr {
  fill: var(--svg-color--eaea64, #eaea64);
  d: path("M22.635 40.15c.037-.058.106-.026.154-.055c.077-.049.168-.003.248-.039c.045-.003.084.007.113.044c-.164.099-.344.024-.515.05");
}

.q252yih8i {
  fill: var(--svg-color--fdfd02, #fdfd02);
  d: path("M28.475 37.02q-.074-.003-.149-.002c-.091-.016-.176-.01-.253.05c-.185.082-.398.061-.577.161c-.116.037-.253.003-.358.09c-.061.012-.118.038-.181.033c-.036 0-.072.002-.106-.005c-.091-.028-.178-.031-.262.021a.5.5 0 0 1-.086.053c-.042.01-.083.031-.13.022c-.052-.016-.108-.013-.164-.015c-.089-.001-.179-.003-.26.046c-.053.025-.104.053-.163.057c-.046.001-.09.025-.138.013c-.084-.02-.166-.01-.25-.012c-.095.005-.195-.019-.282.043a1 1 0 0 1-.145.053c-.081.01-.16.005-.24.007c-.091-.014-.201.037-.26-.078c.012-.046.036-.075.087-.072l-.002-.002c.072-.047.158-.07.235-.106l-.007.002c.06-.058.145-.082.199-.149a.1.1 0 0 1 .046-.01c.084-.047.164-.101.247-.148l.021-.003c.052-.043.109-.076.16-.118c.058-.031.124-.041.185-.066a.6.6 0 0 0 .146-.064c.061-.031.128-.031.195-.031q.099.017.2.014c.099-.005.199.017.293-.033a1 1 0 0 1 .089-.047a.4.4 0 0 1 .163-.035c.073.01.147.016.22-.013a1 1 0 0 1 .099-.021c.069-.006.135-.025.202-.042a.4.4 0 0 1 .071-.012q.09-.005.177-.004c.097-.005.197.02.291-.028q.023-.025.047-.048a.15.15 0 0 1 .093-.037c.067.006.135.013.203.011c.073.002.146-.005.218.023c.015.007.041.019.044.013c.023-.037-.043-.008-.033-.041q0-.038.021-.068c.091-.093.206-.082.319-.076c.099.031.202.014.303.02q.03.01.054.03c.015.029.003.054-.012.079l.007.025c-.01.148-.171.197-.215.322c-.12.067-.208.195-.362.198");
}

.q261-1hxw {
  fill: var(--svg-color--565708, #565708);
  d: path("M13.3 27.739q-.05.11-.103.219c-.039-.105-.06-.204.103-.219");
}

.q3-gvac9l {
  fill: var(--svg-color--423511, #423511);
  d: path("m19.245 34.622l-.137-.017c-.038-.014-.049-.043-.053-.079q0-.033.014-.065c.02-.031.044-.053.082-.06c.128.032.089.137.094.221");
}

.q38picikp {
  fill: var(--svg-color--e7ec5d, #e7ec5d);
  d: path("m26.316 37.473l.064-.041l.09-.052c.048.04.124-.01.163.055c-.096.089-.209.041-.317.038");
}

.q3e9-2pzw {
  fill: var(--svg-color--392505, #392505);
  d: path("m31 25.891l-.109.003a.274.274 0 0 1-.158-.305c.034-.005.072-.058.106.002c.074.046.06.138.099.2z");
}

.q40mb_blg {
  fill: var(--svg-color--d4d49c, #d4d49c);
  d: path("m26.07 35.483l-.003-.043q.016-.036.046-.007l.012.05z");
}

.q56yht9gh {
  fill: var(--svg-color--0f1f01, #0f1f01);
  d: path("m13.3 33.08l-.091-.002c-.06-.255-.149-.503-.154-.768q.02-.034.039-.001c.151.235.077.531.206.771");
}

.q5bi8n_ha {
  fill: var(--svg-color--4c0100, #4c0100);
  d: path("m30.12 29.367l.002-.078c.068.036.187.004.191.135c-.077.021-.139-.006-.193-.057");
}

.q5fv3ctxb {
  fill: var(--svg-color--2e3100, #2e3100);
  d: path("m13.04 28.509l-.02-.002l-.018.002c.031-.14.011-.298.14-.401c-.019.136-.033.277-.102.401");
}

.q5kyaachb {
  fill: var(--svg-color--3e4100, #3e4100);
  d: path("M30.64 36.27c-.007.077.01.169-.104.188q-.06-.013-.072-.073c.029-.093.046-.199.186-.179q.019.036-.01.064");
}

.q6w7gq2gx {
  fill: var(--svg-color--737300, #737300);
  d: path("M15.68 32.402c-.064-.001-.135.021-.183-.049c.023-.111.094-.074.159-.049c.033.028.048.059.024.098");
}

.q7e7pxpnt {
  fill: var(--svg-color--676b0f, #676b0f);
  d: path("M22.717 40.715a.1.1 0 0 1 .021-.027a.5.5 0 0 1 .323.029q.016.028-.011.045l-.269-.004q-.03-.022-.064-.043");
}

.q8_s-3b4n {
  fill: var(--svg-color--ecf4fa, #ecf4fa);
  d: path("M22.584 27.705c.005.095-.045.145-.134.145c-.089.002-.138-.057-.135-.143c0-.076.045-.127.123-.131c.088-.003.146.033.146.129");
}

.q8sjonbkw {
  fill: var(--svg-color--3b380b, #3b380b);
  d: path("m31.647 34.2l-.091.002c-.054-.12-.031-.214.098-.268q.007.037.011.073z");
}

.q94aosxaf {
  fill: var(--svg-color--eded56, #eded56);
  d: path("m17.71 36.824l.106-.013c.061-.031.127-.017.19-.014q.037.028.016.066c-.105-.003-.217.04-.312-.039");
}

.q9h587j4v {
  fill: var(--svg-color--520000, #520000);
  d: path("M30.17 37.26a.54.54 0 0 1-.354.123c-.035-.027-.03-.067-.028-.104c.004-.075.046-.115.115-.131c.049-.006.102.053.151-.007c.085-.006.158.001.116.119");
}

.qa7eiq08f {
  fill: var(--svg-color--214021, #214021);
  d: path("m15.15 38.26l-.002.051c-.11-.036-.188-.099-.195-.222l.192.131z");
}

.qayy6ab2u {
  fill: var(--svg-color--ece945, #ece945);
  d: path("M15.252 36.36c.089.008.189-.043.262.049c-.102.065-.2.104-.262-.049");
}

.qcg7865uy {
  fill: var(--svg-color--f0f318, #f0f318);
  d: path("m18.12 21.643l-.104-.101l.327-.151l.283-.073c.056.018.123.007.169.059a.08.08 0 0 1-.01.069c-.104.033-.197.1-.314.092c-.063.033-.108.107-.193.101c-.052-.001-.103.051-.158.004");
}

.qcnd7gb2d {
  fill: var(--svg-color--fdfd01, #fdfd01);
  d: path("M32.02 31.02a.17.17 0 0 0-.1-.098c-.079.035-.122-.027-.175-.061a.5.5 0 0 0-.2-.096q-.032-.01-.06-.026a.8.8 0 0 0-.234-.12q-.032-.01-.062-.022c-.061-.028-.118-.06-.186-.067s-.137-.008-.2-.031c-.055-.021-.098-.058-.148-.084c-.068-.041-.147-.043-.224-.061a.5.5 0 0 1-.123-.055a.8.8 0 0 0-.221-.079a3 3 0 0 1-.258-.069a.16.16 0 0 1-.076-.06c-.064-.07-.145-.018-.217-.029c-.045.002-.089.01-.132.016a.2.2 0 0 1-.067-.001l-.166-.041c-.1-.031-.21-.01-.306-.062c-.056-.1-.145-.129-.253-.114c-.075 0-.151-.004-.226-.021c-.063-.02-.131-.031-.193-.062a.15.15 0 0 1-.058-.063a.9.9 0 0 1 .003-.516c.036-.056.089-.065.148-.063a.4.4 0 0 1 .113.039c.079.05.169.037.256.04c.093-.003.182.022.271.038c.175.006.349.012.517.073c.184.048.369.099.551.165c.109.053.198.168.345.111a.32.32 0 0 1 .2.057c.084.08.201.088.298.138c.092.032.174.087.272.102l.057.009c.049.063.147.061.184.141c.26.057.474.192.671.361c.111.104.194.441.135.567c-.028.066-.072.094-.136.044");
}

.qcrv5ab0p {
  fill: var(--svg-color--b30202, #b30202);
  d: path("m16.526 25.494l.063.008c-.025.077.028.173-.056.236c-.074-.078-.013-.162-.007-.244");
}

.qcyhf7h6n {
  fill: var(--svg-color--490401, #490401);
  d: path("M17.566 29.18q-.004-.026-.011-.051l-.006-.142q.055-.001.109-.007c.021.094.085.194-.048.259q-.02-.03-.044-.059");
}

.qd-g32b4d {
  fill: var(--svg-color--4a4a08, #4a4a08);
  d: path("M28.965 35.792c-.144.01-.221-.053-.217-.2z");
}

.qddsuob9s {
  fill: var(--svg-color--f0f21c, #f0f21c);
  d: path("M29.354 30.05c-.06.033-.051.09-.053.145c-.023.035-.055.039-.091.029a.1.1 0 0 1-.039-.054q0-.036.024-.064l.005-.11c.057.005.119-.007.154.054");
}

.qdk2w9gkc {
  fill: var(--svg-color--e7e118, #e7e118);
  d: path("M24.788 40.543c-.002-.051.01-.107-.055-.135l.005-.053c.079-.038.175-.023.253-.066c.076.007.141-.066.221-.035q.049.076-.01.145l-.056.059l-.257.067z");
}

.qe0iuezeo {
  fill: var(--svg-color--f3e797, #f3e797);
  d: path("M21.875 24.867q-.01-.054-.017-.106q.003-.098.009-.197l.054-.002l-.012.303z");
}

.qe63u6z3l {
  fill: var(--svg-color--27420d, #27420d);
  d: path("m14.649 34.629l-.221.095c-.038.019-.075.024-.111-.003a.1.1 0 0 1-.012-.079c.099-.122.209-.113.327-.033z");
}

.qeox7ubzh {
  fill: var(--svg-color--787800, #787800);
  d: path("M23.91 21.02q.051.031.039.091c-.099.015-.197.031-.248-.088c.07-.046.14-.042.209-.003");
}

.qf_dcn-rf {
  fill: var(--svg-color--66250d, #66250d);
  d: path("M30.28 32.2a.85.85 0 0 1 .36-.089c-.089.155-.208.189-.36.089");
}

.qfh5dvbpx {
  fill: var(--svg-color--f8f707, #f8f707);
  d: path("m17.258 23.03l-.103-.056c-.025-.101.053-.09.109-.102q.02-.003.039-.002a.16.16 0 0 1 .142-.091c.037-.093.118-.114.207-.121c.046.026.059.067.061.116q.027.015.02.033c-.007.018-.01.018-.015.018c-.02.05-.069.043-.106.057c-.046.075-.129.09-.202.116c-.047.032-.09.085-.152.032");
}

.qfpmy0_xt {
  fill: var(--svg-color--e9e85c, #e9e85c);
  d: path("M28.684 31.735a.1.1 0 0 0 0-.038l.151-.058c.065.007.151-.02.164.087c-.102.103-.207.101-.315.009");
}

.qg16sm3tm {
  fill: var(--svg-color--e3e413, #e3e413);
  d: path("m14.729 25.434l-.104-.006c-.017-.034-.031-.07-.021-.109c.02-.055.063-.079.115-.092c.072-.014.146-.018.22-.027q.037.001.073.014c.056.067.205.039.182.184c-.039.035-.089.043-.14.05c-.061.005-.121-.015-.183-.013z");
}

.qgajtfbba {
  fill: var(--svg-color--848404, #848404);
  d: path("m12.848 32.556l.051-.105c.051.063.046.135.041.207c-.086.016-.099-.033-.092-.102");
}

.qgcrkxbpd {
  fill: var(--svg-color--ced111, #ced111);
  d: path("m19.06 34.627l-.181-.07a.06.06 0 0 1 .007-.05a.14.14 0 0 1 .044-.03l.053-.008q.028 0 .053.01a.1.1 0 0 1 .043.028l.029.099a.3.3 0 0 0-.048.021");
}

.qgya2iyuf {
  fill: var(--svg-color--021b01, #021b01);
  d: path("m22 20.57l.017.084c-.039.063-.102.063-.164.067a.24.24 0 0 1-.141-.036a.1.1 0 0 1-.022-.1l.022-.028q.145.008.288.013");
}

.qhe-m8bkd {
  fill: var(--svg-color--4b4807, #4b4807);
  d: path("M32.16 29.899q-.04.048-.079.101l-.005-.214c.035-.089.009-.181.015-.273a.05.05 0 0 1 .055-.029c.034.137.028.276.014.415");
}

.qhkiucigd {
  fill: var(--svg-color--747300, #747300);
  d: path("m28.573 32.396l-.099.001l-.051-.048l.061-.047c.045-.033.094-.021.142-.016q.022.018.02.04q-.001.024-.008.022z");
}

.qhvbtqgvd {
  fill: var(--svg-color--631608, #631608);
  d: path("m17.504 35.13l.155-.024l.041.124c-.072-.018-.178.027-.196-.1");
}

.qicm6mbsy {
  fill: var(--svg-color--f4f24e, #f4f24e);
  d: path("M22.932 26.19a.1.1 0 0 0-.037.016c-.581.025-1.161.048-1.739-.012a.1.1 0 0 1-.007-.031c.2-.154.434-.061.651-.087q.234.003.468 0c.212.021.433-.038.64.05q.057.015.024.064");
}

.qiym7ob0x {
  fill: var(--svg-color--4e500c, #4e500c);
  d: path("M14.13 28.26c-.101-.058-.267-.034-.262-.217c.128.021.209.101.262.217");
}

.qj27q9bse {
  fill: var(--svg-color--ad1c1b, #ad1c1b);
  d: path("m27.81 32.354l.046-.099c.005.104.024.212-.04.309z");
}

.qjxp2yfxx {
  fill: var(--svg-color--f2f20a, #f2f20a);
  d: path("M28.703 35.28q.203.157.401.314c.028.126.245.177.145.354h.002c-.023.024-.033.059-.069.07a.1.1 0 0 1-.065-.014c-.077-.051-.137-.119-.202-.182c-.063-.063-.122-.129-.197-.178a1 1 0 0 1-.107-.082c-.048-.05-.099-.098-.095-.175a.14.14 0 0 1 .059-.08c.038-.026.084-.028.128-.026");
}

.qjzlnobxw {
  fill: var(--svg-color--f1f104, #f1f104);
  d: path("m26.479 25.952l.001-.108q-.02-.016-.016-.037q0-.022.005-.021c.036-.047.089-.066.138-.091l.07-.005l.109.055c.059.021.113.049.135.116a.15.15 0 0 1-.021.112a.2.2 0 0 1-.097.072c-.11.021-.222.043-.315-.048a.1.1 0 0 1-.009-.045");
}

.qkht-5bnh {
  fill: var(--svg-color--ab2729, #ab2729);
  d: path("M23.394 35.17c.012-.053.062-.06.099-.079c.033-.002.063 0 .064.043c-.025.142-.104.049-.163.036");
}

.qkvwnsbjr {
  fill: var(--svg-color--56570a, #56570a);
  d: path("M30.367 26.715h-.037c-.053-.043-.099-.087-.055-.16c.071.031.074.099.092.16");
}

.qls_mmpyj {
  fill: var(--svg-color--8d1914, #8d1914);
  d: path("M17.905 34.87q-.001-.018.005-.033l.058-.163l.051-.011c-.007.198.144.255.289.313a.12.12 0 0 1-.047.072c-.072.041-.142.022-.207-.019z");
}

.qm7j98w0n {
  fill: var(--svg-color--090700, #090700);
  d: path("M18.687 34.619a.1.1 0 0 0-.047.013l.028-.071h.01q.025.012.02.029q-.004.02-.011.019v.011");
}

.qm8_ccckk {
  fill: var(--svg-color--67250c, #67250c);
  d: path("m26.846 21.878l-.005.062l-.157-.09l.001-.056c.069-.002.144-.015.161.084");
}

.qny86ir5k {
  fill: var(--svg-color--3e3f07, #3e3f07);
  d: path("m24.898 34.512l.041.008c.029.009.059.016.072.05q.003.03-.015.058a.05.05 0 0 1-.055-.014l-.061-.054a.3.3 0 0 1 .018-.048");
}

.qonjywbra {
  fill: var(--svg-color--fafb1e, #fafb1e);
  d: path("M18.479 34.834q.028-.006.055-.014l.015.023l-.002.026l-.021.02a.05.05 0 0 1-.047-.021a.04.04 0 0 0 0-.034");
}

.qqvngyzey {
  fill: var(--svg-color--4e4f40, #4e4f40);
  d: path("M27.635 34.454a.05.05 0 0 0-.036-.01c-.065-.134-.022-.229.102-.296c.021.11-.059.199-.063.304z");
}

.qqzum9b0a {
  fill: var(--svg-color--3a3b2a, #3a3b2a);
  d: path("M25.662 36.927c-.051.075-.142.006-.198.059q-.025-.015-.019-.031q.007-.017.017-.018a.36.36 0 0 1 .209-.166q.027-.032.054 0c.019.069-.025.111-.063.156");
}

.qra2yubpk {
  fill: var(--svg-color--1c1e04, #1c1e04);
  d: path("m13.1 33.484l.042.002c-.006.088.083.157.058.251a.29.29 0 0 1-.1-.253");
}

.qrbfaisod {
  fill: var(--svg-color--1f1a01, #1f1a01);
  d: path("M16.522 30.614c.042.064-.057.202.104.204c.124 0 .265.036.31-.139q.107.06.23.062c.063.021.133.027.149.11a.1.1 0 0 1-.058.057c-.255.01-.508.038-.76-.015q-.042-.032-.02-.079c.014-.067-.03-.147.045-.2");
}

.qrgcnbb0s {
  fill: var(--svg-color--314021, #314021);
  d: path("m13.199 28.767l-.012-.067a.9.9 0 0 1 .104-.402a.16.16 0 0 1 .06.074q.043.136.012.273c-.019.081-.041.172-.164.122");
}

.qrthxee9n {
  fill: var(--svg-color--27420f, #27420f);
  d: path("M13.201 35.886a.19.19 0 0 1 .106.159c-.115 0-.108-.08-.106-.159");
}

.qsf8wnbce {
  fill: var(--svg-color--fdfd01, #fdfd01);
  d: path("M30.738 31.04c.05-.027.123.004.158-.063c.049.039.133.025.157.102l-.013.045c-.091.07-.188.104-.303.059z");
}

.qsgvg2hub {
  fill: var(--svg-color--162d05, #162d05);
  d: path("M18.842 40.51q.048-.02.098-.037c.087-.059.152-.023.209.049l-.055.043c-.086-.012-.183.029-.252-.055");
}

.qtpk3tbyc {
  fill: var(--svg-color--f3f162, #f3f162);
  d: path("M25.19 37.63c-.125.112-.271.044-.409.05c.053-.125.174-.03.251-.079a.2.2 0 0 1 .158.029");
}

.qvdzaybqb {
  fill: var(--svg-color--384308, #384308);
  d: path("M14.529 29.17c-.002-.141.208-.047.205-.188l.108.034c.038-.02.074-.028.103.017q.001.02-.004.039l-.059.051c-.062.057-.146.005-.213.048z");
}

.qw10oinbt {
  fill: var(--svg-color--545301, #545301);
  d: path("M28.22 35.24c-.13-.021-.199-.101-.228-.224q.062.026.124.056l.108.132q.017.015.01.025q-.006.01-.014.011");
}

.qwkaofjqh {
  fill: var(--svg-color--19410d, #19410d);
  d: path("M13.811 36.778c.107.069.166.175.222.283c-.181-.01-.167-.174-.222-.283");
}

.qwohugcks {
  fill: var(--svg-color--2d2a00, #2d2a00);
  d: path("m13.558 36.1l-.214.198c-.069-.077-.033-.171-.039-.258c.067.092.171.029.253.06");
}

.qx-8cdbku {
  fill: var(--svg-color--76200a, #76200a);
  d: path("m25.727 21.424l-.115.005c-.077.017-.151.017-.217-.034a.15.15 0 0 1-.028-.108a.12.12 0 0 1 .04-.064c.099.078.306-.016.32.201");
}

.qxswdvbrz {
  fill: var(--svg-color--f0f047, #f0f047);
  d: path("M22.438 25.07c.039.001.075-.002.089-.045q.103.025.205.053q.008.019.005.041c-.096.058-.197.026-.299.021q-.04-.034 0-.07");
}

.qz9_3tx-o {
  fill: var(--svg-color--e8ee6b, #e8ee6b);
  d: path("M17.764 37.592c.112.019.242-.063.337.058c-.114-.018-.234.006-.337-.058");
}

.r_jee-j5u {
  fill: var(--svg-color--791f11, #791f11);
  d: path("M28.733 31.426c.114-.057.231-.111.368-.087c.029.017.063.026.065.069a.1.1 0 0 1-.038.056c-.074.033-.154.034-.231.046q-.052.002-.104-.006c-.032-.016-.055-.04-.06-.078");
}

.r_r5msb8p {
  fill: var(--svg-color--d6d697, #d6d697);
  d: path("M25.712 35.03q.001.024-.005.048q-.022-.004-.046-.003l.001-.05a.07.07 0 0 1 .05.005");
}

.r-mld_woi {
  fill: var(--svg-color--68680c, #68680c);
  d: path("M18.675 40.19c-.092-.02-.186-.03-.26-.097c.115-.04.215-.049.26.097");
}

.r0mwcbb5z {
  fill: var(--svg-color--b4b117, #b4b117);
  d: path("M19.454 35.07c.001-.072.07-.098.1-.15q.134-.065.204.068c-.005.098-.079.143-.151.188c-.092.022-.109-.062-.153-.106");
}

.r0q4ehbvp {
  fill: var(--svg-color--eef063, #eef063);
  d: path("m23.09 21.542l-.452-.046l.012-.008c.167.013.344-.051.506.041q-.027.041-.066.013");
}

.r1j2q6beh {
  fill: var(--svg-color--e8e656, #e8e656);
  d: path("M17.04 29.534h-.533c.142-.087.217-.179.347-.113c.101.053.124-.05.18-.089c.062.066.055.133.006.202");
}

.r24uaybjl {
  fill: var(--svg-color--631e08, #631e08);
  d: path("M25.559 40.35c-.085.115-.21.115-.335.11a.06.06 0 0 1-.069.008c-.029-.039-.008-.069.02-.095c.084-.055.181-.078.274-.105a.14.14 0 0 1 .107.018q.02.021.013.041q-.005.023-.01.023");
}

.r3ccu7baf {
  fill: var(--svg-color--646506, #646506);
  d: path("m31.867 32.25l-.054.207c-.079-.094-.091-.171.054-.207");
}

.r3nbu3iax {
  fill: var(--svg-color--595a07, #595a07);
  d: path("m26.53 22.713l-.195-.017c-.031-.026-.04-.055-.007-.086l-.002.005c.099-.032.176-.019.204.098");
}

.r3yl35uli {
  fill: var(--svg-color--2d2200, #2d2200);
  d: path("m27.656 37.4l.003.071l-.256.016q-.029-.004-.056-.012a.1.1 0 0 1 .011-.037c.074-.069.176 0 .254-.05z");
}

.r40jhmihb {
  fill: var(--svg-color--72140b, #72140b);
  d: path("M29.821 30.357c-.125.082-.207.068-.222-.097l.056-.005c.028.08.137.027.166.102");
}

.r4b7px2gt {
  fill: var(--svg-color--373636, #373636);
  d: path("m16.18 24.06l.008.095a.2.2 0 0 1 .038.118c-.002.783.021 1.565-.012 2.348q-.022.052-.079.041l-.007-2.476c0-.048-.015-.105.052-.126");
}

.r4bei3qlz {
  fill: var(--svg-color--f3f30c, #f3f30c);
  d: path("M32.22 31.21c-.012.044.051.1-.007.135c-.065.041-.082-.064-.14-.062a.1.1 0 0 1-.097.026a.34.34 0 0 1-.14-.106c-.028-.038-.05-.079-.046-.13c.018-.069.051-.13.118-.166c.064-.012.104.026.142.069a.4.4 0 0 0 .104.106q.038.028.063.064q.008.03.004.059z");
}

.r4i-15gws {
  fill: var(--svg-color--5f0204, #5f0204);
  d: path("M20.379 37.495a.26.26 0 0 1 .207.085c-.016.027-.036.03-.063.018l-.147-.025c-.024-.027-.028-.053.003-.078");
}

.r4lqpzzyi {
  fill: var(--svg-color--0d2201, #0d2201);
  d: path("M17 38.36c-.187-.011-.29-.154-.418-.26c.019-.042.044-.072.096-.046c.075.137.256.162.322.306");
}

.r5f3l8b4w {
  fill: var(--svg-color--1b1b00, #1b1b00);
  d: path("m25.301 34.723l-.086-.019q-.015.005-.029.012q-.015-.032.015-.053l.005-.005l.021-.014l.015.019z");
}

.r5p5_ybxq {
  fill: var(--svg-color--eae96e, #eae96e);
  d: path("M18.521 37.695c.14.028.311-.092.419.089l-.023.007h-.024c-.105-.086-.23-.043-.346-.056z");
}

.r5xrwtbhd {
  fill: var(--svg-color--dbdd50, #dbdd50);
  d: path("m14.945 29.03l-.103-.017l.104-.096q.025-.016.05-.027c-.012.048.077.133-.051.14");
}

.r6_hhzi1e {
  fill: var(--svg-color--797c00, #797c00);
  d: path("M16.274 36.511c.074.011.185-.048.189.097c-.023.038-.053.031-.084.01c-.045-.025-.109-.034-.105-.107");
}

.r6k_kqb9c {
  fill: var(--svg-color--f4f15b, #f4f15b);
  d: path("m18.17 25.28l-1.689-.009a.1.1 0 0 1 0-.034l1.179-.018l.47.001l.055.012q.012.03-.015.048");
}

.r6n1_r_1m {
  fill: var(--svg-color--54530e, #54530e);
  d: path("m25.765 40.04l-.057-.046c.064-.061.144-.065.226-.054c-.035.071-.096.097-.169.1");
}

.r7l2f5bmt {
  fill: var(--svg-color--5c4037, #5c4037);
  d: path("m27.556 26.16l.051-.048c.076.084.094.153-.044.183a.2.2 0 0 1-.007-.049a.06.06 0 0 1-.026-.043a.06.06 0 0 1 .026-.043");
}

.r8_r26b4e {
  fill: var(--svg-color--34341f, #34341f);
  d: path("M13.61 36.511c-.041.003-.082.008-.105.051c-.065-.034-.048-.101-.061-.154c.021-.053.068-.052.113-.055q.028.078.053.158");
}

.r89xtz-ui {
  fill: var(--svg-color--fdfd02, #fdfd02);
  d: path("M14.318 31.48c.076.008.161-.018.217.061c.069.071.16.038.242.047c.051-.007.104.024.154.001c.14-.028.238.091.366.101c.066-.004.13.01.194.023c.039-.009.072-.05.12-.035c.069.036.089.118.152.159q.05.002.103.002c.046.071.005.157.043.231c-.03.119.065.285-.13.341a.1.1 0 0 1-.064.013c-.041-.02-.07-.054-.108-.078c-.077-.04-.159-.021-.24-.023c-.161.018-.311-.053-.47-.046c-.104-.007-.212-.002-.298-.076c-.044-.113-.143-.09-.231-.087q-.073.003-.145.002a1 1 0 0 1-.187-.023c-.036-.01-.068-.024-.104-.039a.8.8 0 0 0-.376-.092a1 1 0 0 1-.178-.021a1.3 1.3 0 0 0-.265-.081a.185.185 0 0 1-.12-.177c-.005-.091.007-.184-.026-.27c.014-.086-.042-.187.053-.257c.092-.024.166.049.253.049c.101.058.204.099.322.077a.7.7 0 0 0 .433.104c.085.068.201.044.29.094");
}

.r8eqyoy_r {
  fill: var(--svg-color--f9fa00, #f9fa00);
  d: path("M24.851 21.12q.015.01.032.007c.076.041.196-.033.243.089a.13.13 0 0 1-.01.115c-.108.095-.218.021-.328 0a.2.2 0 0 1-.062-.045c-.02-.067.006-.121.053-.169a.1.1 0 0 1 .072.003");
}

.r9304nx3q {
  fill: var(--svg-color--454706, #454706);
  d: path("M18.18 22.359q.016.01.003.026c-.07.038-.113.121-.207.12c-.015-.162.12-.119.204-.146");
}

.r9lc-qbjt {
  fill: var(--svg-color--737417, #737417);
  d: path("M12.89 29.28c-.006.089.021.185-.047.262c-.041-.021-.019-.074-.045-.102c-.008-.076-.027-.158.092-.16");
}

.raw1rvb5y {
  fill: var(--svg-color--5a180c, #5a180c);
  d: path("M30.32 27.14c-.137-.028-.096-.133-.096-.22c.063.061.066.145.096.22");
}

.rb7tty0ry {
  fill: var(--svg-color--490000, #490000);
  d: path("m29.3 29.16l.002-.077c.067.024.15.011.195.086a1 1 0 0 0-.092.038c-.053.022-.066-.043-.105-.047");
}

.rcaycihbe {
  fill: var(--svg-color--565518, #565518);
  d: path("M19.09 37.3c-.089-.002-.164-.028-.198-.122c.089-.043.15 0 .208.064q.027.033-.01.058");
}

.rcc-78b7n {
  fill: var(--svg-color--7c7c00, #7c7c00);
  d: path("M20.18 21.639c.054.009.123-.027.157.05a.2.2 0 0 0-.018.046c-.017.051-.041.084-.099.05c.006-.05-.02-.083-.06-.105z");
}

.rcvfodzze {
  fill: var(--svg-color--5c5b0e, #5c5b0e);
  d: path("m17.08 22.262l-.129.091c-.015-.116.026-.15.129-.091");
}

.rd2sopq7t {
  fill: var(--svg-color--1d330a, #1d330a);
  d: path("M13.357 25.338c.01.135-.014.26-.122.356c.058-.133-.149-.308.065-.416q.029-.027.062-.005a.055.055 0 0 1-.005.065");
}

.rd6pw3b6f {
  fill: var(--svg-color--231005, #231005);
  d: path("m22.979 40.911l.11.053l-.199.018c-.095.05-.2.046-.304.05q0-.058-.002-.115c.133-.085.265-.093.395-.006");
}

.rdeo07b2x {
  fill: var(--svg-color--3f4101, #3f4101);
  d: path("m31.05 31.535l.042.003a.3.3 0 0 1 .001.298l-.039.018l-.05-.109c-.046-.085-.018-.151.046-.21");
}

.re74qj_vt {
  fill: var(--svg-color--1c3c56, #1c3c56);
  d: path("M19.656 30.32a.25.25 0 0 0-.201-.08c.094-.041.19-.086.201.08");
}

.re82c-bpw {
  fill: var(--svg-color--262c00, #262c00);
  d: path("m13.238 26.762l-.296.063l-.054-.058a.12.12 0 0 1 .063-.082c.052-.018.098-.014.139.021c.049.023.121-.02.148.056");
}

.rfcm5jybp {
  fill: var(--svg-color--383131, #383131);
  d: path("M23 35.34q-.041-.011-.082-.019c.092-.058.195-.075.301-.094a.23.23 0 0 1-.219.113");
}

.rfion-bdh {
  fill: var(--svg-color--1f0c04, #1f0c04);
  d: path("M18.13 25.894q-.005-.128-.012-.253l.043-.037q.007.146.017.29z");
}

.rfl3o5g1b {
  fill: var(--svg-color--292100, #292100);
  d: path("m16.837 24.623l.003-.058l.103-.005l.108.016q.01.038-.017.064c-.07.04-.143.112-.197-.017");
}

.rg4yb7bup {
  fill: var(--svg-color--fbfc01, #fbfc01);
  d: path("M15.464 24.46c.104.002.211.02.303-.051a.1.1 0 0 0 .048-.01c.084.054.064.113.007.173c-.043.041-.098.022-.146.031l-.014.008c-.083.063-.149.02-.215-.035q-.026-.039.007-.072a.2.2 0 0 1 .01-.044");
}

.rgv9wbcbb {
  fill: var(--svg-color--7f1a1a, #7f1a1a);
  d: path("M17.09 24.16h-.811a.13.13 0 0 1-.061.024a.1.1 0 0 1-.06-.029c-.011-.033-.016-.065.016-.09c.307-.006.614-.014.922-.014c3.503-.002 7.01-.002 10.512.005c.082 0 .232-.094.248.099q-.02.036-.049.005q-.38 0-.76-.003a.87.87 0 0 1-.723 0l-3.993.007a.4.4 0 0 1-.221.061c-.138-.007-.28.028-.404-.065h-3.992c-.108.1-.265.027-.378.106a.2.2 0 0 1-.071.015c-.077-.015-.125-.069-.175-.121");
}

.riabt9bnk {
  fill: var(--svg-color--5d5f0d, #5d5f0d);
  d: path("m27.25 36.14l-.075.003c-.045-.021-.107-.007-.134-.063l.009-.03c.089-.021.184-.054.2.09");
}

.riop4yz2m {
  fill: var(--svg-color--a20504, #a20504);
  d: path("M17.09 24.16c.087-.01.137.036.163.114c-.026.07-.115.104-.11.193q-.015.051-.034.102a.2.2 0 0 1-.066.033a.12.12 0 0 1-.1-.039c.081-.122.019-.297.147-.403");
}

.rj3m_wd9x {
  fill: var(--svg-color--fdfd01, #fdfd01);
  d: path("m13.611 34.971l-.172.061c-.057.059-.139.086-.192.147l.005-.005q-.042.042-.099.025a.3.3 0 0 1-.108-.18q-.005-.03-.007-.059c-.064-.028-.075-.09-.096-.146l-.053-.154c-.056-.06-.063-.142-.102-.209l-.059-.214c-.098-.07-.045-.198-.107-.282c-.046-.065-.064-.145-.09-.22v-.096c-.084-.089-.086-.202-.103-.313l-.003-.106c-.079-.066-.066-.167-.101-.25q-.003-.054-.002-.108a.1.1 0 0 1-.02-.063c.01-.081.01-.16-.044-.229l-.028-.061c-.02-.064.01-.129-.005-.193q-.004-.06-.005-.121c-.069-.105-.058-.23-.092-.344c-.029-.089.02-.181-.01-.27v.005c-.036-.039-.024-.089-.024-.135a.37.37 0 0 0-.007-.276a.2.2 0 0 1 .004-.072c.02-.049.063-.072.11-.087a.9.9 0 0 0 .296-.135a.2.2 0 0 1 .08-.013c.149.016.168.126.174.244c.006.122-.013.247.03.367c.039.169-.004.348.065.513c.014.063.034.123.029.188c-.029.118.021.231.028.347c.003.059.048.102.07.152c.047.135.086.273.098.418c-.025.128.034.243.065.363a.7.7 0 0 0 .087.245a.4.4 0 0 1 .05.123c.008.097.058.179.097.265c.017.094.036.186.11.255c.065.11.13.22.156.349c.01.094.051.19-.026.274");
}

.rj6gvpbdx {
  fill: var(--svg-color--767600, #767600);
  d: path("M17.654 36.726c.059-.013.114-.015.16.033q.032.032.006.069c-.038.016-.074.02-.11-.004l-.105-.053a.08.08 0 0 1 .049-.045");
}

.rjtjr_bar {
  fill: var(--svg-color--282c00, #282c00);
  d: path("M17.409 30.463c.029 0 .049.012.042.045q-.048.002-.042-.045");
}

.rk258fphd {
  fill: var(--svg-color--eff6fc, #eff6fc);
  d: path("M22.602 33.864c-.012.082-.049.142-.145.136c-.091-.003-.135-.059-.133-.147c.001-.081.057-.12.13-.125q.136-.006.148.136");
}

.rkchkobai {
  fill: var(--svg-color--a42829, #a42829);
  d: path("M23.663 35.02c.026-.038.06-.054.105-.039c-.012.068-.003.152-.115.142q-.037-.057.01-.103");
}

.rmcvilp0x {
  fill: var(--svg-color--4b2509, #4b2509);
  d: path("m17.09 29.27l.075.014c.041.052.041.11.019.169c-.058.09-.113-.01-.171 0c-.091.031-.183-.017-.283.014c.105.013.202.013.298.016a.12.12 0 0 1 .082.061a.07.07 0 0 1-.019.064a.2.2 0 0 1-.092.05a.2.2 0 0 1-.065 0a1.2 1.2 0 0 0-.226-.019a.3.3 0 0 1-.065-.008l-.058-.029c-.145-.038-.108-.155-.099-.249c.012-.113.111-.073.181-.077c.108-.006.219-.003.327-.003q.048-.044.096-.003");
}

.rploq3lcx {
  fill: var(--svg-color--0a0808, #0a0808);
  d: path("M16.02 32.859q-.023.053-.051.11c-.089-.082-.075-.178-.039-.277q.022-.043.07-.031q.012.098.02.198");
}

.rpwj8ib3x {
  fill: var(--svg-color--f5f44f, #f5f44f);
  d: path("M21.767 23.733V20.67a.05.05 0 0 1 .048.002l.007 3.063z");
}

.rqd8icbar {
  fill: var(--svg-color--e4e515, #e4e515);
  d: path("M15.634 37.589a1 1 0 0 0-.332-.334c-.017-.077-.096-.143-.051-.233l-.004.004c.081-.076.161-.037.24 0a.3.3 0 0 1 .086.065a.4.4 0 0 1 .07.118c.056.084.149.13.21.207c.055.069.132.135.066.237c-.119.085-.187-.055-.285-.064");
}

.rqpma_9_g {
  fill: var(--svg-color--f4f833, #f4f833);
  d: path("m22.17 25.11l-.251.002q-.024-.018-.014-.033q.007-.015.017-.016c.082.018.176-.026.248.047");
}

.rr3wt9brq {
  fill: var(--svg-color--74220b, #74220b);
  d: path("M24.07 20.916c.148-.084.284-.061.408.051c.001.051-.014.096-.06.123a.14.14 0 0 1-.072 0c-.084-.068-.248-.01-.279-.169z");
}

.rsxcak-ev {
  fill: var(--svg-color--e3df0d, #e3df0d);
  d: path("m30.02 24.707l.109.051l.051.049c-.018.089-.149.064-.159.161a.07.07 0 0 1-.058.017a.18.18 0 0 1-.072-.105a.08.08 0 0 1 .015-.059c.071-.007.11-.042.114-.114");
}

.rt_srpwtm {
  fill: var(--svg-color--cac98a, #cac98a);
  d: path("m18.993 34.456l.055.011a.1.1 0 0 0 0 .041q-.029-.003-.056-.008a.1.1 0 0 0 .001-.044");
}

.ruibl3lkx {
  fill: var(--svg-color--272b00, #272b00);
  d: path("M28.23 31.793c.134-.127.298-.101.459-.096q.026.04-.012.069c-.147.041-.287.229-.448.022z");
}

.ruqcs6fch {
  fill: var(--svg-color--be0e0b, #be0e0b);
  d: path("M26.325 24.15h.723c0 .067.004.135 0 .2c-.005.108.024.153.146.118a.5.5 0 0 1 .272-.004c.127.039.114.104-.008.146c-.111.021-.226-.001-.337.026a.2.2 0 0 1-.069-.002c-.068-.021-.128-.056-.143-.135a.2.2 0 0 1 .005-.068c.005-.043.01-.086-.036-.112l-.056-.017c-.047-.011-.093-.025-.142-.016l-.056.012a.3.3 0 0 0-.105.027c-.036.041-.029.092-.036.14a.3.3 0 0 1-.02.067a.15.15 0 0 1-.05.055a.3.3 0 0 1-.111.032c-.079.007-.16.005-.24.005a.4.4 0 0 1-.236-.057c.016-.191.166-.107.251-.107c.312.003.328-.011.248-.31");
}

.rva-fgb7b {
  fill: var(--svg-color--4c4a08, #4c4a08);
  d: path("M30.689 27.379c-.021 0-.04.004-.06.004c-.053-.077-.099-.16-.092-.26q.015 0 .029-.002q.06.13.123.258");
}

.rvc8tjdsp {
  fill: var(--svg-color--592404, #592404);
  d: path("M27.298 38.26c-.031.059-.094.049-.146.059c.026-.142.12-.2.257-.207z");
}

.rwj-y7b0z {
  fill: var(--svg-color--66220e, #66220e);
  d: path("M29.874 32.3c.104-.063.222-.072.338-.092c-.068.193-.197.174-.338.092");
}

.rwoq_4bmg {
  fill: var(--svg-color--551407, #551407);
  d: path("m25.15 21.21l.059-.046c.069.01.146-.007.201.053l-.01.081q-.163.064-.25-.088");
}

.rwq0jdbmj {
  fill: var(--svg-color--f8f637, #f8f637);
  d: path("m17.15 25.12l.005-.05h.344c-.1.129-.229.045-.349.05");
}

.rwrpwmicm {
  fill: var(--svg-color--371b0a, #371b0a);
  d: path("m30.988 30.867l.01-.104l.19.017q.02.061-.041.084l-.007.007c-.051.087-.104.123-.152-.004");
}

.rwwzjtt0m {
  fill: var(--svg-color--777400, #777400);
  d: path("M18.07 35.28a.2.2 0 0 0 .052 0l.001.055l-.053-.004a.2.2 0 0 0 0-.051");
}

.rxhktixel {
  fill: var(--svg-color--f2f205, #f2f205);
  d: path("M13.758 26.936c.033.049-.104.104.005.151l-.008.053a1 1 0 0 0-.125.224c-.023.063-.034.126-.074.181l-.001.101c-.028.093-.081.179-.096.275q-.022.084-.053.163c-.038.077-.043.161-.069.241c-.053.13-.07.269-.097.403c-.082.174-.067.364-.097.547c-.063.14-.023.363-.281.339q-.04-.02-.041-.064c.032-.088-.007-.193.068-.27v-.09c.004-.078-.011-.16.053-.224l-.001-.034c-.002-.146.042-.28.082-.416c.034-.139.058-.278.12-.408q.028-.074.054-.149c.004-.085.023-.166.103-.219c0-.06-.004-.12.056-.159a.8.8 0 0 1 .072-.303c.012-.099.084-.168.113-.256c.067-.041.11-.146.217-.086");
}

.rxw9_8hpv {
  fill: var(--svg-color--14350c, #14350c);
  d: path("M11.759 31.17c-.008-.207.042-.414-.082-.612c-.053-.081-.031-.201.086-.257l.027.019a.7.7 0 0 1 .117.167c.046.144-.003.301.069.44c.027.069.01.135-.01.202a.4.4 0 0 1-.031.06c-.031.036-.067.059-.117.055c-.033-.017-.054-.038-.059-.074");
}

.rybtm8bsh {
  fill: var(--svg-color--2e300e, #2e300e);
  d: path("M12.838 30.802c-.14.074-.098.207-.103.323q-.024.026-.041-.003c-.015-.095.028-.235-.154-.205c.049-.127.168-.12.271-.142q.03-.006.027.027");
}

.rykw3l1bp {
  fill: var(--svg-color--f7f40a, #f7f40a);
  d: path("m27.14 39.58l-.073.01c-.06.052-.108.119-.189.145c-.077.02-.145.063-.214.098a.7.7 0 0 1-.22.09c-.048.031-.089.075-.153.072c-.059.003-.12.004-.164-.047a.1.1 0 0 1-.009-.065c.045-.074.122-.102.191-.14q.102-.05.205-.104a.7.7 0 0 0 .168-.105c.116-.084.22-.192.376-.2q.06 0 .107.039a.16.16 0 0 1 .034.112c-.005.04-.019.075-.059.095");
}

.ryowhqbav {
  fill: var(--svg-color--f1f357, #f1f357);
  d: path("m17.708 37.43l.101-.045l.056.098c-.086-.01-.183.039-.253-.05z");
}

.ryuc65bvv {
  fill: var(--svg-color--1e3304, #1e3304);
  d: path("m18.942 22.259l.002.048c-.081.145-.217.094-.337.097l.084-.097c.09.023.167-.029.251-.048");
}

.rzpk7mbmp {
  fill: var(--svg-color--1d1609, #1d1609);
  d: path("m21.661 24.652l-.371.01c.075-.207.246-.067.371-.104z");
}

.s_1k18r8m {
  fill: var(--svg-color--dfde08, #dfde08);
  d: path("m18.637 35.03l-.105-.004a.08.08 0 0 1-.026-.059a.1.1 0 0 1 .031-.056a.13.13 0 0 1 .064-.017a.1.1 0 0 1 .055.038a.09.09 0 0 1-.017.093z");
}

.s_dc0bclp {
  fill: var(--svg-color--514f0b, #514f0b);
  d: path("M19.664 21.13c.058-.008.123.009.168-.049c.048.015.115-.031.146.045q.023.032-.021.041l-.299.014q.005-.027.006-.051");
}

.s-a32r5dy {
  fill: var(--svg-color--636200, #636200);
  d: path("M17.358 30.46c-.076.041-.098.157-.211.146a.1.1 0 0 0-.01-.045l.064-.148c.057.001.12-.02.157.047");
}

.s-octnb_w {
  fill: var(--svg-color--1d1500, #1d1500);
  d: path("M25.775 35.23h-.063a.1.1 0 0 0 .01-.049a.07.07 0 0 1 .051-.029a.13.13 0 0 1 .056.024a.1.1 0 0 1-.003.061q-.03.023-.051-.007");
}

.s04vw6bcv {
  fill: var(--svg-color--8b8e00, #8b8e00);
  d: path("m27.854 36.612l-.145-.005l-.103-.049l.158-.057c.055-.018.076.02.099.057z");
}

.s05smxbog {
  fill: var(--svg-color--d8d70e, #d8d70e);
  d: path("M22.17 25.586c.026.055.046.107-.051.101c.003-.041.012-.08.051-.101");
}

.s0kwctb2p {
  fill: var(--svg-color--26300b, #26300b);
  d: path("m12.742 26.772l-.117.306c-.234-.115-.186-.261-.047-.419l.034-.001c.065.014.15.004.13.114");
}

.s1lwflb-h {
  fill: var(--svg-color--b4ae43, #b4ae43);
  d: path("m18.514 36.2l.018-.047l.05.007q-.02.046-.068.04");
}

.s21rlgd8t {
  fill: var(--svg-color--f0f154, #f0f154);
  d: path("M20.944 40.09c.151.035.313-.018.457.055c-.171-.014-.349.051-.513-.043q.025-.03.056-.012");
}

.s26_2ibeu {
  fill: var(--svg-color--282a00, #282a00);
  d: path("M24.02 40.517q.079-.027.151-.055l.086.055c-.05.058-.122.034-.183.051z");
}

.s2lpufb4h {
  fill: var(--svg-color--d0d20d, #d0d20d);
  d: path("m17.431 35.07l.167-.115c.051.006.094.023.115.074l-.054.081c-.043.065-.098.054-.155.024z");
}

.s2t1cgvyy {
  fill: var(--svg-color--58560c, #58560c);
  d: path("M17.669 24.7c.138.114.299.061.45.063q.023.017.017.035c-.006.018-.009.018-.014.018l-.003.002l-.327-.004c-.077 0-.132-.022-.123-.114");
}

.s2wl_sn_x {
  fill: var(--svg-color--f2f356, #f2f356);
  d: path("m26.02 25.07l-.009.059l-.024.005l-.024-.005l.006-.253a.07.07 0 0 1 .048.001c.057.062.042.129.003.193");
}

.s32kmhs8b {
  fill: var(--svg-color--f4f30a, #f4f30a);
  d: path("M17.202 38.557c-.004.043-.012.082-.055.107a.16.16 0 0 1-.13-.05c-.061 0-.106-.056-.171-.041c-.048-.056-.096-.108-.143-.164c-.074-.015-.12-.072-.175-.118l-.101-.089c-.022-.056.007-.093.048-.124a.16.16 0 0 1 .107-.006c.14.094.265.209.416.287q.062.055.126.105c.047.015.096.026.078.093");
}

.s3bvj-78i {
  fill: var(--svg-color--590000, #590000);
  d: path("M23.864 37.945c-.04.002-.076-.003-.099-.041h.302c-.056.061-.134.035-.203.041");
}

.s50r52m7o {
  fill: var(--svg-color--a21b19, #a21b19);
  d: path("M18.682 32.914c.032.07.082.137.054.222c-.068-.061-.159-.118-.054-.222");
}

.s5alv_wbd {
  fill: var(--svg-color--383800, #383800);
  d: path("m16 32.661l-.018.005h-.019a.12.12 0 0 1-.115-.053c-.011-.055.021-.081.063-.104h.06z");
}

.s7ly94b4x {
  fill: var(--svg-color--682c2b, #682c2b);
  d: path("M24.06 34.765c.031-.072.112-.085.166-.128c-.026.08-.026.188-.159.162z");
}

.s8ajs9tua {
  fill: var(--svg-color--632202, #632202);
  d: path("M25.559 40.35v-.05q-.02-.017-.018-.039q.004-.022.008-.021c.05-.044.105-.048.166-.031c.031.013.063.03.092.043c-.058.097-.152.101-.248.098");
}

.s9kyy6i7i {
  fill: var(--svg-color--443411, #443411);
  d: path("m31.445 34.505l.075.01c-.118.074.014.273-.162.315a.13.13 0 0 1-.048-.063c-.013-.118-.004-.222.135-.262");
}

.sa08j0pyh {
  fill: var(--svg-color--4b4902, #4b4902);
  d: path("M31.2 29.29c.094.138.021.327.133.46c-.063.06-.123-.043-.185.002l.004-.02a.18.18 0 0 1-.046-.139c.04-.098-.088-.249.094-.303");
}

.safi0abgl {
  fill: var(--svg-color--521e02, #521e02);
  d: path("m26.98 23.18l.069.092c-.096-.017-.194-.026-.224-.145q.078.024.155.053");
}

.safjg7bsh {
  fill: var(--svg-color--282000, #282000);
  d: path("m28.733 31.426l.061.04c-.061.091-.168.013-.238.065a.03.03 0 0 0-.012-.029l-.007-.06q.099-.007.196-.016");
}

.samr2jbmr {
  fill: var(--svg-color--60390c, #60390c);
  d: path("M24.888 37.887q-.024-.024-.052-.045q-.019-.039.024-.041q.067.004.135.004q0 .042-.002.082z");
}

.sb8y-gtjm {
  fill: var(--svg-color--113579, #113579);
  d: path("M20.478 31.15c-.059-.044-.12-.082-.197-.072c.102-.078.179-.084.197.072");
}

.sb9x9fblt {
  fill: var(--svg-color--f3f206, #f3f206);
  d: path("m28.539 37.12l-.101.062c-.07.042-.138.091-.212.127c-.069.028-.142.014-.212.021c-.048-.003-.096-.005-.12.046a.3.3 0 0 1-.189.053h-.077c-.083.01-.176-.026-.251.041a.2.2 0 0 1-.058.048c-.089.024-.178.01-.267.015c-.099.009-.207-.028-.292.055c-.117.085-.259.021-.384.065c-.052.014-.106 0-.159.017c-.137.097-.291.061-.44.069c-.132.01-.268-.027-.396.025c-.049.023-.1.04-.146.066c-.081.015-.161.008-.242.01h-.161c-.173 0-.344-.01-.513.036c-.049.017-.097.039-.146.054a.5.5 0 0 1-.113.012c-.089 0-.178.004-.267-.003a.12.12 0 0 1-.09-.062c-.01-.045.017-.068.056-.083l.06-.01c.078-.053.174-.066.26-.096c.131-.024.26-.074.396-.07c.081-.002.16 0 .24-.002h.077c.125-.007.255.033.37-.046a.2.2 0 0 1 .072-.033c.118-.033.24-.02.36-.023c.128-.008.259.023.384-.029a1 1 0 0 1 .107-.046c.074-.022.152-.024.229-.026c.098-.003.197.019.29-.033a1 1 0 0 1 .104-.044c.074-.022.149-.022.227-.024c.096-.005.197.018.284-.045c.086-.056.194-.049.283-.097c.172-.097.364-.111.554-.143c.089-.019.176-.035.263-.056a.27.27 0 0 1 .155.018c.048.028.078.069.065.131");
}

.sbevwqvmh {
  fill: var(--svg-color--272700, #272700);
  d: path("M29.16 31.547c.097-.019.205.014.294-.057q.03.022.059.046l-.015.046c-.075.066-.176.002-.256.047l-.197.01c.005-.073.089-.047.115-.092");
}

.sc7artbdi {
  fill: var(--svg-color--4d4e00, #4d4e00);
  d: path("M29.25 35.948c.048-.156-.21-.19-.145-.354l.27.25c-.003.08-.062.094-.125.104");
}

.sckp32sbj {
  fill: var(--svg-color--f7f70a, #f7f70a);
  d: path("M18.691 22.307c-.04-.017-.053-.049-.057-.089c.025-.079.108-.017.148-.06c.024-.047.069-.059.118-.065c.079-.044.156-.102.255-.054q.038.052.026.115c-.038.116-.154.09-.235.128c-.079.058-.161.107-.255.025");
}

.sd3sbxufp {
  fill: var(--svg-color--5c5d05, #5c5d05);
  d: path("m30.64 34.2l.05.057c-.019.064-.03.135-.107.16c-.027-.084.025-.149.057-.217");
}

.se_thcbes {
  fill: var(--svg-color--504e41, #504e41);
  d: path("M32.33 30.617c-.015-.072.026-.159-.056-.213l-.043-.082c.257.025.144.17.099.295");
}

.sg52v8rwk {
  fill: var(--svg-color--494905, #494905);
  d: path("M15.677 23.23c-.101.092-.166.23-.324.248c.069-.128.189-.207.294-.299c.035.004.042.02.03.051");
}

.sggnlw5tm {
  fill: var(--svg-color--dada14, #dada14);
  d: path("M26.371 24.756q-.248.01-.495.017l-.002-.12c.05-.045.11-.038.17-.041a4 4 0 0 1 .32-.014q.093.075.007.158");
}

.sghe2ob7a {
  fill: var(--svg-color--090700, #090700);
  d: path("m18.635 34.561l.093-.044l.029.024l-.02.033q-.02.002-.036.007l-.033-.021l-.017-.004z");
}

.sh-qmvb-q {
  fill: var(--svg-color--6b6c0e, #6b6c0e);
  d: path("M13.445 27.27a.65.65 0 0 1-.09.306c-.087-.119-.021-.211.053-.301q.015-.037.037-.005");
}

.shufelbox {
  fill: var(--svg-color--f5f504, #f5f504);
  d: path("m12.688 34.801l-.09-.24c-.102-.078-.064-.212-.115-.311v.004c-.079-.072-.069-.18-.101-.27l-.104-.341c-.088-.11-.062-.25-.101-.371l.007.005c-.091-.123-.067-.277-.108-.414v.005c-.053-.071-.051-.155-.056-.237c-.008-.09.065-.182-.003-.271l-.046-.104c-.052-.082-.028-.169-.017-.257c.008-.032-.012-.046-.04-.051c-.058-.14.012-.297-.059-.434a.36.36 0 0 1 .024-.216c.058-.07.122-.116.21-.048c.057.091.033.194.057.291l.005.071a.55.55 0 0 0 .011.296c.021.1.037.2.093.289a.2.2 0 0 1 .013.104c-.013.087-.039.176-.003.265c.02.099.027.2.085.288a.2.2 0 0 1 .017.098a.4.4 0 0 0 .084.273a.2.2 0 0 1 .019.097a.43.43 0 0 0 .08.305a.2.2 0 0 1 .019.095c-.014.105.052.183.088.271c.017.092.035.183.105.252c.04.057.066.119.063.191a.24.24 0 0 0 .089.204a.2.2 0 0 1 .063.149c-.01.071.034.113.074.162q.019.028.022.061c.005.068.045.126.062.191a.17.17 0 0 1-.017.109c-.036.044-.081.059-.132.021l-.089-.104c-.075-.052-.067-.144-.105-.211v.002c-.077-.051-.07-.147-.105-.219");
}

.si4641blq {
  fill: var(--svg-color--edf2ef, #edf2ef);
  d: path("M19.656 30.32c.013.105-.023.181-.129.212c-.065.02-.119-.017-.149-.065c-.061-.099-.015-.173.077-.227c.082-.015.165-.025.201.08");
}

.si6s-wbeh {
  fill: var(--svg-color--fdfd02, #fdfd02);
  d: path("M13.238 26.762q.062.003.122.008c.108.045.214.09.194.238c-.017.096-.083.17-.107.26a.8.8 0 0 0-.067.318a.4.4 0 0 1-.056.158c-.053.063-.102.127-.096.217a.6.6 0 0 1-.049.163a1.5 1.5 0 0 0-.134.39c-.031.131-.085.258-.073.397a.2.2 0 0 1-.012.065a.22.22 0 0 0-.034.211a.2.2 0 0 1-.014.096a.3.3 0 0 0-.061.186c-.005.087-.019.169-.084.233c-.082.07-.197.091-.278.171c-.087.049-.171.117-.284.082c-.063-.045-.079-.104-.059-.176a.86.86 0 0 1 .073-.392q.004-.025.004-.048c.001-.054-.004-.109.007-.166a.5.5 0 0 0 .024-.092c.036-.054.053-.111.032-.176a.2.2 0 0 1 .004-.067c.013-.077.015-.161.082-.22l.053-.271c.01-.12.054-.232.085-.347c.026-.105.05-.212.096-.312c.038-.1.067-.205.125-.297l.056-.154c.026-.074.014-.168.099-.214c.02-.065.036-.134.056-.199c.084-.088.192-.074.296-.062");
}

.sibhawb8r {
  fill: var(--svg-color--f5f60e, #f5f60e);
  d: path("M19.406 22.09a8 8 0 0 1-.252.08l-.013-.136l.058-.046c.092.021.179.02.253-.048q-.02.076-.046.15");
}

.sjh2di6kv {
  fill: var(--svg-color--51530d, #51530d);
  d: path("m18.79 21.479l-.009-.053l.019-.04c.051-.008.106-.001.143-.051l.048-.003c.012.158-.129.106-.201.147");
}

.sjq3lbc_n {
  fill: var(--svg-color--f9f907, #f9f907);
  d: path("m24.17 21.958l.06-.116l.361.005c.028.044.041.092.019.143a.2.2 0 0 1-.06.048c-.075.021-.153.007-.23.01c-.063-.008-.136.002-.15-.09");
}

.sjs5xkblr {
  fill: var(--svg-color--252600, #252600);
  d: path("M17.15 29.938q0-.024.004-.049q.022-.03.046-.004q.155.006.311.009q.002.02.002.043z");
}

.skuluetnl {
  fill: var(--svg-color--45441b, #45441b);
  d: path("M13.354 34.05a.05.05 0 0 0-.003.035c-.107-.055-.156-.134-.103-.254z");
}

.sn2xf232h {
  fill: var(--svg-color--3d3c00, #3d3c00);
  d: path("m21.654 25.18l.053.002q.004.02.004.039l-.51.002l-.005-.028l.106-.02c.119-.059.238-.072.352.005");
}

.sn6jazbtt {
  fill: var(--svg-color--0d0b05, #0d0b05);
  d: path("M18.12 24.66c-.085-.027-.192.063-.265-.044c.082-.103.171-.04.257-.007q.024.013.02.031q-.005.02-.012.02");
}

.sp_h5obyp {
  fill: var(--svg-color--2c4d0b, #2c4d0b);
  d: path("M15.4 35.522c.02.06.041.117-.06.115l-.301-.003l.168-.094z");
}

.speca1_kn {
  fill: var(--svg-color--2d3000, #2d3000);
  d: path("m13.556 30.509l.048.053c-.087.093-.202.034-.303.053l-.053-.002c.079-.107.194-.104.308-.104");
}

.spuwnjb_k {
  fill: var(--svg-color--752618, #752618);
  d: path("m26.29 38.816l-.08.099c-.033.06-.079.087-.146.062q-.022-.032.005-.063c.047-.092.127-.107.221-.098");
}

.spvdfef5t {
  fill: var(--svg-color--5c5a00, #5c5a00);
  d: path("M15.391 32.35c-.18.001-.37.041-.5-.137c.171-.034.327.064.495.048c.053.026.046.055.005.089");
}

.sq52lmb_w {
  fill: var(--svg-color--545500, #545500);
  d: path("m27.771 38.15l-.007-.145q.104-.03.211-.057c-.049.087-.097.174-.204.202");
}

.ss-fttp4d {
  fill: var(--svg-color--c3ad45, #c3ad45);
  d: path("M25.772 26.2h1.775a.2.2 0 0 1 .008.047l-1.687.01c-.041 0-.086 0-.096-.057");
}

.ss-gbqfqh {
  fill: var(--svg-color--36402a, #36402a);
  d: path("M13.09 29.27c-.013-.197-.007-.395.094-.574a.16.16 0 0 1 .061.074c.04.125.036.253.014.378c-.017.082-.039.176-.164.133z");
}

.ssh14fj4u {
  fill: var(--svg-color--333100, #333100);
  d: path("M16.837 37.27q-.152 0-.303-.004q-.047-.049-.001-.099l.239.015c.045.012.093.024.065.088");
}

.str-odbcj {
  fill: var(--svg-color--2a2b2b, #2a2b2b);
  d: path("M16.13 26.664h.034c.084.072.058.171.058.262c.004.404.002.812.002 1.217c-.029.241.067.492-.06.727h-.034z");
}

.stx3h-buo {
  fill: var(--svg-color--f9f90f, #f9f90f);
  d: path("m15.04 29.95l.051.144l-.408.118a.21.21 0 0 1-.166.104c-.322.032-.623.154-.936.234a2 2 0 0 0-.33.094c-.041.007-.077 0-.106-.031c-.067-.003-.144.011-.154-.089c.025-.078.104-.032.152-.063l-.002.001c.071-.075.173-.085.26-.123c.113-.033.226-.082.348-.082c.167-.09.373-.084.529-.205c.131.016.258-.017.384-.043c.091-.031.182-.07.281-.061q.047-.001.097.002");
}

.su1iu2b8n {
  fill: var(--svg-color--474608, #474608);
  d: path("M12.584 30v.038c-.077.056-.15.123-.258.111c.031-.142.163-.113.258-.149");
}

.sur5ow26r {
  fill: var(--svg-color--5a2306, #5a2306);
  d: path("M27.711 37.945c-.031.064-.098.05-.15.066c.023-.156.13-.209.27-.221q-.06.08-.12.155");
}

.swhztidag {
  fill: var(--svg-color--d0d10f, #d0d10f);
  d: path("m29.415 36.2l.039.036c.088.099-.052.154-.046.237q-.02.019-.041.035c-.059.031-.068.134-.162.11c0-.075-.028-.133-.103-.161c-.003-.146.132-.19.206-.281a.13.13 0 0 1 .107.024");
}

.sxiecgbxr {
  fill: var(--svg-color--241e00, #241e00);
  d: path("m27.05 37.529l.048.05q-.127.005-.25.012a.1.1 0 0 0-.009-.038c.064-.074.139-.041.211-.024");
}

.sxnrdhadd {
  fill: var(--svg-color--3b450e, #3b450e);
  d: path("m13.827 34.819l-.25-.616q.015-.039.039-.007c.158.161.232.363.296.571z");
}

.sybn4vjed {
  fill: var(--svg-color--737300, #737300);
  d: path("M19.2 37.646c-.071-.026-.165.037-.216-.056c.066-.132.161-.089.259-.043l.057.046a.1.1 0 0 0 .002.038c-.03.039-.066.035-.102.015");
}

.syhp5-wkn {
  fill: var(--svg-color--505002, #505002);
  d: path("M13.659 35.28c-.01-.155.112-.137.207-.155q.023.017.015.033q-.008.015-.016.015z");
}

.syktxr09l {
  fill: var(--svg-color--5c0000, #5c0000);
  d: path("m27.656 37.4l.236-.021c-.046.11-.14.103-.233.093q-.023-.035-.003-.072");
}

.symwg_bjg {
  fill: var(--svg-color--131200, #131200);
  d: path("M18.312 22.261c-.005.085-.017.161-.134.125q0-.015-.003-.026c.024-.061.055-.116.137-.099");
}

.sz79jnuoy {
  fill: var(--svg-color--213704, #213704);
  d: path("M14.369 35.886a.7.7 0 0 1 .355-.151a.07.07 0 0 1 .067-.003c.008.084.019.153.128.178c.132.029.257.072.394.08c.126.009.253.034.313.171a.1.1 0 0 1-.031.066c-.224.057-.428-.06-.643-.071c-.092-.005-.181-.041-.274-.028c-.099.011-.146-.062-.204-.121l-.072-.065a.14.14 0 0 1-.033-.056");
}

.szlkakb5i {
  fill: var(--svg-color--262700, #262700);
  d: path("m12.163 31.848l.06.35c-.147-.061-.079-.197-.105-.299c-.023-.053.003-.06.045-.051");
}

.szwwqnfgb {
  fill: var(--svg-color--0a0602, #0a0602);
  d: path("m26.489 29.29l-.017.244c-.077-.09-.031-.194-.039-.293a.05.05 0 0 1 .046-.002z");
}

.t_0v-1_am {
  fill: var(--svg-color--414235, #414235);
  d: path("m26.889 35.594l-.014-.002h-.015c.025-.098.058-.188.18-.197a.23.23 0 0 1-.151.199");
}

.t_fmi_bty {
  fill: var(--svg-color--494343, #494343);
  d: path("M19.907 37.37a.25.25 0 0 1 .238.114c-.095-.021-.197-.024-.272-.1c.003-.023.017-.028.034-.014");
}

.t_wz7qbqn {
  fill: var(--svg-color--e5e6be, #e5e6be);
  d: path("M22.479 23.746c-.015.055-.057.041-.095.04l-.004-3.219h.05q-.002 1.471 0 2.942c.001.081-.035.174.049.237");
}

.t-9bwxbre {
  fill: var(--svg-color--ebec0e, #ebec0e);
  d: path("M13.558 36.1c.156-.173.388-.23.567-.367c.08-.047.177-.054.253-.111c.089-.019.181-.028.256-.088h.053c.072.035.168.027.217.112c-.013.092-.093.103-.157.132c-.128.022-.238.089-.352.146a.8.8 0 0 0-.211.108c-.085.054-.171.11-.272.13a.36.36 0 0 0-.188.104q-.075.062-.153.114c-.039.024-.082.027-.126.024c-.051-.021-.087-.053-.101-.107c0-.142.125-.149.214-.197");
}

.t0z7-m0pi {
  fill: var(--svg-color--274209, #274209);
  d: path("M12.482 34.25q.09.143.115.311c-.158-.057-.11-.194-.115-.311");
}

.t222kqbvo {
  fill: var(--svg-color--2f3900, #2f3900);
  d: path("M16.998 23.24q.024.02.046.043c-.079.059-.146.138-.253.15q-.029.03-.055-.003z");
}

.t2vnkpc6g {
  fill: var(--svg-color--2e2e00, #2e2e00);
  d: path("m13.409 29.744l-.099-.039l.257-.067a.24.24 0 0 1-.158.106");
}

.t38y6qq6w {
  fill: var(--svg-color--454607, #454607);
  d: path("M12.226 31.07c.03-.131.129-.15.242-.147c-.012.159-.149.118-.242.147");
}

.t3v2jqbzn {
  fill: var(--svg-color--591c08, #591c08);
  d: path("M27.969 22.666c-.087-.054-.186-.095-.211-.21c.163-.022.207.072.211.21");
}

.t547dcbzq {
  fill: var(--svg-color--888900, #888900);
  d: path("M28.792 26.873a.05.05 0 0 0-.002.043c-.063.039-.13.072-.208.056c.018-.145.121-.104.21-.099");
}

.t6i9drbja {
  fill: var(--svg-color--e2e01b, #e2e01b);
  d: path("m17.15 30.354l-.019-.048l.02-.031c.142-.119.271-.046.403.021q.03.018.056.043c.02.034.008.064-.02.089a.2.2 0 0 1-.06.026c-.041.012-.082.018-.125.026q-.03.003-.061 0c-.051-.014-.102-.024-.147-.05a.1.1 0 0 1-.047-.076");
}

.t6owtpb0h {
  fill: var(--svg-color--6e0b05, #6e0b05);
  d: path("M27.05 29.602c-.051.089-.048.188-.045.284l-.067.002a.43.43 0 0 1-.005-.299z");
}

.t6x1zcboq {
  fill: var(--svg-color--dfdf0d, #dfdf0d);
  d: path("M16.943 26.04a.2.2 0 0 0 0-.046c.038-.14.046-.294.211-.356c.07-.007.079.044.092.094c.005.087-.026.169-.046.253a.2.2 0 0 1-.038.063a.05.05 0 0 1-.065 0c-.053.013-.104.026-.154-.008");
}

.t7txer11l {
  fill: var(--svg-color--5f0000, #5f0000);
  d: path("m24.995 37.805l.256-.012c.053-.019.064.005.052.053c-.096.066-.204.037-.31.041q-.041-.042.002-.082");
}

.t8zk3pcvy {
  fill: var(--svg-color--cacb24, #cacb24);
  d: path("M30.479 25.13c.07.08.204.108.209.244q-.069-.017-.139-.037a.08.08 0 0 1-.07.013a.16.16 0 0 1-.085-.118a.13.13 0 0 1 .032-.105l.005-.01a.2.2 0 0 1 .048.013");
}

.t9_02clmd {
  fill: var(--svg-color--1f3c07, #1f3c07);
  d: path("m16.33 35.33l-.116-.005c.183-.084.385-.086.573-.138q.004.019.004.039c-.128.147-.303.092-.461.104");
}

.t9z77ibtp {
  fill: var(--svg-color--d7d70a, #d7d70a);
  d: path("m17.862 34.878l-.051.094q-.049.03-.099.058c-.048-.012-.094-.023-.115-.074l.03-.125c.047.028.08-.006.118-.027c.068-.021.098.02.117.074");
}

.tbgcdj_fm {
  fill: var(--svg-color--dcdd13, #dcdd13);
  d: path("M12.892 26.508a.44.44 0 0 1 .253.051l-.049.052c-.12.049-.24.099-.32-.062a.1.1 0 0 1 .016-.037z");
}

.tbp2icc6i {
  fill: var(--svg-color--7e250c, #7e250c);
  d: path("m26.02 21.475l-.054.046c-.067-.044-.166-.008-.219-.089c.101-.036.206-.119.273.043");
}

.tbq_vxbpo {
  fill: var(--svg-color--f9f640, #f9f640);
  d: path("M15.09 23.704h-.031l.015-.035z");
}

.tbstdss9q {
  fill: var(--svg-color--292825, #292825);
  d: path("M16.546 34.05c.153.053.137.188.151.308c-.132-.063-.127-.193-.151-.308");
}

.tc4h_4blz {
  fill: var(--svg-color--2d2d00, #2d2d00);
  d: path("m12.285 29.07l-.02.097c-.046.01-.069 0-.051-.053c.015-.102-.005-.21.061-.301q.031.013.031.048l.013.053c.009.056.004.11-.034.156");
}

.tc851ggkp {
  fill: var(--svg-color--581503, #581503);
  d: path("M28.02 37.33c.054-.072.145-.036.212-.068a.06.06 0 0 1 .065.02c.017.037.01.072-.013.106l-.106.106c.017-.125-.119-.098-.158-.164");
}

.td_6g3bsa {
  fill: var(--svg-color--f5f413, #f5f413);
  d: path("M25.11 22.305q-.038-.027-.072-.054a.06.06 0 0 1 .005-.063a.2.2 0 0 1 .158-.038l.061.002c.102.013.209.012.286.097l.126.01c.066.079.163.103.254.137c.057.06.141.072.208.11c.023.032.023.067.01.102c-.027.046-.075.056-.121.07c-.064.004-.11-.034-.158-.067l.005.002c-.068-.034-.146-.053-.21-.095l-.094-.06c-.084.011-.133-.071-.209-.081l-.049-.021a.4.4 0 0 1-.2-.051");
}

.td_8icbmt {
  fill: var(--svg-color--1a1a00, #1a1a00);
  d: path("M25.91 35.28q.01.022.01.049l-.085-.013a.1.1 0 0 1-.01-.04q.016-.023.044-.021q.027 0 .041.025");
}

.td7upkbmn {
  fill: var(--svg-color--d6d769, #d6d769);
  d: path("m21.821 23.735l.481.011q.012.015.01.038l-.565-.007a.07.07 0 0 1 .02-.054q.032-.012.054.012");
}

.tdtnysb5t {
  fill: var(--svg-color--c4ad47, #c4ad47);
  d: path("M21.16 26.2q.867.007 1.739.012c-.086.088-.194.043-.29.045c-.482.002-.968-.004-1.453-.005a.1.1 0 0 1 .004-.052");
}

.tdu_zibdm {
  fill: var(--svg-color--553d3a, #553d3a);
  d: path("m18.16 36.36l.07-.007c.105 0 .094.075.094.145a.3.3 0 0 1-.164-.138");
}

.tdwihkb8i {
  fill: var(--svg-color--f1f10f, #f1f10f);
  d: path("m17.813 39.13l-.043-.05a.4.4 0 0 1-.153-.1c-.169-.086-.35-.153-.47-.313c-.003-.055.015-.098.063-.125c.084-.018.142.018.186.087h-.005c.269.136.539.266.804.408c.146.088.326.112.45.24c.025.053.017.099-.036.132a.11.11 0 0 1-.108-.015c-.136-.008-.239-.127-.383-.113c-.061-.13-.218-.071-.305-.15");
}

.te8mlqh8k {
  fill: var(--svg-color--d20607, #d20607);
  d: path("m22.12 24.25l.002-.094l.207.007l-.056.104l-.053-.002q-.054.033-.1-.015");
}

.teha-84an {
  fill: var(--svg-color--a6280c, #a6280c);
  d: path("m22.796 25.683l.037.007c.176.087.127.222.074.356l-.013.002l-.014-.003c-.029-.023-.065-.041-.089-.072c-.05-.098-.094-.195.005-.29");
}

.tenkm8bzd {
  fill: var(--svg-color--0d2e00, #0d2e00);
  d: path("M21.504 20.563c.065-.148.138-.146.21-.005l-.003.005a.3.3 0 0 1-.064.039c-.051.014-.097-.003-.138-.035z");
}

.teyaoq5-u {
  fill: var(--svg-color--fdfd03, #fdfd03);
  d: path("M15.456 34.612v-.192c.097-.109.221-.089.344-.069c.046.019.063.056.065.102c-.075.129-.204.105-.322.108z");
}

.tfm_cfpue {
  fill: var(--svg-color--0d1200, #0d1200);
  d: path("M29.762 24.82c-.032-.01-.08.006-.087-.051q.039.002.077.006a.07.07 0 0 1 .01.045");
}

.th_s67bzp {
  fill: var(--svg-color--343634, #343634);
  d: path("m23.453 37.89l-.135.048l-.128-.048l.265-.074q.044.036-.002.074");
}

.th2i30qom {
  fill: var(--svg-color--4b4c0c, #4b4c0c);
  d: path("M14.281 37.03c.104.049.188.109.188.24c-.152-.006-.185-.112-.188-.24");
}

.tirutlbtw {
  fill: var(--svg-color--fafa02, #fafa02);
  d: path("m25.856 30.614l.003-.207q-.009-.097.077-.142q.256-.067.51-.002a.1.1 0 0 1 .055.063c-.021.145-.119.248-.191.367c-.036.09-.087.161-.192.183c-.198.042-.275-.033-.262-.262");
}

.tixruff7z {
  fill: var(--svg-color--d0d110, #d0d110);
  d: path("M18.03 35.29c-.051-.123-.209-.173-.219-.322c-.024-.052.005-.087.041-.116a.1.1 0 0 1 .067-.005c.074.031.122.092.171.151q.045.068.062.147q.004.03-.006.063a.16.16 0 0 1-.057.072q-.028.015-.059.01");
}

.tj8_3sepc {
  fill: var(--svg-color--443b0a, #443b0a);
  d: path("M26.994 25.22v-.045a.2.2 0 0 1 .054-.041c.082-.032.178-.001.255-.056c.034-.053.043-.099-.021-.135c-.079-.019-.161-.005-.241-.017a.2.2 0 0 1-.107-.05a.12.12 0 0 1-.016-.08a.1.1 0 0 1 .051-.065a.9.9 0 0 1 .554.007c-.026.159-.096.315-.056.484a.75.75 0 0 1-.473-.002");
}

.tj82s8jsp {
  fill: var(--svg-color--f8f508, #f8f508);
  d: path("m26.02 35.33l-.057.011l-.051-.012l.003.003a.07.07 0 0 1-.03-.047a.08.08 0 0 1 .025-.053l.005-.006c.033.021.066.038.099.059a.2.2 0 0 1 .006.045");
}

.tj88cxbiv {
  fill: var(--svg-color--100e01, #100e01);
  d: path("M32.24 30.465c-.02-.036.002-.051.031-.061c.138.039.07.133.056.213q-.027.045-.058.089a.07.07 0 0 1-.053.036a.1.1 0 0 1-.059-.031c-.035-.104.076-.157.083-.246");
}

.tjec-p6xw {
  fill: var(--svg-color--ccb6a1, #ccb6a1);
  d: path("M30.776 33.29c.02-.067.001-.143.056-.201c0 .073.013.148-.005.215c-.019.066-.034-.002-.051-.014");
}

.tkat80paf {
  fill: var(--svg-color--e7e712, #e7e712);
  d: path("m28.28 37.28l-.05-.013c.05-.083.123-.1.212-.08l-.008.019c-.037.053-.078.099-.154.074");
}

.tkk-iib9t {
  fill: var(--svg-color--4f2604, #4f2604);
  d: path("M17.501 24.352c-.084.02-.143-.002-.158-.098l.173.004z");
}

.tkl4wt1yi {
  fill: var(--svg-color--f3f207, #f3f207);
  d: path("M28.08 22.814c-.045.004-.087.012-.112.056c-.141.069-.195-.059-.277-.123a.25.25 0 0 1-.065-.135c-.004-.069.015-.125.089-.147a.1.1 0 0 1 .047-.009q.135.076.211.21l-.004-.003c.047.043.176.026.111.151");
}

.tkomizblj {
  fill: var(--svg-color--e4e40a, #e4e40a);
  d: path("M18.06 29.654v.235h-.352c-.063-.096-.079-.189.01-.28c.116-.001.236-.029.342.045");
}

.tkot8pb-f {
  fill: var(--svg-color--e2e20e, #e2e20e);
  d: path("M29.651 37.17c.042-.121.146-.193.213-.291c.039-.057.09-.055.146-.033a.1.1 0 0 1 .045.064c.003.118-.069.193-.151.264q-.044.052-.091.104l-.041.006l-.171-.009c-.02-.053.033-.071.05-.105");
}

.tkuizxbmx {
  fill: var(--svg-color--c1c7a3, #c1c7a3);
  d: path("m12.06 32.6l-.051-.092q.006-.074.009-.148c.094.066.041.158.042.24");
}

.tkysypb-w {
  fill: var(--svg-color--dcd946, #dcd946);
  d: path("M24.86 37.801a.2.2 0 0 0-.024.041q-.175.006-.351.015a.3.3 0 0 1-.207-.008c.186-.107.386-.043.582-.048");
}

.tl41bwbhx {
  fill: var(--svg-color--505002, #505002);
  d: path("M14.737 36.2a.28.28 0 0 1 .213.1l-.058.069l-.15-.032z");
}

.tlq41rx6x {
  fill: var(--svg-color--013399, #013399);
  d: path("M19.702 31.849c-.344-.084-.52-.33-.551-.654c-.033-.363-.01-.731-.015-1.098c-.002-.097.034-.138.135-.137q.626.006 1.252 0c.13-.001.156.058.155.173c-.007.313.006.631-.007.945c-.02.409-.227.676-.579.773a.9.9 0 0 1-.39-.002m2.338-4.559c.205 0 .409.005.613 0c.111-.003.151.039.149.148c-.007.357.008.717-.015 1.073a.78.78 0 0 1-.714.715a.77.77 0 0 1-.771-.585c-.099-.411-.028-.832-.041-1.25c-.003-.116.089-.102.164-.102zm.05 2.665c.204.018.513-.099.658.045c.157.154.044.468.049.711c.005.219.031.442-.053.658c-.125.325-.424.539-.741.523a.766.766 0 0 1-.702-.602c-.092-.402-.024-.814-.041-1.225c-.005-.111.077-.111.158-.111zm1.464.02c.407-.005.815-.006 1.223-.016c.118-.002.168.034.166.159c-.008.323.007.647-.008.97c-.019.393-.219.649-.564.76a.8.8 0 0 1-.409 0a.65.65 0 0 1-.508-.517c-.05-.413-.01-.825-.023-1.239c-.002-.086.035-.125.123-.117m-.77 2.686c.003.371.018.746.005 1.117a.77.77 0 0 1-.7.748c-.382.034-.697-.212-.794-.623a9 9 0 0 1 0-1.242c.496-.038.993-.035 1.489 0");
}

.tlyy3tbxs {
  fill: var(--svg-color--093602, #093602);
  d: path("M14.787 23.738c-.07.18-.238.271-.361.404c.013-.215.208-.304.313-.453c.05-.016.063.003.048.049");
}

.tm03ulbde {
  fill: var(--svg-color--154306, #154306);
  d: path("m12.06 32.6l.017.269c-.111-.104-.149-.221-.067-.36c.05.012.022.066.05.091");
}

.tmtqqm6hs {
  fill: var(--svg-color--e7ea61, #e7ea61);
  d: path("M27.29 36.453c.063-.051.141-.033.212-.05l.059.012c-.082.072-.179.038-.271.038");
}

.tn9kx2b8b {
  fill: var(--svg-color--282a00, #282a00);
  d: path("M25.313 40.2c-.021.052-.074.043-.113.062l-.206.041l-.015-.019l.017-.018c.106-.016.188-.149.317-.066");
}

.tnms_6bav {
  fill: var(--svg-color--2b2b00, #2b2b00);
  d: path("M31.402 27.633a.5.5 0 0 1-.133-.352l.013.004c.065.108.125.216.12.348");
}

.to5a-yrtm {
  fill: var(--svg-color--646624, #646624);
  d: path("M18.675 34.76a.1.1 0 0 1-.036.008q-.018-.016-.015-.035q0-.021.005-.021l.029-.011l.028.016a.1.1 0 0 1-.011.043");
}

.to6uzwbyx {
  fill: var(--svg-color--eae712, #eae712);
  d: path("m27.25 36.14l.267.064c.041.073.012.128-.048.174c-.063.033-.13.024-.195.022a.45.45 0 0 1-.271-.133a.1.1 0 0 1-.017-.074c.035-.063.089-.089.158-.094a.2.2 0 0 1 .106.041");
}

.tob-0lb3i {
  fill: var(--svg-color--454706, #454706);
  d: path("M25.16 39.58c-.004-.037-.005-.076.038-.096l.203-.048c-.017.154-.154.107-.241.144");
}

.tohje-f2n {
  fill: var(--svg-color--45432d, #45432d);
  d: path("M26.889 35.594c.033.109-.214.179-.043.309q.019.036-.012.064a.17.17 0 0 1-.174.006l-.026-.024c-.019-.179.122-.257.227-.356z");
}

.tor7-cc7l {
  fill: var(--svg-color--f2f209, #f2f209);
  d: path("M13.811 36.778q-.019-.032-.041-.063c.008-.091.005-.189.138-.191c.216.086.296.289.406.467c.023.117.074.209.194.252a.8.8 0 0 1 .21.246a.17.17 0 0 1-.013.148a.12.12 0 0 1-.064.039c-.217-.024-.292-.215-.416-.354l-.063-.09c-.047-.057-.12-.088-.132-.17h.003c-.119-.059-.131-.202-.222-.283");
}

.tpdz3fojl {
  fill: var(--svg-color--fcfc02, #fcfc02);
  d: path("M22.796 25.683c-.033.108.008.209.036.312c-.101.056-.211.018-.315.027c-.058-.007-.086-.049-.114-.094a.9.9 0 0 0-.222-.317a.1.1 0 0 1-.01-.069c.169-.106.354-.044.529-.037c.092.002.086.105.096.178");
}

.tpjz_ogvu {
  fill: var(--svg-color--be1e18, #be1e18);
  d: path("m22.01 24.303l-.1-.006c-.064-.031-.135-.049-.192-.092l-.014-.049l.418-.002q.038.044.015.099c-.032.044-.077.05-.127.05");
}

.tpnx04bpe {
  fill: var(--svg-color--f2f40a, #f2f40a);
  d: path("m16.431 23.483l.117.06c-.021.125-.117.166-.221.197l-.065.013c-.061.019-.103.003-.112-.063c.021-.081.062-.144.151-.155h.017c.033-.028.067-.053.113-.052");
}

.tq4ujpoij {
  fill: var(--svg-color--676800, #676800);
  d: path("m29.05 32.31l-.058-.058q.009-.017.015-.036c.055-.063.123-.028.186-.026q.037.03.011.067a.1.1 0 0 1-.011.036z");
}

.tqbhkviwv {
  fill: var(--svg-color--111f03, #111f03);
  d: path("m13.305 28.355l-.014-.059c0-.089.017-.175.071-.248q.049-.017.073.027c.026.126.099.276-.13.28");
}

.ts0mp9chz {
  fill: var(--svg-color--4d4c43, #4d4c43);
  d: path("M25.462 36.937a.3.3 0 0 1 .002.049c-.031.074-.094.089-.166.086c.029-.077.068-.139.164-.135");
}

.tsi9skbsu {
  fill: var(--svg-color--32290a, #32290a);
  d: path("M22.845 24.82v.344q.028.038-.003.078c-.148.089-.308.053-.466.039a.3.3 0 0 1-.146-.072a.2.2 0 0 1-.043-.065a.17.17 0 0 1 .013-.11a.08.08 0 0 1 .06-.027c-.033-.012.048-.01.022.013c-.006.007.012.026.011.021c-.007-.073-.038-.145-.012-.22a.15.15 0 0 1 .074-.093c.159-.044.316-.056.473.014q.04.032.017.078");
}

.tt2a5sa2s {
  fill: var(--svg-color--f1f330, #f1f330);
  d: path("m16.886 25.07l.06.061l-.265.002q-.024-.033-.002-.067a.2.2 0 0 1 .067-.032a.16.16 0 0 1 .14.036");
}

.tt75hvbqh {
  fill: var(--svg-color--cece0f, #cece0f);
  d: path("m18.523 34.26l-.082.044c-.076-.016-.23.15-.209-.09c.094.043.127-.063.195-.082l.096.082l.021.012v.024z");
}

.ttk_0olej {
  fill: var(--svg-color--262024, #262024);
  d: path("M16.787 34.584c.134.045.155.168.197.274q-.01.048-.041.01a.42.42 0 0 1-.156-.284");
}

.ttmrjwu8v {
  fill: var(--svg-color--f5f507, #f5f507);
  d: path("M16.325 37.37c-.022-.094-.022-.094-.251-.087l-.467-.074l-.048-.072c-.024-.135.082-.099.149-.111c.051-.002.103-.002.151-.019c.067-.019.122-.001.156.064c.041.061.105.053.166.059c.128.036.27.019.388.096c.089.005.18.002.269.003c.051.002.104-.003.15.026c.083.118.209.063.317.076c.104.003.211-.012.308.039c.077.046.164.053.252.063c.063.002.126 0 .188.002q.059 0 .115.003a.4.4 0 0 1 .178.069c.087.092.192.015.287.029h.189c.048.002.097-.001.146.01c.079.052.176.048.263.077c.097.079.221.014.324.06l.309-.002l.149.055c.066.032.13.063.207.041c-.061.115-.177.038-.261.072l.001-.002c-.166-.058-.335-.024-.504-.018l-.52-.045c-.115-.145-.288-.02-.419-.089l-.396-.006a.1.1 0 0 1-.023-.04c-.1-.09-.231.005-.337-.058c-.108-.012-.222.009-.32-.053c-.087-.077-.204.012-.294-.051l-.414-.047a1.3 1.3 0 0 0-.408-.07");
}

.tu-f4acsj {
  fill: var(--svg-color--6d6f18, #6d6f18);
  d: path("M13.461 35.38c-.021-.21.136-.063.202-.101q-.101.053-.202.101");
}

.tu6wqug9s {
  fill: var(--svg-color--e4e418, #e4e418);
  d: path("M17.14 30.771c-.107.056-.223.132-.209-.091c.053-.067.029-.172.11-.227c.084-.014.104.055.136.107a.3.3 0 0 1 .017.073c-.001.054-.007.104-.054.138");
}

.tuhadebap {
  fill: var(--svg-color--f5f403, #f5f403);
  d: path("m22.587 40.04l.005-.096c.142-.053.288-.021.431-.022c.07.06.018.102-.02.146c-.069.038-.144.024-.216.027c-.072 0-.146.007-.2-.055");
}

.tv9hgcz9e {
  fill: var(--svg-color--8e8c00, #8e8c00);
  d: path("m16.891 24.92l.089-.043c.084.076.079.158.014.244a.1.1 0 0 1-.048.006c-.026-.024-.064-.036-.082-.07q-.03-.077.027-.137");
}

.tvmuz7bwp {
  fill: var(--svg-color--1d1900, #1d1900);
  d: path("M25.447 34.867a.1.1 0 0 1-.036-.006q-.006-.016-.004-.034z");
}

.twnkrm_ll {
  fill: var(--svg-color--d9d505, #d9d505);
  d: path("m25.804 35.35l-.021-.004l-.02.005c-.055-.025-.051-.075-.051-.125a.05.05 0 0 1 .048-.018a.15.15 0 0 1 .063.053q.015.024.015.053a.05.05 0 0 1-.034.036");
}

.twxc8ofqk {
  fill: var(--svg-color--e9eb5c, #e9eb5c);
  d: path("M20.378 39.843q0-.025.005-.05c.087.004.177-.017.253.045z");
}

.txobbdcfs {
  fill: var(--svg-color--960703, #960703);
  d: path("M17.659 25.18c-.073-.054-.042-.138-.063-.208c.01-.069.039-.113.119-.097a.22.22 0 0 1 .053.172a.2.2 0 0 1-.017.072a.15.15 0 0 1-.049.057q-.02-.001-.043.004");
}

.tzaqnjb2k {
  fill: var(--svg-color--101100, #101100);
  d: path("m11.92 31.28l-.005-.102c.052-.08.112-.131.202-.048q.004.023.012.045c.02.032.019.065.007.1q-.03.027-.061.004c-.053-.089-.102.017-.155.001");
}

.tzk7ycc9b {
  fill: var(--svg-color--d6d714, #d6d714);
  d: path("M22.22 25.951c0-.104-.069-.18-.107-.265h.004c.043-.021.034-.066.051-.101l.007-.012c.174.033.224.164.255.314c-.079.031-.021.188-.156.171l-.002-.015c-.031-.024-.079-.038-.052-.092");
}

.tzyz41b2f {
  fill: var(--svg-color--535500, #535500);
  d: path("M27.727 22.716c-.089.038-.157.028-.177-.084q-.023-.02-.011-.038q.01-.013.021-.013l.099.04z");
}

.u_f032bml {
  fill: var(--svg-color--c8c88b, #c8c88b);
  d: path("m18.625 34.867l.01.056l-.052-.012l-.017-.02l.011-.023q.023-.02.048-.001");
}

.u_wfpdo4j {
  fill: var(--svg-color--9b0102, #9b0102);
  d: path("m26.891 29.22l-.012-.154l.115-.096c.018.096.087.202-.06.26q-.022-.004-.043-.01");
}

.u--4oqeca {
  fill: var(--svg-color--e8e749, #e8e749);
  d: path("M28.383 29.23c.048-.015.118.035.143-.049l.064.005l.055.091c-.091-.001-.188.039-.262-.047");
}

.u-k7tlbzl {
  fill: var(--svg-color--4d3e15, #4d3e15);
  d: path("M18.319 34.05q.069-.078.139-.154a.1.1 0 0 1 .075-.009c.074.091.039.175-.017.259a.1.1 0 0 1-.067.032a.16.16 0 0 1-.13-.128");
}

.u03s3803d {
  fill: var(--svg-color--585736, #585736);
  d: path("M24.791 37.38c-.048.103-.142.105-.235.106c.041-.116.119-.155.235-.106");
}

.u0fw1dbtv {
  fill: var(--svg-color--efef68, #efef68);
  d: path("m20.688 40.04l-.06-.086c.125-.088.247-.098.367.01l-.002.006a.1.1 0 0 1-.019.025q-.096.076-.195.006z");
}

.u0v_zqbxm {
  fill: var(--svg-color--535504, #535504);
  d: path("m25.765 35.38l-.002-.028q.006-.034.043-.027c.049.02.092.051.136.078c.026.021.045.047.033.083c-.048.02-.056.063-.06.11c-.073-.057-.152-.11-.15-.216");
}

.u19m_9b5e {
  fill: var(--svg-color--5f5f07, #5f5f07);
  d: path("M18.951 40.34a.03.03 0 0 0-.002-.027c.126-.082.24-.02.354.037q.043.05 0 .103l-.053.003c-.072-.106-.19-.098-.299-.116");
}

.u1gld9dow {
  fill: var(--svg-color--211c07, #211c07);
  d: path("m28.11 23.796l-.053.063l-.404-.014l.005-.059c-.021-.041.005-.061.037-.076a.2.2 0 0 1 .066-.002c.084.016.167.033.253.026c.04.008.078.018.096.062");
}

.u2q85dois {
  fill: var(--svg-color--f8f805, #f8f805);
  d: path("m18.951 40.34l-.007.112a.6.6 0 0 1-.31-.106l.055-.144c.104-.003.194.022.26.11z");
}

.u2vhfab-g {
  fill: var(--svg-color--990102, #990102);
  d: path("m17.11 29.02l-.106.151c.037-.049-.096-.219.106-.151");
}

.u30fjwnqn {
  fill: var(--svg-color--1c3c07, #1c3c07);
  d: path("M20.379 21.843c.257.007.508-.087.768-.056l.053.007c-.049.029-.104.089-.149.085c-.402-.034-.782.166-1.186.117c-.003-.113.096-.11.163-.146c.117-.018.233-.053.351-.007");
}

.u30y38bgb {
  fill: var(--svg-color--6f7111, #6f7111);
  d: path("m18.02 36.864l-.011-.038c.004-.033.033-.035.053-.048h.165l-.052.082z");
}

.u3ue6ub8l {
  fill: var(--svg-color--a91213, #a91213);
  d: path("M27.615 33.598c-.113-.104.02-.159.046-.236c.01.083.02.167-.046.236");
}

.u4dnd8b6c {
  fill: var(--svg-color--1c1900, #1c1900);
  d: path("m25.936 35.38l-.019-.054q.03-.02.06-.002q.02.031-.007.056z");
}

.u4ohbl-qa {
  fill: var(--svg-color--364f14, #364f14);
  d: path("M12.944 35.619c.067.053.123-.078.19-.015l.002.188q-.155-.019-.192-.173");
}

.u4oicrbot {
  fill: var(--svg-color--7c180d, #7c180d);
  d: path("M29.459 30.26c-.14.097-.254.03-.368-.054c.033-.035.069-.033.107-.009l.104-.005q.078.035.157.068");
}

.u4p1rm1qh {
  fill: var(--svg-color--1a1a00, #1a1a00);
  d: path("m25.866 35.28l-.041-.002l-.05-.053l.04.004a.1.1 0 0 1 .049.006q.023.015.015.03q-.005.015-.013.015");
}

.u51sudl_h {
  fill: var(--svg-color--3f2600, #3f2600);
  d: path("m26.739 36.15l-.204-.051l.05-.056l.15.049c.052-.015.064.015.064.058q-.028.033-.06 0");
}

.u5w_ngb_x {
  fill: var(--svg-color--4e4d00, #4e4d00);
  d: path("M21.75 40.969a.1.1 0 0 1 .02.044l-.059.053l-.043.012c-.075-.062-.082-.146-.082-.231q-.005-1.307 0-2.611q0-.079.032-.147a.1.1 0 0 1 .081-.053a.1.1 0 0 1 .038.086c.01.948-.02 1.898.013 2.847");
}

.u7_c0gb2c {
  fill: var(--svg-color--6d6f09, #6d6f09);
  d: path("M16.585 36.562c.072 0 .15-.012.207.053c-.032.079-.102.039-.157.046c-.031-.024-.079-.039-.051-.096z");
}

.u70p2abpg {
  fill: var(--svg-color--15110c, #15110c);
  d: path("m22.64 38.1l.003 1.739c-.101-.067-.059-.171-.059-.259c-.006-.504-.002-1.01-.004-1.51c0-.007-.005-.019-.01-.021q-.022-.003-.044-.001c-.04.024-.078.027-.108-.014a.1.1 0 0 1 .016-.077c.228-.133.479-.112.726-.128c.051.006.104.022.152.036c.063.011.128.017.183.053q.022.019.019.042q0 .024-.009.023l-.662.02c-.057.057-.155.02-.203.097");
}

.u851chb8d {
  fill: var(--svg-color--2a2605, #2a2605);
  d: path("m27.551 30.894l-.504-.029a.2.2 0 0 1-.042-.064c-.01-.051-.005-.099.03-.14c.123.005.222.156.361.063c.048-.029.064-.084.104-.12q.035-.015.053.019q.006.1.008.2q.024.04-.01.071");
}

.u88fc7bkn {
  fill: var(--svg-color--71710e, #71710e);
  d: path("m29.15 23.938l.204.162c.041.067.116.115.118.206c-.19-.052-.289-.18-.322-.368");
}

.u8s1yvlia {
  fill: var(--svg-color--33351b, #33351b);
  d: path("m19.09 37.3l.01-.058l.206.106l-.053.038a.27.27 0 0 1-.163-.086");
}

.u9muyjsmx {
  fill: var(--svg-color--263106, #263106);
  d: path("m15.663 31.525l-.411-.057c.007-.077.05-.065.099-.039l.513.007c-.045.08-.151.018-.201.089");
}

.u9ye6c-8k {
  fill: var(--svg-color--f9f808, #f9f808);
  d: path("m21.717 25.793l.148.049q.022.031.018.064c-.016.057-.027.112-.067.156c-.085.005-.162.004-.155-.113l-.006-.07c-.006-.048.018-.074.062-.086");
}

.u9z9t8-td {
  fill: var(--svg-color--2d2501, #2d2501);
  d: path("m26.896 29.592l-.05-.056c-.063-.033-.059-.113-.108-.155c-.065-.051-.149-.034-.222-.063a.1.1 0 0 1-.051-.051a.07.07 0 0 1 .032-.065c.11-.068.233-.014.349-.033a.4.4 0 0 1 .076.016c.052.018.083.06.119.096q.012.075.021.148c.098.097.228.013.334.059a.2.2 0 0 1 .063.036q.023.034-.002.066c-.024.021-.034.056-.067.07a.2.2 0 0 1-.067.003c-.087-.018-.178-.015-.266-.015a.4.4 0 0 1-.104-.017a.3.3 0 0 1-.057-.039");
}

.u9zk21amd {
  fill: var(--svg-color--575800, #575800);
  d: path("M18.474 21.537c.088-.082.202-.084.308-.111q.022.016.019.034q-.006.018-.01.019c-.106.022-.187.177-.317.058");
}

.uaom-pcfw {
  fill: var(--svg-color--fafb03, #fafb03);
  d: path("M15.05 24.816h-.046c-.094-.024-.186.06-.279.005a.17.17 0 0 1-.033-.104a.17.17 0 0 1 .048-.104l.21-.002c.041-.028.079-.031.117.003c.043.073.024.138-.017.202");
}

.ub2l8cbka {
  fill: var(--svg-color--243b66, #243b66);
  d: path("M23.961 31.848h.409a.41.41 0 0 1-.409 0");
}

.ubric5b5h {
  fill: var(--svg-color--cbca24, #cbca24);
  d: path("m18.894 35.16l-.161.007l.005-.146c.092.003.184-.115.274.003z");
}

.ubue6-tza {
  fill: var(--svg-color--141700, #141700);
  d: path("M21.2 20.668c.109-.005.229.013.301-.105l.032.033c.082.388.06.775.014 1.164a.15.15 0 0 1-.063.066a.42.42 0 0 1-.258.021a.2.2 0 0 1-.069-.031c-.069-.095.058-.097.075-.15c-.063-.037-.154-.012-.203-.084a.08.08 0 0 1 .021-.067c.076-.056.168-.042.254-.06c.159-.128.046-.306.08-.457v-.102c.009-.082-.039-.117-.11-.132c-.042-.019-.092-.032-.074-.096");
}

.ubyf6wbhu {
  fill: var(--svg-color--102c06, #102c06);
  d: path("M13.61 36.511c.065.029.099.085.125.149c-.094.003-.171-.023-.23-.099c-.002-.095.048-.081.105-.05");
}

.uc-4ucc-f {
  fill: var(--svg-color--373601, #373601);
  d: path("M16.531 25.437q0 .023.002.042c-.081-.054-.057-.133-.05-.207c.549-.037 1.1-.01 1.648-.016c.064.01.064.057.062.106q-.025.046-.076.033a20 20 0 0 0-1.512-.005a.2.2 0 0 0-.074.047");
}

.ucmhn_f3r {
  fill: var(--svg-color--3d4105, #3d4105);
  d: path("m24.594 21.988l-.005-.142q.15.054.301.106q.026.046-.021.069c-.099.049-.194.06-.275-.033");
}

.ucrzxisnn {
  fill: var(--svg-color--4e500c, #4e500c);
  d: path("m29.8 26.705l-.288.06c.045-.168.191-.123.305-.147c.022.033.037.068-.017.087");
}

.ud5ul0lud {
  fill: var(--svg-color--4c4c0e, #4c4c0e);
  d: path("m30.738 31.18l.303-.059l.003.111q-.156.005-.309.012z");
}

.ufwn_pvsg {
  fill: var(--svg-color--802212, #802212);
  d: path("M28.18 29.993c.102.02.217-.034.306.056a.1.1 0 0 1-.05.043c-.217-.029-.274.072-.256.277c.016.186-.005.375-.011.563a2.2 2.2 0 0 1 .011-.939");
}

.ugetau70r {
  fill: var(--svg-color--837f1f, #837f1f);
  d: path("m11.818 31.384l.058.108c-.023.046-.064.041-.104.036c-.016-.057.023-.098.046-.144");
}

.ugm1u2tlk {
  fill: var(--svg-color--392d02, #392d02);
  d: path("M25.861 29.596c-.101-.287-.084-.31.184-.319c.112-.005.237.051.336-.053a.06.06 0 0 1 .068.013c.06.088.037.196.073.29a.4.4 0 0 1 .006.147a.2.2 0 0 1-.029.063c-.079.039-.142-.049-.219-.029a.4.4 0 0 1-.061-.028c-.094-.048-.202-.015-.3-.048z");
}

.ugnt9eaos {
  fill: var(--svg-color--7a230d, #7a230d);
  d: path("m29.453 24l.053-.053c.119.104.337.14.258.38l-.202-.13c-.076-.016-.101-.076-.123-.137a.08.08 0 0 1 .014-.06");
}

.ugq9e5a6q {
  fill: var(--svg-color--5b2210, #5b2210);
  d: path("m30.827 25.389l-.14-.014c-.043-.104-.211-.104-.209-.244c.224-.061.27.118.349.258");
}

.ugs-vcbvw {
  fill: var(--svg-color--e4e554, #e4e554);
  d: path("m16.837 37.27l-.064-.088c.091.025.24-.115.269.094q-.023.026-.048 0z");
}

.uikcmf-hc {
  fill: var(--svg-color--191b00, #191b00);
  d: path("m30.972 26.561l-.01-.002c-.089-.037-.094-.125-.111-.201l.02.008l.011.005l.007-.013c.004.078.096.119.083.203");
}

.uikr5pb2j {
  fill: var(--svg-color--652206, #652206);
  d: path("M26.437 34.514c-.069.131.064.203.087.307c-.054.045-.085.112-.142.153a.07.07 0 0 1-.067 0c-.056-.064-.068-.146-.099-.22c-.018-.064-.051-.125-.072-.188a.16.16 0 0 1 .007-.098c.048-.063.113-.036.175-.039q.031 0 .061.012c.025.018.045.039.05.073");
}

.ukrdxwrir {
  fill: var(--svg-color--610a00, #610a00);
  d: path("M28.18 28.914c.167-.047.342-.128.45.1c-.159.042-.295-.082-.45-.062q-.01-.017 0-.038");
}

.ul_bz4men {
  fill: var(--svg-color--919104, #919104);
  d: path("M29.648 24.766q.058-.056.115-.115q.011.013.003.025q.022.014.041.032v.062a.2.2 0 0 1-.063.034a.2.2 0 0 1-.07-.012z");
}

.ul4i6uxsl {
  fill: var(--svg-color--636302, #636302);
  d: path("M25 35.23c-.063.063-.115.131-.109.226l-.123-.128c.051-.048.137-.064.142-.154h.048c.023.011.04.029.042.056");
}

.ul7a65mhy {
  fill: var(--svg-color--292d00, #292d00);
  d: path("M14.629 25.338q0 .045-.003.09c-.086-.075-.238-.021-.298-.149l-.003.003c.122-.089.217-.038.304.056");
}

.ulelctn6r {
  fill: var(--svg-color--bcbf00, #bcbf00);
  d: path("m18.401 34.923l-.022.049h-.067z");
}

.ullyp8mqu {
  fill: var(--svg-color--4c2e0b, #4c2e0b);
  d: path("m28.322 22.923l.068-.008c.089.007.11.058.091.135z");
}

.ulxh9f_mi {
  fill: var(--svg-color--c9c611, #c9c611);
  d: path("M19.14 35.66c-.058.069-.118.132-.214.142a.055.055 0 0 1-.058-.026a.14.14 0 0 1-.005-.068q.07-.15.231-.135c.034.019.053.045.046.087");
}

.umemzwbga {
  fill: var(--svg-color--ebef12, #ebef12);
  d: path("m30.07 26.15l-.058-.05c-.046-.037-.093-.076-.087-.146a.3.3 0 0 1 .02-.069c.056-.069.12-.074.193-.033c.03.023.053.05.033.091c-.081.044-.019.161-.101.207");
}

.umh_d_9-r {
  fill: var(--svg-color--353200, #353200);
  d: path("M29.485 33.689c.134-.034.165.063.202.154l-.07.033c.019-.105-.149-.081-.132-.187");
}

.un6_qz8py {
  fill: var(--svg-color--e6e60d, #e6e60d);
  d: path("M28.994 24.756c.009-.135.164-.056.206-.145l.057.005c.03.02.058.041.052.084q-.005.062-.007.125c-.034.024-.07.02-.108.017c-.068-.029-.155-.006-.2-.086");
}

.unlj9mb-i {
  cx: 22px;
  cy: 32.13px;
  rx: 3.478px;
  ry: 3.441px;
}

.unv0ab3ud {
  fill: var(--svg-color--6b1d09, #6b1d09);
  d: path("M24.524 22.05c.057.067.168.015.218.101c-.129.115-.211-.036-.314-.055c-.002-.084.038-.087.096-.046");
}

.unw38ozkn {
  fill: var(--svg-color--565406, #565406);
  d: path("m14.999 28.895l-.003-.001q0 .058-.05.027c-.058-.063-.193-.065-.149-.2z");
}

.upc9jdcxy {
  fill: var(--svg-color--0e2303, #0e2303);
  d: path("M15.959 24.354c-.053.004-.106-.007-.145.045a.12.12 0 0 1-.058.046c-.065.013-.125.008-.161-.06c.01-.128.128-.188.188-.286a.25.25 0 0 1 .116-.068q.034-.009.06.02z");
}

.uq-57ec8i {
  fill: var(--svg-color--e7e858, #e7e858);
  d: path("m28.583 24.565l-.056.145l-.255-.097v.001c.078-.182.193-.123.311-.049");
}

.uq7twrbez {
  fill: var(--svg-color--283b08, #283b08);
  d: path("M15.357 34.42c.11-.227.315-.066.469-.115q-.015.024-.026.046c-.101.094-.23.038-.344.069z");
}

.uqsy2mb_u {
  fill: var(--svg-color--e1e45b, #e1e45b);
  d: path("m28.636 36.15l.058.053c-.072.082-.164.049-.25.044l.041-.039q.077-.028.151-.058");
}

.urpn2e4ay {
  fill: var(--svg-color--fafa00, #fafa00);
  d: path("M30.741 25.935c-.005.048-.013.092-.059.118l-.097-.005q-.065-.014-.081-.075q-.01-.065.043-.105c.08-.019.162-.046.194.067");
}

.urpxzt-zi {
  fill: var(--svg-color--2b3c02, #2b3c02);
  d: path("m18.632 39.27l.003-.043c.112.031.291-.087.31.144c-.119.011-.215-.051-.313-.101");
}

.us6at4f1w {
  fill: var(--svg-color--848404, #848404);
  d: path("m31.24 31.789l.053.05c.009.065.026.135-.042.186c-.086-.076-.065-.155-.011-.236");
}

.usf5fcbjs {
  fill: var(--svg-color--f9f802, #f9f802);
  d: path("m26.583 22.766l-.11.108c-.106.041-.146-.024-.173-.11a.1.1 0 0 1 .036-.07c.069-.04.134-.021.194.02l.055.008q.017.015.011.029q-.008.014-.013.015");
}

.ushvxcbix {
  fill: var(--svg-color--6f1209, #6f1209);
  d: path("M22.638 20.748a.04.04 0 0 1 0-.039a1.1 1.1 0 0 1 .459-.038c.08.062.212-.046.271.084a.13.13 0 0 1-.078.087a.2.2 0 0 1-.084.005c-.186-.051-.404.071-.568-.099");
}

.ut2uc9bpo {
  fill: var(--svg-color--fefe01, #fefe01);
  d: path("m21.656 38.06l.012 3.02c-.145.115-.161.028-.161-.097l-.008-1.137c-.04-.572-.005-1.143-.019-1.714c0-.06.026-.097.087-.105a.1.1 0 0 1 .089.033");
}

.utj48nbuu {
  fill: var(--svg-color--4b4c0d, #4b4c0d);
  d: path("m12.942 26.712l-.054.056l-.146.005l-.151-.104q.021-.006.046-.007c.112-.039.228-.123.305.05");
}

.uu7rtcb9u {
  fill: var(--svg-color--f3f30d, #f3f30d);
  d: path("m17.606 30.46l.059.003c.041.061.014.139.045.202v.149c-.156.047-.077-.133-.156-.162l-.101-.123q.002-.036.033-.05c.038-.019.084.013.12-.019");
}

.uurp0wn-z {
  fill: var(--svg-color--737510, #737510);
  d: path("M26.723 36.715q.013-.022.018-.043c.066-.004.135-.02.182.051c-.07.065-.136.067-.2-.008");
}

.uvpd8wn7c {
  fill: var(--svg-color--231a16, #231a16);
  d: path("m26.338 36.26l-.067-.007c.118-.104.164-.295.363-.304h-.002c.036.044.005.08-.015.118a1 1 0 0 1-.058.079c-.062.059-.121.128-.221.115");
}

.uwis12g3i {
  fill: var(--svg-color--616407, #616407);
  d: path("M14.277 24.71c.092.032.173-.021.257-.038c.046.021.08.048.053.105c-.043.039-.099.056-.148.084q-.132.063-.209-.064l-.006-.034q.026-.028.053-.053");
}

.uwjzk7pyc {
  fill: var(--svg-color--32250d, #32250d);
  d: path("m16.527 24.566l.313-.001q.024.04-.008.073c-.092.078-.19.1-.303.041a.1.1 0 0 1-.002-.113");
}

.ux8y0sbro {
  fill: var(--svg-color--f2f05b, #f2f05b);
  d: path("M19.247 37.548c-.089.003-.188-.065-.259.043q-.074-.005-.147-.007c-.031-.023-.072-.039-.071-.089c.161.005.329-.067.477.053");
}

.uxmf5cxdr {
  fill: var(--svg-color--4c1507, #4c1507);
  d: path("m26.843 39.697l-.002.091l-.205.11c-.031-.033-.028-.064 0-.096z");
}

.uy407tbdz {
  fill: var(--svg-color--272800, #272800);
  d: path("M23.307 40c.112-.049.231-.051.351-.059c.056-.026.102-.031.118.046c-.076.075-.181.005-.263.053c-.067-.026-.156.063-.206-.04");
}

.uyr66hbfk {
  fill: var(--svg-color--545408, #545408);
  d: path("M25.557 35.23c-.106.115.035.322-.152.407c-.077-.109.007-.227-.019-.338c.004-.069-.037-.11-.094-.144c-.052-.032-.111-.06-.147-.113a.06.06 0 0 1 .005-.06l.112-.116q.02-.024.052-.02a3 3 0 0 1 .173.038q.03.014.05.039a.37.37 0 0 1 .07.184c-.001.049-.007.093-.05.123");
}

.uyxo67amk {
  fill: var(--svg-color--253964, #253964);
  d: path("M21.706 33.994c.041-.061.067-.125.051-.201c.09.094.098.168-.051.201");
}

.uz_7ftb8h {
  fill: var(--svg-color--6a6a00, #6a6a00);
  d: path("m28.385 29.786l-.052.046a.1.1 0 0 1-.062.046c-.043.003-.079-.007-.104-.046l.05-.082a.17.17 0 0 1 .168.036");
}

.uzcpmssrf {
  fill: var(--svg-color--051500, #051500);
  d: path("M18.02 21.484q0 .02.004.038c-.024.113-.112.123-.206.122l.002-.016c.016-.115.108-.128.2-.144");
}

.v_8z4inzh {
  fill: var(--svg-color--676629, #676629);
  d: path("m18.53 34.815l.053.002l.001.053l-.053-.002z");
}

.v_srvrnzc {
  fill: var(--svg-color--454518, #454518);
  d: path("M12.634 33.951a.04.04 0 0 0-.003.031c-.109-.053-.151-.13-.099-.246a.32.32 0 0 1 .102.215");
}

.v-8t-60nc {
  fill: var(--svg-color--64490f, #64490f);
  d: path("m18.05 35.03l.227-.013l.017.007a.1.1 0 0 1 .006.051a.06.06 0 0 1-.026.041l-.006.012a.14.14 0 0 1-.045.044l-.013.007a.05.05 0 0 1-.041.024a.1.1 0 0 1-.05-.007z");
}

.v-ssyfzbe {
  fill: var(--svg-color--220, #220);
  d: path("M30.685 30.357c-.101.069-.188.082-.245-.049a.36.36 0 0 1 .245.049");
}

.v-thf5b_p {
  fill: var(--svg-color--5a0a0a, #5a0a0a);
  d: path("M19.758 34.617c.096.037.197.065.214.192c-.086-.049-.193-.073-.214-.192");
}

.v061jg11f {
  fill: var(--svg-color--eaea06, #eaea06);
  d: path("m27.561 23.627l-.193-.142c-.056-.007-.081-.041-.084-.096a.13.13 0 0 1 .065-.08c.061-.031.113.018.171.02c.082.051.134.153.245.159c.031.043.045.089.023.14c-.026.046-.069.069-.12.081c-.06.003-.086-.036-.107-.082");
}

.v0j_1dbpa {
  fill: var(--svg-color--8d1f1e, #8d1f1e);
  d: path("M21.1 35.33c.076-.006.149-.008.211.05q.024.018.013.034q-.008.017-.017.016c-.084-.002-.191.046-.207-.1");
}

.v0pq0cblu {
  fill: var(--svg-color--583909, #583909);
  d: path("M31.956 33.12c-.003.155-.09.28-.154.411q-.042.021-.064-.021a.42.42 0 0 1 .109-.399c.037-.018.075-.02.109.009");
}

.v1s9tnb0t {
  fill: var(--svg-color--636100, #636100);
  d: path("M12.737 29.736c-.058.086-.158.066-.236.099c.02-.145.136-.132.234-.147q.026.017.017.032q-.008.016-.015.016");
}

.v334k4b0f {
  fill: var(--svg-color--fcfb04, #fcfb04);
  d: path("m24.327 21.18l.055-.11a.07.07 0 0 0 .048-.002c.123 0 .25-.015.359.063q-.027.075-.056.146c-.128-.058-.284-.01-.406-.097");
}

.v3iv-92ry {
  fill: var(--svg-color--edeb21, #edeb21);
  d: path("m26.29 38.816l.021-.003q.095-.058.195-.099l.023-.003c.06.037.087.089.063.161l-.081.115c-.065-.014-.126.037-.193.01a.2.2 0 0 1-.107-.081c-.006-.059.038-.076.079-.1");
}

.v3qpysyoo {
  fill: var(--svg-color--4f0e0b, #4f0e0b);
  d: path("M28.08 22.814c.013-.087-.096-.084-.112-.151c.194-.003.316.115.426.252q-.031.04-.068.008z");
}

.v3t9lgb0p {
  fill: var(--svg-color--212200, #212200);
  d: path("M29.1 26.912q-.152.004-.306.004q-.027-.015-.018-.029t.02-.014a.7.7 0 0 1 .304-.053c.033.032.028.061 0 .092");
}

.v466zjb5b {
  fill: var(--svg-color--1b3c0c, #1b3c0c);
  d: path("M15.959 24.354v1.181c-.089 0-.085-.072-.101-.13a4 4 0 0 0-.022-.248a.3.3 0 0 1 .003-.069c.023-.171.031-.34-.048-.502c0-.07-.006-.141.009-.211q.07-.093.159-.021");
}

.v4794dbem {
  fill: var(--svg-color--f6f406, #f6f406);
  d: path("m21.438 39.946l.014.094c-.123.108-.269.048-.404.051a.12.12 0 0 1-.066-.048a.08.08 0 0 1 .026-.074a.6.6 0 0 1 .43-.023");
}

.v47mbxqgr {
  fill: var(--svg-color--1c3409, #1c3409);
  d: path("M13.865 32.21q.77.173 1.542.35q-.027.03-.058.003c-.51-.031-1-.14-1.483-.309q-.026-.014-.018-.028q.008-.017.017-.016");
}

.v51io8bmq {
  fill: var(--svg-color--e6f1fa, #e6f1fa);
  d: path("M24.22 30.662c.05 0 .099.059.094.143s-.067.135-.157.129c-.079-.007-.127-.062-.127-.134c-.001-.085.049-.143.19-.138");
}

.v5hbbzbna {
  fill: var(--svg-color--53531a, #53531a);
  d: path("M20.238 37.733q-.022.016-.016.043c-.077.08-.145.038-.212-.017c-.021-.039-.022-.077.012-.111z");
}

.v5kfh2b_o {
  fill: var(--svg-color--515200, #515200);
  d: path("m13.868 28.05l-.154-.01c-.077-.031-.134-.081-.139-.171a.1.1 0 0 1 .031-.059c.123.043.195.138.262.24");
}

.v5klsm7pz {
  fill: var(--svg-color--f9f60d, #f9f60d);
  d: path("M24.327 21.18q-.19-.03-.378-.063a.3.3 0 0 1-.048-.071a.1.1 0 0 1-.001-.056l.02-.021c.046-.027.092-.058.151-.046c.082.097.256-.007.311.146c.029.061-.007.089-.055.111");
}

.v7r-uztld {
  fill: var(--svg-color--2f301b, #2f301b);
  d: path("M24.372 37.574q0-.024.003-.048c.056-.034.103-.122.183-.038l-.079.058c-.032.03-.054.087-.107.028");
}

.v81l_ybvn {
  fill: var(--svg-color--fefc00, #fefc00);
  d: path("m19.15 40.521l-.209-.049l.005-.019c-.033-.038-.029-.075.002-.112c.133-.041.248-.025.325.104c-.005.047-.017.084-.076.068l-.024-.002z");
}

.v8jrmmiwd {
  fill: var(--svg-color--fdfd03, #fdfd03);
  d: path("m29.494 24.306l-.026-.002c-.048-.063-.135-.105-.13-.204c.028-.044.061-.078.118-.053c.074.023.06.107.105.15z");
}

.v8pdqkekz {
  fill: var(--svg-color--171700, #171700);
  d: path("M18.583 34.868v.043l-.053.007l-.021-.025l.021-.024h.001l.025-.02z");
}

.v8wb-wl2f {
  fill: var(--svg-color--312200, #312200);
  d: path("m28.687 25.576l.06-.051l.194.033l-.052.032z");
}

.v96tr1b6y {
  fill: var(--svg-color--113210, #113210);
  d: path("m17.04 35.438l.044-.005q.06.077.115.153q.024.022.014.039q-.008.018-.017.019c-.113-.023-.13-.119-.156-.206");
}

.v9a9tvbgc {
  fill: var(--svg-color--6b6c10, #6b6c10);
  d: path("M13.354 34.05c.069.082.063.188.092.283c-.171-.028-.111-.146-.095-.248q0-.018.003-.035");
}

.v9o5qobfe {
  fill: var(--svg-color--56560b, #56560b);
  d: path("M30.752 33.946h.022a.6.6 0 0 1-.085.313c-.031-.004-.036-.035-.05-.057a.5.5 0 0 1 .113-.256");
}

.v9svuemiw {
  fill: var(--svg-color--363304, #363304);
  d: path("m25.1 34.29l.132.009c.034.025.056.063.082.098c.06.1.188.048.26.117c.038.13-.041.204-.128.273a.2.2 0 0 1-.069.013a.3.3 0 0 1-.063-.024l-.028-.02q-.024-.023-.046-.047q-.033-.033-.065-.068q-.034-.035-.065-.071a.3.3 0 0 1-.052-.087a.3.3 0 0 1-.013-.069c.001-.049.009-.095.055-.124");
}

.va55kepqn {
  fill: var(--svg-color--e2e862, #e2e862);
  d: path("m20.254 40.771l.228-.007c.036.01.082.007.092.061c-.109-.008-.222.021-.32-.054");
}

.vav2s_f-h {
  fill: var(--svg-color--31140d, #31140d);
  d: path("m16.479 30.814l.005.048c.005.041-.002.082-.007.124q0 .015.004.032c-.058.007-.103-.005-.101-.075q.002-.102.099-.129");
}

.vavn1-qhe {
  fill: var(--svg-color--595508, #595508);
  d: path("m16.589 24.873l-.064-.071q-.007-.047.034-.069c.146-.054.295-.041.444-.015a.16.16 0 0 1 .106.105a.07.07 0 0 1-.021.065a.2.2 0 0 1-.061.035a1 1 0 0 1-.128.036a.2.2 0 0 1-.094-.005c-.038-.01-.075-.025-.115-.033a.2.2 0 0 1-.056-.015a.2.2 0 0 1-.045-.033");
}

.vc1jipopa {
  fill: var(--svg-color--fcf924, #fcf924);
  d: path("M18.07 35.28q.024-.025.052-.051l.022.025l-.022.027v-.002q-.027.031-.052.001");
}

.vcdalsn0x {
  fill: var(--svg-color--666723, #666723);
  d: path("M18.788 34.613a.2.2 0 0 1-.012.047l-.039.004l.003.002q-.02-.016-.015-.031q.003-.019.008-.018l.026-.016z");
}

.vd9w2bchv {
  fill: var(--svg-color--fbfa01, #fbfa01);
  d: path("M16.782 24.917c-.068.038-.041.101-.041.154h-.053q0-.098-.003-.194c.042-.006.085-.018.097.04");
}

.vddlq7hyi {
  fill: var(--svg-color--111206, #111206);
  d: path("m20.02 37.648l-.007.087c-.068.036-.115.007-.149-.055q-.026-.042-.051-.087c.081-.026.137.04.207.055");
}

.vdm2tbc_d {
  fill: var(--svg-color--595908, #595908);
  d: path("M15.819 24.1h-.238c.104-.077.138-.227.279-.265l.065.221c-.026.041-.063.049-.106.044");
}

.ve7_r0rgv {
  fill: var(--svg-color--292900, #292900);
  d: path("m14.499 24.884l.235-.024q.027.024.019.058c-.041.05-.107.01-.151.044l-.122.002q.01-.018.007-.034a.07.07 0 0 0 .012-.046");
}

.vejbrwbul {
  fill: var(--svg-color--e2e206, #e2e206);
  d: path("M27.298 38.26q.03.024.056.048c.043.054.038.106-.001.157l-.25.11l-.056-.158a.1.1 0 0 1 .041-.053q.032-.022.063-.046c.034-.058.091-.06.147-.058");
}

.veq0awb_v {
  fill: var(--svg-color--4a3536, #4a3536);
  d: path("M16.943 34.868a.2.2 0 0 1 .041-.01c.091.075.151.163.112.288a.6.6 0 0 1-.153-.278");
}

.veycj7bfv {
  fill: var(--svg-color--383904, #383904);
  d: path("m32.02 28.863l-.063.009c-.031-.105-.123-.2-.044-.321c.085.09.057.213.107.312");
}

.vf-1qobyc {
  fill: var(--svg-color--474a00, #474a00);
  d: path("M14.677 25.18c.105-.067.188-.007.269.051c-.05.082-.13.044-.199.048z");
}

.vfaa4eb5t {
  fill: var(--svg-color--f6f604, #f6f604);
  d: path("M11.975 29.381a.1.1 0 0 0 .034-.021c.063-.108-.012-.216-.001-.324a.06.06 0 0 1 .013-.063c.13-.204.101-.454.197-.665a.4.4 0 0 1 .063-.312l-.002.005c.04-.102.012-.225.094-.313q.018-.009.01-.026c.038-.094.03-.204.108-.279l.135-.305c-.057-.133 0-.234.091-.328a.2.2 0 0 1 .156-.019q.056.021.084.076c.021.075-.004.143-.033.21c-.053.069-.105.137-.105.229a.4.4 0 0 1-.056.154a.8.8 0 0 0-.131.267c-.033.097-.069.194-.089.296c-.031.137-.083.268-.071.409a.5.5 0 0 1-.063.24a.5.5 0 0 0-.092.217c-.031.087-.024.181-.046.271a.45.45 0 0 0-.015.236a.4.4 0 0 1-.009.072c-.061.125-.058.265-.085.396c-.036.082-.026.195-.153.212c-.128-.048-.082-.158-.087-.252a.4.4 0 0 1 .031-.078c.01-.016.012-.029.003-.048c-.016-.085-.037-.174.019-.257");
}

.vffcvvbew {
  fill: var(--svg-color--051201, #051201);
  d: path("M11.907 31.487q.006.23.008.46c-.106-.118.017-.317-.146-.414l.003-.005a.3.3 0 0 1 .077-.06q.035-.007.058.019");
}

.vfg_izpic {
  fill: var(--svg-color--767613, #767613);
  d: path("M23.795 40.62c-.085.046-.169.077-.25-.009q-.02-.031.014-.044c.091-.034.157.038.236.053");
}

.vfyrixlap {
  fill: var(--svg-color--591717, #591717);
  d: path("M17.97 36.14c.147-.004.186.131.266.212q-.033.039-.07.007c-.078-.063-.175-.11-.196-.219");
}

.vfzyusj7u {
  fill: var(--svg-color--2c2b00, #2c2b00);
  d: path("M17.611 37.433c-.098-.063-.211-.048-.317-.058c-.029-.058-.164.041-.142-.094q.097.006.195.009c.083.034.173.005.257.022c.058.025.13.038.113.129c-.035.018-.071.025-.106-.008");
}

.vg5y1xbcf {
  fill: var(--svg-color--474702, #474702);
  d: path("M15.497 37.07a7 7 0 0 0-.25-.043c.028-.094-.039-.17-.048-.255c.115.113.275.133.41.198q.02.017.02.038q-.003.022-.007.021a.3.3 0 0 1-.125.041");
}

.vgje1nk2f {
  fill: var(--svg-color--f5f705, #f5f705);
  d: path("M26.12 35.434q-.024.001-.046.007l-.052-.007l-.006-.051q-.016-.028.005-.051q.026-.018.051 0q.025.05.048.102");
}

.vioukkblp {
  fill: var(--svg-color--272c00, #272c00);
  d: path("M17.472 39.598c.067.077.222.048.236.19c-.079-.063-.233-.034-.236-.19");
}

.vj1w_ibfh {
  fill: var(--svg-color--202200, #202200);
  d: path("m23.25 20.964l.356.038q.037-.008.06.024c-.132.072-.276.029-.414.042c-.033-.034-.03-.068-.002-.104");
}

.vkadm8btw {
  fill: var(--svg-color--fcf924, #fcf924);
  d: path("M18.03 35.29q.019-.01.039-.017q.011.015.019.03l-.01.032l-.031.012l-.028-.021l-.002-.002z");
}

.vkcg_fbaw {
  fill: var(--svg-color--27420d, #27420d);
  d: path("m14.12 34.811l.002-.044c.033-.134.115-.101.199-.056l.015.018c-.01.084-.089.058-.137.082z");
}

.vkql6bkjg {
  fill: var(--svg-color--ecf021, #ecf021);
  d: path("m19.664 21.13l-.007-.123c.028-.033.064-.036.105-.029c.003.048.021.086.069.104c-.03.098-.1.068-.167.048");
}

.vkwx-g_ja {
  fill: var(--svg-color--192d05, #192d05);
  d: path("m17.202 38.557l-.076-.092c.122 0 .252-.013.27.161z");
}

.vl_swvb1g {
  fill: var(--svg-color--171b00, #171b00);
  d: path("m26.532 39.665l.003-.007q.037-.117.154-.07c-.037.054-.099.062-.157.077");
}

.vlm-txb7z {
  fill: var(--svg-color--f0f215, #f0f215);
  d: path("M18.8 21.386c-.064-.007-.134.002-.171-.068c.067-.093.2.01.266-.087c.04.024.046.063.048.104c-.017.105-.08.082-.143.051");
}

.vlqrb8vxj {
  fill: var(--svg-color--541604, #541604);
  d: path("M26.23 22.785q.046 0 .091.002c.044.039.084.092.154.087q.05.047.101.092c-.152.008-.256-.074-.346-.181");
}

.vnap1qhzd {
  fill: var(--svg-color--e9e910, #e9e910);
  d: path("M15.863 25.379c-.056.01-.118 0-.164.048c-.104.022-.197-.028-.296-.043l-.003-.103c.099-.063.21-.052.318-.055c.041.059.185.02.145.153");
}

.vnd2sdtod {
  fill: var(--svg-color--787700, #787700);
  d: path("M26.634 37.435c-.058-.009-.128.024-.163-.055q.036-.024.067-.049c.028-.028.06-.024.094-.019a.1.1 0 0 1 .06.074z");
}

.vnt45sb6x {
  fill: var(--svg-color--858419, #858419);
  d: path("M30.73 35.19a.07.07 0 0 1 .047-.012c.067.031.086.098.114.156c-.124.029-.136-.065-.161-.144");
}

.vnve8mbft {
  fill: var(--svg-color--585600, #585600);
  d: path("M30.02 29.537c.111.01.22.021.309.101c-.161.141-.231.011-.309-.101");
}

.vnwgael6c {
  fill: var(--svg-color--595705, #595705);
  d: path("M30.74 26.16q.024-.006.049-.007l.06.066l.021.149l-.02-.008c-.083-.041-.092-.123-.11-.2");
}

.vo-4lsbss {
  fill: var(--svg-color--562708, #562708);
  d: path("M30.368 29.431c.127-.072.237-.102.273.092a.6.6 0 0 1-.273-.092");
}

.vo9lhf-cz {
  fill: var(--svg-color--252526, #252526);
  d: path("m25.464 31.691l-.002-5.182q.02-.036.041.002q-.003 2.588-.002 5.178q-.018.036-.037.002");
}

.voa4sabuh {
  fill: var(--svg-color--273b5f, #273b5f);
  d: path("M21.711 30.506a.25.25 0 0 0 .044-.199c.092.09.1.163-.044.199");
}

.vofvbcbcm {
  fill: var(--svg-color--101307, #101307);
  d: path("m16.567 34.67l.049-.006q.05.104.103.207q.001.035-.031.042a.2.2 0 0 0-.043.007z");
}

.voli3j76f {
  fill: var(--svg-color--1f2000, #1f2000);
  d: path("M15.203 24.47c.049-.063.116-.081.192-.072q.055.014.079.067a.1.1 0 0 1-.014.069q-.081.096-.2.056c-.045-.027-.075-.061-.057-.12");
}

.vozai_3hk {
  fill: var(--svg-color--2e2704, #2e2704);
  d: path("m31.751 28.05l.061-.006c.038.151.094.301.087.46c-.12-.128-.122-.296-.148-.454");
}

.vp185jbvu {
  fill: var(--svg-color--e5de4c, #e5de4c);
  d: path("M28.549 27.14c-.079.057-.171.043-.258.054c.065-.111.169-.049.258-.054");
}

.vqel62b9b {
  fill: var(--svg-color--813737, #813737);
  d: path("m16.27 32.672l-.087-.013a.05.05 0 0 1-.005-.048c.058-.106-.053-.227.024-.334q.028-.032.069-.016z");
}

.vrtfp4b0t {
  fill: var(--svg-color--6f240a, #6f240a);
  d: path("M23.973 39.688c-.092.069-.204.083-.313.1c.041-.235.181-.154.313-.1");
}

.vs100fbfq {
  fill: var(--svg-color--f8fa1c, #f8fa1c);
  d: path("M17.14 29.485q.01-.1.022-.197c.336.008.336.008.342.353c.004.086 0 .168 0 .252l.002.002c-.096.049-.195.02-.294.02c-.107-.08-.074-.202-.088-.309c-.001-.041-.01-.084.016-.121");
}

.vtiso1bxy {
  fill: var(--svg-color--e4e24f, #e4e24f);
  d: path("m17.312 25.653l-.005-.115l.201-.001l-.002-.004c.024.058-.005.096-.048.13c-.051.022-.1.024-.146-.01");
}

.vtlr869ho {
  fill: var(--svg-color--6e6d05, #6e6d05);
  d: path("M17.545 25.867c-.116.02-.126-.139-.229-.139l-.004-.075q.07-.013.14-.021c.053.012.078.051.098.097c.013.046.018.092-.005.138");
}

.vux51zb3t {
  fill: var(--svg-color--646307, #646307);
  d: path("m15.543 34.561l.322-.108l.055.005c-.081.198-.217.191-.377.103");
}

.vvj0lig3l {
  fill: var(--svg-color--402700, #402700);
  d: path("M29.336 25.939q-.087.008-.172.013l-.06-.046l.26-.012z");
}

.vvl4rubeb {
  fill: var(--svg-color--1a1a00, #1a1a00);
  d: path("M25.611 35.05v-.021a.2.2 0 0 1 .051-.009a.08.08 0 0 1 .028.048a.1.1 0 0 1-.029.046z");
}

.vw0a-f3mw {
  fill: var(--svg-color--e6e60b, #e6e60b);
  d: path("m25.301 35.18l.003-.062c.067.014.142.018.139.114l-.089.048q-.049-.005-.069-.051q-.013-.029.016-.049");
}

.vw69a4a3p {
  fill: var(--svg-color--ebf4f9, #ebf4f9);
  d: path("M22.14 30.913c-.086.017-.173.042-.224-.062c-.029-.062-.02-.124.029-.163c.081-.062.161-.04.23.028c.038.076.03.141-.035.197");
}

.vwodytnru {
  fill: var(--svg-color--b30c10, #b30c10);
  d: path("M27.514 33.905c-.112-.094.013-.13.046-.188c.016.07.014.137-.046.188");
}

.vwr5zwbwc {
  fill: var(--svg-color--271d00, #271d00);
  d: path("m29.708 29.18l-.093.081l-.104.005c-.012-.059-.06-.056-.104-.059c.006-.072.046-.064.092-.038z");
}

.vx0nyxbfp {
  fill: var(--svg-color--484508, #484508);
  d: path("m13.146 30.46l-.152.063l-.094.033c.03-.163.128-.154.246-.096");
}

.vysvay14y {
  fill: var(--svg-color--555a00, #555a00);
  d: path("M27.936 23.638c-.058.053-.111-.017-.169-.001q0-.075-.002-.148c.069.037.13.081.171.149");
}

.w_2geub3x {
  fill: var(--svg-color--f7f316, #f7f316);
  d: path("M25.848 40.25a.1.1 0 0 0-.041.009c-.054.013-.09-.012-.12-.055a.17.17 0 0 1-.011-.104a.13.13 0 0 1 .061-.082q.088-.044.168-.104c.039-.023.08-.047.128-.021a.3.3 0 0 1 .061.158a.08.08 0 0 1-.056.073c-.065.042-.118.099-.19.126");
}

.w_31h4bvj {
  fill: var(--svg-color--921e08, #921e08);
  d: path("M23.348 20.771c-.056-.102-.188-.017-.251-.101c.123.019.274-.077.363.086c-.033.038-.069.038-.112.015");
}

.w_31u2bwf {
  fill: var(--svg-color--eacd23, #eacd23);
  d: path("M27.05 29.602c.096.02.204-.037.291.039q.025.016.024.033q0 .023-.007.023a.3.3 0 0 1-.085.053a.2.2 0 0 0-.118.095c-.033.072-.094.046-.15.041c-.119-.116-.062-.204.045-.284");
}

.w_dpt3bkv {
  fill: var(--svg-color--223c08, #223c08);
  d: path("M19.561 39.535c.303.01.589.099.876.176c.248.065.524-.014.762.132q0 .023.003.042c-.05.069-.12.066-.192.06c-.115-.039-.238-.024-.356-.051c-.086-.031-.178-.031-.267-.046c-.064-.01-.125-.036-.19-.035c-.216-.003-.408-.113-.621-.129a.23.23 0 0 1-.129-.098c.012-.077.051-.089.114-.051");
}

.w-1_kvnza {
  fill: var(--svg-color--050503, #050503);
  d: path("M22.631 20.668q.005.02.007.041a.1.1 0 0 1 .024.063c-.005.044-.013.09-.013.137q.003.053.002.107q.003.23 0 .456v.069q0 .048.003.1c.01.045.043.079.053.123q0 .038-.014.072q-.01.039-.026.076c-.024.616-.011 1.231-.006 1.848a.14.14 0 0 1-.021.089c-.046.026-.09.024-.131-.014a.27.27 0 0 1-.046-.136c-.002-1.029-.019-2.059.01-3.088c.017-.045.032-.113.092-.098c.07.018.027.109.066.155");
}

.w-5x4o20i {
  fill: var(--svg-color--807f00, #807f00);
  d: path("M23.25 20.964q.003.052.002.104c-.074.009-.153.023-.161-.09a.08.08 0 0 1 .049-.046l.104-.009q.008.021.006.041");
}

.w-6vtijmv {
  fill: var(--svg-color--f9f805, #f9f805);
  d: path("m14.568 28.826l.118-.112q.055.002.11.007c.034.082.113.13.161.202c0 .07-.053.094-.104.118c-.046.012-.089-.002-.132-.018a.3.3 0 0 1-.059-.033c-.049-.043-.101-.086-.094-.164");
}

.w-7ew3b6x {
  fill: var(--svg-color--dbe7f4, #dbe7f4);
  d: path("M20.478 31.15c.019.104-.006.189-.118.219c-.063.019-.111-.02-.146-.072c-.065-.1.017-.154.067-.219c.092-.047.16-.031.197.072");
}

.w-jl0-b_p {
  fill: var(--svg-color--72760d, #72760d);
  d: path("m18.05 37.477l-.188.006c-.028-.021-.055-.038-.063-.072l.013-.031l.239.011q.076.044-.001.086");
}

.w-yms8cxe {
  fill: var(--svg-color--262700, #262700);
  d: path("M28.22 26.365c.141-.08.307-.061.457-.11l-.066.097c-.072.064-.167.006-.244.043l-.146.005z");
}

.w0ctqibfl {
  fill: var(--svg-color--2d2c00, #2d2c00);
  d: path("M28.992 25.338v.049c-.102-.003-.208.004-.299-.059c.028-.088.099-.023.148-.041c.043.041.117-.01.151.051");
}

.w0u5macsn {
  fill: var(--svg-color--444505, #444505);
  d: path("M13.692 34.926a.2.2 0 0 0-.028.029l-.053.016c.025-.093-.063-.18-.01-.273c.128.037.183.103.091.228");
}

.w0y2r5r1i {
  fill: var(--svg-color--383803, #383803);
  d: path("M26.28 30.813c.06.01.119.011.112-.074c-.007-.072.034-.075.087-.069c.14.099.262.104.355-.063c.141-.006.115.161.21.204c0 .019.002.034.004.053a3 3 0 0 1-.771-.002q0-.024.003-.049");
}

.w1g-a8kpj {
  fill: var(--svg-color--203e10, #203e10);
  d: path("m14.938 23.534l.058.002l-.012.133l-.197.069l-.048-.049c.065-.056.104-.141.199-.155");
}

.w2xbo-boh {
  fill: var(--svg-color--e8e809, #e8e809);
  d: path("m28.17 29.832l.112.015c.085.051.186.003.274.038l.079.001l.205.056l-.048.142c-.049.056-.087-.011-.131-.01c-.063-.003-.127.007-.189-.01c-.094-.038-.212.023-.292-.07c-.025-.054-.11-.101-.01-.162");
}

.w31p75p-u {
  fill: var(--svg-color--122a01, #122a01);
  d: path("m15.351 31.43l-.099.039a1.3 1.3 0 0 1-.414-.106a.54.54 0 0 1 .513.067");
}

.w3e3bqb5y {
  fill: var(--svg-color--f5f505, #f5f505);
  d: path("M31.2 29.29c-.14.081.07.22-.052.306c-.032.026-.068.026-.108.01a.3.3 0 0 1-.092-.164c-.007-.156-.097-.301-.072-.462c.01-.099-.039-.18-.072-.267a.5.5 0 0 1-.023-.138c0-.065.012-.13.023-.194c.019-.089-.034.031-.043-.008c-.073-.038-.075-.112-.092-.178a.7.7 0 0 0-.079-.227c-.048-.082-.065-.175-.092-.264c-.02-.063-.039-.128-.069-.19a4 4 0 0 1-.142-.337l-.078-.205a3 3 0 0 0-.086-.193q-.04-.081-.085-.161a.6.6 0 0 0-.12-.183c-.046-.055-.079-.113-.074-.189c.023-.085.041-.174.159-.169q.06.017.071.077l.205.403c.003.065.041.116.072.17q.04.104.101.201q.042.108.104.207c.046.077.048.173.101.246c.052.081.02.206.133.254q.002.03.002.061c-.011.102.041.18.104.25l.001.047c.026.107.033.223.103.316l-.002-.005c.02.143.015.291.106.415l-.003-.004c.023.141.02.289.104.415q-.005.082-.005.16");
}

.w3lcpt_ax {
  fill: var(--svg-color--202300, #202300);
  d: path("m20.751 40.705l.094-.046l.145.014l-.051.048c-.065.022-.13.047-.188-.016");
}

.w4011ucbw {
  fill: var(--svg-color--57471c, #57471c);
  d: path("M17.431 35.07c-.104-.125.067-.157.08-.243c.031-.041.069-.041.11-.015c.038.051.038.105.017.163c-.05.074-.104.14-.207.095");
}

.w472smdbu {
  fill: var(--svg-color--f3f11a, #f3f11a);
  d: path("m27.753 23.743l-.042-.005c-.021-.015-.052-.02-.052-.055c.025-.039.064-.047.107-.047c.058-.067.113.015.169.001l.04.052c-.046.133-.14.069-.222.054");
}

.w4geblv-c {
  fill: var(--svg-color--49190a, #49190a);
  d: path("M28.677 38.438c.132-.135.255-.281.423-.375c-.06.22-.235.328-.414.436a.06.06 0 0 1-.015-.039q.002-.024.006-.022");
}

.w5dywxbbr {
  fill: var(--svg-color--591808, #591808);
  d: path("m26.684 21.85l-.712-.329c-.002-.037.011-.059.054-.046c.242.063.459.173.659.319q.02.018.014.038q-.009.017-.015.018");
}

.w5uy2hbpa {
  fill: var(--svg-color--cdcec7, #cdcec7);
  d: path("m28.13 32.1l.038-.008c.089.084.074.174.013.266l-.051.038z");
}

.w5w07bb_c {
  fill: var(--svg-color--faf91d, #faf91d);
  d: path("M26.33 25.646c-.12-.118-.271-.036-.406-.059l-.005-.069c.183-.022.364-.054.544.013c-.008.079-.05.122-.133.115");
}

.w5wl4ym6f {
  fill: var(--svg-color--262500, #262500);
  d: path("m28.626 29.803l.007.083c-.024.036-.061.043-.103.042c-.075-.016-.154-.021-.212-.083c-.001-.046.01-.077.066-.059q.122.01.242.017");
}

.w66f4abwa {
  fill: var(--svg-color--3f4005, #3f4005);
  d: path("M25.23 35.792c.033-.032.07-.054.118-.046q.025.069.046.14c-.091.034-.125-.034-.164-.094");
}

.w6l4zrbmk {
  fill: var(--svg-color--171800, #171800);
  d: path("M13.719 36.26q.021.016.041.034c-.031.01-.056.012-.041-.034");
}

.w7ompabjh {
  fill: var(--svg-color--fcfc02, #fcfc02);
  d: path("m14.629 25.338l-.304-.057a.9.9 0 0 0-.407-.1l-.004-.005c-.146-.058-.33.07-.453-.093l.146-.02c.242-.042.48.03.719.016a.26.26 0 0 1 .123.015c.061.021.125.022.188.036a.2.2 0 0 1 .061.024c.038.031.064.067.05.12c-.05.006-.094.016-.119.064");
}

.w7pxklhzn {
  fill: var(--svg-color--fdfd01, #fdfd01);
  d: path("m17.652 21.948l.058-.026c.046-.059.123-.068.179-.113a.6.6 0 0 0 .161-.094a.3.3 0 0 1 .056-.029a2 2 0 0 0 .168-.088c.067-.034.128-.085.211-.088c.108.018.197-.045.292-.078c.092-.021.158-.088.233-.138c.092-.034.189-.044.283-.067c.095-.021.197.002.287-.049a.5.5 0 0 1 .103-.045a.6.6 0 0 1 .261.007c.091.028.176-.04.267-.012c0 0 .012-.005.01-.007l-.007-.024c.012-.038.041-.056.077-.067c.05-.008.099-.007.148-.007c.063-.003.121.011.183.024a.6.6 0 0 0 .245-.075a.5.5 0 0 1 .108-.048c.08-.022.164-.021.246-.021c.076.006.148.009.199.076c-.002.173.051.35-.031.52c-.148.037-.315-.039-.449.078a.5.5 0 0 1-.111.053c-.104.031-.211.025-.317.027c-.094.004-.19-.021-.279.029q-.03.021-.063.036c-.065.027-.135.038-.202.063c-.092.022-.178.067-.267.1c-.07.021-.143.026-.215.033q-.137.028-.273.067c-.106.031-.217.058-.304.139a.4.4 0 0 1-.122.059c-.11.004-.22.004-.301.096a.4.4 0 0 1-.128.037a.4.4 0 0 0-.176.074a1 1 0 0 0-.189.127a.14.14 0 0 1-.063.022a.36.36 0 0 0-.176.06c-.031.027-.058.061-.09.089c-.063.036-.13.065-.196.099a.3.3 0 0 0-.154.094a.2.2 0 0 1-.061.021c-.082.001-.137.061-.199.104a.7.7 0 0 0-.188.135c-.05.039-.093.09-.16.105c-.097-.021-.095.097-.162.116a.7.7 0 0 0-.188.173a.2.2 0 0 1-.058.032c-.072.019-.108.077-.148.134a.25.25 0 0 1-.102.077c-.039.015-.082.018-.115.049q-.033.033-.07.064c-.079.07-.142.156-.212.233l-.199.265a.2.2 0 0 1-.05.046c-.059.035-.126.055-.187.084a3 3 0 0 0-.285.133c-.058.02-.118.025-.179.031c-.076.004-.144.038-.216.057c-.09.024-.181.057-.258-.028a.34.34 0 0 1 .096-.2c.092-.112.183-.225.309-.3c.061-.145.252-.197.264-.376a1 1 0 0 1 .092-.064c.024-.017.034-.043.048-.067c.13-.024.207-.112.268-.219c.12-.07.199-.186.304-.27c.096-.001.158-.053.202-.133l.064-.062a.1.1 0 0 1 .043-.042c.039-.065.11-.083.171-.117c.069-.073.151-.126.233-.183q.267-.203.578-.325c.025-.056.071-.082.129-.091l.072-.106q.016 0 .027-.003c.096-.014.153-.125.264-.096a.44.44 0 0 1 .211-.11");
}

.w8lkwybgy {
  fill: var(--svg-color--7d7c17, #7d7c17);
  d: path("M14.379 24.965c.025-.041.068-.036.107-.036a.1.1 0 0 1 .031.054a.17.17 0 0 1-.014.096a.13.13 0 0 1-.078.053c-.038-.009-.081-.007-.101-.051z");
}

.w8ll72bso {
  fill: var(--svg-color--282720, #282720);
  d: path("M24.89 33.896c.048-.117.099-.233.206-.313c.008.154-.047.27-.206.313");
}

.w8ydt5b5o {
  fill: var(--svg-color--ece1c2, #ece1c2);
  d: path("M21.261 25.639q.099.136-.014.262z");
}

.w9h-fobrh {
  fill: var(--svg-color--fafc01, #fafc01);
  d: path("M19.715 40.51c.105 0 .211-.008.305.053c.034.069.005.12-.052.161c-.109.01-.207-.034-.307-.069c-.051-.075-.015-.116.054-.145");
}

.w9ofi8vgl {
  fill: var(--svg-color--6a6a09, #6a6a09);
  d: path("m12.163 31.848l-.046.051c-.07-.105-.052-.209.004-.314c.085.075.046.172.042.263");
}

.wbx7msbws {
  fill: var(--svg-color--fcfd01, #fcfd01);
  d: path("M24.675 40.41q.03 0 .059-.003c.122.003.091.068.055.135c-.063.039-.154-.014-.204.068q-.051 0-.102-.003c-.043-.043-.048-.091-.023-.143c.057-.072.141-.042.215-.054");
}

.wcqd_qhbj {
  fill: var(--svg-color--e3e21f, #e3e21f);
  d: path("M25.417 35.936c-.027.046-.072.061-.121.065a.7.7 0 0 1-.204-.204q.033-.044.089-.047a.3.3 0 0 1 .065.013c.063.028.086.102.151.123z");
}

.wdpt3c5kt {
  fill: var(--svg-color--edee09, #edee09);
  d: path("M16.998 39.621q-.079-.047-.158-.091c-.026-.101.017-.166.099-.214c.127-.003.206.101.313.142c.05.041.091.095.163.099a.2.2 0 0 1 .061.023a.6.6 0 0 0 .286.147a.9.9 0 0 1 .381.186c.053.077.178.071.208.176c-.028.117-.132.084-.208.108c-.19-.033-.343-.161-.529-.207a.1.1 0 0 0-.018-.043c-.084-.049-.185-.065-.26-.128a.19.19 0 0 1-.149-.065c-.051-.063-.16-.043-.189-.133");
}

.wdq3_zv-b {
  fill: var(--svg-color--502727, #502727);
  d: path("M17.498 35.611c.109.066.213.135.22.281c-.114-.06-.232-.121-.22-.281");
}

.we50plbap {
  fill: var(--svg-color--492e2b, #492e2b);
  d: path("m23.663 35.02l-.01.103q-.047.01-.097.018l-.064-.043z");
}

.we7xwjknp {
  fill: var(--svg-color--292700, #292700);
  d: path("M20.688 40.04h-.154c-.083-.046-.175 0-.257-.034c-.023-.045 0-.071.034-.096a.3.3 0 0 1 .074-.024a.46.46 0 0 1 .236.023c.051.029.082.068.067.131");
}

.weqer3buy {
  fill: var(--svg-color--303100, #303100);
  d: path("M12.326 32.972c.067.07.072.164.101.25c-.144-.04-.122-.146-.101-.25");
}

.weu7i0bss {
  fill: var(--svg-color--e2db5d, #e2db5d);
  d: path("M28.975 25.548a.1.1 0 0 0-.034.011c-.064.001-.129.006-.192-.006q-.037-.027-.015-.065q.125.002.254.002q-.008.028-.013.058");
}

.wfgsj28zs {
  fill: var(--svg-color--5b5a00, #5b5a00);
  d: path("m14.734 27.29l.002-.057l.222.099c-.094.086-.154-.003-.224-.042");
}

.wfr7youms {
  fill: var(--svg-color--122602, #122602);
  d: path("m17.4 22.963l.014.063c-.017.093-.087.103-.161.104l-.005-.059a.2.2 0 0 1 .01-.045c.063.015.096-.041.142-.063");
}

.wftbadbpk {
  fill: var(--svg-color--4c4900, #4c4900);
  d: path("M20.18 21.02c.039.006.089-.004.105.054l-.076.048c-.063.039-.128.045-.19-.005l.003-.043z");
}

.wfy7or33k {
  fill: var(--svg-color--7c2414, #7c2414);
  d: path("m24.788 22.17l.099-.002l.141.048l.009.038c-.128.102-.183-.007-.249-.084");
}

.wgx8aab0s {
  fill: var(--svg-color--572a01, #572a01);
  d: path("m26.02 40.11l.067-.055c.036-.063.084-.094.156-.056q.018.037-.012.07c-.026.113-.133.071-.202.101q-.025-.017-.02-.038q.004-.022.011-.022");
}

.wh8wlgbvx {
  fill: var(--svg-color--330e02, #330e02);
  d: path("m27.457 29.589l-.005-.056c-.036-.05-.08-.076-.145-.06c-.079.003-.143-.017-.171-.099c.105-.122.253-.129.373-.072c.086.041.048.168.017.256c-.005.017-.044.02-.069.031");
}

.wi5m5fb6h {
  fill: var(--svg-color--830000, #830000);
  d: path("m24.07 37.904l.114-.012c.089-.031.177-.065.272-.024l.028.031c-.196.104-.404.104-.618.086q-.018-.033.01-.056c.065-.02.134.01.194-.025");
}

.wk-4q6blg {
  fill: var(--svg-color--b4b018, #b4b018);
  d: path("M18.514 36.09c-.02-.11.063-.156.133-.212c.029-.014.06-.025.092-.015a.18.18 0 0 1 .104.072c-.063.101-.129.197-.261.215q-.029.025-.058.002a.07.07 0 0 1-.01-.062");
}

.wknbcbbbu {
  fill: var(--svg-color--e9eb9b, #e9eb9b);
  d: path("m31.09 31.836l-.001-.298l.016-.056c.071.122.078.241-.015.354");
}

.wknbhetjf {
  fill: var(--svg-color--003500, #003500);
  d: path("m11.975 29.381l-.019.259c-.095-.094-.054-.176.019-.259");
}

.wkq7sfuez {
  fill: var(--svg-color--fcfa1f, #fcfa1f);
  d: path("m18.642 34.705l-.002-.073q.01-.03.042-.023q.017.016.011.031q-.003.018-.008.017l.003.063a.2.2 0 0 1-.046-.015");
}

.wkv1r9bhb {
  fill: var(--svg-color--f5f604, #f5f604);
  d: path("M31.15 35.463c.046.033.064.074.038.129c-.063.029-.031.266-.19.086a1 1 0 0 0-.089-.173a.6.6 0 0 1-.072-.144a.5.5 0 0 0-.089-.166c-.076-.097-.183-.168-.243-.277a.2.2 0 0 1-.019-.071c-.002-.063.012-.121.077-.152c.112-.021.171.069.25.118a.24.24 0 0 1 .102.132c.009.085.086.126.124.192c.068.096.068.218.111.326");
}

.wlw7ls07h {
  fill: var(--svg-color--dedd60, #dedd60);
  d: path("M18.12 34.666c.128-.046.012-.1.005-.149l.101-.012c-.036.053.095.216-.106.161");
}

.wmyhjuu9w {
  fill: var(--svg-color--5b5f1f, #5b5f1f);
  d: path("M31.2 29.13c-.176-.104-.13-.263-.104-.415c.08.126.088.27.104.415");
}

.wngqhvb-g {
  fill: var(--svg-color--161600, #161600);
  d: path("m17.912 35.457l.059-.017l-.005.034v.061z");
}

.wnlp91b2y {
  fill: var(--svg-color--616100, #616100);
  d: path("M17.638 25.693a.1.1 0 0 0-.026.032c-.023.046-.058.046-.099.03l-.062-.124l.055-.099c.059.042.13.073.132.161");
}

.wo_fkybrs {
  fill: var(--svg-color--102d01, #102d01);
  d: path("M16.02 38.978a.35.35 0 0 1 .169.148c-.104.003-.157-.05-.169-.148");
}

.woe55bbiv {
  fill: var(--svg-color--661803, #661803);
  d: path("M29.403 32.402c.124-.068.265-.057.398-.09c-.043.174-.182.135-.301.137c-.025-.027-.077-.002-.097-.047");
}

.wok0c0b-k {
  fill: var(--svg-color--f2f306, #f2f306);
  d: path("m29.964 24.973l.063-.005c.084.002.168-.001.202.101q.029.034 0 .068c-.09.06-.176.023-.261-.013c-.035-.02-.062-.046-.071-.087c.001-.043.016-.072.067-.064");
}

.wpm170fmc {
  fill: var(--svg-color--540000, #540000);
  d: path("m28.79 27.12l-.109.102l-.098-.006l-.001-.069c.068-.01.14-.017.208-.027");
}

.wpr1gljnf {
  fill: var(--svg-color--474a00, #474a00);
  d: path("m21.452 20.977l-.024-.008l-.024.006l-.205-.013a.05.05 0 0 1-.023-.051q.01-.03.043-.033l.231-.018z");
}

.wpvgr1piu {
  fill: var(--svg-color--fbfb07, #fbfb07);
  d: path("M17.547 25.942q-.022.026-.048.053a.56.56 0 0 1-.35.005c-.023-.09.039-.159.059-.236l.107-.035c.14-.042.181.076.25.151q.011.036-.018.062");
}

.wpyurgb3x {
  fill: var(--svg-color--f4f355, #f4f355);
  d: path("m25.15 37.545l-.056-.017c.1-.077.213-.036.321-.036c-.077.066-.178.026-.265.053");
}

.wq8gtkbwi {
  fill: var(--svg-color--595507, #595507);
  d: path("m28.746 33.34l.224.202c-.108-.031-.241-.035-.224-.202");
}

.wqoyhfygr {
  fill: var(--svg-color--4b0c02, #4b0c02);
  d: path("M21.19 25.396c-.063-.078-.188-.157.004-.231l-.002.024q.025.016.018.043a.06.06 0 0 0 .01.049a.2.2 0 0 1 .009.053a.2.2 0 0 1-.024.048z");
}

.wqr7nibuk {
  fill: var(--svg-color--1a4610, #1a4610);
  d: path("M12.28 27.997c.021.112-.055.204-.063.312c-.074-.124-.076-.233.063-.312");
}

.wqwr0bbfy {
  fill: var(--svg-color--9a9b9b, #9a9b9b);
  d: path("M28.17 29.733c-.112-.178-.023-.372-.048-.556q.029-.027.053.005q-.005.275-.005.551");
}

.wr5hgxb5c {
  fill: var(--svg-color--ebea8d, #ebea8d);
  d: path("M16.16 23.676c.013.051.051.07.099.077c-.074.043-.146.074-.178-.046l.01-.017a.07.07 0 0 1 .069-.014");
}

.wsjhh-qoi {
  fill: var(--svg-color--f7f704, #f7f704);
  d: path("M25.715 35.12a.1.1 0 0 0-.008-.044q-.018-.018-.01-.033t.015-.015c.056.007.08.05.104.092l-.004.007q-.022.027-.049.005a.2.2 0 0 0-.048-.012");
}

.wtt98llps {
  fill: var(--svg-color--292a00, #292a00);
  d: path("M29.821 25.673c.017-.08-.096-.069-.101-.133l.291.06c.01.082-.053.097-.108.119c-.036.004-.072 0-.082-.046");
}

.wui37ebut {
  fill: var(--svg-color--83341b, #83341b);
  d: path("M25.352 39.27c-.061.097-.168.05-.248.081c.024-.177.154-.112.257-.114q-.007.017-.009.033");
}

.wuxnd1bpv {
  fill: var(--svg-color--6b680c, #6b680c);
  d: path("M31.3 31.34c-.116-.127-.001-.283-.051-.418c-.007-.082.03-.089.089-.049l.023-.004c-.056.154.049.326-.061.471");
}

.wv52sobxj {
  fill: var(--svg-color--d4d49b, #d4d49b);
  d: path("m25.866 35.28l-.002-.045q.026-.007.051-.004a.1.1 0 0 1-.005.051l-.021-.002z");
}

.wwlgwdbxi {
  fill: var(--svg-color--e2e258, #e2e258);
  d: path("M28.626 29.803c.081.032.291-.131.212.141v-.002c-.079.033-.146.016-.21-.034q-.034-.053-.002-.105");
}

.wx39_sgmh {
  fill: var(--svg-color--797700, #797700);
  d: path("m18.737 34.664l-.051.053l.001.002q-.021-.017-.02-.036q.003-.02.008-.021q.016-.005.031-.012q.018.007.031.014");
}

.wx5vfffgy {
  fill: var(--svg-color--fdfd02, #fdfd02);
  d: path("m27.334 22.463l.031.063c.082-.002.142.054.211.085c.046.043.068.117.15.105c.081.051.125.153.238.154l.011.007c.042.061.059.149.16.146c.124.123.291.2.395.349c.144.073.209.249.382.286a.7.7 0 0 1 .276.26c.044.146.151.243.266.332a.3.3 0 0 1 .04.056q.136.171.27.345c-.005.066-.045.105-.102.13a.13.13 0 0 1-.067.002c-.112-.05-.219-.106-.346-.106q-.035 0-.067-.002a.4.4 0 0 1-.135-.033c-.07-.059-.163-.077-.241-.121a.3.3 0 0 1-.055-.043c-.049-.046-.096-.096-.143-.142a7 7 0 0 0-.211-.21q-.113-.116-.227-.23l-.064-.064q-.045-.035-.097-.065a1 1 0 0 1-.136-.119a.4.4 0 0 0-.151-.105a.7.7 0 0 1-.234-.174c-.053-.053-.104-.107-.175-.135a.4.4 0 0 1-.138-.089a.32.32 0 0 0-.158-.11c-.084-.031-.157-.08-.231-.128c-.069-.052-.128-.115-.214-.14l-.061-.03a.7.7 0 0 0-.199-.118c-.065-.043-.14-.072-.21-.105l-.212-.104c-.079-.04-.156-.081-.245-.096a.4.4 0 0 1-.098-.036a.35.35 0 0 0-.28-.086a.2.2 0 0 1-.064-.016c-.048-.028-.086-.069-.133-.096a1 1 0 0 0-.214-.086a3 3 0 0 0-.31-.075c-.099-.009-.198-.002-.296-.029c-.07-.024-.128-.072-.195-.103c-.077-.034-.164-.049-.236-.094c-.103-.059-.216-.029-.324-.035c-.094-.002-.189.003-.279-.025a1 1 0 0 1-.115-.048c-.152-.075-.347.036-.483-.11a3 3 0 0 1 .002-.491c.049-.07.123-.073.197-.079c.084-.001.168-.003.248.025c.067.027.125.084.205.077c.125.001.247.008.368-.014a.2.2 0 0 1 .074.004a.55.55 0 0 0 .284.063a.8.8 0 0 1 .343.067c.128.059.299.008.396.149l.005.005c.117.065.253.077.373.135c.098.005.185.061.283.058c.069-.01.137-.013.181.054c.041.079.117.096.194.112q.332.156.667.309c.063.045.117.107.205.103c.074.054.146.121.25.104c.057.024.118.041.149.104l.06.056q.096.082.205.145z");
}

.wxy3wuarw {
  fill: var(--svg-color--4f4f4f, #4f4f4f);
  d: path("M21.3 32.619q.002.023.007.047l-.012 1.237a3.6 3.6 0 0 1 .005-1.284");
}

.wy60pt04s {
  fill: var(--svg-color--651f12, #651f12);
  d: path("M22.381 20.567q-.022-.028-.046-.053c.24-.108.283-.087.296.153c-.063-.005-.003-.132-.102-.102a.12.12 0 0 1-.091.031a.2.2 0 0 1-.057-.029");
}

.wzue76btq {
  fill: var(--svg-color--5f5b07, #5f5b07);
  d: path("M25.919 24.877c-.017-.034-.101-.041-.043-.104c.142-.12.303-.079.46-.052q.062.027.071.091a.13.13 0 0 1-.026.065c-.105-.032-.108.122-.202.114c-.06.005-.101-.038-.151-.055l-.058-.022q-.027-.018-.051-.037");
}

.x_90pw7gj {
  fill: var(--svg-color--767506, #767506);
  d: path("M28.79 24.457c-.056.068-.131.056-.205.047a.07.07 0 0 1-.029-.051a.07.07 0 0 1 .026-.053l.053-.123z");
}

.x--3r0bog {
  fill: var(--svg-color--474700, #474700);
  d: path("M20.321 40.658c-.026-.038-.1-.028-.095-.096l.209.007l.051.09l-.057.014z");
}

.x--rsv84v {
  fill: var(--svg-color--57591c, #57591c);
  d: path("M25.07 35.638a.36.36 0 0 0 .194-.154q.012-.003.026-.002l.001.087q-.046.06-.095.119z");
}

.x-acaqbpt {
  fill: var(--svg-color--9b2824, #9b2824);
  d: path("M17.08 25.12c-.061-.077-.029-.166-.029-.25l.039-.001z");
}

.x-b_aqbjr {
  fill: var(--svg-color--3e4000, #3e4000);
  d: path("M25.568 36.15c-.037-.042-.085-.082-.059-.149l.217-.049l-.033.104c-.021.057-.048.108-.125.094");
}

.x-gul3pnt {
  fill: var(--svg-color--dfde14, #dfde14);
  d: path("m17.05 24.609l-.004.154q-.253 0-.509.004l.001-.099l.303-.046c.079.13.137-.047.209-.013");
}

.x-gx8nn5g {
  fill: var(--svg-color--323920, #323920);
  d: path("m31.912 31.949l-.055-.064l.019-.245q.025.003.049.002a.56.56 0 0 1-.001.3z");
}

.x-tmulyom {
  fill: var(--svg-color--361f09, #361f09);
  d: path("m28.23 26.2l-.066-.006c-.095-.267-.031-.541-.037-.813a.1.1 0 0 1 .061-.027a.2.2 0 0 1 .07.008c.064.021.144.017.185.089a.08.08 0 0 1-.026.063c-.21.125-.23.217-.127.604c.003.045-.028.065-.06.082");
}

.x-u73lnda {
  fill: var(--svg-color--383807, #383807);
  d: path("M31.19 32.416c-.065-.107-.072-.199.06-.262l-.011.153c-.024.033.002.089-.049.109");
}

.x01aszb4d {
  fill: var(--svg-color--46493c, #46493c);
  d: path("m27.312 34.977l-.057-.006c.025-.068.038-.145.135-.148c.006.069-.013.122-.078.154");
}

.x0f513bbh {
  fill: var(--svg-color--696700, #696700);
  d: path("M26.939 26.14v-.075c.036-.067.094-.069.156-.049c.118.02.24-.017.355.022q.03.051.057.102z");
}

.x0xykcc_s {
  fill: var(--svg-color--4c4c4b, #4c4c4b);
  d: path("m16.13 32.1l.038.005c.054.045.051.103.036.163c-.024.084.026.178-.038.257a1.1 1.1 0 0 1-.036-.425");
}

.x0zccvbde {
  fill: var(--svg-color--eceb49, #eceb49);
  d: path("M28.385 36.16c-.094.063-.201.043-.305.053c.087-.109.201-.053.305-.053");
}

.x10zodbal {
  fill: var(--svg-color--2c4d0b, #2c4d0b);
  d: path("m14.794 35.743l-.069-.009l.174-.092l.142-.012c.011.246-.121.172-.247.113");
}

.x1pyx3bkp {
  fill: var(--svg-color--f5f350, #f5f350);
  d: path("M21.819 38.1c-.002.857.003 1.716-.01 2.574c-.004.225.049.335.292.296c.058-.009.119 0 .178.001c-.164.079-.34.014-.51.038a.2.2 0 0 1-.058-.079c-.049-.727-.013-1.451-.02-2.176c-.001-.212-.041-.428.041-.635q.037-.047.087-.019");
}

.x20xusb3x {
  fill: var(--svg-color--3e3908, #3e3908);
  d: path("M32.07 32.2c-.01.169.058.349-.052.508l-.036-.017c-.125-.166-.035-.324.02-.483q.031-.032.068-.008");
}

.x3_6ohb1j {
  fill: var(--svg-color--f8f807, #f8f807);
  d: path("M24.426 34.913q.228-.175.456-.354q.048.002.085.032c.04.033.076.071.115.104c.039.037.089.059.137.081a.2.2 0 0 1 .051.044a.2.2 0 0 1 .01.069a.18.18 0 0 1-.116.123c-.086.024-.175.043-.245.103c-.066.049-.127.105-.216.105a.2.2 0 0 1-.068-.016c-.074-.041-.129-.102-.185-.162c-.025-.04-.055-.08-.024-.129");
}

.x3cyd6odr {
  fill: var(--svg-color--7e1802, #7e1802);
  d: path("M21.721 24.2c.074.008.176-.041.192.092q-.076.023-.149.048a2 2 0 0 1-.043-.14");
}

.x40z9yb-z {
  fill: var(--svg-color--1f1e1f, #1f1e1f);
  d: path("M16.13 32.1v-3.228q.056-.011.077.041c.038.751.01 1.502.015 2.253c.002.298.021.597-.013.896q-.022.053-.079.038");
}

.x481yf02g {
  fill: var(--svg-color--a8a602, #a8a602);
  d: path("M21.73 38.1q.016.001.033.01l-.014 2.863c-.012-.021-.033-.043-.033-.064q.006-1.407.014-2.809");
}

.x49989bew {
  fill: var(--svg-color--a40605, #a40605);
  d: path("m16.481 30.15l.043.003q.046.002.076.039q.015.028.016.058a.1.1 0 0 1-.024.055c-.012.089-.01.183-.069.26c-.087-.13-.021-.277-.042-.415");
}

.x4pipacvd {
  fill: var(--svg-color--2b2400, #2b2400);
  d: path("m29.357 27.03l-.059-.038c.034-.101.106-.117.198-.091q.052.047.012.107z");
}

.x5me6db7m {
  fill: var(--svg-color--3e3d01, #3e3d01);
  d: path("m26.834 25.997l.053-.038c.045.017.067.053.084.096c.005.034 0 .065-.031.088h-.508c-.002-.039.01-.075.048-.095h.034c.091-.003.181.01.27-.01a.14.14 0 0 0 .05-.041");
}

.x64f7qgrk {
  fill: var(--svg-color--1c0902, #1c0902);
  d: path("m32.07 32.2l-.017-.004l-.019.002c-.09-.118-.039-.216.047-.306l.047.051a.28.28 0 0 1-.003.232z");
}

.x67fquzrg {
  fill: var(--svg-color--d6d71b, #d6d71b);
  d: path("M20.238 37.733q.023-.008.037.013c.074.04.107.091.046.17c-.104.049-.212.033-.32.015a.07.07 0 0 1-.044-.058c.041-.097.14-.082.215-.115a.3.3 0 0 1 .066-.025");
}

.xa0sjdb1k {
  fill: var(--svg-color--f7f447, #f7f447);
  d: path("M21.566 26c-.105.065-.207.077-.306-.008z");
}

.xa1352j4v {
  fill: var(--svg-color--52500d, #52500d);
  d: path("M28.994 24.756q.104.04.207.077v.024c-.104-.01-.219.055-.309-.043q-.024-.016-.017-.034q.009-.017.017-.017z");
}

.xamr67vaw {
  fill: var(--svg-color--3a3c02, #3a3c02);
  d: path("M12.162 29.793c.007.057.012.114.067.152c.026.084-.031.121-.086.162c-.049.021-.089.004-.123-.029a.07.07 0 0 1-.01-.063c.102-.043.044-.162.11-.223q.02-.038.042.001");
}

.xbkm_9uwo {
  fill: var(--svg-color--a5a275, #a5a275);
  d: path("M18.687 34.607a.1.1 0 0 0-.009-.048l.055.003l.006.051z");
}

.xc9elmrxs {
  fill: var(--svg-color--afaf0b, #afaf0b);
  d: path("m25.936 35.38l-.009.053c-.063.007-.125.005-.123-.085a.1.1 0 0 1 .031-.031a.1.1 0 0 1 .063-.012l.028.015a.08.08 0 0 1 .01.06");
}

.xcdo7ccjb {
  fill: var(--svg-color--707514, #707514);
  d: path("m12.269 32.513l-.049.053c-.064-.085-.066-.168.008-.247c.072.052.043.126.041.194");
}

.xce_xy08e {
  fill: var(--svg-color--4c4d31, #4c4d31);
  d: path("M27.312 34.977c-.026.088-.04.186-.153.209c-.017-.094.043-.152.097-.215q.03-.029.056.006");
}

.xcqkbhx1k {
  fill: var(--svg-color--1e1900, #1e1900);
  d: path("m25.406 34.92l.005-.059l.021-.011l.015.017q.029.029.061.056z");
}

.xd5vwzbqs {
  fill: var(--svg-color--543608, #543608);
  d: path("M31.751 28.05a.8.8 0 0 1-.094-.311c-.024-.041-.026-.078.008-.115c.18.094.064.291.146.42q-.026.043-.06.006");
}

.xeeve54gz {
  fill: var(--svg-color--764410, #764410);
  d: path("m24.275 39.646l-.115-.01c.046-.128.12-.113.207-.041z");
}

.xepvxxbhk {
  fill: var(--svg-color--302e00, #302e00);
  d: path("m12.162 29.793l-.021-.002l-.02.002c.008-.142-.023-.293.1-.405z");
}

.xfe80wy7k {
  fill: var(--svg-color--f1f108, #f1f108);
  d: path("m15.916 38.664l-.152.1c-.091.04-.105-.056-.156-.087l-.185-.169c-.133-.043-.2-.163-.296-.25a.2.2 0 0 1-.022-.069q0-.059.038-.102c.075-.041.146-.01.217.013a.54.54 0 0 1 .239.214c.052.072.101.148.196.171c.07.039.154.071.121.179");
}

.xfs60ab8k {
  fill: var(--svg-color--45470a, #45470a);
  d: path("m12.887 27.02l-.099.214c-.051-.11-.044-.194.099-.214");
}

.xfzfgvbod {
  fill: var(--svg-color--1e1b00, #1e1b00);
  d: path("M15.966 22.978q0 .044-.043.042a.1.1 0 0 1-.003-.041a.06.06 0 0 1 .046-.001");
}

.xh5-vabqc {
  fill: var(--svg-color--f3f448, #f3f448);
  d: path("m20.499 21.595l-.07.05l-.091.044a.2.2 0 0 1-.157-.05c.093-.094.21-.044.318-.044");
}

.xi_73q-fc {
  fill: var(--svg-color--462808, #462808);
  d: path("M30.938 25.791a.3.3 0 0 1-.099-.2c.04-.021.048-.056.05-.095c.102.083.02.2.049.295");
}

.xj5xy3bxm {
  fill: var(--svg-color--7d7c00, #7d7c00);
  d: path("m20.948 20.979l-.058.048c-.061.015-.135.069-.153-.052q.009-.02.007-.042c.029-.058.079-.052.13-.034c.034.015.064.039.074.08");
}

.xk5cqkbmc {
  fill: var(--svg-color--fafc1c, #fafc1c);
  d: path("M18.401 34.923q.015.002.026-.005l.021.026l-.019.027h-.002q-.024.03-.051.001h.002q-.019-.037.023-.048");
}

.xkgulpcjl {
  fill: var(--svg-color--c3c023, #c3c023);
  d: path("M27.404 29.526a.11.11 0 0 0-.061-.096c.019-.034.026-.102.076-.077c.07.038.026.117.032.18h-.024z");
}

.xklk57brl {
  fill: var(--svg-color--c5c58c, #c5c58c);
  d: path("M18.07 35.424a.2.2 0 0 0 0-.043l.057.006z");
}

.xl6i_ye-n {
  fill: var(--svg-color--e6e501, #e6e501);
  d: path("m18.17 30.16l-.043.044c-.092.079-.204.077-.314.07c-.409-.029-.82-.041-1.23-.063l-.055-.058c.041-.082.118-.051.181-.051q.626-.006 1.255 0c.069.001.154-.031.206.058");
}

.xmis3gv3f {
  fill: var(--svg-color--1e3966, #1e3966);
  d: path("m19.702 31.849l.391.003a.39.39 0 0 1-.391-.003");
}

.xmvdk1bcg {
  fill: var(--svg-color--f3f10e, #f3f10e);
  d: path("M28.481 23.05q.005.02.024.022c.103.023.149.092.161.191a.14.14 0 0 1-.069.129a.1.1 0 0 1-.073.007a3.4 3.4 0 0 1-.421-.335c-.05-.053-.103-.101-.14-.163a.1.1 0 0 1-.007-.07c.029-.048.075-.06.127-.063c.104.005.181.063.255.13c.035.065.119.08.143.152");
}

.xo9zdluql {
  fill: var(--svg-color--fafc00, #fafc00);
  d: path("M26.838 35.943q.003.022.01.043c.026.092-.045.108-.101.135c-.07.008-.126-.014-.162-.077l.047-.097z");
}

.xohbhibbk {
  fill: var(--svg-color--4e4d00, #4e4d00);
  d: path("M29.711 30.16c-.097-.06-.226-.023-.313-.107c.021-.051.063-.048.108-.045c.07.052.166-.018.234.048q.038.028.074.052q.02.016.014.031q-.01.016-.014.016z");
}

.xp2cb5-nv {
  fill: var(--svg-color--e8e214, #e8e214);
  d: path("m25.407 21.375l-.008.113c-.092.01-.161-.064-.252-.066c-.031-.016-.054-.037-.054-.077l.007-.125a.2.2 0 0 0 .046-.005q.126.043.25.088z");
}

.xp7jknayi {
  fill: var(--svg-color--f7f706, #f7f706);
  d: path("m29.655 31.29l.099-.022c.061-.004.106-.079.178-.04a.24.24 0 0 1 .051.219c-.112.145-.279.096-.426.12a.16.16 0 0 1-.103-.043a.3.3 0 0 1-.044-.058a.2.2 0 0 1-.029-.104a.1.1 0 0 1 .039-.056c.076-.047.158-.003.235-.016");
}

.xpf2_xgfh {
  fill: var(--svg-color--363700, #363700);
  d: path("M29.408 36.477c-.056-.093.066-.152.046-.237q.073.078.146.151c-.081-.01-.142.026-.192.086");
}

.xpfyjlbwo {
  fill: var(--svg-color--1a1700, #1a1700);
  d: path("M31.09 26.756c-.131-.008-.123-.106-.128-.197l.01.002z");
}

.xpv-b-b0z {
  fill: var(--svg-color--cf0101, #cf0101);
  d: path("M16.181 28.15h.043l.003 4.091a.2.2 0 0 1-.046.01l-.013-.151l-.004-3.232z");
}

.xsgs0v-9q {
  fill: var(--svg-color--4b4801, #4b4801);
  d: path("M30.988 30.867c.049.079.102.028.152.004c-.02.102.023.212-.041.307c-.039-.016-.063-.049-.09-.075c-.045-.041-.104-.067-.134-.123q-.01-.034.021-.053z");
}

.xucu3cb6n {
  fill: var(--svg-color--434315, #434315);
  d: path("M30.995 28.31c-.122-.077-.142-.188-.103-.316c.075.092.087.203.103.316");
}

.xux7tackt {
  fill: var(--svg-color--1f2400, #1f2400);
  d: path("M14.932 31.589c-.023.084-.096.021-.138.044c-.053-.063-.181.045-.204-.088a.53.53 0 0 1 .342.044");
}

.xv264-b8b {
  fill: var(--svg-color--efed5d, #efed5d);
  d: path("M27.1 37.28c.031.072.094.035.145.041c-.084.11-.197.043-.298.053q-.026-.014-.016-.024q.008-.013.016-.013z");
}

.xv6xwhw7f {
  fill: var(--svg-color--e7e448, #e7e448);
  d: path("M15.813 36.459q.103.029.204.053c-.084.047-.183.15-.204-.053");
}

.xwd3job7w {
  fill: var(--svg-color--010a01, #010a01);
  d: path("M17.535 35.996c-.115-.024-.176-.111-.234-.204q.026-.032.052 0z");
}

.xweqgj0rx {
  fill: var(--svg-color--3a3a00, #3a3a00);
  d: path("M26.33 25.738a.32.32 0 0 1-.057.201c-.06-.088-.007-.148.057-.201");
}

.xwghwqbho {
  fill: var(--svg-color--5e5c0e, #5e5c0e);
  d: path("M15.857 25.896c.087.05.059.135.059.207q.002.691-.001 1.381a.1.1 0 0 1-.046.043q-.108.013-.109-.096c.088.002.114-.046.114-.128c-.009-.468-.012-.936-.017-1.407");
}

.xwk6gupxh {
  fill: var(--svg-color--f9fa03, #f9fa03);
  d: path("M17.501 24.352c.049.017.056.055.053.099q-.177.007-.356.017c-.035.02-.067.022-.098-.01c-.061-.154.071-.15.153-.186l.056-.021a.03.03 0 0 0 .034.004c.045.044.115.049.158.097");
}

.xx5x1-bcj {
  fill: var(--svg-color--2d2000, #2d2000);
  d: path("M26.384 37.635c.048.012.105-.003.142.045l-.298.015a.1.1 0 0 0-.006-.038z");
}

.xxbsdeboz {
  fill: var(--svg-color--edf752, #edf752);
  d: path("M20.402 20.865c.115-.077.25-.035.371-.058l.014.018c.006.042-.007.062-.05.045z");
}

.xxw20ocxy {
  fill: var(--svg-color--3f4015, #3f4015);
  d: path("M27.25 36.439v-.085l.198-.005l.055.054c-.06.063-.148.004-.212.05z");
}

.xy41i7b1e {
  fill: var(--svg-color--595a00, #595a00);
  d: path("M24.729 39.691c.071-.077.178-.064.263-.102c-.05.134-.129.194-.263.102");
}

.xyjnm03zl {
  fill: var(--svg-color--871b18, #871b18);
  d: path("M25.811 30.1q.02-.01.039.002c.031.008.05.032.064.061a.3.3 0 0 1 .027.087a.07.07 0 0 1-.02.055l-.063.099c-.079-.092-.04-.201-.047-.304");
}

.xykb855qe {
  fill: var(--svg-color--484903, #484903);
  d: path("M28.422 24.1c-.114-.003-.157-.12-.251-.157l.003-.096a.6.6 0 0 1 .248.253");
}

.xz1iec_nj {
  fill: var(--svg-color--2b2100, #2b2100);
  d: path("M28.693 30.07a.03.03 0 0 0-.01.034l-.25-.015l.05-.043z");
}

.xzs5s4bpv {
  fill: var(--svg-color--274209, #274209);
  d: path("M12.382 33.984c.062.08.077.176.101.27c-.128-.057-.107-.164-.101-.27");
}

.xzsallbkc {
  fill: var(--svg-color--e4e40f, #e4e40f);
  d: path("m15.713 35.23l.164-.055c.135.033.235-.087.365-.075c.14-.051.294-.046.432-.106c.093.004.129.082.18.139c0 .045-.024.076-.058.101c-.183.093-.388.089-.579.149c-.147.007-.291.091-.441.03q-.1-.07-.063-.183");
}

.y__hw3baa {
  fill: var(--svg-color--7a130a, #7a130a);
  d: path("m28.544 31.502l-.361.07l-.007-.092c.12-.01.235-.072.361-.038a.06.06 0 0 1 .007.06");
}

.y_0hwi55z {
  fill: var(--svg-color--313400, #313400);
  d: path("m29.762 32.14l-.053-.041c.076-.065.171-.046.259-.06v.055q-.104.02-.206.046");
}

.y_5b-83es {
  fill: var(--svg-color--545400, #545400);
  d: path("M15.203 24.47q.024.043.049.082c-.015.034-.044.052-.077.063c-.043.015-.087.03-.131.002l-.098-.005c.041-.133.176-.088.257-.142");
}

.y_7mevbzp {
  fill: var(--svg-color--eff00d, #eff00d);
  d: path("M21.872 25.53q.021-.003.041.013c.063.026.152.025.133.133a.33.33 0 0 1-.168.184c-.063.016-.118-.007-.166-.049c-.034-.054-.001-.083.041-.107l.007-.06c.002-.046.009-.089.05-.12a.07.07 0 0 1 .062.006");
}

.y_9sfpbfn {
  fill: var(--svg-color--575400, #575400);
  d: path("M31.25 34.971q.006.032.008.063c-.012.079.033.185-.1.204l-.011-.06c-.048-.11-.025-.185.103-.207");
}

.y_c00d0xu {
  fill: var(--svg-color--7b7d18, #7b7d18);
  d: path("m20.415 21.07l.01-.094c.069-.003.144-.022.191.053q.02.01.044.018l-.044.021z");
}

.y-5gkeb7h {
  fill: var(--svg-color--686900, #686900);
  d: path("m32.15 29.483l-.033.015a.1.1 0 0 1-.054.043c-.046-.046-.045-.104-.036-.163l.054.007c.065.007.082.041.069.098");
}

.y-dxpzibo {
  fill: var(--svg-color--595352, #595352);
  d: path("m18.523 32.31l.017-2.01l.036 2.063q-.028.03-.038-.01l-.015-.041");
}

.y-xzbobkx {
  fill: var(--svg-color--1e1a00, #1e1a00);
  d: path("m25.551 34.971l-.038.001l-.008-.051z");
}

.y0nzxbbil {
  fill: var(--svg-color--550400, #550400);
  d: path("M28.373 32.602a.1.1 0 0 1 .015-.036l.209-.007c.031-.024.059-.027.085.007c-.08.099-.192.097-.304.089z");
}

.y1-thkbva {
  fill: var(--svg-color--1d2e04, #1d2e04);
  d: path("M18.432 37.789c.026-.044.07-.047.114-.054c.129-.067.257-.125.346.056c-.019 0-.034.004-.051.004z");
}

.y1hyu_ben {
  fill: var(--svg-color--1c3606, #1c3606);
  d: path("M16.483 39.32c.077.013.143.042.186.111c-.08-.006-.184.025-.186-.111");
}

.y1r9v9twl {
  fill: var(--svg-color--631604, #631604);
  d: path("M22.274 25.02h-.048c-.102-.123-.084-.274-.099-.419a.34.34 0 0 1 .06-.145a.14.14 0 0 1 .097-.061c.058.094.115.187.25.164a.08.08 0 0 1 .021.064c-.033.114-.209.007-.227.145q0 .05-.004.102c-.048.039.001.113-.05.15");
}

.y23qnebec {
  fill: var(--svg-color--f9fb01, #f9fb01);
  d: path("m30.342 25.952l-.118-.006c-.034-.052-.048-.103-.015-.158c.061-.056.128-.041.197-.02a.1.1 0 0 1 .058.053a.14.14 0 0 1-.014.118q-.048.05-.108.013");
}

.y2ygvnzyu {
  fill: var(--svg-color--1d3904, #1d3904);
  d: path("M18.942 22.259q.107-.044.212-.091c.062-.098.144-.128.252-.08l.407-.079c-.026.158-.179.097-.263.134c-.192.078-.383.188-.606.164q-.024-.015-.017-.031q.009-.016.015-.017");
}

.y3d_2v9fy {
  fill: var(--svg-color--52500b, #52500b);
  d: path("m30.18 25.728l.061-.046l.191.063q.019.019.011.035q-.007.016-.011.015l-.196-.019z");
}

.y4cfxjbpy {
  fill: var(--svg-color--404612, #404612);
  d: path("M15.464 24.46q-.034-.03-.068-.063a.1.1 0 0 1 .006-.044q.107.004.213.011c.037.058.102.028.152.045c-.076.164-.188.123-.303.051");
}

.y51rlqbdp {
  fill: var(--svg-color--161600, #161600);
  d: path("m18.07 35.424l-.053.007l-.02-.024l.02-.025h.002q.028-.026.051 0q.019.015.012.028q-.005.014-.012.014");
}

.y5tyzgbab {
  fill: var(--svg-color--31310b, #31310b);
  d: path("M22.636 40.15q-.026.004-.051.004l.002-.105l.202.015q.021.03-.002.058c-.048.023-.11-.01-.152.038z");
}

.y5w_vbyqf {
  fill: var(--svg-color--fbfc20, #fbfc20);
  d: path("m17.968 35.38l.049-.053q.009.012.019.021l-.002.03l-.02.021q-.03.01-.048-.02z");
}

.y6ljy5bvz {
  fill: var(--svg-color--2a2a00, #2a2a00);
  d: path("m24.995 40.27l-.002.036c-.069.095-.171.029-.255.051c.077-.053.157-.102.257-.087");
}

.y8io6w_cv {
  fill: var(--svg-color--f6f522, #f6f522);
  d: path("m21.813 25.559l-.053.085c-.159-.104-.339-.036-.506-.061a.3.3 0 0 1 .007-.055c.183-.012.371-.062.552.031");
}

.y8lu7k7rs {
  fill: var(--svg-color--302b2c, #302b2c);
  d: path("m20.99 37.699l.047-.017q.179.008.358.019l-.099.049c-.103-.008-.212.017-.306-.051");
}

.yavujeqzr {
  fill: var(--svg-color--141404, #141404);
  d: path("m16.479 34.512l.041-.055l.097.207q-.022.036-.049.006z");
}

.yb2d7b_hp {
  fill: var(--svg-color--f1ee02, #f1ee02);
  d: path("M26.02 34.976c.048-.007.09-.007.118.042c.036.074-.012.141-.02.209l-.002.002a.1.1 0 0 1-.061.029a.13.13 0 0 1-.065-.023a.17.17 0 0 1-.062-.159c.01-.052.051-.077.094-.1z");
}

.ybkxt1_rw {
  fill: var(--svg-color--1b1b00, #1b1b00);
  d: path("m25.24 34.663l-.036-.005a.1.1 0 0 1-.005-.035q.023.02.041.04m.105.104h-.025l-.024-.05z");
}

.ybz502bbt {
  fill: var(--svg-color--eaea5f, #eaea5f);
  d: path("M26.578 36.766c-.023-.086-.096-.023-.139-.048c.089-.094.199-.04.301-.046q.02.032-.018.043c-.042.034-.086.06-.144.051");
}

.yc3_iabnl {
  fill: var(--svg-color--392100, #392100);
  d: path("M18.221 26.289a21 21 0 0 1-1.739.002q-.006-.055.041-.077a9 9 0 0 1 1.657-.002q.047.026.041.077");
}

.ychvjpqxs {
  fill: var(--svg-color--ecd459, #ecd459);
  d: path("m23.617 20.86l-.261.008q-.005-.024-.004-.05l.252.007z");
}

.yczkv-35y {
  fill: var(--svg-color--572204, #572204);
  d: path("m27.659 23.684l.052.055q-.026.025-.048.051l-5.03.002q0-.024.005-.048l4.723.01c.092 0 .195.015.198-.126q.05.027.098.056");
}

.yd_4zobrk {
  fill: var(--svg-color--abac7f, #abac7f);
  d: path("m28.18 25.377l-.024.002l-.024-.002l.005-.197l.039-.003c.009.061.079.039.103.079c.009.075-.069.078-.099.121");
}

.yekqd6abk {
  fill: var(--svg-color--656106, #656106);
  d: path("M25.15 34.986v.02c-.002.066-.039.107-.087.144a.3.3 0 0 1-.128.05a.1.1 0 0 1-.062-.03c-.015-.034-.006-.067.007-.101c.076-.071.164-.108.27-.083");
}

.yensxztfi {
  fill: var(--svg-color--020302, #020302);
  d: path("m19.608 26.416l.002.035l-1.07.02l-.002-.06z");
}

.yf3c7m3-k {
  fill: var(--svg-color--111700, #111700);
  d: path("m21.452 41.03l-.001-.114l-.046-.044c-.063-.06-.182-.021-.219-.125c.015-.051.058-.07.097-.092c.185-.124.072-.313.105-.469v-.099a.2.2 0 0 0-.019-.09c-.051-.06-.154-.033-.188-.12a.1.1 0 0 1 .04-.063a.33.33 0 0 1 .243-.012q.04.016.065.05c.098.295.025.603.051.902c.009.094-.052.205.064.274a.2.2 0 0 1 .064.039l.006.015c-.015.108-.095.102-.171.096c-.091-.006-.085-.082-.091-.148");
}

.yf9k3y7qm {
  fill: var(--svg-color--1b3c0e, #1b3c0e);
  d: path("M15.775 38.804c.1.028.161.111.239.171c-.108-.017-.238-.004-.239-.171");
}

.yflbk5ehz {
  fill: var(--svg-color--4b4b05, #4b4b05);
  d: path("m25.1 34.714l-.058.002q-.051-.05-.101-.103h.049c.014-.02.031-.024.053-.021a.14.14 0 0 1 .069.064a.06.06 0 0 1-.012.058");
}

.yg-e5ubjq {
  fill: var(--svg-color--2a2000, #2a2000);
  d: path("m22.684 21.751l.26.005c-.01.077-.059.063-.108.043l-.149-.014q-.004-.017-.003-.034");
}

.yg-k8bsov {
  fill: var(--svg-color--ecec10, #ecec10);
  d: path("M14.13 34.99c-.01-.055-.024-.104-.078-.13c.003-.04.027-.064.062-.081a.4.4 0 0 1 .101-.021a.4.4 0 0 0 .214-.08q.105-.06.221-.107c.131-.021.253-.098.393-.075q.084.06.072.163c-.031.056-.086.077-.145.094c-.079.027-.181.01-.222.111l-.067.008c-.105.021-.221.006-.316.073c-.08.012-.151.065-.235.045");
}

.yg8uyq_ir {
  fill: var(--svg-color--3a3800, #3a3800);
  d: path("M21 40.04h.447v.118l-.05-.01c-.147-.06-.307.006-.457-.036c-.019-.057.005-.077.06-.072");
}

.ygra0bbxi {
  fill: var(--svg-color--4d4d04, #4d4d04);
  d: path("M15.675 24.604c.043-.038.094-.033.146-.031c.169.17.121.361.048.554c.003-.067-.002-.135.008-.202c.019-.166-.014-.29-.202-.321m.044.626c.012-.09.098-.068.148-.1a.36.36 0 0 1 .049.26a.1.1 0 0 0-.044.014a.2.2 0 0 1-.06-.035c-.039-.042-.084-.078-.093-.139");
}

.ygzzu-b7x {
  fill: var(--svg-color--484700, #484700);
  d: path("m21.66 23.735l-.007-3.169l.058-.004l.001.105c.062.072.05.159.052.243v2.622a.6.6 0 0 1-.043.248z");
}

.yhfw7obfr {
  fill: var(--svg-color--0e0901, #0e0901);
  d: path("M26.848 24.715q.025.05.046.104a.3.3 0 0 1-.003.255q-.023 0-.041-.003l-.035-.028c-.051-.116-.068-.229.033-.328");
}

.yhrfujd7a {
  fill: var(--svg-color--b8b500, #b8b500);
  d: path("M18.738 34.557a.1.1 0 0 0-.011-.04l.061-.007l.021.026q-.01.014-.021.026l.003-.002q-.03.035-.053-.003");
}

.yilhdlwzo {
  fill: var(--svg-color--2d2e00, #2d2e00);
  d: path("M12.982 31.535h-.031l-.017-.4c-.02-.057.008-.072.06-.062l.049.059l.002.034c-.094.076-.033.177-.043.266c.017.037.024.075-.02.103");
}

.yiv9lkbuy {
  fill: var(--svg-color--e5e521, #e5e521);
  d: path("M25.292 35.568q.031.062.066.122l-.007.056c-.033.031-.07.053-.118.046a.1.1 0 0 1-.028-.007l-.008-.1c-.018-.079.027-.108.095-.117");
}

.yj2fvbcmm {
  fill: var(--svg-color--0a0a00, #0a0a00);
  d: path("M19.503 37.474c-.105.024-.184-.021-.255-.092a.07.07 0 0 1 .055-.038c.074.033.166.039.2.13");
}

.yjy09yb0d {
  fill: var(--svg-color--800403, #800403);
  d: path("m16.993 25.12l-.014-.244l.071-.01c.043.079 0 .17.029.25l.008.053c-.04.002-.074-.01-.094-.049");
}

.ykhmlvvmz {
  fill: var(--svg-color--eae95f, #eae95f);
  d: path("m17.607 37.28l-.003.055c-.087-.007-.179.012-.257-.046z");
}

.yllixzb-a {
  fill: var(--svg-color--7a7800, #7a7800);
  d: path("M25.04 37.635q-.031-.028-.061-.058l.113-.049q.04-.03.058.017q.026.022.051.046q-.009.02-.015.039z");
}

.ymaan_bqy {
  fill: var(--svg-color--f8f805, #f8f805);
  d: path("m19.05 35.23l.139.1l.006.066c-.125.078-.192.248-.371.243a.7.7 0 0 1-.111-.239c-.051-.231.072-.249.337-.17");
}

.ymc5xzboc {
  fill: var(--svg-color--d8d8bf, #d8d8bf);
  d: path("M12.88 32.19a.04.04 0 0 1-.031-.006l-.058-.129c.057-.013.04-.063.05-.099c.094.065.036.155.039.234");
}

.ymv5xz-gh {
  fill: var(--svg-color--f6f604, #f6f604);
  d: path("M12.285 29.07c-.007-.057-.01-.112.034-.156q.13.112-.034.156");
}

.ymz5veyto {
  fill: var(--svg-color--e5eefa, #e5eefa);
  d: path("M23.91 30.393c-.023.089-.074.14-.164.128c-.089-.01-.137-.07-.122-.159c.013-.072.06-.117.145-.112c.095.006.131.061.141.143");
}

.yn_l2fb-k {
  fill: var(--svg-color--565405, #565405);
  d: path("m28.587 35.32l-.074-.204a.46.46 0 0 1 .19.159c-.026.046-.07.049-.116.045");
}

.yo07teb8d {
  fill: var(--svg-color--f6f733, #f6f733);
  d: path("m26.528 25.13l.01-.055q.151-.117.296.005l.016-.006c-.089.125-.211.056-.322.056");
}

.yo6lywege {
  fill: var(--svg-color--3e3501, #3e3501);
  d: path("m29.92 29.32l.056-.044l.148.018c.025.026.029.053-.002.078c-.074.004-.159.064-.202-.052");
}

.yon1occ-i {
  fill: var(--svg-color--f6f447, #f6f447);
  d: path("M26.28 25.995q0 .024.003.046h-.361a.1.1 0 0 1 .007-.049q.174.003.351.003");
}

.yp2956-hi {
  fill: var(--svg-color--1e1a00, #1e1a00);
  d: path("M30.938 29.635c.024-.039.063-.046.104-.048l.104.005q.003.068.004.137c-.063-.051-.165-.009-.212-.094");
}

.yq-pnv5aj {
  fill: var(--svg-color--e8e31a, #e8e31a);
  d: path("m26.328 22.61l.007.086q-.007.044-.017.091c-.029.013-.061.004-.091-.002l-.152-.07c-.02-.019-.055-.023-.058-.06l.121-.05z");
}

.yq2c24-1c {
  fill: var(--svg-color--88250f, #88250f);
  d: path("M30.12 31.18c-.054.066-.138.037-.202.064q-.082.013-.164.023c.084-.192.225-.134.366-.087");
}

.yqa1bx25r {
  fill: var(--svg-color--240c00, #240c00);
  d: path("M23.601 21.884a.1.1 0 0 0-.046.015l-.197-.011l.053-.05c.07-.015.151-.067.19.046");
}

.yqgdz6rha {
  fill: var(--svg-color--641314, #641314);
  d: path("m30.23 26.922l-.313-.013c-.028-.029-.028-.063-.012-.097a.2.2 0 0 1 .092-.048c.058-.012.113-.021.17.007z");
}

.yr42lkbzw {
  fill: var(--svg-color--fdfdfd, #fdfdfd);
  d: path("M27.758 34.02c-.047.03-.042.082-.058.127a.53.53 0 0 0-.097.311a.3.3 0 0 1-.024.063c-.065.076-.13.151-.145.257a.2.2 0 0 1-.025.061a1 1 0 0 0-.111.163c-.039.065-.082.129-.096.207a.36.36 0 0 1-.118.202c-.09.049-.147.131-.209.208c-.077.115-.177.213-.238.339c-.106.107-.218.209-.323.319c-.091.084-.175.172-.265.258c-.05.043-.107.074-.158.115c-.063.056-.137.104-.204.154c-.065.055-.135.102-.205.149c-.063.04-.116.091-.169.14a.3.3 0 0 1-.058.031a.5.5 0 0 0-.188.115a.2.2 0 0 1-.056.031a.5.5 0 0 0-.188.108a.2.2 0 0 1-.056.03a.4.4 0 0 0-.165.082a.2.2 0 0 1-.059.022c-.066.005-.122.036-.182.063c-.104.034-.203.086-.309.122a.6.6 0 0 0-.231.113a.3.3 0 0 1-.064.018a.8.8 0 0 0-.296.037c-.087.042-.183.001-.272.022l-.76.104c-.252.12-.517.067-.779.071c-.099-.014-.193-.053-.296-.047c-.178.004-.347-.054-.522-.068c-.05-.01-.097-.03-.145-.047a1 1 0 0 0-.17-.049c-.078-.018-.154-.043-.234-.056q-.032-.008-.066-.019a4 4 0 0 0-.224-.077l-.188-.063c-.084-.031-.163-.071-.248-.098q-.032-.01-.06-.026c-.072-.048-.143-.099-.224-.135q-.099-.047-.199-.102c-.052-.031-.102-.072-.166-.079a.2.2 0 0 1-.056-.026a.7.7 0 0 0-.205-.142a.6.6 0 0 1-.192-.128a.4.4 0 0 0-.19-.118a.3.3 0 0 1-.077-.066a.9.9 0 0 0-.288-.282a4 4 0 0 1-.414-.413a1 1 0 0 0-.163-.203c-.063-.063-.11-.137-.162-.205q-.065-.078-.124-.162q-.114-.175-.231-.348a1 1 0 0 1-.115-.211c-.017-.077-.094-.131-.084-.219a2 2 0 0 1-.118-.21c-.053-.099-.127-.185-.164-.29a7 7 0 0 1-.352-1.303a1 1 0 0 1-.023-.205c.002-.073-.029-.141-.043-.211c-.022-.308-.005-.615-.012-.922c-.01-.514.025-1.026-.02-1.537a.4.4 0 0 1-.013-.135c.003-.074.036-.144.032-.217c.005-.161.002-.322 0-.485v-.421c-.018-1.039.064-2.078-.001-3.115v-.097q.003-.577.001-1.15c-.01-.113 0-.226.002-.339c.007-.084.01-.168.086-.225c.12-.064.25-.043.376-.043q2.567-.002 5.136-.002c.348.008.696-.027 1.038.07h.105c.108-.1.243-.068.366-.068q2.32-.002 4.641-.002c.151.012.31-.031.445.072c.069.099.053.212.053.322c.002 1.585.015 3.173-.003 4.757c-.014 1.108.036 2.216-.005 3.324c-.058.171-.033.352-.058.527c-.014.065-.038.13-.058.194a.9.9 0 0 0-.05.332l-.003.02a.76.76 0 0 0-.102.39l-.002.02a.55.55 0 0 0-.103.296");
}

.yts446a2o {
  fill: var(--svg-color--272800, #272800);
  d: path("M29.1 26.912v-.092a.36.36 0 0 1 .25-.051l-.044.058c-.031.022-.063.044-.105.032z");
}

.yuhwapbri {
  fill: var(--svg-color--740300, #740300);
  d: path("m26.939 24.458l-.041-.208c.143.044.119.119.041.208");
}

.yult2f2-h {
  fill: var(--svg-color--525300, #525300);
  d: path("m12.994 31.07l-.06.062l-.048-.314l.112.104c.001.05-.003.098-.004.148");
}

.yw3r8q3xb {
  fill: var(--svg-color--eeef14, #eeef14);
  d: path("m26.28 30.813l.005-.204c.088-.076.089-.221.214-.263c.066-.171.178-.14.298-.067c.039.031.069.068.072.121a.09.09 0 0 1-.058.079c-.051.007-.105-.007-.151.033c-.073.048-.118.121-.171.19c-.063.049-.079.189-.209.111");
}

.ywq33ccdi {
  fill: var(--svg-color--fcfc01, #fcfc01);
  d: path("m21.814 20.673l.205-.019q.148.012.3.021q-.01 1.534-.017 3.07c-.175.017-.349.06-.517-.024c-.053-.085-.044-.181-.044-.274a505 505 0 0 1 0-2.461c.002-.108-.015-.224.073-.313");
}

.yx-emhbim {
  fill: var(--svg-color--494401, #494401);
  d: path("M27.358 25.07a.33.33 0 0 0-.013-.202c.095.08.075.168.015.258l-.007-.002q-.043-.03.005-.054");
}

.yxoparbae {
  fill: var(--svg-color--5f453a, #5f453a);
  d: path("m18.13 30.461l.078-.1c.023.099.03.2.01.301l-.085-.099q-.049-.05-.003-.102");
}

.yxq938bts {
  fill: var(--svg-color--d2b8ad, #d2b8ad);
  d: path("m22.434 25.12l-.024.008l-.024-.005c.013-.081-.051-.176.043-.245l.01.191a.3.3 0 0 0-.005.051");
}

.yy1ceeb9n {
  fill: var(--svg-color--eef13c, #eef13c);
  d: path("m24.02 40.517l-.149.001c.084-.104.199-.045.301-.056c-.013.12-.09.064-.152.055");
}

.yyt9czb_u {
  fill: var(--svg-color--f2f30c, #f2f30c);
  d: path("m13.616 28.13l-.1-.084c-.035-.045-.074-.088-.067-.151c.032-.075.085-.099.157-.05c-.044.109.137.094.107.194l-.01.125c-.037.013-.076.024-.087-.034");
}

.yz1im81ue {
  fill: var(--svg-color--fe0101, #fe0101);
  d: path("M24.967 36.976q-.316.153-.631.308c-.079.049-.175.055-.257.094c-.125.026-.229.118-.359.118c-.076.061-.185.029-.257.097c-.033.071-.099.043-.151.051c-.092.004-.19-.034-.268.05l.005-.002c-.12.055-.25.004-.373.031c-.411.042-.824.011-1.234.019c-.115-.01-.23-.035-.349-.025c-.096-.047-.192-.092-.303-.082c-.064-.02-.128-.02-.194-.025c-.075-.062-.167-.066-.256-.084c-.064-.021-.133-.007-.194-.038c-.072-.023-.128-.085-.212-.081c-.07-.041-.132-.111-.229-.08l-.049-.018c-.04-.088-.122-.098-.201-.115c-.061-.084-.169-.066-.244-.119c-.03-.08-.137-.006-.166-.085c-.069-.084-.144-.156-.262-.156l-.454-.332c-.041-.048-.07-.105-.125-.14c-.073-.077-.146-.156-.234-.217l-.252-.25c-.056-.107-.174-.166-.22-.281c-.036-.01-.091.005-.098-.056c-.018-.072-.075-.118-.116-.175c-.004-.073-.086-.106-.092-.181c-.033-.015-.089.01-.096-.054a.65.65 0 0 0-.125-.257c-.038-.115-.113-.209-.185-.306l-.09-.227c-.056-.099-.076-.217-.151-.308q-.023-.013-.015-.036c.051-.104-.043-.163-.076-.242c-.041-.087.002-.198-.077-.273c-.042-.112-.034-.235-.078-.346c-.069-.164-.066-.337-.076-.51c.003-.142-.031-.279-.021-.421v-4.889c.002-.94-.001-1.879.002-2.819c0-.118-.02-.239.043-.352c.258-.126.53-.043.797-.053c.128.18.005.319-.075.466a.3.3 0 0 1-.11.044c-.084.014-.168.002-.252.017c-.084.043-.048.099-.017.154q.03.042.043.094q.022.104.002.211c-.012.056-.045.102-.072.149q-.011.029-.017.061a.4.4 0 0 0 .013.154a.3.3 0 0 1 .012.066a.8.8 0 0 0 .015.236q.014.105.002.212l-.02.067a.3.3 0 0 1-.06.084c-.094.137.031.094.089.107h1.521c.154.008.118-.069.067-.155a.5.5 0 0 1-.027-.177c-.002-.098.006-.196-.019-.293a.3.3 0 0 1-.003-.105c.001-.085.09-.181-.021-.26a.2.2 0 0 1-.038-.059a.5.5 0 0 1 .005-.295a.36.36 0 0 0 .067-.291c-.069-.121-.181-.037-.271-.047c-.114-.014-.213-.025-.251-.153a.24.24 0 0 1 .002-.123c.026-.072.051-.144.136-.166c1.289-.017 2.578-.009 3.865-.005a.2.2 0 0 1 .088.026a.28.28 0 0 1 .086.277c-.023.074-.05.147-.125.189c-.101.051-.224-.002-.318.072a.4.4 0 0 0-.069.097c-.023.049.005.096.012.143a.4.4 0 0 1-.064.259q-.089.094-.017.197q.015.03.023.063q.018.078.041.157l.015.064c.015.087-.017.169-.012.256a.3.3 0 0 1-.012.098c-.011.065-.085.094-.097.158q.009.025.021.051a.08.08 0 0 0 .051.027c.531-.015 1.062.007 1.591-.013c.048-.021.098-.036.055-.105a.17.17 0 0 1-.028-.089c.014-.125.016-.248-.063-.355a.25.25 0 0 1 .02-.21c.087-.111.034-.214-.026-.313a.6.6 0 0 1-.013-.291c.003-.076.088-.161-.025-.226c-.084-.013-.166-.003-.248-.008q-.221.002-.276-.211a.3.3 0 0 1 .007-.181c.026-.061.064-.111.133-.128c1.294-.017 2.59-.01 3.883-.003c.158.045.183.166.145.302c-.037.138-.147.144-.268.127a.36.36 0 0 0-.2.015c-.035.033-.026.074-.026.115a.4.4 0 0 1-.005.092c-.007.058.037.096.054.143a.4.4 0 0 1 .009.206c-.005.072-.093.085-.11.149l.013.058c.007.065.036.12.074.171a.3.3 0 0 1 .026.101q0 .053-.015.104c-.015.046-.035.089-.051.131c-.033.089-.021.185-.05.273c-.008.032-.018.065-.01.099c.101.08.216.041.322.043q.651.003 1.302 0c.086 0 .13-.027.074-.117a.4.4 0 0 1-.048-.164c-.005-.081.003-.161-.028-.238c-.095-.137.028-.281-.015-.42a1 1 0 0 1-.039-.092c-.061-.159.031-.304.043-.457c-.01-.031-.021-.061-.025-.094l-.005-.065c-.036-.089-.113-.053-.174-.053c-.099.002-.216.043-.25-.095c-.029-.122-.056-.254.094-.329c.245.011.495-.067.733.048c.02.094.01.188.01.281l.002 7.199c0 .23-.014.459-.017.688c.018.081.031.161-.009.238l.005.002c-.077.094.005.214-.054.311v-.007c-.048.103-.038.214-.048.322c-.002.063.007.129-.058.17a.5.5 0 0 0-.046.236c.003.051-.007.094-.056.12c-.026.06-.062.116-.046.188l-.067.209c-.098.026-.047.126-.088.181a4.5 4.5 0 0 1-.522.922c-.051.051-.102.102-.102.181c-.076.132-.229.199-.285.346a.6.6 0 0 0-.233.27c-.01.046-.046.032-.077.032c-.116.103-.224.213-.34.31c-.019.123-.164.115-.212.207a1.1 1.1 0 0 0-.293.2l-.087.06c-.087.043-.174.084-.243.154");
}

.yzk8_lbqr {
  fill: var(--svg-color--535304, #535304);
  d: path("m25.557 35.23l.002-.159q.017-.026.046-.021a.26.26 0 0 1 .124.075q.015.025.024.053l.013.056a1 1 0 0 1 .017.088a.07.07 0 0 1-.018.054c-.108.004-.157-.073-.208-.146");
}

.z_3tg_82b {
  fill: var(--svg-color--4b4b00, #4b4b00);
  d: path("M15 37.84c.16.057.257.18.348.312l-.199-.058c-.008-.109-.155-.137-.149-.254");
}

.z_u_0xx3i {
  fill: var(--svg-color--97943c, #97943c);
  d: path("m18.12 29.938l.051.016q.02.06-.04.067c-.549-.003-1.098.015-1.646-.01l.001-.063c.187-.094.385-.069.582-.072l.091-.002c.123.005.248-.01.365.043c.198-.013.4-.108.596.021");
}

.z-f6eydjh {
  fill: var(--svg-color--575900, #575900);
  d: path("M25.407 40.15c.055-.142.206-.092.301-.151c.055-.03.062.001.057.046c-.021.017-.038.029-.057.046a.22.22 0 0 1-.197.112a.14.14 0 0 1-.104-.053");
}

.z-g1x0bbz {
  fill: var(--svg-color--eaea4d, #eaea4d);
  d: path("m18.79 34.883l.058-.01c.041.082.203.007.195.151a.13.13 0 0 1-.063.023c-.069-.007-.135.015-.204.007a.12.12 0 0 1-.058-.037c-.021-.068-.002-.116.072-.134");
}

.z-shwx6wr {
  fill: var(--svg-color--811c0c, #811c0c);
  d: path("M24.18 40.721c-.067.188-.226.145-.366.141c-.031-.031-.105 0-.109-.072c.084-.125.228-.074.339-.115q.059-.008.112.019z");
}

.z05owvb7j {
  fill: var(--svg-color--f0f10b, #f0f10b);
  d: path("m29.864 26.25l-.048-.048c-.046-.09-.13-.156-.173-.248l-.003-.036a.1.1 0 0 1 .037-.056a.2.2 0 0 1 .105-.021c.081.003.138.045.186.104l.045.152c-.11-.006-.08.121-.149.153");
}

.z14sautfh {
  fill: var(--svg-color--352d04, #352d04);
  d: path("M25.397 34.773c.071-.074.144-.148.161-.257q.023-.044.053-.005l-.003-.004c.068.131.046.314.22.384a.21.21 0 0 1 .079.154a.2.2 0 0 1-.018.065a.07.07 0 0 1-.057.03c-.044-.005-.079-.031-.113-.053a.3.3 0 0 0-.056-.021l-.051-.024a.4.4 0 0 1-.063-.058c-.017-.02-.026-.047-.046-.065l.003.002c-.02-.021-.044-.028-.067-.041a.16.16 0 0 1-.055-.06a.06.06 0 0 1 .013-.047");
}

.z1a46qbbv {
  fill: var(--svg-color--4b391b, #4b391b);
  d: path("M30.729 28.16c-.149-.021-.084-.135-.091-.217c.066.058.052.149.091.217");
}

.z1f8lkavt {
  fill: var(--svg-color--6f0805, #6f0805);
  d: path("m18.17 30.16l.047.038l-.01.164c-.011.049.002.12-.089.106c-.047-.039-.063-.09-.065-.149a.4.4 0 0 1 .036-.131c.019-.028.041-.054.081-.028");
}

.z1psxacmy {
  fill: var(--svg-color--4a140b, #4a140b);
  d: path("M28.893 23.342q.369.239.613.605c.011.053-.017.063-.06.063c-.224-.171-.436-.354-.578-.6q0-.04.025-.068");
}

.z2_vn2pfe {
  fill: var(--svg-color--080803, #080803);
  d: path("M31.24 31.789c.031-.113-.046-.242.053-.347v.396c-.047.014-.068.004-.053-.049");
}

.z24zj6y8u {
  fill: var(--svg-color--e3e41f, #e3e41f);
  d: path("m24.742 35.34l-.062.05l-.1-.098c-.033-.065-.031-.113.058-.119a.1.1 0 0 1 .041.006c.059.04.115.079.063.161");
}

.z2dd-kbzx {
  fill: var(--svg-color--f1f208, #f1f208);
  d: path("m28.11 35.08l.063-.069c.036-.02-.001-.088.063-.088l.271.2c.049.059.13.106.074.204l-.071.066q-.027.019-.063.017a.26.26 0 0 1-.113-.063a1.4 1.4 0 0 0-.152-.125c-.044-.036-.09-.073-.072-.142");
}

.z2dld5nlg {
  fill: var(--svg-color--cfd014, #cfd014);
  d: path("m18.639 35.02l-.004-.101a.13.13 0 0 1-.036-.055a.14.14 0 0 1 .002-.065l.015-.029l.028-.02l.031.006l.115.123l-.055.141z");
}

.z2dq_3tix {
  fill: var(--svg-color--d11414, #d11414);
  d: path("M16.273 27.33h-.048c-.04-.053-.026-.115-.026-.173v-2.825c.002-.058-.014-.119.026-.173l.054-.002q-.002 1.587-.006 3.173");
}

.z334klbnk {
  fill: var(--svg-color--e7eff6, #e7eff6);
  d: path("M22.04 33.583c-.086-.012-.142-.058-.145-.146c-.004-.079.044-.133.118-.142c.085-.01.147.035.156.127c.011.094-.047.137-.129.161");
}

.z4-pqccjm {
  fill: var(--svg-color--282800, #282800);
  d: path("m26.691 37.39l-.05-.046c.058-.063.129-.03.194-.023l.106.021a.1.1 0 0 1 0 .037z");
}

.z5bmk-b2y {
  fill: var(--svg-color--442907, #442907);
  d: path("M30.19 24.807c.073.111.259.132.245.311l-.026.021a.36.36 0 0 1-.198-.041c-.066-.048-.155-.063-.201-.138c.008-.114.09-.139.18-.153");
}

.z6pznodfr {
  fill: var(--svg-color--f1f048, #f1f048);
  d: path("m27.358 25.07l-.005.054l-.315.007c-.041-.024-.048-.05.002-.074l.115.011q.047-.04.094 0q.055 0 .109.002");
}

.z747wh5yw {
  fill: var(--svg-color--fafa01, #fafa01);
  d: path("m30.23 31.17l.154.101c-.01.072-.056.113-.115.145c-.097.024-.193.061-.296.014c-.032-.06-.059-.119-.051-.189c.043-.097.146-.003.202-.064a.06.06 0 0 0 .045-.015q.032-.02.061.008");
}

.z7egizbtp {
  fill: var(--svg-color--c7c784, #c7c784);
  d: path("M18.17 35.28a.1.1 0 0 0 .041 0l-.038.06q-.022-.017-.017-.038q.007-.02.014-.022");
}

.z7tpto08m {
  fill: var(--svg-color--4f5208, #4f5208);
  d: path("M13.606 27.811v.035a.6.6 0 0 1-.141.066a.06.06 0 0 1-.058-.017c.037-.089.015-.216.146-.251a.23.23 0 0 1 .053.167");
}

.z7uojdfzl {
  fill: var(--svg-color--f4f05c, #f4f05c);
  d: path("M21.21 25.288q-.07-.029-.005-.07c.168-.054.339-.071.513-.063a1.9 1.9 0 0 1 .613.061l.515.002l.046.054c-.056.048-.122.057-.19.057q-.673.005-1.347 0a.24.24 0 0 1-.145-.041");
}

.z9gt93uaf {
  fill: var(--svg-color--440, #440);
  d: path("m22.638 20.974l-.049-.009v-.102q.124.03.248.056q.02.014.015.028c-.005.014-.007.015-.01.015z");
}

.z9s3mpx1c {
  fill: var(--svg-color--444215, #444215);
  d: path("m30.895 33.643l-.048-.006c.055-.1.01-.249.149-.309l-.003.105c.002.056-.002.109-.044.154z");
}

.z9wxxr8xx {
  fill: var(--svg-color--811f0f, #811f0f);
  d: path("M26.33 36.578c.005-.064.072-.072.104-.115q.103.003.207.003c.021.017.049.024.063.052q.005.031-.027.034z");
}

.zaaksxf9t {
  fill: var(--svg-color--e2de60, #e2de60);
  d: path("M29.451 31.425h-.317l.02-.038l.242-.01c.017.017.038.033.055.048");
}

.zate2svto {
  fill: var(--svg-color--575700, #575700);
  d: path("M13.752 30.26a.65.65 0 0 1-.346.098q-.02-.015-.013-.028t.013-.014c.112-.037.21-.163.346-.056");
}

.zb-xjbbix {
  fill: var(--svg-color--efef6b, #efef6b);
  d: path("M27.14 29.375c.065.026.128.075.207.056c.094-.015.092.031.061.096q-.184.006-.369.007c-.04 0-.098 0-.074-.06c.008-.024.065-.033.102-.046z");
}

.zb2cpksco {
  fill: var(--svg-color--f0ef08, #f0ef08);
  d: path("M28.18 24.25c.031-.104-.146-.204-.012-.312c.123-.011.157.119.251.157c.096.031.148.112.213.181c.029.057.013.101-.031.14c-.063.038-.124.023-.185-.003c-.082-.051-.176-.084-.236-.163");
}

.zbfrr7aec {
  fill: var(--svg-color--7b200a, #7b200a);
  d: path("M28.479 26.15c.016-.224.138-.151.255-.092c-.079.05-.157.1-.255.092");
}

.zc5ssbvrp {
  fill: var(--svg-color--1e1a00, #1e1a00);
  d: path("m25.551 34.971l.061.063v.021l-.053.02l-.046-.103q.017-.028.038-.001");
}

.zd1sbkb-g {
  fill: var(--svg-color--eff168, #eff168);
  d: path("M16.592 30.3a.1.1 0 0 1-.007-.041c.235-.124.41-.113.561.032c0 0-.015.01-.015.012q-.27-.003-.539-.003");
}

.zd6qhzzqp {
  fill: var(--svg-color--27270c, #27270c);
  d: path("M13.605 25.23c-.048.001-.098-.004-.124.052a.15.15 0 0 1-.124.06l-.006-.057l.053-.104c.083-.047.163-.09.201.049");
}

.zduxq3bor {
  fill: var(--svg-color--f4ef4e, #f4ef4e);
  d: path("M20.284 39.987c.082.024.174-.003.25.056c-.12-.003-.247.049-.355-.046q.049-.046.105-.01");
}

.zdxwivbxd {
  fill: var(--svg-color--4a4c00, #4a4c00);
  d: path("M14.748 34.863c-.009-.154.108-.125.197-.138a.1.1 0 0 1 .051.042z");
}

.zemtv85jy {
  fill: var(--svg-color--f0ec4c, #f0ec4c);
  d: path("M27.05 37.529q-.104.013-.211.023l-.083-.005c.087-.12.21-.043.315-.056z");
}

.zf2aq6b6e {
  fill: var(--svg-color--041502, #041502);
  d: path("M21.454 23.74h.045q.01.021.01.046l-.002.054l-4.559.009l-.973.001c-.05.009-.077-.004-.061-.063c.039-.063.111-.056.169-.08c.086.053.168-.02.253-.008q.045.003.086.022c.067.048.145.045.222.045h4.66c.051 0 .104.008.146-.026z");
}

.zhg01mbes {
  fill: var(--svg-color--edeb52, #edeb52);
  d: path("M28.554 29.885c-.094-.002-.194.047-.274-.038l.054-.015z");
}

.zignzcbrq {
  fill: var(--svg-color--f6f511, #f6f511);
  d: path("M30.791 25.942h.038l.179.155c-.044.135-.168-.05-.219.052q-.022.028-.049.007l-.058-.104c0-.048.013-.089.049-.12q.035-.014.06.01");
}

.zikq0l54x {
  fill: var(--svg-color--e7ea5c, #e7ea5c);
  d: path("m15.507 31.738l-.001-.067c.088-.044.174-.062.253.021l-.158.006z");
}

.ziy3d2bsw {
  fill: var(--svg-color--464600, #464600);
  d: path("M25.568 36.15q.064-.047.125-.095c.014.104-.058.143-.137.174z");
}

.zk131nb4b {
  fill: var(--svg-color--741b0a, #741b0a);
  d: path("M24.952 40.572c-.108.121-.231.115-.365.043l-.001-.004c-.005-.114.092-.092.154-.114c.049-.007.097-.017.146-.005q.057.022.066.08");
}

.zk7gnbp7q {
  fill: var(--svg-color--939596, #939596);
  d: path("M28.18 31.793a.2.2 0 0 0 .044 0q.007.017.017.031a.5.5 0 0 1-.051.271q-.027.026-.063.006c.003-.105-.053-.219.053-.308");
}

.zkli6v3_s {
  fill: var(--svg-color--777804, #777804);
  d: path("m16.642 29.891l-.062-.006q0-.142.002-.279l.064-.004c.073.097.064.194-.004.289");
}

.zkm1321xu {
  fill: var(--svg-color--f4f50a, #f4f50a);
  d: path("M14.585 24.761c.07.033.101-.034.145-.063l.008.12q.03.039-.006.07a.23.23 0 0 1-.232-.005l-.083-.079z");
}

.zl16jpb6z {
  fill: var(--svg-color--040203, #040203);
  d: path("M17.318 24.696c.081.033.071.089.053.144c-.003.012-.053.02-.056.015c-.031-.053-.018-.104.003-.159");
}

.zlp6tlnde {
  fill: var(--svg-color--493f40, #493f40);
  d: path("M25.36 32.818c.049-.135.016-.287.088-.419c.033.007.036.038.052.06c.006.128.044.266-.098.354q-.016.038-.042.005");
}

.zlulpubwz {
  fill: var(--svg-color--f6f925, #f6f925);
  d: path("m30.23 25.776l-.01.17q-.026 0-.051-.002l-.051-.05c-.033-.042-.045-.088-.024-.139a.1.1 0 0 1 .061-.042c.041.003.072.017.075.063");
}

.zm82g-wxt {
  fill: var(--svg-color--fdfd01, #fdfd01);
  d: path("M18.509 36.871q.076.056.149.114c.082.063.166.12.238.19l-.008-.003q.101.053.207.091c.054.037.118.057.169.097c.075.048.158.082.238.113l.058.02c.019.197-.128.14-.231.149a.4.4 0 0 1-.115-.044c-.13-.079-.273-.032-.409-.044q-.111-.005-.222 0c-.047.003-.093.012-.141.003c-.044-.013-.07-.05-.095-.087c-.097-.058-.202-.012-.303-.021a.5.5 0 0 1-.215-.033a.37.37 0 0 0-.242-.067h-.229q-.094.001-.19-.005a.3.3 0 0 1-.104-.031c-.087-.099-.2-.07-.311-.068a1 1 0 0 1-.224-.019c-.115-.043-.233-.026-.351-.033c-.065-.007-.128-.018-.172-.072c-.023-.138-.132-.072-.208-.082a1 1 0 0 1-.184-.021c-.159-.041-.322-.079-.44-.207c-.115-.145-.313-.236-.301-.465a.18.18 0 0 1 .085-.079c.104-.031.204-.033.296.029c.06.076.13.115.229.082a.4.4 0 0 1 .064-.006c.082.026.174-.02.25.041a.3.3 0 0 1 .043.046c.065.065.135.02.202.007a.4.4 0 0 1 .212.006c.056.021.099.062.147.093c.067.044.145.037.221.037q.081-.002.161-.022a.2.2 0 0 1 .099.006c.077.03.131.112.229.098l.065.006c.079.019.158.016.236.016q.093-.001.182.021q.068.024.136.051c.094.039.192.024.29.026h.15c.118.005.23.032.339.067m9.897-1.541l.077.053c.049.058.059.161.169.15q.046.03.096.057c.054.087.104.178.217.2l.181.196c-.02.097-.097.107-.176.121a1 1 0 0 1-.107.004a2 2 0 0 1-.208-.018c-.035-.003-.048.006-.014.006c.004 0 .009.012.014.02a.1.1 0 0 1-.017.059a.16.16 0 0 1-.149.057c-.043-.007-.088-.017-.132-.02c-.08-.002-.163-.014-.235.032c-.047.031-.094.064-.147.081a.3.3 0 0 1-.067.005c-.113-.014-.23.005-.339-.04c-.033-.008-.064-.02-.097-.026a.6.6 0 0 1-.219-.085a.5.5 0 0 0-.216-.129c-.072-.047-.156-.075-.231-.118c-.195-.154.043-.227.063-.34c.058-.067.115-.137.173-.202c.077-.05.074-.142.118-.209c.038-.068.096-.125.122-.2l.109-.163a.2.2 0 0 0 .015-.044c.021-.067.064-.099.137-.086c.082.055.128.158.238.175c.069.056.123.135.217.157l-.005-.003c.086.049.112.169.224.186c.069.03.094.131.189.124");
}

.znvnkpwkv {
  fill: var(--svg-color--4b2c01, #4b2c01);
  d: path("m25.352 39.27l.009-.033c.093-.056.179-.138.304-.111c-.085.091-.2.114-.313.144");
}

.zo6usob4b {
  fill: var(--svg-color--747700, #747700);
  d: path("m18.377 34.972l.051-.001l.002.054l-.053-.003a.2.2 0 0 0 0-.05");
}

.zoa_ld_nw {
  fill: var(--svg-color--333200, #333200);
  d: path("M14.484 25.07c.066.013.149-.004.146.105c-.067-.014-.153.042-.205-.043q.03-.03.059-.062");
}

.zoonxhbdp {
  fill: var(--svg-color--1d3d15, #1d3d15);
  d: path("m12.896 26.314l-.007-.066c-.001-.085.017-.154.125-.145a5 5 0 0 1-.118.211");
}

.zpby_1bxe {
  fill: var(--svg-color--4a0000, #4a0000);
  d: path("M19.907 37.37a.05.05 0 0 0-.034.015a.26.26 0 0 1-.168-.063c.089-.072.151-.043.202.048");
}

.zpix7vpwg {
  fill: var(--svg-color--2c2c04, #2c2c04);
  d: path("M15.865 31.584c.02-.037.056-.048.094-.049q.01.486.017.975a.13.13 0 0 1-.069.029a.19.19 0 0 1-.159-.138c.044-.11.133-.206.106-.339c0-.06.007-.117.004-.176c0-.035-.009-.057-.004-.023l-.022.007q-.052.009-.086-.028a.12.12 0 0 1-.005-.094c.028-.054.099-.072.118-.135q.004-.014.006-.029");
}

.zpkavphrz {
  fill: var(--svg-color--312600, #312600);
  d: path("m29.403 32.402l.098.047l-.194.02c-.055.031-.105.036-.154-.01l-.002-.006q.025-.022.05-.047z");
}

.zqf76qghn {
  fill: var(--svg-color--979400, #979400);
  d: path("m15.451 24.717l.01-.142q.1.016.2.036c-.024.125-.118.114-.21.106");
}

.zqg8bmbox {
  fill: var(--svg-color--4b4f0a, #4b4f0a);
  d: path("M14.687 30.04c-.135-.017-.266.14-.405.012a.6.6 0 0 1 .342-.057c.053-.031.063 0 .063.045");
}

.zqkg9hbtg {
  fill: var(--svg-color--171907, #171907);
  d: path("m12.03 29.03l-.029.251c-.053-.104-.063-.207.018-.304a.3.3 0 0 0 .011.053");
}

.zsgwtcbda {
  fill: var(--svg-color--dfe467, #dfe467);
  d: path("M20.987 40.877q.227-.006.454-.007a.07.07 0 0 1 .01.042c-.158.012-.314.027-.464-.035");
}

.zt58yaczq {
  fill: var(--svg-color--525000, #525000);
  d: path("M25.577 21.544q.017.01.032-.003c.045.046.13.024.16.097c-.092.022-.177.038-.192-.094");
}

.zuzq3cb1h {
  fill: var(--svg-color--262800, #262800);
  d: path("M22.893 25.469c-.086.057-.034.148-.06.221q-.037.018-.067-.007c-.172-.202-.39-.13-.602-.099a.65.65 0 0 1-.303-.003c-.18-.065-.363-.05-.546-.038a.2.2 0 0 0-.061.04l-.01-.005c-.057-.04-.045-.1-.043-.153c.053-.054.12-.061.188-.061c.469.001.937-.021 1.403.01c.048.017.093.034.101.095");
}

.zv_u4nbbo {
  fill: var(--svg-color--6a6e00, #6a6e00);
  d: path("M15.765 31.837c-.102.011-.138-.059-.164-.14c.051-.047.104-.043.158-.006l-.002.006q.03.007.023.021q-.007.017-.017.017z");
}

.zvb8bw-yl {
  fill: var(--svg-color--170603, #170603);
  d: path("M16.527 24.566q.006.052.007.103q.042.048-.001.099a.05.05 0 0 0-.009.034c-.058-.079-.07-.157.003-.236");
}

.zvmydpbnm {
  fill: var(--svg-color--28240c, #28240c);
  d: path("m30.497 36.41l.039.049c-.002.064-.023.112-.097.115c-.007-.01-.015-.02-.026-.022c-.021-.077.001-.128.084-.142");
}

.zx--lgb4r {
  fill: var(--svg-color--1d3a09, #1d3a09);
  d: path("M14.687 30.25a10 10 0 0 1-1.083.308c-.049.013-.063-.008-.048-.053c.363-.152.748-.22 1.131-.297z");
}

.zx-3cybdz {
  fill: var(--svg-color--6a6a18, #6a6a18);
  d: path("M30.17 36.771c-.051-.031-.06-.115-.138-.11c-.062-.024-.057-.072-.043-.123q.018-.037.058-.033c.054.074.145.118.169.215z");
}

.zx5wx7b2i {
  fill: var(--svg-color--2d2524, #2d2524);
  d: path("M22.693 37.746a.2.2 0 0 1-.005-.047l.36-.009c-.108.075-.233.055-.355.056");
}

.zy431wkly {
  fill: var(--svg-color--f1f203, #f1f203);
  d: path("M18.13 21.736a.2.2 0 0 1-.046.005c-.036-.028-.089.063-.117-.019l-.151-.078q.104-.06.206-.122l-.002.02c.055.017.12.019.137.093c.004.037-.01.068-.027.101");
}

.zytt8jbst {
  fill: var(--svg-color--71720e, #71720e);
  d: path("M28.899 23.692c-.213-.005-.3-.153-.369-.32h.058c.084-.017.129.042.18.092c.062.065.157.112.131.228");
}

.zz6v-sbxv {
  fill: var(--svg-color--fefe01, #fefe01);
  d: path("m30.699 36.1l-.066.101l-.136.21l-.084.142c-.098.02-.056.195-.194.167a.44.44 0 0 1-.204-.184a3 3 0 0 0-.513-.5a2 2 0 0 1-.176-.161c-.085-.085-.164-.177-.27-.243a1.8 1.8 0 0 1-.39-.313a.7.7 0 0 0-.173-.146a1 1 0 0 1-.29-.216a.6.6 0 0 0-.175-.145c-.069-.039-.14-.076-.195-.135c-.064-.082-.168-.133-.211-.235c-.036-.101.002-.193.021-.289a.7.7 0 0 1 .067-.166c.048-.079.072-.166.098-.255a4 4 0 0 0 .104-.4q.006-.035.016-.069c.03-.079.023-.17.064-.247a.19.19 0 0 1 .159-.087c.077.005.142.04.196.092c.059.04.058.149.162.139c.099.024.166.097.243.155c.06.078.122.152.223.182c.193.106.363.246.516.406a.36.36 0 0 0 .237.205a.3.3 0 0 1 .13.11a.66.66 0 0 0 .225.21c.072.055.149.102.221.158c.094.085.184.174.224.301l.003.006c.034.117.138.18.21.266c.041.065.076.136.15.172l.051.154c.043.064.036.134.018.203l-.126.205a.5.5 0 0 0-.135.207");
}

.zzjrivv-v {
  fill: var(--svg-color--3a0000, #3a0000);
  d: path("m29.509 27.01l-.003-.067c.018-.069.073-.064.128-.063a.12.12 0 0 1 .064.042c-.04.079-.112.089-.189.088");
}

</style>
