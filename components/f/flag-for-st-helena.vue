<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qnets5b4d"/><path class="lkqw--zvs"/><path class="km5x11bgu"/><path class="u989h0p9t"/><path class="r805eeimt"/><path class="lhaa14yvz"/><path class="rinzqfbrp"/><path class="ny6tnbnnp"/><g class="d2kvgvbvc"><path class="zv_v73bvv"/><path class="r6803zb2z"/><path class="frcurqyni"/><path class="b2be91b4q"/><path class="qq93czbpf"/><path class="bqh8uybhw"/><path class="w2hg8_njs"/><path class="n3i_9obxu"/><path class="ec3_qc1zf"/><path class="im4olbjbg"/><path class="bgzmq_bet"/><path class="lhoxjt50x"/><path class="hhtzz0brx"/><path class="aowjxqohl"/><path class="zrx0itx7k"/><path class="z8guc6dvz"/><path class="mg6j8tbju"/><path class="roy5oi95m"/><path class="c1-5axb5j"/><path class="i103nc18k"/><path class="i9t70lb8l"/><path class="mvdv_fbve"/><path class="rz8685bwq"/><path class="agtc2vbqz"/><path class="jo83idbol"/><path class="a6vox5bxg"/><path class="v2e-sab5l"/><path class="w0wsp8blp"/><path class="deshtcewc"/><path class="kpfy2bbxy"/><path class="nppq9zijl"/><path class="nqu-7em5c"/><path class="c6td-037m"/><path class="crhlfsboz"/><path class="saavr-btq"/><path class="tt78j4f1y"/><path class="h9rz_fr0f"/><path class="drlov32mv"/><path class="a_ez1_b_a"/><path class="cxauqfo-o"/><path class="r7nz5g7wy"/><path class="rfu_8lcdv"/><path class="o7e_q6b0e"/><path class="g4-7kkbkg"/><path class="rbojz5aeg"/><path class="laqu5jbim"/><path class="j6722qbiw"/><path class="n6u2-ubxt"/><path class="lt-c84bjx"/><path class="nvsy0ez-x"/><path class="ry79d14lj"/><path class="j_hoc9boy"/><path class="zd81nmbil"/><path class="xezpymbph"/><path class="l3zr8hber"/><path class="ovn2mo-io"/><path class="ocm63yqka"/><path class="cpl4ielzs"/><path class="pnysh3b4k"/><path class="lew8ocb3f"/><path class="u1-r-wirc"/><path class="hhbec5kvd"/><path class="cctxuhffo"/><path class="csuwd5b-d"/><path class="r7-vqvbfx"/><path class="xrnlb2vhn"/><path class="wr2gc3d2c"/><path class="x0rkbzb1p"/><path class="j3mxojx7l"/><path class="uj3eu17qt"/><path class="f2yjp0bvq"/><path class="b5r740bnm"/><path class="hjkyq9bhu"/><path class="vbozinowv"/><path class="g7tcjej8u"/><path class="xl65szb0r"/><path class="bzp5a6bny"/><path class="ie763cbsv"/><path class="qshzh-brm"/><path class="ww0m4zkjj"/><path class="t0v_wutbm"/><path class="eg-n8dbaq"/><path class="xjrjovuzg"/><path class="syimo33sg"/><path class="vjy51kb-q"/><path class="a739ifbpm"/><path class="w3-nu-xyb"/><path class="dc15q8tls"/><path class="cq0nq5bee"/><path class="rxc0yrbky"/><path class="fw0lbgbmt"/><path class="iajg6sr7b"/><path class="zlaxx1bhc"/><path class="zv6v4x7jy"/><path class="d40ymcc8c"/><path class="wcd_gcb1y"/><path class="x1i8mlb8n"/><path class="th0h2aclz"/><path class="ecogoe_ga"/><path class="t6m6bhbmz"/><path class="l-j-x9bgn"/><path class="y7tu0qbcw"/><path class="q2c2-tbog"/><path class="bu7kt0bap"/><path class="r1b5-9byd"/><path class="m8ewlb42g"/><path class="mz79d-brw"/><path class="s9tjidp8y"/><path class="bl9e9n85w"/><path class="wca5dm17u"/><path class="wz5d27tjh"/><path class="z4875ct8k"/><path class="x99dgx0nf"/><path class="fbkvlyz_q"/><path class="p6r5mxbuc"/><path class="rlurilb-g"/><path class="ba2m55b6x"/><path class="sjlja94us"/><path class="eilprdkuu"/><path class="irx08obdw"/><path class="caeahgtxt"/><path class="vqd6uebhn"/><path class="btyii2bxx"/><path class="m-c7wvbwh"/><path class="jxpdknbil"/><path class="pp4mhn5sn"/><path class="pk6od3eaw"/><path class="hka8m-uzp"/><path class="hzbab8bkc"/><path class="v828lveya"/><path class="hivpijqcv"/><path class="rfb3cmbps"/><path class="s1uwkwb6d"/><path class="ynex2hbmw"/><path class="lw39303oi"/><path class="uh78wb_4f"/><path class="wl-qftbop"/><path class="kgc0dnbnx"/><path class="yyfiz5b3w"/><path class="olv6cl2co"/><path class="g2ghs4bem"/><path class="llz5dkaqg"/><path class="ciqu-tz2h"/><path class="v92478tmz"/><path class="k8zer6bus"/><path class="f29d8qo8n"/><path class="fltpcgwqr"/><path class="tn7-3xwdg"/><path class="y74iz7bpa"/><path class="jww3y3_gn"/><path class="afe_ynbrm"/><path class="bhet17b5t"/><path class="zrsmnobnp"/><path class="ufs6fuhoa"/><path class="gaktgn-gz"/><path class="cp16ksbrj"/><path class="y3g2uhkhy"/><path class="wdc4_tb3i"/><path class="lv1k6i69z"/><path class="zm5x6ibrc"/><path class="tzk6gdbkn"/><path class="cux3k3b-a"/><path class="lst-bubtu"/><path class="qs8p65vtp"/><path class="mdwcnub4q"/><path class="jtqyig_0h"/><path class="pcfr6ac-t"/><path class="tn52zuncq"/><path class="ifo7ekb8v"/><path class="soi5kvfii"/><path class="zw0i49aex"/><path class="f89zagbml"/><path class="as6npd_0j"/><path class="jjiw8ibvv"/><path class="jvxt7nb2v"/><path class="u10f-mbgt"/><path class="df__ufc3u"/><path class="hwdiqabgf"/><path class="urpuz9bnj"/><path class="gedsnpbns"/><path class="abz5q9byb"/><path class="tu1x1ibha"/><path class="v04gbfktc"/><path class="l8hpb--_y"/><path class="w56i7_usr"/><path class="vgj0ulb8a"/><path class="fhm1cvb4f"/><path class="c_x19hbqr"/><path class="so8_q2fzn"/><path class="sxf2tgbcm"/><path class="mfmh3qbou"/><path class="jhv5yj_6m"/><path class="m9wuh0bpx"/><path class="wao6zccne"/><path class="kv9iikv-e"/><path class="dv0tm2bgu"/><path class="ayw_43y6t"/><path class="qnto7ebbc"/><path class="fyp1c3b3a"/><path class="yt4mgpbvg"/><path class="xm1k8srxm"/><path class="s4gp0jsbq"/><path class="vou7ys6bz"/><path class="pjywr2k1m"/><path class="wakj7mbzb"/><path class="ataarddez"/><path class="a7qec5ftj"/><path class="xqccn2bau"/><path class="bv-v_gb5k"/><path class="jjr_gqpor"/><path class="kv-b9o32x"/><path class="tpdyvabyw"/><path class="yr2tterog"/><path class="waq9kkb1g"/><path class="lvgginbhq"/><path class="a68lx7ndj"/><path class="qhfkstb7k"/><path class="sggv8gusm"/><path class="cz0dqrjti"/><path class="yab8x8bnx"/><path class="wvuqigorc"/><path class="whb1cbbtc"/><path class="l_1-l0bbr"/><path class="qegvcpbel"/><path class="upjy9_n8p"/><path class="zqji2ikvg"/><path class="yx7ehdchk"/><path class="pfw36cbti"/><path class="litlv8bse"/><path class="lkx3wjp5p"/><path class="otejvr5gk"/><path class="vsoi0xt1u"/><path class="o6nlpebjn"/><path class="lbv6ubsiy"/><path class="zup9ub0eg"/><path class="p3jvqmztl"/><path class="kdlw9eb7r"/><path class="rsmqawbnp"/><path class="f02cytzfn"/><path class="rwccixbbc"/><path class="gnmiyut7r"/><path class="yg9cjacuw"/><path class="gnp6kbbye"/><path class="m4mrltelu"/><path class="a7kftrb_e"/><path class="s7bhzm0wt"/><path class="jcqk3espa"/><path class="k0jncobnd"/><path class="sa_-7db4h"/><path class="vt_yg4y2l"/><path class="gkbboujxq"/><path class="h2ulc9rvt"/><path class="sl743tb3y"/><path class="vf9lz8b0z"/><path class="cqtvtzbsh"/><path class="tkmzmdups"/><path class="ck40qabvw"/><path class="mdqsik68j"/><path class="h2xjhmlqu"/><path class="t1xd_vbdn"/><path class="q123ey2_w"/><path class="r_0bgd-yp"/><path class="gpnre09gr"/><path class="zu836_15s"/><path class="frrg2dbqq"/><path class="g1snzrj9j"/><path class="b-60uq0ac"/><path class="of5ff8bbz"/><path class="g268rvbtw"/><path class="qqfu3wbvn"/><path class="mh4-r927n"/><path class="ga74lpitr"/><path class="cdqfl4n8k"/><path class="fzq1bdcpe"/><path class="no72ws6sj"/><path class="q7xkxsb_f"/><path class="y5wlaabnj"/><path class="c3yetqtaf"/><path class="ttmu0cc4u"/><path class="deds7cfls"/><path class="en1908bds"/><path class="nobp53biz"/><path class="yc_f8xjnu"/><path class="ve4fqjr9x"/><path class="ursyojbfb"/><path class="h96tzp7wb"/><path class="wbfodzw6a"/><path class="ru-krzb-i"/><path class="o9dyx4b7c"/><path class="t78qlobio"/><path class="zv7q05b2v"/><path class="ldbo7ibej"/><path class="u4xj2zrmd"/><path class="ztvgpbc1y"/><path class="b5u9h_bmz"/><path class="nnj_o-b7j"/><path class="vk5f2-c-v"/><path class="sebyv_i5p"/><path class="g4q4u-bgi"/><path class="qel37ac_n"/><path class="o7xcgkbin"/><path class="hzyb8mbyk"/><path class="q-iwemqbr"/><path class="xs8mn31os"/><path class="rie3oq7cu"/><path class="l-yghvbri"/><path class="laj568bfn"/><path class="l2l0rjbme"/><path class="vpj9n3-tk"/><path class="krh2n9bjn"/><path class="vnnrk-bli"/><path class="jpoiibbok"/><path class="w-rvkrbgg"/><path class="h1bcsp6yg"/><path class="jg56k0b2p"/><path class="j4r5qlbkl"/><path class="cygu6lipy"/><path class="audfwnbvw"/><path class="jy_69w-gl"/><path class="tr4_ikirg"/><path class="yqox7-3ju"/><path class="bxaq1kbgg"/><path class="c2z9fbb-o"/><path class="l9fpzikng"/><path class="sqagtabmu"/><path class="e5aq8f2hv"/><path class="msht68bej"/><path class="koa3sf-di"/><path class="t1twvmbeb"/><path class="ik2e__b5v"/><path class="tuwa7x00l"/><path class="h5g2hebnu"/><path class="hnn0m1bhg"/><path class="collklg7i"/><path class="x-bh2gb8d"/><path class="qjza54bzo"/><path class="rvt036byb"/><path class="fjmg8fbpt"/><path class="qnswj1beb"/><path class="lny97finu"/><path class="gn95frdbj"/><path class="wusk9e47v"/><path class="l-o4qg6nl"/><path class="cohjacske"/><path class="tlysuv6zy"/><path class="szdw3_buz"/><path class="t8kgc1d4v"/><path class="gt46jvbft"/><path class="r-emribxs"/><path class="o43omzb2m"/><path class="re7xufbjt"/><path class="u29q-2n3i"/><path class="axwzbzoid"/><path class="gly00rb4k"/><path class="gwf935yem"/><path class="lg3li_mbp"/><path class="zclo-xi9a"/><path class="ld9lntv3x"/><path class="ifsjtqihb"/><path class="xag2r1qqx"/><path class="hvnxhnbla"/><path class="u5yoi-_ua"/><path class="s0sp2ccgx"/><path class="ca9rlza4k"/><path class="sm8bl9m7y"/><path class="o-vsmrbtr"/><path class="ksvezacev"/><path class="ym-1_2bpp"/><path class="zx9_vph2e"/><path class="dkev40nvf"/><path class="jeiyxrb6s"/><path class="twsc9-b4l"/><path class="e943_bc7k"/><path class="e5uiwvr7j"/><path class="jc8x92bab"/><path class="stfqbky5y"/><path class="n2v27wawo"/><path class="wlfr9ubfq"/><path class="jff5enb5x"/><path class="w3ju2u80e"/><path class="mt9ktcd2v"/><path class="qeu0babxy"/><path class="dl_b8qyig"/><path class="mpyz50bjj"/><path class="pefyvsbtr"/><path class="unxw75u2b"/><path class="yhtp4lhkj"/><path class="atxbs-stn"/><path class="msb8ltbdd"/><path class="f7wv5ublv"/><path class="gkmn-_yrf"/><path class="fk0ui_55x"/><path class="mcd2e68eu"/><path class="s4zfowbev"/><path class="nnttifb6y"/><path class="ih9yt7b5f"/><path class="wmejh-ban"/><path class="rzp3mb6ek"/><path class="mhloddcuz"/><path class="iwjjbd5ak"/><path class="nr23_1bro"/><path class="xz9id_b4b"/><path class="g-be_-d4x"/><path class="tiuo1hbfc"/><path class="xfd0wsvbb"/><path class="jjre5bczz"/><path class="cmr5gkbvn"/><path class="w3mc0lbrd"/><path class="jotua5b3t"/><path class="ddx6x2bdh"/><path class="rlw545vkf"/><path class="k88eajppw"/><path class="plnejbbww"/><path class="ero4-t3-m"/><path class="xu8_arb8z"/><path class="mdop79cpa"/><path class="zcbihp2vo"/><path class="thxwoqbmp"/><path class="kb_jwac4u"/><path class="yltjfybmo"/><path class="tu6oi3b9x"/><path class="si50mvbuw"/><path class="j18a0kbue"/><path class="th4pekb_o"/><path class="q2qn726ni"/><path class="ogwta-bdt"/><path class="g6a49fb1u"/><path class="xrgaq8bsk"/><path class="z28cfibch"/><path class="t7kpdjb_d"/><path class="jqelgrb_x"/><path class="ovrkm3b_m"/><path class="jk3vibbej"/><path class="hwgyo49jx"/><path class="i02jpcbtm"/><path class="p_pf-6b0s"/><path class="pud5fo6ne"/><path class="b8ge15bec"/><path class="m7fs0-btl"/><path class="b4x790xbu"/><path class="bn-lv8b0g"/><path class="v1l4ig5wu"/><path class="c60chibct"/><path class="pmf1tzclr"/><path class="vbmfr4r_j"/><path class="meyoc7kfh"/><path class="hofmrcc0y"/><path class="jvi_65bln"/><path class="pt4uouhwk"/><path class="p-qz66b8n"/><path class="zr_v6n9xk"/><path class="fk3wqmb4p"/><path class="z1s52sbpd"/><path class="vb2q53zcm"/><path class="x__nbdbgp"/><path class="lp6iic5od"/><path class="o2nbulbxh"/><path class="v77_h3bui"/><path class="o79c40u0x"/><path class="lur5xe2uz"/><path class="i8685nbwx"/><path class="v3ge6vbsv"/><path class="k6ux2veua"/><path class="dq57xcyma"/><path class="pwox2odfe"/><path class="wp1kbmy0h"/><path class="ectn0jfpq"/><path class="te6_ryb5y"/><path class="m2n_zubze"/><path class="k2s-ucblc"/><path class="e4rlrsb5q"/><path class="c6c39-0zd"/><path class="jmnl93b4j"/><path class="n3bql2sxf"/><path class="ge2jdub-q"/><path class="s7zlse0-k"/><path class="u9cf1abui"/><path class="qlvhokbjh"/><path class="gdj_ojwri"/><path class="xu_ppz-3x"/><path class="bv7q_xb5d"/><path class="ke_2kcbnl"/><path class="ex4i3rb6v"/><path class="ow_y-lbbe"/><path class="kqdvrm-lf"/><path class="zcw_91-1k"/><path class="aom63mm1v"/><path class="lf2z7yb-b"/><path class="bhnpbvn4s"/><path class="orf-a94bz"/><path class="amyn2bchs"/><path class="ejkkq1bor"/><path class="p46q6o53f"/><path class="n4us_mb1r"/><path class="voytp2bpm"/><path class="wzpl8cc5a"/><path class="uja1mrayy"/><path class="xbeuvybrf"/><path class="f96z6tb2g"/><path class="yld_4zfto"/><path class="q9hmn4l4o"/><path class="sscx3_bzu"/><path class="pucaklbfi"/><path class="e624yb15k"/><path class="q9hn7qbct"/><path class="nmfqzcuqb"/><path class="i_xs5g0gw"/><path class="rfdzfub4m"/><path class="d0o2dzb1s"/><path class="klg5uga7r"/><path class="ol_90rbwk"/><path class="hnswvql5h"/><path class="bjhu-kbpu"/><path class="h-hq-vb4k"/><path class="fi9982baj"/><path class="gjz9c7fbo"/><path class="mxtpm-cla"/><path class="txx79sb_h"/><path class="groz8gb5h"/><path class="ot94h8hda"/><path class="d8cwteefk"/><path class="ir2o-pbxi"/><path class="diehu9jdk"/><path class="vi175hfzl"/><path class="y7cb8-blk"/><path class="jsxe1hbhc"/><path class="l57b3tplw"/><path class="sbc675b0y"/><path class="aq0ny8brg"/><path class="dfssgpbjh"/><path class="nms4znbav"/><path class="gwyf81b0b"/><path class="sq3mczbod"/><path class="uv4zb_j1a"/><path class="gx9c6lbxr"/><path class="xcj0_ibqg"/><path class="mac0h934j"/><path class="knwgn0bxc"/><path class="cghuyybnc"/><path class="rozy09-2c"/><path class="u667ji33e"/><path class="sfaenhtvc"/><path class="r2f52wbwm"/><path class="beoxxxb_r"/><path class="uxrbzxg8q"/><path class="ll2k9xt-q"/><path class="ifi9r9bmx"/><path class="t0a68rbpm"/><path class="u5vs2glju"/><path class="zzxo8ubeo"/><path class="q1cp3mbtu"/><path class="sjdkjqb5m"/><path class="ig6-me4ra"/><path class="i08bmib8y"/><path class="teju7ubgs"/><path class="ku1zx9pra"/><path class="ld6estb2t"/><path class="v6uvrxbuo"/><path class="abvitbcwf"/><path class="i7abhqbtx"/><path class="k88987b1v"/><path class="qaxyvbbjo"/><path class="l39dsrbta"/><path class="tasfpsr1s"/><path class="agdjs6kpa"/><path class="bwgi8f6fo"/><path class="zb-07obzx"/><path class="fkgflsnzs"/><path class="l3x5q1pak"/><path class="f3i9bt82j"/><path class="bn8j-tb5q"/><path class="iwogh8cni"/><path class="mqw4wcbrn"/><path class="okcvfjacn"/><path class="e6966sbon"/><path class="kbx13cctw"/><path class="fxkmwnbij"/><path class="w_dt9smgo"/><path class="xh1uhgthr"/><path class="q1kchwbyk"/><path class="cf8mw0ydv"/><path class="l0licj1sj"/><path class="a8btscc5y"/><path class="ds2nq9bkl"/><path class="y5fv1gbuq"/><path class="eg3y4_bdw"/><path class="a4vk20det"/><path class="eo39abm2y"/><path class="c49jbgbnm"/><path class="fda3zxb7l"/><path class="qc18vkbkv"/><path class="gzdtn4m5h"/><path class="lhe7yvbig"/><path class="wunj6ob0q"/><path class="u92hl0b3e"/><path class="ebg-71twy"/><path class="vg7q1b2bz"/><path class="iuizy8b1u"/><path class="j4xg7umzz"/><path class="sh0v210jr"/><path class="zbhlvcb-w"/><path class="gzgs43ypv"/><path class="avmpt9bep"/><path class="j3gqe6g2z"/><path class="rsh36bgqb"/><path class="ik3x-ztty"/><path class="rrtxfgqus"/><path class="fn5_wnbnm"/><path class="bwvja9fvf"/><path class="nxzqcmpcc"/><path class="obpro_bld"/><path class="k1fl-ob7i"/><path class="qpdp3cblf"/><path class="rhjcfqb-s"/><path class="iq6krieyx"/><path class="asit-k98c"/><path class="e3sz80bxg"/><path class="ykh7esw0c"/><path class="y5a5ttb2j"/><path class="do8izcckt"/><path class="k44cku7wk"/><path class="bd8-x0b0d"/><path class="bzl9siyvu"/><path class="z9c3x0b-c"/><path class="r8eqqzb-g"/><path class="jsqvsxrgx"/><path class="chywqhlon"/><path class="o_aembbgh"/><path class="ujx2u4-5j"/><path class="pnck8ac3i"/><path class="rngmkibnt"/><path class="hrwred6hu"/><path class="tw4t16b6i"/><path class="cep2qlrqx"/><path class="zayirpb-s"/><path class="o_iuexbxy"/><path class="sd-dqm09r"/><path class="pnn_uzbfr"/><path class="k15824bij"/><path class="vwipx0ntj"/><path class="oto5krb8b"/><path class="h5vqhpdms"/><path class="z863ruity"/><path class="k6o--_k_u"/><path class="d-sejsv9g"/><path class="q_kbhvvlm"/><path class="v9_-9kbmj"/><path class="vrqxnobmj"/><path class="alfl73old"/><path class="fmr6lhnqc"/><path class="js1xiy44u"/><path class="ncdtz9b2r"/><path class="i4vhf0ksp"/><path class="de0s6o5fn"/><path class="th-_8il4w"/><path class="bsor1urva"/><path class="gne-qib5e"/><path class="bsvsfubam"/><path class="y0j350rwv"/><path class="qvmzvbs3b"/><path class="rcqvrwb_m"/><path class="z6gexwb8s"/><path class="b7ehe-b-o"/><path class="sjtatbc0z"/><path class="svjcqgbeb"/><path class="ewgk3fb_k"/><path class="fjbbetyxz"/><path class="xmgrvkb0o"/><path class="cgkbnbb5k"/><path class="ckfl78x0p"/><path class="jit9j4fca"/><path class="rjmuwabfk"/><path class="mg90flb8b"/><path class="eok4-t_5n"/><path class="jo2su9qqt"/><path class="orumdob6z"/><path class="cbh509l_t"/><path class="kplk1rb-l"/><path class="xlgtk4zib"/><path class="g8vo48b4i"/><path class="hx37ucbvb"/><path class="vfswlibxm"/><path class="yh294k5-x"/><path class="b-n7edjjd"/><path class="jnv_imvua"/><path class="z6im_6b2s"/><path class="fg3dxccev"/><path class="ajmjoel9b"/><path class="gjnsfebqf"/><path class="jckcn65oj"/><path class="bfiy6-vze"/><path class="c752b1bgq"/><path class="dc2ir0bag"/><path class="os0n5ab6f"/><path class="lp6y-ybnv"/><path class="g4uj0fbru"/><path class="uw7zanbws"/><path class="g1m3m6btj"/><path class="mdpdt95nr"/><path class="lpkffj4kf"/><path class="wexojfb2y"/><path class="lkcu7bcaa"/><path class="cl1iug50b"/><path class="c64pb46ba"/><path class="s22rsgkvn"/><path class="jhmwzobhm"/><path class="rw4zh3swr"/><path class="e9n62p9cy"/><path class="f8d8vxb7k"/><path class="ba1x7obtq"/><path class="g2q_b052e"/><path class="rra-a-w6p"/><path class="b_rlkygzd"/><path class="j_kxcfv-e"/><path class="a1o-q9pjy"/><path class="icbl1e5df"/><path class="nl9rp3byb"/><path class="v5u2g1ytp"/><path class="o88i-f5sy"/><path class="qag1q1bzl"/><path class="hq2zgdctd"/><path class="t_874wura"/><path class="d9a4wbkmk"/><path class="t8-7rlbtp"/><path class="mqvx_82jw"/><path class="w4ybocb3g"/><path class="gwwgxz1qy"/><path class="cdltxjudn"/><path class="va_ticcky"/><path class="j3k14db6t"/><path class="wg58io7uz"/><path class="ca7j4ibir"/><path class="sm9x4dbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-st-helena" /></template>
<style>
.a_ez1_b_a {
  fill: var(--svg-color--bfc2ca, #bfc2ca);
  d: path("M54.47 40.543a1.7 1.7 0 0 1-.214.581c-.056 0-.09-.031-.114-.074c-.029-.063-.02-.127-.018-.191a.34.34 0 0 1 .106-.271c.073-.055.149-.093.24-.045");
}

.a1o-q9pjy {
  fill: var(--svg-color--212223, #212223);
  d: path("M48.731 36.728a.2.2 0 0 1 0 .053c-.173-.001-.346-.006-.522-.007a8 8 0 0 0 .313-.069q.104.008.209.023");
}

.a4vk20det {
  fill: var(--svg-color--392709, #392709);
  d: path("M45.2 39.986a.3.3 0 0 1-.01.069q-.036 0-.067-.002a.18.18 0 0 1-.132-.075c-.059-.091-.096-.184-.071-.295c.056-.106.115-.13.185-.011l.024.16c.04.045.111.071.071.154");
}

.a68lx7ndj {
  fill: var(--svg-color--ebeff2, #ebeff2);
  d: path("M54.851 38.701q0 .05-.006.099c-.093.072-.072.209-.163.285l-.063-.164c-.107-.116-.079-.257-.056-.388c.15-.896.311-1.785.352-2.694c.004-.1.026-.195.107-.266c.228-.016.101.235.227.298l-.007.305c-.081.104-.088.224-.081.347c.035.165-.035.315-.072.469c.035.12-.086.242-.005.366c.02.144-.03.275-.083.405c-.06.109-.016.237-.07.351l-.003.087c-.037.165-.085.33-.077.5");
}

.a6vox5bxg {
  fill: var(--svg-color--e7eaf1, #e7eaf1);
  d: path("M54.05 27.1c.271.004.518.096.747.234a.17.17 0 0 1-.089.122a.3.3 0 0 1-.156.019a1 1 0 0 1-.375-.148a.4.4 0 0 1-.15-.135a.09.09 0 0 1 .023-.092");
}

.a739ifbpm {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M53.22 26.892c-.134-.039-.314.031-.377-.169q.191.048.384.093z");
}

.a7kftrb_e {
  fill: var(--svg-color--6a6a6a, #6a6a6a);
  d: path("M43.798 26.433a.07.07 0 0 0 .002.064c-.129.037-.253.17-.383.006l.096-.065z");
}

.a7qec5ftj {
  fill: var(--svg-color--6e6e6e, #6e6e6e);
  d: path("m39.633 31.09l-.049.038c-.109-.11-.009-.258-.067-.381q.004-.523.004-1.044q.057-.044.11.006a.4.4 0 0 1 .112.224c-.023.386.131.792-.11 1.157");
}

.a8btscc5y {
  fill: var(--svg-color--35485e, #35485e);
  d: path("M47.19 40.902q.005.068.004.132c-.025.028-.055.056-.08.08c-.03-.043-.026-.092-.026-.14a.16.16 0 0 1 .025-.091q.048-.025.077.019");
}

.abvitbcwf {
  fill: var(--svg-color--415973, #415973);
  d: path("m47.729 40.11l.071.272c-.057.03-.067.084-.071.144c-.086.075-.177.138-.294.065c.03-.203.084-.39.294-.481");
}

.abz5q9byb {
  fill: var(--svg-color--6c4200, #6c4200);
  d: path("m42.02 41.14l-.044-.29c.086-.086.045-.198.065-.3c.056.471.512.839.351 1.365c-.143.114.01.326-.144.44l-.005-.303c.026-.324.046-.653-.223-.912");
}

.afe_ynbrm {
  fill: var(--svg-color--09c670, #09c670);
  d: path("m48.45 44.36l-.001.056c-.182.014-.359.02-.524-.076l-.002-.062z");
}

.agdjs6kpa {
  fill: var(--svg-color--3c536b, #3c536b);
  d: path("M45.696 40.14c.01-.076.02-.146.029-.223c.051-.057.116-.066.187-.056c.106.04.216.073.314.138c-.015.157.091.354-.135.45a.25.25 0 0 1-.182-.065c-.058-.09-.149-.155-.213-.244");
}

.agtc2vbqz {
  fill: var(--svg-color--f8f8fa, #f8f8fa);
  d: path("M44.23 26.27c.069.036.176-.009.214.095c-.026.109-.109.125-.202.125c-.155-.039-.303.041-.458.038c-.092-.001-.181-.001-.269-.032c-.05-.026-.093-.061-.083-.128z");
}

.ajmjoel9b {
  fill: var(--svg-color--303030, #303030);
  d: path("M46.17 27.865q.083.039.161.081l-.145.131c-.123-.035-.247-.069-.413-.119c.142-.138.284-.062.397-.093");
}

.alfl73old {
  fill: var(--svg-color--5b3200, #5b3200);
  d: path("M44.597 39.38c-.077.156-.142.329-.368.296c-.133-.134-.249-.275-.232-.482c.008-.101-.054-.16-.146-.186l.005-.082l.3-.37z");
}

.amyn2bchs {
  fill: var(--svg-color--5d662a, #5d662a);
  d: path("M50.911 34.706c-.014-.099.067-.22-.063-.293q.037-.075.079-.151a.4.4 0 0 1 .057.01q.007.217.012.436z");
}

.aom63mm1v {
  fill: var(--svg-color--8cc1fa, #8cc1fa);
  d: path("m52 39.734l-.078-.073c-.01-.017-.018-.029-.026-.046l.004-.034a.34.34 0 0 1 .191-.191c.071-.021.135.001.194.042l.225.232c.037.115-.057.199-.068.303l-.297-.002c-.077-.059-.036-.191-.145-.231");
}

.aowjxqohl {
  fill: var(--svg-color--c7cad3, #c7cad3);
  d: path("m45.23 26.16l.163.078q.042.071-.001.141c-.118.086-.26.023-.385.061a1 1 0 0 1-.146-.006c-.111-.029-.225.01-.335-.002l-.095-.022c-.076-.03-.16-.048-.2-.135c.328-.094.662-.109.999-.115");
}

.aq0ny8brg {
  fill: var(--svg-color--445e7a, #445e7a);
  d: path("m48.17 40.452l-.142-.141c.013-.087.012-.179.033-.266a.14.14 0 0 1 .062-.064c.046-.013.088.001.129.03q.031.032.057.068c-.075.114 0 .285-.139.373");
}

.as6npd_0j {
  fill: var(--svg-color--0a1526, #0a1526);
  d: path("M46.9 43.652c-.02-.161.124-.146.208-.196l.008.09c-.06.033-.12.071-.178.104z");
}

.asit-k98c {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M49.875 34.34c-.126.092-.248-.07-.374-.007c-.128.103-.254-.063-.382-.008l.007-.006c-.115.094-.256.109-.4.108a.65.65 0 0 1-.504-.101c-.086-.041-.118-.122-.146-.203c.171-.154.396-.148.587-.12c.407.055.824-.054 1.229.066c.187.103.057.185-.017.271");
}

.ataarddez {
  fill: var(--svg-color--eaeaea, #eaeaea);
  d: path("m39.576 32.461l-.009-1.049q.002-.109.006-.216q-.058-.058.004-.103a.11.11 0 0 1 .113.046c.084.178.05.38.121.563c.013.492.099.991-.071 1.479c-.133.082-.139-.019-.144-.105c-.015-.205.027-.413-.02-.615");
}

.atxbs-stn {
  fill: var(--svg-color--212e3c, #212e3c);
  d: path("M50.712 40.24c.005.065.001.124-.063.164q-.26.27-.535.017a.36.36 0 0 1-.057-.224a.23.23 0 0 1 .047-.104c.128-.07.255-.015.381-.002c.095.022.177.06.227.149");
}

.audfwnbvw {
  fill: var(--svg-color--424242, #424242);
  d: path("M55.24 29.36c.016-.004.031 0 .049 0l.01.449q-.032-.005-.062-.004z");
}

.avmpt9bep {
  fill: var(--svg-color--eeefef, #eeefef);
  d: path("m46.56 37.75l-.088-.146a.34.34 0 0 0 .17-.175c.363-.114.736-.019 1.104-.05c-.071.218-.221.32-.448.291a1.3 1.3 0 0 1-.443.113c-.1.007-.207.053-.295-.033");
}

.axwzbzoid {
  fill: var(--svg-color--050501, #050501);
  d: path("M49.08 30.653c-.392.017-.598.227-.651.611a2 2 0 0 1-.109.393c-.1.286-.171.539.265.613c.145.022.288.15.257.384c-.217-.078-.395-.3-.64-.209c-.274.104-.173.37-.191.602c-.233-.115-.173-.335-.238-.494c-.229.005-.305.231-.482.339c-.064-.312.195-.4.368-.566c-.18-.112-.311.075-.461.036c-.106-.24.085-.339.241-.364c.469-.08.566-.383.54-.786a.4.4 0 0 1 .042-.101c.077-.1.107-.223.154-.336c.146-.392.162-.4.566-.298c.112.009.227.006.326.075q.045.045.013.101");
}

.ayw_43y6t {
  fill: var(--svg-color--2d261e, #2d261e);
  d: path("M42.02 43.55q-.005.036-.006.072c-.029-.023-.057-.049-.085-.069l-.126-.232c.137.013.203.096.217.229");
}

.b_rlkygzd {
  fill: var(--svg-color--d9da04, #d9da04);
  d: path("m46.49 38.19l-.083.154l-.074-.012l-.019-.515c.084-.08.149-.073.163.052c.012.108.01.216.013.321");
}

.b-60uq0ac {
  fill: var(--svg-color--080402, #080402);
  d: path("M50.48 42.33c.236-.126.488-.032.73-.058c.126-.015.293.051.311-.164c-.064-.146-.277-.21-.235-.42c.104-.126.237-.114.375-.067c.095.048.123.134.131.232c-.011.074.032.139.069.294c-.033-.163-.087-.234-.069-.319c-.018-.193.103-.234.258-.229c.231.011.272.19.274.3c-.029-.098-.043-.253.158-.338c.191-.02.385-.048.569.042c.069.085.063.188.044.288c-.032.117-.094.221-.141.332c-.819.149-1.646.119-2.474.107");
}

.b-n7edjjd {
  fill: var(--svg-color--0a0a0a, #0a0a0a);
  d: path("M47.735 30.342c.197-.091.394-.108.592.005a1.9 1.9 0 0 1-.592-.005");
}

.b2be91b4q {
  fill: var(--svg-color--e2e6f0, #e2e6f0);
  d: path("m55.44 28.16l-.01 3.174c.066.474.015.945.02 1.417c-.018.054-.05.074-.104.063c-.205-.285-.064-.608-.104-.909c.008-.124-.014-.249-.02-.374q.033-.204.026-.42l.003-.441q.004-.435.005-.871c.035-.525-.054-1.055.067-1.576a.13.13 0 0 1 .117-.063");
}

.b4x790xbu {
  fill: var(--svg-color--425b75, #425b75);
  d: path("M45.2 38.97c-.029.169.071.374-.125.5q-.053-.01-.069-.059c-.057-.111.1-.199.034-.315c.007-.1.099-.094.16-.126");
}

.b5r740bnm {
  fill: var(--svg-color--dddfe2, #dddfe2);
  d: path("m52.862 43.633l-.068-.158c-.017-.114-.026-.225.149-.188l.073.117z");
}

.b5u9h_bmz {
  fill: var(--svg-color--6e7523, #6e7523);
  d: path("M46.44 34.16c-.043-.151.062-.327-.077-.466l-.012-.031l.025-.094c.017 0 .034-.005.034-.005c.264.146.199.392.216.612a.13.13 0 0 1-.071.083c-.069.007-.09-.05-.115-.099");
}

.b7ehe-b-o {
  fill: var(--svg-color--3e4956, #3e4956);
  d: path("M50.31 36.577c.078.104.196.067.299.088l.068.133c-.223.058-.473-.081-.685.085q-.038.03-.08.001c-.012-.084-.094-.109-.142-.167a.1.1 0 0 0 .015-.054c.18.005.372.086.525-.086");
}

.b8ge15bec {
  fill: var(--svg-color--5e4f12, #5e4f12);
  d: path("M44.538 38.78q.032-.04.065-.077l.217.458c.011.08-.039.099-.104.103c-.185-.118-.309-.253-.178-.484");
}

.ba1x7obtq {
  fill: var(--svg-color--2f3e4e, #2f3e4e);
  d: path("M50.956 38.836q-.174.034-.355.065l-.088-.141c.148.035.306-.176.449.017z");
}

.ba2m55b6x {
  fill: var(--svg-color--316dbc, #316dbc);
  d: path("m49.06 42.543l-.002-.072c.073-.179.182-.144.302-.054c.007.103.068.142.159.15c.003.125-.119.115-.18.173c-.123-.026-.224.133-.353.043c-.152.022-.296.096-.455.069c-.054-.085-.143-.074-.225-.078c.011-.201.165-.089.253-.104c.169-.026.362.037.501-.127");
}

.bd8-x0b0d {
  fill: var(--svg-color--87baf0, #87baf0);
  d: path("M48.28 36.571q.263-.152.527-.302c.246.083.162.256.119.421c-.041.055-.101.065-.165.064c-.078 0-.156.001-.235-.006c-.088-.054-.252.001-.246-.177");
}

.beoxxxb_r {
  fill: var(--svg-color--5c7881, #5c7881);
  d: path("M49.14 40.31q.014-.033.026-.067c.09.17.057.349.043.524l-.029-.003a4 4 0 0 1-.04-.454");
}

.bfiy6-vze {
  fill: var(--svg-color--deab19, #deab19);
  d: path("m46.47 28.919l.163.004l-.021.194c-.013.036-.008.085-.064.087q-.069.016-.137.028c-.117.03-.1-.043-.089-.115a.6.6 0 0 1 .148-.198");
}

.bgzmq_bet {
  fill: var(--svg-color--e1e4ec, #e1e4ec);
  d: path("m46.42 26.09l-.003.135c-.145.232-.392.092-.583.162c-.036 0-.07-.008-.105-.015c-.122-.038-.246-.052-.372-.07c-.067-.024-.143-.047-.132-.146c.398-.017.794-.105 1.195-.066");
}

.bhet17b5t {
  fill: var(--svg-color--06cc6b, #06cc6b);
  d: path("M45.46 43.882v.043a.35.35 0 0 1-.334-.093c.13-.077.229 0 .334.05");
}

.bhnpbvn4s {
  fill: var(--svg-color--314357, #314357);
  d: path("M52.29 39.432c-.077.001-.157-.015-.219.044q-.06-.093.014-.178l.146-.009q.033.073.059.143");
}

.bjhu-kbpu {
  fill: var(--svg-color--2e1e10, #2e1e10);
  d: path("M46.852 30.56q-.08-.07-.158-.146l.208.001q.043.08.085.15q-.03.049-.078.017a.4.4 0 0 0-.057-.022");
}

.bl9e9n85w {
  fill: var(--svg-color--02d264, #02d264);
  d: path("M50.771 44.07c-.04-.154.213-.302.434-.268c.263.037.452.191.676.409c-.598-.003-1.148.192-1.71.002l.005.005c-.04-.062-.08-.12-.148-.22c.227.039.388.174.585.154c.069.006.193.119.158-.082");
}

.bn-lv8b0g {
  fill: var(--svg-color--8bbff5, #8bbff5);
  d: path("M45.04 39.1c.207.106-.051.261.041.378c-.118.038-.169-.04-.208-.131c-.025-.089.028-.138.092-.182z");
}

.bn8j-tb5q {
  fill: var(--svg-color--573400, #573400);
  d: path("M44.21 39.747a.3.3 0 0 0 .015-.072c.118-.105.214-.234.368-.296a.2.2 0 0 0 .068.002c.146.226.256.465.227.744l-.135.148c-.246-.108-.442-.268-.543-.526");
}

.bqh8uybhw {
  fill: var(--svg-color--ced1d8, #ced1d8);
  d: path("M54.15 41.4c-.133.395-.343.748-.537 1.113c-.042.083-.086.181-.213.154l-.034-.035a.24.24 0 0 1-.018-.145c.032-.105.107-.191.152-.293q.033-.066.062-.129c.085-.178.106-.384.241-.536c.089-.068.132-.188.25-.226c.058.006.083.047.097.097");
}

.bsor1urva {
  fill: var(--svg-color--58643a, #58643a);
  d: path("M48.967 34.629c.021 0 .046-.003.067 0a.4.4 0 0 1 .032.07c-.005.126-.012.245-.015.368q-.045.004-.089.003c-.066-.148-.108-.294.005-.441");
}

.bsvsfubam {
  fill: var(--svg-color--eaeaea, #eaeaea);
  d: path("M50 35.593c-.126-.096-.235.077-.36.027c-.097-.111-.198-.076-.305-.02l.006-.002a.4.4 0 0 1-.38-.001l.011.002c-.019-.121-.007-.256-.158-.302q0-.041.005-.081l1.344.003c.107.195-.174.219-.163.374");
}

.btyii2bxx {
  fill: var(--svg-color--0a1425, #0a1425);
  d: path("M47.32 43.28c.258-.139.383.112.572.194c-.267.002-.535-.097-.78.067a.11.11 0 0 1-.035-.092c.045-.104.152-.124.243-.169");
}

.bu7kt0bap {
  fill: var(--svg-color--01d462, #01d462);
  d: path("M50.854 42.855c.535.04 1.038.302 1.635.15c-.069.16-.104.245-.14.33c-.274.03-.536.159-.817.069a.6.6 0 0 1-.399-.001a1.2 1.2 0 0 0-.511.021c-.115.031-.252.095-.29-.102c.025-.059.1-.067.13-.124c-.041.035-.09.033-.136.029c-.567-.114-1.136-.242-1.719-.224q-.038-.026-.024-.049l.027-.024c.382-.003.762-.016 1.142-.008c.205.004.332-.168.519-.199c.081-.044.102.031.138.074q.065-.032.129-.061c.104.048.225.044.316.119");
}

.bv-v_gb5k {
  fill: var(--svg-color--444, #444);
  d: path("M39.517 30.746c.086.116.018.259.067.381a.15.15 0 0 1-.011.069c-.146-.134-.052-.298-.056-.45");
}

.bv7q_xb5d {
  fill: var(--svg-color--a60a24, #a60a24);
  d: path("M54.29 38.709c.007.048.01.098.017.145l-.319-.003a.63.63 0 0 1 .302-.142");
}

.bwgi8f6fo {
  fill: var(--svg-color--3e566f, #3e566f);
  d: path("M45.939 40.36c.063.003.118.024.152.087a.2.2 0 0 0 .002.052c.044.147-.095.117-.159.16q-.04.037-.078.076a7 7 0 0 1-.226-.153c-.092-.126.035-.242.011-.363c.15-.055.245.002.298.141");
}

.bwvja9fvf {
  fill: var(--svg-color--84b6ec, #84b6ec);
  d: path("M46.622 38.35c.18.156.434.186.597.372l-.666-.003c-.09-.143-.172-.286.069-.369");
}

.bxaq1kbgg {
  fill: var(--svg-color--1e2228, #1e2228);
  d: path("M53.646 41.17h.031a.56.56 0 0 1-.112.386l-.013-.099c-.084-.132-.057-.232.094-.287");
}

.bzl9siyvu {
  fill: var(--svg-color--15181b, #15181b);
  d: path("M49.948 34.11c-.625-.002-1.249-.046-1.873.015c.009-.199.198-.1.286-.175c.149.043.3-.045.447.004a.6.6 0 0 1 .098.061c.025-.004.053-.003.078-.007l.076.001c.196-.152.393-.084.588.004l.375.02q.033.107-.075.077");
}

.bzp5a6bny {
  fill: var(--svg-color--d3d7e3, #d3d7e3);
  d: path("M47.32 47.554a.2.2 0 0 0 .056-.042c.051-.092.126-.134.232-.102a1 1 0 0 0 .067.069c-.112.054-.199.241-.355.075");
}

.c_x19hbqr {
  fill: var(--svg-color--0d0c0b, #0d0c0b);
  d: path("M39.54 35.523q.07.001.145.005c-.13.152-.009.369-.135.525q-.033-.258-.07-.516q.017-.066.06-.014");
}

.c1-5axb5j {
  fill: var(--svg-color--e9eef3, #e9eef3);
  d: path("m54.617 39.754l-.063.068c-.02.062-.058.099-.124.101c-.061-.022-.09-.068-.111-.128c-.001-.314.047-.616.247-.872c.099-.019.129.058.164.125a.4.4 0 0 1 .018.107c-.018.172-.099.332-.085.511a.15.15 0 0 1-.046.088");
}

.c2z9fbb-o {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("m51.733 35.18l-.136-.008c-.119.18-.296.182-.481.162c-.076-.01-.147-.033-.22-.053c-.053-.008-.105-.01-.159-.014c-.105-.01-.213-.007-.313-.047a.4.4 0 0 1-.088-.055c-.116-.145-.412-.057-.434-.326c.012-.072.063-.107.121-.133c.776-.087 1.543.039 2.312.101c.009.214-.076.352-.299.384c-.104.068-.204.041-.303-.011");
}

.c3yetqtaf {
  fill: var(--svg-color--2b80b4, #2b80b4);
  d: path("M46.909 44.736c-.132.155-.35.084-.447.261c-.026.046-.203.011-.235-.109c-.028-.111.08-.101.146-.114c.167-.036.331-.121.536-.038");
}

.c49jbgbnm {
  fill: var(--svg-color--08a600, #08a600);
  d: path("M45.05 39.987c-.067.023-.072.084-.088.141l-.033.002l-.034-.005c-.119-.233-.236-.471-.227-.744a1 1 0 0 0 .064-.071l.088.072c.134.066.11.205.145.316c.026.096.057.191.085.289");
}

.c60chibct {
  fill: var(--svg-color--4a5b4d, #4a5b4d);
  d: path("M46.32 36.842q.012.188.018.376q.032.03.018.051t-.025.02h-.086c-.005-.125.088-.266-.063-.365c.011-.087.078-.075.138-.082");
}

.c64pb46ba {
  fill: var(--svg-color--678eb7, #678eb7);
  d: path("m45.939 40.36l-.298-.142q.03-.042.055-.081c.169-.019.257.047.243.223");
}

.c6c39-0zd {
  fill: var(--svg-color--5f6a76, #5f6a76);
  d: path("M50.766 35.17c-.128.1-.256.128-.373-.018q.189.008.373.018");
}

.c6td-037m {
  fill: var(--svg-color--e2e3e4, #e2e3e4);
  d: path("M55.47 33.557c-.086.086-.051.194-.063.294l-.062-.001a1.05 1.05 0 0 1 .009-1.047l.059.001c.028.17-.053.358.058.521z");
}

.c752b1bgq {
  fill: var(--svg-color--1c1c19, #1c1c19);
  d: path("m46.923 29.29l-.152.09c-.012-.131.008-.25.156-.3q.034.067.063.137zm-.379-.09q.033-.041.064-.087l-.004.514c-.102-.13-.038-.286-.06-.427");
}

.ca7j4ibir {
  fill: var(--svg-color--202000, #202000);
  d: path("M46.919 29.749c.074-.101.167-.138.287-.073l.156.064c-.062.13-.23.019-.297.132q-.016.073-.076.026z");
}

.ca9rlza4k {
  fill: var(--svg-color--f7eadf, #f7eadf);
  d: path("m47.08 27.872l.081-.156q.03.016.063.019q.068.055.077.14c.014.113-.002.219-.089.302a.2.2 0 0 1-.147.048a.2.2 0 0 1-.086-.052c-.038-.085-.016-.158.037-.229c.021-.027.043-.048.064-.072");
}

.caeahgtxt {
  fill: var(--svg-color--05cd6a, #05cd6a);
  d: path("M49.06 42.543c.188.094.007.105-.038.126c-.226.109-.492-.037-.715.105c-.128.003-.263.023-.374-.07c-.026-.019-.035-.03-.024-.048c.008-.013.019-.021.019-.021c.383-.009.762.014 1.132-.092");
}

.cbh509l_t {
  fill: var(--svg-color--202014, #202014);
  d: path("M48.26 29.83c-.059.007-.118.019-.147.079c-.037.074-.09.131-.17.152c-.203.076-.471.1-.554-.074c-.109-.234.236-.206.333-.342a.3.3 0 0 1 .092-.05c.193-.006.299.154.446.235");
}

.cctxuhffo {
  fill: var(--svg-color--202020, #202020);
  d: path("M42.15 26.707c.188-.022.374-.033.538-.134q.054.035.105.072l.025.014c-.037.216-.251.134-.38.207c-.107.016-.208.014-.29-.072z");
}

.cdltxjudn {
  fill: var(--svg-color--5d6527, #5d6527);
  d: path("M49.09 38.02c-.105-.272-.031-.565-.065-.845l.068.002l.025.52z");
}

.cdqfl4n8k {
  fill: var(--svg-color--19a68f, #19a68f);
  d: path("M50.63 42.637c-.129-.117-.289-.051-.435-.072c.161-.134.344-.05.516-.06l.003.122z");
}

.cep2qlrqx {
  fill: var(--svg-color--616c37, #616c37);
  d: path("M48.875 36.706c-.016-.148.075-.309-.064-.437c-.026-.122.049-.161.146-.178q.048.033.097.073l.017.115c-.014.152.015.313-.1.446q-.058.04-.096-.019");
}

.cf8mw0ydv {
  fill: var(--svg-color--425b76, #425b76);
  d: path("M46.818 41.18c.051-.118-.091-.249.021-.366c.092-.039.165 0 .231.061a.2.2 0 0 1 .024.101a.11.11 0 0 1-.063.076c-.053.065-.103.147-.213.128");
}

.cghuyybnc {
  fill: var(--svg-color--5c6630, #5c6630);
  d: path("m49.1 39.785l.004-.747l.033.004c.015.252.013.5.011.749z");
}

.cgkbnbb5k {
  fill: var(--svg-color--5a7ca1, #5a7ca1);
  d: path("m51.54 38.37l-.343-.286c-.051-.039-.043-.094-.033-.149l.036-.003c.118.144.344.201.34.438");
}

.chywqhlon {
  fill: var(--svg-color--141819, #141819);
  d: path("m48.27 38.13l.597.01a.5.5 0 0 1 .099-.062a.5.5 0 0 1 .174-.021c.08.014.161.031.201.116q-.001.075-.076.083c-.209-.01-.422.028-.629-.029l-.575.005c-.071.013-.104-.014-.085-.086z");
}

.ciqu-tz2h {
  fill: var(--svg-color--03d265, #03d265);
  d: path("M45.536 42.532c.061 0 .115.003.173.004c.032.104.159.033.213.113c-.085.098-.239-.023-.313.103c-.091-.05-.058-.144-.073-.22");
}

.ck40qabvw {
  fill: var(--svg-color--2c2c2c, #2c2c2c);
  d: path("m52.33 26.864l-.003-.143c.148.021.294.046.443.066l-.079.087q-.189.16-.361-.01");
}

.ckfl78x0p {
  fill: var(--svg-color--3f5871, #3f5871);
  d: path("M51.78 39.05a.2.2 0 0 1 .005-.071q.068.076.141.15c-.063.033-.071.09-.078.152c-.167-.037-.125-.133-.068-.231");
}

.cl1iug50b {
  fill: var(--svg-color--435c77, #435c77);
  d: path("M49.913 38.761c.103.067.16.159.141.289l-.069-.001a.5.5 0 0 1-.072-.288");
}

.cmr5gkbvn {
  fill: var(--svg-color--008400, #008400);
  d: path("M49.07 41.956q-.038.034-.075.063c-.158-.032-.317-.068-.529-.114c.256-.159.429-.056.604.051");
}

.cohjacske {
  fill: var(--svg-color--8ea1b7, #8ea1b7);
  d: path("M51.733 35.18q.154.005.303.012c-.112.27-.206.087-.303-.012");
}

.collklg7i {
  fill: var(--svg-color--6b353e, #6b353e);
  d: path("M54.02 38.34c-.233.115-.108.328-.137.5c-.17-.103.057-.476-.305-.446c.134-.122.294-.032.442-.054");
}

.cp16ksbrj {
  fill: var(--svg-color--010204, #010204);
  d: path("M44.931 44.39v.07a.65.65 0 0 1-.474-.073z");
}

.cpl4ielzs {
  fill: var(--svg-color--4a4a4a, #4a4a4a);
  d: path("m42.03 26.718l.098-.079a.14.14 0 0 1 .07.081a.2.2 0 0 1-.011.105c-.087.149-.245.141-.384.179a.5.5 0 0 1-.111-.013a.24.24 0 0 1-.084-.069a.12.12 0 0 1 .018-.102c.12-.092.265-.091.404-.102");
}

.cq0nq5bee {
  fill: var(--svg-color--c7cbd6, #c7cbd6);
  d: path("M41.35 42.873q.038-.04.081-.079c.073.059.185.098.146.229l-.078.079a8 8 0 0 1-.149-.229");
}

.cqtvtzbsh {
  fill: var(--svg-color--ededcd, #ededcd);
  d: path("m41.25 26.975l.374-.112c.007.06.056.072.104.083c-.109.313-.251.354-.543.157l-.023-.02c.021-.041.056-.074.088-.108");
}

.crhlfsboz {
  fill: var(--svg-color--d2d7e3, #d2d7e3);
  d: path("M43.43 26.367q.04.036.083.07c.005.054-.021.091-.062.125a.34.34 0 0 1-.179.054a.33.33 0 0 0-.211.055a.36.36 0 0 1-.188.022a.16.16 0 0 1-.082-.048c.096-.358.417-.204.639-.278");
}

.csuwd5b-d {
  fill: var(--svg-color--d7dae2, #d7dae2);
  d: path("m43.745 45.535l-.014.034c-.172-.077-.317-.177-.383-.363q.036.015.067-.004c.179-.038.208.141.312.213zm7.161.097a.1.1 0 0 0-.042-.059c.01-.034.021-.063.034-.098c.122-.06.139-.314.358-.188c-.042.19-.2.263-.35.345");
}

.cux3k3b-a {
  fill: var(--svg-color--2887ae, #2887ae);
  d: path("M49.653 43.31c.052.09.144.078.228.085c-.155.218-.249.146-.306-.067c.017-.039.042-.048.078-.018");
}

.cxauqfo-o {
  fill: var(--svg-color--cccfd5, #cccfd5);
  d: path("M50.46 26.405c.063-.089.169-.067.261-.091c.17.017.348-.012.507.08c-.02.087-.084.138-.152.186a.2.2 0 0 1-.098.017c-.107-.018-.207-.093-.324-.072a.3.3 0 0 1-.098-.015a.2.2 0 0 1-.096-.105");
}

.cygu6lipy {
  fill: var(--svg-color--272727, #272727);
  d: path("M55.25 28.09h.029c.023.022.032.048.04.071q-.014.6-.03 1.197h-.049z");
}

.cz0dqrjti {
  fill: var(--svg-color--4b4b4b, #4b4b4b);
  d: path("M55.16 36.522c-.093-.142-.11-.27.081-.347c-.005.123-.013.243-.081.347");
}

.d-sejsv9g {
  fill: var(--svg-color--5c7fa4, #5c7fa4);
  d: path("m46.867 34.529l-.233-.226c.174-.022.23.071.233.226");
}

.d0o2dzb1s {
  fill: var(--svg-color--af6a2d, #af6a2d);
  d: path("M46.977 30.19q.084.144.171.288c-.021.082-.078.113-.158.112c-.054-.042-.121-.081-.088-.173c-.044-.102-.167-.17-.137-.305a.13.13 0 0 1 .131-.029c.048.022.064.064.081.107");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d40ymcc8c {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("m51.964 44.602l-.001.072c-.028.093-.057.055-.082-.001q.041-.038.083-.071m-9.339-.142q.028.037.06.073q.029.019.02.038q-.012.02-.013.019c-.098-.009-.079-.07-.067-.13");
}

.d8cwteefk {
  fill: var(--svg-color--f2d9c3, #f2d9c3);
  d: path("M47.07 27.987c-.178.004-.258-.08-.225-.262c.143-.055.099.189.232.146c.001.041-.005.079-.007.116");
}

.d9a4wbkmk {
  fill: var(--svg-color--e0e000, #e0e000);
  d: path("M48.879 35.01q.008-.191.02-.383q.032 0 .068.006l-.004.441l-.034.007l-.034-.008a.2.2 0 0 0-.016-.063");
}

.dc15q8tls {
  fill: var(--svg-color--dfe2eb, #dfe2eb);
  d: path("M39.68 37.533c-.022.079.009.177-.075.233a7 7 0 0 1-.025-.266c.022-.086.006-.183.079-.254c.062.027.048.085.05.136c.001.053.009.107-.029.151");
}

.dc2ir0bag {
  fill: var(--svg-color--693400, #693400);
  d: path("M46.39 29.14c-.052.039-.02.064.014.091l-.021.073c-.133.018-.232-.007-.233-.168l.105-.143c.112-.016.169.025.135.147");
}

.ddx6x2bdh {
  fill: var(--svg-color--54613f, #54613f);
  d: path("m48.988 40.39l.022.877q-.047.004-.095.006q.013-.442.023-.885q.027 0 .05.002");
}

.de0s6o5fn {
  fill: var(--svg-color--718294, #718294);
  d: path("m49.948 34.11l.075-.078c.115.183.021.263-.148.309a6 6 0 0 1 .073-.231");
}

.deds7cfls {
  fill: var(--svg-color--8ec4fd, #8ec4fd);
  d: path("M44.38 38.25c.271-.483.545-.962.812-1.447c.068-.131.117-.271.173-.406c.092-.192.29-.169.448-.222a.6.6 0 0 1 .289.009a.4.4 0 0 1 .192.123c.087.13.062.283.09.426a.4.4 0 0 1-.013.105c-.03.063-.082.106-.134.156c-.14.121-.311.188-.473.273c-.067.04-.152.05-.203.121a.4.4 0 0 1-.036.083a.5.5 0 0 1-.047.081c-.037.125-.06.253-.088.38c-.006.183-.049.358-.042.54a.4.4 0 0 1-.021.188c-.048.041-.061.083-.012.133a.24.24 0 0 1-.003.139a.3.3 0 0 1-.087.11l-.147.118a.3.3 0 0 1-.14.061a.3.3 0 0 1-.149-.036c-.176-.097-.184-.297-.276-.445c-.074-.156-.263-.279-.133-.49");
}

.deshtcewc {
  fill: var(--svg-color--d7dae1, #d7dae1);
  d: path("M49.705 46.3c.165-.112.298-.284.526-.291q.03.027.024.058a.1.1 0 0 1-.011.031c-.121.17-.313.235-.468.342c-.064-.027-.115-.058-.071-.14");
}

.df__ufc3u {
  fill: var(--svg-color--cd6200, #cd6200);
  d: path("M41.479 41.472c-.102-.031-.104-.12-.122-.206c-.062-.287-.158-.531-.385-.767c-.197-.205-.238-.57-.415-.833c.013-.221.07-.435.061-.655c-.035-.1.065-.222-.053-.31c-.131-.37.146-.482.396-.502c.28-.021.311.26.35.475c.012.084-.001.173-.002.26c-.109.231.045.431.104.628c.126.412.3.809.39 1.236c.035.179.215.227.329.333c.256.256.216.564.161.876c-.193.171-.241-.057-.325-.131c-.156-.14-.244-.366-.489-.404");
}

.dfssgpbjh {
  fill: var(--svg-color--646c24, #646c24);
  d: path("M48.988 40.39q-.024-.003-.049-.002q.004-.412.004-.825l.051.009z");
}

.diehu9jdk {
  fill: var(--svg-color--5a3300, #5a3300);
  d: path("M44.09 38.25c-.004.081-.022.166.06.228l.007.074c-.084.324-.122.36-.351.331c.023-.236-.224-.472-.006-.713l.051-.143c.163-.017.147.163.239.223");
}

.dkev40nvf {
  fill: var(--svg-color--ce6200, #ce6200);
  d: path("M43.42 35.644c.056.072.137.066.216.068c.141.145.275.32.229.522c-.095.399-.002.761.146 1.122c-.183.207-.271-.008-.379-.094c-.109-.093-.108-.234-.113-.274c.063.258-.109.587-.076.929c-.054.105-.004.237-.075.33c.023-.013.033-.044.035-.081c.007-.067.008-.14.034-.208c.015-.063 0-.127.009-.186c.022-.136.109-.225.246-.227c.141-.001.167.121.193.228c.019.072.014.146.03.22a.32.32 0 0 1-.057.22c-.116.101-.192.202-.115.372a.81.81 0 0 1-.067.73c-.091.096-.132.261-.318.22a2 2 0 0 0-.129.03c-.164-.215-.269-.447-.173-.722c.044-.129-.048-.201-.106-.294c-.23-.375-.293-.791-.224-1.227c-.068-.111-.109-.266-.013-.345c.489-.402.22-.858.095-1.288a.8.8 0 0 1 .033-.57c.191-.113.31-.074.363.156c.031.141.075.286.216.369");
}

.dl_b8qyig {
  fill: var(--svg-color--212926, #212926);
  d: path("M46.46 39.26c-.242-.029-.138.16-.14.246c-.016.536-.013 1.072-.015 1.609c-.077-.018-.123-.066-.156-.134q.038-.081-.048-.099a.17.17 0 0 1-.042-.166c.044-.072.017-.141-.011-.21a.2.2 0 0 1 .003-.096a.9.9 0 0 0 .084-.418c.003-.166 0-.33-.173-.428a.26.26 0 0 1-.118-.097a.14.14 0 0 1 .019-.101c.103-.124.354.003.388-.232a.19.19 0 0 1 .213.017q.036.057-.004.109");
}

.do8izcckt {
  fill: var(--svg-color--dfdfdf, #dfdfdf);
  d: path("m48.735 35.438l-.146.07c-.128.087-.246.067-.358-.034c-.107-.034-.205-.079-.25-.196c.19-.24.444-.154.685-.137a.26.26 0 0 1 .144.11c.039.085.022.15-.075.187");
}

.dq57xcyma {
  fill: var(--svg-color--6a88a6, #6a88a6);
  d: path("M48.984 34.01q.002-.24.001-.478l.07-.051q.02.022 0 .041q.063.06.086.147c.014.12.014.238-.061.341c-.03.034-.065.033-.096 0");
}

.drlov32mv {
  fill: var(--svg-color--dee0e5, #dee0e5);
  d: path("m52.42 43.911l.006-.023q.008-.062.064-.054c.067.037.11.085.075.165c-.144.184-.213.454-.524.433l.075-.101c.045-.183.245-.248.304-.42");
}

.ds2nq9bkl {
  fill: var(--svg-color--83b5eb, #83b5eb);
  d: path("M47.13 40.978q-.005.066-.007.137l-.086-.06q.008-.046.018-.091q.046-.046.075.014");
}

.dv0tm2bgu {
  fill: var(--svg-color--1c140b, #1c140b);
  d: path("M42.17 43.888q-.075-.132-.147-.266q-.033-.024-.02-.051l.017-.021c.133.078.235.172.22.34l-.036-.009z");
}

.e3sz80bxg {
  fill: var(--svg-color--82b3e7, #82b3e7);
  d: path("M48.957 36.09a.05.05 0 0 1 .001-.039c.064-.097-.035-.22.055-.311a.2.2 0 0 1 .102-.04c.354.212.511.582.711.91a.2.2 0 0 1-.018.105c-.101.093-.197.007-.295-.007a.3.3 0 0 1-.078-.055c-.059-.071-.108-.149-.197-.185a.3.3 0 0 1-.108-.08a3 3 0 0 1-.144-.173a.15.15 0 0 1-.029-.125");
}

.e4rlrsb5q {
  fill: var(--svg-color--7d8a98, #7d8a98);
  d: path("M50.38 35.09q-.096-.004-.197-.006c-.055.049-.113.043-.17-.001l-.068-.155c.125.105.351-.051.435.162");
}

.e5aq8f2hv {
  fill: var(--svg-color--eb072c, #eb072c);
  d: path("m53.5 38.39l.076.009c.299-.129.289.139.371.287a.3.3 0 0 0 .121.064c.08.017.162.023.234.07q.017.021.03.042l-.069.14a.09.09 0 0 1 .004.094c-.131.165-.415.117-.498.353c-.032.063-.133.087-.118.182l-.063.041c-.109.056-.217.06-.32-.002c.032-.279-.165-.356-.374-.428c-.071-.11-.033-.206.031-.303a.16.16 0 0 1 .088-.052c.106-.021.222.045.32-.039l.05-.072c.047-.098.026-.21.062-.313a.16.16 0 0 1 .055-.073");
}

.e5uiwvr7j {
  fill: var(--svg-color--03b600, #03b600);
  d: path("M43.827 41.468c-.06-.014-.166-.023-.166-.04c-.043-.408-.468-.704-.343-1.157c.187-.111.275.04.354.155c.127.175.284.308.451.44c.185.15.352.165.53.013c.196.025.331.151.46.288c-.271.191-.536.34-.878.138c-.175-.105-.275.099-.408.163");
}

.e624yb15k {
  fill: var(--svg-color--131313, #131313);
  d: path("M47.3 28.458c-.105.103.01.385-.301.336c-.095-.016.054.117.007.184c.033.053.01.098-.021.139c-.069.069-.123.146-.115.247l.005.1c.015.104.052.205.036.312c-.016.078-.054.139-.14.158a.17.17 0 0 1-.109-.032a.38.38 0 0 1-.146-.312a8 8 0 0 1 .003-.41q-.001-.11.035-.223a.7.7 0 0 1 .071-.142c.086-.127.162-.253.069-.409c-.09-.247-.368-.166-.521-.301c-.032-.109.054-.155.12-.209c.108-.061.209-.141.34-.14c.187.084.252.271.365.418l.019.003c.071.104.214.122.284.23z");
}

.e6966sbon {
  fill: var(--svg-color--909312, #909312);
  d: path("M51.18 39.435c-.105-.164-.039-.352-.065-.529q.031-.034.066-.004l.008.014c-.004.171-.007.347-.009.519");
}

.e943_bc7k {
  fill: var(--svg-color--c15b00, #c15b00);
  d: path("m53.21 40.05l.221.008c.217.005.519-.063.198.305c-.1.11-.074.284-.071.431c.033.07-.014.096-.065.116c-.242-.002-.478.026-.616.269c-.093-.003-.123-.07-.148-.144a.7.7 0 0 1-.018-.166c-.002-.055-.001-.105-.001-.16c0-.023.003-.049-.002-.072c-.014-.123.055-.313-.154-.303c-.187.008-.146.187-.136.317q.015.08 0 .157a.3.3 0 0 1-.048.098a.28.28 0 0 1-.197.069c-.233-.038-.394-.001-.354.298c.012.096-.004.207-.155.192c-.042-.025-.092-.058-.096-.104c-.032-.339-.271-.42-.553-.449c-.055-.027-.089-.068-.092-.13a.2.2 0 0 1 .078-.072c.28-.015.491-.104.467-.44c.022-.079.081-.124.151-.154l.59-.021c.329-.097.67.047 1-.045");
}

.e9n62p9cy {
  fill: var(--svg-color--35485d, #35485d);
  d: path("m47.06 40.894l.072.004l-.003.08q-.035-.008-.075-.014q.005-.037.006-.07");
}

.ebg-71twy {
  fill: var(--svg-color--8dc2fb, #8dc2fb);
  d: path("M45.863 38.665c-.125-.024-.26.137-.38-.02c.268-.182.483-.42.691-.665c.246.011.143.212.19.337a.3.3 0 0 1-.072.203c-.119.12-.274.129-.429.145");
}

.ec3_qc1zf {
  fill: var(--svg-color--c7c9cf, #c7c9cf);
  d: path("M40.79 41.524c.045.069.037.172.128.22c.088.14.146.295.213.446c-.009.104.048.172.116.236c.077.028.073.084.051.146q-.053.046-.106.003c-.288-.39-.476-.831-.645-1.282c.019-.055.049-.095.112-.094c.096.085.154.19.131.325");
}

.ecogoe_ga {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M43.29 45.14a.1.1 0 0 1 .036 0c.017.033.023.055.032.073c-.044-.004-.076-.022-.068-.073");
}

.ectn0jfpq {
  fill: var(--svg-color--7f8419, #7f8419);
  d: path("m50.928 34.26l.005-.604q.047.005.1.006c-.052.126-.04.254-.022.382l-.025.226q-.039.047-.058-.01");
}

.eg-n8dbaq {
  fill: var(--svg-color--c5cad6, #c5cad6);
  d: path("M45.819 46.913c.023-.015.05-.029.07-.044c.11-.019.188.031.243.121c-.007.057-.045.082-.096.099c-.094-.029-.203-.044-.217-.176");
}

.eg3y4_bdw {
  fill: var(--svg-color--3c536b, #3c536b);
  d: path("m46.597 39.924l-.054.004q-.005-.156-.013-.315l.07-.156c.139.01.115.078.058.157c.068-.047.09-.147.19-.151c.094.083.08.195.076.307c-.058.155-.15.241-.327.154");
}

.eilprdkuu {
  fill: var(--svg-color--03d165, #03d165);
  d: path("m47.17 46.578l-.188.018c-.268.13-.499.007-.729-.133c.309.015.629-.082.917.115");
}

.ejkkq1bor {
  fill: var(--svg-color--f7f7f5, #f7f7f5);
  d: path("M47.3 28.458c.137.015.217.058.202.231c-.027.305.247.48.52.352c-.053.195-.048.187.191.293c.059.027.085.13.128.198c.327.219.364.274.346.514q-.061.002-.126.002c-.139 0-.234-.099-.344-.163a2 2 0 0 0-.408-.231a3 3 0 0 1-.313-.218a5 5 0 0 0-.22-.175a1 1 0 0 1-.064-.069c-.064-.097-.191-.108-.258-.198c-.137-.344.221-.362.346-.536");
}

.en1908bds {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M39.69 33.583c-.12.1-.01.271-.126.366l-.005-.504c.104-.119.241-.12.379-.119c2.872.021 5.75.038 8.624.067a1 1 0 0 1 .147.02a.34.34 0 0 1 .124.074c.009.05-.003.092-.047.125c-.168.107-.359.088-.544.081c-.583-.017-1.169.04-1.749-.05a.3.3 0 0 1-.116-.078q-3.151-.026-6.299-.047c-.131 0-.274-.045-.388.065");
}

.eo39abm2y {
  fill: var(--svg-color--022d00, #022d00);
  d: path("m45.05 39.987l.072.066a.2.2 0 0 0-.007.055q-.041.048-.08.104q-.039-.043-.073-.084c-.035-.087-.056-.163.088-.141");
}

.eok4-t_5n {
  fill: var(--svg-color--717e8b, #717e8b);
  d: path("M50.45 37.09q-.001-.027.005-.056c.226-.081.16.13.219.216c-.073-.052-.148-.108-.224-.16");
}

.ero4-t3-m {
  fill: var(--svg-color--526a73, #526a73);
  d: path("M51.17 39.991c.003-.187.01-.378.015-.564c.133.158-.043.407.151.549c-.052.063-.107.042-.166.015");
}

.ewgk3fb_k {
  fill: var(--svg-color--8bc0f9, #8bc0f9);
  d: path("M51.657 38.4c-.165.14-.35.027-.522.047c-.08-.127.034-.233.033-.352c.223-.039.269.162.372.282q.058.01.117.023");
}

.ex4i3rb6v {
  fill: var(--svg-color--722f3a, #722f3a);
  d: path("M53.02 38.915c.141-.008.291.051.413-.073c-.091.29-.258.143-.413.073");
}

.f02cytzfn {
  fill: var(--svg-color--fcfcf8, #fcfcf8);
  d: path("M51.14 26.617c.098.005.19.01.287.017q.04-.003.078-.002c-.03.029-.063.062-.095.091c-.092.078-.186.073-.28.007q-.036-.063.01-.113");
}

.f29d8qo8n {
  fill: var(--svg-color--05cd69, #05cd69);
  d: path("M47.938 42.635q0 .034-.003.069c-.2.008-.405-.042-.596.055l-.002-.069c.189-.129.398-.056.601-.055");
}

.f2yjp0bvq {
  fill: var(--svg-color--dfe2e8, #dfe2e8);
  d: path("M42.17 43.888a.2.2 0 0 1-.055.033c-.126-.063-.187-.175-.247-.289c-.041-.069.004-.09.061-.103c.051.02.088.058.128.094c.053.082.188.127.113.265");
}

.f3i9bt82j {
  fill: var(--svg-color--414f5f, #414f5f);
  d: path("m46.02 39.465l-.076.223q-.072.07-.138-.005c-.018-.094.052-.151.085-.224c.044 0 .086.005.129.006");
}

.f7wv5ublv {
  fill: var(--svg-color--a24c00, #a24c00);
  d: path("M51.684 41.679c-.135.017-.284-.053-.399.07q-.023.065-.068.013a.54.54 0 0 1-.183-.393a.17.17 0 0 1 .101-.028c.181.078.382.074.563.15a.13.13 0 0 1 .092.054c.011.08.018.158-.106.134");
}

.f89zagbml {
  fill: var(--svg-color--0fbb7b, #0fbb7b);
  d: path("M46.42 43.29c.06.014.166-.045.167.059c.003.086-.1.08-.17.077q0-.067.003-.136");
}

.f8d8vxb7k {
  fill: var(--svg-color--5c7fa5, #5c7fa5);
  d: path("M50.661 39.05c-.096-.021-.201-.036-.061-.152c.109-.08.215-.174.355-.065l-.067.229q-.039-.007-.078-.009a.15.15 0 0 1-.075.042a.16.16 0 0 1-.074-.045");
}

.f96z6tb2g {
  fill: var(--svg-color--0b0b0b, #0b0b0b);
  d: path("M48.559 30.12c-.189.019-.259-.227-.447-.207c-.008-.129.057-.133.147-.079c.08.103.272.042.301.218z");
}

.fbkvlyz_q {
  fill: var(--svg-color--07ca6d, #07ca6d);
  d: path("m45.84 43.44l.581-.015q.104-.064.003-.136c-.069-.014-.149-.01-.161-.127l.917.062c.006.258-.228.256-.373.349c-.127.041-.255-.027-.378.005q-.295-.04-.59-.085q-.04-.021-.038-.023c.02-.024.031-.03.039-.03");
}

.fda3zxb7l {
  fill: var(--svg-color--222e3b, #222e3b);
  d: path("M51.634 39.657c.091-.043.185-.09.29-.072l-.001.076c-.072.051-.179.057-.222.15c-.082-.024-.068-.092-.067-.154");
}

.fg3dxccev {
  fill: var(--svg-color--363600, #363600);
  d: path("m46.919 29.749l-.074-.008a8 8 0 0 1-.07-.303c.077-.052.153-.06.219.022c.097.04.194.084.293.124q-.041.045-.08.091a.5.5 0 0 1-.288.074");
}

.fhm1cvb4f {
  fill: var(--svg-color--23a600, #23a600);
  d: path("M40.647 38.961c.097.251-.007.476-.09.705c-.123-.211.055-.413.012-.621c.023-.032.026-.078.078-.084");
}

.fi9982baj {
  fill: var(--svg-color--5e5e5e, #5e5e5e);
  d: path("M45.738 27.645c-.028.113-.171.041-.211.131c-.091.01-.168-.015-.283-.134z");
}

.fjbbetyxz {
  fill: var(--svg-color--749fce, #749fce);
  d: path("M51.949 39.59q-.043-.077-.083-.157c-.013-.063-.059-.117-.06-.182c.011-.072.023-.137.119-.119l.155.166l-.014.178z");
}

.fjmg8fbpt {
  fill: var(--svg-color--5a6370, #5a6370);
  d: path("M53.709 39.46c.142.129.308.054.465.051c-.143.192-.36.022-.523.118c-.123-.107.005-.128.058-.169");
}

.fk0ui_55x {
  fill: var(--svg-color--e5e500, #e5e500);
  d: path("m51.17 39.991l-.134.013c-.203-.235-.081-.518-.11-.78c.014-.129-.005-.275.159-.332c.143.163-.011.375.091.543l.009-.008a.96.96 0 0 1-.015.564");
}

.fk3wqmb4p {
  fill: var(--svg-color--48584a, #48584a);
  d: path("m46.36 35.13l-.001.076c.039.196.048.39-.01.58l-.09.002c-.082-.089-.077-.188-.051-.294a.64.64 0 0 0 .06-.381q.047.01.092.017");
}

.fkgflsnzs {
  fill: var(--svg-color--414f5f, #414f5f);
  d: path("m45.879 39.4l-.018-.076c.036-.059.111-.026.157-.063c.081-.01.116-.152.225-.08c.013.297-.227.169-.364.219");
}

.fltpcgwqr {
  fill: var(--svg-color--16ab8a, #16ab8a);
  d: path("m50.1 44.596l-.014-.153l.439.004l.004.031q-.213.06-.429.118");
}

.fmr6lhnqc {
  fill: var(--svg-color--8bc0f8, #8bc0f8);
  d: path("m49.648 34.02l-.588-.004l.005-.363h.058c.154.153.417.149.525.367");
}

.fn5_wnbnm {
  fill: var(--svg-color--82b3e8, #82b3e8);
  d: path("M46.867 37.29c.016-.125.113-.135.208-.147c.041.069.113.084.182.099c-.119.106-.259.042-.39.048");
}

.frcurqyni {
  fill: var(--svg-color--dadbdd, #dadbdd);
  d: path("M39.38 34.876c-.094-1.264-.051-2.528.028-3.792c.153.121.11.288.117.446c.022.404-.054.813.041 1.214a4.7 4.7 0 0 1-.002.984c-.087.241-.045.495-.062.743c-.008.143.024.303-.122.405");
}

.frrg2dbqq {
  fill: var(--svg-color--fdfdfb, #fdfdfb);
  d: path("m53.953 27.339l-.356-.101l.162-.126l.082.001c.007.127.176.103.205.212z");
}

.fw0lbgbmt {
  fill: var(--svg-color--e4e7ee, #e4e7ee);
  d: path("M54.18 41.03q.038.049.078.095a7 7 0 0 0-.108.273q-.038-.042-.069-.085c-.043-.041-.047-.09-.036-.141c.024-.067.059-.126.135-.142");
}

.fxkmwnbij {
  fill: var(--svg-color--405872, #405872);
  d: path("M50.2 39.571q.047-.083.087-.168c.066-.088.071-.239.232-.236c.123.02.245.046.29.189q-.001.047.001.094c-.033.068-.073.138-.107.207c-.064.02-.128.045-.192.065c-.132.147-.263.189-.404.013c-.023-.088.038-.123.093-.164");
}

.fyp1c3b3a {
  fill: var(--svg-color--1e1e1e, #1e1e1e);
  d: path("M39.543 34.626c-.157-.287-.026-.602-.084-.896l.005-.977c.009-.36.014-.724.031-1.085c.004-.086-.056-.202.072-.257c.207.319.059.675.103 1.01q-.007.392-.008.789a2 2 0 0 1-.003.127a1 1 0 0 1-.015.127c-.036.169-.005.346-.033.516c-.072.21.022.436-.068.645");
}

.fzq1bdcpe {
  fill: var(--svg-color--0a1425, #0a1425);
  d: path("m48.988 42.783l.37-.082q.032.026.021.052t-.021.025c-.123.007-.247.169-.37.005");
}

.g-be_-d4x {
  fill: var(--svg-color--0d0601, #0d0601);
  d: path("M50.648 40.471c-.184.093-.382.084-.58.083q-.13-.008-.255-.018c.057-.088.213-.004.245-.143c.019-.024.037-.024.061-.008a.7.7 0 0 0 .53.02z");
}

.g1m3m6btj {
  fill: var(--svg-color--8cc1fa, #8cc1fa);
  d: path("M48.17 40.01q.008-.033.021-.066c.079.023.063.083.058.139z");
}

.g1snzrj9j {
  fill: var(--svg-color--010101, #010101);
  d: path("M49.36 42.42a.47.47 0 0 0-.302.054c-.474-.17-.981-.112-1.467-.22a.87.87 0 0 0-.514.063c-.38.159-.674.027-.937-.246c-.259-.268-.494-.562-.819-.761c-.084-.037-.184-.043-.265-.099c-.147-.1-.286-.206-.456-.27a23 23 0 0 0-1.414-.987c-.139-.117-.33-.2-.262-.441c.101-.086.209-.06.316-.021a1 1 0 0 1 .1.044c.213.134.428.27.656.382c.085.057.165.114.252.168c.177.137.387.219.57.34q.078.057.162.103c.093.056.19.101.286.154c.065.04.124.087.204.104c.125.029.25.057.382.045a.5.5 0 0 1 .313.087c.061.046.123.093.189.126l.089.04c.062.023.126.049.191.066c.294.027.585.009.876.015c.166.011.333-.014.498.004c.264-.01.525-.004.787.003l.107.005c.064.005.129.006.19-.033a.46.46 0 0 0 .145-.186c.14-.223.241-.499.575-.506a.36.36 0 0 1 .207.05a.13.13 0 0 1 .051.088c-.025.091-.12.113-.174.175a2 2 0 0 1-.142.128a.8.8 0 0 0-.243.237c-.063.09-.117.182-.178.275a.5.5 0 0 1-.085.089c-.479.187-.972.063-1.459.067c-.155 0-.317-.019-.477-.027c-.203-.061-.416-.028-.624-.043c-.134-.014-.265-.054-.402-.039c-.125-.034-.26-.035-.379-.095c.104.06.227.049.336.095c.094.006.187-.003.277.015c.135.041.275.022.412.03c.887.092 1.774.099 2.666.063c.298-.011.586-.088.885-.075c.256.011.119-.182.129-.295c-.008-.154-.002-.31-.001-.462a2 2 0 0 0-.015-.212a.3.3 0 0 1 .001-.101a1 1 0 0 1 .056-.188a.5.5 0 0 1 .183-.227a.3.3 0 0 1 .089-.039q.044-.012.093-.016c.045-.003.092-.003.138-.008c.062-.005.121-.016.182-.024a.4.4 0 0 1 .09.001c.1.024.182-.027.269-.058a.2.2 0 0 1 .099.01c.103.073.229.065.342.109c.067.045.142.086.054.178c-.171.102-.356.053-.537.064l-.223-.005c-.438 0-.442.004-.458.467c-.01.221.056.431.102.642c.043.154.127.289.222.417c.071.172.289.267.268.485c-.129.178-.312.066-.467.086c-.204.025-.412-.031-.616.025c-.362.159-.757-.075-1.123.085");
}

.g268rvbtw {
  fill: var(--svg-color--151210, #151210);
  d: path("M52.96 42.23c.001-.105-.036-.213.047-.307c.111-.079.031-.241.139-.321c.084-.067.177-.111.269-.161c.055-.018.107-.015.154.02q.03.05-.004.099c-.038.288-.458.263-.47.573z");
}

.g2ghs4bem {
  fill: var(--svg-color--13b185, #13b185);
  d: path("m45.84 43.44l-.001.053l-.746-.005q-.038-.018-.025-.038l.02-.019q.378.006.752.009");
}

.g2q_b052e {
  fill: var(--svg-color--87baf1, #87baf1);
  d: path("m50.729 39.05l.082.001c-.002.055.005.119-.07.144c-.053-.046-.05-.095-.012-.145");
}

.g4-7kkbkg {
  fill: var(--svg-color--c9cdd7, #c9cdd7);
  d: path("M39.964 39.12c-.258-.102-.155-.347-.215-.529c.046-.047 0-.159.113-.16q.145.306.134.644c0-.001-.02.03-.032.045");
}

.g4q4u-bgi {
  fill: var(--svg-color--5f561a, #5f561a);
  d: path("M41.17 35.591c.032.005.066.014.1.018l.124.307l-.077.085c-.215-.072-.209-.223-.145-.392z");
}

.g4uj0fbru {
  fill: var(--svg-color--709ac7, #709ac7);
  d: path("M48.33 39.563c.013.063.012.124-.067.145a.2.2 0 0 1-.076-.051q-.022-.028-.016-.054a.1.1 0 0 1 .009-.028q.078-.008.15-.012");
}

.g6a49fb1u {
  fill: var(--svg-color--8e4400, #8e4400);
  d: path("M51.767 41.903q.033.003.065.002c.035.072.095.137.056.236c-.104-.049-.108-.146-.121-.238");
}

.g7tcjej8u {
  fill: var(--svg-color--d3d6dc, #d3d6dc);
  d: path("m41.657 43.32l.06-.042l.091.043c.051.072.192.095.126.232q-.035.038-.069.079a.62.62 0 0 1-.208-.312");
}

.g8vo48b4i {
  fill: var(--svg-color--292929, #292929);
  d: path("M46.929 29.08q.038-.047.076-.101c.116.01.231.032.28.16c-.06.146-.181.124-.3.108c-.056-.042-.097-.09-.056-.167");
}

.ga74lpitr {
  fill: var(--svg-color--14284a, #14284a);
  d: path("M50.854 42.855c-.12-.003-.246.017-.317-.116c.11-.006.229-.04.331-.013c.163.042 0 .086-.014.129");
}

.gaktgn-gz {
  fill: var(--svg-color--04080f, #04080f);
  d: path("M44.931 44.39q.187-.041.377-.08c.017.018.02.035.02.035l-.021.039l-.376.076q-.038-.027-.025-.049q.011-.022.025-.021");
}

.gdj_ojwri {
  fill: var(--svg-color--5a7ca0, #5a7ca0);
  d: path("M52.3 38.459c-.092-.077-.235-.114-.193-.28c.087.074.228.121.193.28");
}

.ge2jdub-q {
  fill: var(--svg-color--808516, #808516);
  d: path("M51.13 36.55c-.101-.231-.059-.475-.054-.715l.049.005z");
}

.gedsnpbns {
  fill: var(--svg-color--07b400, #07b400);
  d: path("M42.02 41.14c-.177-.1-.309-.17-.349-.452c-.043-.301-.169-.631-.307-.931c-.104-.225-.141-.482-.194-.73c-.011-.065.064-.094.134-.093c.057.294.156.555.371.788c.289.31.168.759.301 1.128c.041.094.161.175.044.29");
}

.gjnsfebqf {
  fill: var(--svg-color--f5f516, #f5f516);
  d: path("m46.993 29.461l-.219-.022a.2.2 0 0 1-.004-.061c.037-.053.063-.122.152-.09l.37-.004c.008.242-.199.121-.299.177");
}

.gjz9c7fbo {
  fill: var(--svg-color--f8f00e, #f8f00e);
  d: path("M45.94 29.22c.156-.24.317-.479.468-.725c.057-.099.124-.111.215-.08c.044.038.047.086.028.141c-.068.111-.171.202-.248.313a1 1 0 0 0-.097.166c-.037.057-.077.109-.154.107l-.136.156z");
}

.gkbboujxq {
  fill: var(--svg-color--696969, #696969);
  d: path("M43.1 26.661q-.035-.012-.066-.025c.058-.127.128-.199.248-.056l-.109.077q-.037.046-.073.004");
}

.gkmn-_yrf {
  fill: var(--svg-color--19232d, #19232d);
  d: path("M47.49 41.14q.005.067.012.133c-.324-.034-.66.066-.978-.068q.013-.024.026-.043c.068-.051.15-.055.232-.066c.075-.002.138-.045.208-.072c.04-.01.085-.01.127-.012l.125-.018a.3.3 0 0 1 .132.018c.055.029.106.06.116.128");
}

.gly00rb4k {
  fill: var(--svg-color--fbfb00, #fbfb00);
  d: path("M48 31.18c.186.454.021.777-.436.867c-.186.034-.37.068-.375.316c-.003.063-.02.124-.085.152c.029-.106.004-.219-.073-.272c-.354-.239-.199-.536.009-.682c.289-.209.37-.549.62-.764l.042-.027c.233.041.268.225.298.41");
}

.gn95frdbj {
  fill: var(--svg-color--6e757c, #6e757c);
  d: path("M51.651 37.27c.095-.199.289-.13.445-.167l-.001.094a.53.53 0 0 0-.44.119z");
}

.gne-qib5e {
  fill: var(--svg-color--8dc2fb, #8dc2fb);
  d: path("m49.783 36.663l-.67-.915c-.03-.145.1-.14.175-.188a.48.48 0 0 1 .334-.009c.121.063.274-.15.378.043c.179.301.354.599.529.902c-.031.093-.114.134-.192.181c-.187.087-.373.147-.554-.014");
}

.gnmiyut7r {
  fill: var(--svg-color--f1f1de, #f1f1de);
  d: path("m39.828 27.607l-.005-.084q.077-.044.152-.093c.087-.024.17-.054.221-.134l.379-.063c.041.053.044.107.018.167c-.225.191-.461.325-.765.207");
}

.gnp6kbbye {
  fill: var(--svg-color--434343, #434343);
  d: path("m39.608 27.972l-.012-.378a.2.2 0 0 1 .071.009l-.014.369z");
}

.gpnre09gr {
  fill: var(--svg-color--a6a6a6, #a6a6a6);
  d: path("M55.37 28.16h-.027l-.029-.001a.1.1 0 0 1-.045-.102c.016-.115-.034-.237.038-.346c.17.133.026.303.063.449");
}

.groz8gb5h {
  fill: var(--svg-color--20150c, #20150c);
  d: path("m46.638 27.802l.008-.162c.048-.069.096-.142.141-.211c.003.102-.071.218.059.297c.044.114.137.188.225.262c-.118.026-.077.114-.072.187c-.191-.059-.287-.204-.361-.373");
}

.gt46jvbft {
  fill: var(--svg-color--d4d400, #d4d400);
  d: path("m51.06 34.04l-.049.004c-.128-.133-.127-.262.022-.382l.021-.021c.004.131.005.267.006.399");
}

.gwf935yem {
  fill: var(--svg-color--11110a, #11110a);
  d: path("m48.727 29.378l-.088.07c-.1.068-.191.163-.331.127c-.214-.131-.382-.32-.614-.424c-.264-.118-.271-.412-.403-.619a.27.27 0 0 1-.045-.195q.026-.125.071-.239c.028-.045.06-.08.118-.066c.074.518.512.721.864 1q.216.172.428.346");
}

.gwwgxz1qy {
  fill: var(--svg-color--ee0, #ee0);
  d: path("m49.03 36.28l.006.428l-.074.001c.016-.144-.062-.302.068-.429");
}

.gwyf81b0b {
  fill: var(--svg-color--8d9113, #8d9113);
  d: path("m48.925 38.96l.026-.136c.091.243.051.497.043.745l-.051-.009z");
}

.gx9c6lbxr {
  fill: var(--svg-color--425b76, #425b76);
  d: path("m48.18 39.864l.174-.005c-.016.071-.028.149-.044.221l-.061-.003c-.022-.042-.039-.089-.074-.124c0 0-.011-.03-.018-.044q.01-.024.023-.045");
}

.gzdtn4m5h {
  fill: var(--svg-color--2c3c4e, #2c3c4e);
  d: path("M46.849 39.462c-.055.06-.107.166-.169.173c-.106.007.045-.159-.079-.179a.55.55 0 0 1-.063-.313c.127.122.289.119.445.115c-.051.064-.182.072-.134.204");
}

.gzgs43ypv {
  fill: var(--svg-color--425a75, #425a75);
  d: path("M45.2 39.986a3 3 0 0 0-.071-.153c.091.031.142-.048.212-.072c.013.109-.078.16-.141.225");
}

.h-hq-vb4k {
  fill: var(--svg-color--f5f5f3, #f5f5f3);
  d: path("M46.19 28.08c.231.053.535-.034.606.32a.23.23 0 0 1-.131.088c-.243.073-.313.318-.462.482c-.081.089-.1.24-.258.248c-.129-.132-.025-.277-.018-.415c.017-.261.055-.525-.192-.711c-.134-.063.016-.306-.203-.314c-.024-.192.172-.035.211-.131l-.002-.006c.118-.044.198-.175.345-.157c.069-.029.136-.035.192.027a.67.67 0 0 1-.085.384c-.13.06-.04.121-.003.185");
}

.h1bcsp6yg {
  fill: var(--svg-color--393939, #393939);
  d: path("M49.06 33.481c.098-.074.212-.05.323-.049l5.88.047l.002.081c-.367.057-.739.017-1.107.017c-.915.002-1.831-.014-2.748-.021c-.148-.001-.297-.011-.437.052c-.604.013-1.21.039-1.813-.031a.2.2 0 0 1-.1-.096");
}

.h2ulc9rvt {
  fill: var(--svg-color--4d4d4d, #4d4d4d);
  d: path("M54.09 41.17h-.063c.063-.098-.006-.291.205-.281l-.051.137z");
}

.h2xjhmlqu {
  fill: var(--svg-color--fefe00, #fefe00);
  d: path("M54.98 27.727c.114.074.147.171.148.313c-.007 1.612.002 3.225.002 4.838c.001.146-.019.297-.029.441c-.114.134-.271.111-.417.11q-7.278-.052-14.556-.112c-.147-.001-.303.02-.414-.116l-.02-1.563l.073-3.598c.004-.145-.018-.295.06-.433c.263-.027.503-.125.744-.231c.204-.088.469-.043.61-.275c.221.084.406.057.543-.155h.021c.266.046.502-.171.771-.087c.192-.082.45.043.586-.197a.3.3 0 0 1 .072-.004c.173.16.353.016.524-.002c.561-.055 1.121-.133 1.683-.205l.435-.022c1.265-.077 2.529-.027 3.79.061c.223.087.451.062.681.076l.839.128q.142.014.28.03c.265.088.538.136.813.157c.188.031.378.048.56.105c.121-.012.219.053.321.105c.025-.021.056-.037.082-.058c.067.208.265.157.413.205c.143-.05.254.01.356.101q.267.105.537.205c.169.055.306.182.492.183");
}

.h5g2hebnu {
  fill: var(--svg-color--fbfbfb, #fbfbfb);
  d: path("M53.709 39.46c-.067-.174.036-.255.175-.301c.11-.035.228-.049.339-.068c.091.127.113.25-.02.365q-.033.015-.029.055c-.165.057-.328.135-.465-.051");
}

.h5vqhpdms {
  fill: var(--svg-color--54613b, #54613b);
  d: path("M48.819 34.02c-.006-.102.064-.217-.066-.29q.046-.074.088-.147c.133.13.023.295.065.439q-.041-.003-.087-.002");
}

.h96tzp7wb {
  fill: var(--svg-color--87baf1, #87baf1);
  d: path("M45.978 35.05q.144.03.288.063c.127.137.09.272 0 .409c-.104.116-.219.213-.392.166c-.123-.068-.109-.163-.051-.27c.049-.102.099-.202.148-.309q-.024-.02-.013-.042z");
}

.h9rz_fr0f {
  fill: var(--svg-color--dadce3, #dadce3);
  d: path("M45.35 46.574q.271.117.543.238q.029.037.005.075a.1.1 0 0 1-.077.025c-.223.004-.382-.121-.535-.26q-.044-.098.064-.078");
}

.hhbec5kvd {
  fill: var(--svg-color--e0e3ea, #e0e3ea);
  d: path("M39.457 28.11q.026 0 .051-.002c.179.301.173.604-.003.904l-.055-.002z");
}

.hhtzz0brx {
  fill: var(--svg-color--c6cbd6, #c6cbd6);
  d: path("M49.46 26.27c.084-.021.18.001.246-.078a5 5 0 0 1 1.013.128c-.029.091-.124.108-.19.155a.26.26 0 0 1-.139.044c-.126-.014-.24-.102-.374-.054q-.05.005-.1.003c-.119-.012-.237-.002-.354-.032c-.065-.035-.108-.086-.102-.166");
}

.hivpijqcv {
  fill: var(--svg-color--2f73b8, #2f73b8);
  d: path("m47.25 45.02l-.273-.046c.244-.105.407-.172.568-.245c.012.21-.133.259-.295.291");
}

.hjkyq9bhu {
  fill: var(--svg-color--c5c9d3, #c5c9d3);
  d: path("M41.575 43.02c.096.056.186.118.142.256q-.005.057-.06.04c-.098-.041-.127-.128-.16-.217c-.031-.081.007-.095.078-.079");
}

.hka8m-uzp {
  fill: var(--svg-color--07ca6d, #07ca6d);
  d: path("M45.3 45.44q-.038-.002-.077-.002a.36.36 0 0 0-.329-.031c-.067 0-.135.013-.199-.02c-.044-.149.104-.104.157-.151c.197-.032.396-.108.592.005c.03.076-.021.109-.072.143q-.038.027-.072.056");
}

.hnn0m1bhg {
  fill: var(--svg-color--07090a, #07090a);
  d: path("M52.34 34.807c-.799-.004-1.592-.008-2.39-.009c-.122-.035-.082-.095-.012-.135c.148-.084.322-.071.486-.083c.146.021.292.036.439.033q.053-.002.109.001c.034-.002.072 0 .106 0c.039.001.072.008.108.014c.087.019.177.036.256.078c.294.07.614-.075.898.101");
}

.hnswvql5h {
  fill: var(--svg-color--d8d7d6, #d8d7d6);
  d: path("M46.913 30.14a2 2 0 0 0-.148-.026q-.068-.075-.137-.146l.064-.08q.03.01.062.016c.102.043.22.078.159.236");
}

.hofmrcc0y {
  fill: var(--svg-color--6a706a, #6a706a);
  d: path("M46.34 36.33c-.027-.003-.059-.003-.086-.005c-.057-.01-.129.012-.137-.079c.1-.104.218-.095.338-.041a.1.1 0 0 1 .048.102q-.037.059-.101.032l-.029-.011z");
}

.hq2zgdctd {
  fill: var(--svg-color--57789c, #57789c);
  d: path("M46.983 40.3q-.001.107.001.216l-.15-.064c-.054-.037-.076-.082-.032-.141c.055-.081.121-.029.181-.011");
}

.hrwred6hu {
  fill: var(--svg-color--6288b0, #6288b0);
  d: path("M47.27 40.542c-.101.045-.196.061-.28-.027c-.057-.072-.07-.145-.001-.216c.026-.06.079-.075.142-.081q.066.162.139.324");
}

.hvnxhnbla {
  fill: var(--svg-color--202008, #202008);
  d: path("M49.605 30.729c.207.107.431.189.512.441l-.519-.291c-.04-.05-.044-.101.007-.15");
}

.hwdiqabgf {
  fill: var(--svg-color--04b500, #04b500);
  d: path("M41.479 41.472c.073-.089.334.01.424.137c.107.156.231.3.346.444c.066.1.055.203.005.303l-.116.04l.117.109c.062.079.138.113.238.086l.353.142c.098.099.157.207.11.351a.535.535 0 0 1-.601-.045a1 1 0 0 0-.335-.129c-.076-.031-.136-.082-.135-.162c.003-.35-.07-.646-.392-.861c-.118-.083-.088-.273-.014-.415");
}

.hwgyo49jx {
  fill: var(--svg-color--121517, #121517);
  d: path("M46.642 37.43c-.375-.11-.756-.05-1.134-.044c-.061-.116-.061-.116.228-.166c.158-.001.315-.039.475-.025q.052 0 .104.004q.08 0 .159.004a1 1 0 0 1 .104 0h.211q.053-.003.109-.002c.129.01.259-.019.389-.035c.168.048.428-.063.445.254a1.77 1.77 0 0 1-1.09.01");
}

.hx37ucbvb {
  fill: var(--svg-color--dfdfda, #dfdfda);
  d: path("M46.99 29.21c.092-.054.223.041.295-.077a1 1 0 0 1 .01.094c.009.02.007.036.007.036c-.111.128-.232.114-.357.064c-.067-.07-.04-.104.045-.117");
}

.hzbab8bkc {
  fill: var(--svg-color--091222, #091222);
  d: path("M48.5 45.911c-.32.036-.623.036-.729-.361q.071.038.142.079c.145.202.408.151.587.282");
}

.hzyb8mbyk {
  fill: var(--svg-color--47627f, #47627f);
  d: path("M45.823 35.423c.019.076-.047.185.076.226c.008.13-.058.122-.146.076l-.086-.005c.031-.11.058-.221.156-.297");
}

.i_xs5g0gw {
  fill: var(--svg-color--f8f8f0, #f8f8f0);
  d: path("M46.604 29.631c-.014.099.033.179.088.253q.038.097-.064.08c-.111-.086-.186-.247-.372-.195c-.142-.191-.014-.352.067-.517a.2.2 0 0 1 .093-.07c.06-.013.114-.003.153.048c.025.131-.009.272.035.401");
}

.i02jpcbtm {
  fill: var(--svg-color--111517, #111517);
  d: path("M45.27 38.699c.081.028.148-.009.21-.054c.146.057.256-.112.402-.061c.121.03.248.031.373.032c.077-.009.153-.003.227-.003a1 1 0 0 0 .122-.004c.212-.01.419.018.63.006c.118.035.289-.002.275.206c-.18.025-.36.033-.537-.013l-1.701-.005c-.074-.032-.087-.066-.001-.104");
}

.i08bmib8y {
  fill: var(--svg-color--853f00, #853f00);
  d: path("m52.37 40.862l.008.66c-.057.001-.114.005-.174.004l.025-.598z");
}

.i103nc18k {
  fill: var(--svg-color--e2e4ea, #e2e4ea);
  d: path("M48.5 47.11a.4.4 0 0 0 0-.068c-.015-.164.15-.133.215-.208l.309-.101c.072-.078.145-.153.267-.097l.037.036c-.238.22-.525.343-.828.438");
}

.i4vhf0ksp {
  fill: var(--svg-color--515e58, #515e58);
  d: path("M48.84 34.628c.01-.132-.054-.227-.157-.297q.22-.003.443-.009c-.071.089-.078.198-.092.307a.13.13 0 0 1-.061.046a.2.2 0 0 1-.076-.001a.1.1 0 0 1-.057-.046");
}

.i7abhqbtx {
  fill: var(--svg-color--75a1d1, #75a1d1);
  d: path("M47.44 40.591c.087-.072.19-.076.294-.065c.03.144-.15.186-.147.314a.16.16 0 0 1-.152.018a.14.14 0 0 1-.082-.123q.044-.075.087-.144");
}

.i8685nbwx {
  fill: var(--svg-color--10a000, #10a000);
  d: path("m44.24 38.475l-.092.006c-.158-.041-.133-.129-.06-.228l.071-.077q.038.037.075.078q.005.108.006.221");
}

.i9t70lb8l {
  fill: var(--svg-color--b3b7c0, #b3b7c0);
  d: path("M51.5 26.425c.208.059.477-.052.607.216c-.098.116-.23.099-.36.091c-.083-.009-.164-.033-.249-.045a.2.2 0 0 1-.092-.029c-.053-.041-.088-.094-.074-.167c.044-.054.12-.027.168-.066");
}

.iajg6sr7b {
  fill: var(--svg-color--c2c3c7, #c2c3c7);
  d: path("M39.4 35.75c.09.124.062.261.04.396a.7.7 0 0 1-.04-.396");
}

.icbl1e5df {
  fill: var(--svg-color--778492, #778492);
  d: path("m49.41 37.12l-.309-.027c.12-.178.225-.184.309.027");
}

.ie763cbsv {
  fill: var(--svg-color--2d3545, #2d3545);
  d: path("M51.26 45.29c-.166-.023-.22.159-.358.188q.069-.314.393-.27z");
}

.ifi9r9bmx {
  fill: var(--svg-color--0b0500, #0b0500);
  d: path("M51.06 41.38c.038-.176-.108-.342-.033-.521c.534-.135.603.23.655.611l.004.04c-.225.038-.452.073-.626-.13");
}

.ifo7ekb8v {
  fill: var(--svg-color--09c670, #09c670);
  d: path("M43.929 45.03c.117-.057.197-.057.277 0c-.08.058-.164.053-.277 0");
}

.ifsjtqihb {
  fill: var(--svg-color--2b2b2b, #2b2b2b);
  d: path("M49.37 30.531c-.045-.139.018-.183.145-.167c.155.018.321-.044.462.067c-.045.075-.114.089-.194.081c.184.102.354.237.58.229c.063.037.145.091.04.151c-.128.075-.159.194-.213.31l-.074-.031a2.1 2.1 0 0 0-.518-.369c-.077-.059-.176-.092-.231-.18a.09.09 0 0 1 .003-.091");
}

.ig6-me4ra {
  fill: var(--svg-color--040200, #040200);
  d: path("M52.741 41.467c-.107.11-.242.046-.365.056c-.145-.218-.111-.438-.008-.66l-.004-.002c.15-.09.3-.114.441.021l-.003.122c-.072.149.082.325-.061.463");
}

.ih9yt7b5f {
  fill: var(--svg-color--080, #080);
  d: path("M49.889 41.895c.164.04.317.107.499.023c.144-.064.312-.042.471.026c-.329-.108-.631.331-.971.021q-.037-.024-.024-.046q.013-.024.025-.024");
}

.ik2e__b5v {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M53.01 38.913c-.016-.187.064-.35.125-.519c.09-.14.209-.12.338-.065c.002.021.011.043.011.043l.028.034c-.115.131.021.313-.09.444l.005-.009c-.111.176-.262.127-.413.073h-.004");
}

.ik3x-ztty {
  fill: var(--svg-color--5a788d, #5a788d);
  d: path("m46.49 37.28l.012-.518a.13.13 0 0 1 .091-.008c.069.039.16.063.119.174c-.251.037-.126.229-.144.36z");
}

.im4olbjbg {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M46.42 26.09q.914-.004 1.83-.001c.067.001.153-.022.19.069q.04.053-.004.104a.27.27 0 0 1-.171.038c-.156-.043-.314-.028-.471-.028l-.668-.006c-.178.001-.358-.021-.536.021a.24.24 0 0 1-.17-.035c-.041-.057-.047-.11 0-.162");
}

.iq6krieyx {
  fill: var(--svg-color--8cc1f9, #8cc1f9);
  d: path("M46.539 36.772c.037-.154-.081-.335.096-.457c.095.045.188.082.292.024c.126-.054.217-.216.39-.134c.063.053.165.072.147.187l-.449.608l-.224.023l-.082-.098c-.058-.048-.114-.103-.17-.153");
}

.ir2o-pbxi {
  fill: var(--svg-color--07b100, #07b100);
  d: path("M44.21 39.747q-.105.042-.207.079c-.146-.162-.07-.472-.363-.535c-.01-.058-.026-.112.039-.149c.079-.043.087-.166.199-.167c.289.134.232.463.378.677a.14.14 0 0 1-.046.095");
}

.irx08obdw {
  fill: var(--svg-color--06cb6c, #06cb6c);
  d: path("M50.53 44.808c.2-.152.419-.042.707-.071c-.237.316-.471.237-.704.153q-.064-.04-.003-.082");
}

.iuizy8b1u {
  fill: var(--svg-color--50645d, #50645d);
  d: path("m46.26 37.824l.035-.002c.16.147.111.316.068.483q-.026.022-.051.04c-.151-.081.033-.288-.138-.365c-.012-.075.03-.119.086-.156");
}

.iwjjbd5ak {
  fill: var(--svg-color--3e2f00, #3e2f00);
  d: path("M44.823 40.524c.117-.123-.05-.166-.066-.251c.018-.071.047-.134.118-.167a.17.17 0 0 1 .107.001c.05.025.079.071.112.12c.08.176.113.332-.158.346z");
}

.iwogh8cni {
  fill: var(--svg-color--384e65, #384e65);
  d: path("m51.634 39.657l-.203-.012q-.017-.145-.031-.293a.2.2 0 0 1 .089-.046c.139.006.281-.006.399.092c.05.056.077.116.062.191l-.025-.005c-.088.06-.181.106-.291.073");
}

.j_hoc9boy {
  fill: var(--svg-color--c0c3ca, #c0c3ca);
  d: path("M42.841 44.685a.55.55 0 0 1 .357.363c-.219-.024-.342-.141-.357-.363");
}

.j_kxcfv-e {
  fill: var(--svg-color--0a0b0c, #0a0b0c);
  d: path("m49.934 36.884l-.076.067c.005-.179-.127-.148-.232-.149a44 44 0 0 0-.894-.021q-.038-.017-.025-.036c.006-.013.017-.017.017-.017q.082-.014.152-.021l.084.001a.5.5 0 0 1 .085-.052a.4.4 0 0 1 .098-.023c.114-.007.229-.009.342.021l.285.064c.1.012.145.078.164.166");
}

.j18a0kbue {
  fill: var(--svg-color--ad5200, #ad5200);
  d: path("M51.684 41.679c.06-.028.074-.079.08-.14c.044-.053.105-.068.171-.065c.195.066.435-.043.595.149c-.251.051-.156.271-.209.472c-.069-.194-.004-.44-.3-.43c-.185.01-.197.104-.188.24q-.035.051-.065-.002a4 4 0 0 1-.084-.224");
}

.j3gqe6g2z {
  fill: var(--svg-color--82b3e7, #82b3e7);
  d: path("m46.765 37.28l-.199.002c-.113-.164-.134-.311.078-.41a.22.22 0 0 1 .17.056c.102.132.105.251-.049.352");
}

.j3k14db6t {
  fill: var(--svg-color--7ba6c8, #7ba6c8);
  d: path("m50.937 38.07l.027.06l-.003.327c-.133-.006-.276.051-.396-.061c.213-.02.207-.238.322-.343a.14.14 0 0 0 .05.017");
}

.j3mxojx7l {
  fill: var(--svg-color--3d3d3d, #3d3d3d);
  d: path("M54.47 40.13c.045.142-.169.281-.001.421l.004-.007l-.225.101c-.116-.209-.006-.361.113-.514q.055-.035.109-.001");
}

.j4r5qlbkl {
  fill: var(--svg-color--5b5b5b, #5b5b5b);
  d: path("m55.23 30.25l.003-.445c.021-.035.042-.03.062.004l.01-.014c-.045.149.035.32-.075.455");
}

.j4xg7umzz {
  fill: var(--svg-color--768ba1, #768ba1);
  d: path("m46.18 37.674l.013.035c-.082-.011-.163-.036-.246-.061q-.03-.026-.017-.042l.024-.019c.146-.154.169.011.226.087");
}

.j6722qbiw {
  fill: var(--svg-color--c0c3ca, #c0c3ca);
  d: path("M51.36 45.12c.134-.143.25-.304.447-.37c-.033.263-.195.372-.447.37");
}

.jc8x92bab {
  fill: var(--svg-color--c35c00, #c35c00);
  d: path("M50.707 41.16c-.129.184.316.239.108.389c-.121.088-.337.049-.511.064c-1.134.098-2.267.033-3.396-.056c.094-.19.248-.072.38-.069c.524 0 1.048-.003 1.569.004c.172.004.32-.027.435-.168c.074.004.147.011.222.005c.139-.015.321.063.39-.119c.062-.164.05-.34-.102-.47c.026-.151.145-.114.242-.119c.063-.025.1.01.132.057c.057.124.03.262.049.392c.035.246.134.34.346.138c.038-.038.076-.072.136-.048");
}

.jckcn65oj {
  fill: var(--svg-color--f2ea1e, #f2ea1e);
  d: path("M46.696 28.857c-.114-.09.101-.254-.074-.331l.001-.115q.085-.009.168-.014c.147.191.016.321-.095.46");
}

.jcqk3espa {
  fill: var(--svg-color--f4f4d9, #f4f4d9);
  d: path("M54.56 27.415q-.039.063-.073.129c-.22.09-.387-.003-.537-.154c-.009-.037.005-.067.03-.094c.063-.041.135-.037.206-.038q.185.08.374.157");
}

.jeiyxrb6s {
  fill: var(--svg-color--8dc3fc, #8dc3fc);
  d: path("M48.916 41.27h-.888c-.19-.275.015-.521.062-.78c.061-.132.078-.275.126-.411c.016-.067.026-.136.05-.199c.012-.047.029-.093.041-.141q.02-.099.045-.195l.062-.248c.044-.183.092-.357.141-.535a.24.24 0 0 1 .115-.138c.297-.055.28.197.354.364c.031.194.016.395.018.594l-.006.813c-.041.293.088.608-.12.876");
}

.jff5enb5x {
  fill: var(--svg-color--030100, #030100);
  d: path("M49.803 40.737c.109-.033.241-.066.231.106c-.01.199.126.487-.076.57c-.183.075-.479.17-.665-.093l-.002.006c.049-.087.148-.123.196-.21a.7.7 0 0 1 .264-.279z");
}

.jg56k0b2p {
  fill: var(--svg-color--fafbfd, #fafbfd);
  d: path("m50.925 33.536l4.336.024l-.014.512c-.114-.098-.003-.27-.121-.369c-.065-.076-.152-.072-.239-.073q-1.827-.015-3.653-.025c-.062-.001-.12.024-.181.038a.065.065 0 0 1-.047.063a.14.14 0 0 1-.085-.018a.14.14 0 0 1-.037-.078a.1.1 0 0 1 .041-.074");
}

.jhmwzobhm {
  fill: var(--svg-color--6186ad, #6186ad);
  d: path("M51.78 39.05c.015.078-.032.175.067.231c.067.043.089.09.019.148c-.113-.081-.278.063-.378-.088c.213-.045.138-.211.146-.342q.074.028.146.051");
}

.jhv5yj_6m {
  fill: var(--svg-color--04b500, #04b500);
  d: path("M40.647 38.961q-.04.04-.078.084l-.004-.344c.247.019.082.163.082.26");
}

.jit9j4fca {
  fill: var(--svg-color--8ec3fd, #8ec3fd);
  d: path("M50.565 38.39q-.14.03-.28.064c-.05.011-.05.042-.012.067c.017.013.044.014.069.02c.087.03.135.109.2.169a.36.36 0 0 1 .084.155q.02.087.051.169a.09.09 0 0 1-.022.079q-.072.047-.146.092c-.115.017-.063.223-.217.194q-.118-.178-.238-.354c-.075-.082-.08-.2-.141-.289l-.076-.08q.077-.079.153-.162c.048-.102.076-.198-.024-.284a.8.8 0 0 1-.331-.101c-.228-.129-.478-.232-.601-.488c-.004-.16-.046-.325.06-.473l.01-.082l-.005.004c.108-.056.217-.091.309.027c.23.155.305-.101.45-.171a.12.12 0 0 1 .076-.067c.019.003.038.001.038.001a.24.24 0 0 1 .026.117c.044.079.136.088.205.125c.152.131.248.303.369.457c.056.12.131.224.234.304c.065.063.128.129.113.23c-.059.167-.112.337-.354.277");
}

.jjiw8ibvv {
  fill: var(--svg-color--0ac473, #0ac473);
  d: path("m49.653 43.31l-.078.018l-.231-.031c.103-.117.206-.045.303-.045q.005.028.006.058");
}

.jjr_gqpor {
  fill: var(--svg-color--dfe9f4, #dfe9f4);
  d: path("m54.45 39.901l-.046.229q-.08.254-.158.513c-.065.079-.065.162-.017.249c-.15.055-.104.226-.188.317c-.075.104-.048.264-.186.338l-.233.605c-.26.076-.284-.057-.202-.246c.123-.276.261-.549.367-.833c.155-.293.23-.62.354-.927c.049-.131.057-.298.241-.332z");
}

.jjre5bczz {
  fill: var(--svg-color--c05b00, #c05b00);
  d: path("m51.06 41.38l-.029-.007a1 1 0 0 1-.141-.661q.027.034.053.07c.026.026.057.052.084.077c.101.171.205.337.033.521");
}

.jk3vibbej {
  fill: var(--svg-color--fdfdfd, #fdfdfd);
  d: path("M45.583 37.599c-.065-.035-.063-.099-.075-.158a.1.1 0 0 0 0-.055c.37-.179.742-.172 1.121-.025c.073.119.016.204-.068.285c-.1.074-.206.107-.331.068c-.105-.055-.205-.14-.339-.084c-.104-.01-.213.025-.308-.031");
}

.jmnl93b4j {
  fill: var(--svg-color--393b3d, #393b3d);
  d: path("m51.95 36.681l-.001.125c-.38.047-.769-.095-1.142.064c-.074.04-.125-.002-.177-.046a.2.2 0 0 1-.054-.138a.14.14 0 0 1 .063-.079c.079-.035.165-.038.249-.042q.051-.001.102.005a.6.6 0 0 1 .144.052z");
}

.jnv_imvua {
  fill: var(--svg-color--ce6200, #ce6200);
  d: path("M46.908 30.582c.027-.008.053-.008.078-.017l.161-.09q.038.05.072.101c-.103.091-.206.081-.311.006");
}

.jo2su9qqt {
  fill: var(--svg-color--474a10, #474a10);
  d: path("m51.16 37.938l.033.149l-.063.355q-.088.005-.174.012c-.071-.086-.088-.177-.034-.277c.027-.036.063-.041.1-.011c.201.01.049-.161.115-.223z");
}

.jo83idbol {
  fill: var(--svg-color--d7dae2, #d7dae2);
  d: path("M46.34 47.09c.244.009.391.282.65.246q.048.013.046.06c-.023.045-.055.072-.104.076c-.255-.036-.473-.152-.679-.295q.018-.073.087-.087");
}

.jotua5b3t {
  fill: var(--svg-color--3f5771, #3f5771);
  d: path("m52.15 39.965l-.081.059c-.1-.038-.262.085-.301-.112c.002-.181.185-.117.26-.198c.121.048.173.124.122.251");
}

.jpoiibbok {
  fill: var(--svg-color--292929, #292929);
  d: path("M48.827 33.431q-4.631-.032-9.264-.067l-.005-.095l7.442.069q.913.011 1.832.025q.025.025.014.046c-.006.018-.012.022-.019.022");
}

.jqelgrb_x {
  fill: var(--svg-color--8cc1fa, #8cc1fa);
  d: path("m45.27 38.699l.001-.202c.041-.18.037-.363.059-.545c.117-.15-.017-.373.141-.518l.034.006c.058.02.1.063.15.093c.095.058.206.033.312.052a.5.5 0 0 1 .232.089a.22.22 0 0 1 .085.129a.5.5 0 0 1-.046.21c-.193.28-.417.529-.722.697c-.08-.002-.167.094-.246-.011");
}

.js1xiy44u {
  fill: var(--svg-color--2f3f51, #2f3f51);
  d: path("m48.818 35.22l.009-.089l.067-.059q.045-.035.09-.063a.5.5 0 0 1 .108-.025c.162-.04.318.064.479.025c.155-.012.268.218.442.075l.17.001a2 2 0 0 1-.022.137c-.445.229-.895.187-1.343-.002");
}

.jsqvsxrgx {
  fill: var(--svg-color--719abf, #719abf);
  d: path("M48.52 34.837c.111.09.13-.012.167-.079c.188-.055.205.095.253.209a.3.3 0 0 1-.001.111c-.02.054-.053.09-.114.099c-.17-.082-.402.02-.53-.182q.112-.08.225-.158");
}

.jsxe1hbhc {
  fill: var(--svg-color--374c63, #374c63);
  d: path("M48.18 39.09c-.003-.116.062-.203.132-.289c.104-.063.208-.096.312.004a1.5 1.5 0 0 1-.15.526c-.221.067-.3-.033-.294-.241");
}

.jtqyig_0h {
  fill: var(--svg-color--14b086, #14b086);
  d: path("m48.829 44.27l-.246.074q-.036-.056-.068-.11c.113-.065.217-.036.314.036");
}

.jvi_65bln {
  fill: var(--svg-color--8ec4fe, #8ec4fe);
  d: path("M47.51 38.804c-.064-.15-.203-.034-.294-.085c-.237-.083-.504-.114-.639-.373a.22.22 0 0 1 .006-.155c.12-.168.291-.285.455-.407c.085-.05.171-.109.261-.155a1.7 1.7 0 0 0 .444-.248c-.137-.14-.338-.046-.489-.135c-.071.024-.144.029-.207-.023a.3.3 0 0 1-.081-.198c.063-.261.272-.427.417-.638c.06-.071.112-.152.168-.232c.057-.076.11-.155.207-.186c.04-.075.104-.158-.059-.159c-.207-.002-.413.015-.61-.074a.75.75 0 0 1-.651-.337c-.041-.101-.016-.197.036-.29c.066-.069.149-.058.229-.049a.47.47 0 0 0 .326.07c.263-.044.612.065.66-.365c-.208-.075-.429-.019-.637-.087a.5.5 0 0 1-.185-.096c-.083-.077-.139-.185-.249-.234c-.039-.027-.076-.059-.042-.114c-.129-.205.011-.471-.149-.669l2.387-.004l.034.043a.3.3 0 0 1-.026.164c-.087.159-.247.201-.399.254c-.081.041-.192.013-.244.114c.018.071.077.119.114.177c.08.177.25.307.257.518c-.034.104-.124.156-.204.215c-.055.035-.111.071-.171.099c-.047.028-.114.043-.093.12c.047.069.116.106.178.153c.095.089.192.074.295.011a.28.28 0 0 1 .199-.032c.096.032.147.108.185.193c.05.135.051.279.078.42a.3.3 0 0 1-.019.102c-.04.078-.103.14-.157.207c-.157.165-.354.254-.563.321c-.107.076-.284.028-.349.188c.003.118.067.189.177.226a.46.46 0 0 0 .322-.05a.38.38 0 0 1 .416.066c.121.123.14.272.098.432c-.041.127-.149.208-.215.318a1 1 0 0 1-.431.365c-.07.029-.146.031-.213.069c-.024.04-.016.078-.001.12l.046.076c.048.107.178.125.24.211a.24.24 0 0 1 .021.148c-.033.113-.095.216-.137.326c-.055.156-.11.313-.222.441a.84.84 0 0 0-.171.446a.4.4 0 0 1-.099.175c-.135.111-.198.269-.261.424a.3.3 0 0 1-.141.15a.15.15 0 0 1-.102-.016a.4.4 0 0 1-.086-.189c-.031-.113-.085-.22-.125-.329a2.6 2.6 0 0 0-.193-.465a1.5 1.5 0 0 1-.069-.306c-.016-.145.094-.171.196-.207l.305-.001a.46.46 0 0 0 .379-.001c.049-.052.095-.102.146-.152c.172-.373-.198-.202-.299-.301");
}

.jvxt7nb2v {
  fill: var(--svg-color--8fc4fe, #8fc4fe);
  d: path("M40.22 34.939c-.247.093-.32.362-.515.509c-.134-.093-.133-.238-.117-.368c.048-.345-.018-.691.002-1.035c.01-.168-.019-.344.063-.505c.091-.129.229-.139.367-.137c2.07.021 4.144.008 6.214.062q.062.015.117.053c.108.137.005.302.055.445a.4.4 0 0 1-.014.106c-.029.063-.082.111-.124.166c-.146.16-.303.311-.495.419c-.092.087-.257-.013-.323.134a.29.29 0 0 0 .15.197c.121.062.271.021.377.119c.071.132.004.24-.063.349c-.075.089-.133.194-.199.289c-.064.098-.211.118-.237.253c-.009.066-.008.131-.009.197q.002.108-.009.213c-.287.665-.616 1.309-1.082 1.873a.11.11 0 0 1-.106-.035c-.129-.202-.11-.452-.196-.67c-.159-.466-.052-.961-.151-1.438c-.03-.138-.038-.27-.189-.332c-.106-.066-.234-.104-.33-.191c-.121-.111-.158-.269-.206-.416c-.079-.224-.187-.177-.306-.04c-.16.184-.166.44-.301.637c-.139.309-.459.421-.688.63c-.373.07-.41-.27-.571-.457c-.058-.107-.092-.222-.134-.334a.7.7 0 0 0-.23-.365c-.117-.12-.155-.268-.182-.43c-.043-.28-.08-.287-.33-.074c-.067.076-.102.194-.238.176");
}

.jww3y3_gn {
  fill: var(--svg-color--0bc175, #0bc175);
  d: path("M44.1 44.842c.16.033.301-.125.511-.031c-.196.042-.339.173-.507.027z");
}

.jxpdknbil {
  fill: var(--svg-color--09c571, #09c571);
  d: path("M44.11 44.838c-.234.018-.382-.104-.534-.301c.303-.055.472.03.53.305z");
}

.jy_69w-gl {
  fill: var(--svg-color--494949, #494949);
  d: path("M39.644 29.31q-.003.263-.008.518q-.031-.076-.064-.151l.022-.366z");
}

.k0jncobnd {
  fill: var(--svg-color--161616, #161616);
  d: path("M54.19 27.26c-.03.062-.085.072-.144.067c-.077-.063-.284 0-.205-.212c.067.021.133.037.2.056c.055.022.125.023.149.089");
}

.k15824bij {
  fill: var(--svg-color--6388b1, #6388b1);
  d: path("M47.46 36.39c-.043-.066-.147-.084-.147-.187l.336-.023q-.098.104-.189.21");
}

.k1fl-ob7i {
  fill: var(--svg-color--8bbff7, #8bbff7);
  d: path("m46.23 38.497l.01.21c-.127.004-.262.051-.382-.042c.099-.109.25-.112.372-.168");
}

.k2s-ucblc {
  fill: var(--svg-color--56623d, #56623d);
  d: path("m50.898 36.14l.014-.97c.056.029.107.06.162.09a.2.2 0 0 1-.009.043c-.019.257.013.516-.026.774a.15.15 0 0 1-.084.081q-.028-.01-.057-.018");
}

.k44cku7wk {
  fill: var(--svg-color--8dc1f9, #8dc1f9);
  d: path("M46.618 38.2c-.019 0-.037-.006-.054-.01q-.004-.22-.005-.44l.296-.065c.048.09.255-.059.219.151c-.134.146-.27.284-.456.364");
}

.k6o--_k_u {
  fill: var(--svg-color--657a90, #657a90);
  d: path("M48.23 35.475c.118.058.236.045.358.034c-.131.134-.254.167-.358-.034");
}

.k6ux2veua {
  fill: var(--svg-color--80b0e4, #80b0e4);
  d: path("M46.51 34.601q.001-.185-.001-.365q.038-.004.076-.003c.02.023.034.047.054.071c.119.031.175.13.233.226c.063.008.125.012.158.077c-.101.119-.242.022-.358.063q-.081-.037-.162-.069");
}

.k88987b1v {
  fill: var(--svg-color--3f5871, #3f5871);
  d: path("M47.43 40.812q.073.015.148.028q-.004.055-.005.11c.013.07-.025.121-.071.168l-.02.021l-.135-.092c-.047-.106-.006-.18.083-.235");
}

.k88eajppw {
  fill: var(--svg-color--3d546d, #3d546d);
  d: path("m45.878 40.931l-.021-.193c-.034-.063.01-.088.056-.109c.078-.006.13.025.149.105c.035.047.063.098.095.148c-.005.047-.05.053-.075.08q-.103-.013-.204-.031");
}

.k8zer6bus {
  fill: var(--svg-color--04d067, #04d067);
  d: path("m44.698 45.36l.227.002c.077-.042.142-.059.141.064c-.141.023-.279.059-.422.061c-.121.006-.085-.072-.043-.136c.037-.03.068-.024.097.009");
}

.kb_jwac4u {
  fill: var(--svg-color--cb6000, #cb6000);
  d: path("m46.23 41.474l.001-.064l.438.02q-.078.036-.151.072a7 7 0 0 0-.288-.028");
}

.kbx13cctw {
  fill: var(--svg-color--17202a, #17202a);
  d: path("M50.13 40.1q-.003-.04-.004-.082c.121-.105.244-.061.369-.006c.042.002.123.001.126.01c.014.116-.131.077-.163.155a.6.6 0 0 1-.328-.077");
}

.kdlw9eb7r {
  fill: var(--svg-color--f6f6e8, #f6f6e8);
  d: path("M51.665 26.643c.153.117.332.062.502.073q.08.001.161.006c.043.055.04.11.003.168a.3.3 0 0 1-.106.058c-.284.011-.564.009-.807-.171c-.019-.076.035-.11.084-.145c.06-.092.109-.022.163.011");
}

.ke_2kcbnl {
  fill: var(--svg-color--773741, #773741);
  d: path("M53.42 38.851c.037-.148-.062-.32.09-.444c-.025.149.05.317-.09.444");
}

.kgc0dnbnx {
  fill: var(--svg-color--04cf68, #04cf68);
  d: path("M49.633 45.712c-.01-.16.16-.139.227-.219c.041.025.195-.092.117.086c-.065.151-.2.16-.344.133");
}

.klg5uga7r {
  fill: var(--svg-color--af5a0d, #af5a0d);
  d: path("M46.852 30.56q-.05.042-.095.086c-.074-.044-.15-.064-.226-.01c.039-.082-.055-.268.162-.222c.035.065.176.021.159.146");
}

.km5x11bgu {
  fill: var(--svg-color--2b3990, #2b3990);
  d: path("M32 10.01V10H19v6.699zm-19 6.689V10h-3c-2.62 0-4.723.778-6.318 2.085z");
}

.knwgn0bxc {
  fill: var(--svg-color--415a74, #415a74);
  d: path("M49.984 39.05c-.1.05-.198.101-.302.15a1.1 1.1 0 0 1-.16-.526c.104-.005.206.069.314.008c.047.017.096.032.125.08c.042.093.088.187.023.288");
}

.koa3sf-di {
  fill: var(--svg-color--0d0d10, #0d0d10);
  d: path("M53.01 38.913q-.052.145-.108.289c.003.05.017.097.017.145c-.006.098-.004.196-.062.283l-.038.028c-.109.068-.098.198-.144.298l-.007.077c-.1.088-.187.069-.262-.036c-.048-.123-.007-.242.023-.361c.118-.311.146-.65.314-.943c.165-.109.06-.454.375-.429c.053.031.071.082.074.14c-.016.184-.046.365-.182.509");
}

.kpfy2bbxy {
  fill: var(--svg-color--dce0eb, #dce0eb);
  d: path("m39.464 36.57l.074-.001c.188.068.061.232.102.343c.021.112.092.216.059.339c-.037.083-.01.198-.119.25a4.5 4.5 0 0 1-.116-.931");
}

.kplk1rb-l {
  fill: var(--svg-color--4d4d14, #4d4d14);
  d: path("m47.813 29.596l-.005.085c-.145.041-.268.148-.431.121a.32.32 0 0 1-.171-.109c-.023-.051-.006-.097.028-.14c.084-.075.16-.165.283-.185c.11.061.246.087.296.228");
}

.kqdvrm-lf {
  fill: var(--svg-color--ccce08, #ccce08);
  d: path("m50.911 37.19l.142-.008l.087.098c.052.211-.012.43.022.642c.043.269.023.298-.159.272c-.106-.166-.035-.368-.112-.541c-.015-.155-.11-.314.02-.463");
}

.krh2n9bjn {
  fill: var(--svg-color--fefefc, #fefefc);
  d: path("m39.715 33.2l15.387.118c.229-.236-.011-.565.156-.815q.004.449.004.89c-.096.099-.217.112-.344.112c-1.979-.014-3.959-.025-5.938-.048c-.049-.001-.097-.014-.146-.022c-2.925-.039-5.849-.049-8.774-.077c-.169-.001-.353.05-.501-.089q.007-.405.018-.808c.159.226-.068.524.138.739");
}

.ksvezacev {
  fill: var(--svg-color--2c2300, #2c2300);
  d: path("M46.02 30.04c.068-.042.137-.065.204-.003c.071.064.075.13.02.206q-.007.053-.009.107a.54.54 0 0 1-.215-.31");
}

.ku1zx9pra {
  fill: var(--svg-color--843e00, #843e00);
  d: path("M52.741 41.467c0-.156-.029-.317.062-.463l.07.15q.017.185.031.37z");
}

.kv-b9o32x {
  fill: var(--svg-color--02cd5f, #02cd5f);
  d: path("M52.697 43.563a6 6 0 0 0-.208.169c-.184-.423.277-.543.406-.813c.079-.162.195-.461.508-.41l-.003.16c-.222.155-.311.406-.457.618a4 4 0 0 0-.149.188z");
}

.kv9iikv-e {
  fill: var(--svg-color--363029, #363029);
  d: path("m40.62 41.07l-.1-.149q-.043-.15-.09-.3c.201.09.186.274.19.449");
}

.l_1-l0bbr {
  fill: var(--svg-color--747474, #747474);
  d: path("m47.689 26.29l.001-.037c.034-.071.104-.042.146-.079c.155.008.323-.072.463.064c-.193.158-.407.044-.61.052");
}

.l-j-x9bgn {
  fill: var(--svg-color--356dc6, #356dc6);
  d: path("M53.56 42.22c.004.128-.101.196-.154.293c-.342.363-.722.701-.859 1.212c-.029.047-.061.09-.126.053c-.044-.141-.185-.269-.068-.438c-.066-.127-.147-.218-.314-.205c-.404.029-.782-.096-1.157-.223c-.005-.118-.005-.118-.302-.08c-.075.001-.151.015-.2-.063c-.02-.168.096-.188.219-.193a1 1 0 0 1 .105-.001l.208.001q-.093-.002-.188-.001c-.138.005-.28-.025-.41.046c-.051.058-.007.156-.074.211a.86.86 0 0 1-.706.182c-.294-.057-.594-.038-.891-.045c-.044.004-.075-.011-.105-.044v-.067c.11-.113.253-.123.394-.132a.6.6 0 0 0 .369-.028c.055-.021.084-.055.055-.118c-.039-.085-.04-.159.04-.222c.226-.154.477-.099.723-.073c.138.014.269-.036.406-.039c.782.022 1.561-.015 2.338-.093a.7.7 0 0 1 .245-.061c.15.026.327-.009.452.128");
}

.l-o4qg6nl {
  fill: var(--svg-color--ececec, #ececec);
  d: path("M52.02 36.828c.079.005.188-.067.218.078l-.141.138c-.091-.051-.086-.131-.077-.216");
}

.l-yghvbri {
  fill: var(--svg-color--7d3e00, #7d3e00);
  d: path("m42.21 38.39l.067-.001c-.073.232.257.316.213.583c-.191-.148-.316-.293-.353-.505a.13.13 0 0 1 .073-.077");
}

.l0licj1sj {
  fill: var(--svg-color--35485d, #35485d);
  d: path("m47.43 40.812l-.082.236q-.077-.005-.153-.014c-.048-.044-.063-.104-.062-.168c.026-.078.043-.167.163-.127c.017 0 .033-.005.048-.005z");
}

.l2l0rjbme {
  fill: var(--svg-color--1faa00, #1faa00);
  d: path("m40.86 36.807l.107.011c-.008.119-.022.24-.041.436c-.13-.179-.144-.305-.066-.447");
}

.l39dsrbta {
  fill: var(--svg-color--21271d, #21271d);
  d: path("m46.47 39.18l.072-.035c.056.092.114.186.117.3c-.014.077-.048.138-.125.169h-.035a2.5 2.5 0 0 1-.033-.354q.003-.038.004-.08");
}

.l3x5q1pak {
  fill: var(--svg-color--3c536b, #3c536b);
  d: path("m45.935 40.661l.159-.16c.076.008.138.037.128.131c-.01.099-.088.094-.16.102q-.063-.038-.127-.073");
}

.l3zr8hber {
  fill: var(--svg-color--ced2dd, #ced2dd);
  d: path("m44.918 46.26l-.075.142c-.125-.072-.283-.109-.307-.29c.18-.084.273.057.382.148");
}

.l57b3tplw {
  fill: var(--svg-color--324559, #324559);
  d: path("M48.18 39.09c.063.125.143.226.293.241c.011.083.014.165-.065.222l-.065.056c-.041.017-.083.024-.124.033c-.043.01-.083.021-.128.024a.2.2 0 0 1-.085-.019a.24.24 0 0 1-.082-.102q.129-.227.256-.455");
}

.l8hpb--_y {
  fill: var(--svg-color--bb5900, #bb5900);
  d: path("M43.45 42.962h.065c.169.215.295.434.1.723z");
}

.l9fpzikng {
  fill: var(--svg-color--8cc1f9, #8cc1f9);
  d: path("m51.676 35.773l.271.88c-.013.015-.025.034-.025.034c-.287.088-.561.119-.827-.022a.36.36 0 0 1-.065-.18c-.013-.216-.003-.433-.006-.649c.017-.172-.028-.354.082-.512c.156-.054.313-.117.439.064c.057.127.051.271.131.385");
}

.laj568bfn {
  fill: var(--svg-color--15af00, #15af00);
  d: path("m40.784 36.514l.119-.012c.218.211.218.211.064.315q-.059.039-.107-.011c-.006-.101.004-.21-.076-.292");
}

.laqu5jbim {
  fill: var(--svg-color--fafafb, #fafafb);
  d: path("M52.16 26.642c.233-.133.431.021.643.079a.11.11 0 0 1-.028.103c-.149.089-.293-.005-.441-.008a.34.34 0 0 1-.153-.067a.1.1 0 0 1-.021-.107");
}

.lbv6ubsiy {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("m55.32 34.864l-.128-.016c-.062-.23.059-.478-.066-.699c-.144-.125-.128-.271-.053-.423c.084-.073.128-.03.145.058c.021.095-.015.196.028.288c.068.163-.088.366.08.514c0 .094-.005.186-.006.278");
}

.ld6estb2t {
  fill: var(--svg-color--0d0600, #0d0600);
  d: path("M50.586 40.916c-.016.11-.029.218.048.313c.028.23-.135.204-.283.216c-.168.012-.21-.084-.213-.224l-.007-.513c.214-.067.467-.222.455.208");
}

.ld9lntv3x {
  fill: var(--svg-color--252515, #252515);
  d: path("M45.662 28.16c.023-.023.045-.049.068-.07c.332.048.282.321.312.542c.021.162-.086.313-.046.479q.032.069.054.142q.014.044.012.091c0 .072-.026.143.014.212c.039.056.118.092.088.177c-.016.034-.052.036-.083.006c-.065.006-.123.031-.153.097a1.5 1.5 0 0 1-.169-.999c.039-.247.022-.464-.097-.677");
}

.ldbo7ibej {
  fill: var(--svg-color--5c3f07, #5c3f07);
  d: path("M44.38 38.25c.008.185.161.294.225.45c.035.076-.015.093-.074.103a.63.63 0 0 1-.354-.348c-.02-.082-.014-.156.045-.219q.057-.033.109.005z");
}

.lew8ocb3f {
  fill: var(--svg-color--f4f5f8, #f4f5f8);
  d: path("m55.23 27.646l.001-.136c.426.105.156.432.209.655l-.051-.007q-.019-.015-.04-.023c-.095-.112-.021-.259-.072-.379a.2.2 0 0 1-.067-.042q-.015-.044.02-.068");
}

.lf2z7yb-b {
  fill: var(--svg-color--e5e2e2, #e5e2e2);
  d: path("M52.854 39.31c.229-.035.508-.139.416.289l-.075.068l-.375-.001c-.041-.124 0-.241.034-.356");
}

.lg3li_mbp {
  fill: var(--svg-color--090805, #090805);
  d: path("M46.531 30.634a.75.75 0 0 1-.298-.287a.09.09 0 0 1-.023-.082c.029-.053.037-.105-.018-.149c-.053-.04-.114-.054-.174-.079c-.029-.068-.063-.137-.092-.202c-.035-.1.031-.126.104-.144c.099-.002.199.02.301 0c.153-.008.234.1.328.198c.053.059.108.118.138.196c.022.118.162.204.117.353a.18.18 0 0 1-.181.031c-.168-.083-.082.126-.162.14z");
}

.lhaa14yvz {
  fill: var(--svg-color--red, red);
  d: path("m18 19l14-.667V18H18zM.228 18.409L14 19v-1H.305q-.042.202-.077.409M9.242 17l-6.976-3.448a10 10 0 0 0-.759 1.146L6.203 17zm-6.97-3.456l-.005.008L9.242 17zM22.83 17L32 12.318v-1.551L19.792 17zm0 7L32 28.682V27.17L25.869 24z");
}

.lhe7yvbig {
  fill: var(--svg-color--33373d, #33373d);
  d: path("M47.51 38.804c.145.058.531-.133.3.301c.048-.174-.011-.235-.194-.236c-.215-.005-.436.023-.643-.059z");
}

.lhoxjt50x {
  fill: var(--svg-color--d3d6dc, #d3d6dc);
  d: path("M48.44 26.24v-.082c.427-.14.844.017 1.265.029c-.001.133-.108.133-.192.155c-.107.008-.217.007-.32.039c-.256-.014-.535.086-.753-.141");
}

.litlv8bse {
  fill: var(--svg-color--404040, #404040);
  d: path("M50.37 26.474c-.123.001-.244 0-.347-.081q.212-.13.347.081");
}

.lkcu7bcaa {
  fill: var(--svg-color--314357, #314357);
  d: path("M50.14 39.755v.031c-.145.028-.207-.094-.297-.161c.094-.199.244-.045.366-.054q-.032.092-.068.184");
}

.lkqw--zvs {
  fill: var(--svg-color--2b3990, #2b3990);
  d: path("M0 24v2.432L4.686 24zm54-14H32v4.714L27.386 17H32v7h-4.614L32 26.395V31h-.192L19 24.651V31h-6v-6.349L.234 31H0v12c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11V21c0-6.075-3.373-11-10-11M1.212 15.28A11 11 0 0 0 .554 17h4.132z");
}

.lkx3wjp5p {
  fill: var(--svg-color--f7f7d4, #f7f7d4);
  d: path("M44.979 26.354c.11.128.271.058.404.097c-.038.16-.173.163-.293.171c-.508.038-1.01.116-1.512.173c-.136.015-.273.041-.383-.077c-.032-.085.021-.118.09-.137q.066-.04.132-.077c.142.052.27-.037.406-.036c.146.017.281-.05.429-.034q.092-.036.189-.068l.034-.003c.121.091.244-.008.366.001z");
}

.ll2k9xt-q {
  fill: var(--svg-color--050200, #050200);
  d: path("M53.49 40.866q.028.107.057.209a.9.9 0 0 0-.142.396c-.163.068-.337.045-.505.053c-.113-.116-.136-.237-.031-.37c.052-.351.13-.384.621-.288");
}

.llz5dkaqg {
  fill: var(--svg-color--363b44, #363b44);
  d: path("M47.608 47.41q-.118.05-.232.102c-.143.024-.254-.062-.379-.106q-.007-.032-.011-.067c.21.052.421.057.631.005q-.002.035-.009.066");
}

.lny97finu {
  fill: var(--svg-color--4b6785, #4b6785);
  d: path("m52.7 38.696l-.095-.003c-.17.011-.211-.073-.172-.227q.05-.047.101-.09a.5.5 0 0 1 .166.32");
}

.lp6iic5od {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("M47.761 35.968q-.053.109-.108.215c-.093.032-.175.087-.271.102c-.151.001-.286.078-.426.114a.55.55 0 0 1-.328-.042c-.049-.023-.093-.058-.136-.092l-.37-.018c-.104-.167-.205-.117-.306-.001c-.11-.034-.294.087-.308-.146l.155-.201c.701-.005 1.4-.05 2.098.069");
}

.lp6y-ybnv {
  fill: var(--svg-color--384e65, #384e65);
  d: path("M47.882 40.01q.072-.186.141-.375h.081a.13.13 0 0 1 .104.071q.013.049-.024.081q-.039.038-.073.075a.2.2 0 0 1 .054.06l.025.021c.027.035.017.056-.021.066a.3.3 0 0 0-.069.01a4 4 0 0 1-.218-.009");
}

.lpkffj4kf {
  fill: var(--svg-color--1c2732, #1c2732);
  d: path("m48.16 39.917l-.054-.06a.12.12 0 0 1 .067.007a.1.1 0 0 1-.013.053");
}

.lst-bubtu {
  fill: var(--svg-color--1d3c2e, #1d3c2e);
  d: path("m52.42 43.773l.071-.041c.053-.082.068-.2.208-.169c.008.156-.105.236-.207.325l-.031-.003l-.034.002z");
}

.lt-c84bjx {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M54.725 27.4q.036-.033.07-.067l.44.177q.064.067.012.145a.2.2 0 0 1-.102.033c-.176-.04-.359-.076-.42-.288");
}

.lur5xe2uz {
  fill: var(--svg-color--09ab00, #09ab00);
  d: path("m44.747 39.24l-.018.073c-.011.056-.039.094-.098.101a.2.2 0 0 1-.094-.043a2.2 2.2 0 0 1-.417-.803a.15.15 0 0 1 .026-.099c.031-.02.063-.014.092.009c.126.077.218.187.299.306a.7.7 0 0 0 .21.456");
}

.lv1k6i69z {
  fill: var(--svg-color--464a51, #464a51);
  d: path("m49.26 46.544l.073.133c-.117-.077-.204.043-.308.057c.004-.157.105-.19.235-.19");
}

.lvgginbhq {
  fill: var(--svg-color--e2e2e3, #e2e2e3);
  d: path("m39.606 34.794l-.027-.003l-.025.016l-.011-.181c.005-.228.014-.451.021-.677c.085-.106-.078-.298.126-.366l-.008.457c-.131.24-.011.506-.076.754");
}

.lw39303oi {
  fill: var(--svg-color--14af86, #14af86);
  d: path("M48.15 45.23c.172-.067.344-.214.497.051z");
}

.m-c7wvbwh {
  fill: var(--svg-color--070e19, #070e19);
  d: path("M45.02 42.878c.275.092.553.182.915.3c-.431.067-.729.017-.94-.289z");
}

.m2n_zubze {
  fill: var(--svg-color--8ec3fd, #8ec3fd);
  d: path("M50.38 35.09s.013.038.011.06c.119.085.245.065.373.018l.146.001c.161.279.104.577.08.876c-.035.136-.137.234-.226.339c-.049.057-.097.114-.164.147a.17.17 0 0 1-.104-.009c-.266-.244-.385-.572-.527-.888c-.054-.181.143-.289.136-.457c.009-.051.027-.1.079-.124c.072-.017.142-.024.196.037");
}

.m4mrltelu {
  fill: var(--svg-color--3d3d3d, #3d3d3d);
  d: path("M44.25 26.433c-.142.104-.297.065-.452.064q-.04-.02-.027-.043q.013-.02.025-.021c.152.024.302-.159.454 0");
}

.m7fs0-btl {
  fill: var(--svg-color--435c77, #435c77);
  d: path("M45.34 37.938c-.004.189.066.386-.069.559c-.091-.206.047-.398.033-.601q.051-.005.036.042");
}

.m8ewlb42g {
  fill: var(--svg-color--376bbb, #376bbb);
  d: path("M44.878 41.568v.062c-.063.238-.297.23-.468.317c.215.08.61-.204.608.304c-.246.067-.559.055-.536.443c-.221-.327-.531-.561-.828-.81a.24.24 0 0 1-.038-.105c.002-.242.211-.266.365-.343c.314-.042.619-.054.897.132");
}

.m9wuh0bpx {
  fill: var(--svg-color--0e0d0b, #0e0d0b);
  d: path("M39.619 36.946h.033c.153.132.076.301.096.451q-.03-.003-.062-.002l-.028-.148c.039-.106-.098-.192-.039-.301");
}

.mac0h934j {
  fill: var(--svg-color--3c526a, #3c526a);
  d: path("M49.823 39.659a.9.9 0 0 1-.141-.46c.022-.211.194-.168.328-.194a.2.2 0 0 1 .095.035c.116.104.241.205.235.385a.27.27 0 0 1-.104.169c-.115.067-.249.016-.367.059z");
}

.mcd2e68eu {
  fill: var(--svg-color--5b6631, #5b6631);
  d: path("M46.38 41.14c.169-.313.043-.648.078-.973c.021-.183.014-.366.02-.553q.072-.019.108.043c.062.104.058.213.057.324c.003.273-.006.543.003.814c.004.135-.001.275-.115.376l-.01.035q-.073-.037-.141-.066");
}

.mdop79cpa {
  fill: var(--svg-color--924500, #924500);
  d: path("M51.22 41.762a.2.2 0 0 1 .068-.013c.094.111.227.196.242.362c-.166-.059-.25-.195-.31-.349");
}

.mdpdt95nr {
  fill: var(--svg-color--2e4052, #2e4052);
  d: path("M48.18 39.694s.008-.036.008-.057q.038.034.072.069q0 .031-.004.063a.2.2 0 0 1-.071.013z");
}

.mdqsik68j {
  fill: var(--svg-color--f8f8d6, #f8f8d6);
  d: path("M54.98 27.727q.09-.043.18-.082l.074-.001l.005.082c.095.121.068.256.05.392c-.049.402-.014.81-.029 1.214l-.004.465c-.01.151.019.307-.024.455l-.008.957c-.005.358-.088.716.038 1.068q0 .113-.004.227c-.053.229-.01.461-.03.688c-.007.082-.006.19-.145.111c-.114-.164-.088-.357-.086-.542c.003-.92.024-1.842.016-2.763c-.01-.757-.097-1.513-.033-2.271");
}

.mdwcnub4q {
  fill: var(--svg-color--258ca8, #258ca8);
  d: path("m50.771 44.07l.197.126c-.156.036-.263.035-.356-.043c.059-.011.125-.018.159-.083");
}

.meyoc7kfh {
  fill: var(--svg-color--6c7884, #6c7884);
  d: path("m46.12 36.25l-.312-.003l.006.002c.085-.207.152-.216.315-.053z");
}

.mfmh3qbou {
  fill: var(--svg-color--251b11, #251b11);
  d: path("M40.627 41.2c-.004-.043-.003-.092-.007-.133c.143.117.267.244.17.455q-.083-.158-.163-.322");
}

.mg6j8tbju {
  fill: var(--svg-color--e4e5e6, #e4e5e6);
  d: path("M55.39 35.794c-.076-.069-.058-.16-.071-.242c-.164-.221-.063-.473-.091-.71l.002-.267c.027-.242-.064-.504.099-.729q.078-.03.118.039c-.005.352.035.704-.035 1.056c.042.287-.001.568-.022.853");
}

.mg90flb8b {
  fill: var(--svg-color--4f6073, #4f6073);
  d: path("M50.45 37.09c-.096.041-.225-.034-.293.092c-.097-.021-.127-.097-.154-.177q.226.016.452.029l.021.029z");
}

.mh4-r927n {
  fill: var(--svg-color--276a9d, #276a9d);
  d: path("m50.41 42.8l-.138-.074c-.08-.028-.211-.031-.075-.161c.153-.026.319-.122.435.072c-.113.001-.215.012-.222.163");
}

.mhloddcuz {
  fill: var(--svg-color--af5300, #af5300);
  d: path("m50.13 40.708l-.086-.09a.2.2 0 0 0 .023-.064c.182-.124.394-.003.58-.083c.065.031.081.084.061.154c-.079.087.061.265-.124.316c-.105-.17-.286-.184-.454-.233");
}

.mpyz50bjj {
  fill: var(--svg-color--009c00, #009c00);
  d: path("M48.21 42.07c-.592-.262-1.261.087-1.859-.309c.636.153 1.283-.04 1.859.309");
}

.mqvx_82jw {
  fill: var(--svg-color--dbdd05, #dbdd05);
  d: path("M49.09 38.02a1 1 0 0 1 .004.102q-.075.008-.149.02l-.014-.594c.049-.121-.062-.278.094-.372c.102.274-.029.569.065.844");
}

.mqw4wcbrn {
  fill: var(--svg-color--5a7ca0, #5a7ca0);
  d: path("M51.49 39.34q-.044.006-.089.008a.5.5 0 0 1-.069-.293a.27.27 0 0 1 .173-.175c.078.001.133.041.176.103c.086.198.116.367-.191.357");
}

.msb8ltbdd {
  fill: var(--svg-color--415973, #415973);
  d: path("M50.712 40.24q-.128-.036-.254-.068c-.004-.049.032-.102-.012-.146a.2.2 0 0 1-.055-.122a.34.34 0 0 1 .107-.222c.08-.053.163-.086.259-.047c.143.105.15.254.128.409z");
}

.msht68bej {
  fill: var(--svg-color--d3d8dd, #d3d8dd);
  d: path("M52.1 37.04s-.004.039-.004.061c-.142.088-.346.019-.454.184c-.109.046-.223.049-.337.061a.34.34 0 0 1-.17-.03a.4.4 0 0 1-.146-.104c-.085-.128-.236-.235-.153-.423c.345-.127.697-.026 1.044-.048a.4.4 0 0 1 .12.027c.106.064.09.174.1.272");
}

.mt9ktcd2v {
  fill: var(--svg-color--fafa01, #fafa01);
  d: path("m46.38 41.14l-.072-.022c-.21-.574-.09-1.161-.069-1.744c.002-.102.086-.176.211-.148c.144.105.112.26.121.405c-.003.382.001.766-.013 1.148c-.004.141.019.311-.178.361");
}

.mvdv_fbve {
  fill: var(--svg-color--d7dbe6, #d7dbe6);
  d: path("M53.4 42.665c-.007.307-.195.521-.382.739c-.083-.026-.113-.085-.115-.166c.113-.236.17-.525.499-.569z");
}

.mxtpm-cla {
  fill: var(--svg-color--555514, #555514);
  d: path("M46 29.36c-.079.07.279.229-.049.244c-.003-.083-.038-.176.049-.244");
}

.mz79d-brw {
  fill: var(--svg-color--01d462, #01d462);
  d: path("M45.02 42.25c-.072-.217-.216-.299-.424-.196c-.2.1-.299-.041-.499-.157c.324-.058.573-.11.782-.268c.286.259.73.171 1.017.48c-.167.113-.312.199-.533.135c-.139-.041-.054.081-.044.141q.043.015.03.034q-.014.018-.026.019q-.154-.094-.303-.188");
}

.n2v27wawo {
  fill: var(--svg-color--06b400, #06b400);
  d: path("M42.728 37.32c.02.27.147.515.128.801c-.01.166.063.371.266.456c.056.026.124.09.081.146c-.235.291.047.561.028.84a9 9 0 0 0-.268-.051c-.153-.37-.165-.771-.22-1.16c-.047-.337-.344-.615-.223-.988q.025-.059.082-.033q.064-.008.126-.011");
}

.n3bql2sxf {
  fill: var(--svg-color--e2e201, #e2e201);
  d: path("M51.13 36.622q-.082.015-.163.033c-.132-.171-.115-.345-.005-.518c.065-.276-.084-.576.1-.838l.002.012c.063.171.012.35.029.521c.015.242-.045.483.03.717a.3.3 0 0 1 .007.073");
}

.n3i_9obxu {
  fill: var(--svg-color--d9dde5, #d9dde5);
  d: path("m55.39 35.794l-.16 1.57c-.082.029-.127-.014-.166-.075c-.019-.117-.005-.233-.029-.349c.004-.139.034-.275.058-.413a1.1 1.1 0 0 0 .051-.372q-.004-.139.005-.279c.005-.098.008-.189.059-.276a.11.11 0 0 1 .097-.052c.106.055.029.173.085.246");
}

.n4us_mb1r {
  fill: var(--svg-color--f4f40a, #f4f40a);
  d: path("m48.686 30.05l-.346-.514c.118.035.157-.207.299-.084q.257.201.519.396c.005.073-.016.116-.098.079c-.185-.145-.287-.031-.374.123");
}

.n6u2-ubxt {
  fill: var(--svg-color--dee0e6, #dee0e6);
  d: path("m45.35 46.574l-.064.079c-.169-.043-.305-.149-.441-.249c-.028-.075.008-.117.075-.142q.215.154.43.312");
}

.ncdtz9b2r {
  fill: var(--svg-color--8abef6, #8abef6);
  d: path("M49.572 35.01c-.16.134-.346.046-.521.061c-.105-.128-.13-.252.015-.368q.257.153.506.307");
}

.nl9rp3byb {
  fill: var(--svg-color--8dc3fc, #8dc3fc);
  d: path("M49.48 36.652c-.103.137-.244.046-.367.058c-.097-.14-.155-.272.068-.349l.05.063c.135.022.176.141.244.228z");
}

.nmfqzcuqb {
  fill: var(--svg-color--bb7332, #bb7332);
  d: path("M47.3 28.349a.3.3 0 0 0-.175-.188q.062-.118.128-.236l.104.188c-.001.078.052.177-.057.236");
}

.nms4znbav {
  fill: var(--svg-color--566779, #566779);
  d: path("M48.651 38.673q.034-.043.072-.085c.107-.107.227-.096.35-.029q.055.051.013.11c-.119-.015-.134.065-.135.155c.024.051.037.102-.026.136c-.075-.111-.006-.36-.274-.287");
}

.nnj_o-b7j {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M45.38 35.936a.36.36 0 0 1 .288-.037c.037.113-.022.189-.104.254c-.057.036-.117.062-.186.039z");
}

.nnttifb6y {
  fill: var(--svg-color--4a6077, #4a6077);
  d: path("M45.41 40.876q.004-.073.01-.144c.063-.083.103-.198.24-.189a.32.32 0 0 1 .243.219c.01.062-.022.114-.029.169c-.166.084-.308-.058-.464-.055");
}

.no72ws6sj {
  fill: var(--svg-color--122341, #122341);
  d: path("M49.36 42.778v-.077q.082-.066.162-.134c.125.211-.092.158-.162.211");
}

.nobp53biz {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M45.524 35.05c-.182-.031-.13-.179-.148-.289c.281-.115.574-.12.866-.117h.137c.419.025.846-.037 1.263.053c.125.242.046.446-.207.508c-.118.025-.242.007-.361-.008c-.104-.018-.208-.046-.317-.039a1 1 0 0 0-.239.027a.6.6 0 0 1-.245.009a.46.46 0 0 1-.317-.115c-.143-.049-.294.061-.432-.029");
}

.nppq9zijl {
  fill: var(--svg-color--e0e3eb, #e0e3eb);
  d: path("m55.41 34.94l.004-1.09c-.068-.115-.123-.23.063-.294c.004.465.04.926-.067 1.384");
}

.nqu-7em5c {
  fill: var(--svg-color--c5cbd8, #c5cbd8);
  d: path("M39.731 38.452c-.094-.217-.101-.454-.127-.686c.068-.065-.029-.202.106-.237c.12.205.07.447.138.661c-.035.089-.016.204-.117.262");
}

.nr23_1bro {
  fill: var(--svg-color--506f8e, #506f8e);
  d: path("M51.4 39.965c.052-.101.082-.203.031-.319c.061-.055.126-.05.198-.02a.28.28 0 0 1 .11.177a.15.15 0 0 1-.035.095c-.055.224-.185.118-.304.067");
}

.nvsy0ez-x {
  fill: var(--svg-color--dee0e5, #dee0e5);
  d: path("M42.23 43.89v.021l.021.014c.106.098.232.182.28.333l-.014.091c-.24-.042-.314-.251-.411-.428q.001-.073.071-.091q.04.016.053.06");
}

.nxzqcmpcc {
  fill: var(--svg-color--fafa00, #fafa00);
  d: path("M46.23 38.497q.037-.075.077-.151l.019-.009a.1.1 0 0 1 .105.008a.31.31 0 0 1 .033.365l-.225-.003c-.066-.067-.045-.137-.009-.21");
}

.ny6tnbnnp {
  fill: var(--svg-color--red, red);
  d: path("M0 28.73v.023L9.242 24z");
}

.o_aembbgh {
  fill: var(--svg-color--415467, #415467);
  d: path("M48.28 36.571c.038.116.171.064.239.133c-.088.102-.217.009-.313.069q-.149.012-.299.021c-.029.032-.059.031-.091.006c-.056-.075-.053-.136.046-.157c.137-.031.278-.048.418-.072");
}

.o_iuexbxy {
  fill: var(--svg-color--455f7b, #455f7b);
  d: path("m47.882 40.01l-.082.008c-.102-.196.05-.318.13-.462l.093.079c.045.16-.027.275-.141.375");
}

.o-vsmrbtr {
  fill: var(--svg-color--323007, #323007);
  d: path("M47.14 27.643c-.091-.013-.225.042-.21-.134l.07-.137c.154.033.169.143.14.271");
}

.o2nbulbxh {
  fill: var(--svg-color--83b5ea, #83b5ea);
  d: path("M46.5 35.782c.005-.121.011-.238.018-.36l.571.313c-.185.142-.392.054-.589.047");
}

.o43omzb2m {
  fill: var(--svg-color--455f7b, #455f7b);
  d: path("m51.53 35.467l.029.004c.125.069.082.2.111.303c-.147-.057-.073-.214-.14-.307");
}

.o6nlpebjn {
  fill: var(--svg-color--1b1b1b, #1b1b1b);
  d: path("M54.931 38.11c-.021-.126-.036-.251.07-.351c-.018.118.057.254-.07.351");
}

.o79c40u0x {
  fill: var(--svg-color--fefe00, #fefe00);
  d: path("M46.35 35.79q.006-.287.01-.58c.124.186.048.39.056.583l-.034.003z");
}

.o7e_q6b0e {
  fill: var(--svg-color--dadfe9, #dadfe9);
  d: path("M54.612 39.829c.139.276-.076.485-.146.721c-.224-.094-.1-.258-.079-.4a.73.73 0 0 1 .225-.321");
}

.o7xcgkbin {
  fill: var(--svg-color--687d95, #687d95);
  d: path("m45.978 35.05l-.006.061c-.148-.016-.317.087-.447-.063c.15.018.301-.078.453.002");
}

.o88i-f5sy {
  fill: var(--svg-color--36392a, #36392a);
  d: path("M48.961 35.598q.19-.001.38.001c-.051.084-.199.029-.228.149l-.035-.011l-.036.004q-.04-.074-.081-.143");
}

.o9dyx4b7c {
  fill: var(--svg-color--404a55, #404a55);
  d: path("m45.755 34.593l.518.002q.015.023.033.045c.01.038-.005.072-.028.103l-.901.021c.061-.203.277-.057.378-.171");
}

.obpro_bld {
  fill: var(--svg-color--4f6050, #4f6050);
  d: path("M46.47 38.71c.003-.125.023-.251-.064-.361c-.053-.096.01-.128.083-.154c.025 0 .051-.004.076-.004l.031-.016l.022.025q-.001.075.004.146c-.142.102-.059.243-.069.369q-.043 0-.083-.005");
}

.ocm63yqka {
  fill: var(--svg-color--4c4c4c, #4c4c4c);
  d: path("m54.786 39.16l.068.055a.1.1 0 0 1-.004.07c-.116.112-.056.322-.231.4c-.132-.196.012-.354.075-.524q.044-.067.092-.001");
}

.of5ff8bbz {
  fill: var(--svg-color--06cc6b, #06cc6b);
  d: path("M51.54 42.671c.391-.338.853-.024 1.268-.142c-.387.311-.804.413-1.268.142");
}

.ogwta-bdt {
  fill: var(--svg-color--813d00, #813d00);
  d: path("M53.02 41.631q.09-.005.178-.003c-.097.07-.042.246-.187.291q.003-.145.009-.288");
}

.okcvfjacn {
  fill: var(--svg-color--32404b, #32404b);
  d: path("M51.48 38.914c.009.113-.061.142-.153.146c-.067-.028-.048-.146-.146-.145l-.029-.04a.14.14 0 0 1 .04-.089a.32.32 0 0 1 .239-.072a.16.16 0 0 1 .079.059c.019.054.015.101-.03.141");
}

.ol_90rbwk {
  fill: var(--svg-color--9f4b00, #9f4b00);
  d: path("m46.24 30.24l-.02-.206c.089.048.213.082.181.21c-.012.055-.106.016-.161-.004");
}

.olv6cl2co {
  fill: var(--svg-color--3370c2, #3370c2);
  d: path("M46.807 43.497q-.005.082-.007.164c-.13-.005-.278.078-.371-.083c.109-.087.25-.051.378-.081");
}

.orf-a94bz {
  fill: var(--svg-color--88bbf2, #88bbf2);
  d: path("M50.47 34.64c.099-.123.294-.087.383-.227c.187.061.105.182.063.293c-.151-.009-.313.066-.446-.066");
}

.orumdob6z {
  fill: var(--svg-color--898d13, #898d13);
  d: path("m51.03 38.17l-.063-.039q-.05-.014-.027-.06l.035-.458c.096.179.053.37.055.557");
}

.os0n5ab6f {
  fill: var(--svg-color--7f3e00, #7f3e00);
  d: path("m46.39 29.14l-.136-.146c-.016-.065-.001-.115.059-.153l.15.077c.001.08.038.179-.073.222");
}

.ot94h8hda {
  fill: var(--svg-color--e1e1e1, #e1e1e1);
  d: path("M46.5 27.574a5 5 0 0 1-.242-.013l-.173-.08a.4.4 0 0 1 .033-.055c.141.018.287.016.382.148");
}

.otejvr5gk {
  fill: var(--svg-color--414141, #414141);
  d: path("M44.842 26.362c-.121.069-.245.133-.366-.001c.122.015.245-.124.366.001");
}

.oto5krb8b {
  fill: var(--svg-color--758ba2, #758ba2);
  d: path("M47.819 36.801q.045-.006.091-.006c-.026.134.104.187.146.285q.033.02.024.04l-.013.025q-.257-.084-.248-.344");
}

.ovn2mo-io {
  fill: var(--svg-color--c6cad3, #c6cad3);
  d: path("M40.04 39.19q.007.043.016.082c.057.13.139.252.06.4c-.275-.128-.25-.329-.147-.556l-.011.002q.106-.038.082.072");
}

.ovrkm3b_m {
  fill: var(--svg-color--8bbef5, #8bbef5);
  d: path("M45.28 38.928c.048.069.091.137.137.205c.075.146.34-.022.362.215c-.022.25-.21.368-.393.491c-.096.043-.192.069-.288.004a.3.3 0 0 1-.07-.168a.7.7 0 0 1 .021-.244c.057-.151.055-.323.152-.461q.043-.019.079-.042");
}

.ow_y-lbbe {
  fill: var(--svg-color--f7f7f8, #f7f7f8);
  d: path("M50.675 36.798q.066.034.133.072c.136.061.181.188.245.307a.23.23 0 0 1-.121.102c-.084.029-.168.05-.257.012c-.1-.074-.157-.219-.321-.171c-.138.008-.278.021-.383-.098a.21.21 0 0 1 0-.191c.223-.217.463-.141.704-.033");
}

.p_pf-6b0s {
  fill: var(--svg-color--7eaee2, #7eaee2);
  d: path("M46.25 37.29c-.172-.014-.355.062-.512-.068l.449-.297c.248.084.167.223.063.365");
}

.p-qz66b8n {
  fill: var(--svg-color--222931, #222931);
  d: path("M47.02 34.606c.217.076.469-.003.667.157l-1.336-.024c.026-.16.17-.121.271-.158c.133-.016.265.041.398.025");
}

.p3jvqmztl {
  fill: var(--svg-color--2a2a2a, #2a2a2a);
  d: path("M54.682 39.09c.052-.098-.009-.259.163-.285q-.028.177-.059.356l-.092.001z");
}

.p46q6o53f {
  fill: var(--svg-color--f6f5f3, #f6f5f3);
  d: path("M48.705 30.57c-.342-.179-.398.054-.455.306c-.022.102-.085.193-.132.287c-.215-.066-.175-.43-.471-.402a.7.7 0 0 1-.445-.126a.6.6 0 0 1-.114-.11c-.061-.105-.142-.201-.141-.333c.117-.193.242-.002.364-.01l.102.03c.125.049.257.027.386.033l.557.001c.224 0 .444.003.646.122c.019.085.105.043.148.082c-.098.223-.314.015-.445.12");
}

.p6r5mxbuc {
  fill: var(--svg-color--06cb6c, #06cb6c);
  d: path("M43.33 44.27c.648-.294.648-.294 1.02-.07c-.331.275-.688-.015-1.02.07");
}

.pcfr6ac-t {
  fill: var(--svg-color--0fb97d, #0fb97d);
  d: path("M45.606 45.37c-.105.003-.205.002-.308.005q.07-.068.144-.137c.095-.008.15.039.164.132");
}

.pefyvsbtr {
  fill: var(--svg-color--059f00, #059f00);
  d: path("M44 39.886q0-.028.006-.06c.053-.08.126-.121.228-.096c.185.172.354.37.58.499c.064.096.203.189.009.295c-.199-.136-.442-.201-.618-.375c-.061-.092-.176-.144-.205-.263");
}

.pfw36cbti {
  fill: var(--svg-color--f2f2de, #f2f2de);
  d: path("M49.607 26.488c.113-.028.246.017.337-.095c.025-.002.056-.001.081-.001q.179.005.347.081q.04-.034.086-.068q.069.044.141.086c-.029.195-.197.142-.314.177c-.234-.027-.509.096-.678-.18");
}

.pjywr2k1m {
  fill: var(--svg-color--4c4c4c, #4c4c4c);
  d: path("M55.31 31.17c-.007-.151-.055-.306.04-.449l-.004.443z");
}

.pk6od3eaw {
  fill: var(--svg-color--0c192f, #0c192f);
  d: path("m44.35 45.01l.659.005c-.212.144-.422.183-.659-.005");
}

.plnejbbww {
  fill: var(--svg-color--c15b00, #c15b00);
  d: path("M46.23 41.474a.73.73 0 0 1-.425-.115c.16-.045.299-.035.426.051q.04.023.026.043q-.013.02-.027.021");
}

.pmf1tzclr {
  fill: var(--svg-color--4f604c, #4f604c);
  d: path("m46.34 36.33l-.021.451c-.127-.139-.027-.305-.065-.456q.044-.025.086.005");
}

.pnck8ac3i {
  fill: var(--svg-color--3a4958, #3a4958);
  d: path("M48.15 35.08c.171.151.421-.027.591.135c-.253.026-.52-.099-.76.064c-.062-.139-.062-.139.169-.199");
}

.pnn_uzbfr {
  fill: var(--svg-color--535c3d, #535c3d);
  d: path("M48.932 37.543h-.055c-.005-.15.027-.305-.068-.441l.296-.01a.11.11 0 0 1 .021.088a.3.3 0 0 1-.042.086c-.058.088-.032.224-.152.278");
}

.pnysh3b4k {
  fill: var(--svg-color--fafafb, #fafafb);
  d: path("m42.15 26.707l-.021-.068c.184-.058.356-.177.559-.065c-.13.234-.315.26-.538.133");
}

.pp4mhn5sn {
  fill: var(--svg-color--0cbf77, #0cbf77);
  d: path("m48.61 42.933l-.003.073c-.204.291-.401.01-.605.015c.157-.192.368.004.531-.101z");
}

.pt4uouhwk {
  fill: var(--svg-color--b1b105, #b1b105);
  d: path("M48.836 33.524q.076.002.149.008c.13.148.109.311.028.476a.11.11 0 0 1-.112.032c-.154-.135-.034-.309-.061-.463l-.023-.018a.1.1 0 0 0 .019-.035");
}

.pucaklbfi {
  fill: var(--svg-color--313117, #313117);
  d: path("M47.657 30.804a.08.08 0 0 1-.024-.068c.367-.089.354.253.485.428q-.057.009-.114.015c-.141-.102-.146-.329-.347-.375");
}

.pud5fo6ne {
  fill: var(--svg-color--fdfd00, #fdfd00);
  d: path("M46.32 36.842a.06.06 0 0 0 .001-.06a.85.85 0 0 1 .008-.46q.073-.03.122.03c.055.307.194.626-.11.889c-.079-.13-.051-.265-.021-.399");
}

.pwox2odfe {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M49.06 33.647q-.004-.066-.01-.125l1.869.014l-.003.049c-.135.136-.311.125-.482.125c-.416.003-.832-.008-1.25-.02a.2.2 0 0 1-.124-.043");
}

.q_kbhvvlm {
  fill: var(--svg-color--556577, #556577);
  d: path("M48.06 37.15a.3.3 0 0 0-.003-.065q.188.007.378.012c-.112.121-.246.064-.375.053");
}

.q-iwemqbr {
  fill: var(--svg-color--546860, #546860);
  d: path("m46.35 33.659l.012.031q-.008.161-.019.322q-.15-.177.007-.353");
}

.q123ey2_w {
  fill: var(--svg-color--fdfdf6, #fdfdf6);
  d: path("m52.773 27.01l-.006-.07c.125.02.289-.052.334.148z");
}

.q1cp3mbtu {
  fill: var(--svg-color--0e0700, #0e0700);
  d: path("M52.37 40.722c-.106-.445-.056-.557.271-.512c.356.049.126.325.175.493c-.146.136-.295.129-.446.019");
}

.q1kchwbyk {
  fill: var(--svg-color--82b3e7, #82b3e7);
  d: path("m46.53 41.17l.013-1.241q.047-.04.096-.001c.133.186.111.416.182.623c.03.082.059.166.07.254c-.01.127.053.273-.072.38z");
}

.q2c2-tbog {
  fill: var(--svg-color--01d561, #01d561);
  d: path("M47.925 44.34c.006.13.037.268-.178.234c-.106-.018-.224-.015-.199.153a.46.46 0 0 1-.285.203c-.048.013-.094.016-.141.029c.047.014.102.009.131.059c-.035.187-.193.127-.309.153c-.281.115-.564.21-.865.068c.113-.131.139-.24-.073-.293c-.095-.027-.188-.068-.284-.094c-.139-.034-.217-.12-.211-.265c.007-.198.168-.073.254-.11c.051-.021.168.014.144-.063c-.091-.272.13-.163.196-.146c.485.125.958.116 1.43-.057c.142-.054.271-.016.389.065c.027.014.035.025.027.041q-.014.024-.026.023");
}

.q2qn726ni {
  fill: var(--svg-color--4b2400, #4b2400);
  d: path("M52.693 42.09c-.044-.085-.062-.195.035-.211c.109-.018.068.088.045.148c-.01.026-.049.041-.08.063");
}

.q7xkxsb_f {
  fill: var(--svg-color--5d3802, #5d3802);
  d: path("M45.11 41.16a.3.3 0 0 1 .209.144c-.146.089-.297.173-.445.261c-.304.063-.597-.117-.902-.038c-.064-.021-.158.004-.161-.105c.056-.14.186-.258.303-.216c.346.117.666.004.996-.046");
}

.q9hmn4l4o {
  fill: var(--svg-color--c2b926, #c2b926);
  d: path("M47.22 30.576c.152.018.238.207.413.159q.085.012.024.068l.007-.008c-.31.035-.616.059-.903-.098a.07.07 0 0 0-.004-.053c-.033-.06.003-.09.047-.115a.4.4 0 0 1 .097-.012c.107.015.208.062.319.059");
}

.q9hn7qbct {
  fill: var(--svg-color--d2721c, #d2721c);
  d: path("M47.3 28.407c-.145-.016-.312-.002-.284-.23q.055-.01.114-.017c.134-.008.207.04.175.188q-.001.032-.005.059");
}

.qag1q1bzl {
  fill: var(--svg-color--5a7ca0, #5a7ca0);
  d: path("M49.48 36.652c-.079-.077-.161-.149-.244-.228c.193-.044.222.093.244.228");
}

.qaxyvbbjo {
  fill: var(--svg-color--7dacdf, #7dacdf);
  d: path("M47.51 41.12c-.016-.072.003-.131.071-.168c.063.018.16.017.134.113c-.03.102-.128.063-.205.055");
}

.qc18vkbkv {
  fill: var(--svg-color--2e3f52, #2e3f52);
  d: path("M50.889 39.06q.034.07.068.145q-.01.136-.143.147c-.103-.049-.202-.099-.306-.147c.006-.063.048-.093.104-.112c.037-.007.075-.01.111-.021c.037-.021.068-.044.11-.054q.046-.002.056.042");
}

.qegvcpbel {
  fill: var(--svg-color--666, #666);
  d: path("m47.836 26.17l-.146.06c-.197-.03-.408.06-.595-.065z");
}

.qel37ac_n {
  fill: var(--svg-color--4c5d4e, #4c5d4e);
  d: path("m46.34 34.08l.009.524q-.025.036-.066.017l-.015-.021c-.013-.148.072-.309-.064-.442c.012-.081.077-.074.136-.078");
}

.qeu0babxy {
  fill: var(--svg-color--c56000, #c56000);
  d: path("m43.36 39.535l.284-.244c.373-.033.322.288.416.495a.3.3 0 0 1-.006.111a.2.2 0 0 1-.061.097c-.239-.115-.528-.157-.633-.459");
}

.qhfkstb7k {
  fill: var(--svg-color--fafbfd, #fafbfd);
  d: path("M55.25 35.871c-.201-.029-.134-.192-.155-.311c-.192-.462-.161-.927-.012-1.395c.143-.071.138.043.135.12c-.007.172.029.34.036.51q.003.395-.006.797c-.001.095.001.184.002.279");
}

.qjza54bzo {
  fill: var(--svg-color--556576, #556576);
  d: path("M54.29 38.709c.014-.157.168-.354-.105-.446c.102-.122.203-.117.21.044c.01.185.079.382-.063.555l-.025-.008a.15.15 0 0 1-.017-.145");
}

.qlvhokbjh {
  fill: var(--svg-color--8399b1, #8399b1);
  d: path("m51.35 37.485l-.078-.084q-.061-.06-.006-.126l.389-.004l.004.029a3 3 0 0 1-.309.185");
}

.qnets5b4d {
  fill: var(--svg-color--4189dd, #4189dd);
  d: path("M32 12.344v-.026L22.83 17z");
}

.qnswj1beb {
  fill: var(--svg-color--f9f900, #f9f900);
  d: path("m51.07 34.703l-.036.009l-.037-.005c-.12-.112-.104-.26-.104-.403a.46.46 0 0 1 .061-.236q.044-.054.106-.025l.022.297c.069.122.092.246-.012.363");
}

.qnto7ebbc {
  fill: var(--svg-color--241f1a, #241f1a);
  d: path("M41.42 42.722q-.068-.075-.141-.151l-.036-.144c.168.034.189.156.177.295");
}

.qpdp3cblf {
  fill: var(--svg-color--47515a, #47515a);
  d: path("m46.539 36.772l-.027-.007a4 4 0 0 1-.024-.425l.005-.076q.072.002.143.01q.03.044.031.102c-.013.14.026.299-.128.396");
}

.qq93czbpf {
  fill: var(--svg-color--ececec, #ececec);
  d: path("M39.464 32.754c-.114-.417-.019-.839-.041-1.258q-.01-.204-.017-.412q.02-1.032.044-2.069q.072-.026.109.038c.096.212.039.438.054.654l-.007.98c-.002.168-.016.339.038.505a.6.6 0 0 1-.007.262c-.076.3-.024.603-.047.903c-.009.144.022.297-.126.397");
}

.qqfu3wbvn {
  fill: var(--svg-color--09c571, #09c571);
  d: path("M50.711 42.505c.183.001.368-.045.601.063c-.224.109-.41.095-.598.06q-.078-.06-.003-.123");
}

.qs8p65vtp {
  fill: var(--svg-color--0fb97d, #0fb97d);
  d: path("m44.698 45.36l-.098-.009c-.046-.3.18-.061.25-.125c-.051.044-.102.092-.152.134");
}

.qshzh-brm {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M40.12 27.22q.038.035.075.074c.006.171-.086.187-.221.134l-.075-.125c.064-.049.132-.092.221-.083");
}

.qvmzvbs3b {
  fill: var(--svg-color--87baf1, #87baf1);
  d: path("M50.594 36.5q.005.069.004.142l.009.023c-.125.058-.25.121-.299-.088q.11-.039.222-.082a.3.3 0 0 0 .064.005");
}

.r_0bgd-yp {
  fill: var(--svg-color--f1f1ec, #f1f1ec);
  d: path("M42.518 26.858c-.255.034-.498.195-.771.087c.115-.103.295-.031.401-.151c.097-.005.191-.006.285-.013z");
}

.r-emribxs {
  fill: var(--svg-color--586777, #586777);
  d: path("M53.19 39.667a.15.15 0 0 0 .006.074c-.129-.016-.281.063-.381-.083v.008c.123-.09.251-.118.375.001");
}

.r1b5-9byd {
  fill: var(--svg-color--01d562, #01d562);
  d: path("M48.752 43.905c-.201-.17-.403-.132-.602.003c-.022-.134-.146-.116-.23-.152c-.093-.018-.204-.008-.243-.157c.304.09.589.102.852-.086c.114-.084.223-.053.345.004c.342.155.731.223.96.587c.056.087.213.117.342.111l-.006-.005c.029.096-.386.041-.082.232c.05.047.05.1.016.153c.037.101.163.026.214.107c-.357.04-.338.02-.675-.243c-.087-.068-.281-.167-.461-.093c-.235.097-.486.064-.732.048c-.027-.013-.035-.025-.035-.025c.017-.023.028-.03.028-.03q.078-.008.141-.018c.067-.073.138-.135.246-.074l.317.003l-.235-.29c.064-.066.146-.026.236-.034c-.145-.023-.276.026-.396-.041");
}

.r2f52wbwm {
  fill: var(--svg-color--53635c, #53635c);
  d: path("M49.15 39.04s-.031 0-.048-.004l-.015-.369l.004-.06l.139-.006c-.095.134-.044.295-.08.439");
}

.r6803zb2z {
  fill: var(--svg-color--5d3100, #5d3100);
  d: path("M44.617 43.502c-.001.126.098.284-.058.362c-.124.064-.246.01-.346-.115c-.041-.055-.158-.146-.262-.053c-.41.379-.951.246-1.427.373c-.135.051-.212-.049-.304-.111a1 1 0 0 1-.052-.081c-.039-.12-.126-.208-.202-.308a.6.6 0 0 0-.186-.196a.5.5 0 0 1-.096-.103c-.043-.08-.09-.16-.152-.229a1.3 1.3 0 0 0-.15-.235a.3.3 0 0 1-.032-.089c-.024-.099-.051-.191-.143-.247c-.063-.077-.14-.142-.153-.247c-.028-.16-.072-.309-.202-.418a.7.7 0 0 1-.134-.265c.024-.154-.035-.284-.123-.406a.4.4 0 0 1-.043-.087a.74.74 0 0 0-.162-.386c-.05-.07-.081-.144-.065-.23l.008-.017a.4.4 0 0 1-.117-.227c.01-.187-.033-.365-.072-.544c-.062-.124-.103-.253-.154-.381a.5.5 0 0 1 .01-.109c-.156-.574-.235-1.163-.334-1.746c-.035-.151-.007-.309-.058-.457c-.034-.169-.056-.341-.013-.51c.024-.092.048-.152-.081-.086c-.037-.092-.006-.188-.032-.279c.022-.188.018-.379.1-.556a.4.4 0 0 1 .051-.101c.1-.13.178-.276.303-.376c.088-.069.169-.211.311-.083c.05.162-.044.289-.102.422c-.079.167-.127.328-.004.484q.045.028.071-.012c.064-.081.065-.262.197-.233c.14.033.114.2.115.323a.36.36 0 0 1-.028.18c-.273.499-.059.997-.001 1.494c.023.215.128.316.372.313c.438-.004.641.119.733.538c.16.712.462 1.385.548 2.116c-.018.114-.012.245-.163.288c-.034-.017-.08-.036-.082-.069c-.032-.688-.559-1.196-.688-1.848c-.016-.098-.004-.195-.02-.29c-.028-.173-.057-.347-.299-.331c-.257.015-.279.17-.233.371q.001.165-.001.326c.016.2-.052.4-.012.598c.27.623.738 1.145.892 1.822c-.002.219.043.409.23.559c.261.211.147.566.294.823c.238.545.722.687 1.283.713c.016-.114-.051-.263-.079-.409c-.029-.259-.223-.303-.427-.325a1.6 1.6 0 0 1-.39-.148c-.076-.047-.16-.065-.241-.103q-.211-.121-.055-.311c.125-.088.012-.359.269-.342c.108.346.269.607.704.596c.225-.006.324.186.353.399c.04.146.126.284.134.415c-.021-.105-.04-.237-.118-.353c-.011-.17-.061-.397.141-.445c.185-.042.284.173.349.325c.076.184.146.366.253.528c.06.091.101.209.247.163c.038-.023.077-.049.128-.034");
}

.r7-vqvbfx {
  fill: var(--svg-color--d8dbe3, #d8dbe3);
  d: path("m52.56 43.999l-.074-.11c-.009-.145.111-.233.165-.351c.031-.043.069-.072.124-.072c.077.031.05.113.083.167a1.1 1.1 0 0 1-.298.366");
}

.r7nz5g7wy {
  fill: var(--svg-color--dee1e6, #dee1e6);
  d: path("m49.705 46.3l.072.14c-.144.096-.272.215-.449.232l.004.004c-.035-.038-.108-.056-.073-.133c.135-.105.334-.094.446-.243");
}

.r805eeimt {
  fill: var(--svg-color--red, red);
  d: path("M14 31h4v-8h14v-4.667L18 19v-9h-4v9L.228 18.409A15 15 0 0 0 0 21v2h14z");
}

.r8eqqzb-g {
  fill: var(--svg-color--85b8ee, #85b8ee);
  d: path("M48.27 38.13c.14-.111.297-.204.386-.371c.083-.026.173-.139.251-.014a.33.33 0 0 1-.04.429a1.1 1.1 0 0 1-.597-.044");
}

.rbojz5aeg {
  fill: var(--svg-color--fbfcfc, #fbfcfc);
  d: path("m53.22 26.815l.521.15c.047.047.035.094-.003.141c-.181.058-.344-.002-.511-.064a.16.16 0 0 1-.058-.138a.17.17 0 0 1 .051-.089");
}

.rcqvrwb_m {
  fill: var(--svg-color--547395, #547395);
  d: path("M50.897 36.3a4 4 0 0 1-.227.063c.044-.104.141-.159.228-.223l.025-.005c.021.061.027.116-.026.165");
}

.re7xufbjt {
  fill: var(--svg-color--6e839d, #6e839d);
  d: path("M53.47 38.33c-.114.02-.225.045-.338.065l-.016-.131c.123-.01.251-.036.354.066");
}

.rfb3cmbps {
  fill: var(--svg-color--01d562, #01d562);
  d: path("M45.32 42.44c-.001-.02-.001-.035-.004-.053c.194.015.386.033.59.052c-.045.134-.134.082-.198.099q-.087.065-.173-.004q-.107-.048-.215-.094");
}

.rfdzfub4m {
  fill: var(--svg-color--d2c00c, #d2c00c);
  d: path("M46.39 29.31c-.066.146-.131.297-.13.463c-.076.086-.128.039-.176-.031c.026-.108-.136-.038-.126-.133c.115-.061-.002-.168.049-.244q.01-.021.018-.043l-.004-.023c.008-.092.034-.17.145-.175a.44.44 0 0 1 .224.186");
}

.rfu_8lcdv {
  fill: var(--svg-color--fafbfc, #fafbfc);
  d: path("M40.729 27.14q-.002-.068-.006-.131c.138-.087.295-.117.452-.139c.072.023.108.071.088.152a.22.22 0 0 1-.113.099c-.139.012-.275.162-.421.019");
}

.rhjcfqb-s {
  fill: var(--svg-color--f6f6f6, #f6f6f6);
  d: path("M48.808 37.1c-.123-.009-.246-.134-.373-.009c-.119.064-.243.025-.366.024c-.103-.098-.256-.172-.158-.356c.099-.06.214-.047.315-.071c.176-.012.354-.001.529-.005c.26.004.518 0 .777.011c.146.006.304.003.367.182c-.023.285-.179.397-.458.344c-.095-.041-.169-.164-.301-.085a.4.4 0 0 1-.095.026c-.087.016-.163-.016-.237-.061");
}

.rie3oq7cu {
  fill: var(--svg-color--07b400, #07b400);
  d: path("m41.18 35.608l.145.39c.005.067.014.135.019.203c-.153.099-.034.28-.115.408c-.201-.069-.129-.318-.319-.423l-.002.315q-.051.055-.119.012c-.25-.151.031-.331-.024-.493c.217-.059.244-.306.415-.412");
}

.rinzqfbrp {
  fill: var(--svg-color--red, red);
  d: path("M32 28.72v-.038L22.83 24zM9.242 24L0 28.753v1.527L12.282 24z");
}

.rjmuwabfk {
  fill: var(--svg-color--8abef6, #8abef6);
  d: path("M50.52 37.619q-.18-.22-.364-.44c.015-.199.169-.074.253-.11c.142-.017.197.089.264.179c.093.03.162-.042.242-.063l.061.425c.059.149.029.302.02.455q-.06.055-.104-.014l-.146-.123c-.07-.109-.162-.197-.226-.309");
}

.rlurilb-g {
  fill: var(--svg-color--12b283, #12b283);
  d: path("m51.13 43.4l.399.001c-.077.034-.154.065-.293.122c.179.013.301.019.523.033c-.442.153-.789.16-1.244.036c.268-.079.473-.052.615-.192");
}

.rlw545vkf {
  fill: var(--svg-color--7a3a00, #7a3a00);
  d: path("M50.586 40.916q.063-.146.123-.291l-.002.532a1 1 0 0 0-.073.071c-.182-.078-.154-.189-.048-.312");
}

.rngmkibnt {
  fill: var(--svg-color--88bcf3, #88bcf3);
  d: path("M48.819 34.02c-.153-.008-.318.061-.458-.063c.125-.083.316-.057.392-.228c.197.06.113.177.066.291");
}

.roy5oi95m {
  fill: var(--svg-color--e0e3e8, #e0e3e8);
  d: path("m55.42 32.804l.018-1.465c.097.66.041 1.324.04 1.986c-.259-.146-.161-.336-.058-.521");
}

.rozy09-2c {
  fill: var(--svg-color--46617d, #46617d);
  d: path("m50.13 40.1l-.001.076c-.047.042-.092.043-.136-.005c-.091-.05-.105-.13-.081-.225c.05-.066.113-.11.205-.093q.041.025.06.069a.2.2 0 0 1 .007.1a.2.2 0 0 1-.054.078");
}

.rra-a-w6p {
  fill: var(--svg-color--445e7a, #445e7a);
  d: path("M50.729 39.05q.008.07.012.145l-.085-.082q-.002-.032.006-.063z");
}

.rrtxfgqus {
  fill: var(--svg-color--405973, #405973);
  d: path("M46.765 37.28c.023-.086.142-.163.026-.261c.066-.092.145-.083.224-.023l.061.146c-.047.083-.138.1-.208.147z");
}

.rsh36bgqb {
  fill: var(--svg-color--cc0, #cc0);
  d: path("m46.41 36.34l.08.001c.135.121.098.28.097.434c-.077.158-.039.341-.097.504l-.154.01a.13.13 0 0 1 .008-.07c.142-.284.039-.586.066-.879");
}

.rsmqawbnp {
  fill: var(--svg-color--6a6a6a, #6a6a6a);
  d: path("M51.12 26.556c.053-.121.151-.061.234-.065q.04.074.074.144q-.13.124-.283.032a.09.09 0 0 1-.025-.111");
}

.ru-krzb-i {
  fill: var(--svg-color--8bc0f8, #8bc0f8);
  d: path("M45.755 34.593c.149-.147.303-.292.453-.44c.267.115.174.288.076.464c-.18.081-.356.103-.529-.024");
}

.rvt036byb {
  fill: var(--svg-color--485c72, #485c72);
  d: path("M51.53 35.467c-.062-.237-.253-.131-.395-.151l-.032.018c-.031-.006-.045-.017-.06-.028l.025-.048c.181.005.356-.012.521-.086c-.008.102-.02.199-.031.3z");
}

.rw4zh3swr {
  fill: var(--svg-color--eff0f2, #eff0f2);
  d: path("M50.51 38.761c-.141-.006-.153-.112-.17-.216c.331-.009.664-.068.987.05l.074.147l-.219.108a6 6 0 0 0-.224-.073c-.15.038-.3.074-.448-.016");
}

.rwccixbbc {
  fill: var(--svg-color--f3f3f2, #f3f3f2);
  d: path("m39.633 31.09l.003-1.26c-.036-.179-.008-.355-.014-.535c-.008-.433.031-.865-.012-1.297c-.016-.135-.04-.271.058-.395c.035-.059.09-.078.155-.079q.048.056.061.129c-.023 1.146-.02 2.29-.037 3.435c-.003.191.038.406-.151.551c-.101-.175-.017-.369-.063-.549");
}

.rxc0yrbky {
  fill: var(--svg-color--f8f8fa, #f8f8fa);
  d: path("M51.05 26.558c.009-.106.09-.138.178-.163q.137.017.272.03q-.075.035-.148.065a.3.3 0 0 1-.216.106a.13.13 0 0 1-.086-.038");
}

.ry79d14lj {
  fill: var(--svg-color--3d3d3d, #3d3d3d);
  d: path("m52.771 26.788l.027-.067a.1.1 0 0 1 .04.002c.108.098.273.066.377.169l.017.123a.2.2 0 0 0-.015.047c-.048.056-.106.08-.178.052c-.082-.058-.18-.066-.271-.103c-.049-.023-.083-.058-.092-.11c.008-.057.065-.074.095-.113");
}

.rz8685bwq {
  fill: var(--svg-color--f7f8fa, #f7f8fa);
  d: path("M39.457 28.11c-.004-.062-.001-.123-.012-.183c-.06-.364.058-.599.455-.626c.067.023.105.065.092.143a.3.3 0 0 1-.142.113a1 1 0 0 1-.153.066a.3.3 0 0 0-.07.046c-.037.113 0 .231-.032.342a.3.3 0 0 1-.047.094q-.042.038-.091.005");
}

.rzp3mb6ek {
  fill: var(--svg-color--311f10, #311f10);
  d: path("M53.21 40.05c-.331.093-.667.052-1 .043l-.146-.073c-.002-.07.043-.101.101-.126a.26.26 0 0 1 .274.069c.057.082.145.071.227.066q.274.012.545.021");
}

.s0sp2ccgx {
  fill: var(--svg-color--202009, #202009);
  d: path("M49.605 30.729q-.005.079-.007.15q-.261-.112-.521-.227l.001-.063c.097-.123.197-.013.298-.003q.114.074.229.143");
}

.s1uwkwb6d {
  fill: var(--svg-color--0bbf73, #0bbf73);
  d: path("M44.995 42.889c-.063-.425.299-.116.403-.25c-.069.177-.274.124-.378.239z");
}

.s22rsgkvn {
  fill: var(--svg-color--517091, #517091);
  d: path("M45.803 39.683q.067.004.138.005c.023.077.128.154 0 .229h-.215q.036-.115.077-.234");
}

.s4gp0jsbq {
  fill: var(--svg-color--bbb, #bbb);
  d: path("M55.35 29.824a.2.2 0 0 0-.048-.028l-.05-.04c-.085-.138-.057-.292-.066-.44c.033-.371-.053-.749.068-1.116q.044-.066.115-.035l.021-.006q-.019.833-.04 1.665");
}

.s4zfowbev {
  fill: var(--svg-color--5c3907, #5c3907);
  d: path("M45.41 40.876q-.08-.061-.161-.119c-.186-.155-.17-.379-.199-.588a.25.25 0 0 1 .04-.109a.12.12 0 0 1 .111-.02c.229.171.275.418.286.681a.3.3 0 0 1-.077.155");
}

.s7bhzm0wt {
  fill: var(--svg-color--f1f1de, #f1f1de);
  d: path("m54.725 27.4l.436.244c.018.11-.067.123-.138.147a.68.68 0 0 1-.528-.194c-.05-.09-.017-.145.069-.183q.08-.005.161-.014");
}

.s7zlse0-k {
  fill: var(--svg-color--656c24, #656c24);
  d: path("M51.12 35.84q-.026-.001-.051-.005c0-.174-.003-.352-.004-.523q.036.005.073.004z");
}

.s9tjidp8y {
  fill: var(--svg-color--04cf67, #04cf67);
  d: path("M50.28 45.27c-.668-.057-1.281-.115-1.816-.562c.292-.085.56-.07.828-.05c.047.002.242-.015.073.166c-.092.1.108.099.175.107c.268.035.535.045.74.339");
}

.sa_-7db4h {
  fill: var(--svg-color--f4f4d9, #f4f4d9);
  d: path("M40.572 27.376q0-.07.003-.142l.154-.095c.148.052.258-.188.417-.065q.06.028.06.088c-.154.239-.37.306-.634.214");
}

.saavr-btq {
  fill: var(--svg-color--cbcfd9, #cbcfd9);
  d: path("M44.1 45.723c.146.134.396.147.441.396c-.25.027-.372-.176-.537-.301a.12.12 0 0 1 .096-.095");
}

.sbc675b0y {
  fill: var(--svg-color--243241, #243241);
  d: path("m48.627 38.81l-.312-.004c.004-.047.014-.095.018-.139q-.03-.044-.012-.102c.134-.131.27-.278.417-.015c0 .062-.063.081-.087.122c-.006.05-.016.093-.024.138");
}

.sd-dqm09r {
  fill: var(--svg-color--596e85, #596e85);
  d: path("M47.07 37.836c-.021-.124-.186-.043-.219-.151c.147.045.29-.108.442-.014c-.05.088-.106.166-.223.165");
}

.sebyv_i5p {
  fill: var(--svg-color--6c4316, #6c4316);
  d: path("M41.02 35.33c.007-.023.007-.047.008-.068c.18.047.237.178.245.346q-.057.039-.1-.018q-.073-.131-.153-.26");
}

.sfaenhtvc {
  fill: var(--svg-color--808518, #808518);
  d: path("m49.1 39.785l.048.006q.013.226.021.452q.035.057-.026.067c-.084-.17-.053-.35-.043-.525");
}

.sggv8gusm {
  fill: var(--svg-color--6e6e6e, #6e6e6e);
  d: path("M55.25 35.593c-.16-.238-.012-.5-.054-.744c.049-.051.104-.113.128.016l-.007.688c-.023.01-.044.026-.067.04");
}

.sh0v210jr {
  fill: var(--svg-color--536374, #536374);
  d: path("M45.955 37.588a.1.1 0 0 0-.008.061c-.126.011-.259.073-.364-.05z");
}

.si50mvbuw {
  fill: var(--svg-color--8ec4fe, #8ec4fe);
  d: path("m46.08 40.962l.075-.08c.093.039.046.069-.005.099z");
}

.sjdkjqb5m {
  fill: var(--svg-color--070300, #070300);
  d: path("M51.94 40.24c.229-.041.274.078.279.279c.007.246-.16.192-.301.208c-.225.024-.274-.099-.284-.29c-.014-.26.179-.172.306-.197");
}

.sjlja94us {
  fill: var(--svg-color--0ac373, #0ac373);
  d: path("M49.04 45.551c-.091-.137-.278-.019-.373-.144c.404-.043.8.002 1.194.086c.021.174-.186.109-.227.219c-.072.02-.129.086-.206-.04a.334.334 0 0 0-.388-.121");
}

.sjtatbc0z {
  fill: var(--svg-color--e4e5e6, #e4e5e6);
  d: path("m51.48 38.762l-.081-.02q-.153-.072-.067-.217c.266-.073.528-.128.75.108c0 .154-.178.106-.227.207c-.154.102-.267.035-.375-.078");
}

.sl743tb3y {
  fill: var(--svg-color--eeeed2, #eeeed2);
  d: path("m51.14 26.617l-.01.075c-.323.139-.619.095-.839-.128c.105-.024.225.022.311-.073l.021-.025q.181.013.347.088l.081.004l.067-.002s.026.039.022.061");
}

.sm8bl9m7y {
  fill: var(--svg-color--3a3a14, #3a3a14);
  d: path("m45.965 27.362l.149.064a.09.09 0 0 1-.008.094c-.113.071-.22.168-.37.118q-.044-.041-.09-.081a.6.6 0 0 1 .319-.195");
}

.sm9x4dbfo {
  fill: var(--svg-color--ededed, #ededed);
  d: path("m46.989 29.898l.076-.026c.117.016.143.088.112.192c-.08-.035-.167-.061-.188-.166");
}

.so8_q2fzn {
  fill: var(--svg-color--180f05, #180f05);
  d: path("m40.17 39.729l.01-.074c.097.159.191.316.096.515a16 16 0 0 1-.106-.441");
}

.soi5kvfii {
  fill: var(--svg-color--14294b, #14294b);
  d: path("M45.3 44.39q.001-.038.008-.074c.049-.063.153-.105.169-.031c.024.097-.094.104-.177.105");
}

.sq3mczbod {
  fill: var(--svg-color--425a75, #425a75);
  d: path("m48.33 39.563l.085-.005q-.005.11-.007.225c-.038.039-.084.041-.135.027a.11.11 0 0 1-.042-.082c.002-.074.057-.118.099-.165");
}

.sqagtabmu {
  fill: var(--svg-color--8dc2fa, #8dc2fa);
  d: path("M52.1 37.2c.157.388.237.807.438 1.179a.16.16 0 0 1-.078.128a.2.2 0 0 1-.149-.007c-.106-.083-.169-.209-.298-.266c-.298-.194-.6-.388-.691-.769c.045-.146.195-.159.301-.231c.152-.081.306-.192.477-.034");
}

.sscx3_bzu {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M47.28 30.948c-.106.081-.189.142-.292.219c-.015-.21-.037-.39.292-.219");
}

.stfqbky5y {
  fill: var(--svg-color--c86200, #c86200);
  d: path("M44.654 40.879c.048.091.027.223-.059.178c-.152-.077-.239.224-.412.009c-.193-.242-.502-.379-.649-.68c-.034-.073-.123-.119-.216-.115c-.024-.128-.221-.23-.067-.391c.477.322.972.617 1.403.999");
}

.svjcqgbeb {
  fill: var(--svg-color--101417, #101417);
  d: path("M52.09 38.634c-.245-.147-.501-.115-.757-.039c-.312.105-.629.027-.942.028c-.081-.028-.202-.056-.161-.158c.053-.127.199-.132.323-.142q.204.027.412.029q.089-.002.177-.001c.176-.038.34.072.519.044c.121.083.261.057.394.072c.156.016.107.094.035.167");
}

.sxf2tgbcm {
  fill: var(--svg-color--2d2924, #2d2924);
  d: path("M41.13 42.19a.9.9 0 0 1-.213-.446a.49.49 0 0 1 .213.446");
}

.syimo33sg {
  fill: var(--svg-color--e5e7ee, #e5e7ee);
  d: path("m40.45 41.02l.07-.101c.088.016.039.117.1.149v-.002q.056.064.007.133a1 1 0 0 1-.08.091q-.046-.133-.097-.27");
}

.szdw3_buz {
  fill: var(--svg-color--4a2933, #4a2933);
  d: path("M53.27 39.609c.086.11.209.034.315.061c-.112.131-.253.068-.387.071a.1.1 0 0 1-.035-.087a.12.12 0 0 1 .063-.069z");
}

.t_874wura {
  fill: var(--svg-color--384c63, #384c63);
  d: path("M48.84 34.628q.028.003.059-.005c.046.133.07.258-.02.383c-.058-.09-.011-.257-.191-.248q.073-.066.152-.13");
}

.t0a68rbpm {
  fill: var(--svg-color--020100, #020100);
  d: path("M51.688 41.507c0-.014-.002-.026-.002-.026c.084-.057.065-.129.052-.201c-.085-.468-.002-.523.489-.351c.13.205.133.404-.025.598c-.096.009-.193.013-.289.02l-.149-.007z");
}

.t0v_wutbm {
  fill: var(--svg-color--4e4e4e, #4e4e4e);
  d: path("M54.47 40.13q-.032.003-.063.002c-.092-.098-.041-.166.046-.229l.104-.079s.038 0 .058.007c-.05.098-.095.2-.145.299");
}

.t1twvmbeb {
  fill: var(--svg-color--7fafe3, #7fafe3);
  d: path("M52.745 38.692c.038.353-.114.659-.234.972c-.152.026-.194-.104-.266-.193c-.036-.06-.061-.122-.043-.194c.165-.184.214-.45.412-.614q.056-.01.086.034a.06.06 0 0 1 .045-.005");
}

.t1xd_vbdn {
  fill: var(--svg-color--fefed1, #fefed1);
  d: path("M52.773 27.01a1.5 1.5 0 0 1-.553-.133q.054-.01.11-.016q.178.004.361.011l.075.067q.038.021.029.046q-.011.025-.022.025");
}

.t6m6bhbmz {
  fill: var(--svg-color--01d561, #01d561);
  d: path("M47.17 46.578c.135-.015.276.009.384-.084c-.076-.396-.382-.379-.677-.362c.005-.107.142-.077.13-.189c-.558.043-1.122.127-1.778-.023c.451-.178.795-.387 1.217-.193c.109.052.566-.15.651-.268c.092-.126.689-.269.837-.204c.232.099.479.135.727.153c.104.105.323-.098.373.144c-.166.218-.385.061-.576.075c-.183.014-.363.002-.545.003c-.064.04-.134.022-.205.024c-.057.014-.122-.002-.175.064c.345.342.791.252 1.207.285c.038 0 .076-.008.11 0c.096.028.254-.104.283.1c.027.213-.11.261-.283.289c-.225.038-.445.095-.716.153c.15.061.249.102.406.163l-1.044.26c.035-.113.247-.268-.062-.254c-.154.008-.357.117-.453-.118c.058-.064.121-.054.189-.018");
}

.t78qlobio {
  fill: var(--svg-color--6d4010, #6d4010);
  d: path("M42.828 35.09c.339-.324.339-.324.478.115c.038.114.083.226.125.34c.019.018.027.038.027.038c-.007.038-.013.048-.02.048c-.184.034-.238-.105-.284-.229c-.057-.158-.175-.226-.312-.286z");
}

.t7kpdjb_d {
  fill: var(--svg-color--f6f7f7, #f6f7f7);
  d: path("m46.47 39.18l-.223-.004c-.091.056-.169.131-.281.137a1.9 1.9 0 0 1-.548-.098c-.093-.074-.203-.139-.137-.286q0-.062-.003-.123c.089-.111.211-.121.339-.12c.444.003.893-.013 1.338.023c.187.067.382.06.576.068c.181.009.351.035.349.277a.34.34 0 0 1-.187.262c-.122.05-.248.036-.371.044c-.098.009-.193-.001-.289-.002c-.169-.003-.337-.024-.479-.135a.2.2 0 0 1-.084-.043");
}

.t8-7rlbtp {
  fill: var(--svg-color--83b4ea, #83b4ea);
  d: path("M49.12 37.692q.287.184.574.372c-.08.216-.245.094-.378.095l-.221-.042a.23.23 0 0 1-.069-.163c.005-.096-.024-.202.094-.262");
}

.t8kgc1d4v {
  fill: var(--svg-color--56687b, #56687b);
  d: path("M54.2 39.456a.5.5 0 0 0 .02-.365l.04-.09c.084.164.141.326-.06.455");
}

.tasfpsr1s {
  fill: var(--svg-color--89bbf0, #89bbf0);
  d: path("M45.34 39.761a1.16 1.16 0 0 0 .383-.377c.041-.051.078-.112.16-.077q.03.044-.001.088a.07.07 0 0 0 .009.064c.032.08.012.161-.004.244c-.019.077-.044.155-.063.233a1.4 1.4 0 0 1-.046.188q-.022.07-.04.141c-.034.104-.027.228-.104.319c-.08.034-.081.181-.207.148c-.026-.244-.122-.464-.237-.677q-.036-.035-.024-.083c.049-.076.134-.125.174-.211");
}

.te6_ryb5y {
  fill: var(--svg-color--9c4a00, #9c4a00);
  d: path("m53.62 41.17l-.069-.096c-.068-.057-.125-.116-.057-.209l.067-.069c.146.104.111.239.059.374");
}

.teju7ubgs {
  fill: var(--svg-color--9b4900, #9b4900);
  d: path("M52.806 40.882c-.149-.005-.296-.015-.441-.021l.001-.139l.445-.019q-.004.091-.005.179");
}

.th-_8il4w {
  fill: var(--svg-color--56606a, #56606a);
  d: path("M49.12 34.33c.13-.146.255.078.382.008c-.13.162-.255.004-.382-.008");
}

.th0h2aclz {
  fill: var(--svg-color--bcbcbc, #bcbcbc);
  d: path("m51.29 45.17l.077-.057c-.01.043-.026.074-.077.057");
}

.th4pekb_o {
  fill: var(--svg-color--c35c00, #c35c00);
  d: path("M52.53 41.623c-.2-.052-.424.048-.616-.077c.062-.097.16-.105.26-.113q.087-.004.171-.002q.184.005.368-.016c.07-.005.139.008.204.018c.147.024.299-.007.444.01l.029.018c.046.193-.098.151-.196.168a.2.2 0 0 1-.178.003c-.161.01-.322.045-.486-.009");
}

.thxwoqbmp {
  fill: var(--svg-color--8a4200, #8a4200);
  d: path("M49.751 40.838q-.117.152-.23.303a.12.12 0 0 1-.067-.074c.07-.113.114-.26.297-.229");
}

.tiuo1hbfc {
  fill: var(--svg-color--09ac00, #09ac00);
  d: path("M44.937 40.573c.184-.08.193-.208.096-.361c-.027-.077.016-.098.08-.104l.141.648a.55.55 0 0 1-.317-.183");
}

.tkmzmdups {
  fill: var(--svg-color--f5f5d1, #f5f5d1);
  d: path("M53.23 27.02c.178-.047.341.03.51.068l.017.029c-.003.127-.094.162-.197.194c-.183-.012-.376-.007-.378-.273a.05.05 0 0 1 .048-.018");
}

.tlysuv6zy {
  fill: var(--svg-color--50635d, #50635d);
  d: path("M51.22 34.507c-.124.031-.059.13-.07.201l-.081-.005l.012-.364c.1.014.149.064.139.168");
}

.tn52zuncq {
  fill: var(--svg-color--0c0f15, #0c0f15);
  d: path("M46.18 47.01a.4.4 0 0 1-.062.005c-.076-.052-.153-.098-.23-.148c0 0 .004-.038.002-.057c.127.021.251.047.29.2");
}

.tn7-3xwdg {
  fill: var(--svg-color--1ba194, #1ba194);
  d: path("m45.09 43.43l.006.057c-.086-.043-.201-.065-.158-.196c.009-.025.094-.055.13-.041c.112.035.037.113.022.18");
}

.tpdyvabyw {
  fill: var(--svg-color--7ea6d3, #7ea6d3);
  d: path("M53.879 41.11c-.125.275-.244.557-.382.828c-.087.162-.042.217.126.219l-.065.063c-.155-.026-.328.049-.463-.088c-.051-.171.025-.288.164-.369a.5.5 0 0 0 .225-.232c.069-.121.1-.256.155-.383c.032-.065.079-.123.154-.143c.063.004.102.035.086.105");
}

.tr4_ikirg {
  fill: var(--svg-color--2c2c2c, #2c2c2c);
  d: path("M39.644 29.31h-.049l-.01-1.267q.014-.039.024-.073h.046q-.007.67-.011 1.34");
}

.tt78j4f1y {
  fill: var(--svg-color--cfd1d8, #cfd1d8);
  d: path("M40.28 40.17q.028.117.054.244q-.395-.289-.228-.749q.056.015.096.06c.013.148.118.283.078.445");
}

.ttmu0cc4u {
  fill: var(--svg-color--5f3300, #5f3300);
  d: path("m43.827 41.468l.148.063c-.072.125-.352.062-.292.313c-.192-.123-.104-.344-.182-.506a.9.9 0 0 0-.325-.414c.06.332.3.559.207.856c-.414-.486-.293-1.146-.638-1.733c.229.176.229.176.393.452c-.111-.503-.445-.944-.461-1.476c-.017-.539-.275-1.018-.366-1.637c-.191.394.046.703-.036 1q-.028.036-.071.026c-.043-.034-.082-.084-.139-.018c-.011.047-.008.112-.037.138c-.063.055-.093-.026-.092-.06q.012-.185.057-.364c.158-.59.119-1.129-.374-1.567c-.107-.097-.187-.227-.279-.342c-.075-.05-.084-.122-.068-.202c.021-.054.057-.1.127-.084c.161.142.178.435.463.453c.063-.012.102.026.134.072c.188.326.333.672.589.954c.13.576.338 1.134.386 1.726c.012.134.078.267-.005.395c-.041.23.193.243.286.365c.013.156.14.272.151.427c-.006.439.29.77.424 1.161");
}

.tu1x1ibha {
  fill: var(--svg-color--291e12, #291e12);
  d: path("M39.819 38.435a5 5 0 0 0-.021-.21c-.041-.229-.079-.462-.119-.691l.007-.138q.032-.05.062.002c.104.598.286 1.181.288 1.794l-.083-.071a1.7 1.7 0 0 0-.134-.686");
}

.tu6oi3b9x {
  fill: var(--svg-color--835a00, #835a00);
  d: path("M44 39.886c.094.069.178.146.204.264c-.093-.023-.178-.057-.212-.155q.006-.056.008-.109");
}

.tuwa7x00l {
  fill: var(--svg-color--f5f3f4, #f5f3f4);
  d: path("M53.987 38.851c-.036 0-.072-.005-.107-.007c-.027-.185-.154-.401.137-.5c.064-.01.134-.014.168-.081c.104-.071.162-.029.177.078c.016.105.006.217.001.326c-.074.169-.255.119-.376.184");
}

.tw4t16b6i {
  fill: var(--svg-color--506152, #506152);
  d: path("M48.945 38.13q-.04.002-.078.001c-.081-.12.221-.454-.211-.381l.22-.213q.07-.031.114.029c.085.199.098.387-.045.564");
}

.twsc9-b4l {
  fill: var(--svg-color--8dc2fb, #8dc2fb);
  d: path("M49.813 40.536c-.316.032-.371.325-.527.518c-.188-.021-.141-.177-.167-.289c-.003-.183.018-.369-.049-.547c-.027-.146-.021-.299-.022-.443l.007-.715c.009-.175-.012-.361.148-.487c.134-.071.248-.047.351.054c.112.162.12.364.191.54c.052.153.093.306.146.459q.045.147.086.296c.021.083.037.165.063.246c.025.084.052.168.041.255c-.05.137-.194.046-.268.113");
}

.txx79sb_h {
  fill: var(--svg-color--272727, #272727);
  d: path("M46.17 27.865c.015-.105-.109-.252.086-.304c.085-.041.167-.04.242.013q.078.032.149.065a.13.13 0 0 1-.008.162l-.309.145c-.086.037-.128-.009-.16-.081");
}

.tzk6gdbkn {
  fill: var(--svg-color--1ba294, #1ba294);
  d: path("M49.646 43.25c.101.014.254-.063.234.144c-.093.052-.183.076-.252-.036a.12.12 0 0 1 .018-.108");
}

.u1-r-wirc {
  fill: var(--svg-color--d6dae4, #d6dae4);
  d: path("m44.1 45.723l-.096.095c-.111-.061-.223-.121-.277-.248l.014-.034c.139.022.283.037.359.187");
}

.u10f-mbgt {
  fill: var(--svg-color--ce6200, #ce6200);
  d: path("M40.22 34.939q.078-.109.155-.212c.317-.222.412-.193.434.152c.008.17.076.277.198.37a.8.8 0 0 1 .201.317q-.001.054-.011.104c-.059.123-.109.255-.228.33c-.207.129-.204.307-.131.504c.068.082.136.163.078.281a.36.36 0 0 0-.042.182a.3.3 0 0 1 .032-.131c.12-.164-.025-.268-.088-.387c-.017-.124-.055-.303.099-.31c.235-.015.186.286.321.389c-.111-.134-.087-.251.06-.349c.448.17.846.766.854 1.238c.003.318-.073.628-.056.941c.048.02.077.054.099.097c.018.083.04.163.071.188c-.052-.055-.057-.176-.07-.293c-.021-.233-.066-.47-.055-.705c.006-.086-.006-.196.096-.221c.123-.032.181.074.201.17c.09.391.264.752.31 1.15c.057.485.148.96.417 1.382a.5.5 0 0 1 .055.137c.021.11.049.255-.08.292c-.151.041-.154-.119-.16-.142c.259.274.029.786.347 1.096c.009-.112-.135-.191-.162-.317c-.02-.09-.094-.206.027-.266c.112-.057.186.038.248.117c.11.139.185.296.187.479c.005.108-.018.221.058.318l-.004-.004c-.01.092.015.202.085.232c.621.261.63.842.734 1.374c.01.047.039.089.057.134c-.031.061.057.244-.145.135c-.248-.135-.354-.396-.426-.625c-.07-.215-.189-.361-.332-.573l-.134.446q-.035.048-.065 0c-.094-.272-.246-.409-.569-.387c-.357.027-.449-.13-.487-.66c-.099-.097-.087-.222-.093-.345c-.005-.085.025-.195-.031-.249c-.237-.217-.188-.505-.227-.771c-.015-.123.006-.263-.048-.363c-.289-.531-.31-1.138-.492-1.695c-.122-.387-.318-.532-.714-.436c-.264.063-.352-.056-.375-.268c-.065-.574-.354-1.146-.006-1.728c.06-.099.061-.255-.005-.401c-.094.161-.077.35-.201.479c-.339-.388-.345-.435-.131-.857c.056-.105.096-.224.144-.339");
}

.u29q-2n3i {
  fill: var(--svg-color--040401, #040401);
  d: path("M48.727 29.378c.591.463 1.308.388 2 .437c-.021.228-.231.2-.314.323c.07.137.275.073.347.22c-.117.134-.29.027-.447.108c.283.275.578.541.712.94c-.322.067-.613.075-.834-.204c-.144-.168.102-.281.058-.433c-.092-.112-.216-.181-.332-.256c-.187-.069-.369-.091-.543.03c-.086.034-.168.018-.25-.011a.6.6 0 0 1-.172-.104a1.4 1.4 0 0 0-.285-.198a.35.35 0 0 1-.123-.082a.14.14 0 0 1-.005-.098a.4.4 0 0 1 .106-.103c.109-.128.227-.223.396-.101l.02.008s-.014-.014-.016-.014c-.158-.125-.374-.182-.431-.406c.019-.05.045-.093.111-.056m-1.615 3.136c-.446-.337-.627-.255-.741.342c-.188-.064-.113-.237-.165-.374c-.196.057-.213.274-.367.404c-.127-.218.027-.382.069-.589c-.202.013-.282.183-.405.294c-.038-.388.139-.572.541-.611c.204-.021.457.101.573-.197c.127-.324.295-.638.146-1q-.038-.063.028-.1c.273-.002.555-.025.817.07c.082.304-.115.521-.295.685c-.263.245-.457.45-.185.805c.062.072.058.182-.016.271");
}

.u4xj2zrmd {
  fill: var(--svg-color--614319, #614319);
  d: path("m44.33 38.24l-.095.01a.17.17 0 0 1-.128-.091c-.042-.117-.098-.236-.011-.355c.077-.072.058-.166.075-.253z");
}

.u5vs2glju {
  fill: var(--svg-color--080400, #080400);
  d: path("M53.19 40.2c.183-.003.332-.031.303.198c-.025.209-.073.347-.336.332c-.195-.013-.258-.065-.255-.261c.005-.24.121-.306.288-.269");
}

.u5yoi-_ua {
  fill: var(--svg-color--e6e2df, #e6e2df);
  d: path("M46.786 27.429q.073.038.144.08c.091.014.149.074.21.134l.019.073c.042.087-.006.137-.064.186c-.168.068-.189-.146-.314-.164a.28.28 0 0 1 .005-.309");
}

.u667ji33e {
  fill: var(--svg-color--486380, #486380);
  d: path("M50.13 39.873a5 5 0 0 0-.215.069c-.084-.076-.091-.178-.089-.283l.016-.034c.129-.008.221.058.301.153a.1.1 0 0 1-.013.095");
}

.u92hl0b3e {
  fill: var(--svg-color--586879, #586879);
  d: path("M47.667 39.26q-.19.161-.377.001c.125-.001.248-.002.377-.001");
}

.u989h0p9t {
  fill: var(--svg-color--fff, #fff);
  d: path("M32 18v-1h-4.614L32 14.714v-2.37L22.83 17h-3.038L32 10.767v-.757l-13 6.689V10h-1v8zM18 31h1v-6.349L31.808 31H32v-2.28L22.83 24h3.039L32 27.17v-.775L27.386 24H32v-1H18zm-5-6.349V31h1v-8H0v1h4.686L0 26.432v2.298L9.242 24h3.04L0 30.28V31h.234zM3.682 12.09c-.526.431-.995.92-1.409 1.459l6.969 3.456H6.203l-4.695-2.302a11 11 0 0 0-.296.582l3.474 1.72H.554q-.144.489-.249 1H14v-8h-1v6.699z");
}

.u9cf1abui {
  fill: var(--svg-color--8dc2fb, #8dc2fb);
  d: path("M52.43 38.467c.01.112.081.178.172.227c-.1.216-.121.48-.379.596c-.035.044-.084.052-.137.046a.4.4 0 0 1-.212-.141a.6.6 0 0 1-.128-.213a.3.3 0 0 1 .053-.19c.044-.065.126-.097.146-.177c-.09-.108-.246-.061-.342-.145a.5.5 0 0 1-.086-.064c-.118-.182-.309-.308-.395-.515c-.033-.174-.078-.353.087-.491c.07-.017.106.027.134.086c.222.266.424.549.758.693c.041.108.147.175.193.28z");
}

.ufs6fuhoa {
  fill: var(--svg-color--2a2723, #2a2723);
  d: path("M42.536 44.26c-.103-.104-.225-.189-.28-.333c.118-.004.177.103.27.145z");
}

.uh78wb_4f {
  fill: var(--svg-color--22447f, #22447f);
  d: path("M46.39 43.693c-.182.151-.303.122-.453.064c.124-.15.254-.083.453-.064");
}

.uj3eu17qt {
  fill: var(--svg-color--d3d7e3, #d3d7e3);
  d: path("M46.929 47.47a1 1 0 0 0 .068-.068c.128-.032.237.071.362.051c.047.056.044.093-.039.098c-.155.093-.279.038-.391-.081");
}

.uja1mrayy {
  fill: var(--svg-color--d9d9d8, #d9d9d8);
  d: path("M48.691 30.15c-.234.144-.492.03-.738.06a.16.16 0 0 1-.033-.153a.34.34 0 0 1 .191-.187c.193.001.32.124.447.251q.066.012.133.029");
}

.ujx2u4-5j {
  fill: var(--svg-color--323e4b, #323e4b);
  d: path("M48.3 34.995c.171.075.378 0 .532.133a.2.2 0 0 1 .037.084l-.013.048l-.031.034a1 1 0 0 1-.079-.08c-.178-.126-.439.107-.591-.135z");
}

.unxw75u2b {
  fill: var(--svg-color--a64f00, #a64f00);
  d: path("m51.623 40.12l-.091.163c-.271.051-.43.216-.492.481q-.047.01-.095.016a.08.08 0 0 1-.053-.07c-.04-.604-.013-.627.731-.59");
}

.upjy9_n8p {
  fill: var(--svg-color--fdfdfc, #fdfdfc);
  d: path("M45.82 26.292c0 .047-.002.089-.003.136c-.12.152-.29.13-.451.128c-.143-.039-.35.039-.388-.202c.132-.107.261.01.392.011c.094-.103.221-.055.336-.064z");
}

.urpuz9bnj {
  fill: var(--svg-color--ca6200, #ca6200);
  d: path("M42.02 42.909c.075-.06.194-.171.247-.08c.156.271.446.161.65.279c.147-.115.295-.225.442.001c.045.202.092.404.141.618c-.146.011-.264.01-.353-.096c-.038-.043-.055-.103-.136-.101c-.544.008-.8-.156-.991-.621");
}

.ursyojbfb {
  fill: var(--svg-color--1f272d, #1f272d);
  d: path("M45.38 35.936c-.016-.228.229-.097.292-.216a.16.16 0 0 1 .096-.038c.156.018.313.019.468.019q.056-.003.109-.002l.109.001q.056 0 .109-.004c.193.001.387.014.579-.034c.187.004.373.016.551.069c.178.052.234.146.042.268c-.662.024-1.321-.006-1.981-.004c-.125-.025-.259.012-.374-.059");
}

.uv4zb_j1a {
  fill: var(--svg-color--668bb5, #668bb5);
  d: path("m48.26 39.77l.149.013l-.053.077a.22.22 0 0 1-.144.059a.2.2 0 0 1-.096-.04c-.034-.059-.009-.097.043-.125a.12.12 0 0 1 .101.016");
}

.uw7zanbws {
  fill: var(--svg-color--88bcf4, #88bcf4);
  d: path("M48.18 39.574a.3.3 0 0 0 .007.063q.032.026.018.042l-.025.015l-.075-.064c.009-.037.026-.069.075-.056");
}

.uxrbzxg8q {
  fill: var(--svg-color--3b526a, #3b526a);
  d: path("m49.993 40.17l.136.005l-.01.214l-.029.011l-.031-.003c-.086-.055-.096-.135-.066-.227");
}

.v04gbfktc {
  fill: var(--svg-color--c26500, #c26500);
  d: path("M43.36 43.11c-.148-.119-.296.034-.442-.001l-.072-.376c.286-.031.494.049.514.377");
}

.v1l4ig5wu {
  fill: var(--svg-color--425b76, #425b76);
  d: path("M45.34 37.938a.06.06 0 0 0-.036-.042c.088-.143-.036-.358.166-.462c-.096.158.047.374-.13.504");
}

.v2e-sab5l {
  fill: var(--svg-color--f9f9fa, #f9f9fa);
  d: path("M40.12 27.22c.184-.12.39-.176.603-.214a.17.17 0 0 1 .047.156c-.025.081-.089.123-.162.149c-.127.026-.256.085-.388.033a.17.17 0 0 1-.1-.124");
}

.v3ge6vbsv {
  fill: var(--svg-color--7f8419, #7f8419);
  d: path("M46.51 34.601q-.036 0-.078.004l.015-.448q.032.037.063.079c.081.119.107.241 0 .365");
}

.v5u2g1ytp {
  fill: var(--svg-color--4f6361, #4f6361);
  d: path("M49.19 36.36c-.151.091-.047.232-.068.349l-.083-.004a.6.6 0 0 1-.006-.428q.014-.056.026-.113q.066.096.131.196");
}

.v6uvrxbuo {
  fill: var(--svg-color--5d81a6, #5d81a6);
  d: path("M48.1 40.02c-.036.098.187.254-.071.297c-.07.039-.138.09-.227.07q-.176-.097-.071-.272q.033-.05.068-.097a.2.2 0 0 1 .093-.068c.082-.017.156-.007.208.07");
}

.v77_h3bui {
  fill: var(--svg-color--8dc2fb, #8dc2fb);
  d: path("M46.21 35.498c.114.081.055.191.051.294c-.168-.023-.351.073-.503-.067c.063 0 .132.014.146-.076c.133.009.198-.114.306-.151");
}

.v828lveya {
  fill: var(--svg-color--15ae88, #15ae88);
  d: path("M47.92 43.756c.089.03.309-.135.23.152c-.173.167-.38.147-.659.112c.193-.05.333-.072.458-.125c.154-.066-.024-.09-.029-.139");
}

.v9_-9kbmj {
  fill: var(--svg-color--566779, #566779);
  d: path("M47.976 38.14q.044.041.085.086q-.008.105-.013.207c-.081-.086-.212-.157-.072-.293");
}

.v92478tmz {
  fill: var(--svg-color--222f40, #222f40);
  d: path("M52.42 43.911c-.012.205-.178.298-.304.42c-.034-.238.193-.287.304-.42");
}

.va_ticcky {
  fill: var(--svg-color--6a7989, #6a7989);
  d: path("M49.34 35.601c.108-.124.215-.195.305.02c-.103-.009-.203-.013-.305-.02");
}

.vb2q53zcm {
  fill: var(--svg-color--3d4336, #3d4336);
  d: path("M46.667 34.67c-.102.028-.221-.017-.311.069q-.04 0-.079.003q.004-.066.01-.126a.3.3 0 0 1 .066-.017l.073.005a.2.2 0 0 1 .092-.051c.079.002.143.024.149.117");
}

.vbmfr4r_j {
  fill: var(--svg-color--413e24, #413e24);
  d: path("m44.964 39.16l-.06.142a.13.13 0 0 1-.095.101c-.056-.002-.086-.032-.101-.085q-.002-.051.038-.082q.038-.035.073-.075z");
}

.vbozinowv {
  fill: var(--svg-color--e0e3ea, #e0e3ea);
  d: path("m41.622 26.86l-.087-.084c.161-.049.312-.196.495-.059z");
}

.ve4fqjr9x {
  fill: var(--svg-color--683602, #683602);
  d: path("M42.525 35.771c.147-.203.046-.521.303-.676l.038.042c-.012.336.097.651.172.971c.073.305.078.588-.146.834c-.107.118-.081.279-.141.411a.15.15 0 0 1-.153.022c-.17-.159-.219-.361-.055-.526c.319-.325.147-.63.014-.949c-.033-.036-.069-.074-.032-.129");
}

.vf9lz8b0z {
  fill: var(--svg-color--3c3c3c, #3c3c3c);
  d: path("M50.967 26.554c-.122-.003-.243-.008-.347-.088c.144-.081.26-.055.347.088");
}

.vfswlibxm {
  fill: var(--svg-color--d9d90c, #d9d90c);
  d: path("M47.36 29.74c.158.065.277-.163.445-.06c-.082.182-.285.156-.457.282c.217.039.403.069.591.099l.012.144c-.201.071-.419-.052-.614.054l-.03.004c-.081-.033-.128-.104-.173-.174c-.027-.078-.094-.143-.094-.231c.064-.15.205-.096.32-.118");
}

.vg7q1b2bz {
  fill: var(--svg-color--526761, #526761);
  d: path("M46.18 37.674a.36.36 0 0 0 .291-.069q.121.04.158.163c.028.136.036.271-.037.396a.1.1 0 0 1-.083.061c-.158-.057-.087-.243-.19-.332a.4.4 0 0 1-.06-.067c-.022-.034-.044-.063-.067-.099q-.04-.006-.032-.026q.008-.027.02-.027");
}

.vgj0ulb8a {
  fill: var(--svg-color--090806, #090806);
  d: path("M39.619 36.946c-.048-.12.052-.273-.081-.377l.019-.231c.042.021.095-.149.112-.012c.024.204.002.416-.005.622c0 0-.029 0-.045-.002");
}

.vi175hfzl {
  fill: var(--svg-color--0faa00, #0faa00);
  d: path("m43.798 38.17l.057.752q.031.032.02.057l-.016.025c-.043.071-.096.119-.176.135c.002-.189.05-.387-.046-.568c-.102-.194-.028-.32.161-.401");
}

.vjy51kb-q {
  fill: var(--svg-color--fbfbfc, #fbfbfc);
  d: path("m53.742 27.08l.001-.117c.117.011.229.025.305.133a.3.3 0 0 0-.007.07c-.068.068-.142.025-.212.008a.2.2 0 0 1-.076-.048z");
}

.vk5f2-c-v {
  fill: var(--svg-color--586674, #586674);
  d: path("m45.37 36.19l.135-.092c.081.06.193.039.271.106l.03.038c-.114.146-.323.028-.447.155q.007-.099.011-.207");
}

.vnnrk-bli {
  fill: var(--svg-color--383838, #383838);
  d: path("M48.827 33.506c-3.092-.022-6.178-.042-9.268-.061q-.001-.044.004-.082c.073-.065.165-.041.25-.04c2.989.022 5.979.037 8.967.07q.089.032.047.113");
}

.vou7ys6bz {
  fill: var(--svg-color--e9e9cb, #e9e9cb);
  d: path("M55.22 31.21a.2.2 0 0 0 .051.031c.072.097.061.192.006.288c.054.1.086.201.068.316c-.147.119-.027.296-.087.433c-.22-.22-.237-.724-.038-1.068");
}

.voytp2bpm {
  fill: var(--svg-color--282828, #282828);
  d: path("M49 30.368q-.338-.013-.674-.021a1.24 1.24 0 0 0-.592-.005c-.142.008-.283.027-.399-.083c.141-.271.395-.129.599-.163c.257-.047.502.057.757.05a.7.7 0 0 1 .309.222");
}

.vpj9n3-tk {
  fill: var(--svg-color--9e4d00, #9e4d00);
  d: path("m42.21 38.39l-.072.077q-.033-.035-.07-.069c.016-.043.024-.112.051-.119c.083-.02.079.056.091.111");
}

.vqd6uebhn {
  fill: var(--svg-color--08121e, #08121e);
  d: path("M46.08 45.24q.432-.032.865-.068c-.237.242-.537.228-.84.191c-.056-.009-.033-.076-.025-.123");
}

.vrqxnobmj {
  fill: var(--svg-color--6f88a3, #6f88a3);
  d: path("M46.927 36.34c-.105.106-.204.093-.292-.024a.06.06 0 0 1-.002-.041q.15.031.294.065");
}

.vsoi0xt1u {
  fill: var(--svg-color--434343, #434343);
  d: path("M54.851 38.701c-.113-.188-.027-.347.077-.501l.019.141z");
}

.vt_yg4y2l {
  fill: var(--svg-color--f9f9d1, #f9f9d1);
  d: path("M42.43 26.781c.111-.112.293-.005.397-.128c.067-.032.135-.053.207-.018q.062-.03.106.021c-.068.377-.369.227-.591.261a.17.17 0 0 1-.119-.136");
}

.vwipx0ntj {
  fill: var(--svg-color--5c6066, #5c6066);
  d: path("M48.972 35.6a.4.4 0 0 1-.072.004c-.054-.056-.11-.108-.164-.165q.04-.072.085-.145l-.007.004c.232.004.238.129.158.302");
}

.w_dt9smgo {
  fill: var(--svg-color--202c39, #202c39);
  d: path("M50.14 39.755c.136.077.255-.005.379-.032l-.097.22c-.095.076-.191.014-.288-.008a.13.13 0 0 0-.004-.062l.009-.087z");
}

.w-rvkrbgg {
  fill: var(--svg-color--292929, #292929);
  d: path("M48.827 33.431q.005-.033.006-.067l5.718.032q.357 0 .711-.003l-.003.087c-.13.114-.284.066-.428.065a232 232 0 0 0-5.663.007q-.067.017-.137.026a.26.26 0 0 1-.195-.054l-.009-.019z");
}

.w0wsp8blp {
  fill: var(--svg-color--d6dce9, #d6dce9);
  d: path("m54.946 38.34l.075.178c-.021.24-.062.475-.167.692q-.09.004-.116-.083c-.039-.122-.009-.242.017-.363a1 1 0 0 1 .023-.103c.052-.11.037-.255.168-.321");
}

.w2hg8_njs {
  fill: var(--svg-color--e5e8f1, #e5e8f1);
  d: path("M39.38 34.876c.07-.378-.057-.771.081-1.146c.165.124.106.306.118.468c.01.133-.008.267.035.394a.6.6 0 0 1 .013.19c-.075.238-.049.484-.06.729c-.029.181.039.363-.016.543c.002.093.006.191.007.284c.042.073.047.142.005.215q-.04.052-.098.018l-.023-.425c-.042-.127.01-.267-.04-.396c-.007-.291-.016-.579-.022-.874");
}

.w3-nu-xyb {
  fill: var(--svg-color--1c1c1c, #1c1c1c);
  d: path("m52.16 26.642l.013.032s0 .034-.002.042c-.188.115-.371.197-.502-.073q.22-.003.44-.002a.1.1 0 0 0 .051.001");
}

.w3ju2u80e {
  fill: var(--svg-color--efef02, #efef02);
  d: path("M49.15 41.2a.134.134 0 0 1-.145.064c-.112-.285-.016-.58-.044-.87l.006-.804c-.015-.259.053-.523-.056-.776c-.018-.149.034-.213.186-.159c.05.129.014.264.022.392l-.005.717c.021.182-.059.382.059.556c.022.149.005.296.01.442c-.021.145.041.297-.033.438");
}

.w3mc0lbrd {
  fill: var(--svg-color--934600, #934600);
  d: path("M47.29 41.485c-.123.041-.271-.031-.38.069c-.137.016-.274.023-.396-.054c.03-.068.109-.029.151-.072c.214-.009.422-.028.625.057");
}

.w4ybocb3g {
  fill: var(--svg-color--263341, #263341);
  d: path("M49.31 38.16c.125-.039.277.042.378-.095c.104.097.245.065.365.103c-.244.113-.501.03-.75.032a.1.1 0 0 0 .007-.04");
}

.w56i7_usr {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M39.683 34.04q.013.704.021 1.408l-.02.08c-.061.041-.118.046-.168-.016c.04-.252.002-.509.063-.761c.016-.241-.162-.508.104-.711");
}

.wakj7mbzb {
  fill: var(--svg-color--2e2e2e, #2e2e2e);
  d: path("m55.31 31.17l.036-.006c-.018.122.083.267-.063.367q-.004-.14-.006-.288z");
}

.wao6zccne {
  fill: var(--svg-color--a07000, #a07000);
  d: path("M42.493 42.591c-.022.058-.047.133-.121.118c-.105-.019-.104-.12-.117-.204c.092-.003.181 0 .238.086");
}

.waq9kkb1g {
  fill: var(--svg-color--6f6f6f, #6f6f6f);
  d: path("m39.54 35.523l-.028.018l-.032-.003c.027-.244-.095-.502.074-.731l.014-.063l.039.051c-.02.243.058.494-.067.728");
}

.wbfodzw6a {
  fill: var(--svg-color--704111, #704111);
  d: path("M41.02 35.33c-.143-.095-.304-.173-.276-.393c.047-.366-.152-.312-.371-.211c.061-.162.158-.281.354-.229c.199.055.175.221.159.361c-.016.162.067.279.143.402c.021.019.028.03.018.046q-.014.024-.027.024");
}

.wca5dm17u {
  fill: var(--svg-color--03d165, #03d165);
  d: path("M45.46 43.882c.317-.003.63.102.951.004c.152-.048.311-.072.409-.218a.06.06 0 0 1 .053-.043a.06.06 0 0 1 .067.025c.098.226-.091.614-.294.559c-.39-.11-.82-.046-1.187-.267q-.038-.02-.025-.041q.013-.018.026-.019");
}

.wcd_gcb1y {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M42.685 44.587v-.057c.04.002.069.02.068.066l-.035.006z");
}

.wdc4_tb3i {
  fill: var(--svg-color--00d760, #00d760);
  d: path("M45.3 45.44v-.063c.103-.054.203-.069.308-.005c.017.04.163.089.008.117c-.1.019-.211-.031-.316-.049");
}

.wexojfb2y {
  fill: var(--svg-color--525c66, #525c66);
  d: path("M50.06 38.17c.131.146-.019.238-.068.352c.029-.172-.031-.239-.214-.238c-.38 0-.765.018-1.141-.057c.226-.007.45-.018.673-.024c.242-.189.504.066.75-.033");
}

.wg58io7uz {
  fill: var(--svg-color--57789b, #57789b);
  d: path("M50.52 37.619a.41.41 0 0 1 .226.309c-.114-.075-.238-.144-.226-.309");
}

.whb1cbbtc {
  fill: var(--svg-color--747474, #747474);
  d: path("M47.689 26.29c-.368-.023-.744.1-1.104-.068c.158-.139.34-.045.511-.054c.183.059.374.01.56.033q.066.026.033.089");
}

.wl-qftbop {
  fill: var(--svg-color--2b82b2, #2b82b2);
  d: path("M50.33 43.23c.123-.076.243-.204.444-.03c-.173.052-.305.088-.438.125z");
}

.wlfr9ubfq {
  fill: var(--svg-color--3b5169, #3b5169);
  d: path("M48.17 40.452c.031.285-.177.533-.141.818l-.53.002c-.038-.032-.046-.07-.04-.118a.3.3 0 0 1 .046-.079a.2.2 0 0 0 .016-.131a.4.4 0 0 1-.004-.141c.026-.108.104-.199.129-.313a.28.28 0 0 1 .118-.162a.43.43 0 0 1 .246-.059c.091.03.15.085.16.183");
}

.wmejh-ban {
  fill: var(--svg-color--88bcf3, #88bcf3);
  d: path("M50.886 40.05c-.151-.089-.017-.306-.178-.388c-.05-.135.003-.217.128-.262c.29.161.136.401.106.619a.2.2 0 0 0-.056.031");
}

.wp1kbmy0h {
  fill: var(--svg-color--8fc4fd, #8fc4fd);
  d: path("M49.12 33.647c.41-.128.829-.025 1.245-.05c.184-.014.371-.008.556-.013l.009.073c.06.18.012.364.022.544c.009.08-.024.156-.046.23c-.092.186-.262.204-.443.207c-.167.104-.359.051-.544.076c-.004 0-.017.023-.017.023c.013.025.027.041.04.059l.001.129c.046.048.116.086.083.174c-.168.184-.324.013-.485-.018a1.5 1.5 0 0 1-.523-.344a.3.3 0 0 1-.041-.101c-.019-.109-.004-.212.075-.298a.3.3 0 0 1 .087-.049c.127-.005.256.023.379-.022c.106-.021.217.016.323-.016c.04-.03.1-.048.044-.113c-.085-.028-.177-.026-.26-.067c-.156-.154-.431-.17-.505-.424");
}

.wr2gc3d2c {
  fill: var(--svg-color--c9ced8, #c9ced8);
  d: path("M50.53 45.776c.028.032.061.063.09.092c-.107.109-.221.211-.379.23l-.008-.089c.056-.13.198-.155.297-.233");
}

.wunj6ob0q {
  fill: var(--svg-color--576677, #576677);
  d: path("M46.02 39.26c-.039.057-.097.063-.157.063q-.074.032-.142.065c.027-.24-.294-.058-.306-.251c.204.04.403.08.605.123");
}

.wusk9e47v {
  fill: var(--svg-color--8ec4fd, #8ec4fd);
  d: path("m51.44 34.706l-.289.002c-.05-.094-.103-.187.07-.201q.109.101.219.199");
}

.wvuqigorc {
  fill: var(--svg-color--f5f5ed, #f5f5ed);
  d: path("M49.552 26.393c.132-.037.261-.063.393.001c-.022.21-.203.16-.329.199c-.795.047-1.583-.123-2.381-.091c-.322.015-.646.011-.969.052c-.146.022-.297.02-.43-.071q-.092-.089-.016-.19c.194-.066.407.024.598-.068q.084.001.167-.002c.363.011.723.01 1.083.012q.317.005.631.005l.143.001c.251.029.496.056.746.083c.124.001.253-.012.364.069");
}

.ww0m4zkjj {
  fill: var(--svg-color--2e261e, #2e261e);
  d: path("M40.11 39.674a19 19 0 0 1-.06-.4c.152.091.128.241.133.382q.03.029.015.053c-.01.015-.019.021-.019.021c-.029-.021-.051-.043-.074-.064z");
}

.wz5d27tjh {
  fill: var(--svg-color--2e77b7, #2e77b7);
  d: path("M48.744 46c-.516.158-.991.079-1.437-.258c.09-.182.256-.233.468-.195c.159.291.448.314.729.361c.058.092.152.078.24.092");
}

.wzpl8cc5a {
  fill: var(--svg-color--dedede, #dedede);
  d: path("M50.36 30.741c-.072.13-.171.148-.295.068c-.169-.112-.342-.219-.604-.382l.513.004z");
}

.x__nbdbgp {
  fill: var(--svg-color--05b500, #05b500);
  d: path("M43.849 38.03c-.147-.116.016-.312-.119-.442c-.224.062-.23.253-.257.434c-.067.01-.109-.004-.072-.084c-.104-.392.006-.76.118-1.185c.095.3.123.609.494.604c.07.142.071.298.083.451q.033.184.063.368c.04.063-.001.086-.054.103c-.161-.007-.155-.182-.256-.249");
}

.x-bh2gb8d {
  fill: var(--svg-color--3d4a57, #3d4a57);
  d: path("M52.02 36.828q-.036-.012-.074-.022q-.066-.063.001-.125l-.004-.027c.099.081.451-.129.295.253c-.058-.073-.164 0-.218-.079");
}

.x0rkbzb1p {
  fill: var(--svg-color--c6cad4, #c6cad4);
  d: path("M54.619 39.682c.099-.121-.014-.358.231-.4c-.065.165.047.413-.233.473a.2.2 0 0 1 .002-.073");
}

.x1i8mlb8n {
  fill: var(--svg-color--bbb, #bbb);
  d: path("M43.29 45.06c.018.029.031.06.048.089l-.051-.009z");
}

.x99dgx0nf {
  fill: var(--svg-color--673703, #673703);
  d: path("M43.68 41.839c.146.104.279.223.435.305c.229.123.328.313.368.551c-.021.28.186.522.135.808q-.027.036-.062.077c-.191-.04-.173-.216-.201-.347c-.089-.413-.168-.817-.588-1.049c-.115-.066-.19-.197-.087-.345");
}

.xag2r1qqx {
  fill: var(--svg-color--0f0f0c, #0f0f0c);
  d: path("M45.965 27.362c.347-.18.69-.119 1.035.01c.024.07-.011.116-.062.153c-.043.019-.086.028-.125.048c-.059.041-.104.108-.186.116c-.067.004-.124-.026-.181-.059a.9.9 0 0 0-.36-.132c-.061-.024-.132-.045-.121-.136");
}

.xbeuvybrf {
  fill: var(--svg-color--ececec, #ececec);
  d: path("M48.705 30.57c.123-.136.32.006.444-.12q.111.039.223.081q-.022.032.004.057c-.101.004-.197.003-.298.003c-.125-.006-.251-.016-.373-.021");
}

.xcj0_ibqg {
  fill: var(--svg-color--edeeee, #edeeee);
  d: path("m49.09 38.609l-.366-.021c-.131-.216-.25-.02-.373.011c-.173.067-.229-.066-.305-.167l.002.004c-.054-.081-.064-.166.002-.246c.201-.003.394-.099.601-.058c.339.1.688.033 1.031.06c.181.012.356.026.38.26c-.001.122-.06.209-.152.28c-.145.093-.276.079-.389-.059c-.084-.077-.183-.085-.292-.069a.13.13 0 0 1-.139.005");
}

.xezpymbph {
  fill: var(--svg-color--d6dae4, #d6dae4);
  d: path("M50.53 45.776c.074-.129.168-.226.336-.203q.056.003.042.059c-.066.115-.173.18-.288.236c-.078.016-.111-.014-.09-.092");
}

.xfd0wsvbb {
  fill: var(--svg-color--52624d, #52624d);
  d: path("M50.942 40.02c-.045-.187.15-.43-.127-.564a.1.1 0 0 1-.037-.077c.025-.079.086-.128.147-.175a.08.08 0 0 1 .086.007l.024.799z");
}

.xh1uhgthr {
  fill: var(--svg-color--46607d, #46607d);
  d: path("M50.13 39.935c.1-.065.193.004.288.008l.076.065l-.369.006z");
}

.xjrjovuzg {
  fill: var(--svg-color--fdfdfd, #fdfdfd);
  d: path("M46.04 47.09q.04-.037.083-.071q.027-.047.062-.005c.046.035.132-.002.154.079l-.086.087a4 4 0 0 0-.213-.09");
}

.xl65szb0r {
  fill: var(--svg-color--d0d5e0, #d0d5e0);
  d: path("m41.19 42.575l.092-.005c.143-.04.077.117.141.151q.002.037.006.072c.021.073-.009.097-.081.079a.6.6 0 0 1-.158-.297");
}

.xlgtk4zib {
  fill: var(--svg-color--2d2d01, #2d2d01);
  d: path("M47.518 29.368c-.059.093-.109.193-.231.217c-.109-.019-.248.059-.313-.103c.024-.131.178-.112.241-.205a.2.2 0 0 1 .08-.046c.111-.015.196.019.223.137");
}

.xm1k8srxm {
  fill: var(--svg-color--6f6f6f, #6f6f6f);
  d: path("m55.35 29.824l-.007.893c-.049.147-.012.303-.029.451q-.005.069-.07.084a.14.14 0 0 1-.098-.067c-.083-.285-.04-.578-.022-.866c.056-.148.046-.313.122-.458a.09.09 0 0 1 .104-.037");
}

.xmgrvkb0o {
  fill: var(--svg-color--2f353c, #2f353c);
  d: path("M51.48 38.762c.131-.009.231.135.375.079l-.075.141c.019.02.024.035.024.057q-.007.03-.013.029c-.081.042-.119-.016-.163-.064q-.076-.047-.15-.089z");
}

.xqccn2bau {
  fill: var(--svg-color--b8b8b8, #b8b8b8);
  d: path("m39.571 29.678l-.051.024a52 52 0 0 0-.016-.686l.003-.904l.021-.074q.076-.024.114.043c.111.402.025.813.049 1.219c-.01.137.013.282-.12.378");
}

.xrgaq8bsk {
  fill: var(--svg-color--8f4400, #8f4400);
  d: path("M53.646 41.17a.5.5 0 0 0-.094.287l-.146.012l.004.004c-.104-.163-.033-.283.094-.391c.074-.015.099.033.117.09z");
}

.xrnlb2vhn {
  fill: var(--svg-color--fbfcfc, #fbfcfc);
  d: path("m41.25 26.975l-.072-.104l.359-.094c.088-.032.1.014.087.084v.002c-.092.145-.196.247-.374.112");
}

.xs8mn31os {
  fill: var(--svg-color--644018, #644018);
  d: path("M43.42 35.644q.002-.045.009-.094l.321.146q-.058.007-.114.016c-.099.059-.181.073-.216-.068");
}

.xu_ppz-3x {
  fill: var(--svg-color--723741, #723741);
  d: path("m52.854 39.31l.049-.107c.512.034.512.034.369.407l-.002-.009c-.095-.163-.275-.198-.416-.291");
}

.xu8_arb8z {
  fill: var(--svg-color--4f6d8d, #4f6d8d);
  d: path("M52 39.734c-.018.142-.148.126-.234.177q-.028-.01-.063-.014l-.003-.086c-.027-.175.101-.177.214-.192c.06.015.103.043.086.115");
}

.xz9id_b4b {
  fill: var(--svg-color--009d00, #009d00);
  d: path("m49.889 41.895l-.001.071c-.229-.006-.463-.032-.666.106c-.095.065-.156-.005-.228-.053c-.013-.059-.003-.102.075-.063c.273-.029.536-.169.82-.061");
}

.y0j350rwv {
  fill: var(--svg-color--8bbff8, #8bbff8);
  d: path("M50.893 36.654a7 7 0 0 0-.295-.013q-.056-.072-.004-.142l.077-.141c.086-.026.151-.155.263-.052c-.006.119.045.243-.041.348");
}

.y3g2uhkhy {
  fill: var(--svg-color--2d3645, #2d3645);
  d: path("m43.728 45.41l-.312-.213c.208-.082.279.036.312.213");
}

.y5a5ttb2j {
  fill: var(--svg-color--88b9ee, #88b9ee);
  d: path("m48.22 34.33l.461.001c.136.042.24.105.206.277a.5.5 0 0 1-.151.234c-.072.029-.147.19-.217-.006c-.089-.176-.25-.311-.299-.506");
}

.y5fv1gbuq {
  fill: var(--svg-color--454e39, #454e39);
  d: path("M51.18 38.901a.3.3 0 0 1-.066.004c-.145.066-.047.207-.099.3q-.027 0-.055.004c-.076-.022-.111-.077-.123-.148a.5.5 0 0 1 .063-.255a.3.3 0 0 1 .075-.074c.098-.01.177.018.214.119a.2.2 0 0 1-.009.05");
}

.y5wlaabnj {
  fill: var(--svg-color--16aa8b, #16aa8b);
  d: path("M46.45 42.53q-.037.035-.073.072c-.069-.001-.153.027-.192-.063c-.004-.015.013-.053.025-.058c.091-.041.17-.018.24.049");
}

.y74iz7bpa {
  fill: var(--svg-color--18a78e, #18a78e);
  d: path("m50.53 44.808l.003.082c-.128 0-.244.115-.389.041c.1-.148.249-.112.386-.123");
}

.y7cb8-blk {
  fill: var(--svg-color--23a900, #23a900);
  d: path("m43.4 37.938l.072.084a.44.44 0 0 1-.121.399c-.034-.207-.033-.346.049-.483");
}

.y7tu0qbcw {
  fill: var(--svg-color--356dc6, #356dc6);
  d: path("m46.06 42.759l-.454-.007c-.009-.036.011-.062.028-.094c.015-.027.231.023.039-.087c-.04-.032.101-.068.002-.089c-.121-.026-.246-.035-.361-.083c-.12-.107-.116-.188.053-.229c.106-.024.225.007.333-.065c-.255-.219-.676-.123-.854-.469a.2.2 0 0 1 .007-.109a.5.5 0 0 1 .505-.255c.354.12.584.408.825.67c.266.284.546.325.93.274c.666-.086 1.352-.12 1.965.27a.13.13 0 0 1-.04.116c-.344.223-.716.072-1.077.072c-.199-.013-.4-.056-.595.028c-.311.172-.565-.073-.846-.111c-.018-.004-.037-.023-.055-.021c-.049.004-.024.064-.011.017c.013-.046.069.026.029.005c.076.188-.039.211-.179.215c-.085.003-.151-.102-.244-.048");
}

.yab8x8bnx {
  fill: var(--svg-color--484848, #484848);
  d: path("M55.08 37.36c-.14-.125-.057-.247.005-.366c.157.096-.024.2.006.3a.2.2 0 0 0-.011.066");
}

.yc_f8xjnu {
  fill: var(--svg-color--63380a, #63380a);
  d: path("M43.752 35.696c.227.055.26.226.283.424c.057.478.024.963.136 1.435c.02.101.076.205-.063.266c-.163-.101-.128-.29-.186-.435c-.163-.357-.253-.722-.17-1.117c.039-.201-.157-.364-.11-.573a.1.1 0 0 1 .11 0");
}

.yg9cjacuw {
  fill: var(--svg-color--a2a2a2, #a2a2a2);
  d: path("m39.584 28.05l-.055-.007l.01-.443l.025-.019c.011.002.023.013.032.018c.07.111.021.232.035.349a.11.11 0 0 1-.047.102");
}

.yh294k5-x {
  fill: var(--svg-color--2c2c28, #2c2c28);
  d: path("M47.18 30.06c.045.065.145.092.131.198c-.125.035-.205-.125-.332-.075l-.063-.051c.008-.121-.135-.141-.159-.237c.069-.029.081-.093.091-.158q.037-.033.086-.017q.09.054.099.157c.031.073.128.097.147.183");
}

.yhtp4lhkj {
  fill: var(--svg-color--80afe2, #80afe2);
  d: path("m51.4 39.965l-.063.011c-.28-.066-.134-.322-.213-.477a.5.5 0 0 1-.026-.115c-.014-.154-.041-.314.06-.453c.129-.08.166.033.225.104a1.5 1.5 0 0 1 .133.594c.019.133.047.267-.116.336");
}

.ykh7esw0c {
  fill: var(--svg-color--3f5770, #3f5770);
  d: path("M46.597 39.924c.137.005.215-.11.328-.155c.13.119.178.278.2.449a.3.3 0 0 1-.138.119c-.08.024-.094.093-.103.166c-.026.061-.041.129-.133.092c-.106-.21-.125-.442-.154-.671");
}

.yld_4zfto {
  fill: var(--svg-color--dada11, #dada11);
  d: path("m49.06 29.923l.098-.079c.07.032.202.08.149.149c-.088.12-.169-.023-.247-.07");
}

.yltjfybmo {
  fill: var(--svg-color--a54e00, #a54e00);
  d: path("M49.45 41.07q.036.037.067.074c-.043.103-.125.156-.229.185z");
}

.ym-1_2bpp {
  fill: var(--svg-color--403e19, #403e19);
  d: path("m47.26 27.924l-.037-.189c.227-.013.155.19.214.298l-.072.079c-.139-.006-.075-.125-.105-.188");
}

.ynex2hbmw {
  fill: var(--svg-color--28619c, #28619c);
  d: path("m47.32 43.28l-.216.172c-.054.081-.173.095-.208.196l-.082.016l-.018-.007q-.055-.082.007-.164c.108-.11.311-.1.373-.272z");
}

.yqox7-3ju {
  fill: var(--svg-color--151414, #151414);
  d: path("M52.676 39.956q.462-.002.924-.011c.122-.003.249-.035.298.134c.037.122.052.197-.082.302c-.23.181-.068.421-.01.639a3 3 0 0 1-.111.149l-.045.019l-.04-.03c-.045-.138-.06-.286-.12-.418c-.055-.191.045-.354.105-.541c-.144-.088-.3-.036-.448-.047c-.157-.012-.323.022-.463-.082q-.047-.056-.008-.114");
}

.yr2tterog {
  fill: var(--svg-color--4c4c4c, #4c4c4c);
  d: path("m53.856 41.548l.168-.374q.031-.042.063 0q-.006.068-.008.139c-.102.053-.039.258-.223.235");
}

.yt4mgpbvg {
  fill: var(--svg-color--030303, #030303);
  d: path("m55.36 32.803l-.009 1.047q-.01.37-.022.736c-.273-.085-.134-.317-.175-.487q.008-.252.006-.504l-.001-.125l.001-.125c.007-.271.007-.549.007-.82l.002-.256c.035-.154-.064-.364.182-.425z");
}

.yx7ehdchk {
  fill: var(--svg-color--555, #555);
  d: path("M49.552 26.393c-.122-.019-.26.027-.364-.07c.068-.123.183-.032.272-.058c.045.035.108.053.092.128");
}

.yyfiz5b3w {
  fill: var(--svg-color--2a83b2, #2a83b2);
  d: path("M48.2 44.984c-.13.03-.254.057-.393-.007c.152-.194.277-.028.393.007");
}

.z1s52sbpd {
  fill: var(--svg-color--869eb7, #869eb7);
  d: path("M47.03 35.13c-.141.138-.242.067-.326-.07c.11.024.238-.038.326.07");
}

.z28cfibch {
  fill: var(--svg-color--cd6100, #cd6100);
  d: path("M42.603 37.33q-.044.016-.082.033c-.405-.175-.409-.605-.59-.92c.209-.212.503-.33.661-.599l.029-.021c.185.111.292.809.125.93c-.222.165-.259.345-.143.577");
}

.z4875ct8k {
  fill: var(--svg-color--05ce68, #05ce68);
  d: path("M46.06 42.759c.092-.147.202.027.297-.014c.078-.036.187-.078.014-.143c-.018-.068-.005-.102.073-.072c.318-.064.572.22.89.159q.033.024.022.046s-.015.023-.021.023c-.425.171-.851.223-1.275.001");
}

.z6gexwb8s {
  fill: var(--svg-color--506359, #506359);
  d: path("m50.897 36.3l.026-.164q.023.008.042.006q.001.258.005.518l-.078-.001z");
}

.z6im_6b2s {
  fill: var(--svg-color--a85800, #a85800);
  d: path("M46.32 28.842c.128-.079.128-.283.306-.315c.235.063.073.214.074.331a1 1 0 0 0-.066.065a.23.23 0 0 1-.153.056c-.079-.017-.138-.057-.161-.137");
}

.z863ruity {
  fill: var(--svg-color--6d8299, #6d8299);
  d: path("M48.05 38.432c.106.046.169.171.305.167a.4.4 0 0 1-.018.068c-.157-.003-.285-.045-.287-.235");
}

.z8guc6dvz {
  fill: var(--svg-color--ccd2e0, #ccd2e0);
  d: path("m55.09 37.29l.131.073c-.077.383-.066.783-.204 1.154c-.078-.025-.112-.09-.141-.158a.4.4 0 0 1-.024-.161a.4.4 0 0 1 .016-.104c.041-.119.033-.244.058-.363c.035-.121.046-.246.092-.363a.17.17 0 0 1 .072-.078");
}

.z9c3x0b-c {
  fill: var(--svg-color--2f4154, #2f4154);
  d: path("M46.752 40.595c.064-.025.078-.085.082-.145c.06-.044.116-.021.178-.008c.086.031.175.05.253.1q.015.1.035.197c-.07.032-.091.096-.105.163l-.066-.005q-.037.045-.072-.004l-.216-.076c-.033-.074-.112-.129-.089-.222");
}

.zayirpb-s {
  fill: var(--svg-color--9b9e0d, #9b9e0d);
  d: path("M49.04 35.741c-.03.101.075.242-.084.312a.54.54 0 0 1-.059-.449l.049-.024c.017.009.033.013.051.021c.04.039.064.081.043.14");
}

.zb-07obzx {
  fill: var(--svg-color--33465a, #33465a);
  d: path("M46.23 39.999c-.123.072-.224.067-.286-.082c-.021-.081-.072-.154-.065-.246c.001-.1.067-.156.142-.206c.239.11.24.315.209.534");
}

.zbhlvcb-w {
  fill: var(--svg-color--5a4921, #5a4921);
  d: path("M44.962 39.698a.65.65 0 0 1-.145-.316q.045-.037.087-.079c.071.043.05.185.176.171l-.006-.004l.026.203c-.051-.009-.105-.065-.138.025");
}

.zcbihp2vo {
  fill: var(--svg-color--45554a, #45554a);
  d: path("M49.15 41.2c.001-.145.007-.291.008-.436c0 0 .032.001.047.003c.032.094-.036.214.078.286c-.016.073-.068.115-.133.147");
}

.zclo-xi9a {
  fill: var(--svg-color--151508, #151508);
  d: path("M45.662 28.16c-.302-.239-.666-.339-1.035-.46c.33-.188.683-.122 1.02-.143c.071-.031.092.013.104.066a.17.17 0 0 1-.07.071c-.044.017-.09.016-.137.018c-.029.003-.059-.012-.089-.001l.106.01c.172.055.209.191.215.346c-.016.059-.043.106-.114.093");
}

.zcw_91-1k {
  fill: var(--svg-color--4e5d4c, #4e5d4c);
  d: path("m51.14 37.943l-.002-.669l.123.001l.006.126c-.144.163-.055.357-.068.533l-.027.021z");
}

.zd81nmbil {
  fill: var(--svg-color--d1d5de, #d1d5de);
  d: path("m40.33 40.43l.104.191c.111.065.1.188.134.29c-.021.055-.054.097-.114.11c-.07-.193-.259-.357-.124-.591");
}

.zlaxx1bhc {
  fill: var(--svg-color--fbfbfb, #fbfbfb);
  d: path("M39.819 38.435a3 3 0 0 1-.07.154q-.007-.065-.018-.137c.032-.071-.007-.168.067-.228c.082.064.061.136.021.211");
}

.zm5x6ibrc {
  fill: var(--svg-color--0c0f14, #0c0f14);
  d: path("M48.716 46.834c-.019.125-.175.105-.215.208l-.145-.018a.57.57 0 0 1 .36-.19");
}

.zqji2ikvg {
  fill: var(--svg-color--797979, #797979);
  d: path("M45.706 26.3c-.093.117-.223.058-.336.064q.007-.063.019-.131c.108.004.232-.06.317.067");
}

.zr_v6n9xk {
  fill: var(--svg-color--9fa10b, #9fa10b);
  d: path("M46.48 35.11q.024.156.044.314c.066.124.092.245-.018.36q-.047.004-.091.011c-.165-.167-.033-.374-.078-.557q-.028-.058.023-.103c.039-.005.08-.017.12-.025");
}

.zrsmnobnp {
  fill: var(--svg-color--268aab, #268aab);
  d: path("m48.752 43.905l.485.004c-.125.112-.234.051-.326.071a3 3 0 0 1-.159-.075");
}

.zrx0itx7k {
  fill: var(--svg-color--d7dae2, #d7dae2);
  d: path("M47.617 47.34c.299.015.471-.264.739-.318c.049-.019.097-.033.145-.001q.034.046 0 .087c-.251.181-.519.321-.825.369c-.051-.005-.081-.033-.101-.078q-.007-.049.042-.059");
}

.ztvgpbc1y {
  fill: var(--svg-color--fefe00, #fefe00);
  d: path("M46.34 34.08a.06.06 0 0 0 .001-.063c-.028-.107-.047-.215.017-.319c.236.081.152.286.175.449c-.011.155.022.316-.082.453q-.06.046-.121.001c-.02-.173-.039-.346.01-.521");
}

.zu836_15s {
  fill: var(--svg-color--3f3f3f, #3f3f3f);
  d: path("m55.31 27.716l-.018.376h-.045l-.008-.366a.1.1 0 0 1 .071-.01");
}

.zup9ub0eg {
  fill: var(--svg-color--8ec4fe, #8ec4fe);
  d: path("m55.13 33.703l-.001.446l-.031 1.411c-.146.314-.065.655-.106.985c-.097.797-.245 1.584-.368 2.375a3.7 3.7 0 0 0-.236.895c-.213.411-.268.887-.504 1.291l-.073-.087c-.271-.18-.222-.424-.1-.652c.143-.26.023-.288-.199-.298c-.278-.012-.568.066-.835-.078c-.096-.154-.027-.26.107-.346c.131-.024.26.002.392-.004c.12-.001.24.02.353-.041q.066-.035.136-.061c.135-.053.289-.009.419-.083a.5.5 0 0 0 .099-.092c.08-.114.033-.241.03-.361c0-.067.024-.13.053-.188c.024-.153.136-.318-.059-.443c-.06.018-.117.038-.177.046c-.131.017-.265.002-.395.026a.3.3 0 0 1-.098-.005a.7.7 0 0 1-.135-.05a.38.38 0 0 0-.263-.033c-.196.047-.196.291-.367.361a.16.16 0 0 1-.103-.01c-.096-.076-.131-.194-.2-.293c-.218-.362-.339-.763-.437-1.171a1 1 0 0 1-.008-.102a1 1 0 0 1 .021-.096c.022-.072.075-.128.097-.2c-.025-.137-.178-.09-.238-.172c-.197-.266-.217-.59-.313-.887c-.024-.109-.039-.224-.072-.332c-.019-.095-.02-.188.034-.273a.16.16 0 0 1 .139-.063c.115.014.232.115.348.001c.082-.062.196-.106.121-.247c-.22-.104-.469-.004-.69-.088a.8.8 0 0 1-.304-.238c-.046-.086-.118-.154-.155-.243c-.04-.103-.039-.206-.04-.312c.005-.137-.005-.275.083-.397c.118-.12.271-.106.417-.104c1.077.004 2.158.009 3.235.026c.155.003.362-.059.423.187");
}

.zv_v73bvv {
  fill: var(--svg-color--366cc8, #366cc8);
  d: path("m42.841 44.685l-.088-.088c-.03-.028-.07-.037-.094-.068q-.019-.035-.034-.071l-.103-.108a.217.217 0 0 1 .013-.299c.281-.134.582-.191.891-.221c.149-.016.284-.029.404-.143c.117-.111.269-.128.405-.027c.273.197.306.041.293-.192c-.025-.259-.14-.506-.136-.77c.057-.396.111-.444.605-.521c.152.009.247.122.365.19c.071.041.143.081.203.136c.051.054.077.132.163.146c.117.013.234.005.347.03q.63.237 1.252-.019c.188-.078.384-.077.583-.042c.129.048.265.053.399.059c.102.009.193.031.254.125a.3.3 0 0 1 .005.105c-.071.119-.173.152-.302.09c.161.134.258-.038.384-.076a4.1 4.1 0 0 1 1.662.248a.6.6 0 0 1 .083.075c.075.115.184.085.293.07c.155-.024.313-.044.455.056c.02.27-.202.172-.334.244c.229-.076.449.044.659-.026c-.073-.026-.201.063-.256-.082c.057-.135.193-.132.305-.175c.262.004.519-.053.779-.051c.153.119.057.344.19.473a.4.4 0 0 1 0 .102q-.012.05-.032.1c-.077.131-.22.208-.283.352c-.026.062-.066.109-.134.126l-.012.101c-.024.027-.028.065-.057.089c-.03.022-.049.054-.091.052l-.075.08c-.135.141-.273.278-.447.37l.006-.007a.3.3 0 0 1-.077.057l.004.033c-.118.09-.255.154-.324.292a.7.7 0 0 1-.107.101c-.102.079-.217.139-.303.235c-.095.092-.222.134-.328.207c-.17.099-.33.212-.49.327c-.139.093-.28.181-.439.232c-.117.021-.188.113-.272.183c-.086.053-.171.108-.271.127c-.155.026-.282.11-.402.2c-.239.136-.478.265-.748.322a.88.88 0 0 1-.605-.005c-.231-.047-.44-.157-.65-.262c-.059-.038-.119-.067-.18-.097a.65.65 0 0 0-.326-.192c-.186-.048-.331-.169-.495-.252a6 6 0 0 1-.469-.296a1.8 1.8 0 0 0-.344-.215l.01.004c-.13-.143-.321-.201-.464-.325c-.08-.106-.222-.141-.302-.249c-.035-.034-.074-.062-.107-.1c-.059-.093-.119-.184-.247-.187a.2.2 0 0 1-.077-.052l.009.004a.15.15 0 0 1-.038-.073a.2.2 0 0 0-.027-.08a1 1 0 0 0-.094-.009q-.18-.18-.357-.363");
}

.zv6v4x7jy {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M51.964 44.602q.031-.037.064-.069c.013.061.012.12-.065.142c-.021-.019-.027-.032-.021-.05q.01-.023.022-.023");
}

.zv7q05b2v {
  fill: var(--svg-color--754717, #754717);
  d: path("M42.525 35.771q.035.038.066.077c-.066.371-.343.507-.661.599l-.069-.078c.16-.266.531-.303.664-.598");
}

.zw0i49aex {
  fill: var(--svg-color--0fb97d, #0fb97d);
  d: path("m45.06 45.43l-.141-.064c.135-.135.217-.039.297.066z");
}

.zx9_vph2e {
  fill: var(--svg-color--423c06, #423c06);
  d: path("m46.761 30.698l-.001.084a.37.37 0 0 1-.229-.148v.002c.061-.084.129-.121.22-.039a.1.1 0 0 1 .01.101");
}

.zzxo8ubeo {
  fill: var(--svg-color--090400, #090400);
  d: path("M51.04 40.763c-.08-.525-.059-.544.492-.481c.017.557.08.465-.492.481");
}

</style>
