<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="cyf0nio7t"/><path class="n8-91eb0z"/><path class="swqwdl6-h"/><path class="j3auxxbuf"/><path class="dumtzvgta"/><path class="m1xyqmbvx"/><path class="p-4200rfm"/><path class="ybg-5-bhy"/><path class="o4pf8ub2n"/><path class="ahxlf7ftv"/><path class="db3jarbfa"/><path class="k17qflw7v"/><path class="e_76zfz5b"/><path class="ielbzqymv"/><path class="sy76ipw-o"/><path class="f6_3vcbmc"/><path class="eq4qfqb2h"/><path class="pwcsngb1o"/><path class="h-0fellfc"/><path class="ddf3qyxkp"/><path class="gk7474bqt"/><path class="o2qy065_g"/><path class="j2p-cxb4e"/><path class="yn6cscb_b"/><path class="s_i3uqjzv"/><path class="gv7-05t1q"/><path class="f15nfbb4o"/><path class="acuq17psk"/><path class="u7y3djfwq"/><path class="u0u64itas"/><path class="wbj9veb9o"/><path class="xh95xxb9n"/><path class="mt4tndy-l"/><path class="tvpnnsqsy"/><path class="l54lolb8j"/><path class="b4d69dc2x"/><path class="kmtnakxmc"/><path class="zb1sv5vhf"/><path class="cpe05h04h"/><path class="g63dv-bhd"/><path class="d69xa4boa"/><path class="utmpaltcp"/><path class="w9yden4py"/><path class="qo3ma9m9o"/><path class="tl0l56b0o"/><path class="ua9p4wy1n"/><path class="w1sn9bfdj"/><path class="ql-cdrcll"/><path class="n12ynnhcg"/><path class="jc71tbc_a"/><path class="tdsx5cc0r"/><path class="lppzmcbbe"/><path class="clnjmob4i"/><path class="ineo7w95a"/><path class="dvgeovbah"/><path class="ejyiun1bv"/><path class="c3wwmibtc"/><path class="qeq435bvi"/><path class="o_6xrvb0x"/><path class="q5as__bxw"/><path class="ikm1buewq"/><path class="l5dehzbcr"/><path class="e0r02geid"/><path class="raxe8p1bg"/><path class="axj98czua"/><path class="jrf8t1s7v"/><path class="s9q-i_b0t"/><path class="ulrvp1jlp"/><path class="pf19phb4l"/><path class="q14ing_fl"/><path class="bg6oe_b7z"/><path class="j4z65kfgm"/><path class="b_h8-5blo"/><path class="wsasa4v4o"/><path class="sx0vsbndx"/><path class="nt7979uzu"/><path class="m1tw27b7y"/><path class="kom8g24id"/><path class="t-t8tmkzu"/><path class="r7950ibce"/><path class="kytyn-b2v"/><path class="kwea5o2si"/><path class="kv-d9bcwk"/><path class="wl9ul95wm"/><path class="y7qumyb5t"/><path class="kqc3j1bfm"/><path class="dcjdd5bkk"/><path class="tpkjppb8o"/><path class="ekv47kqad"/><path class="lm_qs_bil"/><path class="dos_6w5ko"/><path class="lg7-ngmxl"/><path class="myvlpbcse"/><path class="owot6wbjm"/><path class="b_idic5-g"/><path class="wl3upcbqp"/><path class="ene1ivdfd"/><path class="ypk88-e-g"/><path class="p2mp-nb2h"/><path class="f26-uabtd"/><path class="hxze3nbbr"/><path class="ipz_uobrk"/><path class="q_01x1bab"/><path class="qdnsnfm9f"/><path class="rjpb_bblc"/><path class="j0up9-43d"/><path class="fhflvabxh"/><path class="ukudhhbtu"/><path class="nrf7-wr6g"/><path class="tmbo0cc3k"/><path class="k97oc4bjl"/><path class="u4nf-2bss"/><path class="gjkxqzbgj"/><path class="d6h6wu6xy"/><path class="m7siesb2d"/><path class="whvrnn94q"/><path class="bz89blbar"/><path class="mnz2qqa8e"/><path class="q9b9lofvl"/><path class="f7rsyybvf"/><path class="g6x4-r_3s"/><path class="eoivvzb2n"/><path class="apndpf_9y"/><path class="l080d5bul"/><path class="nip6xf8bm"/><path class="kdspfobbj"/><path class="kk69x36jj"/><path class="ys9axjbtr"/><path class="oens0lz2l"/><path class="natp48nfi"/><path class="r5w-3dfsi"/><path class="ci8ndod_i"/><path class="fhcnljbrp"/><path class="julxds68l"/><path class="h9_cvc-6y"/><path class="d_319_icz"/><path class="n6zdbmw0p"/><path class="r2bm0obje"/><path class="ppkzmsbvl"/><path class="qid-20brd"/><path class="gugjgus4h"/><path class="trt712bfz"/><path class="ccyrqebko"/><path class="lozw96b-x"/><path class="hxooqybfa"/><path class="i98auobgl"/><path class="g4gjhcdht"/><path class="emxa6xb3b"/><path class="p539njbwu"/><path class="xwa2_q93i"/><path class="aro-bqbln"/><path class="qr75_l-or"/><path class="wk2sl56nx"/><path class="xlyvrebax"/><path class="m__thhb4d"/><path class="xpyzskl1j"/><path class="l--ts0__r"/><path class="a7zyb4boh"/><path class="ti8rmjl_d"/><path class="y0rwezb0g"/><path class="bu1qoybxe"/><path class="l5bn_x8vw"/><path class="bskmz77gf"/><path class="n8rzw6btl"/><path class="oscqbqz6j"/><path class="ky7745xtd"/><path class="sm7h5yb3m"/><path class="hjc_39loa"/><path class="b4mz_hbgb"/><path class="y9n9338ei"/><path class="wwifklb_k"/><path class="v5k4n3bbq"/><path class="tyfr_5_ll"/><path class="r4rd3ibkn"/><path class="cbewpk44i"/><path class="exqep2mos"/><path class="kueof3b6m"/><path class="lvz7-7jqq"/><path class="jhh8y4nnm"/><path class="hymz0obbf"/><path class="g_lhmpbtc"/><path class="ql7yi7t9k"/><path class="rxcyi0wmy"/><path class="d3sma-bgo"/><path class="r7ap8eb9b"/><path class="zt6c4w44e"/><path class="k14ni-6qh"/><path class="bvp1kgbyp"/><path class="v428yvbme"/><path class="oocvj9b6p"/><path class="nvq7v4bwl"/><path class="zaqd45bfy"/><path class="njglbqjte"/><path class="ch2jcpbir"/><path class="f5qmow0ws"/><path class="l32klr8vs"/><path class="d7oeic-qv"/><path class="o4o7odbov"/><path class="rfzvatbxg"/><path class="z3v69m53v"/><path class="lkryhxbtj"/><path class="muqcjuc8c"/><path class="icg-pbb4y"/><path class="waqkbyo9f"/><path class="aapazeb_y"/><path class="l_282-b-e"/><path class="auzjhrbuz"/><path class="o2hdwfefx"/><path class="eza8gwbpo"/><path class="u2efv1sti"/><path class="e0ptin9qv"/><path class="ttudnrbja"/><path class="tdd50zpoj"/><path class="b8x2wqbvm"/><path class="ur6lxdbfo"/><path class="wmp_u9tta"/><path class="zffekz1xy"/><path class="se92-3bbj"/><path class="kuxs_cb1y"/><path class="bfsbhkble"/><path class="aapvf8bui"/><path class="y3aj6uaid"/><path class="w00-bxqgj"/><path class="eb6a1acrc"/><path class="mrp3mybik"/><path class="qno6rgbyl"/><path class="g0kilbcer"/><path class="boknrcb3w"/><path class="i64fuqbsg"/><path class="bsb-5kkaj"/><path class="u31savbyz"/><path class="esmzuccsx"/><path class="sm6xajuia"/><path class="zs0oeeb0e"/><path class="v-pi2dr9b"/><path class="nvojkccgj"/><path class="bls8vv53a"/><path class="on98lkb5j"/><path class="gsaeudbdf"/><path class="royja-36r"/><path class="qovu9pbfr"/><path class="zmqny_boj"/><path class="ix3b7gbja"/><path class="qdfqkz_ft"/><path class="o2g-4_meg"/><path class="h9tmqrb3v"/><path class="yb2dfnboz"/><path class="jscho2b2p"/><path class="zcq2jab8k"/><path class="havuhac8n"/><path class="xg7rohbpo"/><path class="yxv253byw"/><path class="cjy_9q0lt"/><path class="jnwfsrese"/><path class="n599heb3u"/><path class="lc8wtzbow"/><path class="o48gchb_k"/><path class="gk6k1mbhg"/><path class="pxot-v71x"/><path class="dj2d9bszl"/><path class="c0t1ahpkt"/><path class="v9fzo1bue"/><path class="g_n0mpqzc"/><path class="nhu-lbbni"/><path class="yepywjjcq"/><path class="lb7kdssru"/><path class="ilqj3c-gh"/><path class="qeteizbxh"/><path class="sdlnh548y"/><path class="n_ilg_b-q"/><path class="tzl_t88zx"/><path class="e5z2j3mpx"/><path class="us83zjb9u"/><path class="xo6qppbqz"/><path class="m2_svnbhj"/><path class="mhl_flbxn"/><path class="atwwlx8ko"/><path class="li814-b1p"/><path class="kex9pjbnq"/><path class="fwfl8dbcf"/><path class="kywmbbb-n"/><path class="b74sybcjz"/><path class="g9863-bwq"/><path class="pbxgwderu"/><path class="pphchom4m"/><path class="t2czzykqs"/><path class="f0d2u4byj"/><path class="nppcdrb7y"/><path class="eqlk1wbrm"/><path class="se7w7vb1m"/><path class="a030z-t0j"/><path class="xcyj0y_yt"/><path class="ja7t9li1t"/><path class="cngnhofbh"/><path class="yt6020b4c"/><path class="m1ga52bvt"/><path class="pr4xvyabj"/><path class="sfne46rmq"/><path class="xcjcd4tcx"/><path class="jrjsjg7js"/><path class="lvntxcg1r"/><path class="m8wv5gbok"/><path class="nu3vzpbaa"/><path class="f6msmvrfr"/><path class="gi3o8rblt"/><path class="j9t8q92tw"/><path class="boyou-b0o"/><path class="zhv5rt2ak"/><path class="e-9v3uenv"/><path class="m-wgc-blu"/><path class="r1u72-5fc"/><path class="pqrk3ybrm"/><path class="lwagyklhl"/><path class="fmh_ksb5j"/><path class="p2d_30_kq"/><path class="e2xb02__a"/><path class="gvwlibb2s"/><path class="tlu6zsezk"/><path class="r6kwnubbl"/><path class="vcog4ribb"/><path class="tc-kg5w1b"/><path class="d7qfdulqh"/><path class="mhvcg0a4n"/><path class="x0rl3hldp"/><path class="xepgp9xoo"/><path class="l2qqtcbvp"/><path class="vjtvunovd"/><path class="emdk3qb0t"/><path class="fudnhzbqz"/><path class="ir3mmsb-p"/><path class="tck4ebchy"/><path class="mg3_6ibku"/><path class="nb4jzybdb"/><path class="xpe_svbyx"/><path class="ighpykbpp"/><path class="n2df3wmto"/><path class="f-nz2tbja"/><path class="ahjpizsgo"/><path class="msu6hprvs"/><path class="caeoy6byj"/><path class="peq0n9bff"/><path class="gnybnlb_j"/><path class="f02__1blu"/><path class="uaygg_brj"/><path class="xyjj2xbuj"/><path class="bi_qll1_s"/><path class="o9v5vb9af"/><path class="mrw6rv_ky"/><path class="vbcoabmgy"/><path class="yxk73qt4x"/><path class="cnjisaclt"/><path class="wnoda5b7f"/><path class="g1y9ietro"/><path class="w2w89kbmz"/><path class="woovunb2v"/><path class="aeaz0xe7v"/><path class="eu4bu-b7d"/><path class="hp8pvab3z"/><path class="zn0kc5kox"/><path class="ww3xi171i"/><path class="hs0wmxwcc"/><path class="mwq05dg0t"/><path class="j6x5lcj2x"/><path class="obsqmwbwg"/><path class="r2nlx_2xj"/><path class="th4wovb4j"/><path class="x-tkjxbcf"/><path class="t_vntdbkf"/><path class="v20imvb0p"/><path class="yp8u6ccia"/><path class="dnq4_nb1j"/><path class="i-axlijat"/><path class="y7mpudbph"/><path class="twnnxcc5o"/><path class="c840mtb_o"/><path class="fl0q8vb5t"/><path class="a-npn_12b"/><path class="c-1tmfb6w"/><path class="rq_ui2dao"/><path class="d8brrqbzh"/><path class="se7mylbpo"/><path class="j50xc_bko"/><path class="oyzmxfaib"/><path class="ui07iha2h"/><path class="lumud9bud"/><path class="xg3iss5me"/><path class="s3-voqbch"/><path class="g3p6kyb6g"/><path class="wl9h40b4f"/><path class="fmse8ac2l"/><path class="v7-qxjtse"/><path class="wan7q5ihd"/><path class="zyxnovb-p"/><path class="qpc8d747z"/><path class="f65ouwbhd"/><path class="qawx19b8a"/><path class="glz1o9bhv"/><path class="t-982-xpn"/><path class="v_1iftbru"/><path class="v8hjm14qq"/><path class="ce4wnmbnf"/><path class="eekkmqouf"/><path class="pwfelrb-r"/><path class="e55iqcc6j"/><path class="od0-pzbpd"/><path class="nnkd2vlsf"/><path class="v0fdxxqmc"/><path class="e5le-7b3y"/><path class="gycoizcoh"/><path class="thdo36_pl"/><path class="jozzu8yfg"/><path class="l37hbopml"/><path class="u8nouy24f"/><path class="iwy-skbrf"/><path class="oxfx64b9c"/><path class="s5kqleb_s"/><path class="n4u2sldsp"/><path class="nu8k99d-t"/><path class="b2hw40b6c"/><path class="os13aehhv"/><path class="zkv5td-0l"/><path class="nom4_dbth"/><path class="qyr0qk75d"/><path class="c_odhp7ro"/><path class="yeu9iibat"/><path class="grxa3cxpg"/><path class="d3-lhso2l"/><path class="ge3euccqh"/><path class="rde0jue6p"/><path class="xtxtshmdd"/><path class="guy1cykhz"/><path class="g5ja8sgfh"/><path class="peuiumbaz"/><path class="nlzfe8bdr"/><path class="ctlio1b1q"/><path class="xcffumbgm"/><path class="yto2k4b1p"/><path class="qt47uoa8w"/><path class="yu6hz8fzo"/><path class="m30y1tb_m"/><path class="noqp1acee"/><path class="xerd80bon"/><path class="f7fw0gb8x"/><path class="n_-427bii"/><path class="doo4ozbdr"/><path class="g7w-hkbwq"/><path class="ne4elyawu"/><path class="xkpgi9m-t"/><path class="y7pyh7xui"/><path class="l-pw-1twc"/><path class="g9o3dtmkl"/><path class="gj9c3nbwb"/><path class="v523egb-y"/><path class="c44cye-9v"/><path class="ty07ssu8k"/><path class="w6_cgz78h"/><path class="e3rxfcxlz"/><path class="ybblv5xvi"/><path class="zkpmg2b5u"/><path class="ldzq1jbwq"/><path class="tjroydayv"/><path class="q1degtlti"/><path class="en2na0_dd"/><path class="r3mfqrbkn"/><path class="ynhlnj3-j"/><path class="i0ts8nbxc"/><path class="lz0py7bam"/><path class="z3euofbwm"/><path class="x6nr44z8b"/><path class="qq94-ybgm"/><path class="dcmrgsblr"/><path class="u9_0c8b9n"/><path class="pq8tmuphs"/><path class="kklh8vbzd"/><path class="kqi-sgjiq"/><path class="lovmngw6u"/><path class="gxgf65bel"/><path class="o3iidhbqk"/><path class="fetu4onyp"/><path class="mh5sp7bbs"/><path class="pqwgh83iv"/><path class="tne677bit"/><path class="mc2hy7b8t"/><path class="jhku1t4yq"/><path class="jky4oybmq"/><path class="w_uuhvb4j"/><path class="u9mwcrbto"/><path class="zte4e24tr"/><path class="pkg5nwb7t"/><path class="qurgtmvti"/><path class="elcadtb4b"/><path class="tah9_4f0a"/><path class="bfuxpebqv"/><path class="m_8-hor-v"/><path class="zvlz_lb6z"/><path class="p-jb-9qmg"/><path class="kq_nf8jek"/><path class="xpko25byx"/><path class="y8jze_y7f"/><path class="i-b59gbeb"/><path class="pq2hg6bpx"/><path class="cf3wgj0mz"/><path class="a6sj1cber"/><path class="f10k4db1y"/><path class="yykj79bie"/><path class="cg1dn3fcp"/><path class="c5o45cbwi"/><path class="u9-n88xkv"/><path class="clnckdzbs"/><path class="p_qrgzeel"/><path class="s8nv5mb7z"/><path class="r30y1ybdc"/><path class="q1aybvfdr"/><path class="o1ll1gg5p"/><path class="yxccbqbih"/><path class="s2kxr8t-m"/><path class="qlpm9kjaz"/><path class="cmld1syoi"/><path class="faz6lcsny"/><path class="oxivalb-b"/><path class="xmeeb1o7c"/><path class="c6mfnfbnn"/><path class="att4r1bkx"/><path class="tt3k88b9y"/><path class="s6cpo7wjv"/><path class="x7c_bd3ri"/><path class="izxaivbko"/><path class="x118l2bct"/><path class="nc-s9bb1e"/><path class="lfhdvxfkc"/><path class="qs7m63bll"/><path class="buat5obco"/><path class="yivinlbxq"/><path class="u7m8vb_iv"/><path class="vpv46vbaf"/><path class="rt9ribclk"/><path class="y_n0aughh"/><path class="s79m0ecuh"/><path class="m2vnq4o0y"/><path class="aqaz5m_xp"/><path class="ftizocckq"/><path class="rmem1le2l"/><path class="sxags2tbu"/><path class="vdk90thti"/><path class="xg88u1dih"/><path class="jxbrqh6vi"/><path class="wzy--or3w"/><path class="nh65xabgw"/><path class="dp3ka606d"/><path class="sw1ufxbds"/><path class="j1zqdlwqn"/><path class="o0aqgtbqw"/><path class="vnc3l98xr"/><path class="z_n0bibyq"/><path class="rtlw4dn_k"/><path class="qx8gedcud"/><path class="y82nh--tu"/><path class="seedbv-1s"/><path class="jdienobkm"/><path class="au-_0abco"/><path class="b4hvjk9re"/><path class="xkrerdbuw"/><path class="pa91reufw"/><path class="fcz1wig3g"/><path class="ry44nabmj"/><path class="kyf5-c6iq"/><path class="n1qmn6ohe"/><path class="k6fwg6brn"/><path class="n-b00hf-w"/><path class="ixzoc_x3h"/><path class="cf8lxshki"/><path class="y2nvsub1j"/><path class="ve3prbc4z"/><path class="yonewwbsp"/><path class="hso7a-b3h"/><path class="s8zlooseu"/><path class="rcp5m8bce"/><path class="n66n2badu"/><path class="pt7w5ub_p"/><path class="sqlvo41pc"/><path class="orz3lybfw"/><path class="e15t5qn0y"/><path class="oe3hyjbmf"/><path class="ldzp7rbir"/><path class="z6m09956l"/><path class="wnfi42bew"/><path class="sjy2awskn"/><path class="thp-x7b4f"/><path class="ml_50_b1q"/><path class="tfp9mdb0h"/><path class="jlmccccbi"/><path class="v96flotlg"/><path class="k3ljqnnlo"/><path class="j8jo8sb-f"/><path class="y-gwllb8c"/><path class="i0kt-7brd"/><path class="izvyfibrn"/><path class="y3c3n7bhn"/><path class="mkqc2zb3i"/><path class="t68mwrngk"/><path class="zzr7_1bvf"/><path class="lkkbgrbsi"/><path class="u_nikacpk"/><path class="nnrj4vv-w"/><path class="wdle_vbot"/><path class="lwxaz4buy"/><path class="qxftbkbzd"/><path class="zso23li_q"/><path class="asupdzcof"/><path class="vrger1bnu"/><path class="yqmm87tod"/><path class="micyotbnj"/><path class="vglqdfbgi"/><path class="ex0-pabsy"/><path class="mwj95lp6j"/><path class="azl9nhn-r"/><path class="u82h67bnw"/><path class="v_oeei1ck"/><path class="ngo8kjb3d"/><path class="qwqewpnyk"/><path class="h3rntac1y"/><path class="xw9ce4o5g"/><path class="smf-mmben"/><path class="oj8d_7a3q"/><path class="zw8cbybna"/><path class="wqwfq-bfo"/><path class="kx6romb_h"/><path class="h-zgmhbsm"/><path class="w-uxh5bhm"/><path class="dhzyxlbgq"/><path class="pf07uqvff"/><path class="zg7_6dpzu"/><path class="xdimn6utz"/><path class="h5lhmnbvl"/><path class="rvunwk95y"/><path class="rc3h78bbk"/><path class="y4-5dnbdh"/><path class="ofvzhublg"/><path class="o-1gk6b-m"/><path class="ocxuj8beo"/><path class="y4kbnacry"/><path class="sv8s86bdi"/><path class="qfn4j0biq"/><path class="xi884fbxc"/><path class="ovfy7abnk"/><path class="u5dlvkb6z"/><path class="xy_9uvb9f"/><path class="myvi7ocyf"/><path class="tbrqn4xcu"/><path class="snwfetbnc"/><path class="sk9ri61_t"/><path class="wq25_8b1t"/><path class="skis1_b7c"/><path class="xeha01y2w"/><path class="tbpge7bzh"/><path class="hazo93qod"/><path class="en6f234gh"/><path class="af1a1gb6e"/><path class="x9al4cb3o"/><path class="mro10pbtr"/><path class="xzs7mwb4v"/><path class="jrr200bwf"/><path class="mirno0b2g"/><path class="xutshwblt"/><path class="uxmatlb6d"/><path class="tu26svptj"/><path class="vwwrqbblq"/><path class="vlq1s5baq"/><path class="nb1a14_qe"/><path class="x2gr-omvx"/><path class="cxkgpsble"/><path class="rf3aeh2ld"/><path class="hjtplecca"/><path class="jpt0fdvxn"/><path class="k4jzu-b1r"/><path class="tyayqvrij"/><path class="wj_vwvb_t"/><path class="mg5mrsjkg"/><path class="rmh1_36ca"/><path class="whw13eqzl"/><path class="edebdu_jx"/><path class="yfwsisbek"/><path class="z48m29r-p"/><path class="ykt835rth"/><path class="g9krq2b4o"/><path class="zfubapbfb"/><path class="zl5ll9b3z"/><path class="qawy6dbmc"/><path class="hzlw5qckf"/><path class="u0nxbc5fy"/><path class="qp3dxzb8s"/><path class="felnpf62j"/><path class="uc32hj9ot"/><path class="b69hrf7nz"/><path class="a8-8-59sp"/><path class="bbkysfb_e"/><path class="sdkk7td4w"/><path class="micxxbcle"/><path class="ba44mob3o"/><path class="i4n430t2t"/><path class="hhotmhb7g"/><path class="xqfribb0i"/><path class="g-ymyhbrl"/><path class="laiuo7pyc"/><path class="mwuorsbln"/><path class="pgt7eacjv"/><path class="ogg4m9b6r"/><path class="x5h6g2x2j"/><path class="aytwdmykc"/><path class="rs12-5w_c"/><path class="o7v22obef"/><path class="pbo8zm4aw"/><path class="fqb5aqb4c"/><path class="co4lown0e"/><path class="cz7mp5bfx"/><path class="f-r0jhf_m"/><path class="ei7je-spp"/><path class="g6b-vwell"/><path class="xpm1--bnp"/><path class="n2h1mm-qd"/><path class="stslcnb2e"/><path class="rdj3-pbod"/><path class="x2apdee5z"/><path class="arijg5egl"/><path class="n437lcbjv"/><path class="vburc2b3x"/><path class="jmde5n95f"/><path class="pc-n2pect"/><path class="bl2nocbcd"/><path class="n-dxnj2mw"/><path class="ioogmcb3u"/><path class="mbfsz2c7l"/><path class="v8b-3hbgn"/><path class="dw9ax0q-r"/><path class="co71aebxe"/><path class="o9us89bdf"/><path class="w6w3e2bkb"/><path class="ntcj6opho"/><path class="twsxl1b8d"/><path class="gslwzueki"/><path class="buf4h7bjy"/><path class="ssu31jbez"/><path class="f4l5f17pi"/><path class="r5pysqb7k"/><path class="fl8-45vrg"/><path class="v1wm6ccmb"/><path class="c7haj4_uc"/><path class="l7_i3qbmv"/><path class="twcq74b_v"/><path class="wx40dwb3k"/><path class="e-ntnpbum"/><path class="j5lma7bcc"/><path class="s56t2j69h"/><path class="tkz06_b-b"/><path class="sg5c5cboo"/><path class="j4mb4eb7x"/><path class="g82hed_zo"/><path class="gv_egqb7g"/><path class="ydh626t8v"/><path class="kgralkddj"/><path class="silj55bmy"/><path class="sjr0z3cbl"/><path class="yhrl4sg7f"/><path class="t8o5ombwv"/><path class="i7fziq1gc"/><path class="qm1_kp9yd"/><path class="pgj5s131j"/><path class="xeoklhbxw"/><path class="td8ebjh7s"/><path class="sd_o4qbcs"/><path class="z9j66i3ie"/><path class="yubxbbcmi"/><path class="k_wg8zb-r"/><path class="dpr6qrwwj"/><path class="wqc1dz54w"/><path class="fughm-bei"/><path class="j3dfw60la"/><path class="tjjgvxuif"/><path class="qpn6fbcbz"/><path class="a3bvcxost"/><path class="zuxdprhmw"/><path class="eq1mkubye"/><path class="y4fg-9beh"/><path class="masuv7bal"/><path class="g97wi4bqq"/><path class="xwcl2lbev"/><path class="dn0qm0xwj"/><path class="u9ffolb5f"/><path class="a7_vecsin"/><path class="xsdaqnc8l"/><path class="do35dlusd"/><path class="x1tmo-fxy"/><path class="k_wpgbbhe"/><path class="c7dxh7bkr"/><path class="pa1a9ybqf"/><path class="accyaqbzt"/><path class="a33r6pbfk"/><path class="lel_q4bxy"/><path class="edhob3bzy"/><path class="qvw_qqbec"/><path class="rddrk7k7g"/><path class="jw31q-gpt"/><path class="csvfvwb2i"/><path class="ymt1nvjft"/><path class="sgxg7u14c"/><path class="lekvs449w"/><path class="fjawgdbgy"/><path class="r5rcznbmd"/><path class="yvhmznb2w"/><path class="rt7vhw_vw"/><path class="r5x-i8b1q"/><path class="qhetpibuc"/><path class="ovzhilbka"/><path class="ftwbm6_hh"/><path class="wfe6b138a"/><path class="ysk2c7qqs"/><path class="d408nrund"/><path class="atl1550ak"/><path class="yqplbv6ji"/><path class="y7o8gtwlv"/><path class="k6fhbx82h"/><path class="ixq6gd6ip"/><path class="mo8j5fecn"/><path class="jmig4gbla"/><path class="ga7053__c"/><path class="o3x5l04tx"/><path class="hihm8jbsm"/><path class="zky7uibwb"/><path class="vm0c42bon"/><path class="w84_vdjvy"/><path class="y-2xx2scb"/><path class="r9vpyqb0e"/><path class="f89etr9_g"/><path class="o2-bgcj8h"/><path class="o82ssjzjm"/><path class="gcmbbycuf"/><path class="hchsjjbwd"/><path class="rilb5ubhs"/><path class="zkoq3hixe"/><path class="nr0y36lst"/><path class="d2or80s6m"/><path class="hle59yb7z"/><path class="wcnz-yu3g"/><path class="zp3pucylr"/><path class="k7u_7djsx"/><path class="fbvb4wy7n"/><path class="ylr8stb3v"/><path class="znocqxb_m"/><path class="t8_m_7b0b"/><path class="g370__4ea"/><path class="tsiubdecw"/><path class="kep9rg9xr"/><path class="se7c1ybbq"/><path class="x7keotbtn"/><path class="vq4fl3bph"/><path class="xbt06cceo"/><path class="cdf3thu-c"/><path class="imxan-bvn"/><path class="euhsm_b6c"/><path class="ws6jr_-nr"/><path class="g6mdwdjpe"/><path class="xtcdpyb4a"/><path class="iigoktb4t"/><path class="uiexx2beg"/><path class="bgnapjb2c"/><path class="q2fverbhn"/><path class="hnylsz7oh"/><path class="g8rzfib8r"/><path class="m8-i5hbij"/><path class="t17z4dbme"/><path class="r6xvho_tx"/><path class="p1cl86osg"/><path class="v20s_0zpp"/><path class="jul151_sx"/><path class="wkhzgeb_f"/><path class="yildnbbfx"/><path class="z7p_f272z"/><path class="uuj3ybbjy"/><path class="ssbb2crnc"/><path class="wgk10_b0s"/><path class="t0eurwbxs"/><path class="o9-qxbart"/><path class="t8bf0-n4q"/><path class="oapu1rbwu"/><path class="guji0t-wy"/><path class="ded6qnbxh"/><path class="l-wvzrbnr"/><path class="zdm6bfbzv"/><path class="qlvqurbyn"/><path class="ma6mwgawn"/><path class="s5awhrbme"/><path class="qz45ivzlo"/><path class="gyns-panl"/><path class="xp5_tl-wz"/><path class="fki-m1bak"/><path class="npjglt63b"/><path class="gz5j8n0dy"/><path class="a88xpkb_e"/><path class="ds0sw6r1l"/><path class="cu0pgu12f"/><path class="ghai5fbmk"/><path class="pjle0moxi"/><path class="osjmhxttr"/><path class="z6yj58bvm"/><path class="hhlxddb4n"/><path class="vsgitfual"/><path class="nmqvy88du"/><path class="yxxn1u1gn"/><path class="jb8rqbcgy"/><path class="q732x9shm"/><path class="pppccm__m"/><path class="lwfd9iixy"/><path class="yj3s_5vti"/><path class="mgzgf4bwo"/><path class="y9zcelbri"/><path class="v6n28ubvg"/><path class="b_qbn5b4p"/><path class="p2rfsenpg"/><path class="sx1q7gari"/><path class="b3mqvbcsh"/><path class="ea22wimoi"/><path class="b7k-lo26y"/><path class="mfj4b9baa"/><path class="cfo67fb-a"/><path class="g3umo7byz"/><path class="vjaukgbth"/><path class="tlzpnbcpw"/><path class="gr6c_xt_x"/><path class="t1zywotsv"/><path class="z936i5nlu"/><path class="yc73ospth"/><path class="e0t69tb3j"/><path class="z_u1skmvg"/><path class="q9fr5_7bd"/><path class="w2a27fbbn"/><path class="dwqy3y2ih"/><path class="sqwztpblp"/><path class="h20t7ob8s"/><path class="ypbgq-bsa"/><path class="d5_wa1b9q"/><path class="vxn678bdf"/><path class="i23f5dblv"/><path class="fpuymd4fz"/><path class="rid_6eseo"/><path class="z85depied"/><path class="ftqd79b2q"/><path class="b05xozbzx"/><path class="jg7ivhguy"/><path class="zq3f-xbmz"/><path class="lyk4j7opq"/><path class="ymq1fdb5o"/><path class="o3v1c0biq"/><path class="v9tjlspyh"/><path class="xwzvrddkf"/><path class="urro_2bys"/><path class="bm8d03ycl"/><path class="psaxjdbmp"/><path class="ypotnublz"/><path class="aybrowbbu"/><path class="sd699gvud"/><path class="qg115pfyq"/><path class="c77lvwqlp"/><path class="mxetps57l"/><path class="ifhvovb6w"/><path class="axbqzob5x"/><path class="e3u_2oe3s"/><path class="mhhbxtvjl"/><path class="skxhi6b6n"/><path class="gzxnigk2t"/><path class="jq_lweb4n"/><path class="scpde1bun"/><path class="m1ovgobjq"/><path class="wbqyupbeo"/><path class="s9-4uac0g"/><path class="z31kh1-xf"/><path class="koivsuaph"/><path class="hu8qbjo6i"/><path class="b56pa_bhj"/><path class="r2kkcub2b"/><path class="ib4xelblk"/><path class="gvmaw_3mu"/><path class="zy1jd49dl"/><path class="qx3qrmn1e"/><path class="ukhet845k"/><path class="deqq54bka"/><path class="zf37wv0qn"/><path class="h9uhmundc"/><path class="wjfxevbrz"/><path class="klnnhkgij"/><path class="ovh13qbmg"/><path class="pu_6b5b7p"/><path class="c1o3xcb2e"/><path class="kgti05bvk"/><path class="y78wu3bau"/><path class="wieat5btn"/><path class="id291acph"/><path class="m06c5ibxl"/><path class="lo8x96bcd"/><path class="n4x-r5boy"/><path class="z8hebib1m"/><path class="mryx-2bzy"/><path class="prhfhzu4u"/><path class="du8r_gb4j"/><path class="x38ly3--h"/><path class="pcmb12b-c"/><path class="j1vh83qoa"/><path class="qm-v0brlp"/><path class="twewtbbsk"/><path class="jl_f_sb8d"/><path class="a4glwe1zo"/><path class="x77d_qb6o"/><path class="n91r8q-8i"/><path class="oadv6ccwg"/><path class="bnhv__bay"/><path class="bjgawrbhm"/><path class="wvpsi8bfw"/><path class="pahj0lkhg"/><path class="krrz8rx_u"/><path class="d0_f311zg"/><path class="oz336zbhh"/><path class="v_fgt4twr"/><path class="qzopv5b7s"/><path class="n-snanbdf"/><path class="etvdfhbph"/><path class="d_bju848y"/><path class="uwz4c0b8w"/><path class="fvhx6bbyb"/><path class="oriaw-alp"/><path class="hw6z27btn"/><path class="c6x5cix3g"/><path class="ukkol-byd"/><path class="x95h37_rc"/><path class="oeqfoccrc"/><path class="v2i417b5f"/><path class="c-urjnc9l"/><path class="xoq4i3ban"/><path class="kh_7j1b3v"/><path class="wv1g3yb3c"/><path class="anoe64bcd"/><path class="k8c73abuk"/><path class="g7lmr-qnm"/><path class="h9rax1v_b"/><path class="w8a9xf28t"/><path class="vatjsig9x"/><path class="gretulbkn"/><path class="cafyklbxa"/><path class="okleb4bke"/><path class="zjn33cc5z"/><path class="v_o1x6bol"/><path class="n0eq0ox1v"/><path class="j69z_obhq"/><path class="lr5jyybut"/><path class="m2obo7bie"/><path class="dm4-qbbfn"/><path class="u3tnpbb6y"/><path class="to1ptoqrc"/><path class="f6gknp6td"/><path class="nyttg81ke"/><path class="fwzvds90b"/><path class="vkkancbyj"/><path class="f-dzhttsf"/><path class="atdb0itts"/><path class="pa26eeojp"/><path class="hvc4zzb0v"/><path class="wf-fs4rxe"/><path class="tt_jzgrnv"/><path class="ilsp4419l"/><path class="io4a3ubka"/><path class="xy_x-ebji"/><path class="dafytx-ul"/><path class="csqnleb8k"/><path class="g_21afbhy"/><path class="ivl8-ubzw"/><path class="rz2748bpe"/><path class="z9h4ubn6g"/><path class="m4v7wwbzv"/><path class="sb58i4bxt"/><path class="aps864bfo"/><path class="msl6mjbuc"/><path class="neh2msb4j"/><path class="imypjly_k"/><path class="d0-t6wble"/><path class="i5nfjrmsc"/><path class="a00rko8rx"/><path class="ekde1ebms"/><path class="l94qh7btl"/><path class="mh-d-kbkt"/><path class="k23chtw5u"/><path class="gkfmtkx2k"/><path class="by9ndtbon"/><path class="dcaembbtf"/><path class="xdf3k3b1g"/><path class="hykzxfxie"/><path class="uoil_cntr"/><path class="xmvtafbjl"/><path class="ps276ibit"/><path class="em3sm369q"/><path class="x_24filih"/><path class="wydmfufbl"/><path class="hvx9a8b7h"/><path class="fa4h7yw5a"/><path class="vbp6hqbbe"/><path class="k5ugq8crb"/><path class="l8n07j3pq"/><path class="ngl4solrz"/><path class="pq6lg9yhm"/><path class="yuwlm6vrj"/><path class="e7-qrpw2k"/><path class="juntz093y"/><path class="cs3kq-bgc"/><path class="bvgb68t6u"/><path class="n7s1vjk4e"/><path class="za8r20b7g"/><path class="wsa7m8b4z"/><path class="k9e5152sc"/><path class="p0utwzucu"/><path class="opgk7pbtg"/><path class="oes75jiop"/><path class="lu4vewekp"/><path class="rtuk4obkl"/><path class="karoycciu"/><path class="w78wgzble"/><path class="o30hlqb7r"/><path class="uljj2obmv"/><path class="p0g2zn8_g"/><path class="s0s4e8bzo"/><path class="dzbm3-bbv"/><path class="qjlrywbkh"/><path class="yu8ac25vg"/><path class="fxn3-gblx"/><path class="lksj1ac8r"/><path class="zlg-4toem"/><path class="zdojf3btk"/><path class="m87wvacyk"/><path class="wjxgh0xps"/><path class="k3wg5wagr"/><path class="f6mrp_zdo"/><path class="a8qgidnyc"/><path class="l52ddd4cj"/><path class="s0cc2_bac"/><path class="lfwksjb3b"/><path class="qhv-akupd"/><path class="yd47qfbbm"/><path class="kl0ktj_yb"/><path class="nmz1us2mi"/><path class="pl4amcc9r"/><path class="ql0hd3r5w"/><path class="opou4sbfu"/><path class="pst57xbzs"/><path class="uu1kcktnc"/><path class="y5cmhjbkd"/><path class="crgtr3bjc"/><path class="lhikjmbkn"/><path class="ql8xdw13v"/><path class="dca_i_61d"/><path class="eu8iuvbzk"/><path class="n1ws18a6v"/><path class="evf_aqbnh"/><path class="d81k3i6tm"/><path class="d9m54ki2j"/><path class="abq2vv1xk"/><path class="epz9n4_dc"/><path class="et9qypaak"/><path class="bibi__bgi"/><path class="u36qui8_o"/><path class="yklofdewi"/><path class="xah0-8kpl"/><path class="j_o7kcz6x"/><path class="n5zavng6d"/><path class="n07j8qott"/><path class="g_t8ambjy"/><path class="dgms6fbau"/><path class="kdvfzzd_y"/><path class="g80qggulx"/><path class="ymsz-hb3x"/><path class="y4bocf94d"/><path class="bhj4pebuk"/><path class="t0-x_-b4j"/><path class="oper2n_en"/><path class="fmld6xb9x"/><path class="gm2y46bek"/><path class="lhbx-5brt"/><path class="t0eqj8bep"/><path class="s2j-t2c0l"/><path class="zmghlac7w"/><path class="xduq_7bqn"/><path class="ic8xg7a_p"/><path class="e_mm-vgsf"/><path class="qbzwm5b6a"/><path class="h0pk-5bcc"/><path class="sk_6173jv"/><path class="v1qbqfb4k"/><path class="an6hd-9at"/><path class="rjuq9gb3z"/><path class="yy2iofbig"/><path class="zgl22ib6m"/><path class="q0md_obwc"/><path class="l9-hb2rbc"/><path class="u6-wo81bc"/><path class="phhescbxy"/><path class="yxwmk8b0j"/><path class="ot9lr7b5a"/><path class="u6hh95buu"/><path class="qf0n6z6vo"/><path class="djj4lcd6z"/><path class="rbm0rrbza"/><path class="dkg9pdb3j"/><path class="od-7qnbig"/><path class="mq4dxu5jo"/><path class="p4macqb_r"/><path class="a8zjwsbrp"/><path class="jksavccph"/><path class="he1h0wrgf"/><path class="eqyrd4bya"/><path class="pprso5zoq"/><path class="afju6jbll"/><path class="cre4sgb9u"/><path class="ny1tjczol"/><path class="vr32zf7cj"/><path class="ktdhs7bsr"/><path class="ciz7hj8dw"/><path class="p3jouy65a"/><path class="fhb8aobmv"/><path class="r86k-tbem"/><path class="sb4l-rbbh"/><path class="rspjlf97a"/><path class="i1b2g0blv"/><path class="rf1n01ejg"/><path class="q5yhnt7nw"/><path class="l9qmp48vl"/><path class="poa8uqb1c"/><path class="jtinubb6t"/><path class="qtlpe_94w"/><path class="sc7ekkbnr"/><path class="e_z8ypj7u"/><path class="uf55unb_m"/><path class="v9rru0shz"/><path class="f1_1b1b4q"/><path class="hmtdxlbuk"/><path class="x7p4e2f-b"/><path class="y9zaxubxw"/><path class="nb43t_bka"/><path class="hxnc_chfo"/><path class="n5mn7acac"/><path class="vo9smtemj"/><path class="vkky7-bfh"/><path class="q6p7pwven"/><path class="u1g3hxbnq"/><path class="o37t_kbxf"/><path class="ft8fn5bpj"/><path class="bt87hkldk"/><path class="aihq-8o7d"/><path class="a3-2tvbes"/><path class="euz6uobud"/><path class="ca0_3cbzt"/><path class="f6wabpldx"/><path class="wmg2s8b9b"/><path class="zti36gbgw"/><path class="u1q624-yi"/><path class="umrx_vbwn"/><path class="d648sm7ei"/><path class="r7sfikbyj"/><path class="ex4cy_b5m"/><path class="h8w3ypm0d"/><path class="p0riuvzxe"/><path class="htjuz5w_y"/><path class="rtt8k8gsq"/><path class="s0j0hml3r"/><path class="evkhaytlf"/><path class="op5d61b5h"/><path class="ctwsvwrwn"/><path class="hnvjbx_1u"/><path class="od-844bvu"/><path class="txyqhu74v"/><path class="wzeq6zb9t"/><path class="rh5jxei-a"/><path class="fnry4ubbk"/><path class="b8x2vrm6l"/><path class="ksz8tvc2r"/><path class="ylk3t7bke"/><path class="jw1fmi36a"/><path class="bwg_n0b3l"/><path class="apnkiwvvf"/><path class="ag6qvubhw"/><path class="o7qx2-ahw"/><path class="cd8m28mgg"/><path class="bfhbpvb9p"/><path class="jcv1aqbys"/><path class="r3msrlq2i"/><path class="rok7wrb7g"/><path class="ss3wxcbwc"/><path class="evt1jrb_j"/><path class="o5hx_evlk"/><path class="ir_b1p5ct"/><path class="pcf10qbsw"/><path class="gsejf2toi"/><path class="vrw6e72ou"/><path class="dj4h6yj8l"/><path class="pwraisb5t"/><path class="asjbofbun"/><path class="zdjs1t3kq"/><path class="logqpub_g"/><path class="e0bw1ublq"/><path class="y-zg8bbfe"/><path class="vfyuzqbvg"/><path class="xsb5ygb1b"/><path class="lzhb6bcjb"/><path class="cpfghubrp"/><path class="d__sozo4m"/><path class="puj6qckaz"/><path class="p2_qirxkd"/><path class="s_vdbvp0d"/><path class="gw2casd5m"/><path class="zqa6ttury"/><path class="lwqzkih7j"/><path class="vreyosunj"/><path class="k4nuknbbc"/><path class="qo82f1o_y"/><path class="i-82zmbge"/><path class="o4yj6s_sv"/><path class="m3osfnbbt"/><path class="knf7zhxyn"/><path class="zcq1isncp"/><path class="fsaevebiu"/><path class="xe4o_abkn"/><path class="tqp9atbom"/><path class="t2a-f8bfj"/><path class="kvl4jts6z"/><path class="s0c2is_9k"/><path class="t55swsvts"/><path class="l8906tbnl"/><path class="o3i8tdrsp"/><path class="z2rbrunzh"/><path class="fdvec-92v"/><path class="aw3po2ldb"/><path class="khb835b_n"/><path class="qfk06p3tl"/><path class="yow9j8bfr"/><path class="og9fyvbwl"/><path class="k3fnyiz7f"/><path class="jpv-m8dlb"/><path class="h322q8o8r"/><path class="a-ap2dbic"/><path class="chk7pibyh"/><path class="gs0y3fbzm"/><path class="yw446n1ox"/><path class="dpx4wub_r"/><path class="e53bqon4a"/><path class="pie6u3bhz"/><path class="i8ltmwbwh"/><path class="ud_mfirtq"/><path class="kv0zr_bxv"/><path class="pqkm5lbdc"/><path class="xhz137o6b"/><path class="mglusmbnw"/><path class="c9-4ikbzk"/><path class="fos64bg-d"/><path class="xtowobcmy"/><path class="g5t8hdbik"/><path class="f9o-3kbzd"/><path class="a11cwjbqq"/><path class="pv64j4arn"/><path class="glddq-b6o"/><path class="ebc5c0ufy"/><path class="m544-qbys"/><path class="sz9f5obtt"/><path class="mzka65biv"/><path class="nvfkbv8hj"/><path class="d4csxzbmv"/><path class="jqxoguzft"/><path class="mwotuybmw"/><path class="ewhpcdc3g"/><path class="xljc6oayd"/><path class="nwptsyujl"/><path class="cwz_xqjwo"/><path class="pp4awyb2u"/><path class="z9nq5ab5i"/><path class="mz3f50brr"/><path class="rv4n3nc9r"/><path class="lb6djj_bv"/><path class="m4-l4ib8e"/><path class="tpuerz3ss"/><path class="y2hi2wbhq"/><path class="tv7s6acbe"/><path class="zwmk4bcml"/><path class="zo32_ebbr"/><path class="dng_lq5wb"/><path class="afol2xb1j"/><path class="itco-cblb"/><path class="fd8r1txsg"/><path class="irya3lbgg"/><path class="uvdfn1bok"/><path class="fg5lpt7fq"/><path class="g3p39r_1o"/><path class="vvx_e443w"/><path class="albjnp92s"/><path class="sypg0bbdh"/><path class="dwgaxpb2n"/><path class="cg-x_2xsm"/><path class="z98bvt-ao"/><path class="g9ub6xxka"/><path class="by26s31bi"/><path class="dopmecbpe"/><path class="tq_oysy5o"/><path class="cmd6sobvz"/><path class="k1ultnb3u"/><path class="ds8mj7btu"/><path class="f3jwynojs"/><path class="y41qtmgai"/><path class="xmk57ez-f"/><path class="c79net9cd"/><path class="zisoeyluo"/><path class="wqv71cb2l"/><path class="dk3snlbot"/><path class="x02xg3bjg"/><path class="d6a4jo0yi"/><path class="vgwsmlb8d"/><path class="l2dg7t5fh"/><path class="yt8gp5bjj"/><path class="qv3lcubah"/><path class="oj9tfabry"/><path class="mml_shb_z"/><path class="qbux6xces"/><path class="ds9knwb_h"/><path class="dtrcghb_v"/><path class="ulf-w7bxz"/><path class="s9w2hcctf"/><path class="clq_wc-xp"/><path class="sks-jnu5b"/><path class="i4xzbhntc"/><path class="zajvxwo3l"/><path class="d7qvrob2h"/><path class="g4ddmib6p"/><path class="iyjxiyebm"/><path class="qoesl-gsp"/><path class="ibzbnnchi"/><path class="d0loltq2e"/><path class="ywm66jbyt"/><path class="au0b-mb1a"/><path class="afc137b2j"/><path class="g5ip3wkuq"/><path class="ctmaqy2-x"/><path class="w8j3vab-q"/><path class="xze268bqf"/><path class="x98gabccl"/><path class="ioy07hbxy"/><path class="qy1rcfa4z"/><path class="fo6rc6cto"/><path class="ax93sypuw"/><path class="xiu0-vx2t"/><path class="nt82f7bxf"/><path class="wsxaxxbkf"/><path class="y6d2t6bfe"/><path class="qx1cd7b2j"/><path class="p_ss3g0_q"/><path class="qia-ppbhb"/><path class="ymkk1x20e"/><path class="y1k51ulfg"/><path class="rtzg7nwdd"/><path class="m52cjub7e"/><path class="d7772vhun"/><path class="k8xyy3bhb"/><path class="ur1r1fbsi"/><path class="bhhtc7vjl"/><path class="ny30rccts"/><path class="vz7fa2bsh"/><path class="oc-8x5bfg"/><path class="mw0wliqrc"/><path class="ud0p98k4z"/><path class="epalchblc"/><path class="hl6onjbib"/><path class="mhx4_xbre"/><path class="ovg37zpqj"/><path class="a_grgobws"/><path class="hggbetbbw"/><path class="x6wf8iblu"/><path class="zdt0umvqx"/><path class="dkvp6xo-w"/><path class="ms0r-bb7y"/><path class="cvknj8bho"/><path class="xflxsqbzo"/><path class="y3hmb8hdi"/><path class="o8dh87b8i"/><path class="od9la7bwv"/><path class="zmptzq46n"/><path class="eq28het3l"/><path class="n2w_e7b6u"/><path class="ofd7cmm1a"/><path class="ytcy64btm"/><path class="b1d1rhcnx"/><path class="wyfjm04gk"/><path class="ekiiu_jer"/><path class="jo158hw6l"/><path class="zuctt0bze"/><path class="kz9gzmb2x"/><path class="cbjufv00o"/><path class="b1kzy8bqn"/><path class="g8urg9ajs"/><path class="laaqfts6p"/><path class="vr8hcfklr"/><path class="puch3nb_q"/><path class="vxxshy3le"/><path class="i66t_3b-f"/><path class="lxzl3_z7l"/><path class="bdbjudb1l"/><path class="jo4ofsbhu"/><path class="qk2-z8bpk"/><path class="mraxzbxlb"/><path class="d493jlbuw"/><path class="mygky4trh"/><path class="dfntr2bty"/><path class="d51z2d9sf"/><path class="xd-ms1gfu"/><path class="gstqxxbyc"/><path class="zb6c7tbil"/><path class="tvdo41blp"/><path class="ds-gdl5lx"/><path class="k42uyyatw"/><path class="yxm4qwn5n"/><path class="z7826yb8t"/><path class="h55pvyb6k"/><path class="ft1hc68ru"/><path class="sexcyo6pw"/><path class="b2uqypspv"/><path class="y0k_8dqpi"/><path class="so13xueml"/><path class="p5ul-cc8m"/><path class="rnvl_vbae"/><path class="f2je2wbyk"/><path class="e3sx6ub7g"/><path class="txs22dfwx"/><path class="owexfyogz"/><path class="qjwkop_da"/><path class="nym9qbz0r"/><path class="gench440b"/><path class="ckjqf4o0c"/><path class="jpmgaxb_p"/><path class="gzf4snbat"/><path class="wlhpq6bxp"/><path class="bnanvfb2n"/><path class="vv-yjxb7s"/><path class="xc7rmzbmx"/><path class="n8-7oib6e"/><path class="y4_97teip"/><path class="rf-87nb8b"/><path class="k4hcnib7x"/><path class="k2j4p25lo"/><path class="w5zul_74f"/><path class="qugzqi6hy"/><path class="s0_bk3kfm"/><path class="mbcsp1bhe"/><path class="ml6u7dqsu"/><path class="z1v3adbze"/><path class="hf88tgb4i"/><path class="dea340sfe"/><path class="a9ni6g68l"/><path class="st8kkl92y"/><path class="g0uegrbln"/><path class="hk07zkb4z"/><path class="fye_g_5vx"/><path class="spmauul-h"/><path class="wwzisi-fi"/><path class="euys0bbqf"/><path class="s17h_rbzz"/><path class="hr14y7bkz"/><path class="ierzj7b1h"/><path class="lopxj4z7o"/><path class="tep21i_yu"/><path class="lvp275g9v"/><path class="ngy3g0zzk"/><path class="lo9rfgbbj"/><path class="aiv4uabsr"/><path class="p0xqnr68s"/><path class="ri79zpncg"/><path class="fv3qu1b5b"/><path class="xm17en4tj"/><path class="w7z7mgbsf"/><path class="qlo78ebcd"/><path class="ovnafdb_r"/><path class="jdd996bbi"/><path class="io9t7b9gh"/><path class="qf8ow4bww"/><path class="eg22mohkx"/><path class="quws1qk1c"/><path class="npymi25hi"/><path class="vt1uewb-h"/><path class="bzpr4hn5m"/><path class="tfewz36yc"/><path class="a4jkk66bt"/><path class="uqzvbdc0b"/><path class="zp_zuebhb"/><path class="kk-z4eu9g"/><path class="u7up80brz"/><path class="uijkx9bnm"/><path class="jrdgkeuae"/><path class="c-_2rok3s"/><path class="p24s8kb9l"/><path class="f7s9stbwi"/><path class="vgvmomkui"/><path class="dbzz3v1tx"/><path class="g7hwebv4x"/><path class="ixhckp8cv"/><path class="phuxxrbjf"/><path class="a8v6tgb4w"/><path class="q3qz10bjt"/><path class="um10hkpgo"/><path class="pauyaacax"/><path class="w3kn4sc3d"/><path class="wr7nvibas"/><path class="qke16bu6o"/><path class="hpbfh1b9v"/><path class="b6xb6u0uu"/><path class="mztktbcyl"/><path class="jtze48b_r"/><path class="v9hu4rbxe"/><path class="s_q-l1zts"/><path class="suty2d40d"/><path class="r1t5l4hgi"/><path class="xb7fy4rfk"/><path class="se6e6ib7v"/><path class="c-i2bvo8w"/><path class="jffsqkpqy"/><path class="kul4lit6r"/><path class="wukuzibfh"/><path class="mqkfls_jt"/><path class="gvus4zbjs"/><path class="vc-10ob-k"/><path class="rz41dlfcx"/><path class="b3_zdczbu"/><path class="el5v1vm7h"/><path class="r6nvl7b-s"/><path class="mwbedwb2w"/><path class="o06_945gt"/><path class="xeqzf3mvo"/><path class="ep3ejtway"/><path class="oiw4odggw"/><path class="rf56jv6ai"/><path class="u6ll9zbev"/><path class="lb_52xb_i"/><path class="p-vdw3bzv"/><path class="es_1uwbpt"/><path class="ezbjvhbfn"/><path class="lhv1_hbrd"/><path class="th_iaxb9h"/><path class="tnc9leb2t"/><path class="hhryes23a"/><path class="pjjpkcb_y"/><path class="c7b510btj"/><path class="i9vitccfq"/><path class="jv5fywb0g"/><path class="rjqisz75w"/><path class="g3ak6gbpr"/><path class="m1pmzr44l"/><path class="e9zkqdb-h"/><path class="z-xe7rbse"/><path class="tjdumck4k"/><path class="v4bktjbng"/><path class="glo901bsy"/><path class="jipjkulas"/><path class="aj54-acvm"/><path class="trzeifb2l"/><path class="ctl37h4mn"/><path class="j8tlb46mb"/><path class="j1bfg_3zm"/><path class="qbs36gs0e"/><path class="fnbzstbup"/><path class="sxnbp_qeb"/><path class="v7_oy_7bm"/><path class="t3zxf6b9c"/><path class="amf_9xbij"/><path class="r2k_--bim"/><path class="zbkae1bei"/><path class="sacjm7kjq"/><path class="sivrfsb7b"/><path class="x-c974huw"/><path class="fycdmjoeh"/><path class="mrvg0cbda"/><path class="qj2-bdcqz"/><path class="am3w8zn8a"/><path class="h2hbfpszp"/><path class="mgc44u5rk"/><path class="wwsg8tbvu"/><path class="gwmy_qb3k"/><path class="h5nx6zbse"/><path class="yyx2r7blk"/><path class="e0kge3b9d"/><path class="k4y2htb0t"/><path class="kw12otbsn"/><path class="i4za-o91x"/><path class="u2i_ny7il"/><path class="qbe-uub7d"/><path class="gnnzddbtz"/><path class="c39bw-ndt"/><path class="bexlohahv"/><path class="q4q33uben"/><path class="i6y_lqb2q"/><path class="thme2ebgx"/><path class="bl7mmqbxm"/><path class="peuefybtt"/><path class="hx9oherjo"/><path class="pdq47lb4w"/><path class="f4kv-__2w"/><path class="cb14zdexr"/><path class="lh73d8pkt"/><path class="twp764zgu"/><path class="vicn4ffzs"/><path class="uj_zmz-lp"/><path class="uipn_hbcj"/><path class="pb1lzfhkg"/><path class="yeoubkbdr"/><path class="ac5fd53ga"/><path class="h-v7oibjx"/><path class="oo8fsgb9e"/><path class="daktg4y-i"/><path class="mrqp6ub0x"/><path class="jod1crbrd"/><path class="zy_h7xulz"/><path class="q4ek7466r"/><path class="bqvzzblie"/><path class="sbumb_byq"/><path class="hmq9z1bbd"/><path class="sv7e0ogiq"/><path class="n8ec20ahr"/><path class="zxboezjsz"/><path class="bzklo3bnp"/><path class="oge23j4vv"/><path class="a89km2_le"/><path class="nlfvklbdn"/><path class="lsfxm33ry"/><path class="thd9e8bmf"/><path class="h0j06cbhb"/><path class="r5qr_yt1g"/><path class="edcd3bb2p"/><path class="uncm7c0bw"/><path class="t33tzac1f"/><path class="plzxtulna"/><path class="v0i7gdjza"/><path class="ue5984tju"/><path class="lucd3hbjg"/><path class="s7n7r0bzo"/><path class="g0tsz6l5t"/><path class="vyxmhptmu"/><path class="dd0yhgbjm"/><path class="nejxmnbaw"/><path class="bcpwcwbsq"/><path class="wquxe5pph"/><path class="z4ci9ke2v"/><path class="j72tpippq"/><path class="xje3tuqec"/><path class="d24a-nhpn"/><path class="dp4oj1rfw"/><path class="rjk0rw2-h"/><path class="u90fgmdzk"/><path class="qc058cchh"/><path class="o7ilvcs6r"/><path class="x80frpb7n"/><path class="kweoh4hml"/><path class="wj_ckq09v"/><path class="p1-qdl_7z"/><path class="jo4bhd9fx"/><path class="q9zs0ej6d"/><path class="b4m0icbvi"/><path class="w1qo-3b5k"/><path class="whvsvf7rz"/><path class="e6vzx0b3i"/><path class="wy5405b-i"/><path class="esz1s7bsz"/><path class="r0s5srz-z"/><path class="g-77cubrq"/><path class="xm5vy6b0z"/><path class="f6g7q4q6m"/><path class="vpb9n_1cq"/><path class="v_-8uy-ai"/><path class="q71c0bcpf"/><path class="k8__m_b9s"/><path class="x1uaysb2c"/><path class="maqxy3bjw"/><path class="t8q8jf2sx"/><path class="b8-d7dbow"/><path class="nelum5_hy"/><path class="yydke_nlc"/><path class="yybxlub6g"/><path class="h8ciyib_m"/><path class="sv7ghibji"/><path class="khcactrjk"/><path class="m5dz9k56e"/><path class="bwxcxacrk"/><path class="acrcoxaav"/><path class="xyulynbdt"/><path class="w7ccchbad"/><path class="w6gwa8b7t"/><path class="vfu9zac_q"/><path class="vbjjltbii"/><path class="ubbjgxyyu"/><path class="hysa7osnq"/><path class="za2m7ulsv"/><path class="ztxzerbtl"/><path class="rmji61bvf"/><path class="b04y_ob1o"/><path class="lkob1i7_m"/><path class="rh7nwlbkz"/><path class="n1zwxu5cz"/><path class="ebw_hcbog"/><path class="d139jcbnj"/><path class="ldbu0tbql"/><path class="y6h3q8flo"/><path class="vflei7bar"/><path class="xbb28sbwk"/><path class="w5i2i601p"/><path class="m7kxm6pkh"/><path class="vryzoi7vb"/><path class="d7_nv4boj"/><path class="ae53nbqdn"/><path class="a-udxg2is"/><path class="qwrjojj0g"/><path class="hyq05qxoo"/><path class="uxbxz5baa"/><path class="b4wnz5zdk"/><path class="r0o0uobkr"/><path class="k0nkxo8aj"/><path class="o_4zmdnqq"/><path class="sfs7w3bmv"/><path class="yl-nrexpi"/><path class="gtwzbrhue"/><path class="k8b0h_b4j"/><path class="nzus4y5ho"/><path class="mil_4hb4v"/><path class="jp8wy4zgn"/><path class="zmg1ltb4l"/><path class="btwhynb2c"/><path class="enr4bxu4t"/><path class="yjunbbufq"/><path class="t77n7lr2c"/><path class="tqybrf_lr"/><path class="s_pe4mr4k"/><path class="uabv3ns5j"/><path class="jgvtx-btl"/><path class="tq2buwbmz"/><path class="k0y95ibuu"/><path class="q-7p-4bvf"/><path class="k3zvx_bhb"/><path class="y_9zuhb9a"/><path class="vcngpbblv"/><path class="is2ocpb2a"/><path class="etiozmh9j"/><path class="mo1c_yqwq"/><path class="gwce6xbeh"/><path class="awf9ydb-a"/><path class="ys-8jkb9w"/><path class="pyrmiqbys"/><path class="pko-dpafc"/><path class="jul55vbzo"/><path class="w6hr-dh5c"/><path class="a2ir0bcsd"/><path class="a18frnnlk"/><path class="ufa998b8j"/><path class="rfqr0zbom"/><path class="papqkyb9e"/><path class="cydl67bxi"/><path class="sruawybkf"/><path class="oz2uyz6fs"/><path class="tsxo4ig5u"/><path class="hwmh6ubsn"/><path class="k8qa-cbqx"/><path class="k6odjzkhg"/><path class="noyy6lbvr"/><path class="gqxh-kbne"/><path class="gjqltzboy"/><path class="c80b78b2t"/><path class="h4sz59bic"/><path class="zavxgzb3e"/><path class="litz6wczi"/><path class="eg69occfb"/><path class="zklyx7hfj"/><path class="lculv5_lc"/><path class="bl484_cfm"/><path class="ab92fkb1h"/><path class="ra79setzl"/><path class="lv9ofjboa"/><path class="ksxxssbke"/><path class="e9m223bbh"/><path class="sk4s012es"/><path class="ji__igbjo"/><path class="pjas32btq"/><path class="w70pvgbbj"/><path class="gi-ql72vp"/><path class="j2ykpdbai"/><path class="s5bcitktc"/><path class="p70z6xy6t"/><path class="e5_8rzcbq"/><path class="lozk2kbgc"/><path class="s-x1t7bpt"/><path class="wm527vbhk"/><path class="ukaja_b4r"/><path class="qu0z-ia2a"/><path class="mndkgdckl"/><path class="a5a8d7bwd"/><path class="fzlx4rjbf"/><path class="u1wtk9d4v"/><path class="ik40mcbpc"/><path class="pt2a6kbca"/><path class="o3k1y6aib"/><path class="wp4jrmbjk"/><path class="yy0rmybvh"/><path class="p8i1_nopz"/><path class="uuzllx1fh"/><path class="d65kxmb0d"/><path class="obtvaxbgo"/><path class="kfaga9bzx"/><path class="vkt0y3nha"/><path class="e8foz-bbk"/><path class="q9wb2sb8c"/><path class="z5a36t2wv"/><path class="q5z5ncblg"/><path class="lypdbccjs"/><path class="mryaqc5uy"/><path class="t3x4n7bet"/><path class="v9xzyucpi"/><path class="embwk7bda"/><path class="k-_cwfbkv"/><path class="p2x_m6izf"/><path class="migrkx7pj"/><path class="huraqxb5c"/><path class="dby68ibzf"/><path class="awa6vbb7a"/><path class="ixtnchbqa"/><path class="zcn6evgfg"/><path class="lf3uqcxfc"/><path class="fphy7wauw"/><path class="szwnu799w"/><path class="z8m788baf"/><path class="nukd8cd7b"/><path class="dfi2cd58e"/><path class="urh1jpb3e"/><path class="b9_3__94s"/><path class="zku6q0mev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-serbia" /></template>
<style>
.a_grgobws {
  fill: var(--svg-color--0e0f0f, #0e0f0f);
  d: path("M21.759 30.676h.041c.069.019.098.069.063.14c-.029.037-.031.139-.117.061z");
}

.a-ap2dbic {
  fill: var(--svg-color--502a0e, #502a0e);
  d: path("M17.542 21.02c-.009-.09-.002-.188-.058-.263c.163.055.133.158.058.263");
}

.a-npn_12b {
  fill: var(--svg-color--240807, #240807);
  d: path("M17.09 41.17c.008-.025.017-.038.024-.054q.031-.032.06 0q.013.208.021.418c-.161-.086-.035-.254-.105-.364");
}

.a-udxg2is {
  fill: var(--svg-color--f1f1f2, #f1f1f2);
  d: path("M18.892 18.467c-.025.012-.047.03-.067.039c-.078.083-.153.134-.231.005c-.117-.11-.166-.232-.063-.378c.107-.083.216-.113.326-.009q.014.02.031.018c.021.031.037.063.056.094c-.033.077-.007.16-.052.231");
}

.a00rko8rx {
  fill: var(--svg-color--656567, #656567);
  d: path("M12.659 29.31h-.057c-.006-.06-.022-.118.043-.155c.014-.005.041.006.043.014c.016.052.018.101-.029.141");
}

.a030z-t0j {
  fill: var(--svg-color--381211, #381211);
  d: path("M16.55 36.29c.019.072.121.104.104.193c-.138-.078-.088.104-.155.12a.2.2 0 0 1-.049-.071a.28.28 0 0 1 .027-.236q.032-.038.073-.006");
}

.a11cwjbqq {
  fill: var(--svg-color--6a200f, #6a200f);
  d: path("M15.244 21.18c-.021-.02-.038-.035-.058-.057c.058-.035.111-.07.168-.103q-.007.078-.01.154q-.047.048-.1.006");
}

.a18frnnlk {
  fill: var(--svg-color--414141, #414141);
  d: path("M15.11 30.729q.072-.06.152-.113c.034.049.067.109 0 .168c-.05.03-.101.043-.158.016c-.025-.02-.029-.042-.021-.079c.008-.003.018-.003.027.008");
}

.a2ir0bcsd {
  fill: var(--svg-color--0b0c0c, #0b0c0c);
  d: path("M15.185 30.3c.023.019.052.042.072.069v.246c.014.123-.068.123-.152.112c.009-.147.104-.28.08-.427");
}

.a3-2tvbes {
  fill: var(--svg-color--49494a, #49494a);
  d: path("M21.701 31.15c-.069.188-.146.083-.224.004l.072-.008q.077-.001.152.004");
}

.a33r6pbfk {
  fill: var(--svg-color--424545, #424545);
  d: path("M13.948 29.14c.006-.035.109-.017.051-.085c.03-.092.014-.205.104-.301c.05.166-.082.33.059.461q.016.034-.011.062a.11.11 0 0 1-.104.004c-.051-.035-.095-.074-.099-.141");
}

.a3bvcxost {
  fill: var(--svg-color--646565, #646565);
  d: path("M24.418 27.622a.4.4 0 0 0 .046-.051c.062.051.082.121.088.199c-.09.02-.094-.074-.142-.109q-.025-.018-.015-.031c.007-.008.016-.008.023-.008");
}

.a4glwe1zo {
  fill: var(--svg-color--5b5c5c, #5b5c5c);
  d: path("M13.11 35.29a.5.5 0 0 1-.039.272c-.063-.041-.012-.114-.049-.159l-.002-.48q.041-.044.084 0c0 .021.005.033.005.059a.5.5 0 0 0 .001.308");
}

.a4jkk66bt {
  fill: var(--svg-color--414242, #414242);
  d: path("M14.06 32.776c.021-.191.035-.386.056-.572c.126.047.048.138.051.215c-.01.117.021.248-.051.357q-.033.038-.056 0");
}

.a5a8d7bwd {
  fill: var(--svg-color--232424, #232424);
  d: path("M17.18 31.26q.027.024.049.05l-.01.142c-.183-.027.008-.135-.039-.192");
}

.a6sj1cber {
  fill: var(--svg-color--4b3232, #4b3232);
  d: path("m12.595 37.08l-.008.061a.23.23 0 0 1-.1-.211q-.035-.053.018-.078q.042.112.09.228");
}

.a7_vecsin {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M13.688 28.835q.003.017.002.037c.021.103.018.203.014.308c.014.137-.117.243-.084.384l-.002.075q-.062.22-.143.435a.2.2 0 0 1-.112.108c-.103.013-.153-.047-.194-.128c-.025-.109-.068-.217-.068-.334c.021-.126.021-.251.021-.381c0-.051-.002-.108.004-.164c.011-.096.079-.166.074-.266c.022-.07.03-.148.051-.224c.027-.078.017-.181.109-.228c.04.012.056.043.065.078c.01.067 0 .144.072.182c.071.02.137.055.191.118");
}

.a7zyb4boh {
  fill: var(--svg-color--f8d428, #f8d428);
  d: path("M16.183 39.62c-.041.023-.082.054-.125.078c-.109-.002-.08-.105-.104-.164c-.021-.096-.085-.144-.147-.196c-.062-.021-.096.034-.145.05c-.171.038-.216-.042-.178-.193c.013-.131-.033-.273.074-.382c.031-.021.061-.036.086-.056c.08.029.17-.027.24.048c.118-.028.172.079.248.129a.47.47 0 0 1 .119.276c.016.05.012.1.012.146c-.021.088-.076.17-.08.264m5.18.084c-.093-.045-.106-.143-.154-.213c-.104-.078-.032-.189-.054-.278a.53.53 0 0 1 .126-.265l.196-.191c.076.029.164-.027.232.048l.072.008c.122.009.148.095.148.191c.002.104.006.202.022.3a.13.13 0 0 1-.026.072c-.074.054-.119-.004-.17-.038c-.063-.021-.104.008-.145.046c-.104.018-.141.096-.15.193c-.029.043-.007.127-.097.127");
}

.a8-8-59sp {
  fill: var(--svg-color--645712, #645712);
  d: path("m21.437 22.288l-.002.057c-.106-.018-.221 0-.321-.061c.021-.019.044-.031.067-.051q.128.033.256.055m.266.131a.3.3 0 0 0 .058-.043c.074.004.148.004.207.059c-.095.099-.174-.024-.265-.016");
}

.a88xpkb_e {
  fill: var(--svg-color--520c09, #520c09);
  d: path("M23.726 35.721a.34.34 0 0 1 .06.188c.022.047.028.09-.009.135a.9.9 0 0 1-.108-.328q.028-.031.057.005");
}

.a89km2_le {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("M20.712 30.991c-.044 0-.094.002-.115-.049c-.092-.09-.172-.13-.225.036c.018.091-.029.187.031.274l-.004-.004c.099.074.115.164.059.271c-.042.079-.16.127-.109.242c.039.185.123.245.278.114c.031.006.062.006.089.01c.121.077.069.154-.009.23c-.106.096-.233.047-.354.047c-.109-.068-.241-.022-.356-.064c-.123-.018-.202-.084-.226-.201c-.026-.346-.041-.683.009-1.025c.048-.039.083-.09.151-.099c.102-.134.258-.044.379-.094c.141.011.291-.052.424.046c.113.098.023.172-.022.266");
}

.a8qgidnyc {
  fill: var(--svg-color--222, #222);
  d: path("M18.58 40.37c.056.033.108.074.161.113q0 .117.004.242c.016.046.02.135-.037.117c-.083-.02-.045-.113-.035-.178c.014-.098-.037-.168-.097-.232c-.015-.012-.019-.031-.015-.046q.012-.017.019-.016");
}

.a8v6tgb4w {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("M14.411 32.926c.061.116-.141.104-.104.217c-.113-.146.04-.158.104-.217");
}

.a8zjwsbrp {
  fill: var(--svg-color--342e0b, #342e0b);
  d: path("m21.341 39.12l.047.057c-.018.04.021.133-.047.105c-.059-.019-.009-.101 0-.162");
}

.a9ni6g68l {
  fill: var(--svg-color--131515, #131515);
  d: path("m21.914 32.18l-.056.063c-.021-.019-.047-.031-.069-.049c.043-.063.08-.127.122-.188q0 .09.003.174");
}

.aapazeb_y {
  fill: var(--svg-color--403e3d, #403e3d);
  d: path("M24.929 36.768q.003-.477.013-.944c.036-.019.055-.004.06.033q.005.152.004.311c-.013.166.02.334-.02.5c-.001.042-.008.083-.057.1");
}

.aapvf8bui {
  fill: var(--svg-color--402020, #402020);
  d: path("M18.06 26.557a4 4 0 0 1-.15-.196c.027-.09.167.063.159-.086c.286.105.01.188-.009.282");
}

.ab92fkb1h {
  fill: var(--svg-color--191a1a, #191a1a);
  d: path("M14.625 31.516c.002.028.007.062.007.095c-.023.051-.07.063-.119.063a2 2 0 0 1 .062-.157q.024-.036.05-.001");
}

.abq2vv1xk {
  fill: var(--svg-color--565656, #565656);
  d: path("M17.02 40.12a.3.3 0 0 1 .047.049c-.022.078-.043.156-.104.213h-.042c-.015-.104.033-.189.099-.262");
}

.ac5fd53ga {
  fill: var(--svg-color--1d1c1c, #1d1c1c);
  d: path("M17.12 29.685c.066-.173.063-.316-.152-.377c.053-.055.125-.07.196-.074q.042 0 .065.027q-.001.234.004.472z");
}

.accyaqbzt {
  fill: var(--svg-color--414242, #414242);
  d: path("M15.804 30.353c-.146.038-.035.212-.131.271q-.03.024-.063.011c-.096-.142.003-.312-.063-.452l.014-.032c.145-.014.189.1.243.202");
}

.acrcoxaav {
  fill: var(--svg-color--646043, #646043);
  d: path("M15.763 19.614c-.104-.082-.115-.211-.144-.32a.2.2 0 0 1 .043-.012c.052.1.103.213.101.332");
}

.acuq17psk {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("m22.364 18.35l.021.196q.023.03.01.066a.17.17 0 0 1-.074.084c-.083.027-.17.034-.253.043a.2.2 0 0 1-.073-.029a.3.3 0 0 1-.086-.168a.44.44 0 0 1 .006-.204a.2.2 0 0 1 .104-.125c.132-.011.281-.036.345.137");
}

.ae53nbqdn {
  fill: var(--svg-color--edeeee, #edeeee);
  d: path("M18.944 19.357c-.016.013-.025.024-.037.037c-.127.032-.257.06-.379-.021l-.008-.021c-.078-.089-.109-.185-.004-.278h.006c.103-.156.219-.211.359-.052l.037.06c.114.081.019.187.026.275");
}

.aeaz0xe7v {
  fill: var(--svg-color--46400e, #46400e);
  d: path("M15.617 26.577c.085.004.175.006.259.011c-.063.157-.164.079-.259.047c-.015-.017-.019-.022-.013-.039q.008-.02.013-.019");
}

.af1a1gb6e {
  fill: var(--svg-color--6c5e13, #6c5e13);
  d: path("M16.08 23.28c-.128.066-.274.08-.419.104c.104-.166.277-.11.419-.154q.032.018.021.036c-.01.005-.014.014-.021.014");
}

.afc137b2j {
  fill: var(--svg-color--342e12, #342e12);
  d: path("M15.458 18.769c-.025.105.045.232-.063.322a.054.054 0 0 1-.057-.028c-.009-.094-.033-.185 0-.278c.014-.018.031-.041.049-.056z");
}

.afju6jbll {
  fill: var(--svg-color--414140, #414140);
  d: path("M16.01 35.396c-.029.07-.054.146-.082.218c-.043-.047-.074-.142-.162-.063q-.099.024-.111-.079c.094-.123.219-.127.355-.076");
}

.afol2xb1j {
  fill: var(--svg-color--4b4310, #4b4310);
  d: path("M16.231 20.589q.03.079.062.15c-.036.023-.069.051-.104.073c-.031-.004-.041-.03-.051-.055c-.053-.04-.063-.091-.057-.153c.055.051.11.094.15-.015");
}

.ag6qvubhw {
  fill: var(--svg-color--232424, #232424);
  d: path("M19.1 28.15c.014.019.023.038.039.057c.066.101.018.17-.063.229q-.039.013-.073-.023c.034-.087.067-.171.097-.263");
}

.ahjpizsgo {
  fill: var(--svg-color--6c7778, #6c7778);
  d: path("M16.97 28.507c.045.015.092.042.142.063c.047.035.039.07.009.113a1 1 0 0 0-.104.016c-.063-.056-.163-.095-.047-.192");
}

.ahxlf7ftv {
  fill: var(--svg-color--f7d228, #f7d228);
  d: path("M18.792 16.09q.003.075.008.145c.071.114.162.051.248.037c.053-.041.104-.076.166-.027c.041.034.082.074.121.112c.1.065.043.138-.004.208c-.072.04-.107.178-.232.1l.004.008c-.074-.113-.17-.094-.273-.055c-.033.125-.009.248.021.373c.02.09.015.188-.049.269a.16.16 0 0 1-.17.008c-.154-.192-.012-.417-.062-.625c-.112-.11-.209-.022-.308.022h-.041a.5.5 0 0 1-.194-.18c-.019-.094.04-.146.088-.205c.058-.074.121-.103.198-.027c.017.021.037.027.057.041c.168.037.24-.021.2-.197a.2.2 0 0 0-.039-.055c-.138-.162.073-.193.103-.295c.062-.09.109-.016.156.017q.059.059.112.118c.042.108-.042.157-.11.208");
}

.aihq-8o7d {
  fill: var(--svg-color--282828, #282828);
  d: path("M21.498 31.762c.058.104.121.201.101.333c-.092-.032-.053-.17-.155-.193c.02-.045.035-.096.054-.14");
}

.aiv4uabsr {
  fill: var(--svg-color--1f1f1f, #1f1f1f);
  d: path("m13.599 32.831l.043.105c-.004.098-.01.203-.017.303c-.019.039-.032.086-.088.053c-.04-.161.095-.299.062-.461");
}

.aj54-acvm {
  fill: var(--svg-color--e1e1e1, #e1e1e1);
  d: path("M19.618 27.473c.085-.013.055.089.104.104c.078.086.07.186.051.291c-.038.104-.051.229-.156.299c-.032.009-.057-.004-.075-.027c-.062-.125.009-.255.003-.38c.032-.091.007-.202.073-.287");
}

.albjnp92s {
  fill: var(--svg-color--66220d, #66220d);
  d: path("M21.543 21.649c0-.012 0-.031.003-.047a.4.4 0 0 0 .26.014c-.067.144-.164.097-.263.033");
}

.am3w8zn8a {
  fill: var(--svg-color--0f0f0f, #0f0f0f);
  d: path("M19.416 39.542h.058q.027.04.055.086c-.023.058-.066.076-.122.068q.003-.077.009-.154");
}

.amf_9xbij {
  fill: var(--svg-color--232323, #232323);
  d: path("M24.09 30.782c-.031-.021-.063-.037-.095-.057c-.002-.086-.009-.169-.013-.256c-.016-.046-.047-.105.048-.105c.021.137.038.276.06.418");
}

.an6hd-9at {
  fill: var(--svg-color--272828, #272828);
  d: path("M17.74 39.854c.012-.066.036-.133.104-.171c.051.013.105-.035.162-.004c.027.022.037.06.047.09c0 .101-.002.201.043.3l-.021-.004l-.021.004c-.094-.045-.004-.225-.16-.215c-.024.034-.055.057-.096.051z");
}

.anoe64bcd {
  fill: var(--svg-color--484b4b, #484b4b);
  d: path("M12.183 31.04h.062a.4.4 0 0 1-.086.207q-.032-.002-.062.006c-.002-.086.052-.141.086-.213");
}

.apndpf_9y {
  fill: var(--svg-color--582c0d, #582c0d);
  d: path("M15.04 23.756c.057-.069.127-.103.221-.06c-.061.078-.147.047-.221.06");
}

.apnkiwvvf {
  fill: var(--svg-color--515252, #515252);
  d: path("m17.08 28.784l.083.051c.05.119.054.217-.094.269c0-.028-.007-.054-.009-.083z");
}

.aps864bfo {
  fill: var(--svg-color--242525, #242525);
  d: path("M13 30.25a1 1 0 0 0-.078-.048c-.029-.111.068-.176.09-.271c.093.111-.016.212-.012.319");
}

.aqaz5m_xp {
  fill: var(--svg-color--191818, #191818);
  d: path("M24.812 27.16q-.016-.01-.041-.008c-.027-.068-.062-.139-.053-.213a.22.22 0 0 1 .094.221");
}

.arijg5egl {
  fill: var(--svg-color--8d7f38, #8d7f38);
  d: path("M23.782 20.26a.2.2 0 0 0-.051-.029c-.029-.03-.029-.062-.027-.102c.027-.06.064-.099.129-.11c.081.09.217.02.299.104q-.022.024-.045.045c-.115-.015-.205.055-.305.092");
}

.aro-bqbln {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M17.487 41.35c-.104.048-.069.311-.287.186c-.105-.108-.023-.25-.059-.373c0-.186.02-.362.07-.545a.6.6 0 0 1 .053-.145c.043-.088.092-.169.105-.27a.6.6 0 0 1 .083-.194q.061-.066.125-.125c.052-.036.104-.06.168-.048a.13.13 0 0 1 .078.074c.047.102-.017.203.004.308a.13.13 0 0 1-.015.063a.5.5 0 0 0-.073.188c-.033.09-.033.188-.054.281a.5.5 0 0 0-.025.189c.008.166-.009.318-.173.411");
}

.asjbofbun {
  fill: var(--svg-color--f0f1f1, #f0f1f1);
  d: path("M17.16 27.841q.034-.023.065-.047c.014.117.014.236-.104.311q.022-.131.039-.264");
}

.asupdzcof {
  fill: var(--svg-color--85110d, #85110d);
  d: path("M15.15 21.501c.006-.067.063-.079.109-.106c.073-.073.105-.007.144.043q.007.055.011.106c-.098.035-.16-.107-.264-.043");
}

.atdb0itts {
  fill: var(--svg-color--1a1914, #1a1914);
  d: path("M21.574 25.53c-.179.164-.235.438-.479.536c-.041.015-.076.026-.113.042c.035-.193-.096-.311-.414-.345c.221-.106.414-.228.654-.166c.125.029.234-.045.352-.067");
}

.atl1550ak {
  fill: var(--svg-color--3c100a, #3c100a);
  d: path("M21.375 33.724c.009-.021.017-.031.027-.052c.01-.027.022-.031.045-.015c.01.119.034.246.021.362c-.021.181.049.284.219.326c-.049.056-.118.056-.178.093q-.03.017-.06.024q-.032.012-.06-.013q-.003-.358-.014-.725");
}

.att4r1bkx {
  fill: var(--svg-color--210b0b, #210b0b);
  d: path("M25.07 35.34h-.03c-.007-.021-.015-.035-.022-.061c.004-.063.013-.125.017-.195c.013-.022.022-.022.039 0h.013c-.009.089-.012.171-.017.256");
}

.atwwlx8ko {
  fill: var(--svg-color--8c7917, #8c7917);
  d: path("M15.413 39.95c-.167.008-.334.008-.5.018l.13-.13v.018a.25.25 0 0 0 .259 0H15.3c.051-.034.077.015.107.038q.016.016.012.034q0 .022-.006.022");
}

.au-_0abco {
  fill: var(--svg-color--ecebe9, #ecebe9);
  d: path("m23.94 21.02l-.111.06h-.146a.12.12 0 0 1-.111.013a.3.3 0 0 1-.051-.062c-.036-.086-.064-.178-.033-.275c.027-.083.07-.153.152-.193c.09-.033.168-.011.242.041c.018.02.037.036.057.061c.021.035.043.062.063.099a.34.34 0 0 1-.062.256");
}

.au0b-mb1a {
  fill: var(--svg-color--5b5854, #5b5854);
  d: path("M15.503 18.762v.479a.1.1 0 0 1-.07-.01a.27.27 0 0 1-.058-.176c.021-.1-.002-.208.083-.288a.1.1 0 0 0 .045-.005");
}

.auzjhrbuz {
  fill: var(--svg-color--c2ac22, #c2ac22);
  d: path("M22.579 40.44c-.027-.004-.053-.004-.078-.008c-.13-.067-.15-.14-.015-.217q.015.007.032.008c.057.086.242-.127.238.104c-.05.05-.079.14-.177.113");
}

.aw3po2ldb {
  fill: var(--svg-color--732a0e, #732a0e);
  d: path("m16.867 20.966l-.179-.208c.143 0 .215.054.179.208");
}

.awa6vbb7a {
  fill: var(--svg-color--5f5f5f, #5f5f5f);
  d: path("M14.981 19.339c-.018.08.041.17-.043.228c-.045-.071-.079-.147-.002-.223q.025.001.045-.005");
}

.awf9ydb-a {
  fill: var(--svg-color--f6f6f6, #f6f6f6);
  d: path("M13.89 30.458c.008-.062.033-.108.11-.098c.05.117.11.213.251.098c.077.02.098.076.09.146c-.08.104-.041.229-.07.338c-.116.078.029.18-.021.268c-.021.07-.036.146-.096.197a.4.4 0 0 0-.038.058c.042.106-.072.177-.064.274q-.03.047-.059.104c-.091.023-.171.027-.201-.088v-.081a.4.4 0 0 0-.057-.052a.2.2 0 0 1-.037-.065c-.01-.056.014-.106.014-.157c.029-.07.063-.142.057-.224c.076-.111.031-.231.027-.353c.062-.113.021-.246.094-.365");
}

.ax93sypuw {
  fill: var(--svg-color--fad428, #fad428);
  d: path("m18.524 18.08l-.25-.154c-.043.023-.053 0-.055-.036c-.006-.083-.072-.169.004-.248a.2.2 0 0 0 .039-.04c.117.008.229-.035.342-.039c.082-.012.162-.023.236.039c.055-.012.113-.023.172-.043c.056.086.185.066.229.17c-.023.051-.053.104-.037.165q.014.028-.012.06a.3.3 0 0 1-.051.043c-.082.056-.156.125-.256.158a.1.1 0 0 1-.066-.01c-.088-.079-.204-.014-.295-.065");
}

.axbqzob5x {
  fill: var(--svg-color--1f110a, #1f110a);
  d: path("m14.625 36.655l.002.104a.1.1 0 0 1-.055.04q-.05.011-.095.016c.022-.078.062-.141.148-.16");
}

.axj98czua {
  fill: var(--svg-color--763510, #763510);
  d: path("M21.743 23.542c.126.017.271-.008.338.146c-.113-.046-.265-.003-.338-.146");
}

.aybrowbbu {
  fill: var(--svg-color--191818, #191818);
  d: path("M15.361 33.559h-.022l-.021.004c-.017-.028-.031-.062-.075-.058q-.017.04-.038 0c-.006-.049.011-.075.058-.092c.047-.019.067.004.084.037a1 1 0 0 0 .014.109");
}

.aytwdmykc {
  fill: var(--svg-color--665f37, #665f37);
  d: path("M13.894 19.344c-.045.055-.072.129-.146.155c-.023.021-.047.021-.064-.004q-.016-.096-.033-.185q.096-.029.191-.06c.03.022.052.055.052.094");
}

.azl9nhn-r {
  fill: var(--svg-color--5b5011, #5b5011);
  d: path("M15.507 22.22h-.219c.074-.057.096-.182.225-.148a2 2 0 0 0-.006.148");
}

.b_h8-5blo {
  fill: var(--svg-color--49403f, #49403f);
  d: path("M24.13 20.12a1 1 0 0 1 .125-.043l.029.207c-.014.023-.025.023-.042.004c-.056-.043-.104-.084-.157-.123c.004-.029.016-.045.045-.045");
}

.b_idic5-g {
  fill: var(--svg-color--242424, #242424);
  d: path("M23.468 18.872c.004-.071.008-.146.01-.215q.072.077.147.151c-.038.021-.073.036-.11.056q-.02.04-.047.008");
}

.b_qbn5b4p {
  fill: var(--svg-color--fdfdfd, #fdfdfd);
  d: path("M13.06 32.667q.003-.026.002-.057c.02-.143-.032-.281-.036-.422c-.032-.152-.128-.298-.021-.459a1 1 0 0 1 .141-.132c.051-.035.105-.062.172-.054c.109.068.176.201.318.217a.15.15 0 0 1 .045.063c.037.172.029.346.006.517c-.055.147-.027.307-.032.458c.021.175-.058.342-.058.523l.004.245c-.004.111.002.229-.018.339c-.047.121-.031.246-.058.365c-.034.098-.033.209-.036.311a.6.6 0 0 1-.025.113c-.02.063-.063.105-.072.166c-.006.079-.006.148-.006.221c.013.142-.043.272-.033.408c0 .022-.008.047-.012.07c-.069.105-.076.229-.103.346a1 1 0 0 1-.074.33c-.041.084-.032.168-.043.25c-.009.094-.041.18-.057.266c-.026.056-.03.125-.103.147l-.008.062c-.119.013-.15-.045-.105-.146l-.049-.107c.069-.073.035-.184.082-.262c.037-.072.043-.139.056-.214a.7.7 0 0 0 .051-.251c.026-.074.017-.152.022-.229c.004-.063.027-.125.027-.188c.032-.097.016-.181.021-.272v-.354a.3.3 0 0 1 .029-.118a.3.3 0 0 0 .02-.087c.006-.356 0-.71.004-1.063c-.002-.135 0-.271-.004-.404c.004-.109.049-.221.021-.338c-.027-.08.003-.186-.068-.26");
}

.b04y_ob1o {
  fill: var(--svg-color--d5b621, #d5b621);
  d: path("m15.302 20.39l-.062.011c-.047-.083-.138-.133-.153-.235c.014-.105.071-.043.115-.035c.164.032.178.124.1.259");
}

.b05xozbzx {
  fill: var(--svg-color--2a0f0f, #2a0f0f);
  d: path("M15.875 34.3c-.002.021 0 .03.005.042c-.078.066-.172.046-.258.057c-.043.024-.093.043-.109-.031c.112-.064.25.009.362-.068");
}

.b1d1rhcnx {
  fill: var(--svg-color--606060, #606060);
  d: path("M14.158 29.31c-.03.142-.026.295-.092.429c-.041-.002-.063-.031-.073-.065c.073-.134.051-.279.066-.417q.05-.007.103-.006q-.004.022-.004.059");
}

.b1kzy8bqn {
  fill: var(--svg-color--414141, #414141);
  d: path("m20.234 35.34l-.05-.109c-.055-.063-.057-.135 0-.197a.1.1 0 0 0 .045 0c.11.101.014.206.005.306");
}

.b2hw40b6c {
  fill: var(--svg-color--3d270b, #3d270b);
  d: path("m13.177 38.911l-.082.008c-.099-.021-.101-.071-.035-.139c-.018-.033-.016-.056.006-.078q.057.1.111.209");
}

.b2uqypspv {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M24.25 36.02v.103c.006.127.047.248.039.377l.023.209c-.043.005-.086.076-.127-.004l-.037-.104c-.086-.104-.049-.23-.08-.345c-.03-.127-.073-.255-.102-.374c-.023-.121-.066-.24-.074-.361l-.012-.086c-.088-.092-.088-.209-.1-.318l-.002-.09c-.021-.014-.057-.031-.053-.049c.025-.18-.1-.314-.131-.474c-.017-.074-.025-.155-.047-.226c.008-.117-.05-.232-.033-.351l-.006-.075c-.066-.066-.024-.152-.041-.224a1 1 0 0 0-.056-.105c.005-.104-.004-.204.005-.312c.036-.053.061-.104-.027-.135c-.049-.074-.006-.168-.06-.244c-.037-.063-.002-.139-.019-.213a4 4 0 0 1-.01-.234c-.047-.253-.144-.505-.056-.77c.13-.047.161.063.216.133c.043.115.139.039.207.062a.2.2 0 0 1 .047.06c.045.207-.059.438.069.631c-.004.188-.03.363.013.539c.004.07.008.145.027.209c.014.158-.018.316.023.475c0 .132.006.257.031.382c.006.097-.01.193.021.285c.018.077-.007.163.021.233a.4.4 0 0 0 .061.145c.057.094.057.198.057.303c0 .086.033.174.028.267c.022.067.055.136.05.221c.069.147.03.327.135.46");
}

.b3_zdczbu {
  fill: var(--svg-color--515252, #515252);
  d: path("M15.816 34.878q-.098.047-.199.101c.006-.167.099-.144.199-.101");
}

.b3mqvbcsh {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("M14.78 33.15v.149c-.116.098-.071.281-.197.376l-.016.073c-.038.094-.035.197-.102.283l.002-.004c-.043.07-.045.152-.08.229a.6.6 0 0 0-.063.209c-.037.064-.021.146-.076.207c-.134-.026-.151-.121-.136-.23c.015-.092.041-.174.042-.263c0-.017.003-.032.003-.054c.094-.078.07-.207.124-.31c-.004-.086.026-.175.03-.265c0-.018.002-.03.004-.053a.58.58 0 0 0 .066-.359a.7.7 0 0 1 .067-.225c.063-.086.022-.207.071-.303c.018-.065.035-.136.055-.203c-.039-.14.036-.271.023-.414q0-.033.013-.066a.14.14 0 0 1 .097-.034c.1.017.158-.078.247-.092a.1.1 0 0 1 .062.036c.013.02.021.048.027.068c.004.155-.09.297-.054.448l-.002.048c-.07.073-.065.174-.085.26c-.055.109-.028.231-.083.338c-.023.048-.058.094-.039.151");
}

.b4d69dc2x {
  fill: var(--svg-color--f1f0ed, #f1f0ed);
  d: path("M23.05 18.762v-.071c.016-.063.045-.109.105-.133c.094-.052.182-.043.264.04c.02.017.037.04.057.06c.021.063.041.129.015.191a.5.5 0 0 1-.125.157a.28.28 0 0 1-.196.009a.27.27 0 0 1-.142-.143a.1.1 0 0 1 .022-.11");
}

.b4hvjk9re {
  fill: var(--svg-color--f5d429, #f5d429);
  d: path("M18.315 21.751q.13-.093.26-.193c.055-.083.083-.176.16-.238c.005-.025-.004-.052.009-.072c.019-.031.043-.021.042.013c-.023.231.139.366.266.514c-.198.13-.595.119-.737-.024");
}

.b4m0icbvi {
  fill: var(--svg-color--ececec, #ececec);
  d: path("M19.361 29.29c-.06.021-.114.021-.154-.035c-.052-.051-.046-.098-.003-.149a.2.2 0 0 1 0-.042a.54.54 0 0 1 .072-.322c.045-.035.109-.055.137-.113l-.006.009c.055-.041.085 0 .118.03q.016.032.017.066a.6.6 0 0 0 .004.233a.2.2 0 0 1-.019.065c-.038.094-.116.174-.171.258z");
}

.b4mz_hbgb {
  fill: var(--svg-color--e5e6e6, #e5e6e6);
  d: path("M16.199 29.838c.237-.095.351-.322.535-.472c.011-.027.032-.041.062-.027c.104.083.041.195.059.294q0 .062-.03.11c-.075.084-.188.088-.274.137c-.08.012-.16.004-.233.031c-.046-.022-.151.057-.119-.073");
}

.b4wnz5zdk {
  fill: var(--svg-color--323230, #323230);
  d: path("M18.528 19.374q.189.008.379.021a1 1 0 0 0-.018.122c-.117-.09-.242-.09-.363-.003z");
}

.b56pa_bhj {
  fill: var(--svg-color--666, #666);
  d: path("m24.675 35.546l.051-.211a1.1 1.1 0 0 1 .037.432c-.017.018-.017.057-.051.061a.4.4 0 0 1-.037-.282");
}

.b69hrf7nz {
  fill: var(--svg-color--897717, #897717);
  d: path("M20.654 22.22c-.072 0-.146.023-.205-.04c-.017-.013-.022-.022-.017-.04q.006-.019.017-.02c.079.01.195-.053.205.1");
}

.b6xb6u0uu {
  fill: var(--svg-color--222, #222);
  d: path("m15.491 32.15l.016-.011c.051-.015.096-.019.114.041c.015.015.019.032.013.04q-.014.012-.023.012c-.113.059-.07.184-.105.272q-.022.036-.047 0q.014-.174.032-.354");
}

.b74sybcjz {
  fill: var(--svg-color--52190a, #52190a);
  d: path("M15.24 25.485c-.103.07-.22.12-.304.231c.006-.208.124-.264.304-.231");
}

.b7k-lo26y {
  fill: var(--svg-color--f1f1f1, #f1f1f1);
  d: path("M15.03 35.14c.122-.08.183-.215.272-.325c.104-.035.203-.07.312-.078c.091-.023.183-.047.264.029c.019.041.007.073-.021.102c-.075.051-.172.056-.227.133c-.074.072-.131.154-.205.222c-.123.086-.123.237-.199.349a.5.5 0 0 1-.131.139a.28.28 0 0 1-.225.015c-.044.03-.084.034-.126-.008c-.092-.119.026-.155.084-.209l.157-.198c0-.065.019-.116.045-.171");
}

.b8-d7dbow {
  fill: var(--svg-color--f5d328, #f5d328);
  d: path("M19.19 19.344c.007.015.012.035.018.051c.047.06.043.129.045.197a.74.74 0 0 1 0 .325q.022.055.051.106c-.123.005-.24.013-.361.017c-.051-.021-.066-.063-.069-.113c.022-.036.046-.063.069-.098c.047-.106.039-.209-.051-.295l-.004-.018a.24.24 0 0 1-.035-.1a.3.3 0 0 1 .039-.098a.18.18 0 0 0-.004-.201c-.019-.031-.037-.06-.043-.095a.3.3 0 0 1-.004-.104l.023-.067c.047-.06.055-.112-.007-.169c-.039-.047-.065-.098-.056-.161a.3.3 0 0 1 .043-.094a.2.2 0 0 0 .037-.161c-.008-.039-.021-.086-.002-.125c.043-.113.18-.122.239-.221c.101.059.046.156.048.236c.02.399-.017.79.024 1.188");
}

.b8x2vrm6l {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M19.1 28.663c.002-.021-.002-.031-.016-.043a.1.1 0 0 0 .028-.021a.08.08 0 0 1 .067.004c.021.013.039.022.051.04c.009.027.017.047.02.07c0 .109-.05.221-.021.33a.2.2 0 0 1-.016.068c-.07.074-.113.188-.244.164l-.027-.022c-.01-.067-.077-.13-.01-.202c.002-.055.008-.113.008-.172c.108-.034.069-.173.16-.216");
}

.b8x2wqbvm {
  fill: var(--svg-color--d9c025, #d9c025);
  d: path("M14.931 37.547c-.058-.027-.031-.056.008-.073c.02-.052.033-.111.109-.088q.046-.001.094.004c.117-.02.139.048.125.146a.08.08 0 0 1-.063.039c-.09-.008-.187.043-.273-.028");
}

.b9_3__94s {
  fill: var(--svg-color--343535, #343535);
  d: path("M14.742 30.845c-.022.154.026.318-.056.462q-.026.033-.051 0c-.099-.203.059-.386.045-.577q.032.056.062.115");
}

.ba44mob3o {
  fill: var(--svg-color--e9ca26, #e9ca26);
  d: path("M14.158 21.06c-.122-.026-.229.129-.356.026c.02-.059.045-.112.065-.164c.067-.031.083-.18.202-.09c.065.063.149.119.089.228");
}

.bbkysfb_e {
  fill: var(--svg-color--3e370f, #3e370f);
  d: path("M20.449 22.12v.061l-.255-.021q.03-.022.056-.047z");
}

.bcpwcwbsq {
  fill: var(--svg-color--1f1f1f, #1f1f1f);
  d: path("M19.524 29.624c.018.072.031.14.048.214h-.168c.024-.074.045-.142.065-.214q.031-.021.055 0");
}

.bdbjudb1l {
  fill: var(--svg-color--606161, #606161);
  d: path("M21.866 34.713c-.088.075-.182.063-.271.006c.032-.017.065-.028.1-.048a.18.18 0 0 1 .171.042");
}

.bexlohahv {
  fill: var(--svg-color--192222, #192222);
  d: path("m19.286 37.39l-.021-.004c-.084-.043-.104-.123-.104-.21l.021.004z");
}

.bfhbpvb9p {
  fill: var(--svg-color--2f3030, #2f3030);
  d: path("M17.13 27.512q-.001-.171-.005-.351h.063c-.034.119.011.244-.058.351");
}

.bfsbhkble {
  fill: var(--svg-color--e5c927, #e5c927);
  d: path("M21.998 40.43c-.08-.033-.194.054-.245-.075c-.023-.189.137-.104.211-.148c.114.06.094.134.034.223");
}

.bfuxpebqv {
  fill: var(--svg-color--470e09, #470e09);
  d: path("M22.06 25.464c-.086-.01-.17-.027-.254-.038c-.02-.013-.024-.022-.02-.035c.004-.008.012-.017.018-.017c.086.009.188-.031.26.048q.03.018.019.032a.04.04 0 0 1-.023.01");
}

.bg6oe_b7z {
  fill: var(--svg-color--4b4c4b, #4b4c4b);
  d: path("M21.284 17.663a.1.1 0 0 1 0-.057c.122-.074.24-.129.322.053c-.109-.076-.218-.068-.322.004");
}

.bgnapjb2c {
  fill: var(--svg-color--3d1615, #3d1615);
  d: path("M16.65 34.436c.004.022.004.05.008.074l.021.151c-.17-.054-.082-.143-.029-.225");
}

.bhhtc7vjl {
  fill: var(--svg-color--252626, #252626);
  d: path("M23.832 29.378c.115.105-.083.248.04.354q-.025.033-.052.006c-.069-.072-.039-.168-.056-.25c.023-.04.044-.071.068-.11");
}

.bhj4pebuk {
  fill: var(--svg-color--464747, #464747);
  d: path("M20.544 40.657c.021-.019.036-.043.057-.065c.02.069.035.144.056.213h-.054c-.059-.038-.049-.092-.059-.148");
}

.bi_qll1_s {
  fill: var(--svg-color--574545, #574545);
  d: path("M12.903 26.1a.9.9 0 0 1-.094.381c-.049-.062-.031-.13-.006-.197c-.001-.078.025-.148.1-.184");
}

.bibi__bgi {
  fill: var(--svg-color--4b4b4b, #4b4b4b);
  d: path("M16.82 40.591c.017.021.034.048.051.066c-.004.056-.008.108-.051.157c-.015-.021-.031-.045-.052-.062q.03-.077.052-.161");
}

.bjgawrbhm {
  fill: var(--svg-color--252525, #252525);
  d: path("M13.01 32.2h.047c-.004.135.131.272.011.414c-.062-.13-.062-.275-.058-.414");
}

.bl2nocbcd {
  fill: var(--svg-color--44412e, #44412e);
  d: path("M17.12 17.819h.055c.159.2.314.074.473-.009c-.037.118.095.099.127.161c-.006.07-.063.098-.119.118a1.5 1.5 0 0 1-.438-.005a.6.6 0 0 1-.193-.086q-.03-.035-.006-.08q.05-.041.101-.099");
}

.bl484_cfm {
  fill: var(--svg-color--242424, #242424);
  d: path("M14.25 31.2c.017.074-.036.138-.053.207l-.021-.004h-.021c-.002-.074-.004-.146.056-.205q.017-.044.039.002");
}

.bl7mmqbxm {
  fill: var(--svg-color--4c5252, #4c5252);
  d: path("M17.647 31.944c.017-.365-.051-.73.035-1.094c.013.371.081.733-.035 1.094");
}

.bls8vv53a {
  fill: var(--svg-color--392626, #392626);
  d: path("M19.574 25.577c.083.041.169.061.235.041q-.093.127-.19.252c-.083-.061.128-.188-.054-.232q-.021-.027-.012-.041q.009-.02.021-.02");
}

.bm8d03ycl {
  fill: var(--svg-color--1b1010, #1b1010);
  d: path("M13.989 34.979c-.014-.021-.03-.038-.043-.059q.004-.132.01-.26q.05-.001.102.004c-.079.098-.026.214-.069.315");
}

.bnanvfb2n {
  fill: var(--svg-color--666565, #666565);
  d: path("m23.353 32.884l-.019.004l-.013-.012c-.084-.075-.079-.161-.006-.25c.072.054.035.137.047.201c.032.029.026.045-.009.057");
}

.bnhv__bay {
  fill: var(--svg-color--3d4647, #3d4647);
  d: path("M12.485 36.659c-.016 0-.027-.004-.04-.004l.004-.646c.06.212.043.432.036.65");
}

.boknrcb3w {
  fill: var(--svg-color--1a1919, #1a1919);
  d: path("m12.02 31.936l.018.612c.029.035.07.063.045.117h-.003l-.022-.004c-.172-.228-.052-.487-.08-.729q.021-.033.042.004");
}

.boyou-b0o {
  fill: var(--svg-color--2e0303, #2e0303);
  d: path("M20.601 29.15q.008-.033.009-.06c.19.051.053.208.103.303a1 1 0 0 0-.104-.031a.14.14 0 0 1-.047-.105c-.002-.044.017-.075.039-.107");
}

.bqvzzblie {
  fill: var(--svg-color--282c2c, #282c2c);
  d: path("M18.12 29.32h.051q.017-.006.035-.005c0 .106.002.218.004.322c-.074-.092-.067-.206-.09-.317");
}

.bsb-5kkaj {
  fill: var(--svg-color--56310d, #56310d);
  d: path("M22.843 37.866h-.113c-.045-.153-.268-.053-.303-.218c.164-.018.293.066.42.153c.015.016.017.025.013.042q-.012.022-.017.023");
}

.bskmz77gf {
  fill: var(--svg-color--581817, #581817);
  d: path("M15.983 29.829c.046.063.098.028.15.009c.106.086.229.008.344.032a1 1 0 0 0 .173-.021a.4.4 0 0 1 .103 0a.45.45 0 0 0 .199.013a.53.53 0 0 0 .268-.13c.092-.024.107.063.162.105c.094.062.196.028.299.024c.057 0 .111.004.168 0c.072.008.139.019.207 0c.062-.017.125-.029.19-.017c.045.004.081.03.106.067a.3.3 0 0 1 .041.138c.023.836.007 1.674.009 2.507c0 .09-.009.172-.062.251c-.027.026-.053.034-.089.019c-.087-.115-.069-.25-.069-.379c-.002-.526.006-1.05-.006-1.57c-.006-.249.111-.559-.07-.736c-.176-.165-.479-.046-.729-.059c-.431-.021-.867.031-1.299-.031a.17.17 0 0 1-.105-.092c-.022-.046-.03-.091.01-.13");
}

.bt87hkldk {
  fill: var(--svg-color--f3f3f3, #f3f3f3);
  d: path("M21.79 32.2c-.083 0-.122-.074-.191-.104a1 1 0 0 1-.101-.333c-.034-.202-.086-.403-.021-.612c.076.04.149.067.224-.004l.054-.05c.098-.015.094.069.11.129a1 1 0 0 0 .039.188q.027.134.062.269c.037.081-.047.171-.002.263q-.03.033-.053.067c-.042.064-.015.165-.121.187");
}

.btwhynb2c {
  fill: var(--svg-color--444443, #444443);
  d: path("M19.19 19.344c-.105-.129-.042-.279-.049-.42c-.018-.33-.018-.668-.021-1c.027-.005.057-.015.082-.022l-.012 1.444");
}

.bu1qoybxe {
  fill: var(--svg-color--f9f9f8, #f9f9f8);
  d: path("M15.876 36.559c-.005.048-.014.092-.056.119c-.103.108-.149.014-.208-.052c.055-.079-.051-.075-.057-.121c-.069-.057-.117-.121-.117-.213a3 3 0 0 1 .005-.288a.6.6 0 0 1 .045-.181l.032-.064c.048-.064.109-.119.166-.18a.4.4 0 0 1 .08-.064c.104-.055.154.004.185.1a.2.2 0 0 1-.013.065c-.063.091-.055.188-.023.282c.018.06.036.113.057.169c.026.063.058.134.037.209c-.043.079-.064.165-.133.219");
}

.buat5obco {
  fill: var(--svg-color--101008, #101008);
  d: path("M24.312 38.751c.016 0 .035.006.056.006c.017.07.048.148-.062.169c-.006-.021-.006-.046-.01-.071z");
}

.buf4h7bjy {
  fill: var(--svg-color--7e7647, #7e7647);
  d: path("M21.909 18.347h.049c-.003.07-.003.136-.003.208c-.03.042-.065.069-.118.069c-.084-.026-.107-.088-.105-.172c.035-.076.096-.105.177-.105");
}

.bvgb68t6u {
  fill: var(--svg-color--0f0d04, #0f0d04);
  d: path("m13.06 38.12l.055.052c-.016.034-.032.073-.051.108c-.059.063-.133.061-.209.041l.002-.024c.074-.056.083-.177.203-.177");
}

.bvp1kgbyp {
  fill: var(--svg-color--432009, #432009);
  d: path("M22.326 36.87c.265.129.438.354.615.57c-.128.094-.181-.023-.257-.089q-.024-.04.002-.069c-.118-.136-.235-.272-.36-.412");
}

.bwg_n0b3l {
  fill: var(--svg-color--181717, #181717);
  d: path("m17.12 28.682l-.009-.114c.022.004.047.004.065.008c.012.008.021.017.028.017q.033.04.052.086a.2.2 0 0 1 .004.069c-.013.047-.037.084-.08.104c-.055.011-.082-.021-.1-.067q.02-.055.04-.103");
}

.bwxcxacrk {
  fill: var(--svg-color--727477, #727477);
  d: path("M15.658 19.214c-.183-.114-.083-.268-.056-.413c.045.043.037.095.011.146c.034.085-.028.189.045.267");
}

.by26s31bi {
  fill: var(--svg-color--3b3816, #3b3816);
  d: path("M21.18 20.763c.035 0 .075-.005.112-.005a1 1 0 0 1 .052.099c-.043.021-.093.036-.141.055c.033-.057.003-.103-.023-.149");
}

.by9ndtbon {
  fill: var(--svg-color--535353, #535353);
  d: path("m24.285 29.16l-.017.006l-.014-.006c-.072-.123-.134-.24-.057-.387c.068.119.129.242.088.387");
}

.bz89blbar {
  fill: var(--svg-color--3b241c, #3b241c);
  d: path("M23.94 21.02h.054q.024.047.047.103c-.073.004-.157.041-.212-.043c.022-.056.051-.089.111-.06");
}

.bzklo3bnp {
  fill: var(--svg-color--232222, #232222);
  d: path("M18.786 29.885q-.026-.025-.045-.047c.035-.122.074-.244.109-.369a.1.1 0 0 0 .041 0c.002.086.004.168.004.255c-.007.07-.037.133-.109.161");
}

.bzpr4hn5m {
  fill: var(--svg-color--272828, #272828);
  d: path("M13.897 34.15c-.116-.191-.033-.369.048-.543c.076.195-.005.367-.048.543");
}

.c_odhp7ro {
  fill: var(--svg-color--1e0604, #1e0604);
  d: path("m21.904 39.38l.103.008c.01.066.033.143 0 .213l-.099-.113c-.028-.036-.033-.071-.004-.108");
}

.c-_2rok3s {
  fill: var(--svg-color--545454, #545454);
  d: path("M14.308 33.817c-.057.105.039.274-.147.312c.022-.103.026-.218.092-.312q.028-.027.055 0");
}

.c-1tmfb6w {
  fill: var(--svg-color--5a0404, #5a0404);
  d: path("M24.665 26.69a.56.56 0 0 1-.096-.33c.172.068.085.213.096.33");
}

.c-i2bvo8w {
  fill: var(--svg-color--373838, #373838);
  d: path("m14.901 31.778l.035.039c-.051.078-.072.205-.207.102q-.023-.025-.006-.057a.18.18 0 0 1 .178-.084");
}

.c-urjnc9l {
  fill: var(--svg-color--474848, #474848);
  d: path("M12.709 35.788c-.004.08-.014.153-.017.232c-.1 0-.063-.063-.057-.115l.018-.244c.112.008.056.082.056.127");
}

.c0t1ahpkt {
  fill: var(--svg-color--42270b, #42270b);
  d: path("M22.486 40.22c-.12.079-.021.142.015.217c-.059.056-.113.108-.175.159a.95.95 0 0 0 .045-.415a1 1 0 0 1 .103-.009a.1.1 0 0 1 .012.048");
}

.c1o3xcb2e {
  fill: var(--svg-color--434242, #434242);
  d: path("m24.985 32.827l-.025.004l-.025-.004a.32.32 0 0 1 .049-.229c.068.093.048.165.001.229");
}

.c39bw-ndt {
  fill: var(--svg-color--232424, #232424);
  d: path("M19.356 37.665a.6.6 0 0 1-.092-.279l.022.004c.051.086.115.166.07.275");
}

.c3wwmibtc {
  fill: var(--svg-color--49280d, #49280d);
  d: path("M13.274 21.325c.177.045.367-.057.535.059q-.03.04-.07.007a10 10 0 0 1-.465-.021q-.024-.01-.016-.025q.011-.02.016-.02");
}

.c44cye-9v {
  fill: var(--svg-color--2d0605, #2d0605);
  d: path("M14.993 29.13c-.08-.074-.16-.141-.199-.242c.135.027.178.126.199.242");
}

.c5o45cbwi {
  fill: var(--svg-color--452e2e, #452e2e);
  d: path("M24.877 27.473h.044a.34.34 0 0 1 .053.291a.54.54 0 0 1-.097-.291");
}

.c6mfnfbnn {
  fill: var(--svg-color--361309, #361309);
  d: path("M22.494 25.694c-.094-.014-.138-.087-.173-.164c.114-.011.145.072.173.164");
}

.c6x5cix3g {
  fill: var(--svg-color--4a4c4c, #4a4c4c);
  d: path("m12.183 31.04l.095-.271c.036.008.036.035.05.061l-.083.211q-.033.04-.062-.001");
}

.c77lvwqlp {
  fill: var(--svg-color--553a39, #553a39);
  d: path("m14.416 34.24l-.047.008c.017-.082.024-.164.101-.215c.018.077.015.15-.054.207");
}

.c79net9cd {
  fill: var(--svg-color--625f51, #625f51);
  d: path("M14.36 20.993v.02h-.047a3 3 0 0 1-.09-.2c.114.008.102.115.137.18");
}

.c7b510btj {
  fill: var(--svg-color--3c3d3d, #3c3d3d);
  d: path("M24.26 33.35c.06.084.055.169 0 .251z");
}

.c7dxh7bkr {
  fill: var(--svg-color--212121, #212121);
  d: path("m13.429 27.892l-.055.003c.038-.176.152-.313.217-.476c.101.006.07.068.051.121c-.027.119-.043.246-.107.351q-.054.05-.106.001");
}

.c7haj4_uc {
  fill: var(--svg-color--c6c7c8, #c6c7c8);
  d: path("M17.64 18.04c.052-.006.11 0 .133-.066q.078.005.156.004a.16.16 0 0 1 .146.122a.08.08 0 0 1-.039.069c-.105.061-.218.013-.327.021c-.065-.004-.133.004-.2-.016a.1.1 0 0 1-.039-.066c.033-.087.119-.029.17-.068");
}

.c80b78b2t {
  fill: var(--svg-color--1d1e1e, #1d1e1e);
  d: path("M14.05 31.739c-.043-.109.039-.186.063-.274c.051.052.036.114.034.169c-.03.039-.066.072-.097.105");
}

.c840mtb_o {
  fill: var(--svg-color--5f2c2b, #5f2c2b);
  d: path("M19.771 41.585a.07.07 0 0 1 .043.005c.004.083-.031.146-.117.153c-.064.012-.084-.037-.09-.09c.078.035.126-.004.164-.068");
}

.c9-4ikbzk {
  fill: var(--svg-color--635e33, #635e33);
  d: path("M15.14 20.671h.16c.017.004.026.021.032.035a.1.1 0 0 1-.004.052q-.008.03-.034.036c-.091.035-.125-.036-.168-.086c-.011-.02-.006-.037.014-.037");
}

.ca0_3cbzt {
  fill: var(--svg-color--414141, #414141);
  d: path("M19.308 27.932c.065 0-.014.222.137.099q.044.013.051.055c0 .113-.063.197-.156.252q-.04.002-.074-.008c-.063-.08-.012-.182-.033-.269a.07.07 0 0 1 .023-.062c.016-.02.03-.047.052-.067");
}

.caeoy6byj {
  fill: var(--svg-color--5b2e2e, #5b2e2e);
  d: path("M18.474 27.817c-.105-.113-.125-.259-.147-.404c.127.107.141.256.147.404");
}

.cafyklbxa {
  fill: var(--svg-color--212121, #212121);
  d: path("m12.606 33.653l-.055.06l-.013-.146l.045-.104c.012.063.016.126.023.19");
}

.cb14zdexr {
  fill: var(--svg-color--352526, #352526);
  d: path("M16.952 31.46h-.039c-.075-.125-.024-.188.104-.211c-.033.065-.07.133-.065.211");
}

.cbewpk44i {
  fill: var(--svg-color--c9caca, #c9caca);
  d: path("m18.474 27.817l.004.225c-.023.02-.047.02-.07.013c-.109-.075-.165-.192-.24-.294c-.02-.15-.107-.295-.02-.444c.086-.043.138-.011.164.067c.002.015.004.023.015.029c.067.129.104.268.147.404");
}

.cbjufv00o {
  fill: var(--svg-color--5e5e5e, #5e5e5e);
  d: path("M20.234 35.34v.269c-.067.013-.104-.021-.134-.071c-.029-.108-.051-.221.051-.303c.087-.014.051.072.083.105");
}

.ccyrqebko {
  fill: var(--svg-color--fad428, #fad428);
  d: path("M21.574 25.53c.004-.039-.015-.094.047-.104c.07-.004.138-.042.207-.027c.086 0 .173 0 .249.056a.7.7 0 0 1 .248.082l-.003-.004c.075.035.118.105.173.162c.012.008.023.02.032.027c-.037.143.038.294-.032.432c-.063.047-.1 0-.131-.035c-.117-.146-.236-.109-.355-.013l-.052.013c-.178 0-.354-.013-.53-.004a.4.4 0 0 0-.218.152c-.052.042-.103.089-.176.082a.12.12 0 0 1-.093-.07a.14.14 0 0 1 .017-.113c.011-.021.019-.035.026-.055c.226-.159.349-.426.591-.581");
}

.cd8m28mgg {
  fill: var(--svg-color--1a1506, #1a1506);
  d: path("M24.558 38.33q0-.022.004-.035c.041-.065.104-.035.16-.041c.01.033.049.066-.01.093c-.054-.005-.106-.015-.154-.017");
}

.cdf3thu-c {
  fill: var(--svg-color--430907, #430907);
  d: path("M17.226 35.827q.096 0 .199-.015c.043-.03.08-.03.117.011c-.07.067-.165.049-.25.049c-.056.026-.066 0-.066-.045");
}

.ce4wnmbnf {
  fill: var(--svg-color--592726, #592726);
  d: path("m20.397 28.544l-.092-.264c.136.045.157.139.092.264");
}

.cf3wgj0mz {
  fill: var(--svg-color--39302f, #39302f);
  d: path("M12.595 37.08c.098.09.105-.029.153-.062q.04.02.013.062c-.004.115-.078.119-.166.104l-.008-.044c-.011-.023-.011-.039.008-.06");
}

.cf8lxshki {
  fill: var(--svg-color--716213, #716213);
  d: path("M20.97 22.07c-.136-.024-.26-.076-.397-.06c-.067.008-.115-.024-.119-.103q.233-.005.474-.004c.042.024.072.052.072.107a.1.1 0 0 1-.03.06");
}

.cfo67fb-a {
  fill: var(--svg-color--492a2a, #492a2a);
  d: path("m15.824 33.21l.06-.379c.094 0 .121.074.15.146c.005.232.074.464-.051.688c-.04.209.056.426-.059.629c.004-.336.008-.676.014-1.01c0-.093-.023-.135-.114-.074");
}

.cg-x_2xsm {
  fill: var(--svg-color--524c20, #524c20);
  d: path("M21.536 20.448q.003-.157.01-.311q.017-.037.051-.016c.043.084-.066.203.063.273c-.026.058-.075.054-.124.054");
}

.cg1dn3fcp {
  fill: var(--svg-color--392929, #392929);
  d: path("M22.97 25.896c.017-.022.027-.043.039-.063c.047.091.084.182.043.283c-.082-.054-.06-.144-.082-.22");
}

.ch2jcpbir {
  fill: var(--svg-color--ddc126, #ddc126);
  d: path("m12.806 38.497l-.127.147a.12.12 0 0 1-.082.032c-.133-.078-.084-.163-.004-.243l.002-.006c.061-.073.111-.177.237-.117a.1.1 0 0 1 .04.06a2 2 0 0 1-.066.127");
}

.chk7pibyh {
  fill: var(--svg-color--5a4211, #5a4211);
  d: path("M15.925 18.816c-.017 0-.033.005-.048.005c.003-.084.027-.154.103-.197c.013.076-.025.134-.055.192");
}

.ci8ndod_i {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("m22.897 28.399l.004-.013c.033-.108.004-.231.04-.336c.016-.047.088-.079.058-.15c.014-.118.057-.231.105-.338v-.012c.035-.161.101-.312.131-.468c-.02-.209.044-.418-.043-.613c-.035-.086-.096-.168-.092-.271c-.018-.022-.035-.056-.051-.082c-.033-.09-.029-.197-.072-.287c.016-.137-.053-.291.065-.418c.099-.09.216-.07.332-.045q.009.017.024.008c.1-.008.171.037.244.102q.012.015.027.004c.075.029.161.024.225.08c.103.02.168.122.279.135c.096.104.213.202.279.336c.07.09.141.18.107.307c-.004.007-.004.019.008.023c.089.09.043.228.097.329c-.03.091.022.169.056.251c.028.067.045.146.076.208c.039.103.057.22.104.322c.035.089.049.192.072.291l.004.007c.065.11.065.232.101.35q-.009.02.011.027c.018.114.09.264-.142.213a.74.74 0 0 1-.248-.232c-.04-.065-.063-.148-.119-.207a1 1 0 0 1-.069-.121c-.023-.08-.063-.15-.088-.229c.006-.091-.074-.13-.113-.193c-.021-.027.02-.004-.008-.027c-.013.031.008.057.008.08c.012.063.035.122.048.186c.02.116.03.243-.013.356c-.037.071-.098.099-.168.104c-.072-.011-.119-.056-.166-.104c-.043-.043-.047-.114-.095-.157c-.038-.178-.128-.337-.169-.511c-.001-.017.01-.032.01-.047c-.013 0-.021.017-.015.036q.075.28.196.55c.016.021.023.04.023.067c-.012.117.038.225.047.34c-.004.138.031.285-.047.414c-.136.095-.166-.013-.199-.109c-.004-.086-.054-.166-.054-.25c-.006.085.048.165.05.25c.024.104.061.199.01.309c-.026.053-.075.051-.123.038c-.108.032-.062.188-.17.216c-.024.008-.049 0-.068-.009c-.04-.038-.032-.09-.043-.133a.36.36 0 0 1-.018.179a.14.14 0 0 1-.111.073c-.105-.04-.157.032-.202.108c-.084.104-.126.232-.207.338a.3.3 0 0 1-.134.072c-.137.049-.291.047-.436.078c-.084.021-.173.034-.213.129c-.051.08-.094.162-.168.224c-.066.051-.145.079-.208.146c-.062.06-.125.098-.216.055c-.115-.125-.082-.266-.055-.416c.055-.079.082-.182.154-.254c.006-.076.108-.061.125-.129a.6.6 0 0 1 .275-.179c.083-.047.184-.038.262-.098c.207-.2.412-.413.582-.646c-.002-.099.067-.169.104-.257m-8.63-2.07c.011.076-.084.113-.057.188c-.123.212.02.448-.047.667c.018.053.032.109.051.165c.057.071.106.146.1.244q-.008.016.008.04c.07.109.105.234.121.369c.064.224.068.467.197.672a.47.47 0 0 0 .156.208c.066.082.166.132.198.243c.062.134.216.156.317.244c.07.026.164.021.215.094c.188.031.268.208.406.307c.074.188.105.381.016.574a.1.1 0 0 1-.071.043c-.138-.012-.196-.152-.313-.205c-.079-.055-.123-.137-.184-.208c-.041-.046-.076-.104-.145-.122c-.104-.015-.204-.055-.311-.059a.6.6 0 0 1-.211-.055c-.154-.084-.217-.236-.293-.377c-.037-.063-.07-.137-.128-.185c-.067-.021-.112.058-.178.034c-.14-.118-.017-.279-.043-.43a.5.5 0 0 1-.056.269c-.082.047-.141.013-.16-.062c-.028-.115-.117-.07-.184-.099a.4.4 0 0 1-.037-.067c-.017-.086.027-.174.023-.259c.004-.059.02-.11.035-.169a.6.6 0 0 0-.035.145c-.023.135-.048.265-.217.115c-.059-.134-.026-.279-.034-.42c-.006-.117.042-.216.06-.33c.03-.125.082-.246.121-.363c.041-.092.096-.18.1-.281l-.002.031c-.008.06-.045.103-.057.158a9 9 0 0 0-.209.476c-.052.09-.109.159-.228.142c-.199-.099-.136-.279-.142-.443c.017-.096.045-.188.07-.299c-.063.1-.13.181-.126.295c-.002.026-.007.045-.012.07c-.026.059-.067.114-.104.17a.26.26 0 0 0-.105.192c-.077.128-.139.264-.295.312a.2.2 0 0 1-.119-.021c-.085-.056-.037-.146-.045-.224c.041-.11.054-.236.121-.338c.02-.063.039-.117.062-.181c.021-.103.024-.208.097-.294q.016-.006.008-.023c.02-.125.043-.248.105-.354h-.005c0-.104.026-.205.06-.304c.023-.045.017-.102.028-.151c.034-.126.06-.248.115-.364c.155-.275.387-.461.669-.578c.087-.043.173-.086.268-.099c.039.004.067-.017.082-.051c.148-.028.31-.095.445.051l-.007-.007c.147.16.095.318.011.479l-.013.114c-.034.098-.018.221-.092.311");
}

.ciz7hj8dw {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M15.503 36.31c-.074-.089-.029-.193-.045-.292c-.02-.052.006-.063.051-.052c-.002.116-.006.227-.006.344");
}

.cjy_9q0lt {
  fill: var(--svg-color--0b0c0c, #0b0c0c);
  d: path("M20.866 29.838c.107-.009.216.133.322-.005c.043-.004.086-.004.104.048c-.126.112-.273.04-.416.051c-.042-.027-.035-.064-.01-.094");
}

.ckjqf4o0c {
  fill: var(--svg-color--515353, #515353);
  d: path("M23.978 35.872h-.035c-.056-.113-.123-.219-.054-.351c.063.113.108.222.089.351");
}

.clnckdzbs {
  fill: var(--svg-color--121313, #121313);
  d: path("M12.373 35.811a1 1 0 0 1 .078-.063c.091.065.035.134-.002.192a1 1 0 0 1-.058-.071c-.007-.024-.011-.04-.018-.058");
}

.clnjmob4i {
  fill: var(--svg-color--404141, #404141);
  d: path("m19.772 17.922l-.045-.308a1 1 0 0 1 .095-.008l.039.299c-.02.047-.053.043-.089.017");
}

.clq_wc-xp {
  fill: var(--svg-color--c3c8cb, #c3c8cb);
  d: path("M16.14 18.18q-.003-.029-.004-.061c-.005-.012 0-.026.002-.037c.018-.006.034-.006.049-.017l.002.027c.021.008.024.021.021.03q-.009.014-.02.014a.4.4 0 0 1-.05.044");
}

.cmd6sobvz {
  fill: var(--svg-color--f1f1f1, #f1f1f1);
  d: path("M18.505 19.552q.024-.015.021-.039c.097-.174.226-.146.365-.063q.03.03.051.066c.046.086.07.176.055.279a.24.24 0 0 1-.079.133a.1.1 0 0 1-.073 0a1 1 0 0 1-.104-.066c-.103-.016-.242.103-.291-.09c.016-.076-.043-.166.055-.22");
}

.cmld1syoi {
  fill: var(--svg-color--333c3c, #333c3c);
  d: path("m12.328 35.1l.015-.243c.053.091.049.185.037.282a.2.2 0 0 1-.045-.008q-.013-.02-.007-.031");
}

.cngnhofbh {
  fill: var(--svg-color--453a0f, #453a0f);
  d: path("M24.14 37.967h.113l.092.06a.5.5 0 0 0 .014.094c-.002.037-.034.041-.057.053c-.114-.017-.115-.134-.162-.207");
}

.cnjisaclt {
  fill: var(--svg-color--502322, #502322);
  d: path("M24.877 27.473c-.05-.103-.112-.196-.106-.317c.018-.02.033-.02.041.008c.09.084.09.201.109.311q-.023.04-.044-.002");
}

.co4lown0e {
  fill: var(--svg-color--4e4710, #4e4710);
  d: path("M16.228 17.995q.007-.038.02-.08c.083.023.18-.004.25.067c.014.021.018.036 0 .056a.34.34 0 0 1-.234.026a.12.12 0 0 1-.049-.047c.001-.004.007-.018.013-.022");
}

.co71aebxe {
  fill: var(--svg-color--313232, #313232);
  d: path("M20.866 18.02c-.016-.032-.027-.063-.043-.095c.102.008.199.042.302-.006q0 .048.003.097c-.003.026-.023.042-.049.054c-.08.025-.158.039-.213-.05");
}

.cpe05h04h {
  fill: var(--svg-color--f0cf28, #f0cf28);
  d: path("M18.944 16.923c.184.086.342.197.357.425a.17.17 0 0 1-.1.054c-.041 0-.081 0-.121-.015c-.072-.028-.158-.032-.216-.099a.14.14 0 0 1-.022-.08c.025-.096-.07-.241.102-.285");
}

.cpfghubrp {
  fill: var(--svg-color--372f11, #372f11);
  d: path("M19.565 18.15c.052-.005.104-.005.154-.008c.041.016.082.035.062.094q-.105-.001-.209.004c-.132.021-.206.067-.195.232a4.4 4.4 0 0 1-.007.755q-.046.033-.085 0c-.099-.334-.062-.671-.024-1.01c.08-.115.213-.029.304-.067");
}

.cre4sgb9u {
  fill: var(--svg-color--565656, #565656);
  d: path("M15.927 35.653q-.002.136-.006.271c-.021.02-.023.054-.054.063c-.039-.119-.133-.256.06-.334");
}

.crgtr3bjc {
  fill: var(--svg-color--4f4f4f, #4f4f4f);
  d: path("M18.632 40.963q.025.001.051-.005c-.047.104.021.268-.153.308c.026-.105.03-.217.102-.303");
}

.cs3kq-bgc {
  fill: var(--svg-color--332d0a, #332d0a);
  d: path("M12.962 37.595c.02-.104.047-.205.191-.161c-.023.146-.031.304-.245.278c.021-.039.036-.079.054-.117");
}

.csqnleb8k {
  fill: var(--svg-color--0c0c0c, #0c0c0c);
  d: path("m19.996 27.721l-.017.118c.039.039.033.078.002.113c-.031.008-.061 0-.08-.026c-.051-.104-.053-.205.031-.295c.014.008.024.008.041.005q.009.041.023.085");
}

.csvfvwb2i {
  fill: var(--svg-color--232424, #232424);
  d: path("M14.937 29.739q.185.026.361.053q.023.05-.019.078c-.114.047-.228.051-.334-.013c-.035-.038-.044-.079-.008-.118");
}

.ctl37h4mn {
  fill: var(--svg-color--707070, #707070);
  d: path("M19.618 27.473c-.012.089.021.188-.042.265c-.017.022-.03.022-.05.008a.56.56 0 0 1 .029-.26c.022-.007.042-.007.063-.013");
}

.ctlio1b1q {
  fill: var(--svg-color--2d2108, #2d2108);
  d: path("m13.06 38.702l-.006.078c-.08-.068-.067-.177-.101-.271c.036.017.07.027.104.042c.029.016.066.019.068.058c-.018.029-.043.058-.065.093");
}

.ctmaqy2-x {
  fill: var(--svg-color--a2a4ac, #a2a4ac);
  d: path("M15.884 18.282c.014.004.024 0 .041-.008c.008.008.016.02.023.028c-.008.021-.016.028-.023.039h-.046q0-.027.005-.059");
}

.ctwsvwrwn {
  fill: var(--svg-color--bba320, #bba320);
  d: path("M22.323 36.706h.077c-.025.02-.052.035-.077.054z");
}

.cu0pgu12f {
  fill: var(--svg-color--341a1a, #341a1a);
  d: path("M23.935 36.606c.017 0 .035-.004.051-.004h.05c.028-.029.063-.033.104-.025c.047.025.074.063.069.121q-.032.036-.062.008c-.056-.065-.189.039-.212-.1");
}

.cvknj8bho {
  fill: var(--svg-color--282929, #282929);
  d: path("M13.696 29.27c.02.123-.043.209-.116.292c-.147-.149.091-.228.069-.354q.024.036.047.062");
}

.cwz_xqjwo {
  fill: var(--svg-color--766c2f, #766c2f);
  d: path("M22.894 19.19c.02-.031.035-.068.055-.104c.063.031.152.035.156.138c.021.028.017.052-.004.071a4 4 0 0 1-.207-.105");
}

.cxkgpsble {
  fill: var(--svg-color--584c11, #584c11);
  d: path("M16.08 23.28v-.052c.093.021.181-.104.272-.004c-.08.072-.177.044-.272.056");
}

.cydl67bxi {
  fill: var(--svg-color--eee, #eee);
  d: path("m20.15 35.554l-.066.063c-.105-.004-.117-.101-.152-.168c.039-.244-.039-.496.051-.736a1 1 0 0 1 .148-.047c.047.117-.054.256.055.365v.196c-.068.108-.053.217-.036.327");
}

.cyf0nio7t {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M0 25h64v14H0z");
}

.cz7mp5bfx {
  fill: var(--svg-color--5e5d59, #5e5d59);
  d: path("M15.763 18.18c.039-.114-.02-.208-.049-.311c.103.03.114.129.157.207a.14.14 0 0 1-.024.095c-.026.019-.053.036-.084.009");
}

.d__sozo4m {
  fill: var(--svg-color--644b1b, #644b1b);
  d: path("M19.31 19.239c.019-.006.031-.006.045-.006c.054.043.005.122.058.165c.05.091.062.189.056.287c.035.118.035.226-.054.319l-.062.023q-.03.025-.063.008c-.039-.031-.061-.066-.05-.123a.2.2 0 0 1 .036-.055c.056-.097.002-.197-.021-.291q-.023-.092-.015-.191c.008-.056.023-.106.07-.136");
}

.d_319_icz {
  fill: var(--svg-color--fdfdfd, #fdfdfd);
  d: path("M17.556 25.476a.4.4 0 0 0 .062.008a.4.4 0 0 1 .173.023c.113.037.063.085 0 .129a.2.2 0 0 1-.054.027c-.046.008-.048.033-.017.072c.037.049.096.096.121.163c.014.161.156.244.226.374c.026.098-.085.188-.009.283q.135.272.263.542c-.079.056-.015.251-.194.206c-.076-.047-.142.007-.207.029c-.027-.004-.058-.008-.066-.029c-.051-.115-.069-.057-.092.016c-.043.022-.076.008-.099-.029c.002.014.011.021.013.029a.2.2 0 0 1-.007.191c-.106.023-.188.063-.157.201a.1.1 0 0 1-.049.055a.13.13 0 0 1-.148-.027c-.057-.08-.049-.172-.053-.263a.5.5 0 0 0-.063-.239a.3.3 0 0 1-.027-.068c-.012-.084-.092-.133-.125-.201c-.039-.082-.13-.125-.115-.23c-.004-.047-.031-.076-.063-.104c-.072-.063-.154-.094-.236-.133a.2.2 0 0 1-.076-.071c-.039-.087-.074-.169-.125-.249c-.041-.079-.094-.152-.06-.247c.06-.091.114-.192.241-.212c-.221-.105-.458-.047-.688-.086a.37.37 0 0 1-.187-.143c-.021-.06-.083-.121.009-.172q.07-.03.074-.104c.091-.069.177-.146.301-.152c.146-.012.294-.028.434.043q.025.014.047.009c.113.02.225.051.338.053c.039.033.084.068.123.104c.074.036.173.009.229.095l.02.004c.098-.005.174.04.243.103m1.795.784c.088-.134.179-.26.269-.39c.146-.141.046-.231-.063-.321c.063-.083.168-.032.244-.065l.018-.005c.083-.046.171-.094.263-.12c.085-.043.183-.056.271-.088l-.002.006c.076-.072.191-.057.262-.125c.07-.029.148.014.211-.041l-.008.004c.259-.082.509-.104.736.086q.06.064.123.123c.072.041.023.086.012.129a.35.35 0 0 1-.135.134c-.283.122-.604.024-.826.149c.225.004.308.086.322.356a.4.4 0 0 1-.031.067a.7.7 0 0 0-.141.231q-.015.031-.033.06a.44.44 0 0 1-.263.164c-.161.02-.062.16-.112.231c-.037.036-.068.076-.103.11c-.067.043-.078.131-.128.185a.6.6 0 0 0-.057.165c-.056.15-.011.344-.174.439a.14.14 0 0 1-.074-.078c-.03-.063.008-.165-.138-.151c-.079.009-.067-.146-.129-.203c-.022-.024-.049-.047-.071-.071a.12.12 0 0 0-.141-.03a.6.6 0 0 1-.165.042c-.177-.016-.244-.102-.187-.279q.055-.052.106-.109c.005-.095.063-.162.095-.239c.021-.023.041-.056.062-.078c-.004-.052-.004-.101.026-.142c.115-.084-.03-.052-.039-.084q-.021-.03 0-.062m-6.766 4.675h-.049c-.006-.115.025-.236-.018-.342a.65.65 0 0 0-.039-.275c-.02-.085.037-.152.037-.227c.002-.032 0-.061.009-.092c-.031.014.008.037-.009.053c.017.085-.071.136-.066.22c.005.056-.014.114-.014.165c-.051.055-.053.125-.053.192c-.053.04-.068.106-.088.17c-.031.083-.06.173-.091.257c-.026.086-.083.159-.114.238c-.051.068-.104.14-.19.045c-.009-.146-.005-.283-.005-.424c.025-.123.047-.248.052-.371c.011-.041.022-.082.022-.12c.027-.095.014-.192.053-.284c-.016-.172.109-.332.055-.511c.045-.052.012-.117.04-.177c.047-.08.03-.168.049-.26c.068-.121.015-.259.063-.389c.063-.032.07-.091.058-.161c-.006-.165.05-.294.233-.33q.12-.143.231-.287c0-.083.062-.131.104-.188c-.006-.066.033-.113.078-.154c.229.004.082.191.138.275c.034.078.097.095.173.091l.129-.155c.027-.02.049-.015.07 0c.047.182-.063.331-.08.491c-.107.08-.057.205-.094.299c-.012.06-.032.114-.036.172a.3.3 0 0 1-.072.161c-.078.079-.024.173-.032.255c.022.193-.043.369-.063.554c0 .037-.005.07-.013.109c-.027.09-.072.18-.076.279c-.045.216-.008.459-.205.627c-.063.029-.085.139-.187.094m12.709.325q-.007-.035-.01-.071c-.064-.073-.096-.167-.128-.255c-.038-.086-.086-.173-.075-.275l-.002-.09c-.084-.099-.134-.201-.098-.33c.047-.109-.139-.137-.09-.25c-.022-.096-.055-.191-.047-.291c-.008.112.031.224.053.334c.008.088.059.18.044.277c.007.083-.052.154-.046.241c-.043.118 0 .251-.053.366c-.125.07-.148-.049-.203-.109a1.15 1.15 0 0 1-.228-.445a1 1 0 0 1-.028-.193c.004-.072-.018-.148-.035-.219a1 1 0 0 1-.012-.109c-.005-.075-.009-.149-.033-.221c-.016-.047-.018-.099-.023-.148c0-.104-.043-.198-.049-.294a1.1 1.1 0 0 0-.079-.351a.4.4 0 0 1-.044-.133a1.2 1.2 0 0 0-.07-.351c-.02-.134-.125-.261-.055-.409q.041-.013.07.016q.048.061.099.119c.052.008.096-.017.138-.041c.028-.016.042-.043.053-.074c.021-.086-.015-.182.041-.264c.098-.06.108.055.166.083l.062.114c.032.075.073.143.104.22a.53.53 0 0 1 .205.201c.108.074.199.165.203.312c.042.113.031.235.083.345c-.008.138.067.256.06.397c.039.113.039.235.063.354c.021.09.044.18.042.271c.026.105.052.203.046.313c.012.086-.018.181.021.267q.007.078.019.149c.065.187.052.378.063.565c-.088.152-.161.071-.227-.021");
}

.d_bju848y {
  fill: var(--svg-color--555554, #555554);
  d: path("M12.901 31.579c-.057-.067-.032-.153-.057-.228h.018c.031-.03 0-.108.08-.112c.085.051.074.129.059.213c-.022.056-.046.104-.1.127");
}

.d0_f311zg {
  fill: var(--svg-color--353535, #353535);
  d: path("M12.496 30.942c-.015.086.002.184-.099.26c-.006-.146-.027-.274.095-.375c.032.037.029.074.004.115");
}

.d0-t6wble {
  fill: var(--svg-color--3f3f3f, #3f3f3f);
  d: path("M13.175 29.16q-.028-.087-.059-.166c.066-.03.037-.108.061-.159c.049-.005.075.003.053.062c-.006.091-.006.181-.055.263");
}

.d0loltq2e {
  fill: var(--svg-color--dfdfe0, #dfdfe0);
  d: path("m15.658 19.214l.006.068c-.017.021-.03.039-.05.053c-.035.021-.074.029-.109.005c-.043-.042-.055-.093-.062-.152c.004-.146-.035-.293.062-.424l.063-.153c.047-.008.066.02.084.059a2 2 0 0 1-.02.148c-.039.136-.117.274.026.396");
}

.d139jcbnj {
  fill: var(--svg-color--2a2720, #2a2720);
  d: path("M22.427 19.768c-.014-.009-.029-.013-.041-.021c-.043-.031-.041-.07-.018-.104q.034-.067.073-.133c.009-.021.017-.028.032-.009c.005.091.044.187-.046.267");
}

.d24a-nhpn {
  fill: var(--svg-color--dbdbdb, #dbdbdb);
  d: path("M19.464 28.1c.096.023.039.105.061.157c.044.063.02.133 0 .198a.3.3 0 0 1-.024.064a.25.25 0 0 1-.052.098q-.024.03-.057.056c-.09.032-.116-.019-.135-.095c.002-.088-.004-.188.059-.271z");
}

.d2or80s6m {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("m17.904 37.12l.05-.076q.018-.058.064-.027h.022c.021-.011.046-.021.07-.011c.094.021.209.034.149.185a1.2 1.2 0 0 0-.09.271a.4.4 0 0 1-.041.102c-.102.098-.115.229-.109.364a.4.4 0 0 1-.074.26a.5.5 0 0 1-.217.181c-.057.01-.108.01-.141-.055c-.002-.018-.005-.025-.005-.044c-.116-.198-.026-.39.015-.581c.037-.094.057-.188.146-.244c.016-.045.037-.086.051-.132c.004-.089.067-.133.11-.193");
}

.d3-lhso2l {
  fill: var(--svg-color--250606, #250606);
  d: path("M21.18 39.18q.015.154.023.311c-.162-.1-.066-.238-.066-.369c.043-.005.07.012.043.058");
}

.d3sma-bgo {
  fill: var(--svg-color--4a2423, #4a2423);
  d: path("M19.308 27.413c-.02.004-.031.004-.047.008q-.036-.016-.047-.055c-.043-.067-.08-.056-.115.004c-.098-.129-.194-.258 0-.394c-.002.144.056.231.205.236c.069.068.123.135.004.201");
}

.d408nrund {
  fill: var(--svg-color--504d4d, #504d4d);
  d: path("M19.16 33.724q-.03-.007-.056-.006c.004-.141.125-.129.205-.129c.662-.008 1.322-.03 1.979.008a.3.3 0 0 1 .091.044q.04.048-.007.083z");
}

.d493jlbuw {
  fill: var(--svg-color--585858, #585858);
  d: path("M17.226 35.605q.102-.001.203-.008c.016.013.023.021.02.034q-.006.017-.012.016c-.096.047-.2.172-.25-.037q.018-.042.039-.005");
}

.d4csxzbmv {
  fill: var(--svg-color--635b25, #635b25);
  d: path("M22.677 19.13a1 1 0 0 0-.097.055c-.028-.021-.06-.04-.087-.061c-.027-.049-.023-.102.002-.155h.023c.154 0 .295.055.429.122c.017.051-.009.086-.056.104q-.103-.029-.214-.065");
}

.d5_wa1b9q {
  fill: var(--svg-color--411615, #411615);
  d: path("M14.812 34.87c-.039.123-.231.062-.239.217q.025.017.015.039q-.01.017-.019.015c-.124-.088-.119-.162.022-.213c.071-.027.138-.076.221-.058");
}

.d51z2d9sf {
  fill: var(--svg-color--2a2b2b, #2a2b2b);
  d: path("M17.233 34.706q-.024.023-.049.056c-.021-.292.129-.156.252-.101l.002.037c-.069 0-.138-.08-.205.008");
}

.d648sm7ei {
  fill: var(--svg-color--f1f1f1, #f1f1f1);
  d: path("M20.611 29.838c-.058.091-.104 0-.158-.009c-.022-.078-.092-.099-.153-.133a.2.2 0 0 1-.061-.047c-.051-.105-.081-.203 0-.306a.25.25 0 0 1 .191-.032c.088.012.121.09.17.148c0 .013.004.033.004.043c-.079.116.04.226.007.336");
}

.d65kxmb0d {
  fill: var(--svg-color--343535, #343535);
  d: path("m19.524 29.624l-.025.005l-.025-.005c.016-.084.025-.172.041-.258c-.013-.008-.02-.027-.019-.041q0-.022.006-.02c.036-.051.087-.07.15-.078q.032.001.058.031a1.1 1.1 0 0 0-.186.366");
}

.d69xa4boa {
  fill: var(--svg-color--463d0e, #463d0e);
  d: path("M18.519 17.292a.8.8 0 0 0-.006-.408a.1.1 0 0 0 .008-.063q0-.102.004-.209a.13.13 0 0 1 .052-.047c.095.221.004.456.051.68c-.005.09-.054.078-.109.047");
}

.d6a4jo0yi {
  fill: var(--svg-color--0e4780, #0e4780);
  d: path("M21.859 22.87c-.011.08-.052.139-.126.134c-.081 0-.145-.05-.133-.149c.009-.074.061-.122.137-.111c.075-.001.117.05.122.126");
}

.d6h6wu6xy {
  fill: var(--svg-color--7e0c0c, #7e0c0c);
  d: path("M20.04 23.319c-.106.004-.216.036-.312-.039l-.006-.009c.092-.043.192-.016.289-.016q.046.019.029.064");
}

.d7_nv4boj {
  fill: var(--svg-color--59553f, #59553f);
  d: path("M22 20.13c.1.027.178-.043.271-.055c-.022.103-.18.094-.172.215c-.075-.031-.081-.098-.099-.16");
}

.d7772vhun {
  fill: var(--svg-color--242424, #242424);
  d: path("m23.821 30.25l-.028-.003l-.021.003q.03-.135.064-.263c.025-.037.043-.088.104-.052c.051.019.053.06.045.104c-.023.041-.006.087-.038.119c-.032.048-.071.089-.126.092");
}

.d7oeic-qv {
  fill: var(--svg-color--661d09, #661d09);
  d: path("M15.444 26.07c.181.039.393-.099.546.093c-.178-.039-.391.105-.546-.093");
}

.d7qfdulqh {
  fill: var(--svg-color--420c08, #420c08);
  d: path("M20.294 41.14c.03.026.055.052.083.079c-.104.014-.069.096-.075.156c-.011.072.012.158-.102.168c.083-.121-.034-.293.094-.403");
}

.d7qvrob2h {
  fill: var(--svg-color--adadae, #adadae);
  d: path("M20.339 18.04c-.015-.002-.031-.012-.051-.02c.023-.016.043-.027.064-.043q.149-.005.295-.004l.125.047c-.138.106-.283.073-.433.02");
}

.d81k3i6tm {
  fill: var(--svg-color--5d5d5d, #5d5d5d);
  d: path("M16.957 40.38a.56.56 0 0 1-.086.277c-.037-.008-.037-.045-.051-.066c.032-.069.017-.159.095-.211q.018-.044.042 0");
}

.d8brrqbzh {
  fill: var(--svg-color--672a0e, #672a0e);
  d: path("M15.767 26.51c-.019-.013-.037-.022-.053-.036c.082-.031.17-.066.256-.094c-.008.13-.123.102-.203.13");
}

.d9m54ki2j {
  fill: var(--svg-color--232424, #232424);
  d: path("M17.11 39.915c.066.102-.02.17-.043.252c-.041.011-.07.004-.047-.049c-.007-.084.009-.158.09-.203");
}

.dafytx-ul {
  fill: var(--svg-color--5b563b, #5b563b);
  d: path("M20.966 26.25c-.049.037-.045.141-.138.125c.032-.084.006-.188.126-.213q.004.048.012.088");
}

.daktg4y-i {
  fill: var(--svg-color--606161, #606161);
  d: path("m17.544 29.624l.053-.062c.027.075.058.149.084.226q-.026.001-.056-.004c-.051.016-.067-.031-.097-.056l-.01.013l-.017-.004c-.025-.052.041-.074.043-.113");
}

.db3jarbfa {
  fill: var(--svg-color--054c97, #054c97);
  d: path("M22.597 22.913c.084.1.082.203.01.308c-.055.036-.129.024-.174.083a.15.15 0 0 1-.076.023c-.188-.004-.315-.104-.334-.287c-.023-.193.121-.248.275-.274a.2.2 0 0 1 .077.008c.079.039.144.094.222.139");
}

.dby68ibzf {
  fill: var(--svg-color--f1f1f1, #f1f1f1);
  d: path("m14.981 19.339l.063-.098a.6.6 0 0 1 .303.008q.015.025.035.043l.036.207c.005.146-.118.156-.208.197a.3.3 0 0 1-.158 0a.1.1 0 0 1-.051-.061c-.021-.023-.042-.042-.061-.071c-.002-.071-.015-.157.041-.225");
}

.dbzz3v1tx {
  fill: var(--svg-color--5e5e5e, #5e5e5e);
  d: path("m14.638 31.954l-.059-.02c-.023-.07.061-.169-.057-.213q-.03.031-.061.004c-.011-.042.01-.074.045-.094a.2.2 0 0 1 .146-.03c.052.026.062.078.062.132a.5.5 0 0 1-.084.213z");
}

.dca_i_61d {
  fill: var(--svg-color--333, #333);
  d: path("M18.202 40.28c-.025-.02-.051-.035-.079-.054c-.034-.045-.083-.089-.065-.153c.013-.022.022-.022.041 0c.049.098.127.108.224.068c-.038.049-.081.092-.121.139");
}

.dcaembbtf {
  fill: var(--svg-color--323333, #323333);
  d: path("M24.698 28.898c.102.134.082.3.102.452c-.113-.133-.088-.298-.102-.452");
}

.dcjdd5bkk {
  fill: var(--svg-color--65160a, #65160a);
  d: path("M23.604 21.383q.034.001.072.007c-.068.04-.131.075-.199.109c-.043-.006-.088-.02-.129-.027q.13-.048.256-.089");
}

.dcmrgsblr {
  fill: var(--svg-color--5b2d0d, #5b2d0d);
  d: path("M21.904 39.38c0 .037.002.07.003.107c-.059-.049-.155-.049-.15-.149c.049.012.096.03.147.042");
}

.dd0yhgbjm {
  fill: var(--svg-color--e2e2e2, #e2e2e2);
  d: path("M19.731 29.79c-.043.07-.086.117-.162.039l.005.009c-.072-.052-.093-.122-.078-.204c.052-.141.056-.307.181-.408c.041-.041.086-.061.141-.036c.023.017.033.04.043.062c.005.164.013.33-.094.479c-.012.02-.024.035-.036.059");
}

.ddf3qyxkp {
  fill: var(--svg-color--f0f1f1, #f0f1f1);
  d: path("M13.649 19.311c-.04-.06-.08-.122-.119-.176c-.027-.274.009-.315.305-.319c.098.012.137.08.164.158a.33.33 0 0 1-.015.199a.25.25 0 0 1-.111.113c-.071.037-.145.068-.224.025");
}

.dea340sfe {
  fill: var(--svg-color--505050, #505050);
  d: path("M21.908 32.419c-.045-.049-.047-.109-.047-.172c.004-.031.021-.057.055-.063c.033.082.091.161-.008.235");
}

.ded6qnbxh {
  fill: var(--svg-color--231d08, #231d08);
  d: path("M23.21 37.18q-.13.007-.257.008a.096.096 0 0 1-.118 0c-.027-.008-.048-.022-.048-.056a.3.3 0 0 1 .062-.049c.086-.029.175-.021.261-.015c.078-.006.106.036.1.112");
}

.deqq54bka {
  fill: var(--svg-color--262626, #262626);
  d: path("M24.505 30.831c.016 0 .035.004.051 0l-.004.468c-.08.004-.088-.063-.105-.121c-.012-.122-.033-.243.058-.347");
}

.dfi2cd58e {
  fill: var(--svg-color--54504f, #54504f);
  d: path("M14.315 30.62c-.01.129.006.252-.049.375q-.02-.01-.016-.03c.002-.009.006-.019.012-.019c-.04-.119-.128-.244.053-.326");
}

.dfntr2bty {
  fill: var(--svg-color--505151, #505151);
  d: path("M17.239 35.27c-.02.021-.035.044-.055.065c.031-.083-.197-.203.041-.256z");
}

.dgms6fbau {
  fill: var(--svg-color--5c5d5d, #5c5d5d);
  d: path("M20.347 40.02c-.103-.004-.121-.09-.146-.168a.06.06 0 0 1 .043-.047c.069.052.081.136.103.215");
}

.dhzyxlbgq {
  fill: var(--svg-color--42110a, #42110a);
  d: path("M20.462 21.591c.098.02.196.031.297.043c-.112.117-.207.051-.297-.043");
}

.dj2d9bszl {
  fill: var(--svg-color--2a2424, #2a2424);
  d: path("M20.501 36.4c.043.137.129.104.221.063c-.016.13-.121.134-.182.082c-.074-.061-.148 0-.214-.045c.045-.058.092-.108.175-.1");
}

.dj4h6yj8l {
  fill: var(--svg-color--535353, #535353);
  d: path("M17.17 28.21h.105c.01.013.021.021.027.033c.027.142.054.279-.133.334h.004c-.058-.123.053-.244-.003-.367");
}

.djj4lcd6z {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M19.736 38.34q-.019.001-.045-.004c-.095-.01-.118-.105-.192-.143c-.025-.021-.054-.045-.07-.074a.3.3 0 0 1-.023-.105c-.01-.068 0-.148-.035-.225a.5.5 0 0 1-.04-.125a1 1 0 0 0-.078-.248l-.104-.217c-.049-.123.027-.148.115-.17h.217c.027.039.059.078.084.123c-.012.073.055.118.078.18c.039.057.067.119.104.179c.046.094.074.2.082.308c-.004.008-.004.022-.004.03q.001.24-.004.487c-.028 0-.054.004-.085.004");
}

.dk3snlbot {
  fill: var(--svg-color--fc2118, #fc2118);
  d: path("M21.07 22.54q.026-.001.047 0c.081.029.124.1.178.156c.104.121-.055.139-.082.211a.83.83 0 0 1-.501.008c-.105 0-.164-.104-.255-.133c-.065-.143 0-.229.104-.308c.172.001.353-.065.509.066");
}

.dkg9pdb3j {
  fill: var(--svg-color--5c5c5c, #5c5c5c);
  d: path("M19.642 37.34c-.07-.043-.139-.086-.078-.184c.082.039.101.108.101.188z");
}

.dkvp6xo-w {
  fill: var(--svg-color--393a3a, #393a3a);
  d: path("m13.587 29.618l.051.637c-.131.027-.139-.082-.178-.157a.2.2 0 0 0-.039-.056q.081-.212.166-.424");
}

.dm4-qbbfn {
  fill: var(--svg-color--484949, #484949);
  d: path("m17.904 27.312l-.056.063q-.057-.034-.112-.063c.008-.043.016-.117.026-.117c.079-.007.11.054.142.117");
}

.dn0qm0xwj {
  fill: var(--svg-color--3f3e3e, #3f3e3e);
  d: path("M24.3 27.991q0 .046.004.09c-.055.056-.103.027-.147-.016q.07-.034.143-.074");
}

.dng_lq5wb {
  fill: var(--svg-color--3d2a0b, #3d2a0b);
  d: path("M15.244 21.18q.05.001.103-.004c.018.087.039.177.055.263a2 2 0 0 1-.143-.043q-.01-.111-.015-.216");
}

.dnq4_nb1j {
  fill: var(--svg-color--241212, #241212);
  d: path("M20.394 27.737c.014.049.009.094-.051.107c-.031.027-.062.031-.103.013a.2.2 0 0 1-.04-.062a.16.16 0 0 1 .021-.106a.12.12 0 0 1 .062-.034c.058-.002.088.037.111.082");
}

.do35dlusd {
  fill: var(--svg-color--404141, #404141);
  d: path("M13.649 29.2c.031-.105-.071-.231.041-.334c.107.021.082-.113.154-.138c.119.071-.058.287.154.314c.027-.013.059-.005.059.02c0 .06-.045.087-.092.11c-.094-.01-.19-.01-.246.09c-.044.009-.059-.025-.07-.062");
}

.doo4ozbdr {
  fill: var(--svg-color--453131, #453131);
  d: path("M23.2 26.428h-.026l-.027-.004c-.041-.067-.148-.122-.045-.224c.065.064.078.145.098.228");
}

.dopmecbpe {
  fill: var(--svg-color--0c0f0f, #0c0f0f);
  d: path("M21.8 20.655c.08-.099.096-.035.106.043l-.099.06z");
}

.dos_6w5ko {
  fill: var(--svg-color--3f0f07, #3f0f07);
  d: path("m18.576 16.565l-.052.047q-.133.026-.264.047c.077-.125.186-.141.316-.094");
}

.dp3ka606d {
  fill: var(--svg-color--cab222, #cab222);
  d: path("m12.854 38.39l.002.052a.4.4 0 0 1-.053.061c.005-.046.005-.089.051-.113");
}

.dp4oj1rfw {
  fill: var(--svg-color--1e2121, #1e2121);
  d: path("M19.312 28.313a6 6 0 0 1-.014.313q-.05.045-.099.005c-.017-.005-.026-.009-.041-.009c.037-.104.076-.205.114-.312c.014.011.03.011.04.003");
}

.dpr6qrwwj {
  fill: var(--svg-color--444544, #444544);
  d: path("M23.625 28.841q-.001.06-.005.117c-.074.022.005.221-.16.146c.063-.086.066-.185.066-.291c-.002-.04 0-.094.061-.06c.021.012.025.059.038.088");
}

.dpx4wub_r {
  fill: var(--svg-color--e8e9eb, #e8e9eb);
  d: path("M15.06 20.598c-.021-.033-.043-.056-.063-.083q-.032-.035 0-.07v.004c.039-.1-.083-.178-.039-.271a.13.13 0 0 1 .077-.079c.024 0 .051.004.071.016a1 1 0 0 1 .188.274c.008.099.148.188.02.302c-.051.016-.1.02-.148-.005c-.052-.015-.097-.031-.106-.088");
}

.ds-gdl5lx {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M18.271 38.429a.43.43 0 0 1-.146.171c-.063-.022-.072-.085-.092-.135a.94.94 0 0 1-.045-.49c.035-.149-.006-.317.125-.438l-.002-.092c.07-.08.091-.189.143-.275c.04-.061.063-.139.155-.113c.045.016.094.021.129.055a.16.16 0 0 1 .021.108c-.017.08-.058.149-.055.237a.15.15 0 0 1-.02.068c-.059.075-.051.178-.075.27c-.043.152-.004.311-.033.466c-.012.066-.072.109-.105.168");
}

.ds0sw6r1l {
  fill: var(--svg-color--5f3e3d, #5f3e3d);
  d: path("m21.534 33.1l.014-.063c.034.102.064.209.1.313c-.153-.032-.094-.16-.114-.25");
}

.ds8mj7btu {
  fill: var(--svg-color--695f32, #695f32);
  d: path("M18.494 19.811c.052.165.188-.086.247.052q-.062.029-.122.062q-.051.04-.099-.005a.16.16 0 0 1-.084-.104q.027-.035.058-.005");
}

.ds9knwb_h {
  fill: var(--svg-color--494731, #494731);
  d: path("M13.755 19.808c.047.046.036.109.047.169l-.011.215c-.083-.121-.052-.255-.036-.384");
}

.dtrcghb_v {
  fill: var(--svg-color--d9dbdf, #d9dbdf);
  d: path("M16.5 18.12h-.165c-.021-.016-.051-.016-.055-.047l.011-.045c.071.025.122-.119.203-.021l.147.007c.18-.023.363-.02.545-.004c.147.004.3.018.453.021c-.061.021-.113.039-.174.056c-.084.026-.172.008-.262.021c-.233.002-.469-.025-.703.012");
}

.du8r_gb4j {
  fill: var(--svg-color--2b2c2c, #2b2c2c);
  d: path("m24.26 32.831l.049.109l-.006.203c-.125-.089-.031-.209-.043-.312");
}

.dumtzvgta {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M11.58 24.396v11.29c0 2.02.802 3.854 2.099 5.183c1.295 1.33 3.082 2.152 5.05 2.152h.002c1.968 0 3.755-.822 5.05-2.152a7.4 7.4 0 0 0 2.099-5.183v-11.29c-4.764 0-9.53.003-14.299 0");
}

.dvgeovbah {
  fill: var(--svg-color--4e150d, #4e150d);
  d: path("M14.946 22.444a1 1 0 0 0-.055.094c.014.02.01.043-.014.054c-.07-.067-.025-.212-.152-.247l.258.004c.03.047-.05.051-.037.095");
}

.dw9ax0q-r {
  fill: var(--svg-color--2c2b20, #2c2b20);
  d: path("M15.675 18.393q-.007-.043-.014-.101l.102-.112q.032-.014.06-.035q.03.025.056.042q.026.025.035.057a.2.2 0 0 1 0 .069q-.009.035-.027.063a.3.3 0 0 1-.086.059c-.053.006-.097.003-.126-.042");
}

.dwgaxpb2n {
  fill: var(--svg-color--c4a720, #c4a720);
  d: path("M21.519 20.454q-.036-.066-.072-.125c-.038-.071-.016-.129.031-.188c.037-.028.072-.039.091.022c-.013.091.038.197-.032.285z");
}

.dwqy3y2ih {
  fill: var(--svg-color--e4c626, #e4c626);
  d: path("M13.956 37.487a.3.3 0 0 0 .027-.056l.07-.081c.086-.031.166-.052.209.068v.053c-.099.087-.204.061-.306.016");
}

.dzbm3-bbv {
  fill: var(--svg-color--292307, #292307);
  d: path("M15.582 25.759c.056.035.166-.008.187.094c.018.063-.041.086-.096.079c-.074-.008-.162-.017-.177-.114c-.009-.054.025-.079.086-.059");
}

.e_76zfz5b {
  fill: var(--svg-color--e7e7e6, #e7e7e6);
  d: path("M23.888 19.13c.074.076.211.037.269.154c.065.086.119.174.011.271l-.027.046c-.056.079-.138.099-.227.106a.2.2 0 0 1-.076-.017c-.074-.042-.123-.112-.178-.175a.24.24 0 0 1-.027-.109c.002-.023.012-.048.016-.068c.063-.089.123-.179.239-.208");
}

.e_mm-vgsf {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M19.696 39.854q-.086-.113-.169-.227c-.06-.027-.083-.073-.089-.139c-.004-.229.008-.465-.027-.699c-.02-.021-.034-.051-.055-.073a.65.65 0 0 1 .044-.394c.017-.049.034-.086.083-.109c.083-.01.125.083.203.09a.1.1 0 0 1 .051.037c-.064.094.053.128.053.199c.016.056.034.104.051.16c.023.063.051.141.078.207l.02.254c.031.197.035.396-.004.601c.004.026.004.063.007.093c-.088.202-.164.035-.246 0");
}

.e_z8ypj7u {
  fill: var(--svg-color--404040, #404040);
  d: path("M16.543 29.833c.089-.031.146-.146.267-.098a.09.09 0 0 1 .023.098c-.018.029-.045.052-.081.052s-.065 0-.098.004c-.048-.004-.088-.008-.111-.056");
}

.e-9v3uenv {
  fill: var(--svg-color--8c7917, #8c7917);
  d: path("M22.375 39.855c.015-.001.03-.007.043-.007c.033.04.056.074.083.109l-.018.009c-.141.081-.289.046-.438.028c-.027-.012-.047-.028-.052-.064c.021-.046.062-.057.104-.05c.091-.008.187.027.278-.025");
}

.e-ntnpbum {
  fill: var(--svg-color--434032, #434032);
  d: path("m22.579 18.762l.061-.062q.056.052.109.104l-.061.067c-.033-.008-.068-.012-.104-.021c-.016-.025-.007-.058-.005-.088");
}

.e0bw1ublq {
  fill: var(--svg-color--babbbc, #babbbc);
  d: path("M20.229 27.679h-.008a.4.4 0 0 1-.08-.305c.035-.055.065-.108.099-.164c.022.109-.013.225.048.322v.137a.2.2 0 0 1-.059.01");
}

.e0kge3b9d {
  fill: var(--svg-color--181a1a, #181a1a);
  d: path("m17.962 38.913l.051.059q-.005.262-.016.52q-.02.036-.043-.004a2.4 2.4 0 0 1 .008-.575");
}

.e0ptin9qv {
  fill: var(--svg-color--d1b323, #d1b323);
  d: path("m12.699 38.19l.06-.037c.106-.022.147-.146.252-.176l.107-.011c.129.092.021.128-.042.176c-.086.035-.112.15-.218.165c-.065-.023-.146-.019-.159-.117");
}

.e0r02geid {
  fill: var(--svg-color--650806, #650806);
  d: path("M18.341 16.299c-.009-.017-.021-.031-.029-.052c.183.043.236-.047.217-.211a.2.2 0 0 1 .049.017c.047.288.047.288-.237.246");
}

.e0t69tb3j {
  fill: var(--svg-color--321b1b, #321b1b);
  d: path("M13.331 36.45c.045.027-.008.233.143.082q.045.032.011.07c-.015.146-.156.038-.212.104c-.022.021-.047.017-.066-.008c-.039-.096-.003-.178.055-.252c.021-.02.048-.016.069.004");
}

.e15t5qn0y {
  fill: var(--svg-color--33290a, #33290a);
  d: path("M19.294 21.552c-.132-.027-.24-.083-.294-.217c.015-.027.021-.063.056-.066c.094.161.235.2.41.173c.022.087-.051.095-.101.122a.12.12 0 0 1-.071-.012");
}

.e2xb02__a {
  fill: var(--svg-color--5e0d0a, #5e0d0a);
  d: path("M21.363 39.704q.035-.084.071-.157q.025-.04.054-.005c0 .055.004.109.004.174c-.002.044-.011.096-.062.078c-.03-.008-.046-.059-.067-.09");
}

.e3rxfcxlz {
  fill: var(--svg-color--4e2928, #4e2928);
  d: path("M17.556 25.476c-.084-.02-.176-.035-.244-.102c.117-.055.201-.026.244.102");
}

.e3sx6ub7g {
  fill: var(--svg-color--1e2020, #1e2020);
  d: path("M23.415 33.08c.041.029.115.037.053.111c-.027.021-.039.075-.096.045c-.085-.108-.07-.235-.05-.363q.03-.018.055 0c.031.068-.016.147.038.207");
}

.e3u_2oe3s {
  fill: var(--svg-color--453737, #453737);
  d: path("M15.712 33.638c-.091-.105.018-.182.053-.26c.035.095-.01.177-.053.26");
}

.e5_8rzcbq {
  fill: var(--svg-color--494a4a, #494a4a);
  d: path("M18.944 37.35c.08.068.064.171.088.254q-.01.044-.046.059c-.048-.098-.098-.198-.042-.313");
}

.e53bqon4a {
  fill: var(--svg-color--554f0f, #554f0f);
  d: path("M14.772 19.969c-.135-.22-.1-.449-.041-.677c.027-.021.053-.012.072.008c.086.154.02.322.066.48a.2.2 0 0 1-.004.116a.1.1 0 0 1-.093.073");
}

.e55iqcc6j {
  fill: var(--svg-color--331e1e, #331e1e);
  d: path("m16.488 36.528l.011.078c-.115.139-.188.034-.262-.052v-.05c.09-.041.165.017.251.024");
}

.e5le-7b3y {
  fill: var(--svg-color--532e2d, #532e2d);
  d: path("M20.09 25.378c-.08.074-.177.09-.275.102c.054-.115.166-.128.275-.145c.02.013.022.02.02.033q-.01.01-.02.01");
}

.e5z2j3mpx {
  fill: var(--svg-color--3d230b, #3d230b);
  d: path("M24.72 38.626c.258.062.123-.098.104-.189c.123.012.113.096.105.186c-.004.063-.039.111-.105.117c-.083.007-.076-.073-.104-.114");
}

.e6vzx0b3i {
  fill: var(--svg-color--1d1e1e, #1d1e1e);
  d: path("M19.322 28.745q-.054-.03-.106-.066c-.009-.016-.012-.035-.016-.047q.047-.008.098-.006c.041.061.079-.022.116-.004c.013.08-.028.107-.092.123");
}

.e7-qrpw2k {
  fill: var(--svg-color--211d07, #211d07);
  d: path("M13.13 38.607c-.021-.02-.047-.034-.068-.058c.074-.059.037-.145.047-.213c.182-.117.385-.197.511-.43c.046.152-.022.24-.082.325c-.012.022-.026.026-.051.019c-.22.014-.252.223-.357.357");
}

.e8foz-bbk {
  fill: var(--svg-color--262626, #262626);
  d: path("M19.462 28.51c.069.04.08.106.104.168c-.014.024-.034.024-.051.005a1 1 0 0 0-.104-.051c-.01-.053.001-.1.051-.122");
}

.e9m223bbh {
  fill: var(--svg-color--141515, #141515);
  d: path("M23.616 31.04h-.036q-.009-.074-.015-.149q.028-.06.06-.117c.138.094-.03.176-.009.266");
}

.e9zkqdb-h {
  fill: var(--svg-color--4c4c4c, #4c4c4c);
  d: path("M17.698 28.1c-.051.161.027.314.021.473c-.021.016-.045.016-.072.008c-.092-.105-.092-.235-.1-.366q.013-.04.031-.075l.063-.094q.03.025.057.054");
}

.ea22wimoi {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M15.351 33.02q.003-.02.002-.046c.08-.066.08-.165.086-.261c.017-.069.035-.144.043-.218c0-.098.002-.197.084-.275a.6.6 0 0 0 .279-.275c.043-.041.092-.053.145-.017q.019.039.02.079c-.031.229.008.451-.027.681c-.01.05-.031.104-.035.165c.004.129-.063.238-.124.35a4 4 0 0 0-.06.172c-.008.088-.08.164-.054.261c-.065.065-.126.146-.221.183c-.122-.045-.093-.18-.151-.258a.6.6 0 0 1-.037-.113c-.014-.143.046-.282.05-.428");
}

.eb6a1acrc {
  fill: var(--svg-color--e1e2e3, #e1e2e3);
  d: path("M16.97 28.507c.113-.068.088-.225.19-.303c.013.006.021.015.034.019c.063.123.039.244-.021.356a.2.2 0 0 1-.066.037c-.075 0-.131-.024-.137-.109");
}

.ebc5c0ufy {
  fill: var(--svg-color--42370d, #42370d);
  d: path("M14.362 19.18q.01-.046.057-.04c-.018.016-.037.026-.057.04");
}

.ebw_hcbog {
  fill: var(--svg-color--ae9113, #ae9113);
  d: path("M22.366 20.08a1 1 0 0 0-.096-.006c-.088-.103-.064-.209.011-.303a.13.13 0 0 1 .073-.037c.027 0 .055.014.07.037c-.001.102.027.215-.058.309");
}

.edcd3bb2p {
  fill: var(--svg-color--372727, #372727);
  d: path("M20.457 31.52a.33.33 0 0 0-.06-.272c.182.059.2.145.06.272");
}

.edebdu_jx {
  fill: var(--svg-color--665b14, #665b14);
  d: path("M22.12 23.45c.068-.071.373.192.23-.172h.071l.013.312c-.103-.043-.225-.031-.311-.113q-.004-.018-.003-.027");
}

.edhob3bzy {
  fill: var(--svg-color--5d5e5f, #5d5e5f);
  d: path("M13.688 28.835c-.088.01-.143-.057-.213-.082q-.036-.048.008-.079c.146.046.078-.123.146-.154q.029-.039.059 0z");
}

.eekkmqouf {
  fill: var(--svg-color--532a0c, #532a0c);
  d: path("m13.644 38.913l.091-.325c.03.008.032.034.045.06c-.027.095-.021.214-.136.265");
}

.eg22mohkx {
  fill: var(--svg-color--6d6d6e, #6d6d6e);
  d: path("M13.334 31.448c.046.053.058.102-.01.14q-.08.032-.159.06c0-.052 0-.104.053-.131c.034-.038.069-.065.116-.069");
}

.eg69occfb {
  fill: var(--svg-color--373737, #373737);
  d: path("M13.731 31.563c.004.02.004.035.006.059c-.087-.012-.1.1-.169.113c-.019-.07.021-.125.069-.168q.047-.044.094-.004");
}

.ei7je-spp {
  fill: var(--svg-color--a78b13, #a78b13);
  d: path("M15.935 18.09a.2.2 0 0 0 0 .042c.014.016.011.036-.002.05c-.012.018-.032.021-.051.021c-.029-.008-.041-.037-.059-.06c.02-.024.033-.047.051-.067z");
}

.ejyiun1bv {
  fill: var(--svg-color--3f3f3f, #3f3f3f);
  d: path("M24.21 19.708c-.114-.032-.226-.024-.319.056c-.031-.036-.035-.067-.004-.104a7 7 0 0 1 .256-.062q.034.053.067.11");
}

.ekde1ebms {
  fill: var(--svg-color--252727, #252727);
  d: path("M12.8 28.573q-.024.005-.043.004c0-.076-.021-.152.071-.197c.05.074-.015.134-.028.193");
}

.ekiiu_jer {
  fill: var(--svg-color--363636, #363636);
  d: path("M14.925 29.885c-.027.126-.057.254-.082.381a.19.19 0 0 1-.062-.157c.086-.078.043-.18.065-.271q.039.02.079.047");
}

.ekv47kqad {
  fill: var(--svg-color--2d0605, #2d0605);
  d: path("M23.15 21.702c.049.02.093.033.138.049c-.06.076-.116.146-.178.213c-.008-.092.089-.166.04-.262");
}

.el5v1vm7h {
  fill: var(--svg-color--b39b1f, #b39b1f);
  d: path("M15.183 36.497c-.072-.117-.223.012-.297-.094c.145.016.311-.084.422.086q-.064-.002-.125.008");
}

.elcadtb4b {
  fill: var(--svg-color--190505, #190505);
  d: path("M17.437 36.756v-.026l.203.096c.004.039.002.065-.047.039c-.055-.034-.131-.028-.156-.109");
}

.em3sm369q {
  fill: var(--svg-color--1a1706, #1a1706);
  d: path("M24.21 38.493c.002-.152-.129-.183-.226-.217c-.168-.058-.209-.164-.217-.363c.149.164.265.301.445.357c.105.032.098.131.083.223c-.027.031-.059.031-.085 0");
}

.embwk7bda {
  fill: var(--svg-color--66676a, #66676a);
  d: path("m18.886 18.896l.002-.263c.138.087.142.176-.002.263");
}

.emdk3qb0t {
  fill: var(--svg-color--3d2409, #3d2409);
  d: path("M24.558 38.39c-.012.099.117.108.115.201q-.106-.021-.203-.038c-.026.021-.052.021-.072-.01c.052-.055.083-.125.16-.153");
}

.emxa6xb3b {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M20.19 39.38c-.02 0-.038-.004-.061-.004c-.029-.084-.126-.117-.15-.203a2 2 0 0 1-.062-.247c-.008-.095-.047-.183-.075-.271a1.4 1.4 0 0 1-.051-.176a.5.5 0 0 1 .027-.185c.025-.07.066-.132.148-.149c.057-.008.098.014.137.045c.107.072.123.203.186.307c-.018.141.1.199.17.296c.038.094.094.181.137.271c.006.016.012.027.021.047c.044.092.085.178.114.273c0 .052-.027.1-.079.121c-.063.004-.125.014-.187.008c-.094-.042-.191-.073-.275-.133");
}

.en2na0_dd {
  fill: var(--svg-color--312727, #312727);
  d: path("M16.685 36.505c.082-.016.168-.008.24-.057c-.047.166-.135.145-.24.057");
}

.en6f234gh {
  fill: var(--svg-color--662711, #662711);
  d: path("M16.878 22.534c-.174-.1-.363 0-.541-.047c.184-.052.375-.166.541.047");
}

.ene1ivdfd {
  fill: var(--svg-color--4e4f4e, #4e4f4e);
  d: path("m16.13 17.605l.002.056c-.101-.063-.201-.08-.312-.021c.086-.162.199-.096.31-.035");
}

.enr4bxu4t {
  fill: var(--svg-color--6d6d6d, #6d6d6d);
  d: path("M15.349 19.12q-.005.063-.004.133c-.09.072-.184.06-.281.021c-.063-.056-.032-.091.021-.127c.088-.007.18-.021.264-.027");
}

.eoivvzb2n {
  fill: var(--svg-color--6b300e, #6b300e);
  d: path("M18.11 17.296h-.04c.017-.078.03-.156.132-.168c-.022.061-.032.134-.092.168");
}

.ep3ejtway {
  fill: var(--svg-color--3f3e3e, #3f3e3e);
  d: path("M23.985 31.749c.031-.12.05-.252.158-.35c.063.088.111.172.108.28c-.143-.171-.171.066-.266.07");
}

.epalchblc {
  fill: var(--svg-color--3b3c3c, #3b3c3c);
  d: path("M23.06 29.936q-.033.035-.069.083c-.062-.105-.063-.227-.081-.341h.052c.059.073.016.19.098.258");
}

.epz9n4_dc {
  fill: var(--svg-color--5f6060, #5f6060);
  d: path("M17.292 39.593c.012.012.021.027.036.045c-.032.064-.026.168-.144.146c.013-.076.038-.144.108-.191");
}

.eq1mkubye {
  fill: var(--svg-color--0f1111, #0f1111);
  d: path("M24.718 28.1c-.074-.055-.127-.117-.104-.22c.065.056.127.119.104.22");
}

.eq28het3l {
  fill: var(--svg-color--fbfbfb, #fbfbfb);
  d: path("M14.158 29.31q.046.02.101.04a.4.4 0 0 1 .004.066c.041.16.125.005.184.027c-.008.11-.014.229-.02.338c.049.07-.013.148.02.215a.3.3 0 0 1-.008.072c-.051.125-.086.25-.133.377c-.01.023-.029.043-.047.063c-.186.109-.26.004-.313-.153a.53.53 0 0 1 .021-.294c.029-.109.072-.212.055-.324c.09-.133.028-.308.136-.427");
}

.eq4qfqb2h {
  fill: var(--svg-color--f1f1f2, #f1f1f2);
  d: path("M15.716 17.87c.019-.082.032-.17.104-.229c.101-.105.196-.066.295-.012c.129.068.129.189.149.307a.3.3 0 0 1-.004.08a.2.2 0 0 1-.054.051a.6.6 0 0 1-.133.055a.3.3 0 0 1-.144.013a.2.2 0 0 1-.069-.024a.45.45 0 0 1-.146-.203c.004-.015.002-.027.002-.038");
}

.eqlk1wbrm {
  fill: var(--svg-color--380e0e, #380e0e);
  d: path("M25.25 29.364c.012 0 .023.004.035.004c.086.084.057.194.061.307c.032.051 0 .059-.043.059c.006-.129-.092-.241-.053-.37");
}

.eqyrd4bya {
  fill: var(--svg-color--665813, #665813);
  d: path("M14.281 39.538c-.087-.146-.083-.217-.035-.307c.089.081.052.157.035.307");
}

.es_1uwbpt {
  fill: var(--svg-color--282929, #282929);
  d: path("M23.88 33.29a1 1 0 0 1-.095-.053l-.013-.197l.053-.108c-.047.133.119.231.055.358");
}

.esmzuccsx {
  fill: var(--svg-color--3c0404, #3c0404);
  d: path("M12.449 35.939v.068c.036.202.011.411.013.614l-.029.033c-.068-.259-.033-.524-.041-.787c.057-.003.082.017.057.072");
}

.esz1s7bsz {
  fill: var(--svg-color--1c1c1c, #1c1c1c);
  d: path("M17.226 28.689q.078-.083.164-.164c.027-.013.059-.032.086-.048c.074.066.063.135.011.2a.1.1 0 0 0 0 .051l-.089-.094l-.026.094c-.015.031-.028.031-.053.009c-.028.004-.06.004-.087.008q-.005-.03-.006-.056");
}

.et9qypaak {
  fill: var(--svg-color--474848, #474848);
  d: path("M17.01 39.53c-.02-.021-.043-.035-.063-.056c.085-.035.168-.062.252-.095c-.017.108-.103.13-.189.151");
}

.etiozmh9j {
  fill: var(--svg-color--1b1b1b, #1b1b1b);
  d: path("m13.989 30.05l-.021-.004h-.023c.066-.113-.023-.256.049-.369q.036.03.073.066a.6.6 0 0 1-.078.307");
}

.etvdfhbph {
  fill: var(--svg-color--555458, #555458);
  d: path("m12.396 31.575l-.049-.104c-.002-.067-.024-.14.068-.179a.34.34 0 0 1-.019.283");
}

.eu4bu-b7d {
  fill: var(--svg-color--750806, #750806);
  d: path("M12.784 26.64c-.016.1-.016.206-.083.288c-.079-.13 0-.236.043-.347c.032.008.045.031.04.059");
}

.eu8iuvbzk {
  fill: var(--svg-color--575858, #575858);
  d: path("M18.524 41.31c.056.121.027.192-.104.225c.018-.083.034-.165.104-.225");
}

.euhsm_b6c {
  fill: var(--svg-color--531b1b, #531b1b);
  d: path("M16.388 35.725c-.084-.063-.182-.119-.101-.252c.05.079.107.147.101.252");
}

.euys0bbqf {
  fill: var(--svg-color--464747, #464747);
  d: path("M24.288 36.501c-.043-.125-.113-.241-.039-.379c.074.115.07.25.098.375q-.03.005-.059.004");
}

.euz6uobud {
  fill: var(--svg-color--bbbcbc, #bbbcbc);
  d: path("M19.31 27.833c.104-.073.088-.195.105-.303c.02-.108.066-.133.148-.054l-.01.009c.049.082.021.176.025.266a.7.7 0 0 1-.089.312c-.179.126-.174-.011-.187-.129q.01-.05.008-.101");
}

.evf_aqbnh {
  fill: var(--svg-color--191a1a, #191a1a);
  d: path("M17.427 39.487c-.019-.021-.037-.048-.054-.062c.004-.093-.075-.076-.126-.093c.055-.062.141-.108.148-.213c.053-.004.072.045.088.086c.022.097.036.204-.056.282");
}

.evkhaytlf {
  fill: var(--svg-color--fee72c, #fee72c);
  d: path("M22.787 37.07c.078-.074.169-.045.256-.029a2 2 0 0 1-.253.093a.3.3 0 0 0-.003-.064");
}

.evt1jrb_j {
  fill: var(--svg-color--e2e2e2, #e2e2e2);
  d: path("M20.09 28.62c-.072-.139-.127-.279-.002-.422c.021.043.041.076.059.114c.082.095.052.213.096.318v.043c-.085.068-.121.013-.153-.053");
}

.ewhpcdc3g {
  fill: var(--svg-color--8d7c18, #8d7c18);
  d: path("M22.63 20.07c-.027.02-.059.043-.088.067c-.054-.114-.027-.224.038-.322c.065.036.05.099.062.16z");
}

.ex0-pabsy {
  fill: var(--svg-color--594e10, #594e10);
  d: path("M17.847 21.905c-.033-.031-.064-.062-.1-.084c.105.012.225-.063.318.039c-.021.012-.04.031-.061.043a1 1 0 0 0-.157.002");
}

.ex4cy_b5m {
  fill: var(--svg-color--554b11, #554b11);
  d: path("M14.573 36.802q.025-.022.055-.042c.105-.009.217-.009.311.058c-.016.021-.033.031-.051.047h-.059c-.068-.105-.179-.02-.256-.063");
}

.exqep2mos {
  fill: var(--svg-color--ecd028, #ecd028);
  d: path("m22.326 36.87l-.005-.11c.002-.015.007-.022.01-.034a.1.1 0 0 1 .059-.038c.02-.004.041.007.062.015c.036.027.067.061.097.092q.04.053.082.104q.051.06.118.111a.2.2 0 0 1 .05.038l.041.05c.018.024.039.056.062.08c.045.052.097.091.144.144c.051.062.12.12.078.225a.1.1 0 0 1-.063.025a.4.4 0 0 1-.154-.094c-.183-.215-.345-.448-.581-.608");
}

.eza8gwbpo {
  fill: var(--svg-color--1c1311, #1c1311);
  d: path("M25.351 32.769c-.084-.105-.002-.186.033-.286c.035-.122.012-.259.016-.39c.013-.021.027-.026.044-.004c.005.213.032.419-.044.624a.07.07 0 0 1 .007.063q-.03.017-.056-.007");
}

.ezbjvhbfn {
  fill: var(--svg-color--656567, #656567);
  d: path("M23.927 34.767c-.039-.025-.043-.064-.031-.109c.018-.023.018-.053.053-.059c-.004.104.152.104.145.213c-.015.021-.031.028-.056.028c-.046-.013-.074-.048-.111-.073");
}

.f-dzhttsf {
  fill: var(--svg-color--656565, #656565);
  d: path("M17.632 27.27c-.033-.043-.061-.086-.035-.141c.016-.036.045-.019.063-.005c.076.068.004.103-.037.146z");
}

.f-nz2tbja {
  fill: var(--svg-color--441e1d, #441e1d);
  d: path("m21.271 36.39l.066.004c-.082.086-.113.238-.283.211c.071-.071.146-.147.217-.215");
}

.f-r0jhf_m {
  fill: var(--svg-color--211f1e, #211f1e);
  d: path("M15.935 18.09c.047-.004.099-.004.146-.008q.031-.03.063-.006a.1.1 0 0 1-.008.071c-.029.028-.068.032-.104.036a.17.17 0 0 1-.104-.031q-.03-.035.007-.062");
}

.f02__1blu {
  fill: var(--svg-color--4c3030, #4c3030);
  d: path("M12.229 28.805c.025.142.029.278-.047.409a.07.07 0 0 1-.037-.059c.038-.111.001-.244.084-.35");
}

.f0d2u4byj {
  fill: var(--svg-color--272828, #272828);
  d: path("M11.933 31.34c.078.023.113-.045.164-.082q.031-.03.062-.006a.56.56 0 0 0-.144.365q-.023.042-.047.004c-.02-.071.012-.15-.043-.221c-.029-.021-.025-.046.008-.06");
}

.f1_1b1b4q {
  fill: var(--svg-color--0a0a0a, #0a0a0a);
  d: path("M16.753 29.885c.014-.017.034-.032.047-.047c.055-.009.11-.042.16 0q.02.048.037.099c-.082-.007-.179.031-.244-.052");
}

.f10k4db1y {
  fill: var(--svg-color--4c3535, #4c3535);
  d: path("m24.87 37.08l-.048-.004l.099-.256c.014.092.038.184-.051.26");
}

.f15nfbb4o {
  fill: var(--svg-color--f4f4f4, #f4f4f4);
  d: path("M21.606 17.659q.05.078.102.151a.14.14 0 0 1 .021.065c0 .023-.01.047-.021.072a.7.7 0 0 1-.184.121a.6.6 0 0 1-.227.021a.16.16 0 0 1-.078-.021a.2.2 0 0 1-.06-.055c.046-.123.017-.271.116-.374c.115-.079.225-.086.331.02");
}

.f26-uabtd {
  fill: var(--svg-color--6b3d0e, #6b3d0e);
  d: path("M22.685 22.372v-.051q.105-.062.213-.121c-.014.121-.117.15-.213.172");
}

.f2je2wbyk {
  fill: var(--svg-color--232424, #232424);
  d: path("M24.09 36.24c.035.116.07.235.059.363h-.11c.05-.125-.01-.247.002-.363q.024-.047.049 0");
}

.f3jwynojs {
  fill: var(--svg-color--675913, #675913);
  d: path("M18.521 19.919c.033 0 .063.005.099.005c-.013.083-.017.17-.12.205c.005-.071.013-.138.021-.21");
}

.f4kv-__2w {
  fill: var(--svg-color--3a2a2a, #3a2a2a);
  d: path("m17.318 32.08l.323-.099c-.039.138-.166.109-.262.142c-.026-.004-.053-.008-.061-.043");
}

.f4l5f17pi {
  fill: var(--svg-color--504d4d, #504d4d);
  d: path("M22.315 18.739c-.086-.024-.184.053-.266-.024c.076-.071.18-.04.266-.071c.024.033.024.062 0 .095");
}

.f5qmow0ws {
  fill: var(--svg-color--cccece, #cccece);
  d: path("m17.231 27.18l.005.012l-.013.01c.031.077.06.155.078.231c0 .116 0 .229-.074.33c-.074.026-.146.039-.168-.068c.004-.054.082-.083.059-.146q.002-.025.005-.039c.017-.122-.038-.252.046-.358c.032-.011.051-.005.062.028");
}

.f6_3vcbmc {
  fill: var(--svg-color--eeeeeb, #eeeeeb);
  d: path("M23.888 19.13q-.098.11-.201.217a.2.2 0 0 1-.07.031a.22.22 0 0 1-.189-.129a.3.3 0 0 1-.021-.117c-.002-.098.007-.193.074-.268c.039-.041.086-.063.146-.052c.205.008.272.13.261.318");
}

.f65ouwbhd {
  fill: var(--svg-color--6f0504, #6f0504);
  d: path("M21.339 25.06h-.418a.42.42 0 0 1 .418 0");
}

.f6g7q4q6m {
  fill: var(--svg-color--262626, #262626);
  d: path("M19.755 28.573c.031.06.051.125.117.155q.03.006.051.005c-.033.051-.068.106-.104.153c-.019.017-.037.021-.058 0c-.041-.046-.056-.114-.093-.168c-.011-.017-.016-.041-.021-.062a.12.12 0 0 1 .045-.08a.07.07 0 0 1 .063-.003");
}

.f6gknp6td {
  fill: var(--svg-color--353737, #353737);
  d: path("M17.951 26.915c-.088-.021-.147-.071-.215-.176c.132.01.183.082.215.176");
}

.f6mrp_zdo {
  fill: var(--svg-color--f0f0f0, #f0f0f0);
  d: path("M18.944 39.76q.001.045-.006.095c.074.105.041.207-.014.307c-.031.074-.054.153-.086.224c-.033.032-.063.065-.099.104c-.103.037-.122-.063-.177-.105c-.035-.096-.061-.196-.114-.278a.46.46 0 0 1-.04-.231a.47.47 0 0 1 .109-.233c.058-.079.074-.175.113-.262a.2.2 0 0 1 .047-.052c.11-.004.08.127.153.16q.009.018.007.045c-.002.086.023.17.107.226");
}

.f6msmvrfr {
  fill: var(--svg-color--441312, #441312);
  d: path("M14.474 28a.1.1 0 0 1-.051-.012q-.054-.174-.104-.357c.162.074.122.238.155.369");
}

.f6wabpldx {
  fill: var(--svg-color--2c2c2c, #2c2c2c);
  d: path("M19.1 28.05a1 1 0 0 0-.09-.009c0-.084.03-.146.114-.185q.017.1.026.193q-.024.024-.05.001");
}

.f7fw0gb8x {
  fill: var(--svg-color--332121, #332121);
  d: path("M22.941 28.05c.022.118.034.235-.04.336c-.054-.117-.013-.23.04-.336");
}

.f7rsyybvf {
  fill: var(--svg-color--412524, #412524);
  d: path("M15.09 18.274a.1.1 0 0 0 .004-.039c.049-.074.133-.048.199-.063l.02.012c-.036.129-.116.154-.223.09");
}

.f7s9stbwi {
  fill: var(--svg-color--494949, #494949);
  d: path("M13.481 35.657a.7.7 0 0 1 .104-.365c.02.013.034.023.038.048c-.045.108.011.258-.142.317");
}

.f89etr9_g {
  fill: var(--svg-color--1f0a0a, #1f0a0a);
  d: path("M19.265 37.03c0-.017 0-.029-.006-.045q.127-.027.254-.059q.028.012.02.023c-.006.006-.012.015-.02.015c-.026.012-.055.026-.033.065c-.071.056-.146.056-.215.001");
}

.f9o-3kbzd {
  fill: var(--svg-color--602a0e, #602a0e);
  d: path("M14.36 20.993c.123-.082.021-.172.004-.254c.135.09.205.185.004.273h-.008z");
}

.fa4h7yw5a {
  fill: var(--svg-color--1b1707, #1b1707);
  d: path("M24.302 38.17c.019-.017.037-.031.055-.052c.119-.004.125.127.207.168l.018.02l-.021.018l.008.019c-.142.023-.218-.053-.267-.173");
}

.faz6lcsny {
  fill: var(--svg-color--551d0c, #551d0c);
  d: path("M22.12 37.495c-.02 0-.031.004-.047.004c.031-.077.061-.166.169-.106z");
}

.fbvb4wy7n {
  fill: var(--svg-color--4c2322, #4c2322);
  d: path("M15.978 34.637c.179.144.109.376.195.555c-.025.054-.057.089-.115.034a1.8 1.8 0 0 1-.133-.412a.24.24 0 0 1 .043-.158z");
}

.fcz1wig3g {
  fill: var(--svg-color--e82017, #e82017);
  d: path("M22.312 21.646a.1.1 0 0 1 .009-.035c.003-.048.006-.099.051-.135c.229-.02.06.186.136.251c.022.129.182.079.229.177q-.014.032-.029.059c-.132.076-.264.139-.414.052q-.02-.002-.021-.021c-.031-.124-.063-.243.039-.348");
}

.fd8r1txsg {
  fill: var(--svg-color--262719, #262719);
  d: path("M16.14 20.758a.4.4 0 0 1 .051.055v.118c-.08-.079-.18-.066-.278-.066c.046-.102.178-.01.227-.107");
}

.fdvec-92v {
  fill: var(--svg-color--710b0b, #710b0b);
  d: path("M16.911 21.292c-.048-.09-.04-.186-.04-.278c.163.074.103.172.04.278");
}

.felnpf62j {
  fill: var(--svg-color--635512, #635512);
  d: path("M21.11 22.286c-.121-.017-.263.02-.349-.109c.139.02.274.036.418.059c.003.05-.011.073-.069.05");
}

.fetu4onyp {
  fill: var(--svg-color--30191a, #30191a);
  d: path("m15.612 25.431l.001-.059c.034-.041.073-.071.134-.047q.027.077.051.16q-.09-.025-.186-.054");
}

.fg5lpt7fq {
  fill: var(--svg-color--095197, #095197);
  d: path("M21.492 21.16c-.104.056-.194-.009-.292-.027a.21.21 0 0 1 0-.221c.044-.026.077-.09.141-.055c.047.004.09.012.139.021c.066.066.133.134.056.238q-.022.024-.044.044");
}

.fhb8aobmv {
  fill: var(--svg-color--625612, #625612);
  d: path("M23.21 39.487c-.125-.021-.125-.021-.063-.263c.091.077.043.185.061.267z");
}

.fhcnljbrp {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M20.326 36.497c-.106.078-.17.235-.339.209c-.071.093-.176.135-.264.199c-.078.028-.152.063-.229.086c-.104.03-.208.063-.311.013c-.106-.065-.104-.177-.104-.278q-.006-1.389 0-2.77c0-.084-.002-.18.058-.248c.063-.057.142-.063.217-.063c.621-.004 1.234-.007 1.854 0c.06 0 .119.009.168.045c.162.224.054.478.087.72c.016.164-.043.321-.055.484a.6.6 0 0 1-.023.163c-.045.09-.09.177-.101.278a.6.6 0 0 1-.108.184a.25.25 0 0 0-.078.18c-.041.129-.125.227-.196.338c-.042.056-.103.09-.144.146c-.076.086-.147.177-.242.242c-.067.016-.122.06-.19.072m-3.226.052c-.047-.036-.1-.074-.145-.115c-.138-.05-.223-.167-.327-.267c-.056-.061-.116-.113-.167-.185c-.051-.077-.102-.153-.123-.247a.7.7 0 0 0-.088-.218a1 1 0 0 1-.068-.122c-.021-.07-.051-.139-.071-.207c-.066-.183-.07-.378-.168-.551a.3.3 0 0 1-.009-.173c.041-.161.013-.332.021-.491c.009-.104-.004-.213.089-.291c.096-.057.199-.039.301-.039q.8-.006 1.602 0c.111 0 .225-.018.328.057c.074.082.066.188.066.293c0 .896.002 1.789 0 2.689c0 .15.004.309-.186.354a.3.3 0 0 1-.085.019c-.104-.008-.183-.099-.286-.117c-.061-.016-.105-.058-.159-.088c-.071-.043-.142-.087-.218-.121c-.114-.035-.198-.134-.307-.18");
}

.fhflvabxh {
  fill: var(--svg-color--42110a, #42110a);
  d: path("M19.05 16.286a.1.1 0 0 0-.004-.043c.057-.078.111-.153.172-.004c-.067-.022-.111.032-.168.047");
}

.fjawgdbgy {
  fill: var(--svg-color--232424, #232424);
  d: path("m13.315 26.788l-.021-.008l-.016.012c.002-.113.037-.209.121-.346a.5.5 0 0 1-.084.342");
}

.fki-m1bak {
  fill: var(--svg-color--5f302e, #5f302e);
  d: path("M23.15 34.556h-.061a.29.29 0 0 1-.033-.271c.072.075.072.177.094.271");
}

.fl0q8vb5t {
  fill: var(--svg-color--1b0d0d, #1b0d0d);
  d: path("M12.399 35.387c-.018.06-.03.112-.047.169l-.019-.426q.029-.034.046.008q.012.124.02.249");
}

.fl8-45vrg {
  fill: var(--svg-color--444135, #444135);
  d: path("M21.909 18.347c-.049.035-.098.063-.148.098c-.054.008-.104.008-.151-.022c-.009-.007-.013-.017-.021-.027c.006-.08.01-.162.018-.235q.009-.016.027-.017c.027.15.178.136.275.203");
}

.fmh_ksb5j {
  fill: var(--svg-color--34170a, #34170a);
  d: path("M16.238 26.722c-.075.109-.224.091-.312.177c.023-.196.207-.129.312-.2z");
}

.fmld6xb9x {
  fill: var(--svg-color--242424, #242424);
  d: path("M19.918 38.911q.031-.001.062.004c.019.086.031.173.047.259c-.016.004-.028.004-.047.004a.053.053 0 0 1-.072-.021c-.044-.086-.052-.164.01-.246");
}

.fmse8ac2l {
  fill: var(--svg-color--3b3635, #3b3635);
  d: path("M20.296 27.18c.004-.079-.094-.023-.105-.079c.013-.103.104-.114.171-.149a.36.36 0 0 1-.066.228");
}

.fnbzstbup {
  fill: var(--svg-color--1b1b1b, #1b1b1b);
  d: path("M13.334 31.448q-.032.086-.116.067c.027-.094.018-.19.104-.259z");
}

.fnry4ubbk {
  fill: var(--svg-color--d6d7d7, #d6d7d7);
  d: path("M18.528 28.616c.104.043.104.156.146.236c-.056.09.121.255-.096.298c-.083-.021-.126-.09-.177-.146a.24.24 0 0 1-.021-.103c.01-.082-.035-.152-.035-.236c.037-.096.09-.145.183-.049");
}

.fo6rc6cto {
  fill: var(--svg-color--4c4b46, #4c4b46);
  d: path("M17.224 18.09h.244c.012.012.017.021.014.04q-.123-.001-.25.005q-.021-.012-.018-.028q.003-.015.01-.017");
}

.fos64bg-d {
  fill: var(--svg-color--3e3d18, #3e3d18);
  d: path("M15.298 20.792q.007-.013.006-.035c.07-.036.125 0 .174.051a.09.09 0 0 1-.02.105c-.025.047-.045.096-.104.105c.03-.08.046-.165-.056-.226");
}

.fphy7wauw {
  fill: var(--svg-color--373838, #373838);
  d: path("M15.195 19.708c-.021.035-.04.072-.065.109l-.013-.008h-.019c.012-.063-.022-.109-.065-.148l.167-.004q.023.013.016.03q-.01.022-.021.021");
}

.fpuymd4fz {
  fill: var(--svg-color--c8ab21, #c8ab21);
  d: path("M15.204 36.549c-.141-.026-.297.069-.429-.06c.021-.016.036-.033.056-.053c.121.016.24 0 .36.012c.042.008.077.025.114.041l-.008.02c.004.014.008.02.008.029c-.031.006-.065.006-.101.011");
}

.fqb5aqb4c {
  fill: var(--svg-color--727171, #727171);
  d: path("M23.462 19.14c-.033-.047-.064-.1-.098-.146c.037-.039.031-.113.104-.117q.024-.026.047-.008a.45.45 0 0 0-.053.271");
}

.fsaevebiu {
  fill: var(--svg-color--5b180c, #5b180c);
  d: path("M20.281 20.812h.051c.028.096.043.18-.038.26c0-.027-.005-.043-.009-.065c0-.066 0-.127-.004-.195");
}

.ft1hc68ru {
  fill: var(--svg-color--363736, #363736);
  d: path("M17.892 38.17c.021.022.041.048.06.069c-.088.013-.104.129-.203.129v-.043c.022-.069.08-.113.143-.155");
}

.ft8fn5bpj {
  fill: var(--svg-color--616768, #616768);
  d: path("m19.425 29.932l-.016-.104l.027-.026a.15.15 0 0 1 .105 0c.008.009.018.021.027.026l-.016.104z");
}

.ftizocckq {
  fill: var(--svg-color--260807, #260807);
  d: path("M15.444 39.593c-.018-.021-.035-.046-.051-.063a1 1 0 0 1 .02-.095c.039 0 .078.004.1.052a1 1 0 0 0-.069.106");
}

.ftqd79b2q {
  fill: var(--svg-color--63302f, #63302f);
  d: path("M13.856 35.29c-.022-.133.039-.252.087-.367a.07.07 0 0 1 .043.059c-.033.104-.024.217-.097.307q-.014.031-.033.001");
}

.ftwbm6_hh {
  fill: var(--svg-color--616262, #616262);
  d: path("M12.856 27.838c0 .083-.031.146-.104.188c-.065-.121.013-.158.104-.188");
}

.fudnhzbqz {
  fill: var(--svg-color--5d190a, #5d190a);
  d: path("M15.04 38.19c.023.12-.043.216-.104.313c-.067-.136.021-.226.104-.313");
}

.fughm-bei {
  fill: var(--svg-color--323434, #323434);
  d: path("M21.699 30.411c-.047-.043-.056-.099-.062-.157c.068-.034.115-.114.203-.114q.03-.017.069-.004c.017.13-.092.189-.146.283q-.033.023-.064-.008");
}

.fv3qu1b5b {
  fill: var(--svg-color--555454, #555454);
  d: path("M13.173 35.872q.025.023.051.056c.008.126.021.253-.051.37a.08.08 0 0 1-.062-.067q.029-.186.062-.359");
}

.fvhx6bbyb {
  fill: var(--svg-color--393b3b, #393b3b);
  d: path("M12.451 32.868c-.062-.063-.071-.127-.032-.233c.065.084.09.137.032.233");
}

.fwfl8dbcf {
  fill: var(--svg-color--39350e, #39350e);
  d: path("M22.957 38.803c-.108.004-.22-.004-.323.042c.092-.147.192-.199.323-.042");
}

.fwzvds90b {
  fill: var(--svg-color--3a3822, #3a3822);
  d: path("M16.49 26.16c-.017-.004-.033 0-.047 0c-.036-.034-.07-.062-.103-.097c.004-.048.008-.099.071-.103c-.055.095.086.118.079.2");
}

.fxn3-gblx {
  fill: var(--svg-color--796915, #796915);
  d: path("M22.18 39.22c.06.095.055.19.004.33a.34.34 0 0 1-.057-.276c.02-.019.018-.054.053-.054");
}

.fycdmjoeh {
  fill: var(--svg-color--626363, #626363);
  d: path("M18.897 38.634c.052-.076-.012-.215.125-.255a.08.08 0 0 1 .06-.026c.04.008.067.021.08.059c-.004.025-.017.037-.042.025c-.154-.022-.053.241-.223.197");
}

.fye_g_5vx {
  fill: var(--svg-color--5d5d5d, #5d5d5d);
  d: path("M22.11 34.87c-.077-.016-.155-.03-.205-.104c.104-.037.178-.019.205.104");
}

.fzlx4rjbf {
  fill: var(--svg-color--3e3e3e, #3e3e3e);
  d: path("M17.318 28.737a.2.2 0 0 0 .054-.009v.318h-.04c-.049-.1-.014-.205-.014-.309");
}

.g_21afbhy {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M13.01 31.673c-.021-.074-.041-.139-.06-.209a.3.3 0 0 0-.036-.227c-.07-.135-.02-.285-.035-.426c.041-.172.022-.357.076-.535c-.02-.117.069-.22.055-.342v-.1c.03-.035.063-.039.102-.023c.054.07.048.165.105.237q.04.091.145.102c.168.181.045.382.029.574c.004.147 0 .308-.027.454q-.001.039-.007.081c-.027.092-.052.185-.106.271c-.029.041-.066.071-.086.115c-.002.057-.031.076-.083.076q-.038-.024-.072-.048");
}

.g_lhmpbtc {
  fill: var(--svg-color--232121, #232121);
  d: path("M18.687 28.726a.3.3 0 0 1 .055-.042q.03-.026.059 0c.035.06.023.118.008.181c-.026.113.035.153.131.168c.046.084.055.166-.002.244a.2.2 0 0 1-.07.036c-.107.021-.216.028-.313-.028c-.054-.045-.031-.098-.01-.145c.086-.089.061-.208.083-.316q.012-.068.059-.098");
}

.g_n0mpqzc {
  fill: var(--svg-color--2b1007, #2b1007);
  d: path("M24.505 37.39c.016.086.057.152.151.168c-.024.053-.118.059-.093.146q-.023.027-.059.011c-.052-.048-.055-.12-.1-.168c-.029-.035-.061-.069-.071-.117c.019-.087.087-.06.144-.063q.015.01.028.023");
}

.g_t8ambjy {
  fill: var(--svg-color--5f5f5f, #5f5f5f);
  d: path("M20.544 40.657c-.037-.098-.128-.18-.039-.297c.032.082.063.155.096.23c-.019.024-.022.06-.057.067");
}

.g-77cubrq {
  fill: var(--svg-color--bababb, #bababb);
  d: path("M19.826 28.18c.246.165.079.365.046.548c-.113.005-.122-.089-.152-.164a.6.6 0 0 1 .004-.251c.016-.06.047-.108.102-.133");
}

.g-ymyhbrl {
  fill: var(--svg-color--262622, #262622);
  d: path("M23.679 19.696v-.188c.105-.014.107.089.16.141c.028.047.021.094-.021.131a.1.1 0 0 1-.073.004c-.041-.013-.048-.056-.066-.088");
}

.g0kilbcer {
  fill: var(--svg-color--54211f, #54211f);
  d: path("M17.737 25.63c.023-.022.066-.039.068-.063c0-.051-.051-.023-.076-.035l-.112-.047c.051-.049.106-.039.167-.017c.059.024.158-.009.159.09c.001.095-.085.09-.147.11q-.044.002-.059-.038");
}

.g0tsz6l5t {
  fill: var(--svg-color--ededed, #ededed);
  d: path("M19.409 29.829c-.049.047-.104.041-.157.009q-.018-.105-.04-.214a.58.58 0 0 1 .102-.353c.02-.015.039-.032.063-.039c.102-.017.143.054.174.134c.03.092-.004.181-.021.271a.3.3 0 0 1-.123.198z");
}

.g0uegrbln {
  fill: var(--svg-color--101010, #101010);
  d: path("M22.386 31.919c-.088.068-.043-.033-.063-.051c.008-.099-.015-.211.108-.264l-.013.061c.044.022.041.048.005.076c-.069.045-.029.121-.037.178");
}

.g1y9ietro {
  fill: var(--svg-color--5e3a3a, #5e3a3a);
  d: path("M12.706 26.928a.8.8 0 0 1-.105.353c-.045-.141-.021-.265.105-.353");
}

.g370__4ea {
  fill: var(--svg-color--563331, #563331);
  d: path("m18.02 37.02l-.064.031c-.07-.051-.138-.086-.206-.131c.015-.012.036-.024.054-.036c.077.034.191.012.216.136");
}

.g3ak6gbpr {
  fill: var(--svg-color--c3c4c4, #c3c4c4);
  d: path("M17.849 27.465v.062c-.039.088.037.174 0 .26c.021.035.035.07.056.103c-.032.083.022.204-.111.245a1.1 1.1 0 0 1-.104-.504c.003-.103.019-.193.159-.166");
}

.g3p39r_1o {
  fill: var(--svg-color--766b2a, #766b2a);
  d: path("M21.761 20.345c.146-.003.01.259.198.208c-.003.06.009.118-.053.146a.16.16 0 0 0-.106-.043c-.09-.092-.023-.208-.039-.311");
}

.g3p6kyb6g {
  fill: var(--svg-color--280d08, #280d08);
  d: path("M22.17 37.558c0 .035.003.063.005.1c-.021.023-.062.069-.066.065c-.09-.063-.037-.147-.031-.226q.019-.031.047-.002q.021.034.045.063");
}

.g3umo7byz {
  fill: var(--svg-color--413232, #413232);
  d: path("M14.158 34.18c.097.065.002.137.008.204c.007.094-.053.207.086.255q.046.033.011.073c-.099.1-.123-.094-.205-.047c-.037.026-.067.026-.103-.004c.146-.125.103-.332.203-.481");
}

.g4ddmib6p {
  fill: var(--svg-color--dbdde0, #dbdde0);
  d: path("M20.339 18.04c.147-.006.291-.016.436-.02c.033 0 .064-.004.093-.004c.09.004.177.004.261.012l-.002.061l.004-.004c-.082.074-.181.037-.271.025c-.17-.02-.344.037-.512-.039c-.003-.007-.003-.017-.009-.031");
}

.g4gjhcdht {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M20.921 40.454c.021.043.036.086.055.125a.29.29 0 0 1 .1.231c.02.078.034.166.053.245c-.07.188-.158-.01-.236.012q-.062-.054-.123-.115a.23.23 0 0 1-.158-.138l-.064-.194c-.023-.071-.044-.146-.082-.217a.6.6 0 0 1-.061-.119c-.027-.074-.051-.148-.08-.224a1.2 1.2 0 0 0-.12-.239c-.047-.063-.086-.139-.125-.209c-.03-.082-.101-.17-.06-.268c.035-.053.082-.03.125-.021q.034.014.064.031c.072.057.151.096.229.153a.8.8 0 0 1 .111.209l.157.267a.7.7 0 0 1 .129.221a.44.44 0 0 1 .086.25");
}

.g5ip3wkuq {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M15.878 18.247c.018-.008.03-.008.045-.012c.012.012.019.02.016.035q-.005.017-.006.016c-.019.018-.039.018-.049-.004q-.011-.011-.006-.035");
}

.g5ja8sgfh {
  fill: var(--svg-color--5c1a0b, #5c1a0b);
  d: path("m15.341 37.504l-.089.038c.013-.086-.053-.116-.108-.152c.125-.071.16.023.197.114");
}

.g5t8hdbik {
  fill: var(--svg-color--918329, #918329);
  d: path("M13.847 19.969q-.022.007-.045.008c-.063-.047-.017-.119-.047-.169c-.005-.035-.013-.08.035-.095c.03.016.07.036.104.056z");
}

.g63dv-bhd {
  fill: var(--svg-color--600e0b, #600e0b);
  d: path("M18.06 23.23c.416-.03.832-.063 1.248 0c.016.004.022.017.016.028q-.006.017-.014.016h-1.252q-.024-.012-.016-.031q.009-.013.018-.013");
}

.g6b-vwell {
  fill: var(--svg-color--5e5a49, #5e5a49);
  d: path("M16.214 18.02q.04.006.079.014c.017.021.017.037.005.062a.13.13 0 0 1-.064.021a.14.14 0 0 1-.061-.027q-.017-.035.016-.059l.012-.013z");
}

.g6mdwdjpe {
  fill: var(--svg-color--321d1d, #321d1d);
  d: path("M17.326 34.411c-.021.021-.034.035-.06.047c-.086-.004-.18.009-.25-.06z");
}

.g6x4-r_3s {
  fill: var(--svg-color--57310c, #57310c);
  d: path("M18.06 16.562c-.002-.018-.004-.027 0-.043c.082.018.119.08.16.143q-.117.014-.16-.1");
}

.g7hwebv4x {
  fill: var(--svg-color--424343, #424343);
  d: path("M14.522 32.616a.45.45 0 0 1-.039.317q-.031.033-.059 0c.021-.108.007-.231.098-.317");
}

.g7lmr-qnm {
  d: path("M12.901 31.579c.016-.041.035-.075.052-.115q.112.082.06.209c-.033.048-.065.018-.098 0q-.013-.055-.014-.094");
}

.g7w-hkbwq {
  fill: var(--svg-color--500806, #500806);
  d: path("M25.09 34.719c.014 0 .027-.006.042-.006c0 .122.028.258-.042.37l-.025-.034c0-.074-.021-.163.017-.235q.002-.052.008-.095");
}

.g80qggulx {
  fill: var(--svg-color--4c4e4e, #4c4e4e);
  d: path("M20.466 39.475c-.024.021-.039.038-.061.062c-.084-.037-.186-.045-.217-.151c.104-.002.188.05.278.089");
}

.g82hed_zo {
  fill: var(--svg-color--4b4733, #4b4733);
  d: path("M14.675 18.855V18.8c.034-.052.069-.095.102-.146h.043c.063.09.023.16-.034.228c-.044.017-.085.023-.111-.027");
}

.g8rzfib8r {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("M22.427 32.391v-.03c-.009-.145-.012-.3-.09-.433c-.021-.08-.025-.153.049-.213c.088-.019.123.06.178.095a.2.2 0 0 1 .062.038c.063.04.16.052.167.153q.03.078.057.156c.004.09-.017.178.021.27a.47.47 0 0 0 .081.29l.002.106c.02.121-.025.26.096.354l.008.069c-.023.182.043.345.078.518c.019.104.051.197.071.302c.03.097.043.201.082.298c0 .082.047.156.004.239c-.06.054-.122.136-.157-.021a2 2 0 0 1-.074-.301q.005-.017-.008-.029c-.084-.057-.056-.157-.095-.225q.006-.023-.01-.035c-.078-.06-.062-.154-.099-.231c.004-.013.004-.022-.006-.036c-.131-.105-.121-.271-.166-.414c.017-.167-.09-.296-.121-.447c-.057-.154-.063-.32-.13-.473");
}

.g8urg9ajs {
  fill: var(--svg-color--3f4040, #3f4040);
  d: path("M19.89 35.448h.043c.086.026.146.09.17.183c-.014.038-.043.06-.084.038c-.129-.025-.144-.115-.129-.221");
}

.g97wi4bqq {
  fill: var(--svg-color--585757, #585757);
  d: path("m23.767 27.27l-.024.004l-.022-.017c-.022-.047-.076-.09-.022-.148c.011-.016.054-.031.058-.023c.049.056-.002.12.01.184");
}

.g9863-bwq {
  fill: var(--svg-color--4a462c, #4a462c);
  d: path("M20.574 26.585c-.008.055-.171.035-.069.141c.027.041.032.075 0 .109a.1.1 0 0 1-.041.013c.023-.099-.174-.122-.082-.228c.049-.051.115-.11.192-.035");
}

.g9krq2b4o {
  fill: var(--svg-color--584c11, #584c11);
  d: path("M22.12 23.45q-.003.011.004.026c-.148.015-.279.002-.361-.146c.121.034.252.034.357.12");
}

.g9o3dtmkl {
  fill: var(--svg-color--500705, #500705);
  d: path("m12.261 34.3l.037.36c-.106-.088-.051-.207-.066-.313q.015-.027.029-.047");
}

.g9ub6xxka {
  fill: var(--svg-color--1a2321, #1a2321);
  d: path("M21.534 21.12c.027-.096-.031-.168-.055-.24q.195.076.055.24");
}

.ga7053__c {
  fill: var(--svg-color--485455, #485455);
  d: path("M20.335 35.915q.146-.116.287.007c-.1.069-.191.036-.287-.007");
}

.gcmbbycuf {
  fill: var(--svg-color--4e2625, #4e2625);
  d: path("M20.599 34.403c.021-.011.039-.027.057-.039c.09.012.125.067.107.149a1.4 1.4 0 0 1-.164-.11");
}

.ge3euccqh {
  fill: var(--svg-color--4f300b, #4f300b);
  d: path("M15.09 40.661c0-.02.002-.049.004-.07c.055.066.129.048.198.04c-.053.106-.11.169-.202.03");
}

.gench440b {
  fill: var(--svg-color--2a2b2b, #2a2b2b);
  d: path("M24.09 36.24h-.052a1.1 1.1 0 0 1-.093-.367h.035c.075.111.071.244.11.367");
}

.ghai5fbmk {
  fill: var(--svg-color--5a2c2b, #5a2c2b);
  d: path("m23.776 36.04l.009-.135a.7.7 0 0 1 .091.295c-.094-.012-.1-.084-.1-.16");
}

.gi-ql72vp {
  fill: var(--svg-color--d3d3d3, #d3d3d3);
  d: path("M17.724 28.573c-.016.07-.119.031-.127.109c-.037.079-.072-.005-.109-.005l-.012-.199c.039-.091-.072-.239.113-.269c.077.108-.015.284.135.364");
}

.gi3o8rblt {
  fill: var(--svg-color--550404, #550404);
  d: path("M25.302 33.616c-.031-.112.004-.225.045-.33c.078.111.069.222-.02.322c-.01.006-.019.006-.025.008");
}

.gj9c3nbwb {
  fill: var(--svg-color--5d3938, #5d3938);
  d: path("M14.313 27.595q-.05-.125-.1-.244c.132.042.154.126.1.244");
}

.gjkxqzbgj {
  fill: var(--svg-color--562f0f, #562f0f);
  d: path("M18.792 16.09c.016-.08.122-.114.107-.213c.106.146.02.189-.107.213");
}

.gjqltzboy {
  fill: var(--svg-color--212121, #212121);
  d: path("M22.784 31.523c.018-.018.029-.036.045-.056c.025.066.055.135.079.205c-.06.004-.103-.014-.128-.067q.003-.039.004-.082");
}

.gk6k1mbhg {
  fill: var(--svg-color--461608, #461608);
  d: path("M24.21 39.31c.06-.135.04-.271-.006-.404q-.039-.034 0-.076c.03.009.063.013.095.021c.027.021.027.048.008.071c-.039.127.092.298-.097.388");
}

.gk7474bqt {
  fill: var(--svg-color--fbfbfb, #fbfbfb);
  d: path("M20.294 17.618c-.002.08.008.166-.053.232c-.005.102-.063.148-.154.168c-.111.008-.187-.051-.253-.134c-.063-.091-.084-.181-.014-.279a.1.1 0 0 0 .012-.05a.3.3 0 0 1 .244-.076c.095.014.15.084.218.139");
}

.gkfmtkx2k {
  fill: var(--svg-color--2d2d2d, #2d2d2d);
  d: path("M24.87 29.993c-.037-.172-.07-.34-.105-.515c.131.154.125.339.152.515q-.023.037-.047 0");
}

.glddq-b6o {
  fill: var(--svg-color--786d28, #786d28);
  d: path("M14.993 20.444v.069c-.029-.024-.06-.05 0-.069");
}

.glo901bsy {
  fill: var(--svg-color--484848, #484848);
  d: path("M18.06 27.786c-.084-.107-.043-.25-.105-.365q.049-.005.098-.004q.027.19.047.373q-.02.001-.04-.004");
}

.glz1o9bhv {
  fill: var(--svg-color--1f0a0a, #1f0a0a);
  d: path("M25.397 29.991q-.02-.001-.043.004c0-.095-.079-.166-.053-.263c.016-.02.027-.043.045-.059c.059.093.051.208.051.318");
}

.gm2y46bek {
  fill: var(--svg-color--272a2a, #272a2a);
  d: path("M19.822 38.34h.05l-.042.152c.017.061-.017.067-.062.061c-.068-.063-.101-.131-.057-.223c.038-.023.075-.027.111.01");
}

.gnnzddbtz {
  fill: var(--svg-color--6c6d6d, #6c6d6d);
  d: path("M19.46 38.01c-.17-.053-.101-.153-.048-.246c.091.064.028.167.048.246");
}

.gnybnlb_j {
  fill: var(--svg-color--4e2928, #4e2928);
  d: path("M21.962 29.417q-.148.079-.289.158c.036-.153.159-.179.289-.201c.016.013.024.02.018.031q-.01.012-.018.012");
}

.gqxh-kbne {
  fill: var(--svg-color--1f2020, #1f2020);
  d: path("M22.269 31.04a.1.1 0 0 0 .047 0c.135.102.008.207.008.311c-.098-.09-.052-.206-.055-.311");
}

.gr6c_xt_x {
  fill: var(--svg-color--2e2009, #2e2009);
  d: path("M12.905 37.39q.004-.032.006-.066c.096.056.257-.088.313.104q-.038.007-.07.008c-.068.053-.113.13-.191.161q-.055.004-.107.003l-.006-.063c.021-.05.04-.096.055-.147");
}

.gretulbkn {
  fill: var(--svg-color--585858, #585858);
  d: path("M12.709 35.788q-.027-.056-.056-.127q.008-.032.006-.056c.016-.021.032-.038.044-.06l.041.004a.34.34 0 0 1-.035.239");
}

.grxa3cxpg {
  fill: var(--svg-color--39310b, #39310b);
  d: path("M14.946 39.43c-.021.021-.043.039-.063.065l-.063-.057a.18.18 0 0 0 .061-.146c-.027-.06 0-.064.045-.06q.008.102.02.198");
}

.gs0y3fbzm {
  fill: var(--svg-color--d8c024, #d8c024);
  d: path("M14.222 20.812c-.069-.141-.271-.175-.276-.363c-.029-.068-.034-.115.06-.115c.153.111.266.244.358.406c.062.069.125.142.044.239c-.124.014-.102-.135-.186-.167");
}

.gsaeudbdf {
  fill: var(--svg-color--4c350c, #4c350c);
  d: path("m22.427 26.22l.002-.057c.146-.121-.002-.307.099-.438c.002.172.157.372-.101.495");
}

.gsejf2toi {
  fill: var(--svg-color--9a9b9b, #9a9b9b);
  d: path("M20.238 27.79c-.062.021-.044.074-.062.113a.1.1 0 0 1-.039-.009c.018-.079-.024-.176.086-.219h.006c.005.042.005.08.009.115");
}

.gslwzueki {
  fill: var(--svg-color--edeeee, #edeeee);
  d: path("M22.02 18.71c.012 0 .019 0 .029.005c.088-.019.178-.015.27-.024c.063.018.102.061.145.105c.043.052.037.119.043.178a.17.17 0 0 1 0 .152a.16.16 0 0 1-.084.084a.16.16 0 0 1-.115.012c-.096-.032-.205-.008-.291-.066c-.104-.106-.049-.232-.043-.351a.4.4 0 0 1 .019-.071c.012-.007.018-.014.027-.024");
}

.gstqxxbyc {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("M15.655 35.495q-.073.012-.143.017c-.063.04-.129.052-.201.011c-.066-.128-.004-.23.086-.32c.063-.082.099-.201.22-.224c.041-.093.126-.085.199-.101l.061-.062c.035-.028.067-.028.099.011c.067.131.104.266.125.414c-.035.029-.01.062.006.098l-.098.06a.8.8 0 0 0-.354.096");
}

.gtwzbrhue {
  fill: var(--svg-color--5d562d, #5d562d);
  d: path("M15.556 19.354a1 1 0 0 0 .015.142c-.013.043-.039.063-.08.071a.13.13 0 0 1-.117-.079a.23.23 0 0 1 0-.19a.12.12 0 0 1 .093-.06q.016-.001.037.004c.015.04.03.072.052.112");
}

.gugjgus4h {
  fill: var(--svg-color--f9d629, #f9d629);
  d: path("M22.16 38.16c.009-.004.011-.014.007-.022c.146-.104.153.047.209.121q.105.302.209.608a.08.08 0 0 1 .008.066c-.055.116-.063.243-.096.364c0 .04-.004.073-.005.108c.001.141-.097.258-.069.396c0 .014-.004.023-.009.039a.16.16 0 0 1-.06.054a.4.4 0 0 1-.25-.006c-.116-.052-.031-.177-.094-.254c0-.019-.004-.028-.008-.042a.8.8 0 0 1-.068-.225c-.053-.246-.09-.488.021-.732c.016-.07.034-.143.057-.207c.005-.116.064-.198.148-.268");
}

.guji0t-wy {
  fill: var(--svg-color--321717, #321717);
  d: path("M22.464 35.34c-.084-.039-.141-.092-.066-.188c.07.052.152.013.229.033c.048-.024.062-.004.06.042c-.072.042-.209-.037-.223.113");
}

.guy1cykhz {
  fill: var(--svg-color--521c0a, #521c0a);
  d: path("M24.757 37.552c.047-.048.062-.107.014-.17c.117.004.119.08.095.156c-.019.072-.066.057-.109.014");
}

.gv_egqb7g {
  fill: var(--svg-color--edcc27, #edcc27);
  d: path("M19.302 17.61a.2.2 0 0 1-.049.043c-.091.063-.171-.033-.256-.016a.27.27 0 0 1-.167-.009c-.082-.063-.167-.063-.255-.027c-.091.022-.188.027-.279.052a.14.14 0 0 1-.072-.009c-.049.027-.082 0-.11-.04c.013-.07-.015-.148.047-.205q.047-.03.099-.055l.633-.012c.074-.031.141-.004.211.012c.037 0 .07 0 .111.005c-.042.116.149.144.087.261");
}

.gv7-05t1q {
  fill: var(--svg-color--0051a2, #0051a2);
  d: path("M15.255 23.12c-.017.061-.062.086-.109.11c-.127.048-.248.048-.346-.067c-.082-.104-.019-.172.039-.248q.084-.062.161-.125q.117.034.231.074c.089.079.146.159.024.256");
}

.gvmaw_3mu {
  fill: var(--svg-color--252727, #252727);
  d: path("M24.509 36.497c-.031-.133-.158-.26-.053-.412c.031.138.061.279.096.412q-.022.036-.043 0");
}

.gvus4zbjs {
  fill: var(--svg-color--4e2727, #4e2727);
  d: path("M15.847 31.987h.004c-.026-.092.021-.16.07-.232c.025.063.064.136.047.209c-.043-.02-.084-.001-.121.023");
}

.gvwlibb2s {
  fill: var(--svg-color--5e270b, #5e270b);
  d: path("M23.679 38.626q.049.14.1.279c-.135-.056-.192-.14-.1-.279");
}

.gw2casd5m {
  fill: var(--svg-color--551c10, #551c10);
  d: path("M20.226 18.239q.143-.008.283-.009c.104.009.213-.003.305.056c.021.012.025.026.021.035c-.008.012-.012.016-.021.016c-.191-.074-.4-.008-.588-.098");
}

.gwce6xbeh {
  fill: var(--svg-color--444545, #444545);
  d: path("M15.558 30.946c-.178.157-.256.06-.313-.119c.09 0 .143.183.257.057c.017.017.035.043.056.062");
}

.gwmy_qb3k {
  fill: var(--svg-color--343434, #343434);
  d: path("m18.411 38.24l.012.271c-.049-.027-.059-.139-.152-.079c.022-.05.045-.092.064-.144c.01-.044.029-.065.076-.048");
}

.gxgf65bel {
  fill: var(--svg-color--342d0c, #342d0c);
  d: path("M23.994 39.07h.054c.059.086.084.174-.007.264q.001-.033-.004-.061c-.015-.068-.026-.139-.043-.203");
}

.gycoizcoh {
  fill: var(--svg-color--592626, #592626);
  d: path("M18.431 41.684c.026.095.059.192.088.288c-.137-.012-.092-.157-.15-.217q.006-.055.062-.071");
}

.gyns-panl {
  fill: var(--svg-color--432424, #432424);
  d: path("m23.888 36.3l.099.303q-.025.034-.052.004c-.063-.096-.139-.19-.047-.307");
}

.gz5j8n0dy {
  fill: var(--svg-color--52460f, #52460f);
  d: path("M23.15 37.508c.078-.07.22.067.267-.082c.035.019.063.04.095.06l.012.055c-.119.048-.241.021-.364.015a.3.3 0 0 0-.01-.048");
}

.gzf4snbat {
  fill: var(--svg-color--494949, #494949);
  d: path("M23.25 34.35c-.062-.072-.06-.174-.083-.268q.012-.033.041-.047c.068.094.082.205.1.313q-.027.04-.058.002");
}

.gzxnigk2t {
  fill: var(--svg-color--5c5c5d, #5c5c5d);
  d: path("M24.26 33.35q.02-.057.043-.112c.084.209.039.428.045.637c-.039.135-.01.267-.02.404c-.018.181.038.373-.033.551c-.064-.404-.033-.813-.035-1.229a.37.37 0 0 0 0-.251");
}

.h-0fellfc {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M24.2 20.564a.25.25 0 0 1-.241.127a.3.3 0 0 1-.105-.062c-.084-.104-.141-.208-.117-.346a.2.2 0 0 1 .04-.076a.35.35 0 0 1 .317-.077c.09.022.131.102.176.168c.014.098.014.191-.07.266");
}

.h-v7oibjx {
  fill: var(--svg-color--363636, #363636);
  d: path("M17.454 29.32c.096.023.102-.084.154-.115c.027.008.041.024.033.047c-.078.095-.051.203-.045.311c.024.059-.002.067-.053.063c.017-.117-.071-.199-.089-.306");
}

.h-zgmhbsm {
  fill: var(--svg-color--5c2d0d, #5c2d0d);
  d: path("M22.489 21.751h.051c.035.091.213-.008.197.152c-.078-.056-.216-.013-.248-.152");
}

.h0j06cbhb {
  fill: var(--svg-color--4a2524, #4a2524);
  d: path("M20.31 30.68c-.115.082-.26.038-.379.094c.091-.173.235-.119.379-.094");
}

.h0pk-5bcc {
  fill: var(--svg-color--4c4f4f, #4c4f4f);
  d: path("M20.14 40.485c.031.09.063.176.092.27c-.012.019-.012.054-.047.06c-.027-.109-.146-.21-.045-.33");
}

.h20t7ob8s {
  fill: var(--svg-color--fee72c, #fee72c);
  d: path("M14.375 37.28c-.079-.004-.167.045-.225-.051c.004-.018.009-.025.015-.038c.071.05.225-.1.236.099l-.012-.01z");
}

.h2hbfpszp {
  fill: var(--svg-color--424242, #424242);
  d: path("M19.12 38.435c.014.012.027.008.04 0c.062-.006.093.025.104.08l-.01.073c-.069-.03-.13-.064-.134-.153");
}

.h322q8o8r {
  fill: var(--svg-color--682c0f, #682c0f);
  d: path("M16.702 21.48v-.022c.07-.043.109-.125.201-.125c-.032.093-.087.164-.201.147");
}

.h3rntac1y {
  fill: var(--svg-color--6c3e10, #6c3e10);
  d: path("M22.22 21.501c.002-.021.002-.036.002-.055c.057-.048.109-.06.156.016a.1.1 0 0 1 0 .031l-.058.119z");
}

.h4sz59bic {
  fill: var(--svg-color--323333, #323333);
  d: path("M13.794 31.754c.051.067.133.062.201.088c-.117.09-.205.112-.201-.088");
}

.h55pvyb6k {
  fill: var(--svg-color--575959, #575959);
  d: path("M18.224 37.18q.019-.016.041-.004c-.02.104-.035.217-.153.265a.31.31 0 0 1 .112-.261");
}

.h5lhmnbvl {
  fill: var(--svg-color--654511, #654511);
  d: path("M17.7 20.978c-.007-.122-.014-.24.143-.279c-.049.089-.096.189-.143.279");
}

.h5nx6zbse {
  fill: var(--svg-color--323333, #323333);
  d: path("M18.01 38.491q.024-.001.049.004c.062.008.054.058.063.104l-.073.207q-.032.03-.059-.004z");
}

.h8ciyib_m {
  fill: var(--svg-color--dedee1, #dedee1);
  d: path("M15.978 20.302c-.019-.063-.024-.141-.112-.164c-.028-.009-.06-.009-.062-.053q.024-.104.137-.108c.068.065.141.134.209.208c.016.122.016.239-.166.141z");
}

.h8w3ypm0d {
  fill: var(--svg-color--3b3c3c, #3b3c3c);
  d: path("M18.214 27.79c.178 0 .137.177.207.264l.006-.004c-.111.074.041.203-.06.279c-.185.035-.171-.189-.299-.232a.2.2 0 0 1-.043-.059a.26.26 0 0 1 .002-.229a.1.1 0 0 1 .062-.04a.1.1 0 0 1 .084.056c.016.02.021.043.039.063c-.002-.031-.022-.063.002-.098");
}

.h9_cvc-6y {
  fill: var(--svg-color--fdfefe, #fdfefe);
  d: path("m25.23 33.997l-.004.015c0 .108-.082.188-.094.289c.012.135-.031.261-.031.39q.001.06-.004.123c-.029.086-.006.184-.037.273c-.018.07.002.143-.02.213c-.013.191-.029.38-.066.568c-.019.299.041.603-.049.898q-.019.025-.009.048c-.047.083.009.201-.087.267c-.092.101-.146.043-.184-.051c-.01-.063-.055-.111-.076-.168c-.012-.021-.016-.048-.021-.072c-.007-.096-.035-.189-.059-.285c-.04-.141-.055-.278-.092-.416a1 1 0 0 1-.014-.117a.7.7 0 0 0-.037-.277c-.017-.053-.017-.111-.021-.172c-.012-.219.031-.445-.04-.667c-.021-.198-.009-.399-.014-.603q.004-.18.003-.364c-.011-.203.022-.407-.025-.612a.63.63 0 0 1-.003-.33a.8.8 0 0 0 .033-.267a.4.4 0 0 1 .016-.11c.012-.074.035-.145.035-.225q.006-.072.023-.146a.7.7 0 0 0 .031-.184c.008-.111.058-.227.049-.342q.008-.08.022-.157a.7.7 0 0 0 .028-.235c.004-.139-.01-.272.014-.41a.2.2 0 0 1 .059-.094c.113-.027.137.133.244.112c.111-.075.041-.192.057-.287c.004-.047.015-.099.048-.134c.094-.047.133.031.187.08c.021.035.026.07.024.109c-.026.1.004.186.052.262c.043.098.081.199.148.281q.023.028.039.063c.072.121.059.253.057.389v.426c.028.242-.04.479-.027.723c-.004.137.033.273-.045.4v.084c.039.109-.014.222-.027.334a1 1 0 0 1-.083.378m-12.902.705c.009-.008.011-.021.004-.03c-.095-.13-.008-.3-.088-.431a.8.8 0 0 1-.09-.301c-.022-.06-.026-.123-.05-.187c-.006-.097-.03-.181-.051-.271c-.004-.084-.002-.161-.004-.243c-.012-.162-.045-.32-.017-.479a.2.2 0 0 0 .017-.069c.051-.088-.072-.13-.052-.209v-.829c0-.134-.017-.271.072-.389a2 2 0 0 0 .116-.232c.035-.074.062-.156.084-.231c.023-.071.046-.146.056-.216c.019-.086.038-.166.133-.185c.144.078.093.216.099.33a.3.3 0 0 1-.016.079c-.012.059-.07.094-.091.153q-.005.013-.006.028c.013-.014.011-.033.022-.047a.1.1 0 0 1 .053-.043q.032-.006.066-.005c.084.025.186-.088.26.028c.051.133.004.285.056.416c.015.074.028.158.053.232a.5.5 0 0 1 .022.118q-.017.258.082.503c.035.129.012.268.06.396l.013.079c.002.09.002.18.032.267c.037.149-.065.287-.03.44c0 .447.017.899-.002 1.349c-.033.085-.115.155-.055.259c.01.135.007.271.01.405c-.003.08-.003.165-.021.247a.7.7 0 0 0-.034.234c-.003.115-.003.231-.065.336c-.061.072-.023.172-.068.252a.5.5 0 0 0-.022.228a.4.4 0 0 1 0 .138c-.04.065-.088.133-.11.211c-.047.08-.092.153-.187.053c-.069-.063-.054-.178-.11-.243c-.006-.067.006-.14-.014-.201c-.031-.188 0-.38-.021-.571a.4.4 0 0 1-.018-.119c.036-.074.014-.147-.02-.22c-.016-.114.008-.231-.026-.349c-.009-.077-.005-.159-.007-.238c-.014-.094-.025-.188-.045-.277c-.006-.06-.012-.117.01-.166");
}

.h9rax1v_b {
  fill: var(--svg-color--191919, #191919);
  d: path("M13.11 34.923h-.086c.027-.037-.155-.127.031-.119c.023.01.045.01.067.018z");
}

.h9tmqrb3v {
  fill: var(--svg-color--f7df2b, #f7df2b);
  d: path("m14.937 40.05l-.022.008l-.025-.008q.011-.044.024-.083c.144-.082.3-.056.454-.056c.045.016.09.026.086.09q-.048.028-.104.057a1.2 1.2 0 0 0-.413-.008");
}

.h9uhmundc {
  fill: var(--svg-color--6a6a6a, #6a6a6a);
  d: path("M24.777 34.31c-.019-.056.002-.125-.054-.171c-.006-.05-.014-.121.037-.132c.069-.017.064.062.057.104c-.005.07-.025.135-.04.199");
}

.havuhac8n {
  fill: var(--svg-color--540f0a, #540f0a);
  d: path("m14.942 26.15l-.006.108c-.102-.177-.198-.343-.012-.522a.73.73 0 0 0 .018.414");
}

.hazo93qod {
  fill: var(--svg-color--8a7817, #8a7817);
  d: path("M17.948 22.11c-.041-.052-.104-.031-.155-.048c.155-.075.315-.043.478-.038c.018.01.021.019.018.026q-.007.01-.018.011a.3.3 0 0 1-.053.042q-.136.009-.27.007");
}

.hchsjjbwd {
  fill: var(--svg-color--2d0605, #2d0605);
  d: path("M21.13 35.482c.078.093-.019.136-.053.193c-.039-.079.021-.133.053-.193");
}

.he1h0wrgf {
  fill: var(--svg-color--2a2b2b, #2a2b2b);
  d: path("M21.652 35.546c.036-.016.075-.031.108-.051q.074.012.146.017q.018.016.009.034c-.004.018-.008.021-.011.021c-.073-.008-.154-.022-.156.091c-.061-.011-.073-.062-.096-.112");
}

.hf88tgb4i {
  fill: var(--svg-color--343535, #343535);
  d: path("M22.02 32.985c-.084-.041-.068-.121-.073-.197c-.004-.047-.043-.11.056-.116c-.023.108.095.204.017.313");
}

.hggbetbbw {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M22.579 30.31q0 .102-.004.205l-.045.106c.006.078-.029.137-.096.177a.14.14 0 0 1-.069.004a.3.3 0 0 1-.084-.067c-.134-.125-.097-.299-.13-.455a.8.8 0 0 1-.066-.231a.13.13 0 0 1 .028-.066c-.013-.083.009-.142.108-.151c.086.033.201-.064.27.061c.031.134.016.288.088.417");
}

.hhlxddb4n {
  fill: var(--svg-color--503e3e, #503e3e);
  d: path("M23.525 35.14c.062.078.062.178.093.27c-.127-.051-.154-.15-.093-.27");
}

.hhotmhb7g {
  fill: var(--svg-color--3a3935, #3a3935);
  d: path("m13.794 20.554l-.063.051c-.084-.004-.165-.004-.248-.008c.07-.066.137-.125.207-.188q.1.037.104.145");
}

.hhryes23a {
  fill: var(--svg-color--202121, #202121);
  d: path("m24.04 35.08l.052.055v.209h-.043a9 9 0 0 0-.052-.264c.017-.022.026-.022.043 0");
}

.hihm8jbsm {
  fill: var(--svg-color--341818, #341818);
  d: path("M20.446 35.04c-.129-.075-.125-.202-.09-.329c.014-.022.025-.022.041 0q.026.165.049.329");
}

.hjc_39loa {
  fill: var(--svg-color--dfc327, #dfc327);
  d: path("M16.521 26.474c.009-.016.016-.021.029-.043q.046-.046.055.021h.02l.002.02c.104.043.206.087.303.152c.041.009.084.009.094.063c-.094.1-.213.09-.334.08c-.145.055-.314.042-.43.176c-.021.006-.035.014-.055.014c-.098 0-.208.07-.279-.063l.004.008c.043-.13.192-.098.271-.177c.09-.043.184-.076.258-.146c.051-.012.043-.043.021-.08q.006-.037.041-.025");
}

.hjtplecca {
  fill: var(--svg-color--60380f, #60380f);
  d: path("M16.968 22.778c-.014-.087.002-.178-.076-.24c.151.02.164.063.076.24");
}

.hk07zkb4z {
  fill: var(--svg-color--191818, #191818);
  d: path("m22.423 31.743l-.005-.078c.099.041.125.117.112.218c-.072-.021-.06-.105-.107-.14");
}

.hl6onjbib {
  fill: var(--svg-color--5b5b5b, #5b5b5b);
  d: path("M22.957 30.411q.05.025.099.055c.015.127.031.248-.162.208l.004.004c.02-.085.039-.181.059-.267");
}

.hle59yb7z {
  fill: var(--svg-color--581817, #581817);
  d: path("M18.1 37.03c-.021-.004-.039-.01-.057-.01c.193-.023.236-.141.23-.333c-.014-.981-.014-1.972-.019-2.96c.037-.023.062-.021.093.016c.068.111.061.231.061.354q.003 1.282 0 2.563c0 .127.01.248-.064.355c-.08.06-.16.041-.244.015");
}

.hmq9z1bbd {
  fill: var(--svg-color--323232, #323232);
  d: path("M17.958 29.26c-.009-.058-.016-.118.039-.161c.035.061.096.114.043.197c-.025-.014-.057-.02-.082-.036");
}

.hmtdxlbuk {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M18.216 29.876c.014-.016.029-.023.045-.034c.043-.052.041-.007.045.019l-.004.021l.014.004a1 1 0 0 1-.1-.01");
}

.hnvjbx_1u {
  fill: var(--svg-color--1f1f1f, #1f1f1f);
  d: path("m20.609 29.25l-.108.008a.1.1 0 0 1-.113.015q-.1-.062-.08-.187c.008-.025.02-.051.049-.065c.066.071.137.142.248.131c-.001.031.004.062.004.098");
}

.hnylsz7oh {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M22.642 33.739c-.006.062-.008.131-.012.187c-.047.062.018.203-.134.181c-.095-.052-.116-.156-.166-.236l-.014-.086c-.083-.054-.06-.15-.097-.229c-.021-.052-.023-.117-.11-.102q-.01-.012-.017-.026a.8.8 0 0 0-.07-.322a1 1 0 0 1-.045-.131c-.018-.094-.025-.187-.034-.278a.4.4 0 0 0-.03-.125c-.018-.057-.037-.106-.037-.162a.43.43 0 0 0-.018-.229a.4.4 0 0 1-.004-.143a.3.3 0 0 1 .062-.135c.039-.041.081-.062.134-.046c.09.054.146.157.27.149c.154.06.099.209.139.316a.4.4 0 0 1 .008.068c.016.175.069.336.112.5c.021.156.136.282.131.449c.019.144.014.277-.068.4");
}

.hp8pvab3z {
  fill: var(--svg-color--40230c, #40230c);
  d: path("M21.755 26.642v-.055c.055-.023.069-.047-.007-.055q-.048-.013-.097-.023c-.004-.04.008-.063.054-.036c.065 0 .136.003.202.008q.046.052.004.11c-.042.055-.101.049-.156.051");
}

.hpbfh1b9v {
  fill: var(--svg-color--3e3f3f, #3e3f3f);
  d: path("M15.347 33.452c-.027-.012-.054-.022-.082-.039c-.035-.146.039-.264.088-.391c.096.151-.06.293-.006.43m-.357-1.092c-.125-.162.054-.318.01-.477c.093.02.113.079.089.165c-.086.092-.039.218-.099.312");
}

.hr14y7bkz {
  fill: var(--svg-color--403911, #403911);
  d: path("M22.688 36.927q.128-.013.256-.021l.008.06c-.068.004-.141.004-.207.012a.2.2 0 0 0-.057-.051");
}

.hs0wmxwcc {
  fill: var(--svg-color--190505, #190505);
  d: path("M22.38 38.26c-.076-.04-.082-.185-.209-.12c-.016-.061.024-.125.068-.105a.22.22 0 0 1 .141.225");
}

.hso7a-b3h {
  fill: var(--svg-color--f0d329, #f0d329);
  d: path("M17.534 21.857a.3.3 0 0 0-.045.052c-.104.051-.203-.009-.303-.021a.12.12 0 0 1-.045-.062c.092-.043.113-.188.244-.178c.035.063.08.106.158.104q.022.028.045.051c.015.051.005.079-.054.054");
}

.htjuz5w_y {
  fill: var(--svg-color--584d11, #584d11);
  d: path("M22.791 36.76c.021.019.038.026.058.046c-.045.077-.131.063-.203.089a.2.2 0 0 1-.062.021c-.045-.017-.045-.06-.058-.094c.073-.096.176-.051.265-.062");
}

.hu8qbjo6i {
  fill: var(--svg-color--1e1f1f, #1e1f1f);
  d: path("M24.397 31.979c.014-.104.035-.209-.096-.257c.01-.042.043-.065.086-.069c.037.016.078.004.111.021c-.016.12-.031.237-.05.36c-.046.01-.07 0-.051-.055");
}

.huraqxb5c {
  fill: var(--svg-color--736c48, #736c48);
  d: path("M15.655 19.657c-.03 0-.053 0-.081-.004c-.06-.008-.083-.043-.079-.102l.075-.057q.042.087.085.163");
}

.hvc4zzb0v {
  fill: var(--svg-color--3b3b3b, #3b3b3b);
  d: path("m19.565 27.477l.054-.106c-.024-.059.006-.094.058-.117c.209.005.033.188.119.252c.057-.027.039-.131.137-.143q.02.135.043.271q-.022.026-.055.027c-.041 0-.08-.013-.121-.021c-.031-.005-.061-.017-.086-.022a.4.4 0 0 1-.097-.067a.3.3 0 0 1-.04-.047z");
}

.hvx9a8b7h {
  fill: var(--svg-color--2d2107, #2d2107);
  d: path("M22.688 37.37s.005-.02.005-.016c.079.039.146.109.248.091c.04.034.079.064.114.103q.029.02.017.031c-.009.013-.015.013-.021.013c-.148-.03-.288-.065-.363-.222");
}

.hw6z27btn {
  fill: var(--svg-color--5a5a57, #5a5a57);
  d: path("m13.162 32.88l-.056.064c-.057-.084-.041-.185-.043-.277c.125.029.094.13.099.213");
}

.hwmh6ubsn {
  fill: var(--svg-color--373737, #373737);
  d: path("M18.572 37.23h-.063c.008-.029.012-.07.017-.098c.034-.053.069-.061.106-.01c-.021.037-.041.082-.06.108");
}

.hx9oherjo {
  fill: var(--svg-color--2f1717, #2f1717);
  d: path("M16.706 32.1a.67.67 0 0 0 .42.008q.04 0 .061.036c-.158.075-.317.091-.477-.006c-.017-.003-.021-.015-.017-.022c.005-.006.009-.016.013-.016");
}

.hxnc_chfo {
  fill: var(--svg-color--414240, #414240);
  d: path("M20.457 29.936h-.327c-.025-.022-.061-.03-.058-.075a.1.1 0 0 1 .071-.06a.2.2 0 0 1 .063 0c.078.017.061-.083.112-.099c.091-.013.142.035.167.121a.14.14 0 0 1-.028.113");
}

.hxooqybfa {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M16.55 40.26c.104-.184.213-.364.317-.543a.43.43 0 0 1 .11-.213a1 1 0 0 0 .184-.155a.2.2 0 0 1 .133-.06q.113.004.122.119a.5.5 0 0 1-.083.198c-.033.071-.085.14-.102.218a.3.3 0 0 1-.065.112a.4.4 0 0 0-.116.191q-.058.124-.097.252a6 6 0 0 0-.076.229c-.021.057-.038.108-.061.16c-.024.123-.162.137-.214.234q-.072.026-.137.056c-.063.026-.123.151-.18 0a1 1 0 0 1 .107-.414c.051-.125.082-.265.158-.384");
}

.hxze3nbbr {
  fill: var(--svg-color--472624, #472624);
  d: path("M24.17 19.552c.054-.094.033-.186-.011-.271c.145.076.158.173.011.271");
}

.hykzxfxie {
  fill: var(--svg-color--171818, #171818);
  d: path("M24.87 29.993h.047c-.021.104.139.106.114.209c-.04.037-.076.066-.114.103a.1.1 0 0 1-.041.004c-.003-.107-.006-.207-.006-.316");
}

.hymz0obbf {
  fill: var(--svg-color--dabc25, #dabc25);
  d: path("M13.218 38.913c.021-.056.067-.051.112-.051c.075.051.106.12.063.209c-.086.094-.002.221-.06.315c-.04.026-.077.022-.114-.004l-.031-.052c-.065-.145-.091-.281.03-.417");
}

.hyq05qxoo {
  fill: var(--svg-color--353125, #353125);
  d: path("M18.218 19.395v-1.418c.017.004.031 0 .043-.004c.004.421.004.836.004 1.257c.004.058.028.124-.047.165");
}

.hysa7osnq {
  fill: var(--svg-color--6c5e14, #6c5e14);
  d: path("m18.16 19.87l.007-.283c.056.104.091.207-.01.311c.001-.011.001-.026.003-.028");
}

.hzlw5qckf {
  fill: var(--svg-color--635713, #635713);
  d: path("M20.19 22.16c-.273-.02-.551-.034-.83-.055c.08-.07.184-.016.266-.047c.207.016.418-.027.62.055c-.004.037-.038.031-.056.047");
}

.i-82zmbge {
  fill: var(--svg-color--70280f, #70280f);
  d: path("M21.02 20.07c-.057.096.013.189 0 .284c-.098-.094-.185-.188 0-.284");
}

.i-axlijat {
  fill: var(--svg-color--1c1111, #1c1111);
  d: path("M17.16 27.841c-.028.004-.056.004-.083.009c-.094-.043-.083-.099-.016-.161c.041.094.102.036.158.027q.021.017.017.035q0 .02-.009.021l-.002.024c-.019.015-.022.058-.065.045");
}

.i-b59gbeb {
  fill: var(--svg-color--5b3030, #5b3030);
  d: path("M23.884 25.526a.2.2 0 0 1 .004.051a.44.44 0 0 1-.217-.099c.084-.028.158-.026.213.048");
}

.i0kt-7brd {
  fill: var(--svg-color--5e1c0d, #5e1c0d);
  d: path("M22.294 22.02c.145.031.277-.013.415-.051c-.127.14-.257.202-.415.051");
}

.i0ts8nbxc {
  fill: var(--svg-color--670d09, #670d09);
  d: path("M20.706 39.4q.006-.058.01-.121c.059.088.096.174-.013.262l-.028-.053z");
}

.i1b2g0blv {
  fill: var(--svg-color--4d2221, #4d2221);
  d: path("M16.03 29.997c0 .942 0 1.879.002 2.822l-.042.012c-.069-.045-.038-.112-.042-.164c.014-.234-.023-.477.023-.713l-.008.009c-.012-.065-.09-.113-.092-.192a.4.4 0 0 1 .006-.138c.025-.384.113-.772.055-1.166q-.011-.023-.027-.048c.141-.141.035-.32.078-.481c.015.016.03.041.047.059");
}

.i23f5dblv {
  fill: var(--svg-color--776714, #776714);
  d: path("M14.681 36.632c.101.182.266.019.391.074l-.133.108a8 8 0 0 1-.317-.044c-.028-.042-.024-.076.005-.117q.025-.011.054-.021");
}

.i4n430t2t {
  fill: var(--svg-color--302f2c, #302f2c);
  d: path("M14.04 20.868c-.098-.142-.104.076-.174.051c.049-.146-.05-.225-.136-.313a.1.1 0 0 1 .084-.075c.144.067.313.116.226.337");
}

.i4xzbhntc {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M16.19 18.14q-.005-.02-.006-.043c.031-.003.064-.013.098-.017c.02.014.033.033.055.047q-.075.005-.147.013");
}

.i4za-o91x {
  fill: var(--svg-color--2c2e2e, #2c2e2e);
  d: path("M19.451 38.34c-.017-.023-.026-.045-.043-.061c-.049-.082-.047-.142.056-.173c.021.022.035.042.057.063q.033.033-.006.068c-.065.007-.041.066-.064.103");
}

.i5nfjrmsc {
  fill: var(--svg-color--696969, #696969);
  d: path("M13.229 28.903q-.028-.03-.053-.063c-.014-.061.021-.111.047-.162a.2.2 0 0 0 .049.005c.006.078.015.152-.043.22");
}

.i64fuqbsg {
  fill: var(--svg-color--484a4a, #484a4a);
  d: path("M17.16 28.2c-.014-.017-.025-.032-.042-.051a.08.08 0 0 1-.011-.063q.036-.143.085-.275a.08.08 0 0 1 .059-.043q.088.009.112.099c.002.119-.004.235-.078.34c-.039.025-.075.033-.113 0z");
}

.i66t_3b-f {
  fill: var(--svg-color--1d1e1e, #1d1e1e);
  d: path("M21.443 34.815c.116.008.245-.027.317.11c-.108-.024-.213-.05-.322-.062q-.001-.023.005-.048");
}

.i6y_lqb2q {
  fill: var(--svg-color--3e3e3e, #3e3e3e);
  d: path("M18.944 37.09c-.037.044-.059.092-.053.147c-.082-.057-.141-.154-.262-.115q-.054.007-.105.008a.6.6 0 0 0-.104-.047v-.051c.174 0 .352 0 .523.004z");
}

.i7fziq1gc {
  fill: var(--svg-color--3c3d3d, #3c3d3d);
  d: path("M24.1 28.353c.039.107.113.217.045.337c-.107-.008-.072-.073-.067-.133c-.032.043.009.162-.108.146c-.01-.012-.019-.016-.028-.023l.002-.469c.115-.028.07.13.156.142");
}

.i8ltmwbwh {
  fill: var(--svg-color--7e5012, #7e5012);
  d: path("M13.79 19.712c.018-.117.08-.196.201-.217c.037.115-.057.182-.1.271c-.054.03-.101.03-.101-.054");
}

.i98auobgl {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("m17.247 39.33l-.047.047a.7.7 0 0 1-.244.139c-.097.018-.189.018-.248-.081q.012-.03 0-.05a.7.7 0 0 1 .102-.28l.209-.381a.37.37 0 0 1 .121-.235l.086-.162c-.014-.104.062-.135.14-.148a.3.3 0 0 1 .21.063a.15.15 0 0 1 .037.06c.009.065.021.135.009.2c-.022.092-.053.178-.051.263a.2.2 0 0 1-.021.069c-.065.102-.078.218-.111.332c-.026.094-.106.133-.192.164");
}

.i9vitccfq {
  fill: var(--svg-color--2a2929, #2a2929);
  d: path("M12.851 30.782a.4.4 0 0 0 .066.004v.449a.6.6 0 0 1-.055.117z");
}

.ib4xelblk {
  fill: var(--svg-color--222525, #222525);
  d: path("M24.877 33.515c-.008.113.007.234-.085.386c-.043-.183.038-.308.036-.442c.045-.009.073-.007.049.056");
}

.ibzbnnchi {
  fill: var(--svg-color--515050, #515050);
  d: path("M15.08 18.723a.4.4 0 0 1 .021-.06l.302-.013c-.005.023-.007.056-.015.079a.12.12 0 0 1-.078.075a.25.25 0 0 1-.23-.081");
}

.ic8xg7a_p {
  fill: var(--svg-color--6a696a, #6a696a);
  d: path("M19.822 40.963h-.056c-.07-.071-.047-.142.012-.198c.069.05.051.125.044.198");
}

.icg-pbb4y {
  fill: var(--svg-color--552c0c, #552c0c);
  d: path("M14.942 26.15c.141-.119.271-.279.475-.099c-.205-.039-.326.122-.479.208q-.047-.058.004-.109");
}

.id291acph {
  fill: var(--svg-color--636365, #636365);
  d: path("m24.877 33.515l-.05-.059c-.005-.062-.021-.131.063-.17c.066.084.026.155-.013.229");
}

.ielbzqymv {
  fill: var(--svg-color--f6f7f7, #f6f7f7);
  d: path("M13.483 20.598q-.03.049-.059.103c-.066-.027-.133-.047-.201-.07c-.058-.109-.113-.213-.063-.342a.2.2 0 0 1 .018-.047c.065-.156.195-.125.316-.108a.2.2 0 0 1 .098.067a.6.6 0 0 1 .114.188a.1.1 0 0 1-.004.066c-.045.085-.134.109-.219.143");
}

.ierzj7b1h {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M13.229 36.706c-.041.072-.078.035-.117 0c-.057-.057-.016-.127-.021-.189c.016-.083.023-.159.043-.234c.06-.108.062-.229.064-.345c.061-.118.049-.262.123-.374q.001-.026.005-.049c-.021-.152.047-.289.047-.438c0-.109 0-.226.063-.322c.082-.129.014-.271.061-.405c.059-.104.023-.226.037-.334c.039-.142.02-.285.023-.433c-.015-.115.035-.23.022-.348c.028-.101.03-.201.037-.31c.046-.188-.013-.39.042-.581c.008-.178 0-.357.004-.539c-.009-.068-.016-.141.086-.159c.042.009.064.036.075.074c.021.058.037.125.12.058c.033-.025.057-.064.086-.096c.045-.046.081-.115.154-.05c.052.092.033.183.023.272q-.004.045-.006.094c-.07.07-.041.164-.048.244c-.021.172-.021.347-.067.514c-.018.16 0 .332-.089.48c-.002.098.009.188-.053.27v.1c-.015.182-.089.358-.048.543q0 .074-.002.146c-.135.117-.063.312-.158.443v.088c-.077.062-.03.177-.098.248c-.002.019-.004.033-.004.058c-.014.065-.033.124-.047.192c-.041.109-.035.234-.107.334l-.002.053c-.062.09-.033.217-.098.307l-.007.063c.005.07-.034.134-.026.207a.3.3 0 0 1-.066.16a8 8 0 0 1-.051.258");
}

.ifhvovb6w {
  fill: var(--svg-color--420807, #420807);
  d: path("m13.483 36.603l-.01-.07c.012-.062-.021-.145.057-.185c.003.086.04.18-.047.255");
}

.ighpykbpp {
  fill: var(--svg-color--300c07, #300c07);
  d: path("M17.1 36.549c.146-.005.229.108.338.181v.026a.5.5 0 0 1-.338-.207");
}

.iigoktb4t {
  fill: var(--svg-color--4a292a, #4a292a);
  d: path("M16.818 34.407c-.054.035-.106.066-.16.104c-.028-.021-.028-.048-.008-.074c.022-.048.062-.063.11-.07a.06.06 0 0 1 .058.04");
}

.ik40mcbpc {
  fill: var(--svg-color--4c4d4d, #4c4d4d);
  d: path("M18.09 28.679h.075l.097.371h-.051c-.074-.112-.083-.248-.121-.371");
}

.ikm1buewq {
  fill: var(--svg-color--4b4310, #4b4310);
  d: path("m14.878 22.592l.014-.054c.088.039.168-.008.252-.032q.048.037.002.075q-.077.037-.151.082z");
}

.ilqj3c-gh {
  fill: var(--svg-color--401309, #401309);
  d: path("M22.427 39.81c-.104-.148.045-.273.024-.422c.065 0 .074.048.082.104q-.055.158-.106.318");
}

.ilsp4419l {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M19.464 27.327q.079-.065.156-.125l.057.051q-.03.063-.059.117c-.055 0-.115.008-.154-.043");
}

.imxan-bvn {
  fill: var(--svg-color--2a1111, #2a1111);
  d: path("M17.226 35.827c.021.015.041.033.063.045c-.089.063-.19.053-.292.057c.006-.021.018-.037.025-.048c.069-.021.136-.036.204-.054");
}

.imypjly_k {
  fill: var(--svg-color--232424, #232424);
  d: path("M12.541 30.05h-.045c.004-.094-.022-.188.067-.274c.048.104-.019.188-.022.274");
}

.ineo7w95a {
  fill: var(--svg-color--552927, #552927);
  d: path("M14.687 18.436c-.148-.073-.252-.021-.328.119c-.025.021-.045.008-.059-.013c.097-.156.191-.322.387-.106");
}

.io4a3ubka {
  fill: var(--svg-color--2b2b2b, #2b2b2b);
  d: path("M19.409 26.428q-.023-.054-.053-.114c.104.043.138-.098.244-.086a.3.3 0 0 1-.191.2");
}

.io9t7b9gh {
  fill: var(--svg-color--1e1e1e, #1e1e1e);
  d: path("M13.07 36.497h.04c-.002.07-.002.143-.002.209c-.03.02-.062.035-.091.054c-.017-.095.03-.177.053-.263");
}

.ioogmcb3u {
  fill: var(--svg-color--090805, #090805);
  d: path("m16.765 17.976l.052-.066c.067.008.132.008.198.013q-.004.022-.002.047c-.08.085-.166.085-.248.006");
}

.ioy07hbxy {
  fill: var(--svg-color--515050, #515050);
  d: path("M22.01 19.18a.4.4 0 0 0 .006-.07c.094.059.226-.027.312.074c-.103.02-.206.047-.31.071c-.025-.019-.025-.048-.008-.075");
}

.ipz_uobrk {
  fill: var(--svg-color--4a200d, #4a200d);
  d: path("M15.714 23.532c.096-.076.209-.039.313-.039c-.094.086-.208.035-.313.039");
}

.ir_b1p5ct {
  fill: var(--svg-color--e2e3e4, #e2e3e4);
  d: path("m20.261 27.841l.049.209c-.156.055-.106-.079-.131-.146c-.008-.051-.039-.117.061-.113c.006.02.011.034.021.05");
}

.ir3mmsb-p {
  fill: var(--svg-color--340e0d, #340e0d);
  d: path("M17.02 38.13c-.043.136.156.086.15.191c-.189.016-.244-.08-.189-.256c.042.006.065.016.039.065");
}

.irya3lbgg {
  fill: var(--svg-color--776614, #776614);
  d: path("M15.897 20.444q.044-.066.08-.144q.03.012.057.028c.023.021.046.039.055.066c-.009.014-.013.023-.013.036c-.059.005-.112.092-.179.014");
}

.is2ocpb2a {
  fill: var(--svg-color--282827, #282827);
  d: path("M13.839 30.463c.018-.07-.056-.099-.07-.154l.174-.267q.025-.037.045.004l.013.314c-.034.039-.049.098-.104.116a.06.06 0 0 1-.058-.013");
}

.itco-cblb {
  fill: var(--svg-color--ceb020, #ceb020);
  d: path("m15.896 20.452l-.031-.313c.152-.015.143.094.146.196c-.022.052-.043.105-.113.111z");
}

.ivl8-ubzw {
  fill: var(--svg-color--383838, #383838);
  d: path("M13.11 29.846c-.034 0-.066-.008-.1-.008q.035-.296.065-.577c.043-.012.065.011.081.047l.002.425c-.028.032-.005.086-.048.113");
}

.iwy-skbrf {
  fill: var(--svg-color--2a2608, #2a2608);
  d: path("M13.366 39.07c.02.004.035.004.055.004a3 3 0 0 1-.043.203q-.023.057-.049.109c.012-.105-.038-.218.037-.316");
}

.ix3b7gbja {
  fill: var(--svg-color--332525, #332525);
  d: path("M25.1 28.628c.019-.148-.131-.209-.178-.321c.219.125.15-.056.162-.158c.125.126.025.279.057.417c.018.042.004.058-.041.062");
}

.ixhckp8cv {
  fill: var(--svg-color--272727, #272727);
  d: path("M14.425 32.934h.057c-.004.074.004.149-.051.211l-.072.068q-.029-.039-.051-.072c-.068-.121.11-.121.104-.215z");
}

.ixq6gd6ip {
  fill: var(--svg-color--392a2a, #392a2a);
  d: path("M20.15 34.458c-.122.035-.245.066-.366.104c.062-.148.194-.117.313-.143q.038.007.053.039");
}

.ixtnchbqa {
  fill: var(--svg-color--e2c020, #e2c020);
  d: path("m15 19.639l.032.022c.063.031.113.063.064.149c-.054.028-.1.032-.11-.047c.014-.038-.076-.089.014-.124");
}

.ixzoc_x3h {
  fill: var(--svg-color--eb1e18, #eb1e18);
  d: path("M21.808 21.614c.049-.016.101-.022.151-.035c.035.133-.094.153-.159.221c-.106.083-.218.016-.328.012l-.082-.094c.025-.074.029-.184.156-.09c.092.074.18.074.262-.014");
}

.iyjxiyebm {
  fill: var(--svg-color--52503d, #52503d);
  d: path("M14.47 18.923c-.043.091-.121.109-.207.105c-.01-.012-.014-.027-.021-.043q.058-.06.116-.117c.045.004.087.012.112.055");
}

.izvyfibrn {
  fill: var(--svg-color--504610, #504610);
  d: path("M15.704 22.12c.014.172-.119.09-.191.117l-.024-.027c-.024-.051-.021-.094.022-.133c.051.004.103.004.154.008q.031.004.039.035");
}

.izxaivbko {
  fill: var(--svg-color--2e1111, #2e1111);
  d: path("M12.503 36.851c-.006.021-.01.053-.017.08c-.073-.08-.052-.18-.054-.271l.012-.004q.023-.034.04.004q.012.093.019.191");
}

.j_o7kcz6x {
  fill: var(--svg-color--393a3b, #393a3b);
  d: path("M17.747 38.37c-.041.057-.08.109-.117.166c-.048.006-.07-.004-.043-.057c.035-.052-.105-.109.004-.165c.051.037.103.037.157.013q.02.02.013.027q-.008.014-.014.016");
}

.j0up9-43d {
  fill: var(--svg-color--241715, #241715);
  d: path("M16.65 17.771c.016-.082-.035-.146-.067-.215q.063-.013.121-.021c-.006.083.025.171-.054.236");
}

.j1bfg_3zm {
  fill: var(--svg-color--202121, #202121);
  d: path("M19.88 28.1c.018-.055-.01-.133.074-.16h-.003l.132.213a2 2 0 0 0-.199-.021a.1.1 0 0 1-.004-.032");
}

.j1vh83qoa {
  fill: var(--svg-color--252626, #252626);
  d: path("M24.411 35.708c-.016.031-.031.065-.053.104v-.259q.014.02.033.004c.006.053.011.1.02.151");
}

.j1zqdlwqn {
  fill: var(--svg-color--fef42f, #fef42f);
  d: path("M22.22 36.618c0 .015 0 .022-.002.037c-.018-.021-.035-.033-.052-.049c.011-.004.019-.012.032-.016c.006.013.016.02.022.028m-6.864-.113c-.014.018-.031.027-.045.039l-.006-.006c-.008-.006-.012-.019-.01-.029q.004-.019.01-.02a.033.033 0 0 1 .047 0z");
}

.j2p-cxb4e {
  fill: var(--svg-color--efeee7, #efeee7);
  d: path("M15.296 18.17c.008-.294.2-.318.42-.302h-.002c.059.094.123.185.098.307a.28.28 0 0 1-.125.154a.4.4 0 0 1-.188.02a.3.3 0 0 1-.187-.109a.2.2 0 0 1-.016-.07");
}

.j2ykpdbai {
  fill: var(--svg-color--e2e2e3, #e2e2e3);
  d: path("M18.08 28.679c-.035-.051-.076-.105-.113-.156q-.034-.156-.072-.313c0-.104.043-.108.115-.053q.033.08.066.148c.121.085.033.229.09.33v.042c-.023.032-.051.032-.074 0z");
}

.j3auxxbuf {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.255 23.993v11.781a7.73 7.73 0 0 0 2.189 5.407c1.352 1.388 3.217 2.246 5.271 2.246h.002c2.051 0 3.916-.858 5.268-2.246s2.189-3.304 2.189-5.407V23.993c-4.969 0-9.945.002-14.919 0");
}

.j3dfw60la {
  fill: var(--svg-color--202121, #202121);
  d: path("M24.365 28c-.021.022-.042.051-.062.078q-.032-.04-.004-.09l-.012-.41q.046-.029.081.01c.016.133.02.275-.003.412");
}

.j4mb4eb7x {
  fill: var(--svg-color--3a372b, #3a372b);
  d: path("M14.375 18.816h.043c.083-.05.177.106.255-.016a.1.1 0 0 1 .027.071c-.033.105-.116.103-.2.099a.3.3 0 0 1-.141-.083q-.016-.04.016-.071");
}

.j4z65kfgm {
  fill: var(--svg-color--edcc27, #edcc27);
  d: path("M18.843 17.237c.02-.117-.025-.24.037-.354c.018.011.041.027.065.039c-.097.095-.035.217-.056.326q-.034.03-.046-.011");
}

.j50xc_bko {
  fill: var(--svg-color--3e3636, #3e3636);
  d: path("M24.667 37.02c.045.039.064.145.156.055q.023-.025.048.004l-.052.108c-.094.021-.165 0-.184-.112c.001-.024.009-.042.032-.055");
}

.j5lma7bcc {
  fill: var(--svg-color--c1c1c1, #c1c1c1);
  d: path("M19.761 17.922c.018.042.01.099.072.118c.028.035.023.07 0 .108c-.033.032-.072.032-.109.036c-.056.004-.105.004-.16.004a.26.26 0 0 1-.192-.027a.08.08 0 0 1-.026-.07c.033-.055.082-.067.141-.063c.102.004.177-.08.274-.106");
}

.j69z_obhq {
  fill: var(--svg-color--0a0b0b, #0a0b0b);
  d: path("m17.226 27.771l-.01-.055q.032-.148.066-.294c.018-.024.027-.024.04 0c.008.098.011.196.019.294c.01.043.063.063.055.117c-.016.016-.032.024-.055.016a1 1 0 0 1-.115-.078");
}

.j6x5lcj2x {
  fill: var(--svg-color--5f5912, #5f5912);
  d: path("M14.15 37.967c.056 0 .105 0 .162-.004c.033-.027.068-.027.104-.009c.019.026.015.053-.008.067c-.096.05-.195.083-.258-.054");
}

.j72tpippq {
  fill: var(--svg-color--252727, #252727);
  d: path("M19.525 27.743c.021-.004.034-.004.051-.008c-.017.141-.041.279 0 .416a.1.1 0 0 1 .004.106a.06.06 0 0 1-.065.012c-.061-.04-.02-.114-.051-.165c-.005-.023-.014-.051-.021-.074q.045-.146.082-.287");
}

.j8jo8sb-f {
  fill: var(--svg-color--191707, #191707);
  d: path("m18.368 21.13l.053-.056c.07.139.064.256-.104.313l.008.004c.012-.084.028-.174.043-.261");
}

.j8tlb46mb {
  fill: var(--svg-color--171919, #171919);
  d: path("M19.837 27.581c-.023.104-.052.205-.076.308q-.025.032-.047 0q.003-.155.01-.312q.055-.001.113.004");
}

.j9t8q92tw {
  fill: var(--svg-color--462c2b, #462c2b);
  d: path("M16.765 29.11c.011.059.06.043.099.055c.054.052.021.1-.003.149c-.014.017-.029.036-.049.04a.2.2 0 0 1-.078.018c.006-.088-.098-.186.031-.262");
}

.ja7t9li1t {
  fill: var(--svg-color--351309, #351309);
  d: path("M14.321 39.696c.083-.057 0-.184.095-.23c0 .064.009.132.002.195c-.002.047.033.117-.032.135c-.064.017-.104-.045-.135-.092c.02-.03.043-.03.07-.008");
}

.jb8rqbcgy {
  fill: var(--svg-color--534648, #534648);
  d: path("M22.466 34.13a.2.2 0 0 1 .016-.045c.129.021.088-.11.148-.158c.029.142.016.242-.164.203");
}

.jc71tbc_a {
  fill: var(--svg-color--361918, #361918);
  d: path("M22.02 18.23c.063-.073.054-.169.059-.259c.061.105.076.24.234.25c.052.005.074.063.059.126c-.09-.122-.227-.1-.352-.117");
}

.jcv1aqbys {
  fill: var(--svg-color--fee62c, #fee62c);
  d: path("M21.974 40.01c-.015-.038.008-.046.033-.063q.237.005.478.018l-.007.05a1.06 1.06 0 0 1-.504-.005");
}

.jdd996bbi {
  fill: var(--svg-color--6b6b6b, #6b6b6b);
  d: path("M13.58 33.563q-.018.005-.037.004q-.005-.14-.006-.274l.088-.051c.039.118-.055.208-.045.321");
}

.jdienobkm {
  fill: var(--svg-color--f8d328, #f8d328);
  d: path("M16.867 20.966a.1.1 0 0 0 .004.048c.076.085.05.185.04.278c0 .013 0 .022-.008.041c-.068.051-.123.132-.227.137c-.104.004-.211.012-.287-.09c-.019-.016-.039-.035-.058-.047c-.006-.043.011-.084.011-.127c.004-.047.043-.07.06-.109c-.033.021-.062.055-.109.036q-.045-.027-.086-.056c-.067-.022-.071-.078-.08-.133a.2.2 0 0 1 .028-.117a.22.22 0 0 1 .109-.11c.049-.017.097-.037.149-.037c.088 0 .183-.013.248.071q.013.014.026.008c.094.038.178.09.18.207");
}

.jffsqkpqy {
  fill: var(--svg-color--202020, #202020);
  d: path("m14.726 31.903l.004.016c-.032.014-.067.018-.1.029c-.004-.078-.017-.154.036-.222c.073.041.101.097.06.177");
}

.jg7ivhguy {
  fill: var(--svg-color--2b1918, #2b1918);
  d: path("M14.775 33.872c.041.084.005.226.163.226c-.181.038-.22-.019-.163-.226");
}

.jgvtx-btl {
  fill: var(--svg-color--484848, #484848);
  d: path("M22.791 31.15c-.022.111.009.217.038.324a.08.08 0 0 1-.045.054a.66.66 0 0 1-.085-.376q.046-.003.092-.002");
}

.jhh8y4nnm {
  fill: var(--svg-color--edd028, #edd028);
  d: path("M24.21 39.31c-.019.057-.052.102-.106.12c-.06-.021-.082-.052-.065-.108c.063-.099.036-.191-.021-.274q-.033-.084.031-.142l-.004.004c.063-.103.125-.053.189 0c.052.139.096.273-.024.4");
}

.jhku1t4yq {
  fill: var(--svg-color--351c1c, #351c1c);
  d: path("M18.979 41.952c-.016-.021-.03-.035-.043-.052c.009-.06.009-.116.051-.157q.038-.033.068.013z");
}

.ji__igbjo {
  fill: var(--svg-color--363636, #363636);
  d: path("M17.646 28.682h-.047c-.023-.114.084-.069.125-.11l-.004.004c.043.041.086.067.129.104c.021-.023.035-.023.051 0v.105c-.129.079-.184-.032-.254-.103");
}

.jipjkulas {
  fill: var(--svg-color--d4d4d5, #d4d4d5);
  d: path("M21.18 25.886c-.104.033-.149-.021-.181-.1c-.017-.035.019-.047.038-.047c.091 0 .11.075.143.147");
}

.jksavccph {
  fill: var(--svg-color--252420, #252420);
  d: path("M22.06 36.29c-.032.024-.063.043-.1.066l-.048-.066c.091-.115-.026-.26.044-.383c.094.077.016.213.105.291c.028.029.032.064-.001.092");
}

.jky4oybmq {
  fill: var(--svg-color--521b19, #521b19);
  d: path("M20.866 40.22h-.043a.44.44 0 0 1-.115-.235c.11.036.137.136.158.235");
}

.jl_f_sb8d {
  fill: var(--svg-color--2d2e2e, #2d2e2e);
  d: path("M13.08 31.723c-.165.149-.008.317-.026.476q-.023.038-.047 0c-.113-.16-.086-.351-.094-.524c.037-.026.083.028.118-.017c.032.011.054.03.049.065");
}

.jlmccccbi {
  fill: var(--svg-color--6a2111, #6a2111);
  d: path("M18.995 20.624q-.078-.016-.057-.101c.158.052.352-.169.479.068a.44.44 0 0 0-.422.033");
}

.jmde5n95f {
  fill: var(--svg-color--3d3f3d, #3d3f3d);
  d: path("M13.952 19.16c.02.022.035.043.053.07c-.037.041-.072.075-.111.114c-.043-.017-.045-.052-.053-.09q.057-.05.111-.094");
}

.jmig4gbla {
  fill: var(--svg-color--4d4343, #4d4343);
  d: path("M21.329 35.08q.001.133.008.271q-.047.005-.101.004c-.024-.113-.02-.211.093-.275");
}

.jnwfsrese {
  fill: var(--svg-color--461a0a, #461a0a);
  d: path("m16.654 26.749l.004.052q-.202.07-.401.146c.08-.182.258-.15.397-.198");
}

.jo158hw6l {
  fill: var(--svg-color--393938, #393938);
  d: path("M15.185 30.3c.091-.086.06-.206.074-.308q.042.021.082.047c-.023.108-.014.23-.084.33a.14.14 0 0 1-.072-.069");
}

.jo4bhd9fx {
  fill: var(--svg-color--e6e6e6, #e6e6e6);
  d: path("M18.476 29.26c-.15.006-.15-.139-.213-.211c-.086-.105-.082-.248-.129-.371a.2.2 0 0 1-.01-.082c.023-.027.016-.125.092-.043a.4.4 0 0 0 .07.027c.012.037.027.066.042.103c.08.046.065.142.093.216l.002.098c.078.073.066.167.053.263");
}

.jo4ofsbhu {
  fill: var(--svg-color--eee, #eee);
  d: path("M17.226 35.08a.1.1 0 0 1 0-.034c-.002-.117.006-.241-.014-.362c.098-.096.176-.042.25.036c.1.229.03.469.049.694a.3.3 0 0 1-.074.199c-.065.022-.127.053-.199.018c-.076-.115.035-.247-.033-.362c-.024-.066-.036-.134.021-.189");
}

.jod1crbrd {
  fill: var(--svg-color--e1e1e1, #e1e1e1);
  d: path("M18.12 29.32c-.023-.005-.055-.009-.083-.017c-.021-.065-.067-.114-.094-.181c-.04-.088-.054-.178-.082-.268l-.013-.066a.2.2 0 0 1 .019-.099c.06-.149.149-.012.229-.026c.02.012.035.022.051.047c.059.104.07.231.105.345c.024.099.008.178-.066.249q-.025.029-.066.016");
}

.jozzu8yfg {
  fill: var(--svg-color--551f1e, #551f1e);
  d: path("M16.81 39.1c.012.111-.045.196-.102.282c-.048-.124.001-.21.102-.282");
}

.jp8wy4zgn {
  fill: var(--svg-color--fcfcfd, #fcfcfd);
  d: path("M21.914 19.18c-.007.012-.012.032-.017.051c-.014-.039-.033-.07-.047-.105a.55.55 0 0 1-.008-.297a1 1 0 0 0 .06-.067c.006.14.009.275.012.418");
}

.jpmgaxb_p {
  fill: var(--svg-color--525151, #525151);
  d: path("M23.782 35.12c.074.092.061.213.1.318c-.158-.068-.154-.187-.1-.318");
}

.jpt0fdvxn {
  fill: var(--svg-color--8a7717, #8a7717);
  d: path("M16.606 23.13q.032.031.063.056c-.082.043-.16.087-.232-.013q.087-.019.169-.043");
}

.jpv-m8dlb {
  fill: var(--svg-color--561e10, #561e10);
  d: path("m16.392 20.702l.002-.041c.101 0 .218-.061.27.09c-.092-.018-.18-.032-.272-.049");
}

.jq_lweb4n {
  fill: var(--svg-color--555, #555);
  d: path("M25.03 31.907a.1.1 0 0 1-.016-.037c0-.004.008-.008.016-.013c-.051-.131.004-.267-.04-.394l-.022-.295c-.016-.051 0-.079.059-.075c.07.33.074.668.063 1c-.005.068.034.154-.056.207a.7.7 0 0 1-.004-.396");
}

.jqxoguzft {
  fill: var(--svg-color--c1a922, #c1a922);
  d: path("M22.01 20.55c.019.039.037.087.058.133c.075.083.073.09-.062.161l-.055.036c-.087.012-.162.004-.208-.088l.062-.035c.025-.032.043-.066.063-.098c.033-.041.047-.097.089-.127q.026-.01.053.018");
}

.jrdgkeuae {
  fill: var(--svg-color--2d2d2d, #2d2d2d);
  d: path("M13.382 36.01c.016-.104-.051-.237.098-.306c.021.121.042.244-.098.306");
}

.jrf8t1s7v {
  fill: var(--svg-color--47270d, #47270d);
  d: path("M23.604 21.383c.16-.099.33-.035.492-.039c-.129.104-.281.019-.42.046q-.04.03-.072-.007");
}

.jrjsjg7js {
  fill: var(--svg-color--371d08, #371d08);
  d: path("M20.761 26.749c.131.043.295.014.369.179l-.369-.13c-.016-.008-.021-.021-.016-.027q.009-.02.016-.022");
}

.jrr200bwf {
  fill: var(--svg-color--6f6114, #6f6114);
  d: path("M17.07 23.11c-.117.118-.271.051-.407.074c-.053.021-.068-.003-.061-.055c.159.006.31-.089.468-.019");
}

.jscho2b2p {
  fill: var(--svg-color--481007, #481007);
  d: path("M15.31 40.18q.072-.032.144-.058c.034.11.173.01.216.104c-.111.084-.24-.008-.355.038z");
}

.jtinubb6t {
  fill: var(--svg-color--424343, #424343);
  d: path("M19.09 30a4 4 0 0 0-.772-.004l-.006-.112c.006-.009.013-.021.021-.027a.26.26 0 0 1 .158-.071c.094-.022.165.071.257.052c.06-.032.087-.095.142-.122c.076-.004.123.047.179.078c.028.027.049.052.043.091c-.009.039-.014.074-.022.115");
}

.jtze48b_r {
  fill: var(--svg-color--2c2d2d, #2c2d2d);
  d: path("M14.784 33.03c.029-.117.063-.244.098-.365c.016-.024.031-.02.047 0c-.067.113-.008.26-.09.369q-.031.028-.055-.004");
}

.jul151_sx {
  fill: var(--svg-color--524948, #524948);
  d: path("M22.698 33.29c.047.144.093.295.141.438a.3.3 0 0 0-.197.015c0-.136.004-.264.008-.395c.011-.021.013-.058.048-.058");
}

.jul55vbzo {
  fill: var(--svg-color--747473, #747473);
  d: path("M14.623 30.624c.099.016.167-.041.224-.118c.049.043.035.099.033.149c-.047.063-.031.168-.134.191c-.058-.02-.032-.086-.063-.117c-.021-.021-.047-.035-.068-.052z");
}

.julxds68l {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M24.819 37.18c-.036.026-.066.056-.1.089c-.041.08-.127.078-.192.104c-.101.037-.224 0-.298.101a.4.4 0 0 1-.188.121c-.179.042-.341-.021-.507-.062a.24.24 0 0 1-.127-.063c-.017-.018-.028-.036-.042-.052a1 1 0 0 0-.123-.153c-.021-.018-.042-.044-.063-.066a1 1 0 0 0-.101-.121a.3.3 0 0 1-.03-.057a.45.45 0 0 0-.129-.18c-.047-.043-.093-.094-.144-.127q-.03-.023-.052-.044a.4.4 0 0 1-.033-.06a.3.3 0 0 0-.063-.109c-.059-.071-.129-.129-.188-.195a.3.3 0 0 1-.061-.102c-.022-.077-.025-.15-.033-.23c-.004-.098-.047-.215.095-.261c.103-.029.19-.062.095-.194c-.047-.06-.097-.117-.097-.199c.008-.113.094-.134.179-.146a.33.33 0 0 0 .182-.085c.057-.07-.01-.07-.052-.091c-.269-.104-.452-.329-.7-.467c-.072-.071-.168-.067-.258-.076a.3.3 0 0 1-.109-.029c-.023-.018-.047-.027-.066-.046c-.132-.045-.186-.138-.18-.276c.007-.146.02-.307-.053-.453c-.011-.203-.065-.41.043-.606c.043-.031.076-.023.114.004c.075.078.054.188.116.271q.016.033.021.065c.01.101.043.181.107.252c.041.048.078.104.154.074c.076-.052.052-.142.095-.205a.13.13 0 0 1 .086-.062c.07-.005.11.037.14.102c.021.072.033.152.088.221a.5.5 0 0 1 .037.098c.02.071.029.146.115.182c.094-.02.055-.102.065-.155a.3.3 0 0 1 .056-.187c.059-.045.125-.045.189-.022c.025.013.043.022.061.048c.04.072.036.161.094.229l.029.062c.014.075.025.147.076.218q.016.029.021.063a.7.7 0 0 0 .053.259c.043.129.148.048.224.067c.036.016.06.037.071.076a.65.65 0 0 0 .099.362a.14.14 0 0 1 .022.065a.4.4 0 0 0 .082.257c.017.024.021.062.021.099c-.004.082.027.156.058.235q.044.14.098.285c.02.071.058.12.095.179c.017.03.021.064.021.102c-.014.097-.012.188.052.278c.043.067.128.071.185.119c.053.06.129.068.192.106c.052.041.085.097.153.111a.3.3 0 0 1 .154.114c.03.073.111.097.151.163m-12.118.09a1 1 0 0 0-.104-.089c.043-.046.092-.09.127-.142c.045-.069.123-.092.189-.133c.018-.018.035-.028.051-.041c.077-.086.194-.108.281-.184c.059-.052.146-.052.193-.127c.043-.07.027-.146.037-.229a.3.3 0 0 1 .025-.104c.059-.084.073-.188.094-.293a.5.5 0 0 1 .043-.101c.043-.086.078-.166.105-.26c.034-.104.048-.217.094-.317c.047-.099.063-.214.088-.313c.01-.102.008-.204.084-.28c.067-.062.146-.006.217-.027c.047-.044.057-.107.07-.167q.023-.111.071-.222c.03-.062.043-.125.06-.186c.006-.025.016-.047.022-.064c.058-.073.06-.17.071-.256a.2.2 0 0 1 .052-.099c.132-.04.185.056.231.151a.2.2 0 0 1 .012.07c.004.063-.031.149.084.157c.051-.03.076-.086.111-.124a.6.6 0 0 0 .125-.221c.023-.067.043-.137.103-.184c.042-.012.069.004.094.031c.062.053.056.166.152.197c.09-.018.134-.086.174-.157c.038-.063.038-.14.054-.213c.02-.083.049-.165.129-.209c.19-.021.148.13.149.228c.005.293-.019.58-.022.873a.2.2 0 0 1-.043.075c-.103.087-.229.087-.35.101c-.091 0-.154.058-.221.109c-.202.094-.34.299-.553.389c-.06.061-.221 0-.192.166c.026.029.065.05.106.065c.098.035.219.017.282.125c.021.121-.067.177-.138.243c-.037.049-.131.061-.088.154c.048.021.098.003.146.015c.083.024.157.06.154.165c-.032.135-.122.259-.108.409a.2.2 0 0 1-.041.13q-.03.039-.063.075l-.068.058a.4.4 0 0 0-.07.098a.2.2 0 0 1-.035.049c-.016.018-.03.027-.049.043a.5.5 0 0 0-.113.117c-.02.033-.047.067-.072.101q-.033.056-.066.108c-.027.027-.061.051-.093.078a.3.3 0 0 0-.085.088c-.01.02-.023.033-.035.056c-.033.038-.062.09-.095.132a.34.34 0 0 1-.149.111c-.172.066-.348.133-.541.095a.5.5 0 0 1-.199-.121c-.073-.104-.199-.067-.299-.104c-.064-.016-.152-.014-.188-.095");
}

.juntz093y {
  fill: var(--svg-color--2d2809, #2d2809);
  d: path("M13.492 38.25c.015-.009.032-.013.051-.021c.099.201-.175.291-.149.479c.006.037-.078-.021-.1-.075c-.085-.208.178-.234.198-.383");
}

.jv5fywb0g {
  fill: var(--svg-color--ededed, #ededed);
  d: path("M16.228 25.886c.055-.061.058-.146.145-.146c.021 0 .051.012.041.047c-.026.075-.071.122-.186.099");
}

.jw1fmi36a {
  fill: var(--svg-color--262727, #262727);
  d: path("M16.907 29.36q-.049-.032-.096-.057c.018-.047.033-.098.052-.143q.098-.069.198-.142q.033.03.041.065c-.004.093-.047.15-.137.168z");
}

.jw31q-gpt {
  fill: var(--svg-color--cecfcf, #cecfcf);
  d: path("M13.08 27.577c-.021.158-.045.314-.011.473c-.139-.092.02-.283-.131-.366c.006-.017.015-.024.021-.036c.067.021.023-.153.121-.071");
}

.jxbrqh6vi {
  fill: var(--svg-color--422524, #422524);
  d: path("M20.261 27.841c.027 0 .057.004.082.004l-.004.209l-.031-.004c-.07-.059-.098-.125-.047-.209");
}

.k_wg8zb-r {
  fill: var(--svg-color--302f2f, #302f2f);
  d: path("M22.998 29.323c.021.027.036.063.058.094q-.031-.001-.062.005c-.013.082.039.167-.024.247c-.016.021-.037.021-.062.009c-.021-.056-.062-.067-.114-.056c.081-.092.036-.271.204-.299");
}

.k_wpgbbhe {
  fill: var(--svg-color--363636, #363636);
  d: path("M12.957 27.65c-.11-.264.202-.339.222-.543a.85.85 0 0 1-.062.472a.13.13 0 0 1-.05.037c-.035.006-.066.045-.11.034");
}

.k-_cwfbkv {
  fill: var(--svg-color--706420, #706420);
  d: path("M18.944 19.357c-.066-.085.013-.188-.025-.274c.123.08.094.183.025.274");
}

.k0nkxo8aj {
  fill: var(--svg-color--52491b, #52491b);
  d: path("M18.517 19.08c-.03.088-.047.188.004.277c-.165-.088-.153-.185-.004-.277");
}

.k0y95ibuu {
  fill: var(--svg-color--494949, #494949);
  d: path("M22.11 30.942c-.063.113-.133.123-.21.016l.007-.084c.055.064.133.053.203.068");
}

.k14ni-6qh {
  fill: var(--svg-color--c4a321, #c4a321);
  d: path("m15.308 40.442l.004-.182c.109-.109.236-.023.356-.038h-.003c.045.062.026.12 0 .185c-.056.066-.119.094-.201.07c-.047-.045-.111.004-.156-.035");
}

.k17qflw7v {
  fill: var(--svg-color--ebebe8, #ebebe8);
  d: path("M13.739 21.13a.2.2 0 0 0-.048-.009c-.082-.063-.236.031-.259-.133l-.008-.011a.19.19 0 0 1-.004-.229a.1.1 0 0 0 .004-.051c-.013-.062.02-.104.069-.134a.3.3 0 0 1 .24 0a.37.37 0 0 1 .2.332c-.018.089-.043.181-.123.24q-.031.016-.071-.005");
}

.k1ultnb3u {
  fill: var(--svg-color--534a10, #534a10);
  d: path("M18.843 19.929c.01 0 .022-.005.033-.005c.059.017.069.063.069.114v.066c-.015.036-.052.071-.075.036c-.044-.063-.078-.137-.027-.211");
}

.k23chtw5u {
  fill: var(--svg-color--2a2b2b, #2a2b2b);
  d: path("M24.21 29.993c.074-.277.037-.562.048-.84h.029c.021.105.041.213.063.314c-.03.047-.021.094-.021.141c0 .021-.004.043.006.063q-.007-.042.028-.063c.016.075.028.146.042.225c-.129-.031-.085.121-.157.158c-.012.027-.021.027-.038.002");
}

.k2j4p25lo {
  fill: var(--svg-color--68696a, #68696a);
  d: path("M23.532 34.34q.023-.024.045-.053c.063.063.061.144.043.222l-.025-.004h-.025c-.035-.052-.059-.103-.038-.165");
}

.k3fnyiz7f {
  fill: var(--svg-color--62140b, #62140b);
  d: path("M16.231 20.589c.003-.047.015-.094.062-.122c.017.073-.038.187.103.192c.018.012.021.02.018.031q-.011.012-.02.012c-.033.013-.067.022-.101.035c-.09-.018-.088-.076-.062-.148");
}

.k3ljqnnlo {
  fill: var(--svg-color--5d3c0f, #5d3c0f);
  d: path("M19.933 21.13v-.039c.117-.051.244-.066.367-.077q.027.032-.006.062c-.013.026-.027.059-.044.086q.032.052-.013.084c-.064-.094-.167-.043-.25-.065c-.049.017-.072.002-.054-.051");
}

.k3wg5wagr {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M19.1 40.18c-.022-.052-.037-.108-.059-.161a.5.5 0 0 1-.133-.154c-.02-.029-.027-.061-.04-.097a2 2 0 0 0-.079-.226q-.017-.033-.021-.065c-.041-.112-.051-.242-.08-.356c-.04-.153.095-.244.13-.375a.4.4 0 0 1 .039-.098c.073-.072.092-.199.216-.225c.089.014.145.078.208.129a.7.7 0 0 1 .115.14a.3.3 0 0 1 .042.147c.033.221.049.441.037.66a.6.6 0 0 1-.018.158q-.008.04-.02.077c-.063.105-.065.239-.116.358c-.042.11-.119.133-.221.088");
}

.k3zvx_bhb {
  fill: var(--svg-color--282828, #282828);
  d: path("m22.331 30.726l-.121.008l.01-.004c-.043-.052-.084-.105-.061-.181q.004-.064.003-.123c-.03-.073-.022-.128.06-.16c.023.158.016.323.109.46");
}

.k42uyyatw {
  fill: var(--svg-color--474747, #474747);
  d: path("m18.11 37.538l-.099.437c-.033-.004-.035-.028-.051-.054c.013-.147-.059-.324.15-.383");
}

.k4hcnib7x {
  fill: var(--svg-color--5d5d5d, #5d5d5d);
  d: path("M22.937 31.727h-.051q-.073.012-.096.079c-.088-.061-.056-.129-.013-.2c.049 0 .096.005.139.031c.027.028.058.051.021.09");
}

.k4jzu-b1r {
  fill: var(--svg-color--857416, #857416);
  d: path("M16.806 22.22c-.018-.016-.039-.028-.053-.047c.047-.051.105-.047.17-.039c.016.016.047.02.051.056a.17.17 0 0 1-.168.03");
}

.k4nuknbbc {
  fill: var(--svg-color--57160c, #57160c);
  d: path("M21.538 19.13q-.023.005-.047.004v-.381c.11.119.055.252.047.377");
}

.k4y2htb0t {
  fill: var(--svg-color--0c0c0c, #0c0c0c);
  d: path("M17.955 39.487q.025.005.042.004q.008.102.01.207c-.054-.015-.113.063-.162-.015q.054-.094.11-.196");
}

.k5ugq8crb {
  fill: var(--svg-color--43390b, #43390b);
  d: path("M22.843 37.866q-.001-.03.004-.063q.108.03.211.054c-.041.142-.133.082-.215.06z");
}

.k6fhbx82h {
  fill: var(--svg-color--5b5d5d, #5b5d5d);
  d: path("m20.91 36.24l-.051.056c-.062-.038.001-.192-.14-.157c.019-.087.114-.083.153-.143c.025.082.061.154.038.244");
}

.k6fwg6brn {
  fill: var(--svg-color--df1c17, #df1c17);
  d: path("M15.46 21.602c.152.013.322.17.444-.058c.125.031.127.047.047.207c-.124.139-.258.082-.39.021c-.054-.047-.11-.09-.101-.17");
}

.k6odjzkhg {
  fill: var(--svg-color--575757, #575757);
  d: path("M23.415 31.827c.053 0 .096 0 .143-.004a.4.4 0 0 0 .067.004c-.069.121-.138.109-.21 0");
}

.k7u_7djsx {
  fill: var(--svg-color--3b100a, #3b100a);
  d: path("m16.03 33.661l.01.063c-.055.264.049.533-.063.79c-.016-.063-.032-.136-.102-.167c-.018-.004-.021-.016-.02-.021q.007-.021.016-.021q.025-.004.049-.019c.061-.188.016-.379.029-.572a.065.065 0 0 1 .04-.063c.016.002.028.01.041.01");
}

.k8__m_b9s {
  fill: var(--svg-color--3a341e, #3a341e);
  d: path("M20.347 18.07c.174.014.354.021.528.028l-.006.036l-.722.012q-.031-.029-.061-.051z");
}

.k8b0h_b4j {
  fill: var(--svg-color--bfa11b, #bfa11b);
  d: path("M15.468 19.239a.5.5 0 0 0-.086.055c-.041-.01-.059-.036-.066-.08c-.002-.036.016-.067.035-.1c-.004-.011 0-.015.01-.026c.014 0 .023.004.035.004a.2.2 0 0 1 .072.147");
}

.k8c73abuk {
  fill: var(--svg-color--373838, #373838);
  d: path("M12.789 30.831c.003.011.004.019.009.033c-.076.01-.084.217-.211.07c.069-.014.096-.07.137-.111c.025-.018.045-.018.065.008");
}

.k8qa-cbqx {
  fill: var(--svg-color--1e2020, #1e2020);
  d: path("M24.04 35.08h-.042l-.07-.314c.056-.007.099.004.119.061c-.002.079-.007.167-.007.253");
}

.k8xyy3bhb {
  fill: var(--svg-color--333434, #333434);
  d: path("M23.415 29.728c-.207-.079-.07-.292-.156-.412q.027-.033.051-.056q.054.234.105.468");
}

.k97oc4bjl {
  fill: var(--svg-color--532b29, #532b29);
  d: path("M14 18.581c.003-.008.003-.021.003-.029c.082-.086.17-.075.262-.008c0 .008-.01.017-.016.023c-.08.045-.162.117-.249.014");
}

.k9e5152sc {
  fill: var(--svg-color--110804, #110804);
  d: path("M13.224 37.981q-.006-.032-.008-.061q.004-.03.004-.063c.059-.008.115-.016.201-.03c-.047.101-.109.14-.197.154");
}

.karoycciu {
  fill: var(--svg-color--463d0e, #463d0e);
  d: path("M15.293 39.17a.57.57 0 0 1-.056.334a.4.4 0 0 1 .011-.334q.024-.027.045 0");
}

.kdspfobbj {
  fill: var(--svg-color--5c0b0b, #5c0b0b);
  d: path("M18.521 16.821c.047.027.022.047-.008.063c-.047.023-.097.051-.144.074c-.001-.102.082-.113.152-.137");
}

.kdvfzzd_y {
  fill: var(--svg-color--191818, #191818);
  d: path("M20.246 39.802c-.017.016-.028.031-.044.047q-.052-.111-.104-.236l.017-.012z");
}

.kep9rg9xr {
  fill: var(--svg-color--4a5657, #4a5657);
  d: path("M16.731 35.915c.087-.09.195-.027.293-.035q.008.03-.026.048c-.095.069-.178.011-.267-.013");
}

.kex9pjbnq {
  fill: var(--svg-color--261a1a, #261a1a);
  d: path("M11.978 30.514c-.014.126.021.258-.057.374c-.013 0-.025.004-.037.004c-.041-.129.031-.247.043-.37q.022-.032.051-.008");
}

.kfaga9bzx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("m19.71 29.26l-.021-.004h-.023c-.063-.154-.002-.271.116-.37h.037c.047.106-.104.204 0 .308q-.054.028-.109.066");
}

.kgralkddj {
  fill: var(--svg-color--ececec, #ececec);
  d: path("M14.375 18.816q-.01.024-.019.052c-.008.066-.043.109-.115.119q-.114-.01-.223-.017c-.086-.126-.112-.255-.019-.39a.45.45 0 0 1 .25-.012a.5.5 0 0 1 .126.248");
}

.kgti05bvk {
  fill: var(--svg-color--646464, #646464);
  d: path("M24.26 32.831c-.004-.078-.037-.176.098-.176c-.002.098.012.2-.049.285c-.047-.023-.023-.076-.049-.109");
}

.kh_7j1b3v {
  fill: var(--svg-color--474848, #474848);
  d: path("m12.326 30.831l-.05-.061c.013-.068-.02-.167.107-.145a2 2 0 0 1-.057.206");
}

.khb835b_n {
  fill: var(--svg-color--601312, #601312);
  d: path("m16.901 18.23l.285.013c-.144.051-.289.09-.435.004z");
}

.khcactrjk {
  fill: var(--svg-color--b8babe, #b8babe);
  d: path("M15.716 19.784c.032-.023.066-.057.098-.08l.125.271c-.047.04-.092.069-.139.108h-.017c-.037-.078-.108-.142-.103-.235a.2.2 0 0 1 .036-.064");
}

.kk-z4eu9g {
  fill: var(--svg-color--434343, #434343);
  d: path("M14.638 31.954c-.008.153-.004.312-.063.459c-.125-.159.008-.318.004-.479c.029-.019.047-.015.059.02");
}

.kk69x36jj {
  fill: var(--svg-color--62380f, #62380f);
  d: path("M13.274 21.325v.045c-.092-.078-.117-.155.035-.195z");
}

.kklh8vbzd {
  fill: var(--svg-color--370909, #370909);
  d: path("m18.526 28.313l.006-.06c.066.072.109.152.098.26l-.008.02c-.117-.036-.156-.105-.096-.22");
}

.kl0ktj_yb {
  fill: var(--svg-color--292b2b, #292b2b);
  d: path("M19.294 40.22c-.027.019-.054.034-.082.054q-.053-.047-.107-.099c.08-.026.184 0 .218-.108q.017-.032.04 0c.004.058-.037.106-.069.153");
}

.klnnhkgij {
  fill: var(--svg-color--606060, #606060);
  d: path("M25.13 30.938q.018-.026.039-.004c.082.064.088.165.112.255c-.155-.018-.133-.149-.151-.251");
}

.kmtnakxmc {
  fill: var(--svg-color--eff0f0, #eff0f0);
  d: path("M14.687 18.436q.023.018.047.043c.025.056.098.091.083.166a.4.4 0 0 1-.123.204c-.104.07-.202.047-.3-.027c-.051-.084-.088-.168-.053-.268c.072-.164.176-.251.346-.118");
}

.knf7zhxyn {
  fill: var(--svg-color--42110a, #42110a);
  d: path("M19.931 20.706a.2.2 0 0 0 0 .048a.36.36 0 0 0-.066.217c-.077-.116-.048-.199.066-.265");
}

.koivsuaph {
  fill: var(--svg-color--666, #666);
  d: path("M24.729 35.04c-.021-.09-.036-.176-.057-.269a.57.57 0 0 1 .035-.331c.071.059.004.151.053.223a.9.9 0 0 1-.031.377");
}

.kom8g24id {
  fill: var(--svg-color--41220e, #41220e);
  d: path("M19.31 23.268c0-.012 0-.032-.002-.043c.137 0 .274.004.414.004l.02.028l-.014.023z");
}

.kq_nf8jek {
  fill: var(--svg-color--221308, #221308);
  d: path("M22.06 25.464c.004-.01.007-.027.004-.042c.104-.005.205.004.26.114c-.096.011-.173-.051-.264-.072");
}

.kqc3j1bfm {
  fill: var(--svg-color--312a0a, #312a0a);
  d: path("M18.11 16.274c-.015.083-.101.145-.058.244c.017.01.02.021.017.027c-.004.008-.013.017-.017.017c-.177-.133-.042-.209.058-.288");
}

.kqi-sgjiq {
  fill: var(--svg-color--2d0d0b, #2d0d0b);
  d: path("M12.08 33.491q-.023.034-.046.063l-.014-.313a.2.2 0 0 0 .043.004q.011.125.017.246");
}

.krrz8rx_u {
  fill: var(--svg-color--fdfdfd, #fdfdfd);
  d: path("M12.845 31.353c-.086-.15-.014-.326-.049-.488a.07.07 0 0 1 0-.076c.041-.031.071-.017.098.021a.94.94 0 0 1 .009.487a.12.12 0 0 1-.058.056");
}

.ksxxssbke {
  fill: var(--svg-color--282929, #282929);
  d: path("M23.731 31.464c-.143-.109-.119-.274-.15-.424h.036c.066.131.087.285.114.424");
}

.ksz8tvc2r {
  fill: var(--svg-color--3e4040, #3e4040);
  d: path("M18.851 29.469c-.024-.079.022-.146.047-.212a.1.1 0 0 1 .049-.004l-.002-.004c.021.051.086.018.115.062c0 .099-.067.146-.145.181c-.023.001-.047-.003-.064-.023");
}

.ktdhs7bsr {
  fill: var(--svg-color--525252, #525252);
  d: path("M15.867 35.987c.017-.022.033-.048.054-.063l.045.207l-.019.004l-.021-.004c-.065-.03-.053-.084-.059-.144");
}

.kueof3b6m {
  fill: var(--svg-color--dedfdf, #dedfdf);
  d: path("M16.654 36.12c.101.105.2.213.3.314a.03.03 0 0 0-.027.016c-.062.096-.154.063-.24.057a.1.1 0 0 0-.031-.02c-.047-.066-.143-.105-.137-.214c.014-.075.031-.155.135-.153");
}

.kul4lit6r {
  fill: var(--svg-color--4e2727, #4e2727);
  d: path("M15.974 31.954c0 .258 0 .509.004.765q-.032.03-.057-.004c.053-.252-.013-.507.053-.761");
}

.kuxs_cb1y {
  fill: var(--svg-color--532e0c, #532e0c);
  d: path("M14.534 37.842c.115-.109.242-.201.416-.183c-.016.157-.241.053-.256.205a.12.12 0 0 1-.109.03a.08.08 0 0 1-.051-.052");
}

.kv-d9bcwk {
  fill: var(--svg-color--4e150d, #4e150d);
  d: path("M21.284 23.483c.115-.066.215-.023.313.051a.57.57 0 0 1-.313-.051");
}

.kv0zr_bxv {
  fill: var(--svg-color--7f5d27, #7f5d27);
  d: path("M14.168 19.243q.077-.03.155-.053c.002.153-.068.217-.219.197c-.007-.06.036-.099.064-.144");
}

.kvl4jts6z {
  fill: var(--svg-color--5f4d17, #5f4d17);
  d: path("m18.02 19.339l.088-.156c.049.023.061.075.076.122c.012.06.033.122.029.185c-.006.024-.01.047-.021.071c-.051.095-.143.188-.019.295a.1.1 0 0 1 .027.062a.14.14 0 0 1-.071.117q-.036.018-.066-.008c-.318-.208-.082-.456-.043-.688");
}

.kw12otbsn {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M19.937 39.762c0-.203 0-.399.004-.601c.011.004.023.012.039.016l.013.154c-.039.14.029.293-.056.431");
}

.kwea5o2si {
  fill: var(--svg-color--432322, #432322);
  d: path("M23.16 18.558c-.032.042-.071.086-.104.133a.34.34 0 0 0-.119-.291c.13-.032.146.112.223.158");
}

.kweoh4hml {
  fill: var(--svg-color--242525, #242525);
  d: path("M20.18 28.741c-.137.139-.109.318.075.516c-.022.004-.048.004-.067.004c-.031-.021-.063-.035-.094-.055c-.066.02-.109-.014-.138-.071c-.004-.157-.021-.317.089-.452l.051-.063c.049.023.084.086.153.057q-.035.034-.069.064");
}

.kx6romb_h {
  fill: var(--svg-color--5f4213, #5f4213);
  d: path("m21.472 21.811l.328-.013c-.105.103-.215.084-.328.013");
}

.ky7745xtd {
  fill: var(--svg-color--e5c929, #e5c929);
  d: path("M20.574 26.585c.081-.059.157-.11.237-.166c.037.004.063.027.086.055c.033.091.1.152.169.205c.053.008.106.012.143.063c.066-.009.111.063.179.051q.077.042.158.076c-.094.147-.232.102-.363.086c-.02-.008-.035-.021-.056-.027c-.1-.114-.254-.102-.38-.158c-.079-.02-.158.027-.236-.003c-.123-.112-.062-.155.063-.182");
}

.kyf5-c6iq {
  fill: var(--svg-color--044c94, #044c94);
  d: path("M18.528 20.86c-.061-.158-.008-.296.15-.308c.127-.009.24.103.209.274c-.107.148-.228.112-.359.034");
}

.kytyn-b2v {
  fill: var(--svg-color--511c0c, #511c0c);
  d: path("M16.228 23.483c.058-.177.205-.078.311-.104c.044-.028.066-.011.063.04q-.188.03-.374.064");
}

.kywmbbb-n {
  fill: var(--svg-color--2b1b1b, #2b1b1b);
  d: path("M23.05 25.417c-.074.133-.041.279-.043.418c.019.039.008.063-.039.063c-.015-.18-.113-.374.082-.521q.023.012.015.027q-.007.013-.015.013");
}

.kz9gzmb2x {
  fill: var(--svg-color--5f5f5f, #5f5f5f);
  d: path("M20.234 34.764c0 .088-.003.183-.005.269c-.022.018-.053.018-.079.008c-.109-.105-.091-.229-.044-.354c.114-.092.1.026.128.077");
}

.l_282-b-e {
  fill: var(--svg-color--471414, #471414);
  d: path("M25.491 31.28c-.016-.185-.023-.375-.035-.562c.163.207.11.436.053.655c-.035-.024-.039-.058-.018-.093");
}

.l--ts0__r {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("m18.524 41.31l.004-.05c.099-.08.076-.215.131-.312c.006-.035.031-.061.07-.061c.051.061.023.157.102.205q.007.029.008.05a.4.4 0 0 0 .105.288l-.006-.008a.8.8 0 0 0 .082.221c.016.027.012.064-.004.098a1 1 0 0 0-.055.162c-.021.078-.072.148-.074.233c-.014 0-.021.012-.021.022c-.067.043-.114.129-.212.108a13 13 0 0 0-.137-.299c-.08-.084-.075-.195-.125-.288a.16.16 0 0 1 .033-.109a.1.1 0 0 1-.006-.037a.33.33 0 0 0 .105-.223");
}

.l-pw-1twc {
  fill: var(--svg-color--470a07, #470a07);
  d: path("M15.925 26.891c.08.078.188.021.278.062c-.112.056-.22.126-.278-.062");
}

.l-wvzrbnr {
  fill: var(--svg-color--716514, #716514);
  d: path("M22.402 36.706c.112-.022.253.08.334-.074c.021.004.034.015.051.021q.052.05.015.113c-.08.075-.175.066-.274.053c-.085.012-.107-.048-.126-.113");
}

.l080d5bul {
  fill: var(--svg-color--523c3b, #523c3b);
  d: path("m17.226 17.557l.002-.051c.068-.075.14-.091.213-.007a.36.36 0 0 0-.215.058");
}

.l2dg7t5fh {
  fill: var(--svg-color--63190e, #63190e);
  d: path("M20.708 22.913q.25-.001.501-.006c-.166.103-.334.127-.501.006");
}

.l2qqtcbvp {
  fill: var(--svg-color--1e1919, #1e1919);
  d: path("m25.302 33.616l.025-.008c.025.147.02.28-.096.391c-.009-.131.043-.252.071-.383");
}

.l32klr8vs {
  fill: var(--svg-color--401e09, #401e09);
  d: path("M14.615 37.28c.183-.181.333-.402.58-.515c-.155.175-.312.343-.468.521l-.025.02c-.033.011-.064.006-.087-.026");
}

.l37hbopml {
  fill: var(--svg-color--450806, #450806);
  d: path("M16.234 39.37v-.141c-.021-.048-.048-.1.04-.111c.021.136.047.268-.028.391c-.039-.046-.039-.088-.012-.139");
}

.l52ddd4cj {
  fill: var(--svg-color--363533, #363533);
  d: path("M18.675 40.671c.024.035-.021.098.039.129l.031-.071q.047.078.032.185q-.025.032-.048 0a.2.2 0 0 0-.047.049q-.026.027-.051.004c-.068-.115.035-.204.044-.296");
}

.l54lolb8j {
  fill: var(--svg-color--e9e8e6, #e9e8e6);
  d: path("M19.673 17.583c.019.012.034.02.055.031c.086.084.078.192.074.293a.3.3 0 0 1-.035.067c-.086.076-.187.129-.307.076a.43.43 0 0 1-.134-.181c-.032-.09-.028-.179.038-.256c.025-.021.044-.031.068-.049c.085-.036.165-.071.241.019");
}

.l5bn_x8vw {
  fill: var(--svg-color--f4d128, #f4d128);
  d: path("M22.587 38.903c-.003-.014-.003-.021.002-.033c.016-.004.029-.016.045-.022c.098-.097.203-.12.323-.042c.021 0 .04.008.056.008c.113.042.211.102.25.232l.045.056c-.02.128.047.271-.045.392l.006.004q-.033.025-.063-.004c-.007-.008-.012-.022-.023-.026c.017.021.037.034.051.06c-.002.098-.063.178-.148.178c-.09.004-.035-.114-.072-.164a.3.3 0 0 1-.045-.096c-.016-.02-.026-.039-.043-.061c-.099-.012-.203-.053-.299.023c-.084.018-.121-.027-.128-.105c.036-.105.024-.244.177-.271a.4.4 0 0 1 .164-.09c-.074-.008-.121.07-.197.105c-.091-.027-.104-.075-.056-.144");
}

.l5dehzbcr {
  fill: var(--svg-color--570908, #570908);
  d: path("M22.418 23.276a.25.25 0 0 1 .188-.056c-.188.085-.109.258-.125.401c-.014-.008-.03-.024-.051-.033c-.083-.095-.091-.2-.012-.312");
}

.l7_i3qbmv {
  fill: var(--svg-color--1a180e, #1a180e);
  d: path("M18.06 18.07c-.061-.005-.119-.013-.129-.09c.121-.071.149-.181.125-.308q.031-.028.061-.063c.049 0 .089.016.117.057a.4.4 0 0 1 .004.199a.4.4 0 0 0-.094.157a.09.09 0 0 1-.084.048");
}

.l8906tbnl {
  fill: var(--svg-color--58310e, #58310e);
  d: path("M17.489 20.758c-.139-.095-.253-.056-.359.055q-.027.032-.047-.004c.153-.211.27-.228.406-.051");
}

.l8n07j3pq {
  fill: var(--svg-color--c9ae22, #c9ae22);
  d: path("M22.843 37.917c.075-.014.172.072.215-.061c.047.024.043.07.045.109c-.084-.013-.187.042-.26-.048");
}

.l9-hb2rbc {
  fill: var(--svg-color--5c5d5d, #5c5d5d);
  d: path("M17.632 40.737c.02.021.036.033.051.063c.013.061.009.119-.031.171c-.02-.021-.034-.041-.055-.06c-.012-.065-.012-.127.035-.174");
}

.l94qh7btl {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("m24.466 31.464l-.063.201q-.05.032-.1.06a.3.3 0 0 1-.051-.042c-.048-.084-.113-.159-.145-.249a.4.4 0 0 1-.02-.075c-.023-.125-.068-.248-.063-.378l-.007-.194c-.026-.131-.055-.258-.047-.395c.002-.066-.006-.129-.004-.189c.028-.137.221-.104.244-.25c.049-.063.063-.186.192-.119v.111c-.021.074 0 .133.048.188q.002.11.01.229c-.008.157-.008.317.045.471v.358a.42.42 0 0 0-.039.273");
}

.l9qmp48vl {
  fill: var(--svg-color--e1e1e1, #e1e1e1);
  d: path("M17.849 29.885c-.051.036-.102.051-.153 0a.14.14 0 0 1-.065-.091c-.041-.074-.035-.165-.063-.247c-.01-.104-.061-.21.042-.292a.12.12 0 0 1 .077-.021c.099.023.15.094.187.186c-.008.134.095.264.022.408a.2.2 0 0 1-.047.057");
}

.laaqfts6p {
  fill: var(--svg-color--292929, #292929);
  d: path("M20.234 34.764c-.046-.022-.032-.103-.104-.099c-.041.035-.082.095-.148.047l.005.003c-.022-.173.114-.11.188-.11c.106.002.063.093.059.159");
}

.laiuo7pyc {
  fill: var(--svg-color--574d17, #574d17);
  d: path("M23.782 19.761c.021-.036.04-.08.059-.11a.05.05 0 0 1 .045.013c0 .035.004.066.004.104q-.03.053-.053.105c-.09-.003-.09-.05-.055-.112");
}

.lb_52xb_i {
  fill: var(--svg-color--6f6f6f, #6f6f6f);
  d: path("M23.876 34.407c-.056-.08-.048-.178-.033-.278c.039-.044-.015-.116.051-.155a.54.54 0 0 1 .033.328c-.028.027 0 .084-.051.105");
}

.lb6djj_bv {
  fill: var(--svg-color--5f1e0d, #5f1e0d);
  d: path("M22.23 21.12c-.023.031-.051.072-.078.105q-.021.044-.045.01c-.074-.052-.047-.146-.09-.218q.111.057.213.103");
}

.lb7kdssru {
  fill: var(--svg-color--576364, #576364);
  d: path("M24.986 35.827c-.017 0-.028 0-.045-.004q.043-.275.079-.543a.1.1 0 0 1 .035.082c-.012.127.022.252-.023.369v.059c-.008.033-.021.039-.046.037");
}

.lc8wtzbow {
  fill: var(--svg-color--2b1010, #2b1010);
  d: path("M14.371 25.9c.026-.161.085-.317-.01-.479c.161.138.163.324.01.479");
}

.lculv5_lc {
  fill: var(--svg-color--1b1f1f, #1b1f1f);
  d: path("M13.731 31.409h-.038l.052-.207h.046c.022.078-.026.141-.06.207");
}

.ldbu0tbql {
  fill: var(--svg-color--868686, #868686);
  d: path("m22.474 19.499l-.016.01h-.017c.001-.061-.054-.135.04-.174c0 .056.094.115-.007.164");
}

.ldzp7rbir {
  fill: var(--svg-color--3f370c, #3f370c);
  d: path("M13.739 21.13c.023-.015.042-.036.063-.052c.113-.008.219-.102.34-.06c.043.019.072.04.088.083c0 .047-.016.076-.067.076q-.123-.088-.235.003c-.083.068-.141.021-.189-.05");
}

.ldzq1jbwq {
  fill: var(--svg-color--4f3e3d, #4f3e3d);
  d: path("M20.627 25.18c-.087.047-.174.098-.282.098c.025-.109.107-.109.191-.113c.036-.024.065-.022.091.015");
}

.lekvs449w {
  fill: var(--svg-color--5e5e5e, #5e5e5e);
  d: path("M13.315 26.788c.021.1-.047.17-.1.25c-.018-.09-.029-.174.062-.246q.021-.005.038-.004");
}

.lel_q4bxy {
  fill: var(--svg-color--d3d3d3, #d3d3d3);
  d: path("M14.47 29.31c-.084.004-.109.129-.207.11c-.023-.021-.043-.043-.049-.071c0-.09-.031-.196.086-.248q.084.105.17.209");
}

.lf3uqcxfc {
  fill: var(--svg-color--56543b, #56543b);
  d: path("M15.193 20.09q.111.043.211.09c-.06.06-.05.133-.056.212q-.021.001-.049-.004c.019-.105.002-.202-.101-.259q.006-.017-.005-.039");
}

.lfhdvxfkc {
  fill: var(--svg-color--170904, #170904);
  d: path("M24.611 37.81c-.03-.02-.06-.035-.091-.056l-.014.004c-.015-.017-.019-.027-.011-.039q.01-.012.024-.013q.022.001.039-.004c.037.01.093-.017.101.035c.006.021-.027.047-.048.073");
}

.lfwksjb3b {
  fill: var(--svg-color--616161, #616161);
  d: path("M18.944 41.43c-.139-.057-.17-.15-.105-.288c.074.084.08.19.105.288");
}

.lg7-ngmxl {
  fill: var(--svg-color--585111, #585111);
  d: path("M20.292 23.284c.088-.004.182-.027.258.043c-.084-.008-.168.102-.25 0c-.021-.004-.025-.016-.021-.028q.004-.016.013-.015");
}

.lh73d8pkt {
  fill: var(--svg-color--463638, #463638);
  d: path("M16.706 32.1a.1.1 0 0 1 .004.038c-.128-.09-.229-.185.008-.263c-.094.073-.053.147-.012.225");
}

.lhbx-5brt {
  fill: var(--svg-color--4d4f4f, #4d4f4f);
  d: path("m19.79 38.542l.04-.053c.046.034.06.086.063.137l-.053.074c-.062-.037-.105-.082-.05-.158");
}

.lhikjmbkn {
  fill: var(--svg-color--242525, #242525);
  d: path("M18.315 40.1c.039-.09.064-.19.16-.241c.002.084.009.17.013.266q-.031.032-.067 0c-.025-.044-.065-.042-.106-.025");
}

.lhv1_hbrd {
  fill: var(--svg-color--2f3030, #2f3030);
  d: path("M23.948 34.599c-.02.021-.035.036-.053.059l-.02-.25q.028-.052.051-.105c.009.095.012.196.022.296");
}

.li814-b1p {
  fill: var(--svg-color--44200c, #44200c);
  d: path("M15.404 39.9q-.053-.02-.104-.046c-.006-.119.043-.223.092-.324c.041 0 .043.028.052.063c-.017.091-.027.186-.043.277q-.002.018.003.03");
}

.litz6wczi {
  fill: var(--svg-color--2d2f2f, #2d2f2f);
  d: path("M13.739 30.887a.1.1 0 0 1 .107-.054c-.006.125.021.248-.054.367q-.023.032-.047 0c.002-.104.067-.209-.006-.313");
}

.lkkbgrbsi {
  fill: var(--svg-color--722611, #722611);
  d: path("M17.933 20.55c.145-.078.291-.094.438 0q.025.01.016.027c-.008.004-.013.012-.018.012c-.14-.071-.292.005-.436-.039");
}

.lkob1i7_m {
  fill: var(--svg-color--4c4728, #4c4728);
  d: path("M14.823 19.288q0 .264.003.525c-.093-.169-.026-.35-.046-.521q.02-.005.043-.004");
}

.lkryhxbtj {
  fill: var(--svg-color--a7931d, #a7931d);
  d: path("m14.837 40.478l-.027.004l-.023-.004c-.042-.054-.092-.104-.126-.161c-.009-.067 0-.125.09-.09c.058.019.099.015.122-.049q.03-.004.059-.011q.017.007.037.011c.107.165.042.261-.132.3");
}

.lksj1ac8r {
  fill: var(--svg-color--292409, #292409);
  d: path("M22.18 39.22c-.02.017-.035.035-.053.054v-.523c.018-.021.028-.021.046 0q.006.238.007.469");
}

.lm_qs_bil {
  fill: var(--svg-color--452911, #452911);
  d: path("m18.06 23.23l-.002.043q-.183.008-.364.009l.002-.005c-.019-.008-.022-.021-.017-.026c.004-.008.013-.017.02-.017q.177.001.361-.004");
}

.lo8x96bcd {
  fill: var(--svg-color--1c1c1c, #1c1c1c);
  d: path("m24.466 31.464l.055.063c-.006.049-.014.094-.02.146c-.035.014-.07.054-.1-.008c-.054-.094-.013-.149.065-.201");
}

.lo9rfgbbj {
  fill: var(--svg-color--605f5f, #605f5f);
  d: path("M13.323 35.563c-.016.131-.004.264-.1.364c-.031-.009-.037-.04-.051-.058c.075-.091-.028-.264.151-.306");
}

.logqpub_g {
  fill: var(--svg-color--3b3d3d, #3b3d3d);
  d: path("M18.374 28.478c.086-.027.123.027.152.09l.002.047c-.088-.063-.135-.023-.159.066c-.021.012-.042.018-.063.008c-.041-.027-.063-.063-.057-.113c.023-.056.061-.095.125-.098");
}

.lopxj4z7o {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("m13.419 30.726l.064-.682c.086.044.035.189.152.209c.027.063.055.117.129.056c.084 0 .105.056.117.125c-.009.157-.068.3-.072.451a.5.5 0 0 1-.008.317c-.013.067-.037.135-.059.201q-.03.084-.066.157a.7.7 0 0 0-.074.177c-.018.017-.028.028-.049.038c-.176.056-.16-.12-.232-.19c.002-.057-.043-.103-.034-.166c.019-.051-.009-.112.032-.164l.002-.053c.057-.15.026-.328.098-.476");
}

.lovmngw6u {
  fill: var(--svg-color--601412, #601412);
  d: path("M17.14 38.491c-.023.09-.041.176-.121.233c-.047-.12.016-.192.121-.233");
}

.lozk2kbgc {
  fill: var(--svg-color--1f2121, #1f2121);
  d: path("M18.986 37.659a.4.4 0 0 0 .046-.059l.021.146q-.028.054-.051.11c-.002-.066-.01-.129-.016-.197");
}

.lozw96b-x {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("m18.282 41.79l-.118.004c-.077-.1-.065-.221-.098-.334c-.056-.204-.017-.411-.028-.622c.002-.038.002-.084.01-.125c.053-.142.029-.298.1-.429c.029-.059.074-.104.104-.156a.25.25 0 0 1 .076-.082c.055-.021.096-.004.132.039c.075.093.091.226.167.318a.37.37 0 0 1 .082.268c-.025.094-.033.199-.043.3a2 2 0 0 1-.076.295q-.008.032-.021.065a1 1 0 0 0-.088.209l-.027.066c-.043.074-.146.096-.172.184");
}

.lppzmcbbe {
  fill: var(--svg-color--423e23, #423e23);
  d: path("M21.284 17.663c-.1.103-.009.25-.083.356c-.022.021-.05.022-.075.004c-.025-.032-.029-.071 0-.106a.45.45 0 0 0 .053-.329a1 1 0 0 0 .105.021c.016.016.023.023.016.04c-.004.006-.013.014-.016.014");
}

.lr5jyybut {
  fill: var(--svg-color--474848, #474848);
  d: path("M17.589 27.629c-.072-.056-.102-.027-.102.06c-.098-.083-.059-.162.008-.224c.086-.091.086.062.146.062z");
}

.lsfxm33ry {
  fill: var(--svg-color--2f1717, #2f1717);
  d: path("M20.364 32.14q.183.022.357-.047q.024-.032.043.004c-.164.177-.346.119-.529.052c.037-.041.082-.033.129-.009");
}

.lu4vewekp {
  fill: var(--svg-color--1e1a07, #1e1a07);
  d: path("M14.423 37.508c.014.016.031.026.051.044q-.078.029-.152.051q-.032-.005-.066-.004l.021-.052a.06.06 0 0 0 .043 0a1 1 0 0 1 .103-.039");
}

.lucd3hbjg {
  fill: var(--svg-color--151515, #151515);
  d: path("M20.14 29.838c.043-.188.066-.382.041-.577a.08.08 0 0 1 .057-.031q.06.01.07.064c-.008.033-.043.049-.062.076c-.017.115.035.221.054.326c-.054.032-.024.146-.119.137h-.021z");
}

.lumud9bud {
  fill: var(--svg-color--6c4949, #6c4949);
  d: path("M20.14 27.24q-.01-.084.053-.134c.059-.004.146-.051.105.079v.016l-.039.056c-.035.052-.021.178-.138.095a.2.2 0 0 1 .019-.112");
}

.lv9ofjboa {
  fill: var(--svg-color--2a2a2a, #2a2a2a);
  d: path("M15.15 31.15a1 1 0 0 1-.098.045c-.142-.115.144-.146.055-.252h.056c-.004.068-.012.135-.013.207");
}

.lvntxcg1r {
  fill: var(--svg-color--521c1b, #521c1b);
  d: path("M16.55 40.26c.002.148-.08.268-.156.39c-.024-.162.039-.287.156-.39");
}

.lvp275g9v {
  fill: var(--svg-color--616162, #616162);
  d: path("M13.677 32.34c0 .199.047.396-.035.595c-.043-.021-.021-.075-.043-.104c-.01-.168-.049-.328.047-.479c.011-.008.018-.008.031-.012");
}

.lvz7-7jqq {
  fill: var(--svg-color--edeeee, #edeeee);
  d: path("m20.548 28.946l.063.145c.02.023.02.055-.004.074c-.123.052-.207-.015-.284-.104c-.042-.071-.05-.153-.077-.235c-.018-.08-.021-.166.025-.236q.048-.054.106-.01l.028.086c.036.099.096.186.143.28");
}

.lwagyklhl {
  fill: var(--svg-color--9e130f, #9e130f);
  d: path("M16.231 26.573c.037-.033.074-.072.107-.104l-.002.004c.082-.066.121.023.182.047c.027.033.035.057-.014.067c-.052.043-.099.11-.171.03c-.033-.007-.068-.028-.102-.044");
}

.lwfd9iixy {
  fill: var(--svg-color--4d3234, #4d3234);
  d: path("M22.953 34.03a.45.45 0 0 1 .095.224c-.135-.031-.107-.134-.095-.224");
}

.lwqzkih7j {
  fill: var(--svg-color--7f1a0e, #7f1a0e);
  d: path("M20.548 20.907c.014.125-.062.248-.017.377c-.143-.134-.1-.256.017-.377");
}

.lwxaz4buy {
  fill: var(--svg-color--756615, #756615);
  d: path("M23.365 21.07c.071-.047.147.123.208-.016l.109.02c-.109.199-.212.149-.317-.004");
}

.lxzl3_z7l {
  fill: var(--svg-color--151515, #151515);
  d: path("M18.944 37.03c.048-.008.098-.018.15-.021l.17.019c-.028.049-.154.039-.084.149a.1.1 0 0 1-.062.021a.6.6 0 0 1-.174-.105a.08.08 0 0 1 0-.063");
}

.lyk4j7opq {
  fill: var(--svg-color--582e2d, #582e2d);
  d: path("M13.535 36.25c.015-.123-.008-.258.129-.334c-.032.119 0 .258-.129.334");
}

.lypdbccjs {
  fill: var(--svg-color--1a1b1b, #1a1b1b);
  d: path("M19.569 28.788c-.018-.021-.042-.039-.063-.063a.05.05 0 0 1 .008-.042c.017 0 .037 0 .051-.005c.035-.012.07-.021.105-.038c-.002.013-.004.022-.002.035c-.032.039-.069.074-.099.113");
}

.lz0py7bam {
  fill: var(--svg-color--2d1c07, #2d1c07);
  d: path("M14.519 39.41c.099-.14.19-.14.271.017a.38.38 0 0 0-.271-.017");
}

.lzhb6bcjb {
  fill: var(--svg-color--f7d328, #f7d328);
  d: path("M20.285 21.01c-.097.125-.212.149-.353.082a1 1 0 0 0-.068-.117c-.023-.083-.01-.162.055-.222c.068-.078.164-.074.26-.066a.4.4 0 0 1 .139.139c-.005.066.029.13-.033.184");
}

.m__thhb4d {
  fill: var(--svg-color--f6f7f7, #f6f7f7);
  d: path("M17.388 38.23a.17.17 0 0 0-.162.098l-.024.011l-.026-.013c-.08-.047-.215-.058-.17-.209c.038-.062.012-.156.094-.194c.041-.091.082-.171.127-.255c.012-.079.066-.146.093-.223q.163-.255.327-.506c.013-.054.05-.05.089-.046c.075.038.172.042.229.115c.023.052 0 .094-.031.134c-.047.048-.099.09-.104.165a.35.35 0 0 1-.065.153a.6.6 0 0 0-.133.229c-.072.192-.062.409-.244.541");
}

.m_8-hor-v {
  fill: var(--svg-color--422b0b, #422b0b);
  d: path("M12.905 37.39c-.079-.066-.168-.066-.258-.023c-.004-.043.017-.074.054-.094c.071.01.151-.014.211.051c.023.027.019.046-.007.066");
}

.m-wgc-blu {
  fill: var(--svg-color--2a0b06, #2a0b06);
  d: path("M22.737 40.33c-.014-.16-.178 0-.219-.104c.078.062.305-.265.263.104c-.014.016-.029.02-.044 0");
}

.m06c5ibxl {
  fill: var(--svg-color--5b5c5c, #5b5c5c);
  d: path("M24.988 31.464c.082.123.028.263.04.394c-.045-.131-.04-.263-.04-.394");
}

.m1ga52bvt {
  fill: var(--svg-color--472c0b, #472c0b);
  d: path("M14.418 38.803a.9.9 0 0 0-.255.255c-.021-.191.094-.259.255-.289z");
}

.m1ovgobjq {
  fill: var(--svg-color--3f3f3f, #3f3f3f);
  d: path("M24.458 30.36c.115.114.139.274.196.422q-.02.033-.04 0q-.03.022-.059.049c-.029.016-.06.016-.084-.008c-.115-.151-.124-.306-.013-.463");
}

.m1pmzr44l {
  fill: var(--svg-color--c4c5c5, #c4c5c5);
  d: path("M17.698 28.1q.048.007.098.02c.021.017.038.029.055.052a.73.73 0 0 1 .095.356c-.013.071-.037.131-.106.162c-.082-.005-.125-.06-.152-.125c-.056-.158-.114-.315.01-.465");
}

.m1tw27b7y {
  fill: var(--svg-color--564e11, #564e11);
  d: path("M16.863 23.335c.085-.066.172-.09.267-.012c-.09.022-.178.07-.275.043z");
}

.m1xyqmbvx {
  fill: var(--svg-color--fdd628, #fdd628);
  d: path("M24.04 21.12c.083.057.179.109.058.221c-.144.047-.295-.016-.439.04c-.084.055-.189.075-.271.134c-.039.027-.082.034-.125.051c-.061.016-.08.059-.063.113q.006.033.007.066c-.012.082-.059.146-.094.216c-.066.086-.113.181-.211.237c-.053.088-.153.104-.232.155c-.16.013-.326.083-.482-.011c-.113-.041-.157-.178-.284-.201c-.159-.012-.318.01-.478-.012a.7.7 0 0 1-.246-.102c-.076-.076-.156-.131-.267-.084a1.7 1.7 0 0 1-.444.03a.24.24 0 0 1-.111-.021a.26.26 0 0 1-.133-.069c-.099-.177-.242-.079-.373-.06c-.033-.033-.069-.023-.099.013a.2.2 0 0 1-.108.028a2 2 0 0 1-.269.004a1 1 0 0 1-.112-.017c-.067-.026-.144-.034-.213-.063c-.168-.088-.295-.202-.3-.416c0-.008-.007-.016-.011-.016c-.005 0-.008.008-.012.016a.8.8 0 0 0-.104.197c-.064.113-.177.168-.277.239c-.092.043-.182.099-.289.083c-.096-.023-.195-.02-.293-.023a.5.5 0 0 1-.145-.02c-.035-.012-.063-.031-.09-.047c-.049-.036-.1-.079-.168-.076c-.071.025-.117.1-.184.131c-.078.035-.146.086-.23.105c-.088.015-.18.015-.266.011c-.082 0-.164-.098-.244.052c-.051.09-.229.008-.326.086a.26.26 0 0 1-.141.036a2 2 0 0 0-.291-.013c-.047 0-.092-.003-.139 0c-.102-.003-.158.07-.227.129a.56.56 0 0 1-.236.119q-.056.01-.117.008c-.084-.005-.156-.041-.236-.051c-.221-.071-.334-.26-.459-.438c-.047-.041-.051-.104-.055-.168c.008-.148-.125-.172-.219-.224c-.063-.063-.152-.083-.229-.134c-.156-.051-.319 0-.48-.027c-.07-.07-.021-.126.025-.181c.021-.021.041-.035.061-.052a.4.4 0 0 1 .273-.063a.4.4 0 0 1 .072.02c.137.143.315-.059.457.057c.084.079.182.063.278.039a.5.5 0 0 1 .366.09a.48.48 0 0 1 .126.408c-.013.117-.124.15-.188.217c.008.047.043.066.075.1q.107.076.216 0c.022-.021.047-.043.063-.066c.038-.075.022-.143-.005-.213c-.021-.055-.041-.113-.025-.168a.16.16 0 0 1 .078-.08c.091-.032.173-.004.254.031a.3.3 0 0 1 .082.071c.031.06.061.118.119.165c.105.083.211.1.316-.013a.25.25 0 0 0 .002-.248c-.039-.06-.084-.114-.088-.192a.14.14 0 0 1 .031-.066c.104-.06.208-.113.319-.168c.054-.004.096.004.125.055c.036.061.032.134.073.189q.025.047.049.084a.42.42 0 0 0 .215.233c.102.047.189.02.266-.059c.02-.018.033-.027.053-.043c.092-.06.123-.156.16-.252c.01-.027.026-.043.041-.062a.28.28 0 0 1 .289-.047c.113.094.137.267.286.333l.056.036a.4.4 0 0 0 .291-.005c.095-.008.16-.07.231-.121c.08-.09.142-.182.054-.295q-.054-.072-.14-.059c.078.008.134.043.16.113c.04.105-.022.172-.082.244a.45.45 0 0 1-.257.113a.4.4 0 0 1-.163-.01c-.206-.1-.226-.291-.24-.488c.021-.113.086-.213.134-.317c.039-.063.073-.135.152-.166c.15-.039.298-.06.443.022q.063.033.109.092c.034.06.038.13.096.172c.088.059.17.023.252-.016c.082-.063.063-.192.168-.24c.137-.083.276-.079.424-.02a.39.39 0 0 1 .254.254a.62.62 0 0 1 .004.457a.4.4 0 0 1-.169.231a.4.4 0 0 1-.083.028c-.178.004-.334-.036-.417-.217c-.032-.082-.039-.156.026-.224a.17.17 0 0 1 .162-.022c-.039-.031-.094-.017-.144.004c-.104.078-.086.173-.04.271c.061.125.172.165.292.192c.099.027.192.044.285-.004a.2.2 0 0 1 .055-.035q.082-.056.157-.122c.066-.062.092-.166.186-.204a.23.23 0 0 1 .244.051c.057.063.07.153.131.212q.061.078.131.152c.06.055.119.095.199.051a.6.6 0 0 0 .118-.108a.2.2 0 0 1 .047-.043c.132-.076.162-.217.239-.33a.1.1 0 0 1 .068-.018c.104.047.219.057.33.083a.12.12 0 0 1 .052.052a.2.2 0 0 1-.013.066a.7.7 0 0 0-.117.191a.2.2 0 0 0 .005.162q.038.071.104.108c.074.026.147.032.217-.019a.43.43 0 0 0 .156-.182a.2.2 0 0 1 .049-.055c.078-.043.155-.072.248-.053c.062.021.104.06.131.127a.12.12 0 0 1-.002.07c-.047.078-.07.166-.027.254a.4.4 0 0 0 .063.084c.094.074.166.016.24-.041c.02-.02.034-.043.023-.069c-.053-.06-.125-.093-.153-.17a.6.6 0 0 1 .003-.312c.035-.084.1-.15.18-.205c.021-.007.047-.019.069-.027c.082-.016.167-.016.252-.027a.1.1 0 0 1 .065.01c.074.065.109.008.147-.049c.045-.039.095-.068.156-.064c.11.064.221.117.327-.004a.25.25 0 0 1 .146-.013c.077.028.144.072.209.106");
}

.m2_svnbhj {
  fill: var(--svg-color--2a0f0f, #2a0f0f);
  d: path("M20.675 41.17c-.031-.123-.084-.236-.072-.368q.026-.035.054 0c.037.048.077.105.114.148c-.076.037-.047.101-.049.158c.01.02.013.033.006.062q-.029.021-.053 0");
}

.m2obo7bie {
  fill: var(--svg-color--3e3c29, #3e3c29);
  d: path("M16.927 26.624a.47.47 0 0 1-.302-.153c.128-.004.238.026.302.153");
}

.m2vnq4o0y {
  fill: var(--svg-color--2e1008, #2e1008);
  d: path("m13.78 38.646l-.045-.058c.008-.073.018-.138.027-.205c.039.004.059.021.039.063z");
}

.m30y1tb_m {
  fill: var(--svg-color--4d1210, #4d1210);
  d: path("m20.394 27.737l-.104-.068a.16.16 0 0 1-.046-.141a.14.14 0 0 1 .055-.105q.044.159.095.314");
}

.m3osfnbbt {
  fill: var(--svg-color--52360f, #52360f);
  d: path("M20.19 20.719a.33.33 0 0 0-.258.036q-.022-.019-.016-.032c.006-.013.008-.017.016-.017c.074-.094.166-.059.256-.045q.023.018.021.039c-.006.016-.013.019-.019.019");
}

.m4-l4ib8e {
  fill: var(--svg-color--653010, #653010);
  d: path("M23.04 20.758c-.06.091-.036.188-.036.288c-.08-.108-.121-.215.036-.288");
}

.m4v7wwbzv {
  fill: var(--svg-color--161616, #161616);
  d: path("M13.159 29.31c-.025-.017-.053-.037-.081-.047c.009-.091-.071-.188.039-.261q.107.055.06.166q-.011.072-.018.142");
}

.m52cjub7e {
  fill: var(--svg-color--171818, #171818);
  d: path("M23.578 30.24c-.035.055-.076.104-.11.16c-.012.021-.027.027-.055.021c-.087-.083.031-.149.012-.222c.035-.035-.004-.112.082-.102q.037.072.071.143");
}

.m544-qbys {
  fill: var(--svg-color--dadbdc, #dadbdc);
  d: path("M22.429 19.19q.034-.034.065-.06c.065-.004.104.029.133.087c.022.181.044.354.021.534c-.028.117-.084.231-.073.35a.34.34 0 0 1-.101.203l-.031.055c-.016.04-.016.083-.031.119c-.016.038.002.085-.034.113c-.042.041-.073.082-.11.123a.26.26 0 0 1-.213-.033a.18.18 0 0 1-.07-.125c.008-.071.057-.104.101-.145c.122-.104.183-.236.24-.375c.039-.082.039-.177.062-.267c.025-.076.03-.157.047-.231a.24.24 0 0 0-.017-.194c-.021-.048-.04-.101.011-.154");
}

.m5dz9k56e {
  fill: var(--svg-color--383217, #383217);
  d: path("M17.224 18.09q.002.024.006.043a.3.3 0 0 1-.064.05c-.213-.125-.449-.008-.665-.063c.235-.092.478-.026.723-.03");
}

.m7kxm6pkh {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M22.323 19.771c-.076.085-.046.195-.053.298c-.084.055-.16.141-.271.055l-.022-.004l-.019.008c-.032-.092-.151-.084-.188-.166a.24.24 0 0 1-.004-.154a.34.34 0 0 1 .125-.156c.177-.081.313-.013.432.119");
}

.m7siesb2d {
  fill: var(--svg-color--5e0d0b, #5e0d0b);
  d: path("M14.925 23.284c.024 0 .043.004.068.004c.027.104.057.205-.005.304q-.028.014-.052.032q-.003-.174-.011-.34");
}

.m8-i5hbij {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M22.02 32.985c.016.026.029.059.043.086c.017.131.057.256.053.387v-.004q-.026.033-.048.068c-.058.082-.007.209-.112.271c-.117.062-.13-.084-.199-.109a.63.63 0 0 1-.104-.304q.009-.016-.005-.034c-.108-.082-.041-.225-.125-.314c-.098-.121.059-.289-.063-.408q-.009-.359-.014-.724c.121-.038.121.101.193.132c.054.056.121.094.186.142c.025.021.045.052.066.077c.023.055.017.113.018.17c.02.044.035.082.053.125c0 .078-.009.162.022.238c.013.072-.007.138.036.201");
}

.m87wvacyk {
  fill: var(--svg-color--574d11, #574d11);
  d: path("M22.11 39.9q.003-.017.002-.036c.089-.002.174-.002.265-.009c-.079.091-.175.041-.267.045");
}

.m8wv5gbok {
  fill: var(--svg-color--313939, #313939);
  d: path("M25.08 34.24q.03.005.063.004c.031.086 0 .18.022.262c-.018.066-.026.139-.041.207c-.009.023-.026.027-.042.006q0-.242-.002-.479");
}

.ma6mwgawn {
  fill: var(--svg-color--3d2121, #3d2121);
  d: path("M23.15 34.556c.017.049.029.105.1.052q.061-.039.118 0q.013.025.024.054c-.109-.004-.291.19-.301-.104q.025-.026.059-.002");
}

.maqxy3bjw {
  fill: var(--svg-color--685c12, #685c12);
  d: path("M20.87 18.13q-.005-.017.006-.036q.13-.01.254-.015c-.043.234-.168.062-.26.051");
}

.masuv7bal {
  fill: var(--svg-color--3d3e3e, #3d3e3e);
  d: path("M21.923 30.15c-.027 0-.058-.007-.084-.012c.073-.051.071-.168.174-.2l-.004-.004q.089.166-.086.216");
}

.mbcsp1bhe {
  fill: var(--svg-color--252727, #252727);
  d: path("M22.271 32.07c-.019-.076.004-.14.05-.201c.024.013.019.062.062.049c.022.152.149.285.043.441c-.06-.074-.043-.162-.056-.244c-.009-.082-.047-.082-.099-.045");
}

.mbfsz2c7l {
  fill: var(--svg-color--f3f3f3, #f3f3f3);
  d: path("M15.09 18.274c.069-.042.176.006.223-.09a2 2 0 0 0 .152.109c.09.142.071.268-.039.381c-.098.063-.203.061-.308.035c-.043-.01-.08-.035-.084-.09q-.001-.032-.006-.063a.5.5 0 0 1 .062-.282");
}

.mc2hy7b8t {
  fill: var(--svg-color--5c2b29, #5c2b29);
  d: path("M18.888 42.14c-.08-.101.01-.163.049-.238a.06.06 0 0 1 .043.052c-.034.061-.061.128-.092.186");
}

.mfj4b9baa {
  fill: var(--svg-color--4e3f0e, #4e3f0e);
  d: path("M14.888 36.864c-.135.174-.283.33-.485.424c-.06-.078-.179-.021-.236-.099c.002-.079.037-.118.116-.11c.018.004.036.008.05.004c.019-.012.05.016.05-.022c0-.004-.027-.017-.039-.03c.025-.035.047-.078.072-.121c.126-.066.266-.063.401-.074a.1.1 0 0 1 .071.028");
}

.mg3_6ibku {
  fill: var(--svg-color--260f06, #260f06);
  d: path("m12.89 37.758l-.09.054c-.195-.115.141-.107.047-.201a.05.05 0 0 1 .02-.027a.09.09 0 0 1 .098.013c.027.06-.023.084-.055.118z");
}

.mg5mrsjkg {
  fill: var(--svg-color--fdd628, #fdd628);
  d: path("M18.831 22.278c.012-.07-.023-.102-.084-.109c.199-.118.415-.008.618-.059c.267-.031.535-.013.802.016c.083.027.17.022.252.022c.079.028.168.017.236.076c.033-.017.074-.03.109-.047a.9.9 0 0 0 .36.083c.099.023.192.051.292.051c.094.037.188.047.279.076c.091.031.179.042.271.051q.079.031.155.055c.027.08.099.086.162.103c.133.037.122.114.065.208c-.099.063-.293.007-.287.204c.006.176.13.249.283.271c.09.051.068.143.031.2c-.064.079-.156 0-.236 0c-.127-.047-.274-.047-.385-.146q-.023-.005-.047-.004c-.074.004-.146-.032-.22-.028a2 2 0 0 0-.472-.075c-.034 0-.071-.004-.104-.004c-.188-.133-.432-.027-.621-.152c-.053-.017-.107.059-.16-.013c-.111 0-.228.021-.345.008c-.153-.06-.321.021-.479-.06c-.116-.07-.248-.032-.375-.039c-.082-.008-.18.02-.194-.11c.127.017.204-.055.251-.159c.275-.162.04-.252-.051-.363c-.012-.056-.059-.06-.106-.056");
}

.mgc44u5rk {
  fill: var(--svg-color--4f4f4f, #4f4f4f);
  d: path("M18.591 39.33a.4.4 0 0 1 .084.051a.55.55 0 0 1-.096.279c-.098-.112.048-.224.012-.33");
}

.mglusmbnw {
  fill: var(--svg-color--73705a, #73705a);
  d: path("m14.875 20.239l.054-.055q.04-.04.053.012c-.025.084.146.156.014.252c-.041-.067-.082-.141-.121-.209");
}

.mgzgf4bwo {
  fill: var(--svg-color--200c05, #200c05);
  d: path("M22.95 36.812q-.029.005-.057.004c-.017.021-.033.021-.057.016a.1.1 0 0 1-.047-.07l-.003-.105c.089.017.123.088.164.155");
}

.mh-d-kbkt {
  fill: var(--svg-color--f6f6f6, #f6f6f6);
  d: path("M23.774 28.887c-.021-.126.193-.07.158-.208c.134.009.082-.122.125-.18q.048.099.086.191c.018.027.033.051.055.079c-.016.149.061.283.074.438c.019.259.084.519-.043.766c-.041.139-.12.188-.25.126c-.041-.04-.061-.091-.082-.14c-.01-.069-.038-.139-.043-.215c-.1-.113-.008-.244-.022-.365c-.065-.157-.142-.316-.058-.492");
}

.mh5sp7bbs {
  fill: var(--svg-color--511f1e, #511f1e);
  d: path("M22.897 28.399c-.006.1-.024.192-.104.256c-.054-.123.03-.184.104-.256");
}

.mhhbxtvjl {
  fill: var(--svg-color--220a09, #220a09);
  d: path("M15.206 33.507h.038l-.062.209q-.02-.023-.043-.057z");
}

.mhl_flbxn {
  fill: var(--svg-color--4b4613, #4b4613);
  d: path("M21.745 40.18c.061.069.146.039.221.051c-.035.104-.207-.026-.211.13q-.115-.033-.1-.152c.006-.067.048-.058.09-.029");
}

.mhvcg0a4n {
  fill: var(--svg-color--190505, #190505);
  d: path("M22.532 39.491q-.041-.05-.082-.104l-.014-.109c.031-.029.06-.033.09 0c-.004.079.013.135.107.094q.023.018.016.037c-.004.008-.008.018-.014.018a.6.6 0 0 0-.103.064");
}

.mhx4_xbre {
  fill: var(--svg-color--2a2b2b, #2a2b2b);
  d: path("M21.816 31.25c-.032-.047.026-.129-.062-.151c-.052-.075-.068-.146-.009-.222c.043-.01.069-.051.117-.06c.039.005.06.029.075.06q.006.033.005.067c-.03.095.103.188.004.278c-.037.032-.08.053-.13.028");
}

.micxxbcle {
  fill: var(--svg-color--5d5313, #5d5313);
  d: path("M18.341 16.299c.202.034.266-.063.236-.249a.19.19 0 0 1 .006.268c-.059.062-.167.066-.242-.019");
}

.micyotbnj {
  fill: var(--svg-color--b11011, #b11011);
  d: path("m18.06 21.45l-.002.094c-.102.047-.203.031-.306.007l-.019-.007l.156-.104c.055.006.112.006.171.01");
}

.migrkx7pj {
  fill: var(--svg-color--746b3b, #746b3b);
  d: path("M15.716 19.882c-.084.047-.061.123-.052.195c-.047 0-.098.004-.116-.051c-.068-.091-.063-.193-.066-.295a.16.16 0 0 1 .064-.094c.039-.016.075-.012.108.02q.03.066.062.125z");
}

.mil_4hb4v {
  fill: var(--svg-color--6b6129, #6b6129);
  d: path("m21.998 19.495l-.093.127c-.077-.021-.084-.071-.059-.135q.025-.134.051-.255q-.022-.039.017-.051h.095l.01.075a7 7 0 0 1-.021.239");
}

.mirno0b2g {
  fill: var(--svg-color--504610, #504610);
  d: path("M17.647 23.08c-.016-.021-.035-.037-.051-.057c.17-.003.338-.011.506-.016c.037.005.072.013.106.016l.001.036z");
}

.mkqc2zb3i {
  fill: var(--svg-color--3e240d, #3e240d);
  d: path("M16.39 21.379c.108.011.193.102.313.079v.022c-.048.075-.175-.026-.203.091c-.059-.051-.134-.094-.11-.192");
}

.ml_50_b1q {
  fill: var(--svg-color--4f380d, #4f380d);
  d: path("M22.489 21.751c-.071-.07.023-.211-.111-.26c-.016-.022-.019-.039-.012-.066a.14.14 0 0 1 .127-.07c.023.008.046.016.059.038a.6.6 0 0 0-.013.358q-.028.034-.05 0");
}

.ml6u7dqsu {
  fill: var(--svg-color--484949, #484949);
  d: path("M22.12 33.456a.43.43 0 0 1-.053-.385c.057.123.166.241.053.385");
}

.mml_shb_z {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M23.667 20.17q0-.202.002-.401l.01-.075q.031.03.061.055q-.004.196-.004.387c-.002.035-.004.063-.004.093c-.02-.026-.045-.041-.065-.059");
}

.mndkgdckl {
  fill: var(--svg-color--282a2a, #282a2a);
  d: path("m17.18 31.833l.098.049q.086.001.17-.006c-.102.068-.218.195-.268-.043");
}

.mnz2qqa8e {
  fill: var(--svg-color--3e3e3e, #3e3e3e);
  d: path("M24.24 20.29q.022-.005.042-.004c.023.109.061.225-.085.278a.42.42 0 0 0 .043-.274");
}

.mo1c_yqwq {
  fill: var(--svg-color--434444, #434444);
  d: path("M15.499 31.618h-.034c.016-.158.063-.312-.002-.469c.057-.016.103.014.141.053c-.015.143-.011.295-.105.416");
}

.mo8j5fecn {
  fill: var(--svg-color--4a3130, #4a3130);
  d: path("M20.433 35.708q-.21-.19-.021-.404z");
}

.mq4dxu5jo {
  fill: var(--svg-color--5a4e10, #5a4e10);
  d: path("M16.04 39.08c.055.099.072.157.024.236c-.057-.064-.069-.126-.024-.236");
}

.mqkfls_jt {
  fill: var(--svg-color--0f0f0f, #0f0f0f);
  d: path("M15.921 32.715q.028-.001.057.004c.016.044.031.078.043.116a.03.03 0 0 1 0 .029c-.012.02-.027.037-.043.062l-.094-.099c-.025-.051-.021-.09.037-.112");
}

.mraxzbxlb {
  fill: var(--svg-color--6d6d6d, #6d6d6d);
  d: path("M17.233 34.706a.3.3 0 0 1-.008.343c-.094-.078-.034-.193-.041-.287c.015-.021.017-.052.049-.056");
}

.mro10pbtr {
  fill: var(--svg-color--887616, #887616);
  d: path("M17.647 23.08c-.129.051-.26.092-.385-.013a.56.56 0 0 1 .334-.043c.016.019.051.019.051.056");
}

.mrp3mybik {
  fill: var(--svg-color--232424, #232424);
  d: path("M18.312 27.383c-.047-.032-.084-.086-.153-.043q-.034.005-.058-.021q-.007-.03.012-.062c.039-.021.154.022.107-.04c-.174-.235.113-.042.1-.118c.061.021.15.008.083.118c-.03.054-.06.112-.091.166");
}

.mrqp6ub0x {
  fill: var(--svg-color--dcdddc, #dcdddc);
  d: path("M18.524 29.528c.02.043.037.09.056.133c.004.078-.056.125-.103.177c-.057.015-.107.051-.17.024c-.016-.005-.029-.017-.045-.02c-.018-.071-.031-.139-.049-.209c-.011-.109-.063-.225-.015-.34c.217-.071.287-.022.326.235");
}

.mrvg0cbda {
  fill: var(--svg-color--4f4f4f, #4f4f4f);
  d: path("M18.687 39.34q.028-.117.059-.237l.09.383c-.132.038-.073-.122-.149-.146");
}

.mrw6rv_ky {
  fill: var(--svg-color--53190a, #53190a);
  d: path("M15.612 25.431q-.162.023-.319.039c.068-.148.21-.074.32-.098c.012.011.021.022.012.039q-.006.018-.013.02");
}

.mryaqc5uy {
  fill: var(--svg-color--202121, #202121);
  d: path("M19.72 28.577c-.084-.094.039-.17.016-.264h.033q-.009.136-.014.26h-.02z");
}

.mryx-2bzy {
  fill: var(--svg-color--616062, #616062);
  d: path("M24.356 32.583c-.076-.102-.122-.192.051-.238a.45.45 0 0 1-.051.238");
}

.ms0r-bb7y {
  fill: var(--svg-color--242525, #242525);
  d: path("M13.421 30.04a.3.3 0 0 0 .063.004a.96.96 0 0 1-.029.664c-.035.048-.074.048-.12.016c-.004-.191.103-.38.027-.572c.024-.04.039-.077.059-.112");
}

.msl6mjbuc {
  fill: var(--svg-color--222, #222);
  d: path("M12.659 29.31c-.014.118-.009.244-.08.394c-.063-.166.023-.279.023-.394q.027-.026.057 0");
}

.msu6hprvs {
  fill: var(--svg-color--483131, #483131);
  d: path("M12.435 27.78c-.012.113-.02.23-.094.324c-.02.023-.033.023-.048-.004c.015-.121.027-.243.142-.32");
}

.mt4tndy-l {
  fill: var(--svg-color--e8e8e5, #e8e8e5);
  d: path("M17.646 17.811c-.004-.06-.008-.112-.01-.177c.076-.078.174-.078.271-.085c.091.004.148.055.193.132c.035.146-.021.252-.142.332a.34.34 0 0 1-.215.003c-.075-.043-.166-.083-.097-.205");
}

.muqcjuc8c {
  fill: var(--svg-color--1e1c14, #1e1c14);
  d: path("m15.503 36.31l.055.191h-.201c-.01-.01-.014-.021-.022-.027c-.015-.063.009-.138-.022-.201a.3.3 0 0 1 .007-.109c.022-.06.036-.116.096-.156c.028-.004.052.008.063.031c.012.089-.011.179.024.271");
}

.mw0wliqrc {
  fill: var(--svg-color--3d3d3d, #3d3d3d);
  d: path("M22.489 29.889q.022-.005.051-.004c.057.137.119.267.092.424a.1.1 0 0 1-.082.013c-.113-.135-.141-.276-.061-.433");
}

.mwbedwb2w {
  fill: var(--svg-color--242424, #242424);
  d: path("M23.728 31.46c.058.104.125.197.133.318h-.075a.05.05 0 0 1-.056.016c-.022-.016-.016-.045-.022-.063c-.011.021.005.063-.04.073c-.02 0-.031.01-.042.021c-.022.023-.048.023-.065-.004c-.039-.156.004-.285.167-.361");
}

.mwj95lp6j {
  fill: var(--svg-color--651a0c, #651a0c);
  d: path("M14.761 22.02q.179.001.362-.004c-.122.123-.243.109-.362.004");
}

.mwotuybmw {
  fill: var(--svg-color--5c290f, #5c290f);
  d: path("M22.423 20.338c-.008-.099.086-.13.12-.205c.013-.048.032-.079.089-.067c-.004.119.004.245-.158.275q-.028.021-.051-.003");
}

.mwq05dg0t {
  fill: var(--svg-color--50250b, #50250b);
  d: path("m24.617 38.16l-.22-.142c.146-.069.19.03.22.142");
}

.mwuorsbln {
  fill: var(--svg-color--feda24, #feda24);
  d: path("M23.675 19.395a.3.3 0 0 0-.049-.051h.061z");
}

.mxetps57l {
  fill: var(--svg-color--3b2f30, #3b2f30);
  d: path("M14.79 35.18a1 1 0 0 1-.119.008c-.044.003-.084-.008-.103-.049c0-.015.004-.038.004-.054c.072.031.146.068.218.095");
}

.mygky4trh {
  fill: var(--svg-color--656566, #656566);
  d: path("m17.226 35.605l-.02.005h-.02c-.002-.092-.002-.178-.002-.271c.016-.023.016-.061.055-.067c.098.115-.011.223-.013.333");
}

.myvi7ocyf {
  fill: var(--svg-color--a28b1a, #a28b1a);
  d: path("M18.1 23c.168-.102.369.02.539-.083c.017-.071.054-.091.121-.075c.108.061.235.023.35.047c.078.014.195-.012.193.135a.4.4 0 0 1-.09.012h-.979c-.048-.005-.098.007-.134-.036");
}

.myvlpbcse {
  fill: var(--svg-color--532e2b, #532e2b);
  d: path("M13.272 19.603c-.018 0-.036.004-.053.004c-.063-.113-.127-.229.027-.318a.32.32 0 0 0 .026.314");
}

.mz3f50brr {
  fill: var(--svg-color--5c270f, #5c270f);
  d: path("M23.571 20.13c-.018.003-.032.003-.053.003l.007-.421q.024.002.044.017a.2.2 0 0 1 .058.099a.4.4 0 0 1-.026.275c-.01.005-.021.019-.03.027");
}

.mzka65biv {
  fill: var(--svg-color--e8c826, #e8c826);
  d: path("M22.378 21.46a2 2 0 0 1-.156-.016a1 1 0 0 1-.069-.059c-.021-.047-.005-.102-.007-.154c0-.058.035-.089.086-.109c.062 0 .129.004.187.004a.28.28 0 0 1 .06.26c-.036.023-.069.051-.101.074");
}

.mztktbcyl {
  fill: var(--svg-color--535555, #535555);
  d: path("M15.449 31.802c.002.048.003.1.003.145c-.105-.049-.083.223-.219.098c.09-.07.069-.235.216-.243");
}

.n_-427bii {
  fill: var(--svg-color--4e3434, #4e3434);
  d: path("M14.267 26.329a.6.6 0 0 1 .094-.313c.027.121.029.235-.094.313");
}

.n_ilg_b-q {
  fill: var(--svg-color--211616, #211616);
  d: path("M12.521 28.313a.57.57 0 0 0-.233.33c-.097-.083.032-.188-.019-.282c.031-.039.08-.025.123-.025a1 1 0 0 1 .129-.023");
}

.n-b00hf-w {
  fill: var(--svg-color--685b13, #685b13);
  d: path("M16.654 22.01c-.192.066-.384.138-.591.06c.08-.055.135-.134.262-.063c.055.028.257.021-.023-.205c.188.067.271.096.351.123c.03.026.03.057.001.085");
}

.n-dxnj2mw {
  fill: var(--svg-color--6f6841, #6f6841);
  d: path("M16.496 18.01q-.01-.019.001-.029l.157-.22c.056.047.11.099.162.146a.12.12 0 0 1-.052.098a.3.3 0 0 1-.142.063c-.05.002-.105.002-.126-.058");
}

.n-snanbdf {
  fill: var(--svg-color--171919, #171919);
  d: path("M12.644 34.35c.017-.034.035-.064.049-.102q.008.148.018.293c-.02.041-.035.076-.051.113a4 4 0 0 1-.016-.304");
}

.n07j8qott {
  fill: var(--svg-color--383939, #383939);
  d: path("M20.1 39.612c-.108.049-.022.189-.113.243q-.035.032-.071-.001a.2.2 0 0 1-.022-.123c.043-.135-.02-.292.086-.404c.027-.012.057-.008.076.02c-.028.096.07.165.061.255z");
}

.n0eq0ox1v {
  fill: var(--svg-color--262626, #262626);
  d: path("M17.853 27.43c0-.021 0-.037-.004-.056a.07.07 0 0 1 .056-.063c.075 0 .071-.313.209-.055v.055c-.002.047-.011.098-.054.129a.2.2 0 0 1-.105.032a.2.2 0 0 1-.102-.042");
}

.n12ynnhcg {
  fill: var(--svg-color--43494a, #43494a);
  d: path("M13.966 19c-.012-.082-.093-.121-.131-.185c.033-.104.057-.211.17-.262a.12.12 0 0 1 .029.062c-.023.119.014.232-.012.351a.2.2 0 0 1-.056.034");
}

.n1qmn6ohe {
  fill: var(--svg-color--e5c425, #e5c425);
  d: path("m15.1 21.552l-.057-.031c-.121-.087-.191-.188-.117-.346c.072-.09.174-.034.258-.051a.2.2 0 0 1 .093.062a.3.3 0 0 1 .009.188c-.023.072-.105.076-.137.125z");
}

.n1ws18a6v {
  fill: var(--svg-color--3a3a3a, #3a3a3a);
  d: path("M17.427 39.855c-.09-.046-.006-.172-.1-.218c-.021-.006-.037-.021-.037-.045l.083-.168a.13.13 0 0 1 .095.068c.035.119.082.235.031.356q-.034.04-.072.007");
}

.n1zwxu5cz {
  fill: var(--svg-color--caaf27, #caaf27);
  d: path("M22.11 20.458c-.09-.051.049-.121-.012-.172c-.037-.105.045-.153.106-.207a.3.3 0 0 1 .067-.032c.033-.005.066-.005.093.032c-.062.136-.101.293-.254.379");
}

.n2df3wmto {
  fill: var(--svg-color--b19e1e, #b19e1e);
  d: path("m15.202 36.714l-.126-.012a.08.08 0 0 1 0-.063a.35.35 0 0 1 .116-.116a.2.2 0 0 1 .097 0c.007.009.017.011.024.021c-.009.078 0 .162-.111.17");
}

.n2h1mm-qd {
  fill: var(--svg-color--726b44, #726b44);
  d: path("M20.09 17.989q.073-.074.154-.138c.072.017.15.007.207.07c-.016.042-.053.071-.089.099a.3.3 0 0 1-.089.051c-.061.017-.119.017-.174-.019c-.016-.013-.021-.032-.02-.039q.004-.026.011-.024");
}

.n2w_e7b6u {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("m14.418 30.02l-.002-.007c.009-.079.007-.161.063-.227c.029-.246.166-.043.25-.061c.037.036.078.066.117.107c.039.084.058.171.015.266c-.036.191-.065.385-.187.546a.12.12 0 0 1-.061.046a.11.11 0 0 1-.116-.015a.6.6 0 0 1-.139-.265a.95.95 0 0 1 .06-.39");
}

.n437lcbjv {
  fill: var(--svg-color--41413a, #41413a);
  d: path("M23.625 20.55c.058-.09.024-.24.16-.287a.52.52 0 0 0 .099.337c-.086 0-.17.004-.254.004c-.021-.012-.025-.022-.021-.041q.008-.013.016-.013");
}

.n4u2sldsp {
  fill: var(--svg-color--403e13, #403e13);
  d: path("M21.71 38.803c-.08-.009-.167.038-.232-.046c.084-.028.178-.111.232.046");
}

.n4x-r5boy {
  fill: var(--svg-color--636363, #636363);
  d: path("M25.02 31.1q-.029.038-.061.075c-.05-.075-.043-.156-.033-.236c.11.023.091.097.094.161");
}

.n599heb3u {
  fill: var(--svg-color--4d0303, #4d0303);
  d: path("M12.175 33.931c.039.086.023.191.098.266c.041.02.037.053.033.09c-.015.03-.037.056-.074.062c-.092-.124-.092-.272-.112-.424q.03-.026.055.006");
}

.n5mn7acac {
  fill: var(--svg-color--2b2b2b, #2b2b2b);
  d: path("m19.12 29.885l-.04-.047c-.088-.103-.006-.157.054-.222a.1.1 0 0 1 .074-.008a.19.19 0 0 1 .076.201c-.014.033-.032.04-.059.043q-.053.014-.105.033");
}

.n5zavng6d {
  fill: var(--svg-color--5b5b5b, #5b5b5b);
  d: path("M17.585 38.48a.4.4 0 0 0 .042.056q-.044.124-.089.24c-.111-.117.004-.199.047-.296");
}

.n66n2badu {
  fill: var(--svg-color--49380e, #49380e);
  d: path("M14.931 21.17c-.051.146.059.235.115.346c-.168-.028-.021.157-.121.181h-.027a.56.56 0 0 0-.129-.416c.074-.005.106-.077.162-.111");
}

.n6zdbmw0p {
  fill: var(--svg-color--fad528, #fad528);
  d: path("M24.07 37.547c.032-.035.071-.069.106-.103c.019-.021.037-.022.06-.022c.094.052.103.177.2.233c.029.02.057.045.076.078q.02.025.004.067c-.065.071-.157.019-.236.03c-.042.035-.145.008-.102.115c.051.064.102.137.168.194a.6.6 0 0 0 .199.173c.016.021.028.039.03.063c-.019.1-.116.119-.171.183a.12.12 0 0 1-.075.011c-.03-.019-.06-.039-.071-.078c-.004-.25-.295-.203-.375-.375c.074.158.318.131.358.33c.002.058.021.108.078.142c.067.058.036.12.006.181c.004.034.008.068-.015.098a.15.15 0 0 1-.092.03c-.051-.004-.104-.011-.146.025a.2.2 0 0 1-.053.034c-.063.035-.123.056-.189.016l-.056-.064a.4.4 0 0 1-.099-.281c-.002-.037-.008-.082-.012-.119c-.035-.073-.076-.153-.042-.244q0-.063-.004-.121c-.103-.122-.196-.247-.382-.174l-.014.004c-.033.023-.063.036-.101.025c-.043-.016-.073-.045-.112-.064a3 3 0 0 0-.186-.082c-.109-.105-.26-.143-.4-.201l.004.01q-.028-.032-.019-.07c.062-.083.062-.221.202-.238q.041 0 .072.012c.125.065.242.146.375.193c.017.006.031.016.041.021c.022.022.052.041.063.068c.003-.035-.038-.063-.018-.098c.018-.02.037-.039.062-.043c.109-.049.212.012.323.016c.187.01.361.107.543.025");
}

.n7s1vjk4e {
  fill: var(--svg-color--a1130e, #a1130e);
  d: path("m14.729 37.28l.002.084c-.02.045-.045.071-.09.082c-.058.019-.114.053-.157-.021a.3.3 0 0 1 .128-.145z");
}

.n8-7oib6e {
  fill: var(--svg-color--2e1718, #2e1718);
  d: path("M23.25 34.35h.058c.021.093.074.167.058.261h-.118c-.002-.09 0-.172.002-.261");
}

.n8-91eb0z {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v4h64v-4c0-6.075-3.373-11-10-11");
}

.n8ec20ahr {
  fill: var(--svg-color--eaeaea, #eaeaea);
  d: path("M18.892 29.469c.039-.071.082-.129.156-.158c.069-.104.133-.069.188.013c.046.121.01.221-.079.301c-.029.072-.055.14-.083.214c-.116.055-.128-.056-.179-.113c-.06-.088-.037-.171-.003-.257");
}

.n8rzw6btl {
  fill: var(--svg-color--601413, #601413);
  d: path("m21.291 29.881l.097.008q.05.07-.018.133c-.119.071-.251.056-.378.056c-.487.004-.97 0-1.457.004c-.271.004-.294.029-.294.304c-.006.681 0 1.36-.004 2.048c0 .125.018.259-.063.382c-.027.021-.057.028-.092.009c-.063-.086-.068-.182-.068-.276c0-.829-.01-1.657.008-2.482c.006-.047.01-.094.025-.138c.024-.055.064-.096.125-.105c.086.02.161.066.252.051h1.017q.108.001.214-.004c.073-.004.144 0 .211 0c.145-.014.281.022.425.01");
}

.n91r8q-8i {
  fill: var(--svg-color--4c4e4e, #4c4e4e);
  d: path("M12.539 30.3c.003.103.009.196.013.299c0 .063.067.147-.051.173c-.047-.109.051-.244-.063-.343c-.098-.043-.037-.114-.037-.185c.061-.02.1.014.138.056");
}

.natp48nfi {
  fill: var(--svg-color--452a28, #452a28);
  d: path("M24.25 20.08q.025-.112.053-.219c.08.098.084.176-.053.219");
}

.nb1a14_qe {
  fill: var(--svg-color--554910, #554910);
  d: path("M15.456 22.429v.054a5 5 0 0 1-.313.099c-.002-.023-.002-.051-.002-.074q.159-.041.315-.079");
}

.nb43t_bka {
  fill: var(--svg-color--393a3a, #393a3a);
  d: path("m20.866 29.838l.01.099h-.221c-.04-.04-.08-.074-.096-.128c-.004-.104-.123-.226.047-.304c.052.135.104.273.26.333");
}

.nb4jzybdb {
  fill: var(--svg-color--371007, #371007);
  d: path("M15.341 37.504c.019.071.049.163-.011.208c-.062.037-.099-.067-.147-.104c.009-.033.045-.037.063-.058l.004-.009c.024-.031.05-.058.091-.037");
}

.nc-s9bb1e {
  fill: var(--svg-color--472f30, #472f30);
  d: path("M17.292 25.37a.45.45 0 0 1-.229-.095c.095-.014.194-.034.229.095");
}

.ne4elyawu {
  fill: var(--svg-color--3b220a, #3b220a);
  d: path("M16.238 26.722v-.023c.005-.06.055-.063.096-.078c.062.021.116-.008.171-.032c-.039.14-.185.072-.267.133");
}

.neh2msb4j {
  fill: var(--svg-color--222424, #222424);
  d: path("M13.321 28.411a.4.4 0 0 0 .053.066c-.086.042-.042.146-.102.204q-.027.034-.049-.004c.046-.085-.056-.219.098-.266");
}

.nejxmnbaw {
  fill: var(--svg-color--272929, #272929);
  d: path("M19.767 29.731c.051-.162.056-.322.062-.482c.032-.012.06.005.085.019c.032.033.063.056.08.101c-.148.082-.104.231-.119.36a1 1 0 0 0-.108.002");
}

.nelum5_hy {
  fill: var(--svg-color--d2d3d6, #d2d3d6);
  d: path("M19.317 19.588c.029.108.143.22 0 .325c-.122-.051-.083-.151-.083-.248a.14.14 0 0 1 .083-.077");
}

.ngl4solrz {
  fill: var(--svg-color--a38d1b, #a38d1b);
  d: path("M24.402 37.704c.075-.063.062-.138.036-.217c.136.029.027.15.082.221c-.004.019-.008.029-.012.05a1 1 0 0 0-.106-.054");
}

.ngo8kjb3d {
  fill: var(--svg-color--312a0b, #312a0b);
  d: path("M21.495 21.544c-.035-.021-.074-.035-.109-.051c.01-.106.035-.197.16-.213c-.005.09-.076.174-.051.264");
}

.ngy3g0zzk {
  fill: var(--svg-color--595a5a, #595a5a);
  d: path("M13.578 34.03c.004.104.036.219-.051.316l-.022-.01q-.024-.016-.014-.049c-.012-.125-.023-.25.035-.367c.046.02.022.077.052.11");
}

.nh65xabgw {
  fill: var(--svg-color--fee62c, #fee62c);
  d: path("m22.274 36.706l-.057-.053c-.016-.014-.02-.021-.018-.039q.006-.02.014-.021c.041-.011.065.008.079.046q-.003.02-.002.037q-.004.012-.016.03");
}

.nhu-lbbni {
  fill: var(--svg-color--461515, #461515);
  d: path("M23.2 27.11h.047a.9.9 0 0 1-.145.444c-.058-.168.071-.3.098-.444");
}

.nip6xf8bm {
  fill: var(--svg-color--790b08, #790b08);
  d: path("M17.03 17.493c-.075-.016-.146-.047-.225-.016c.087-.129.161-.109.225.016");
}

.njglbqjte {
  fill: var(--svg-color--4d430f, #4d430f);
  d: path("M21.904 39.38c-.021-.193.062-.408-.122-.567c.059-.062.118-.112.177-.171c.003.249-.008.497.048.746q-.057.043-.103-.008");
}

.nlfvklbdn {
  fill: var(--svg-color--363838, #363838);
  d: path("M19.778 30.87q-.006.513-.008 1.024a1.64 1.64 0 0 1 .008-1.024");
}

.nlzfe8bdr {
  fill: var(--svg-color--412909, #412909);
  d: path("M24.775 37.39q-.136-.096-.271.004l-.014-.004a.06.06 0 0 1 .014-.061c.059-.074.141-.039.215-.054c.05.023.052.066.056.115");
}

.nmqvy88du {
  fill: var(--svg-color--573b3b, #573b3b);
  d: path("M21.956 33.794c.035-.094.038-.201.112-.271c.005.107.023.224-.112.271");
}

.nmz1us2mi {
  fill: var(--svg-color--646464, #646464);
  d: path("M19.04 41.594c-.015.021-.032.036-.047.056c-.067-.063-.085-.138-.046-.225c.067.04.071.111.093.169");
}

.nnkd2vlsf {
  fill: var(--svg-color--1e1010, #1e1010);
  d: path("M12.08 33.491c.062.08.041.178.052.272c.022.046 0 .062-.047.062c-.017-.086-.033-.181-.051-.271c.012-.024.012-.051.046-.063");
}

.nnrj4vv-w {
  fill: var(--svg-color--080704, #080704);
  d: path("M19.1 21.06c-.018-.017-.033-.026-.051-.044q.231-.15.254.125c-.063-.029-.112-.117-.203-.081");
}

.nom4_dbth {
  fill: var(--svg-color--3c1108, #3c1108);
  d: path("M22.11 39.9a1 1 0 0 1-.1.007q-.03.026-.059 0c.085-.074.055-.172.063-.263c.117.031.002.173.097.22q.031.014.021.028c-.006.008-.01.008-.022.008");
}

.noqp1acee {
  fill: var(--svg-color--422827, #422827);
  d: path("M19.04 27.575c-.01.104-.026.201-.097.282c-.06-.129.011-.207.097-.282");
}

.noyy6lbvr {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M23.353 32.884c0-.02.008-.037.01-.057c.089.07.042.17.053.256c-.086-.047-.022-.139-.063-.199");
}

.npjglt63b {
  fill: var(--svg-color--3f1308, #3f1308);
  d: path("M22.95 36.812c.085.053.146.119.15.23a.1.1 0 0 1-.058 0a.3.3 0 0 1-.11-.059a.2.2 0 0 1-.035-.056c-.016-.044-.031-.086-.004-.129c.023-.008.04-.008.057.014");
}

.nppcdrb7y {
  fill: var(--svg-color--3a0605, #3a0605);
  d: path("m11.933 31.34l-.008.062c-.113-.161-.052-.337-.041-.51q.017-.005.037-.004z");
}

.npymi25hi {
  fill: var(--svg-color--5a5a5a, #5a5a5a);
  d: path("M13.11 35.29c-.066-.104-.07-.207 0-.312z");
}

.nr0y36lst {
  fill: var(--svg-color--f5f6f6, #f5f6f6);
  d: path("M14.812 34.87c.199-.09.291-.334.527-.371c.078-.075.18-.098.282-.123c.091-.008.185.01.269-.047c.098.026.136.09.09.185l-.002.123a.07.07 0 0 1-.03.062c-.104.043-.218.021-.317.057c-.099.029-.209.029-.279.119c-.104.104-.164.244-.297.322c-.086.043-.179.01-.265.01c-.085-.039-.183-.047-.237-.137c.001-.184.182-.118.259-.2");
}

.nrf7-wr6g {
  fill: var(--svg-color--481707, #481707);
  d: path("m18.843 16.629l-.004-.075c.105-.016.23-.057.264.113c-.082-.043-.166-.073-.26-.038");
}

.nt7979uzu {
  fill: var(--svg-color--840906, #840906);
  d: path("M13.421 20.749q0 .115.004.229c-.131-.071-.156-.149-.004-.229");
}

.nt82f7bxf {
  fill: var(--svg-color--797972, #797972);
  d: path("M19.31 19.239q-.004.081-.012.164c-.039.004-.063-.009-.082-.043c-.076-.429-.029-.861-.024-1.293c0-.063.015-.146.114-.138c.037.043-.021.112.047.147l-.002.063c-.012.021-.021.031-.041.039z");
}

.ntcj6opho {
  fill: var(--svg-color--707072, #707072);
  d: path("m21.606 18.16l-.061-.104c.027-.076.055-.149.159-.146a.45.45 0 0 0-.073.235c-.007.006-.019.011-.025.015");
}

.nu3vzpbaa {
  fill: var(--svg-color--554343, #554343);
  d: path("M23.1 27.562a.6.6 0 0 1-.105.338c-.086-.149.012-.243.105-.338");
}

.nu8k99d-t {
  fill: var(--svg-color--423f15, #423f15);
  d: path("M15.884 38.803c-.082-.009-.17.038-.238-.046c.083-.018.182-.119.238.046");
}

.nukd8cd7b {
  fill: var(--svg-color--121212, #121212);
  d: path("M23.15 31.05c.025-.049.016-.165.115-.057l-.055.107c-.036.006-.053-.017-.06-.05");
}

.nvfkbv8hj {
  fill: var(--svg-color--43290e, #43290e);
  d: path("M22.58 19.811a3 3 0 0 0 0-.625c-.005-.09.042-.083.097-.056c.008.066.012.139.019.203c.03.182.034.354-.002.535c-.005.037 0 .084-.052.103c-.065-.038-.055-.101-.062-.16");
}

.nvojkccgj {
  fill: var(--svg-color--352222, #352222);
  d: path("M20.09 38.23c.1.004.201.042.297-.014c.011.111-.186.146-.104.283c-.1-.063-.144-.171-.193-.269");
}

.nvq7v4bwl {
  fill: var(--svg-color--626262, #626262);
  d: path("M19.364 40.842c.082.205.018.426.068.633c-.043.022-.084.05-.123.073l.002-.596c.034-.029.006-.082.053-.11");
}

.nwptsyujl {
  fill: var(--svg-color--695b0f, #695b0f);
  d: path("M22.01 20.844c.01-.06.133-.071.061-.161c.07-.027.133-.012.193.027c-.045.119-.145.134-.254.134");
}

.ny1tjczol {
  fill: var(--svg-color--2d2d2d, #2d2d2d);
  d: path("m15.655 35.495l.109.057l-.049.056q-.078.058-.16.009q-.031-.005-.043-.021c-.033-.036-.028-.073-.006-.106q.08-.052.149.005");
}

.ny30rccts {
  fill: var(--svg-color--181818, #181818);
  d: path("M23.821 29.737c.02 0 .033 0 .052-.006q.034.101.065.208l-.104.052a4 4 0 0 0-.013-.254");
}

.nym9qbz0r {
  fill: var(--svg-color--434444, #434444);
  d: path("M22.582 31.882c.085.016.14-.063.208-.08c.045.063.092.134 0 .201c-.042-.084-.172-.024-.208-.121");
}

.nyttg81ke {
  fill: var(--svg-color--192222, #192222);
  d: path("m17.695 25.639l-.004.11c-.056-.041-.13-.061-.158-.144c.066-.039.109.034.162.034");
}

.nzus4y5ho {
  fill: var(--svg-color--46463b, #46463b);
  d: path("M22.323 19.771c-.135-.047-.252-.177-.415-.083c-.034-.023-.04-.059-.038-.093c.02-.067.053-.106.126-.101c.095.129.22.17.37.147l.016.104c-.02.011-.039.016-.059.026");
}

.o_4zmdnqq {
  fill: var(--svg-color--6d5f11, #6d5f11);
  d: path("M18.513 18.651a.5.5 0 0 0 .013.244c-.144-.074-.158-.156-.013-.244");
}

.o_6xrvb0x {
  fill: var(--svg-color--5a5b5d, #5a5b5d);
  d: path("M13.44 19.657c-.074.08-.193.018-.27.084c.016-.043.032-.091.049-.134q.024-.038.053-.004c.062.007.129-.011.168.054");
}

.o-1gk6b-m {
  fill: var(--svg-color--312a0a, #312a0a);
  d: path("M18.737 21.321c-.041.088-.071.184-.161.237c.035-.093.03-.207.161-.237");
}

.o06_945gt {
  fill: var(--svg-color--f4f4f4, #f4f4f4);
  d: path("M23.667 31.806q.017-.06.036-.113q.018.04.035.086c.051.209-.026.43.043.633l.005.065c-.002.015-.002.021-.002.031c-.124-.013-.107-.104-.109-.19z");
}

.o0aqgtbqw {
  fill: var(--svg-color--feea2c, #feea2c);
  d: path("M22.321 36.76c-.016-.019-.031-.034-.047-.054l.007-.008a.04.04 0 0 0 .026-.012q.014.011.026.016q.015.036-.012.058");
}

.o1ll1gg5p {
  fill: var(--svg-color--7e0906, #7e0906);
  d: path("M20.72 41.38c-.008-.077-.012-.147-.017-.222c.005-.02.011-.033.019-.056c.053.097.07.185-.002.278");
}

.o2-bgcj8h {
  fill: var(--svg-color--7b0806, #7b0806);
  d: path("M20.466 35.25q-.005-.091-.013-.188c.142.057.151.121.013.188");
}

.o2g-4_meg {
  fill: var(--svg-color--221b1b, #221b1b);
  d: path("M16.709 39.436c.066.081.158.031.24.039c.051-.017.069 0 .063.056c-.047.063-.097.118-.146.188c.061-.16-.189-.142-.157-.283");
}

.o2hdwfefx {
  fill: var(--svg-color--cdb423, #cdb423);
  d: path("M24.757 37.552c-.035.004-.066.004-.102.006c-.141.029-.163-.054-.155-.168c.089-.109.183-.105.275-.004l-.005-.004c.063.066.103.126-.013.17");
}

.o2qy065_g {
  fill: var(--svg-color--efefef, #efefef);
  d: path("M17.03 17.493c.018.021.031.043.051.06a.24.24 0 0 1 .09.263a.22.22 0 0 1-.135.153a.3.3 0 0 1-.193.004a.44.44 0 0 1-.207-.161a.2.2 0 0 1-.008-.074a.4.4 0 0 1 .073-.201q.053-.033.104-.059c.083-.108.151-.032.225.015");
}

.o30hlqb7r {
  fill: var(--svg-color--1c1807, #1c1807);
  d: path("M15.255 38.807a.06.06 0 0 0 .036.006c.002.121.002.237.002.36h-.045z");
}

.o37t_kbxf {
  fill: var(--svg-color--0c0c0c, #0c0c0c);
  d: path("M20.457 29.936c-.004-.04-.004-.071-.004-.106c.058-.037.104 0 .158.01c.039.023.043.059.043.099q-.1-.004-.197-.003");
}

.o3i8tdrsp {
  fill: var(--svg-color--6b4b13, #6b4b13);
  d: path("M16.39 20.31a.4.4 0 0 0-.047-.307c.162.082.235.178.047.307");
}

.o3iidhbqk {
  fill: var(--svg-color--51290d, #51290d);
  d: path("m21.18 39.18l-.043-.061c.016-.078.035-.16.14-.172c-.03.08-.066.157-.097.233");
}

.o3k1y6aib {
  fill: var(--svg-color--5c5c5d, #5c5c5d);
  d: path("M20.243 31.3c-.15-.021-.111-.138-.1-.224c.022-.15-.067-.144-.164-.136c.035-.108.123-.118.205-.094c.09.019.058.108.06.172c.002.097-.001.189-.001.282");
}

.o3v1c0biq {
  fill: var(--svg-color--5b3132, #5b3132);
  d: path("M13.739 35.605h.042c0 .107-.063.191-.097.285c-.083-.112.001-.192.055-.285");
}

.o3x5l04tx {
  fill: var(--svg-color--502a2c, #502a2c);
  d: path("M19.817 35.767c.117.008.232.012.326.102c-.121.015-.247.026-.326-.102");
}

.o48gchb_k {
  fill: var(--svg-color--53320e, #53320e);
  d: path("M23.24 37.967c.207-.121.317-.021.382.174c-.141-.029-.209-.228-.382-.174");
}

.o4o7odbov {
  fill: var(--svg-color--151007, #151007);
  d: path("M22.371 40.18c-.088-.07-.176-.091-.269 0c-.071.047-.108.002-.141-.058v-.004q-.024-.023-.016-.043c.002-.017.009-.021.013-.021c.128-.083.279-.033.419-.063q.028-.008.063-.021c.021-.009.041-.009.061-.009c.174.1-.02.144-.027.209c-.033.036-.067.036-.103.01");
}

.o4pf8ub2n {
  fill: var(--svg-color--fadb2b, #fadb2b);
  d: path("M15.813 22.329q-.02.033-.045.055c-.106.023-.228.031-.33.079c-.1.009-.187.062-.283.075c-.088.02-.169.082-.26.022c-.047-.055-.008-.094.02-.142c.055-.039.118-.047.182-.059c.141-.039.26-.129.402-.173c.077-.022.156-.043.227-.086c.088-.013.182.037.272.021c.022-.021.046-.037.068-.056c.198-.004.392-.028.581-.099c.103-.012.207.011.312-.023c.039-.009.076-.023.113-.031c.119-.041.25.008.368-.057a.2.2 0 0 1 .115-.02c.104.039.211.016.316.023c.061 0 .118-.005.174.016c.354-.047.706-.041 1.061-.041c.029 0 .063 0 .093.005c.117.028.235.016.354.016h.219c.195.013.387.063.582.052a1 1 0 0 0 .098.004c.159.105.361.02.523.103c.123.051.254.035.375.079c.156.047.328-.008.48.07c.116.041.223.115.344.146c.107.063.254.037.346.134c-.002.039.072.059.019.102c-.131.092-.269.037-.399.018a.5.5 0 0 1-.188-.066c-.063-.035-.138-.047-.208-.07c-.105-.027-.21-.055-.322-.071c-.088-.007-.168-.047-.254-.051c-.124 0-.24-.058-.361-.05c-.053.002-.099.007-.146-.006a.4.4 0 0 0-.242-.053a.7.7 0 0 1-.199-.025c-.197-.055-.399 0-.598-.047c-.143-.047-.293-.024-.438-.028c-.299.013-.594-.036-.889-.022c-.166.008-.33-.021-.494.02c-.205.009-.408.009-.604.055c-.084.014-.167-.007-.252.018c-.062.016-.134.011-.198.039c-.131-.012-.261.039-.396.031q-.054.001-.107-.004c-.138.081-.282.089-.431.097");
}

.o4yj6s_sv {
  fill: var(--svg-color--5a2f0e, #5a2f0e);
  d: path("M20.813 18.338v-.052c.104-.004.197.023.265.106c-.099.027-.173-.036-.265-.054");
}

.o5hx_evlk {
  fill: var(--svg-color--9a9b9b, #9a9b9b);
  d: path("M19.951 27.944a1 1 0 0 0 .028-.105c.055.02.107.039.164.056c-.028.086.066.195-.055.263h-.006c-.063-.06-.14-.107-.131-.214");
}

.o7ilvcs6r {
  fill: var(--svg-color--212121, #212121);
  d: path("m18.13 28.05l-.013.199c.025.052-.008.063-.051.071c-.059-.039-.086-.09-.059-.168q0-.026.004-.063q.027-.02.059-.039z");
}

.o7qx2-ahw {
  fill: var(--svg-color--1d1e1d, #1d1e1d);
  d: path("M19 28.415h.046c.061.063.092.125.043.209v-.004c-.087.022-.109-.063-.166-.101q.04-.047.077-.104");
}

.o7v22obef {
  fill: var(--svg-color--5d5b41, #5d5b41);
  d: path("M13.566 19.704q.052-.001.112.004c-.016.053-.027.111-.043.162c-.125.004-.102-.086-.104-.162q.019-.005.035-.004");
}

.o82ssjzjm {
  fill: var(--svg-color--1c100f, #1c100f);
  d: path("M19.517 36.965v-.038l.195-.074q.03.04.059.074a5 5 0 0 0-.254.038");
}

.o8dh87b8i {
  fill: var(--svg-color--4e2727, #4e2727);
  d: path("M15.933 31.673c.002-.131.009-.26.013-.387c.007-.078-.037-.104-.106-.098c.157-.22.109-.476.1-.724c.062.404.071.805-.007 1.209");
}

.o9-qxbart {
  fill: var(--svg-color--2c2323, #2c2323);
  d: path("M22.412 35.97c-.099-.061-.108-.186-.183-.257c.016-.025.016-.065.051-.077c.07.044.137.089.207.127c-.187.008-.033.144-.075.207");
}

.o9us89bdf {
  fill: var(--svg-color--5a532d, #5a532d);
  d: path("M21.261 18.02c.094.014.189.02.287.031c.045.008.065.041.072.083c-.01.079.051.157-.002.239c-.113.078-.158-.026-.223-.09c-.048-.082-.147-.14-.134-.263");
}

.o9v5vb9af {
  fill: var(--svg-color--462827, #462827);
  d: path("M19.574 25.577c-.005.021-.005.041-.009.061c-.059-.02-.084-.091-.063-.114c.082-.086.188-.065.293-.038c-.052.08-.172.009-.221.091");
}

.oadv6ccwg {
  fill: var(--svg-color--5c5b5b, #5c5b5b);
  d: path("M12.386 32.528c-.045-.142-.074-.238.006-.393c.053.147.062.239-.006.393");
}

.oapu1rbwu {
  fill: var(--svg-color--180906, #180906);
  d: path("M24.07 37.547c-.183.157-.367.011-.548-.009c-.021-.008-.025-.016-.023-.03s.008-.022.012-.022c.189.001.365.093.559.061");
}

.obsqmwbwg {
  fill: var(--svg-color--642f2f, #642f2f);
  d: path("M12.591 27.305c-.023.103-.025.207-.096.293c-.023-.119-.052-.236.096-.293");
}

.obtvaxbgo {
  fill: var(--svg-color--1e1d1d, #1e1d1d);
  d: path("M19.522 29.29c-.002.021-.004.049-.008.072c-.061-.017-.051-.164-.158-.08c.004-.117.049-.217.154-.277c.052.093.066.189.012.285");
}

.oc-8x5bfg {
  fill: var(--svg-color--292929, #292929);
  d: path("M23.06 29.936c-.025.173.049.317.104.476a.1.1 0 0 1-.055.076a.2.2 0 0 1-.063.01c-.047-.01-.068-.045-.088-.084c.066-.125.027-.265.032-.394c-.022-.072.01-.088.07-.084");
}

.ocxuj8beo {
  fill: var(--svg-color--050505, #050505);
  d: path("M16.968 21.968v-.055c.061-.028.115-.057.174-.086c-.008.016-.002.022.009.035c.002.055-.044.074-.084.098a.5.5 0 0 0-.099.008");
}

.od-7qnbig {
  fill: var(--svg-color--0f1111, #0f1111);
  d: path("m19.642 37.34l.012.014l.011-.008c.07.027.084.087.097.148l-.017-.004l-.015.004c-.061-.029-.084-.086-.088-.154");
}

.od-844bvu {
  fill: var(--svg-color--505152, #505152);
  d: path("m20.356 29.02l-.012.083c-.145-.039-.145-.143-.115-.26c.02-.021.045-.021.066-.008c.061.052.061.119.061.185");
}

.od0-pzbpd {
  fill: var(--svg-color--690605, #690605);
  d: path("M12.02 32.725q0 .208-.004.416c-.058-.137-.078-.277.004-.416");
}

.od9la7bwv {
  fill: var(--svg-color--6f6f6e, #6f6f6e);
  d: path("M15.712 31.03c-.123 0-.082.109-.105.174c-.067.026-.117 0-.162-.047c-.02-.086.037-.135.083-.189c.043-.042.084-.083.147-.09c.051.037.037.097.037.152");
}

.oe3hyjbmf {
  fill: var(--svg-color--3c340c, #3c340c);
  d: path("M16.292 21.13c.09-.103.186-.156.32.02c-.215-.083-.209.095-.281.183c-.06-.062-.039-.136-.039-.203");
}

.oens0lz2l {
  fill: var(--svg-color--62380f, #62380f);
  d: path("M18.788 15.756c-.051-.021-.1-.043-.156-.017c-.027-.052-.005-.072.047-.08c.066-.002.113.02.109.097");
}

.oeqfoccrc {
  fill: var(--svg-color--6a6969, #6a6969);
  d: path("M12.5 33.35a.4.4 0 0 0 .05-.056c.037.052.055.104.037.17c-.025.031 0 .084-.046.104a.27.27 0 0 1-.041-.218");
}

.oes75jiop {
  fill: var(--svg-color--b19a1e, #b19a1e);
  d: path("M14.326 37.903c.082.036.167.019.25.006c-.024.095-.104.047-.157.063l-.105-.008z");
}

.ofd7cmm1a {
  fill: var(--svg-color--333, #333);
  d: path("M14.481 29.786c0 .082.006.166-.064.228c-.154-.083-.002-.151.008-.231c.016-.001.037.003.056.003");
}

.ofvzhublg {
  fill: var(--svg-color--282309, #282309);
  d: path("M19.569 21.905c.035-.031.066-.062.104-.084c.037-.009.068-.013.104-.021v.108q-.106.002-.208-.003");
}

.og9fyvbwl {
  fill: var(--svg-color--532d0e, #532d0e);
  d: path("m17.08 20.809l.047.004a.4.4 0 0 0 .043.269a.2.2 0 0 0-.043.043a.34.34 0 0 1-.047-.316");
}

.oge23j4vv {
  fill: var(--svg-color--c7c8c8, #c7c8c8);
  d: path("m17.529 29.728l.095.055c.023.063.041.131-.057.118c-.158-.02-.011-.119-.038-.173");
}

.ogg4m9b6r {
  fill: var(--svg-color--84752c, #84752c);
  d: path("M13.583 20c.082.048.049.119.047.188c-.014.023-.031.04-.059.04l-.04-.042l-.006-.118c.021-.025.041-.043.058-.068");
}

.oiw4odggw {
  fill: var(--svg-color--595958, #595958);
  d: path("M23.825 33.726c-.063-.154-.047-.32-.04-.484c.056-.021.075.016.095.051c-.004.095-.004.182-.004.274c-.041.041.012.122-.051.159");
}

.oj8d_7a3q {
  fill: var(--svg-color--60220d, #60220d);
  d: path("M15.987 21.76c-.021-.004-.036-.004-.053-.004c.024-.075.102-.157-.029-.212l.072-.11c.103.106.086.215.01.326");
}

.oj9tfabry {
  fill: var(--svg-color--5f5d54, #5f5d54);
  d: path("m23.576 19.819l-.007-.095q.048.024.1.047a.5.5 0 0 1-.002.401h-.063l-.033-.047l-.002.003c.049-.1.039-.204.007-.309");
}

.okleb4bke {
  fill: var(--svg-color--181813, #181813);
  d: path("M16.339 26.07c-.229-.083-.318-.303-.443-.483c.31.033.641-.066.924.199c-.189-.041-.307.056-.408.183c-.061.007-.03.077-.073.101");
}

.on98lkb5j {
  fill: var(--svg-color--3b2727, #3b2727);
  d: path("M15.974 36.34c-.015-.064-.03-.135-.047-.204a.07.07 0 0 1 .068-.013a.76.76 0 0 1 .271.371a.1.1 0 0 1-.029.064c-.09-.025-.111-.146-.215-.159c-.048.005-.071-.006-.048-.059");
}

.oo8fsgb9e {
  fill: var(--svg-color--222121, #222121);
  d: path("M17.228 29.26h-.046c-.043-.122.06-.161.127-.227a.07.07 0 0 1 .063.013l.01.212c-.052-.034-.104-.055-.154.002");
}

.oocvj9b6p {
  fill: var(--svg-color--e4e5e5, #e4e5e5);
  d: path("M18.937 28.06c.025-.003.048-.012.076-.016q.048-.032.102.004q.026.053.02.104c-.023.104-.058.194-.09.288a.23.23 0 0 1-.105.109a.2.2 0 0 1-.08-.004c-.059-.059-.07-.114-.008-.174c.061-.095.118-.188.085-.311");
}

.op5d61b5h {
  fill: var(--svg-color--352e0b, #352e0b);
  d: path("m22.747 36.977l-.011.091a.23.23 0 0 1-.151-.152a.02.02 0 0 0-.004-.027c.038-.05.078-.02.117 0a.11.11 0 0 1 .049.088");
}

.oper2n_en {
  fill: var(--svg-color--595959, #595959);
  d: path("M19.894 38.626a.7.7 0 0 1 .084.287a.1.1 0 0 1-.067.021c-.095-.046-.112-.133-.099-.229c.014-.042.037-.071.082-.079");
}

.opgk7pbtg {
  fill: var(--svg-color--050401, #050401);
  d: path("M14.485 37.426q.078.013.158.022c-.059.03-.111.068-.17.104c-.056.031-.06 0-.051-.044a1 1 0 0 1 .063-.082");
}

.opou4sbfu {
  fill: var(--svg-color--292407, #292407);
  d: path("M21.769 25.932c-.073.013-.131-.008-.129-.065c.008-.106.117-.08.184-.106c.041-.019.092-.019.092.047c.002.107-.088.107-.147.124");
}

.oriaw-alp {
  fill: var(--svg-color--2b2c2c, #2b2c2c);
  d: path("M12.5 33.35a10 10 0 0 1-.049-.349c.116.107.086.207.099.293c.021.06-.006.07-.05.056");
}

.orz3lybfw {
  fill: var(--svg-color--3f360d, #3f360d);
  d: path("M21.386 22.07q.002.023.002.047c-.136-.043-.289.043-.418-.047q-.001-.03.004-.052c.051-.086.14-.022.209-.063c.065.043.135.078.203.115");
}

.os13aehhv {
  fill: var(--svg-color--352309, #352309);
  d: path("M24.4 38.542q.033 0 .069.008l-.104.207q-.032.045-.056-.006c.045-.055.022-.103-.029-.141c.006-.043.041-.046.068-.062a.3.3 0 0 1 .052-.006");
}

.oscqbqz6j {
  fill: var(--svg-color--44130d, #44130d);
  d: path("M21.384 29.997q0-.058.004-.108l.047-.062c.039.043.035.086.009.133c.049.131-.056.279.063.394c.023.251-.016.511.062.763a.2.2 0 0 1-.021.073c-.089.192.008.386-.002.577c-.002.057-.027.105-.033.165c-.012.229.008.455.015.687c-.046.069.014.258-.181.16c-.051-.111-.045-.225-.047-.334q-.003-1.036.002-2.066c.002-.132-.017-.269.082-.382");
}

.osjmhxttr {
  fill: var(--svg-color--191818, #191818);
  d: path("M22.331 33.868c.083.043.102.144.15.215c.025.027.02.045-.016.045a.3.3 0 0 1-.134-.26");
}

.ot9lr7b5a {
  fill: var(--svg-color--3b3b3b, #3b3b3b);
  d: path("M21.33 35.34c.16.008.28.111.431.148c-.021.049-.065.057-.108.053c-.041.023-.128-.113-.114.042c-.143-.021-.126-.177-.209-.243");
}

.ovfy7abnk {
  fill: var(--svg-color--322108, #322108);
  d: path("M15.09 22.337v.037l-.146.07c-.071-.07.039-.059.039-.095c.037-.003.072-.003.107-.012");
}

.ovg37zpqj {
  fill: var(--svg-color--242424, #242424);
  d: path("M21.699 30.411h.058c.145.017.15.039.072.25q-.03.035-.068.015c-.066-.079-.066-.175-.062-.265");
}

.ovh13qbmg {
  fill: var(--svg-color--5b5c5c, #5b5c5c);
  d: path("M25.03 31.907c0 .135.002.27.004.396c-.107-.127-.023-.263-.004-.396");
}

.ovnafdb_r {
  fill: var(--svg-color--242727, #242727);
  d: path("M13.11 36.23c.021.023.043.042.063.067c0 .068-.009.144-.06.197c-.017.022-.029.028-.041 0c.034-.083-.059-.181.038-.264");
}

.ovzhilbka {
  fill: var(--svg-color--545454, #545454);
  d: path("M13.728 27.22c-.023.016-.053.028-.08.047c.017-.062-.055-.157.017-.177c.078-.024.07.072.063.13");
}

.owexfyogz {
  fill: var(--svg-color--242525, #242525);
  d: path("M23.519 33.931a.9.9 0 0 1 .059.355c.023.057-.001.061-.045.053c.023-.137-.139-.264-.014-.408");
}

.owot6wbjm {
  fill: var(--svg-color--292d2d, #292d2d);
  d: path("M14.3 18.542c.02.004.037.012.059.012c.021.09.042.173.061.262a.07.07 0 0 1-.063.008a.36.36 0 0 1-.113-.25l.021-.027c.01-.005.025-.009.035-.005");
}

.oxfx64b9c {
  fill: var(--svg-color--542c0e, #542c0e);
  d: path("M16.272 39.12c-.018.045-.027.082-.039.111c-.035-.1-.071-.195-.104-.299c.1.028.13.106.143.188");
}

.oxivalb-b {
  fill: var(--svg-color--4c2209, #4c2209);
  d: path("M14.634 40.33h.039c.057.033.104.076.112.149c-.085-.014-.13-.069-.151-.149");
}

.oyzmxfaib {
  fill: var(--svg-color--432a2a, #432a2a);
  d: path("m18.1 41.489l.06.307c-.137-.061-.11-.186-.114-.299l.023-.031q.013.012.031.023");
}

.oz2uyz6fs {
  fill: var(--svg-color--282929, #282929);
  d: path("m18.415 37.806l-.051-.057c.027-.09-.047-.225.111-.254c-.021.102-.04.209-.06.311");
}

.oz336zbhh {
  fill: var(--svg-color--484949, #484949);
  d: path("M13.02 35.987c-.01.086.017.176-.047.252q-.039.033-.072-.004c.023-.123.043-.244.068-.363c.095 0 .062.06.051.115");
}

.p_qrgzeel {
  fill: var(--svg-color--2d0605, #2d0605);
  d: path("M15.665 40.41v-.185c.026-.013.075-.041.079-.008a.2.2 0 0 1-.079.193");
}

.p_ss3g0_q {
  fill: var(--svg-color--716313, #716313);
  d: path("M18.839 17.605q-.135-.001-.264-.008c-.016-.013-.021-.022-.016-.036c.008-.006.012-.015.018-.015c.102-.038.207-.1.262.059");
}

.p-4200rfm {
  fill: var(--svg-color--fdd628, #fdd628);
  d: path("m15 22.79l-.007-.127c.004-.082.063-.104.121-.133q.157-.059.316-.105c.099-.02.201-.04.295-.086a.2.2 0 0 1 .098-.032c.15 0 .29-.026.422-.104q.054-.018.105-.012c.152.04.299-.047.447-.031a.7.7 0 0 0 .191-.035a1 1 0 0 1 .21-.021c.248-.026.493-.071.744-.05h.265c.153.016.317-.04.459.055c.063.109-.05.133-.09.191a1 1 0 0 1-.083.072c-.082.061-.181.084-.272.125q-.026.018-.021.045q.008.02.021.018c.08.043.164.074.24.125c.084.076.227.109.176.275c-.153.141-.365.031-.535.109c-.154.031-.313.02-.471.02c-.103 0-.205-.012-.307.027c-.092.026-.188.022-.283.035c-.14-.017-.271.043-.41.039a.4.4 0 0 0-.16.036c-.041.013-.084.028-.129.032c-.091 0-.177.027-.269.031a1.1 1.1 0 0 0-.384.115a.4.4 0 0 1-.067.016a.38.38 0 0 0-.25.074c-.054.021-.106.009-.161.027c-.177.023-.253-.042-.207-.229c.023-.043.063-.07.1-.103c.043-.032.086-.071.125-.108c.051-.067.045-.118-.043-.149c-.066-.037-.157-.048-.186-.142");
}

.p-jb-9qmg {
  fill: var(--svg-color--191818, #191818);
  d: path("M17.316 37.444c.012.092-.05.152-.093.223c-.05-.109.028-.163.093-.223");
}

.p-vdw3bzv {
  fill: var(--svg-color--1f1f1f, #1f1f1f);
  d: path("M23.894 33.971c-.018.056-.033.104-.051.155c-.008-.133-.011-.264-.019-.4l.052-.159q.01.198.018.404");
}

.p0g2zn8_g {
  fill: var(--svg-color--5a5011, #5a5011);
  d: path("M15.304 39.854q-.13.12-.26 0z");
}

.p0riuvzxe {
  fill: var(--svg-color--ebecec, #ebecec);
  d: path("M18.214 27.79c.035.078.094.146.031.24c-.09-.059-.098-.162-.146-.24c-.107-.112-.142-.231-.047-.373c.017-.034.006-.086.06-.105c.017.008.032.021.047.027c0 .154.087.295.055.451");
}

.p0utwzucu {
  fill: var(--svg-color--2a2508, #2a2508);
  d: path("m14.573 37.88l.004.029c-.084.045-.168.058-.25-.006a.21.21 0 0 1 .208-.063c.009.012.027.026.038.04");
}

.p0xqnr68s {
  fill: var(--svg-color--474747, #474747);
  d: path("m13.421 35.08l-.095.436c-.125-.143.047-.285 0-.428c.011-.02.022-.026.043-.034q.034.005.052.026");
}

.p1-qdl_7z {
  fill: var(--svg-color--3d3e3e, #3d3e3e);
  d: path("M19.1 28.663c-.045.074-.008.221-.16.216c.069-.063.011-.216.16-.216");
}

.p1cl86osg {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("M21.959 35.907c-.054-.095-.098-.197-.208-.25c-.061-.148.057-.123.131-.131c.112.063.277-.037.36.117q.095.161.171.326c.005.084.014.165.018.243c-.013.093-.071.11-.146.11a.46.46 0 0 1-.258-.11c-.061-.09-.046-.202-.068-.305");
}

.p2_qirxkd {
  fill: var(--svg-color--50200f, #50200f);
  d: path("M19.412 19.398c-.062-.043-.053-.104-.058-.165c0-.259.009-.519-.004-.777c-.006-.17.05-.248.222-.213c-.129.037-.183.114-.177.264c.019.298.014.592.017.891");
}

.p24s8kb9l {
  fill: var(--svg-color--2e2f2f, #2e2f2f);
  d: path("M14.431 33.15c-.041.119.039.276-.113.356c.011-.096.027-.189.041-.288c-.026-.082.012-.082.072-.068");
}

.p2d_30_kq {
  fill: var(--svg-color--2a1a08, #2a1a08);
  d: path("m24.05 38.911l.002.16c-.019.021-.033.021-.054 0c-.071-.004-.13-.025-.162-.1z");
}

.p2mp-nb2h {
  fill: var(--svg-color--2f1311, #2f1311);
  d: path("M23.938 20.661c.086-.032.171-.061.261-.097c-.002.114-.123.11-.166.187q-.016.031-.052.022c-.037-.03-.066-.063-.043-.112");
}

.p2rfsenpg {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M13.535 36.25c-.002.035-.005.063-.005.099c-.051.063-.004.142-.038.209c-.13.127-.161.021-.192-.086c-.004-.056.012-.113.018-.173c.011-.079.033-.149.027-.232a.2.2 0 0 1 .015-.066a.66.66 0 0 0 .085-.293a.3.3 0 0 1 .018-.067c.059-.101.074-.207.109-.312a.7.7 0 0 0 .033-.193q0-.037.013-.069a.6.6 0 0 0 .067-.261a.5.5 0 0 1 .024-.105c.081-.125.084-.271.114-.412c.002-.047.01-.103.018-.153c.036-.167.08-.337.064-.515a.3.3 0 0 1 .014-.11c.061-.104.068-.22.092-.326c.043-.132.012-.272.043-.397c.045-.121.023-.248.051-.361c.049-.135.027-.271.037-.408a.4.4 0 0 1 .033-.109a.14.14 0 0 1 .098-.052c.131.04.173-.142.301-.121c.063.05.064.13.068.207c.014.15-.076.3-.029.455a.43.43 0 0 1-.04.224c-.045.094-.052.209-.104.303l-.039.06c-.037.042-.099.08-.062.155a.5.5 0 0 1 .034.096c.004.098-.026.186-.034.28c0 .024-.008.048-.013.073c-.029.076-.029.164-.051.242c-.031.109-.056.22-.086.32c-.004.029-.013.049-.021.075c-.06.163-.062.351-.204.479c-.036.067-.012.146-.023.219c-.047.117-.062.248-.104.365c-.07.097-.039.222-.104.313c-.017.105-.108.188-.078.301q-.021.006-.021.025c-.093.078-.053.225-.128.321");
}

.p2x_m6izf {
  fill: var(--svg-color--3c3722, #3c3722);
  d: path("M18.892 18.467c-.004-.077-.015-.164.051-.231c.038.093.027.169-.051.231");
}

.p3jouy65a {
  fill: var(--svg-color--3e3f3f, #3e3f3f);
  d: path("m15.509 35.97l-.051.052q-.021.005-.045.004c.02-.09-.016-.225.148-.213a3 3 0 0 1-.052.157");
}

.p4macqb_r {
  fill: var(--svg-color--665912, #665912);
  d: path("M21.341 39.12c.023-.068.06-.127.162-.123c.01.098-.089.115-.115.18a.1.1 0 0 1-.047-.057");
}

.p539njbwu {
  fill: var(--svg-color--fbfbfb, #fbfbfb);
  d: path("M19.606 41.653c-.055-.06-.115-.117-.174-.179c-.151-.185-.026-.401-.086-.603c-.026-.099.013-.203-.06-.289c-.008-.105 0-.226-.026-.33c-.006-.075.026-.135.049-.197c.056-.098.031-.262.205-.262c.066.055.066.137.095.212c.021.067.03.146.056.217c.055.134.057.283.137.416q.026.045.021.104a.5.5 0 0 0 .014.27c.045.18-.043.355-.037.539c-.031.095-.053.208-.194.102");
}

.p5ul-cc8m {
  fill: var(--svg-color--2c2c2c, #2c2c2c);
  d: path("M23.62 34.51c.16.137.08.354.16.519c-.2.004-.061-.185-.143-.26c-.063-.056-.076-.163-.067-.263q.027-.038.05.004");
}

.p70z6xy6t {
  fill: var(--svg-color--5e5e5d, #5e5e5d);
  d: path("M19.05 37.745c.096.209-.002.427.058.634h-.086c-.009-.173-.052-.347-.021-.521c.027-.033 0-.089.049-.113");
}

.p8i1_nopz {
  fill: var(--svg-color--343535, #343535);
  d: path("M20.14 31.882c.065-.006.053-.08.098-.104c.014.078.041.18-.069.176c-.077 0-.223.041-.217-.133l-.004.004c.063.021.126.037.192.057");
}

.pa1a9ybqf {
  fill: var(--svg-color--2c2c2c, #2c2c2c);
  d: path("M13.429 27.892h.104l-.06.313c-.073.106.057.271-.086.362c-.002-.026-.011-.058-.015-.09c-.021-.021-.049-.028-.053-.067c-.05-.187.114-.333.11-.518");
}

.pa26eeojp {
  fill: var(--svg-color--393a3a, #393a3a);
  d: path("M19.308 27.413c.054-.067.002-.135-.004-.2l.16-.06c.035.037.033.084.057.125c.031.041.086.051.111.1c.006.048-.021.082-.058.109c-.078.039-.089.114-.112.186c-.025.074-.025.18-.15.16c-.049-.141.113-.281-.004-.42");
}

.pa91reufw {
  fill: var(--svg-color--756714, #756714);
  d: path("M18.315 21.751c.244.094.488.072.736.022c.074-.042.145-.042.207.028c-.016.043-.056.047-.091.066c-.385.065-.774.02-1.163.03c0-.043.008-.075.059-.043c.098 0 .174-.056.252-.103");
}

.pahj0lkhg {
  fill: var(--svg-color--2d2e2e, #2d2e2e);
  d: path("M13.167 33.24a1 1 0 0 1-.095.049c-.056-.119.095-.226.034-.348c-.02-.058.005-.068.057-.064c.012.119.036.246.004.363");
}

.papqkyb9e {
  fill: var(--svg-color--454646, #454646);
  d: path("M15.04 30.768c.006.108-.078.079-.123.063c-.05-.017-.082-.061-.035-.123c.051.025.09.089.158.06");
}

.pauyaacax {
  fill: var(--svg-color--252727, #252727);
  d: path("M13.325 36.29c-.004-.08-.002-.153.051-.211c.116.07-.012.138-.007.211q-.023.038-.044 0");
}

.pb1lzfhkg {
  fill: var(--svg-color--2b1917, #2b1917);
  d: path("M17.318 32.08q.033.026.062.043c-.064.01-.132.017-.193.023q-.031-.015-.061-.035c.062-.013.129-.017.192-.031");
}

.pbo8zm4aw {
  fill: var(--svg-color--635c37, #635c37);
  d: path("M23.468 19.233c-.162.029-.226-.105-.313-.201c-.021-.019-.019-.047.008-.062c.065.007.138.011.203.021c.083.015.067.094.099.146c-.001.028.003.057.003.096");
}

.pbxgwderu {
  fill: var(--svg-color--171818, #171818);
  d: path("M25.08 34.24c-.014-.041-.033-.138-.018-.123c.162.119.111-.076.162-.105c-.004.098.043.203-.032.295a.14.14 0 0 1-.074-.023z");
}

.pc-n2pect {
  fill: var(--svg-color--3e3b31, #3e3b31);
  d: path("M20.09 17.989v.031c-.07.09-.16.083-.26.055c-.064-.031-.093-.078-.066-.152h.01c.029-.004.062-.008.089-.016c.092-.029.14.092.227.082");
}

.pcf10qbsw {
  fill: var(--svg-color--2f3030, #2f3030);
  d: path("M20.243 28.633a.7.7 0 0 1-.096-.318h.041q.086.119.058.255z");
}

.pcmb12b-c {
  fill: var(--svg-color--393e40, #393e40);
  d: path("M25.07 35.08h-.041a.46.46 0 0 1 .041-.271z");
}

.pdq47lb4w {
  fill: var(--svg-color--4d3a3b, #4d3a3b);
  d: path("M16.808 30.991c.02-.097.039-.194.149-.194c.074 0 .106.063.104.142q-.026.034-.053 0c-.093-.104-.128.06-.2.052");
}

.peq0n9bff {
  fill: var(--svg-color--3a2121, #3a2121);
  d: path("M20.976 29.663a.5.5 0 0 1-.269-.277c.127.058.23.138.269.277");
}

.peuefybtt {
  fill: var(--svg-color--321b1b, #321b1b);
  d: path("M16.952 31.46c.143.127.166.281.104.443c-.047.127-.129.148-.197.004c.225.031.146-.138.146-.234c.002-.078-.098-.124-.09-.213q.02-.024.037 0");
}

.peuiumbaz {
  fill: var(--svg-color--531816, #531816);
  d: path("M20.89 41.07c.08-.053.162.075.237-.013c.028.034.056.077-.002.104c-.103.036-.169-.026-.235-.091");
}

.pf07uqvff {
  fill: var(--svg-color--5b4f11, #5b4f11);
  d: path("M19.294 21.552q.03 0 .063-.008a.4.4 0 0 1 .309 0c-.124.095-.245.074-.372.008");
}

.pf19phb4l {
  fill: var(--svg-color--2e3030, #2e3030);
  d: path("M16.226 17.605c.006.106.012.205.021.312q.023.045-.02.08c-.094-.094-.002-.241-.094-.334c-.018-.013-.021-.021-.018-.032q.007-.024.016-.023q.048-.004.095-.003");
}

.pgj5s131j {
  fill: var(--svg-color--3f3f3e, #3f3f3e);
  d: path("M23.767 29.489c-.106-.166-.047-.375-.146-.531c-.027-.039-.025-.084.005-.117c.026.016.054.027.083.046q.034-.033.07-.013c.045.16.055.33.082.496c-.008.056-.032.103-.094.119");
}

.pgt7eacjv {
  fill: var(--svg-color--e7e8e9, #e7e8e9);
  d: path("M13.794 20.554c-.059-.031-.103-.074-.103-.145v.008c-.036-.071-.054-.149-.091-.217c-.021-.066-.014-.129-.019-.197c.019-.043.036-.09.054-.133c-.045-.056-.009-.114 0-.17c.006-.074.049-.134.078-.19c.034-.079.09-.134.15-.194c.039-.033.085-.074.133-.109a.14.14 0 0 1 .07-.016a.13.13 0 0 1 .097.04c.026.071-.014.114-.062.157q-.055.059-.114.109c-.05.07-.113.138-.151.22c-.02.043-.027.086-.037.13c-.022.1.002.195.027.294l.027.063c.037.078.089.151.132.23c.067.128.2.216.271.346c.039.075.069.149.055.232c-.012.063-.043.102-.103.109l-.053-.067c.013-.09-.077-.122-.116-.188c-.043-.133-.104-.25-.245-.312");
}

.phhescbxy {
  fill: var(--svg-color--2a2b2b, #2a2b2b);
  d: path("M17.742 40.44h-.044c.011-.067-.04-.179.103-.153c-.023.048-.04.101-.059.153");
}

.phuxxrbjf {
  fill: var(--svg-color--383838, #383838);
  d: path("M14.308 33.817h-.057c.012-.092-.005-.188.063-.263c.111.091-.028.177-.006.263");
}

.pie6u3bhz {
  fill: var(--svg-color--3e3d18, #3e3d18);
  d: path("M14.524 19.12c.08-.152.217-.148.355-.141c.02.012.025.036.03.055a.11.11 0 0 1-.06.076a.23.23 0 0 1-.127.021c-.064-.007-.131-.007-.198-.011");
}

.pjas32btq {
  fill: var(--svg-color--313131, #313131);
  d: path("M17.837 28.16q.026.029.055.049c.103.076.125.174.088.293c-.018.027-.038.031-.068.02c-.026-.12-.1-.229-.075-.362");
}

.pjjpkcb_y {
  fill: var(--svg-color--383a3a, #383a3a);
  d: path("M24.308 34.979a.21.21 0 0 1 0 .256z");
}

.pjle0moxi {
  fill: var(--svg-color--432d2d, #432d2d);
  d: path("M24.15 36.706c.015-.004.027 0 .037 0c.041 0 .084-.049.127.004c.039.022.041.058.039.104c-.083-.002-.199.056-.203-.108");
}

.pkg5nwb7t {
  fill: var(--svg-color--51210d, #51210d);
  d: path("M22.737 40.33h.043c-.047.066-.055.217-.202.111z");
}

.pko-dpafc {
  fill: var(--svg-color--222323, #222323);
  d: path("M14.78 30.11q.028.078.061.156q.001.123.006.24c-.021.148-.104.166-.224.117c.089-.157.201-.307.118-.51l.016-.004z");
}

.pl4amcc9r {
  fill: var(--svg-color--1e2323, #1e2323);
  d: path("M18.729 40.911h.047c.02.06.035.121.055.184c-.13-.012-.086-.114-.102-.184");
}

.plzxtulna {
  fill: var(--svg-color--302626, #302626);
  d: path("M20.36 30.938h.042v.313c-.108-.088-.065-.203-.042-.313");
}

.poa8uqb1c {
  fill: var(--svg-color--44211e, #44211e);
  d: path("M16.04 32.821q1.113-.001 2.222.004h.055c-.051.116-.15.051-.225.051c-.685.009-1.369.009-2.052.013c-.007-.013-.015-.017-.022-.022q.006-.014.008-.027z");
}

.pp4awyb2u {
  fill: var(--svg-color--7c0f0c, #7c0f0c);
  d: path("m22.693 19.87l.002-.535a.68.68 0 0 1-.002.535");
}

.pphchom4m {
  fill: var(--svg-color--262626, #262626);
  d: path("M25.491 31.28a.5.5 0 0 0 .018.094c-.065.074-.053.166-.063.252q-.023.037-.042-.004c.013-.131-.074-.235-.108-.356c.064-.011.116.16.195.014");
}

.ppkzmsbvl {
  fill: var(--svg-color--f8d528, #f8d528);
  d: path("M15.04 38.19c.115-.129.204-.129.26.046c.041.127.178.209.16.358c.031.19.098.376.061.577c-.016.076-.043.154-.047.238a1 1 0 0 1-.031.11a1.1 1.1 0 0 0-.102.308a.3.3 0 0 1-.045.056a.3.3 0 0 1-.213.012a.1.1 0 0 1-.039-.06c0-.038-.008-.075-.05-.096c-.052-.096-.032-.209-.093-.307a.5.5 0 0 1-.034-.197a1 1 0 0 0-.036-.273a.23.23 0 0 1 .025-.151c.004-.1.039-.187.068-.276c.014-.008.016-.021.014-.029c-.001-.12.062-.215.102-.316");
}

.pppccm__m {
  fill: var(--svg-color--3f2424, #3f2424);
  d: path("M22.783 35.13a.4.4 0 0 0 .076.008c-.048.057-.104.072-.173.088c-.02-.016-.039-.027-.059-.042a2 2 0 0 1 .156-.054");
}

.pprso5zoq {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M15.05 35.932c.032-.071.068-.149.1-.215c.021-.085.06-.149.15-.171a.5.5 0 0 1 .197.004a.3.3 0 0 1 .066.035c.072.065-.006.14.002.203v.023c-.086.042-.088.148-.148.211c-.02.057.004.127-.059.167c-.11.103-.234.095-.365.042c-.029-.109.043-.197.057-.299");
}

.pq2hg6bpx {
  fill: var(--svg-color--191818, #191818);
  d: path("M20.331 37.857h-.02l-.02.009c-.064-.061-.083-.136-.091-.224c.077.058.11.132.131.215");
}

.pq6lg9yhm {
  fill: var(--svg-color--53470f, #53470f);
  d: path("M24.2 38.835v.074c-.056-.035-.108-.043-.16.004c-.012-.156.069-.127.16-.078");
}

.pq8tmuphs {
  fill: var(--svg-color--331e09, #331e09);
  d: path("M14.818 38.801q.031.001.067.008v.151q-.024.033-.043 0c.006-.08-.076-.103-.113-.147v-.054c.028.017.059.027.089.042");
}

.pqkm5lbdc {
  fill: var(--svg-color--9c891a, #9c891a);
  d: path("m14.772 19.969l.051-.056c.125.043.133.141.131.25c-.016.041-.038.065-.081.074a.42.42 0 0 1-.101-.268");
}

.pqrk3ybrm {
  fill: var(--svg-color--331208, #331208);
  d: path("M15.925 26.589c.135-.043.267-.114.416-.118c.031.11-.074.071-.109.104c-.105-.02-.2.112-.307.014");
}

.pqwgh83iv {
  fill: var(--svg-color--521412, #521412);
  d: path("M16.287 41.06c.058.076.118-.014.179 0c-.031.076-.082.132-.168.103c-.056-.026-.043-.068-.011-.103");
}

.pr4xvyabj {
  fill: var(--svg-color--180e0e, #180e0e);
  d: path("M13.366 39.07c.014-.07.023-.146-.036-.205c.114-.021.146.184.278.098a.23.23 0 0 1-.188.111c-.019.022-.034.016-.054-.004");
}

.prhfhzu4u {
  fill: var(--svg-color--686765, #686765);
  d: path("M24.397 31.979c.018.02.037.035.053.055a.2.2 0 0 1-.043.183c-.103-.077-.049-.16-.01-.238");
}

.ps276ibit {
  fill: var(--svg-color--272727, #272727);
  d: path("M24.358 29.61q-.011.03-.027.066c-.008-.01-.025-.016-.025-.023c-.006-.068-.018-.134.041-.185z");
}

.psaxjdbmp {
  fill: var(--svg-color--593b3a, #593b3a);
  d: path("M15.513 34.37c.035.01.074.021.108.029c-.094.037-.188.063-.282.098c.008-.106.094-.113.174-.127");
}

.pst57xbzs {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M18.58 39.663c-.056.057-.112.104-.104.19c-.049.084-.08.175-.157.241c0 .012.004.029.005.042c-.111.119-.18.048-.238-.06c-.063-.104-.07-.229-.098-.346c-.006-.244 0-.486-.002-.729l.002-.172a.44.44 0 0 1 .068-.235c.056-.071.121-.129.188-.188c.1-.067.16-.021.221.061c.066.097.121.201.156.313a.55.55 0 0 1 .016.569c.003.111-.068.21-.057.314");
}

.pt2a6kbca {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M20.243 31.3c.053.062.016.133.003.196c-.112.111 0 .285-.104.397c-.076.017-.15.032-.188-.062c-.066-.303-.107-.605.032-.899l-.007.008c.131-.079.191-.021.209.109c.011.088-.013.179.055.251");
}

.pt7w5ub_p {
  fill: var(--svg-color--605412, #605412);
  d: path("M21.81 22.22c.052-.047.152-.04.149-.146c.113.035.13.156.21.221q.003.017.002.029a.6.6 0 0 1-.361-.104");
}

.pu_6b5b7p {
  fill: var(--svg-color--787877, #787877);
  d: path("M24.462 35.983c-.146.004-.105-.096-.104-.171c.031-.034.006-.085.052-.104c.056.08.054.18.052.275");
}

.puch3nb_q {
  fill: var(--svg-color--353737, #353737);
  d: path("m21.906 35.567l.001-.056c.074 0 .146-.004.223-.004c.053-.035.064.022.092.042c.06.004.053.048.06.086c-.017.029-.035.052-.052.077c-.03-.237-.249-.024-.324-.145");
}

.puj6qckaz {
  fill: var(--svg-color--6c5d2f, #6c5d2f);
  d: path("M19.783 18.239q-.032-.044-.062-.095c.039-.013.08-.032.119-.043c.071-.062.158-.047.24-.04c.035.016.063.04.068.083c.105.086.256 0 .361.086c-.09.056-.187.04-.283.009z");
}

.pv64j4arn {
  fill: var(--svg-color--eed829, #eed829);
  d: path("M15.14 20.671a.1.1 0 0 1-.014.035c-.072-.004-.099-.039-.072-.108q.042.033.086.073");
}

.pwcsngb1o {
  fill: var(--svg-color--f0f1f1, #f0f1f1);
  d: path("M20.325 17.557c.176-.206.301-.047.438.065c.084.088.055.174-.013.256a.3.3 0 0 1-.142.086a.3.3 0 0 1-.157.005c-.075-.024-.155-.033-.216-.091a.4.4 0 0 1 .023-.275a.09.09 0 0 1 .067-.046");
}

.pwfelrb-r {
  fill: var(--svg-color--394040, #394040);
  d: path("M12.293 28.1a.2.2 0 0 1 .048.004c.028.076-.065.174.051.232c-.035.043-.076.035-.123.023c-.053-.09.022-.172.024-.259");
}

.pwraisb5t {
  fill: var(--svg-color--cecece, #cecece);
  d: path("M17.38 27.833c.064.012.057.067.064.111c.023.078-.016.135-.043.194a.4.4 0 0 1-.041.06q-.029.027-.061.004l-.021.008a.6.6 0 0 1 .063-.36c.012-.005.028-.009.039-.017");
}

.pxot-v71x {
  fill: var(--svg-color--555013, #555013);
  d: path("M23.259 39.491c.029-.129-.045-.271.047-.395c.035.136.127.284-.047.395");
}

.pyrmiqbys {
  fill: var(--svg-color--3a3b3b, #3a3b3b);
  d: path("M14.408 30.54c-.056-.027-.026-.176-.149-.104c.027-.149.061-.295.16-.414l.006.429q.027.054-.017.089");
}

.q_01x1bab {
  fill: var(--svg-color--513f3e, #513f3e);
  d: path("m20.09 17.497l-.256.06c.044-.122.146-.114.251-.103c.017.012.025.017.019.031q-.003.012-.014.012");
}

.q-7p-4bvf {
  fill: var(--svg-color--5b5c5a, #5b5c5a);
  d: path("M22.269 31.04c-.061-.098-.043-.207-.061-.312c.04-.042.079-.038.122-.008c.013.019.026.034.038.056c-.104.069-.012.18-.057.264c-.011.023-.028.023-.042 0");
}

.q0md_obwc {
  fill: var(--svg-color--525252, #525252);
  d: path("M17.333 40.499c-.074-.123-.07-.224.096-.267a7 7 0 0 1-.096.267");
}

.q14ing_fl {
  fill: var(--svg-color--451b0c, #451b0c);
  d: path("m19.214 17.351l.088-.003c.035.079.069.146.105.211c.016.008.023.021.016.026q-.008.02-.018.018l-.008.004q-.046.05-.104.016c-.051-.083-.165-.145-.079-.272");
}

.q1aybvfdr {
  fill: var(--svg-color--5a0404, #5a0404);
  d: path("M11.964 30.3q.014.078.024.155l-.011.056l-.049.007c-.01-.08-.018-.157.036-.218");
}

.q1degtlti {
  fill: var(--svg-color--312020, #312020);
  d: path("m23.05 25.417l-.002-.043c.105-.094.215-.055.325-.008a.56.56 0 0 0-.323.051");
}

.q2fverbhn {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M23.632 35.473a.4.4 0 0 1-.014-.065c-.083-.067-.072-.176-.093-.27c.006-.012.002-.031-.011-.043c-.08-.122-.097-.266-.104-.404q.003-.03-.022-.029a.1.1 0 0 1-.06-.045c-.043-.078-.06-.166-.084-.256c-.022-.111-.056-.223-.084-.326c-.021-.09-.036-.177-.063-.261c-.041-.165-.062-.327-.107-.487a.4.4 0 0 1-.016-.08c-.041-.123-.032-.25-.069-.373a1 1 0 0 1-.022-.113c-.004-.1-.047-.198-.051-.298c-.008-.084.004-.167-.025-.245c-.018-.057-.037-.109-.041-.169a.8.8 0 0 0-.004-.201a.1.1 0 0 1 .012-.062c.033-.047.074-.055.125-.039a.47.47 0 0 0 .32.177c.123.147.002.366.127.515a.4.4 0 0 1 .026.201c-.019.096-.053.191-.01.292c.026.106.021.226.055.333c.021.087.007.171.048.252q.032.063.041.132c-.005.097-.023.185.041.269a.3.3 0 0 1 .008.072c-.027.133.039.254.039.383c.002.066.025.119.037.179c.02.185.092.346.174.503a.2.2 0 0 1 .02.105a.47.47 0 0 0 .084.321c.009.021.02.038.021.067c.004.128.031.255.07.384c.021.12.079.243.104.37c.011.105.022.217-.026.324q-.025.036-.063.043c-.133-.078-.103-.206-.121-.323c0-.037-.006-.067-.012-.104c-.055-.082-.072-.187-.113-.271c-.017-.064-.045-.141-.061-.205c-.027-.09-.083-.159-.076-.253");
}

.q3qz10bjt {
  fill: var(--svg-color--282929, #282929);
  d: path("m13.623 35.34l-.038-.049c-.076-.084-.008-.118.053-.16c.093.076-.024.138-.015.209");
}

.q4ek7466r {
  fill: var(--svg-color--191919, #191919);
  d: path("M17.962 29.774c-.021.043-.064.051-.105.059c.041-.145 0-.277-.02-.41q.025-.032.053-.006q.037.175.072.357");
}

.q4q33uben {
  fill: var(--svg-color--343636, #343636);
  d: path("m15.304 35.596l-.033-.081l.018-.007l.225.004v.084z");
}

.q5as__bxw {
  fill: var(--svg-color--594544, #594544);
  d: path("M13.166 20.11a.03.03 0 0 1 0 .029c-.122-.126-.2-.256-.004-.391c-.077.124-.045.245.004.362");
}

.q5yhnt7nw {
  fill: var(--svg-color--e6e6e6, #e6e6e6);
  d: path("M18.216 29.876c-.049.017-.102.037-.149.052c-.062-.041-.124-.083-.15-.162c-.032-.104-.069-.211-.073-.33a.3.3 0 0 1 .025-.108a.2.2 0 0 1 .074-.086a.2.2 0 0 1 .143.021q.03.021.057.051c.07.083.072.192.117.292c.03.066.047.133.035.205c-.01.039-.046.051-.079.065");
}

.q5z5ncblg {
  fill: var(--svg-color--636363, #636363);
  d: path("M19.569 28.788c-.014.055.01.129-.053.172c-.088-.077-.047-.155-.01-.234c.036.003.056.027.063.062");
}

.q6p7pwven {
  fill: var(--svg-color--0f0f0f, #0f0f0f);
  d: path("M19.222 29.853c.01-.007.02-.007.029-.015c.055-.04.108-.028.163.005c.021.027.029.054.011.089c-.072-.011-.184.065-.203-.079");
}

.q71c0bcpf {
  fill: var(--svg-color--5f5836, #5f5836);
  d: path("M21.812 19.14c-.032.063.043.169-.075.205c.05-.249.028-.495-.024-.739c.082.046.092.13.098.211c.06.102.056.213.001.323");
}

.q732x9shm {
  fill: var(--svg-color--d2b323, #d2b323);
  d: path("M23.05 37.01c.017.013.033.021.047.032a.04.04 0 0 0 .013.024c-.072.108-.177.042-.271.046c.014-.115.109-.078.178-.097a.1.1 0 0 0 .033-.005");
}

.q9b9lofvl {
  fill: var(--svg-color--570404, #570404);
  d: path("M14.13 21.756c.049-.021.096-.037.146-.056c-.004.071-.004.143-.008.207c-.081-.013-.093-.093-.138-.151");
}

.q9fr5_7bd {
  fill: var(--svg-color--fde62c, #fde62c);
  d: path("M14.345 37.03a.6.6 0 0 1 .274-.004c-.112.119-.218.123-.338.057c.023-.019.042-.031.064-.053");
}

.q9wb2sb8c {
  fill: var(--svg-color--4f4f4f, #4f4f4f);
  d: path("M18.16 28.637c-.09-.086-.027-.229-.09-.33c.016-.017.029-.037.043-.052a.6.6 0 0 1 .1.299c-.016.025-.033.058-.053.083");
}

.q9zs0ej6d {
  fill: var(--svg-color--292a2a, #292a2a);
  d: path("M18.421 28.898a.4.4 0 0 1-.092-.216h.042c.047.063.091.13.05.216");
}

.qawx19b8a {
  fill: var(--svg-color--323232, #323232);
  d: path("m20.745 36.446l.114-.147c-.025-.056.001-.063.051-.056q.005.104.005.207c-.057-.016-.115.039-.17-.004");
}

.qawy6dbmc {
  fill: var(--svg-color--544a10, #544a10);
  d: path("M21.492 23.319v-.043c.079-.004.155-.004.22.051c-.078.102-.146-.008-.22-.008");
}

.qbe-uub7d {
  fill: var(--svg-color--f3f3f3, #f3f3f3);
  d: path("M19.464 38.1c-.087.035-.063.105-.056.174c-.075.063.006.221-.144.236l-.104-.08q-.021-.027-.05-.056c-.104-.188-.04-.39-.071-.585c-.021-.053-.012-.104-.026-.159c-.043-.088-.045-.19-.066-.288q-.027-.053-.053-.111c-.055-.078-.027-.121.053-.146c.102-.048.145.062.216.086q.051.114.114.217c.039.087.063.183.082.271c.02.035.037.072.056.103c.021.079-.036.179.048.246a1 1 0 0 0 .001.092");
}

.qbs36gs0e {
  fill: var(--svg-color--272828, #272828);
  d: path("M13.419 30.726c.004.169-.006.33-.095.479l.013-.479z");
}

.qbux6xces {
  fill: var(--svg-color--544a0c, #544a0c);
  d: path("M22.521 18.971h-.026a3 3 0 0 0-.066-.154c0-.021 0-.038.002-.059l.147.004c.067.026.019.06.006.09c-.062.02-.065.067-.063.119");
}

.qbzwm5b6a {
  fill: var(--svg-color--4a4a4a, #4a4a4a);
  d: path("M19.696 39.854c.082.038.16.104.246 0l.045.001c.005.071-.071.14-.008.214q-.023.039-.059 0c-.069-.076-.224-.059-.224-.215");
}

.qc058cchh {
  fill: var(--svg-color--e1e2e2, #e1e2e2);
  d: path("M18.374 28.478c-.018.048-.037.09-.089.102c-.048.024-.08 0-.106-.03a1.1 1.1 0 0 1-.112-.308c0-.074-.013-.149.062-.188c.122.029.09.22.235.225z");
}

.qdfqkz_ft {
  fill: var(--svg-color--342d0b, #342d0b);
  d: path("M15.558 38.813q-.031.204-.059.416c-.018.017-.029.013-.043 0c0-.213.004-.422.004-.633c.09.046.021.161.098.217");
}

.qdnsnfm9f {
  fill: var(--svg-color--562221, #562221);
  d: path("M20.09 17.497q.001-.018-.004-.043c.1-.012.149.092.24.104q-.015.03-.029.063c-.1.013-.133-.093-.207-.124");
}

.qeq435bvi {
  fill: var(--svg-color--49110d, #49110d);
  d: path("m22.638 18.471l-.011.188c-.056.056-.122.061-.194.037a.17.17 0 0 1-.073-.096c.005-.02.016-.04.022-.055c.096.01.19.024.256-.074");
}

.qeteizbxh {
  fill: var(--svg-color--411709, #411709);
  d: path("M13.22 39.38h.108c.031-.03.009-.08.049-.107c.062.051.05.149.146.178c-.129.044-.232.054-.303-.071");
}

.qf0n6z6vo {
  fill: var(--svg-color--5f6161, #5f6161);
  d: path("M17.904 37.12c-.013.08-.036.145-.104.189c-.066-.115.006-.16.104-.189");
}

.qf8ow4bww {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M13.533 34.35c-.11.063-.019.205-.101.275c.012-.112-.051-.236.06-.336c.03.011.054.027.041.061");
}

.qfk06p3tl {
  fill: var(--svg-color--73370f, #73370f);
  d: path("M16.08 19.61c-.08-.07-.181-.142-.103-.275c.044.087.107.169.103.275");
}

.qfn4j0biq {
  fill: var(--svg-color--13202e, #13202e);
  d: path("M23.21 21.493a3 3 0 0 1-.062.213c-.067-.096-.043-.166.062-.213");
}

.qg115pfyq {
  fill: var(--svg-color--582525, #582525);
  d: path("M14.306 34.442c.016.016.025.039.041.057c-.021.074-.012.162-.084.215l-.011-.072c.011-.069.001-.145.054-.2");
}

.qhetpibuc {
  fill: var(--svg-color--6e6e6e, #6e6e6e);
  d: path("M13.948 28.579c-.008.053-.021.1-.071.1c-.043 0-.04-.047-.032-.075a.13.13 0 0 1 .047-.075c.05-.015.045.036.056.05");
}

.qhv-akupd {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M19.364 40.842c-.018.04-.032.077-.053.11a10 10 0 0 0-.047-.361q.022-.04.045-.004c.092.074.042.173.055.255");
}

.qia-ppbhb {
  fill: var(--svg-color--4d440f, #4d440f);
  d: path("M18.578 17.549q-.002.025-.002.051c-.103-.022-.204.114-.313.008a.7.7 0 0 1 .315-.059");
}

.qid-20brd {
  fill: var(--svg-color--fad528, #fad528);
  d: path("M15.798 25.485c.053.016.09.041.1.098c.189.109.266.332.451.443c.033.051.08.086.113.137c.029.086.094.16.112.261q-.001.059-.062.069c-.104-.02-.158-.133-.263-.152c-.019-.01-.022-.02-.021-.032s.007-.021.012-.021c-.07-.066-.129-.152-.25-.129c-.168-.119-.378.013-.545-.095c-.006-.012-.018-.012-.028-.012c-.149-.039-.294-.06-.399.098c-.023.035-.072.04-.104-.013a.35.35 0 0 1 .014-.398c.008-.004.014-.017.01-.025c.043-.156.162-.213.304-.231q.028-.006.054-.017c.1-.061.209-.07.323-.07c.085-.026.119.06.179.089");
}

.qj2-bdcqz {
  fill: var(--svg-color--595959, #595959);
  d: path("M18.944 39.76c-.15-.024-.164-.111-.104-.233z");
}

.qjlrywbkh {
  fill: var(--svg-color--44240a, #44240a);
  d: path("M16.272 26.392c0-.031.005-.061.005-.09c.128-.014.159.122.241.172a.1.1 0 0 0-.002.047c-.061-.017-.123-.027-.182-.047z");
}

.qjwkop_da {
  fill: var(--svg-color--575755, #575755);
  d: path("M23.372 33.24q.047-.027.096-.047c-.02.107.051.235-.053.332c-.076-.085-.038-.186-.043-.285");
}

.qk2-z8bpk {
  fill: var(--svg-color--2b2d2d, #2b2d2d);
  d: path("M17.484 35.448c-.042-.248.019-.502-.046-.75c-.018-.008-.021-.018-.018-.026q.007-.01.016-.011c.173.115.084.297.099.449c.013.113-.004.229-.006.338q-.022.038-.045 0");
}

.qke16bu6o {
  fill: var(--svg-color--515252, #515252);
  d: path("M15.449 31.802c-.071-.064-.028-.119.019-.186h.032c-.036.178.091.351.007.525l-.016.01q-.017-.104-.039-.209q-.064-.065-.003-.14");
}

.ql-cdrcll {
  fill: var(--svg-color--645711, #645711);
  d: path("M18.788 17.245c.031-.231-.063-.469.051-.691q.041.034.004.075c.012.085.023.174.037.255c-.025.109-.014.223-.015.333c-.005.03-.005.065-.046.069c-.033.01-.031-.021-.031-.041");
}

.ql0hd3r5w {
  fill: var(--svg-color--282828, #282828);
  d: path("M18.901 40.17a.2.2 0 0 1 .048.005a.32.32 0 0 1-.11.208c-.022-.081.036-.143.062-.213");
}

.ql7yi7t9k {
  fill: var(--svg-color--e3e4e4, #e3e4e4);
  d: path("M16.765 29.11c.109-.117.172-.271.25-.408c.025-.043.061-.048.103-.031c.042.043.03.098.026.148c-.004.075-.006.16-.039.231a.33.33 0 0 1-.236.149c-.057-.009-.12-.001-.104-.089");
}

.ql8xdw13v {
  fill: var(--svg-color--4f5054, #4f5054);
  d: path("M18.423 40.12h.066c.055.072.105.149.09.254c0 .019 0 .043-.002.063c-.099-.084-.103-.212-.154-.317");
}

.qlo78ebcd {
  fill: var(--svg-color--1f2121, #1f2121);
  d: path("m13.578 34.03l-.052-.108a10 10 0 0 1 .017-.354q.018-.04.037-.004z");
}

.qlpm9kjaz {
  fill: var(--svg-color--660706, #660706);
  d: path("M16.702 41.11c-.002.09-.002.184-.002.272c-.081-.09-.053-.182.002-.272");
}

.qlvqurbyn {
  fill: var(--svg-color--562b2b, #562b2b);
  d: path("M22.783 35.13c.043-.055.083-.105-.004-.148c.056-.059.108-.048.142.016c.038.067-.012.104-.062.144c-.033.019-.055.017-.076-.012");
}

.qm-v0brlp {
  fill: var(--svg-color--61605f, #61605f);
  d: path("M13.167 33.24q-.002.213-.008.424c-.049.387.012.774-.034 1.16l-.007-.008c-.029.021-.051.012-.066-.017q.012-.756.021-1.515c.018-.04.039-.074.094-.044");
}

.qm1_kp9yd {
  fill: var(--svg-color--2d2d2d, #2d2d2d);
  d: path("M24.1 28.353c-.153.063-.078-.126-.16-.143c.011-.109-.135-.211-.004-.325q.042.016.054.06q.051.206.11.408");
}

.qno6rgbyl {
  fill: var(--svg-color--e2e3e3, #e2e3e3);
  d: path("M20.19 28.313c0-.067.019-.125.107-.099q.006.036.008.066c.056.075.117.152.094.264c-.008.013-.012.023-.021.035a.3.3 0 0 0-.06-.008q-.033.037-.078.021a.26.26 0 0 1-.05-.279");
}

.qo3ma9m9o {
  fill: var(--svg-color--4b4310, #4b4310);
  d: path("M22.12 22.491c.141.008.271.09.417.055a.42.42 0 0 0-.065.256c-.027.033-.063.031-.099.016q-.018-.007-.024-.016c-.028-.143-.227-.156-.229-.311");
}

.qo82f1o_y {
  fill: var(--svg-color--512e0d, #512e0d);
  d: path("M19.414 20c.019-.105.033-.207.054-.318c.074.123.106.234-.054.318");
}

.qoesl-gsp {
  fill: var(--svg-color--aeaeae, #aeaeae);
  d: path("M17.188 18.02q-.274.005-.547.004l.123-.043c.082-.004.166-.004.25-.008c.055.014.116.03.174.047");
}

.qovu9pbfr {
  fill: var(--svg-color--36280b, #36280b);
  d: path("M12.699 38.19q.077.052.159.104l-.004.023l.004.021c-.113-.044-.18.038-.266.092c.04-.079-.063-.22.107-.24");
}

.qp3dxzb8s {
  fill: var(--svg-color--726214, #726214);
  d: path("M17.07 21.958q.043-.047.084-.096q.17.02.339.045c-.129.1-.276.049-.423.051");
}

.qpc8d747z {
  fill: var(--svg-color--060707, #060707);
  d: path("M16.199 29.838c.015.103.091.032.138.047c.063-.017.141-.07.165.051c-.124-.03-.286.085-.368-.101q.031.004.065.003");
}

.qpn6fbcbz {
  fill: var(--svg-color--232424, #232424);
  d: path("M22.22 29.782q-.003.018-.002.047a.4.4 0 0 1-.074.151c-.045.042-.082.027-.121-.009l-.012-.032c-.039-.196.103-.153.209-.157");
}

.qq94-ybgm {
  fill: var(--svg-color--431e0a, #431e0a);
  d: path("M21.488 39.542q-.026-.001-.054.005c.016-.105.035-.209.178-.163z");
}

.qr75_l-or {
  fill: var(--svg-color--f8f9f9, #f8f9f9);
  d: path("M17.798 40.28c0-.018.002-.028.004-.045c-.039-.134.066-.25.063-.383c.04-.07.085-.066.137-.014c.053.061.07.138.104.203a.5.5 0 0 1 .055.195c-.007.152-.072.31-.046.469c0 .031-.005.062-.009.104c-.094.166-.023.348-.051.52c-.013.074-.062.123-.127.158l-.078.146c-.125.108-.197.069-.231-.082c-.024-.183 0-.36 0-.547c.015-.065.026-.136.03-.201c.027-.117.027-.24.072-.351a.24.24 0 0 1 .077-.172");
}

.qs7m63bll {
  fill: var(--svg-color--48310b, #48310b);
  d: path("m16.234 39.37l.012.139q-.032.052-.062.109c-.052-.098.021-.168.05-.248");
}

.qt47uoa8w {
  fill: var(--svg-color--5a0706, #5a0706);
  d: path("M23.625 38.26a.43.43 0 0 1 .042.244c-.121-.058-.121-.144-.042-.244");
}

.qtlpe_94w {
  fill: var(--svg-color--a5a5a6, #a5a5a6);
  d: path("M17.226 29.728c.076.24-.144.153-.229.208c-.047-.007-.06-.043-.06-.083a.22.22 0 0 1 .17-.191c.062-.013.09.031.123.07z");
}

.qu0z-ia2a {
  fill: var(--svg-color--6d6e6e, #6d6e6e);
  d: path("M17.226 31.493c.101.117.025.258.053.39c-.055.028-.074-.017-.098-.048c.02-.112-.056-.24.045-.342");
}

.qugzqi6hy {
  fill: var(--svg-color--2f3232, #2f3232);
  d: path("M22.427 32.391c.168.124.109.322.152.483q-.023.037-.043 0a1.1 1.1 0 0 1-.109-.483");
}

.qurgtmvti {
  fill: var(--svg-color--4b0303, #4b0303);
  d: path("M25.02 36.13c-.008.005-.016 0-.028-.004c0-.102-.004-.194-.006-.297a.2.2 0 0 0 .045-.033c-.002.115-.008.22-.011.334");
}

.quws1qk1c {
  fill: var(--svg-color--4f5050, #4f5050);
  d: path("M13.683 31.778h-.125q-.017-.025.013-.043c.04-.063.052-.16.157-.147c.043.012.076.03.068.086a.12.12 0 0 0-.113.104");
}

.qv3lcubah {
  fill: var(--svg-color--5a220b, #5a220b);
  d: path("M21.291 22.696c-.084-.025-.125-.096-.178-.156c.12-.016.162.052.178.156");
}

.qvw_qqbec {
  fill: var(--svg-color--303131, #303131);
  d: path("M13.08 27.577h.041c.062.15-.13.375.127.473c-.06.033-.119.039-.179 0c-.033-.158-.056-.318.011-.473");
}

.qwqewpnyk {
  fill: var(--svg-color--572a0d, #572a0d);
  d: path("m18.37 20.589l.002-.039c.098-.067-.023-.141.012-.208c.106.083.118.198.094.325z");
}

.qwrjojj0g {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M18.591 18.512c.08.062.154 0 .231-.005c.012.048.012.099.065.126a.22.22 0 0 1-.002.263l.004-.003q-.184.135-.365 0v.003c-.063-.079-.11-.156-.012-.244c.048-.036.079-.079.079-.14");
}

.qx1cd7b2j {
  fill: var(--svg-color--706114, #706114);
  d: path("M19.241 17.731c-.059-.078-.225-.012-.229-.169q.123.048.242.091z");
}

.qx3qrmn1e {
  fill: var(--svg-color--494b4b, #494b4b);
  d: path("M24.761 34.661c-.063-.064-.029-.151-.052-.223c.005-.104.011-.197.015-.302c.121.024.058.106.056.171c-.009.121-.013.233-.019.354");
}

.qx8gedcud {
  fill: var(--svg-color--f9d428, #f9d428);
  d: path("M21.959 20.907c.052.022.052.07.058.112c.076.056.098.138.131.218c.012.104-.063.176-.11.254c-.026.024-.062.039-.082.071l.003.017c-.02.059-.07.074-.124.088c-.104.033-.214.048-.308-.03a.3.3 0 0 1-.071-.103c-.026-.106.026-.182.091-.256l-.005.004c.021-.027.06-.035.089-.063a.13.13 0 0 1-.072-.013a.3.3 0 0 1-.067-.02c-.021-.031-.013-.063 0-.094c.03-.063.043-.122-.036-.157c-.043-.017-.087-.026-.126-.047a.18.18 0 0 1-.069-.118a.5.5 0 0 1 .027-.136c.034-.101.055-.206.184-.229q.032-.008.063-.02a1 1 0 0 0 .122-.047c.043-.018.089-.041.124.011c.049.09.031.188.063.279a.4.4 0 0 1 0 .102c-.009.029-.021.052-.029.079c.022.079.108.046.144.098");
}

.qxftbkbzd {
  fill: var(--svg-color--443c0c, #443c0c);
  d: path("M23.05 21.19c.041-.017.049-.051.053-.09a.1.1 0 0 1 .058-.004a.1.1 0 0 1 .043.036l.007.004c-.007.063.04.156-.039.181c-.073.018-.126-.044-.122-.127");
}

.qy1rcfa4z {
  fill: var(--svg-color--828384, #828384);
  d: path("M18.12 19.348a2 2 0 0 1-.018-.165c-.01-.354.068-.708-.047-1.049l.002-.066c.017-.012.035-.027.051-.037c.035-.014.063-.01.083.025c.052.385.017.773.021 1.16c-.002.066-.014.123-.092.132");
}

.qyr0qk75d {
  fill: var(--svg-color--51260b, #51260b);
  d: path("M14.321 39.696a.3.3 0 0 0-.07.008c-.072-.056-.164-.104-.096-.217q.084.102.166.209");
}

.qz45ivzlo {
  fill: var(--svg-color--191818, #191818);
  d: path("m24.466 36.958l-.01-.021c.027-.079.07-.127.158-.096c.055.042.051.114.053.174q-.016.032-.031.054c-.004-.111-.115-.074-.17-.111");
}

.qzopv5b7s {
  fill: var(--svg-color--1e1e1e, #1e1e1e);
  d: path("M12.917 36.45c-.023.09.023.217-.113.26c.041-.081-.051-.192.051-.264q.031-.031.062.004");
}

.r0o0uobkr {
  fill: var(--svg-color--534c1c, #534c1c);
  d: path("M18.854 18.12c-.109-.041-.215-.016-.326.009q-.005-.029-.004-.05c.12-.047.241-.131.33.041");
}

.r0s5srz-z {
  fill: var(--svg-color--f7f7f8, #f7f7f8);
  d: path("M20.04 28.682c-.01.157.011.317-.045.472c.019.096.052.196-.117.161q-.026-.038-.048-.065c-.004-.021-.006-.037-.012-.057c-.141-.082-.051-.197-.043-.302c.02-.08.082-.119.148-.157c.029-.045.042-.118.117-.052");
}

.r1t5l4hgi {
  fill: var(--svg-color--434242, #434242);
  d: path("M15.468 32.721c-.017 0-.037-.004-.051-.004a.32.32 0 0 1 .039-.209h.047c.004.075.018.151-.035.213");
}

.r1u72-5fc {
  fill: var(--svg-color--150c07, #150c07);
  d: path("M14.871 40.18c.002.091-.06.091-.114.071c-.078-.021-.078.026-.084.078q-.019.03-.037 0c-.086-.317.182-.058.235-.149");
}

.r2bm0obje {
  fill: var(--svg-color--fad628, #fad628);
  d: path("M13.224 37.426c.043.044.088.082.127.126c.205.081.392-.032.582-.057c.099-.008.194-.033.289.009a.1.1 0 0 1 .056.052v.023c-.003.039-.05.062-.069.096c.031-.026.063-.057.088-.084c.038-.044.098-.057.146-.083q.087-.052.167-.104a.3.3 0 0 1 .121-.068c.084-.01.181-.069.242.05c.013.05-.004.103.008.151c.016.035.037.069.016.108c-.02.004-.035.013-.045.017c-.157.023-.258.15-.396.196c-.07.036-.146.063-.205.113a.3.3 0 0 1-.061.036a.2.2 0 0 1-.135-.04c-.126-.125-.197.056-.299.06c-.074.072-.016.161-.036.239c-.017.048-.021.099-.034.142c-.027.063-.01.125-.021.188c-.043.104-.054.226-.119.317a.14.14 0 0 1-.033.047c-.094.06-.18.037-.266-.016q-.069-.01-.136-.008a.14.14 0 0 1-.062-.027c-.088-.047-.037-.158-.1-.217a.26.26 0 0 1 .051-.136c.09-.142.143-.338.373-.298c.08.143-.104.183-.103.292c.019-.117.188-.169.138-.318a.3.3 0 0 1 .039-.108a.9.9 0 0 1-.434.23a.1.1 0 0 1-.081-.066a.17.17 0 0 1 .034-.139c.064-.06.099-.132.144-.195c.017-.026.056-.026.071-.056c-.027-.008-.063-.008-.085-.026c-.083-.09-.228.022-.308-.09a.1.1 0 0 1 0-.07a.9.9 0 0 0 .267-.278c.02-.012.044-.012.069-.008");
}

.r2k_--bim {
  fill: var(--svg-color--595858, #595858);
  d: path("M24.03 30.364q-.023.053-.048.105a.28.28 0 0 1-.035-.219c.016-.021.031-.035.046-.055c.049.052.054.108.037.169");
}

.r2kkcub2b {
  fill: var(--svg-color--373838, #373838);
  d: path("M24.374 34.868q-.04.005-.074.004q-.014-.017-.009-.039c.009-.195.011-.391.017-.584q.012-.036.037-.004q.012.313.029.623");
}

.r2nlx_2xj {
  fill: var(--svg-color--49260a, #49260a);
  d: path("M13.01 37.981c-.065.09-.131.176-.252.176c.061-.091.119-.186.252-.176");
}

.r30y1ybdc {
  fill: var(--svg-color--1a0908, #1a0908);
  d: path("M15.509 26.482q-.002.054-.002.114c-.056-.016-.125-.032-.109-.104c.013-.05.074-.018.111-.01");
}

.r3mfqrbkn {
  fill: var(--svg-color--3b1b1a, #3b1b1a);
  d: path("M20.706 39.4c-.044-.09-.117-.171-.092-.281a.22.22 0 0 1 .102.16c.027.04.029.087-.01.121");
}

.r3msrlq2i {
  fill: var(--svg-color--e4c327, #e4c327);
  d: path("M21.974 40.01q.253-.001.504.004c-.166.104-.342.039-.514.031z");
}

.r4rd3ibkn {
  fill: var(--svg-color--dabf25, #dabf25);
  d: path("M15.202 36.714c-.002.02-.007.033-.009.054c-.2.147-.37.326-.522.522c-.047.063-.107.113-.158.176c-.021.021-.045.046-.074.064c-.041.021-.082.041-.125.03a.3.3 0 0 1-.074-.073q-.026-.046-.004-.103a.4.4 0 0 1 .117-.132q.029-.02.061-.035c.163-.1.285-.23.417-.363l.076-.07c.043-.039.083-.082.137-.106c.021-.013.048-.013.072-.013c.031 0 .067.019.086.049");
}

.r5pysqb7k {
  fill: var(--svg-color--565036, #565036);
  d: path("M22.315 18.739v-.096c.016-.016.027-.031.043-.043c.023.016.046.036.068.051c.002.039.037.072.03.11a.1.1 0 0 1-.028.055a1 1 0 0 0-.113-.077");
}

.r5qr_yt1g {
  fill: var(--svg-color--442e2f, #442e2f);
  d: path("M20.36 30.938c.001-.078.031-.15.115-.146c.068.005.104.076.121.148c-.064.018-.125-.09-.193-.004c-.015.026-.032.026-.043.002");
}

.r5rcznbmd {
  fill: var(--svg-color--1b1c1c, #1b1c1c);
  d: path("M14.937 29.739v.1q.02.017.015.039c-.002.017-.009.021-.015.021c-.051.017-.088-.004-.131-.03c-.039-.037-.117-.063-.074-.138a.04.04 0 0 0 0-.036q.103.02.205.044");
}

.r5w-3dfsi {
  fill: var(--svg-color--1b2e34, #1b2e34);
  d: path("M22.375 22.817q.05-.006.099-.016l.123.113c-.09-.001-.156-.05-.222-.097");
}

.r5x-i8b1q {
  fill: var(--svg-color--464646, #464646);
  d: path("M15.404 29.944c.104.027.101.141.155.207l.002-.004c-.213.051-.2-.07-.154-.212z");
}

.r6kwnubbl {
  fill: var(--svg-color--281008, #281008);
  d: path("M13.218 38.913c-.072.139-.049.274-.029.42c-.158-.108-.024-.281-.094-.416q.038-.04.084-.008z");
}

.r6nvl7b-s {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M23.821 30.25c.018-.056.008-.148.115-.104c.029.028.033.067.045.104c.011.079.004.157.031.231c.002.084-.004.157.021.235c.014.104-.01.213.021.313c.015.129.031.26.09.377l-.004-.013c-.017.14-.09.246-.156.351a1 1 0 0 1-.127.027c-.108-.056-.115-.176-.158-.271q-.019-.034-.029-.07c-.035-.129-.074-.263-.094-.395c-.004-.096.038-.191-.004-.285c-.039-.102.059-.2.004-.299c.016-.032-.02-.104.057-.074c.124.047.154-.039.188-.127");
}

.r6xvho_tx {
  fill: var(--svg-color--efefef, #efefef);
  d: path("M22.11 34.87c.131.058.178.193.283.279c.007.065.055.121.066.188c.051.06.098.123.154.175c.066.06.088.136.057.213c-.031.072-.123.026-.186.038c-.071-.05-.178.012-.236-.075a.7.7 0 0 1-.074-.13c-.017-.121-.08-.225-.117-.342c-.1-.09-.201-.191-.301-.29c-.093-.074-.215-.062-.317-.11c-.032-.158.09-.083.149-.101c.09.056.18-.024.272-.003q.023.025.043.055a.6.6 0 0 1 .207.103");
}

.r7950ibce {
  fill: var(--svg-color--5a110c, #5a110c);
  d: path("M20.708 23.384c.121-.068.227-.028.323.05a.65.65 0 0 1-.323-.05");
}

.r7ap8eb9b {
  fill: var(--svg-color--cfb824, #cfb824);
  d: path("M21.255 26.581c-.027-.051-.05-.099-.078-.149l.199-.013h.053c.094.008.178.052.268.08c.052.02.138-.024.154.047c.019.08-.064.056-.105.066a.29.29 0 0 1-.25-.023q-.125-.007-.241-.008");
}

.r7sfikbyj {
  fill: var(--svg-color--464646, #464646);
  d: path("M20.601 29.46c-.104.043-.082-.102-.151-.113c-.013-.057.017-.086.062-.113c.035-.017.069-.004.099.016c0 .039 0 .074-.005.115z");
}

.r86k-tbem {
  fill: var(--svg-color--6a5c13, #6a5c13);
  d: path("M22.688 39.02c.01-.104.08-.108.177-.104c-.035.101-.115.086-.179.101z");
}

.r9vpyqb0e {
  fill: var(--svg-color--1c0303, #1c0303);
  d: path("m20.411 34.403l-.064-.018c.101-.077.205-.043.309-.021c.004.047-.012.067-.057.039z");
}

.ra79setzl {
  fill: var(--svg-color--404242, #404242);
  d: path("m15.04 31.448l.012-.254c.021-.035.039-.078.1-.043c0 .131.015.268-.104.37z");
}

.raxe8p1bg {
  fill: var(--svg-color--710d0c, #710d0c);
  d: path("M17.22 23.284a1 1 0 0 1 .099-.017c.114-.036.228-.012.34-.012l.035.021c-.16.064-.317.092-.474.008");
}

.rbm0rrbza {
  fill: var(--svg-color--232424, #232424);
  d: path("M19.829 37.817c-.063-.103-.079-.217-.1-.326h.027c.057.104.162.197.073.326");
}

.rc3h78bbk {
  fill: var(--svg-color--605712, #605712);
  d: path("M22.712 21.23q.132-.146.303-.046c-.09.084-.202.023-.303.046");
}

.rcp5m8bce {
  fill: var(--svg-color--eccf28, #eccf28);
  d: path("M20.243 21.847c-.135.008-.279.066-.402-.043c.142-.061.301-.26.402.043");
}

.rddrk7k7g {
  fill: var(--svg-color--616161, #616161);
  d: path("m13.483 28.676l-.008.078q-.111-.059-.088-.185c.067-.109-.015-.255.086-.361z");
}

.rde0jue6p {
  fill: var(--svg-color--260f06, #260f06);
  d: path("M12.603 37.536a.4.4 0 0 1 .248 0c.017.017.022.025.02.043q-.004.02-.014.021l-.01.011c-.067-.075-.193.046-.244-.075");
}

.rdj3-pbod {
  fill: var(--svg-color--0b0a06, #0b0a06);
  d: path("m20.599 17.909l.052.063c-.099.094-.196.089-.294.004c.033-.02.063-.041.094-.055z");
}

.rf-87nb8b {
  fill: var(--svg-color--262828, #262828);
  d: path("M23.1 31.872c.028.01.062.014.094.018c-.202.141-.243-.032-.305-.163a.1.1 0 0 1 .061-.021a.24.24 0 0 1 .15.166");
}

.rf1n01ejg {
  fill: var(--svg-color--f8f9f9, #f8f9f9);
  d: path("M17.323 29.896c-.075-.03-.014-.146-.098-.168l-.028-.032a.6.6 0 0 1-.011-.41c.041-.088.109-.121.199-.068q.051.034.088.085c.06.094.133.192.11.321a.4.4 0 0 1-.051.146c-.043.087-.088.169-.209.126");
}

.rf3aeh2ld {
  fill: var(--svg-color--6f2d0e, #6f2d0e);
  d: path("M16.654 22.95a.34.34 0 0 1 .287-.146a.33.33 0 0 1-.287.146");
}

.rf56jv6ai {
  fill: var(--svg-color--2d2e2e, #2d2e2e);
  d: path("M24.25 36.02c-.182-.11-.098-.312-.152-.468q.02-.04.039 0z");
}

.rfqr0zbom {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M15.1 30.782q.001.075.006.16c.06.094-.051.188-.012.291c0 .077.012.156-.056.215c-.045.107-.089.221-.134.33l-.176.127l-.06-.179c.013-.04-.004-.08-.036-.114c-.039-.022-.031-.066-.031-.104a1 1 0 0 0 .066-.228c.02-.15.008-.299.076-.437c.047-.06.004-.193.139-.188c0 .021.004.035.006.055c.028.09.076.125.157.06a.2.2 0 0 0 .035-.048z");
}

.rfzvatbxg {
  fill: var(--svg-color--362b2b, #362b2b);
  d: path("M16.82 40.815c-.013.189-.126.366-.039.559c-.024.029-.05.066-.081.004a.42.42 0 0 1 .002-.271c-.004-.058.035-.162-.1-.098c-.004-.131.15-.146.166-.255c.054-.007.073.009.052.061");
}

.rh5jxei-a {
  fill: var(--svg-color--cecfcf, #cecfcf);
  d: path("M18.788 28.682c.043-.047.143-.051.087-.153a.07.07 0 0 1 .048-.009c.078 0 .135.043.178.101a.08.08 0 0 1 .008.065c-.043.083-.086.156-.1.252c-.015.048-.029.091-.072.113c-.082-.017-.086.106-.176.103c-.067-.161-.01-.319.027-.472");
}

.rh7nwlbkz {
  fill: var(--svg-color--f9d82a, #f9d82a);
  d: path("M15.304 20.706c.094.021.104-.129.201-.104c-.041.071.172.188-.048.216l-.153-.058z");
}

.ri79zpncg {
  fill: var(--svg-color--161717, #161717);
  d: path("m13.677 32.34l-.017-.004l-.015.012l-.024-.574q.03-.025.062 0c.008.188.025.382-.006.566");
}

.rid_6eseo {
  fill: var(--svg-color--180e0e, #180e0e);
  d: path("M13.229 36.706c.015 0 .029.004.043 0c-.027.185-.238.078-.303.195c.017-.052.033-.095.051-.143c.021-.038.043-.072.092-.076c.041.002.076.024.117.024");
}

.rilb5ubhs {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M16.911 34.633c-.08-.011-.136.155-.23.028c-.092-.02-.033-.088-.049-.137a.3.3 0 0 1 .192-.148c.065 0 .134-.023.2.025l-.008-.004c.082.061.176.012.261.037c.106.034.233.02.321.113c.017.017.033.033.052.056c.026.368.043.731-.011 1.108l.006-.006c-.045.09-.145.09-.219.129c-.063.009-.129-.004-.189.023a.6.6 0 0 1-.229.032c-.091.043-.185 0-.274.022c-.024-.024-.048-.039-.073-.062c-.055-.103-.057-.188.053-.241h.094c.064.026.123.109.203.034c.049-.127.072-.247-.024-.37c-.065-.076-.062-.158-.027-.251a.1.1 0 0 0 .021-.047c.095-.078.068-.183.058-.278c-.04-.031-.028-.152-.128-.063");
}

.rjk0rw2-h {
  fill: var(--svg-color--dbdbdb, #dbdbdb);
  d: path("m17.333 29.05l-.152.212c-.06.062-.14.051-.217.047v-.056c.016-.06.114-.066.105-.149c.07-.073.068-.172.093-.269c.022-.033.045-.058.067-.09c.025-.041.061-.041.101-.027a.6.6 0 0 1 .003.332");
}

.rjpb_bblc {
  fill: var(--svg-color--3f2a29, #3f2a29);
  d: path("m19.407 17.602l.002-.043c.096-.075.188-.125.266.022c-.096-.045-.181-.028-.268.021");
}

.rjqisz75w {
  fill: var(--svg-color--c6c6c6, #c6c6c6);
  d: path("M18.06 27.786c.005.096.005.177.009.269c.004.039-.021.062-.06.065c-.119-.016-.127-.117-.154-.205a.3.3 0 0 1-.031-.129c.018-.086-.008-.172-.01-.258a.2.2 0 0 1 .033-.063a.04.04 0 0 0 .004-.035q.053-.008.104-.009c.101.102.069.248.105.365");
}

.rjuq9gb3z {
  fill: var(--svg-color--2e2e2e, #2e2e2e);
  d: path("M17.18 41.12h-.059c.034-.185.014-.386.158-.53z");
}

.rmem1le2l {
  fill: var(--svg-color--35210c, #35210c);
  d: path("M12.529 38.704c.021-.012.042-.021.063-.037c.026-.008.053-.012.086-.021c-.014.053-.006.135-.035.148c-.056.031-.089-.037-.114-.09");
}

.rmh1_36ca {
  fill: var(--svg-color--706213, #706213);
  d: path("m18.212 23.06l-.002-.036q.525.005 1.051.004l-.002.032z");
}

.rmji61bvf {
  fill: var(--svg-color--6d632f, #6d632f);
  d: path("M15.513 20.557q0 .025.006.047l-.014-.004c-.061.051-.074.185-.201.104a.1.1 0 0 1 0-.035c.064-.114-.102-.168-.063-.271c.016-.019.031-.035.055-.039a.14.14 0 0 1 .071.008c.071.048.132.096.146.19");
}

.rnvl_vbae {
  fill: var(--svg-color--2a2c2c, #2a2c2c);
  d: path("M23.11 33.77c-.039-.173-.172-.332-.062-.521c.03.175.062.345.094.521z");
}

.rok7wrb7g {
  fill: var(--svg-color--4a4736, #4a4736);
  d: path("M14.99 36.23c.128.022.247-.021.362-.045l-.008.098c-.117.088-.238-.031-.358 0z");
}

.royja-36r {
  fill: var(--svg-color--401211, #401211);
  d: path("M23.2 26.428c.121.217.095.448.05.68q-.022.042-.047 0c-.002-.231.031-.459-.057-.684c.021-.019.036-.019.054.004");
}

.rq_ui2dao {
  fill: var(--svg-color--632a0c, #632a0c);
  d: path("m21.705 26.474l-.054.036c-.079-.021-.163-.022-.225-.091c.112-.074.19.016.279.055");
}

.rs12-5w_c {
  fill: var(--svg-color--2e2d29, #2e2d29);
  d: path("M13.683 19.495q.032-.001.064.004a6 6 0 0 0-.068.209q-.06.042-.11-.004c-.001-.094.065-.144.114-.209");
}

.rspjlf97a {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M16.03 29.997c.68-.004 1.365-.004 2.042-.015c.149 0 .192.054.192.199c-.008.879-.008 1.761-.012 2.642c-.181.061-.373.024-.557.022c-.559-.011-1.117.035-1.673-.021a.17.17 0 0 1-.048-.121c-.002-.748-.045-1.494.012-2.246c.012-.148-.024-.306.044-.46");
}

.rt7vhw_vw {
  fill: var(--svg-color--373939, #373939);
  d: path("M15.298 29.85c.002-.017.002-.04.002-.06c.082.016.094.086.104.152v.032c-.007.036-.022.067-.058.083c-.051.012-.082-.018-.11-.061c-.02-.06.015-.107.062-.146");
}

.rt9ribclk {
  d: path("M25.17 34.506c-.009-.087-.021-.175-.022-.261l.051.062c-.012.065-.02.135-.029.199");
}

.rtlw4dn_k {
  fill: var(--svg-color--f6d128, #f6d128);
  d: path("M15.46 21.602c-.016-.019-.031-.034-.049-.058a.2.2 0 0 1-.068-.09c-.024-.094-.062-.186-.041-.283c.026-.047.017-.11.053-.149h-.002c.035-.047.063-.095.104-.138c.094-.055.122-.139.122-.236c.043-.095-.017-.251.158-.268c.047.009.094.035.146.031c.02 0 .041-.004.061 0c.063 0 .128-.017.174.047a.4.4 0 0 1 .033.138c.003.06.012.118.008.176c-.029.095-.125.086-.189.142c-.094.067-.045.186-.086.271c-.043.028-.053.059-.007.096l.103.152c.039.053-.002.096-.016.146c-.209.195-.273.195-.504.023");
}

.rtt8k8gsq {
  fill: var(--svg-color--978117, #978117);
  d: path("M22.953 36.965c.036.018.065.034.101.049q0 .017-.011.024c-.083.018-.172.006-.256.028h-.052c-.023-.041-.027-.079.011-.116c.072-.047.14-.035.207.015");
}

.rtuk4obkl {
  fill: var(--svg-color--594e10, #594e10);
  d: path("M14.843 38.96h.043a.5.5 0 0 1 .039.271q-.023.025-.048.061c-.032-.172-.139-.276-.312-.324c.12-.114.19.06.278-.008");
}

.rtzg7nwdd {
  fill: var(--svg-color--343636, #343636);
  d: path("M23.578 30.24c.063.06.125.082.194.011c.017-.022.039-.022.061-.011c.049.185-.152.168-.208.267c-.028.04-.055.083-.112.067c-.051-.047-.049-.11-.063-.168q.003-.134.128-.166");
}

.rv4n3nc9r {
  fill: var(--svg-color--5c4e10, #5c4e10);
  d: path("M21.746 20.792q.105.042.208.088l.004.027c-.064 0-.134.008-.199 0c-.153-.015-.045-.072-.013-.115");
}

.rvunwk95y {
  fill: var(--svg-color--664612, #664612);
  d: path("m19.933 21.13l.055.053c-.071.054-.016.208-.153.208c.029-.082.062-.173.098-.261");
}

.rxcyi0wmy {
  fill: var(--svg-color--ededee, #ededee);
  d: path("M20.501 36.4c.075-.082.146-.175.221-.255c.148-.063.129.062.158.144c.008.097-.049.143-.134.162q-.022-.007-.022.012c-.106.077-.196.118-.223-.063");
}

.ry44nabmj {
  fill: var(--svg-color--004fa0, #004fa0);
  d: path("m16.187 20.932l.021.146c-.073.123-.188.166-.325.149c-.017-.008-.025-.021-.021-.026q.004-.025.013-.024c-.061-.11-.1-.224.035-.312c.103-.036.21-.068.277.067");
}

.rz2748bpe {
  fill: var(--svg-color--343434, #343434);
  d: path("m13 30.25l-.083.53c-.024.027-.042.027-.067-.004c-.02.021-.041.032-.062.053c-.021-.006-.043-.006-.065-.01c.125-.188.183-.396.201-.617c.041-.015.062.01.076.048");
}

.rz41dlfcx {
  fill: var(--svg-color--575858, #575858);
  d: path("m15.166 35.554l.104-.039c.027.02.047.043.031.079c-.09-.015-.106.075-.156.123c-.016-.021-.034-.037-.051-.058c.024-.039.048-.069.072-.105");
}

.s_i3uqjzv {
  fill: var(--svg-color--edeeee, #edeeee);
  d: path("m13.44 19.657l.09.051c.049.052.102.1.133.162c.018.069-.008.125-.052.177a.2.2 0 0 1-.093.067c-.127 0-.26.075-.373-.035c-.086-.114-.084-.221.015-.332l.011-.008c.06-.117.176-.07.269-.082");
}

.s_pe4mr4k {
  fill: var(--svg-color--676767, #676767);
  d: path("M23.565 30.891c-.061-.103-.045-.217-.035-.326l.046-.106c.062.096.049.205.049.313c.035.069-.009.096-.06.119");
}

.s_q-l1zts {
  fill: var(--svg-color--242525, #242525);
  d: path("M14.931 32.667h-.049c.02-.092-.055-.226.106-.262z");
}

.s_vdbvp0d {
  fill: var(--svg-color--5f160e, #5f160e);
  d: path("M21.09 20.444a.17.17 0 0 1 .098.145c.022.064.041.121-.01.178a.62.62 0 0 0-.414-.037c.025-.083.1-.085.164-.079c.179.028.211-.051.162-.207");
}

.s-x1t7bpt {
  fill: var(--svg-color--f0f1f1, #f0f1f1);
  d: path("M17.487 31.857a.1.1 0 0 1-.04.019c-.056.043-.114.035-.175.021c-.084-.131-.029-.271-.047-.404a.1.1 0 0 1-.006-.043c-.033-.052-.021-.102-.008-.16c.059-.135-.08-.362.182-.404c.08.05.107.128.144.211c-.065.246.013.508-.05.76");
}

.s0_bk3kfm {
  fill: var(--svg-color--313131, #313131);
  d: path("M22.536 32.876h.043c.061.132.198.236.119.41l-.049.062c.006-.169-.146-.298-.113-.472");
}

.s0c2is_9k {
  fill: var(--svg-color--65501d, #65501d);
  d: path("M17.695 18.15q-.029.046-.06.091l-.449.004c-.098.027-.191.043-.285-.013c.083-.055.175-.036.263-.043c.024-.03.043-.073.083-.09c.083-.021.162-.028.232.036z");
}

.s0cc2_bac {
  fill: var(--svg-color--292a2a, #292a2a);
  d: path("M18.901 40.17a.6.6 0 0 0 .037-.316c.074.03.092.094.107.162q-.05.078-.098.159q-.02.037-.046-.005");
}

.s0j0hml3r {
  fill: var(--svg-color--221f08, #221f08);
  d: path("M22.839 37.18h.118q.053.072.103.153h-.051c-.059-.055-.113-.106-.17-.153");
}

.s0s4e8bzo {
  fill: var(--svg-color--42370d, #42370d);
  d: path("M15.214 39.601c.045.053.032.117-.012.131c-.074.021-.044-.039-.035-.074c.006-.02.031-.038.047-.057");
}

.s17h_rbzz {
  fill: var(--svg-color--fbda2a, #fbda2a);
  d: path("M22.688 36.927q-.05-.023-.107-.04c.055-.142.184-.038.268-.081a.1.1 0 0 0 .045.012c.019.031.033.059.053.09c-.087.069-.17.034-.259.019");
}

.s2j-t2c0l {
  fill: var(--svg-color--4b4b4b, #4b4b4b);
  d: path("M19.664 40.22c.07.124.086.271.104.408c-.188-.082-.103-.272-.15-.408q.022-.026.046 0");
}

.s2kxr8t-m {
  fill: var(--svg-color--1c100f, #1c100f);
  d: path("M17.593 36.864c.016-.014.03-.022.047-.041q.078.031.16.061c0 .035-.006.066-.053.035c-.037.009-.066.013-.102.021q-.028-.044-.052-.076");
}

.s3-voqbch {
  fill: var(--svg-color--2e2909, #2e2909);
  d: path("M15.248 37.552c-.019.02-.042.035-.063.059l-.188.034q-.032-.044-.065-.098c.104 0 .212 0 .316.005");
}

.s56t2j69h {
  fill: var(--svg-color--2e2c26, #2e2c26);
  d: path("M19.302 17.61q.05-.005.1-.004c-.057.083-.049.178-.047.266a.1.1 0 0 1-.053.025c-.043 0-.082.004-.117-.029c-.024-.057-.012-.1.01-.149a.3.3 0 0 1 .031-.056a.12.12 0 0 1 .076-.053");
}

.s5awhrbme {
  fill: var(--svg-color--1e1007, #1e1007);
  d: path("M24.505 37.33q-.008.027-.012.06c-.051.004-.105 0-.139.052q-.057.054-.11.012q-.033-.005-.067-.004c.051-.208.223-.073.328-.12");
}

.s5bcitktc {
  fill: var(--svg-color--c5c6c5, #c5c6c5);
  d: path("m19.72 28.577l-.049.063c-.031.038-.063.074-.117.051c-.047-.055-.094-.098-.092-.181q-.004-.025.006-.042c.057-.061.066-.133.092-.204l.017-.11a.3.3 0 0 0 .062-.008c.203-.043.059.118.099.169c.034.092-.014.176-.018.262");
}

.s5kqleb_s {
  fill: var(--svg-color--2d0605, #2d0605);
  d: path("M20.597 39.07c-.107-.06-.133-.16-.138-.271c.073.07.14.152.138.271");
}

.s6cpo7wjv {
  fill: var(--svg-color--231b1b, #231b1b);
  d: path("M19.06 41.755a.2.2 0 0 0-.068-.012v-.095c-.021-.056.006-.067.049-.056c.021.061.102.098.066.177c-.018-.002-.032-.01-.047-.014");
}

.s79m0ecuh {
  fill: var(--svg-color--453031, #453031);
  d: path("M20.627 25.18a.4.4 0 0 0-.091-.016c.082-.086.186-.047.282-.051c-.051.067-.122.053-.191.067");
}

.s7n7r0bzo {
  fill: var(--svg-color--e7e7e7, #e7e7e7);
  d: path("M20.18 29.833c.031-.06.041-.129.121-.137c.024.06.058.118.086.185c-.078.008-.16.055-.207-.048");
}

.s8nv5mb7z {
  fill: var(--svg-color--301b1b, #301b1b);
  d: path("M17.927 41.489c.026-.057.055-.107.084-.158c.121.017.066.093.051.146l-.012.02a1 1 0 0 0-.123-.008");
}

.s8zlooseu {
  fill: var(--svg-color--2e2809, #2e2809);
  d: path("M20.868 21.489c.023-.031.048-.07.073-.103c.137-.165.104-.255-.132-.271c.123-.125.218-.095.307.015c-.003.175-.017.339-.248.359");
}

.s9-4uac0g {
  fill: var(--svg-color--404040, #404040);
  d: path("M24.815 30.921c.017-.121 0-.247.051-.361c.033.01.036.037.05.061c-.014.129.097.285-.093.373q-.043-.034-.008-.073");
}

.s9q-i_b0t {
  fill: var(--svg-color--570404, #570404);
  d: path("M19.05 16.286c-.089.021-.207.181-.246-.051c.08.016.162.032.242.008c.018.008.021.021.018.027q-.006.017-.014.016");
}

.s9w2hcctf {
  fill: var(--svg-color--5a5435, #5a5435);
  d: path("m16.03 18.14l-.025.042c-.016.02-.035.032-.056.027l-.024-.027c.004-.012.004-.032.006-.047c.035 0 .067.005.099.005");
}

.sacjm7kjq {
  fill: var(--svg-color--303131, #303131);
  d: path("M18.58 38.78c.108.146.207.032.308-.016c-.002.132-.196.18-.143.332c.023.092.029.182-.059.241a.06.06 0 0 1-.014.046c-.047.012-.072-.012-.082-.053c.118-.189.057-.37-.01-.55");
}

.sb4l-rbbh {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M21.382 32.884v.775c-.685 0-1.367 0-2.048.008c-.075 0-.174-.06-.228.053q-.01 1.646-.012 3.294c-.035.058-.096.067-.158.076a3 3 0 0 1-.498-.005c-.045-.012-.086-.029-.112-.071c-.001-1-.004-2.01-.007-3.01c0-.097-.004-.188-.008-.288c-.057-.105-.154-.053-.229-.053c-.685-.008-1.368-.008-2.051-.008l.002.004a2.4 2.4 0 0 1-.005-.791c.07-.063.156-.067.242-.063c.681.006 1.361-.022 2.041.019c.004-.94.004-1.885.01-2.828a.79.79 0 0 1 .771.005c.002.938.006 1.883.01 2.823c.67-.041 1.342-.015 2.01-.021c.097 0 .192.004.269.079l-.002-.002");
}

.sb58i4bxt {
  fill: var(--svg-color--050505, #050505);
  d: path("M12.539 30.3a1 1 0 0 0-.136-.054c-.105-.133.117-.11.093-.205q.02-.036.045 0q0 .131-.002.259");
}

.sbumb_byq {
  fill: var(--svg-color--2e2f2f, #2e2f2f);
  d: path("M17.89 29.417q-.028-.001-.053.005q-.07-.083-.143-.165c-.014-.018-.02-.027-.014-.041c.004-.016.008-.02.012-.02c.105-.027.152.06.211.113l-.006-.004a1 1 0 0 1-.007.112");
}

.sc7ekkbnr {
  fill: var(--svg-color--1f2525, #1f2525);
  d: path("m17.681 29.786l.015.099c-.12.086-.247.067-.372.012c.098-.012.131-.094.18-.159q.024-.027.053 0c.022.014.041.037.078.029c.021-.002.036-.001.046.019");
}

.scpde1bun {
  fill: var(--svg-color--686868, #686868);
  d: path("M24.308 34.979c-.006-.033-.006-.074-.008-.107q.033-.046.074-.004c.038.228.026.457.018.689l-.033-.004c-.086-.094-.057-.209-.051-.318a.4.4 0 0 0 0-.256");
}

.sd_o4qbcs {
  fill: var(--svg-color--232424, #232424);
  d: path("M23.774 28.887h-.066q.015-.183.023-.367q.024-.033.043 0c.059.048.019.206.164.158h-.006c.071.167-.064.174-.158.209");
}

.sd699gvud {
  fill: var(--svg-color--3a1c1c, #3a1c1c);
  d: path("M14.306 34.442a.28.28 0 0 1 .063-.197q.022-.028.047-.008c-.022.09-.047.174-.069.262q-.07.009-.041-.057");
}

.sdkk7td4w {
  fill: var(--svg-color--544a11, #544a11);
  d: path("M18.843 17.237c.016 0 .029.008.047.012c0 .014 0 .033.002.041c.019.029.016.059-.012.082c-.209.037-.422.162-.623-.022c.076-.076.174-.043.262-.056c.043 0 .084-.008.108-.047h.161c.024.037.041.021.055-.01");
}

.sdlnh548y {
  fill: var(--svg-color--33302e, #33302e);
  d: path("m12.05 32.663l.022.004q-.004.294-.004.576q-.026.034-.043-.004l-.011-.1a1 1 0 0 1 .004-.416c.01-.017.02-.041.032-.06");
}

.se6e6ib7v {
  fill: var(--svg-color--454646, #454646);
  d: path("M15.04 31.717a1 1 0 0 0-.06.121a.1.1 0 0 0-.05-.021q-.06-.005-.071-.071c.032-.116.03-.252.181-.297q.023.031.014.049q-.008.022-.014.021z");
}

.se7c1ybbq {
  fill: var(--svg-color--2e0a09, #2e0a09);
  d: path("m16.1 35.24l.072-.05c.018.064.037.136.053.207c-.039-.022-.08-.039-.119-.06c-.072-.03-.047-.065-.006-.097");
}

.se7mylbpo {
  fill: var(--svg-color--545411, #545411);
  d: path("M16.272 26.392c-.086.035-.174.059-.256-.013a2 2 0 0 1 .225-.091q.02.001.037.014q.045.046-.006.09");
}

.se7w7vb1m {
  fill: var(--svg-color--3c1109, #3c1109);
  d: path("M24.04 39.33q.03.047.06.104c-.06.081-.125.05-.215.017c.06-.067.105-.127.152-.178c.018.004.023.021.02.033q-.006.025-.017.024");
}

.se92-3bbj {
  fill: var(--svg-color--cdb423, #cdb423);
  d: path("M12.603 37.536c-.012-.063-.006-.121.043-.17c.084-.094.168-.063.252-.004c.06.065.023.121-.018.182c-.091.027-.181-.016-.277-.008");
}

.seedbv-1s {
  fill: var(--svg-color--fad428, #fad428);
  d: path("M20.866 21.548c-.115-.083-.291-.09-.334-.264c-.114-.129-.016-.254.018-.377a.46.46 0 0 1 .215-.177c.109-.098.237-.043.357-.026c.025.004.049.016.07.026c.063.056.068.125.058.204c-.008.057-.013.118-.043.173c-.011.009-.021.013-.03.021l-.058.004c-.032.021-.06-.028-.089-.008c.104.188-.037.271-.16.365q-.005.03-.004.059");
}

.sexcyo6pw {
  fill: var(--svg-color--383c3c, #383c3c);
  d: path("M16.04 32.888c-.002.259-.002.52-.002.775l-.052-.004l-.004-.733c-.02-.046.004-.062.043-.062q.013.006.015.024");
}

.sfne46rmq {
  fill: var(--svg-color--35180c, #35180c);
  d: path("M22.687 37.28q.001.032.007.068l-.005.016a.1.1 0 0 1-.039.017c-.063-.039-.119-.095-.166.021c-.038.084-.075-.01-.112-.013c.055-.187.205-.084.315-.109");
}

.sfs7w3bmv {
  fill: var(--svg-color--423d28, #423d28);
  d: path("M18.494 19.811q-.03-.001-.058.004c-.008-.099-.088-.212.068-.263a.35.35 0 0 0-.01.259");
}

.sg5c5cboo {
  fill: var(--svg-color--565145, #565145);
  d: path("M22.966 18.971c.033-.041.063-.075.094-.118c.035.041.065.079.103.118c-.004.021-.004.047-.008.062c-.066-.015-.15.03-.189-.062");
}

.sgxg7u14c {
  fill: var(--svg-color--2e2d2d, #2e2d2d);
  d: path("M13.642 27.542c-.008-.047-.004-.09-.053-.121a3 3 0 0 0 .059-.157c.013-.04.037-.065.08-.047c.019.118-.03.221-.086.325");
}

.silj55bmy {
  fill: var(--svg-color--c9b222, #c9b222);
  d: path("M14.79 18.864c-.002-.072-.018-.145.028-.207c.065-.057.142-.047.219-.037q.032.024.062.043a.1.1 0 0 1 .008.069a.37.37 0 0 1-.151.149c-.059.024-.115.024-.166-.017");
}

.sivrfsb7b {
  fill: var(--svg-color--282a2a, #282a2a);
  d: path("M19.41 38.79c.103.246.052.502.063.752q-.031.026-.059 0c.03-.25-.069-.498-.004-.752");
}

.sjr0z3cbl {
  fill: var(--svg-color--f4f4f4, #f4f4f4);
  d: path("M23.423 29.1a.1.1 0 0 1 .037 0c.12.013.041-.215.191-.16c.142.142.083.357.174.519c.027.092.025.188.061.275a.7.7 0 0 1 .008.244c-.024.094-.041.188-.082.274c-.069.095-.152.11-.246.036c-.047-.047-.073-.109-.105-.17a.9.9 0 0 1-.109-.32c-.004-.024-.006-.051-.008-.071c-.025-.149-.07-.299-.064-.448c.01-.051.045-.09.063-.138c.013-.041.032-.072.08-.041m-.735.577l.104-.057c.063-.039.105-.015.145.037c.066.105.076.235.115.35a.84.84 0 0 1-.021.408c-.021.09-.039.188-.118.252c-.101.043-.149-.023-.207-.084c-.06-.086-.12-.172-.135-.281c-.003-.143-.06-.275-.076-.417c-.009-.146.139-.134.193-.208");
}

.sjy2awskn {
  fill: var(--svg-color--c3aa21, #c3aa21);
  d: path("M21.18 21.958c-.053.106-.142.043-.209.063l-.047-.114c.108-.096.191-.076.256.051");
}

.sk_6173jv {
  fill: var(--svg-color--242525, #242525);
  d: path("M20.18 40.812c.018-.02.031-.045.047-.061c-.018.117.093.227.014.34c-.067-.078-.048-.18-.061-.279");
}

.sk4s012es {
  fill: var(--svg-color--303232, #303232);
  d: path("M17.849 27.786c-.016-.086-.09-.172 0-.258c.019.086.092.172 0 .258");
}

.sk9ri61_t {
  fill: var(--svg-color--164b7d, #164b7d);
  d: path("M15.813 22.87c-.012.084-.051.139-.125.139c-.09 0-.137-.061-.131-.154c.002-.082.057-.122.135-.111c.075.007.12.053.121.126");
}

.skis1_b7c {
  fill: var(--svg-color--d5bb24, #d5bb24);
  d: path("M18.54 22.396c-.02-.021-.041-.036-.063-.055l.055-.063a.33.33 0 0 1 .32-.065c.053.022.096.047.104.11c-.013.07-.061.113-.122.142c-.103.003-.207-.002-.294-.069");
}

.sks-jnu5b {
  fill: var(--svg-color--656450, #656450);
  d: path("m15.878 18.247l-.002-.06c.02 0 .033-.004.053-.008l-.002.008c.015.015.019.024.017.04q0 .019-.005.02a.06.06 0 0 1-.061 0");
}

.skxhi6b6n {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M24.614 36.845a2 2 0 0 0-.158.094c-.038-.146-.072-.296-.109-.441c-.117-.09-.104-.229-.144-.354c-.008-.04-.017-.074-.024-.119c-.022-.148-.056-.305-.088-.453c-.015-.08-.021-.16-.05-.232c-.017-.067-.019-.135-.021-.201c0-.096.004-.186-.004-.277c-.008-.105-.104-.174-.129-.271c-.026-.096-.022-.188-.022-.288c0-.113.004-.224-.035-.328c-.022-.13-.017-.261-.019-.392c.002-.082.002-.164.011-.241c.012-.149-.081-.276-.06-.427c-.008-.146.02-.299-.031-.446a.4.4 0 0 1-.016-.084c0-.188-.029-.376.018-.562a.15.15 0 0 1 .047-.063c.053-.039.117-.049.174-.073c.098-.075.189-.192.316-.05c.029.021.057.05.082.07c.102.066.094.162.076.262c-.031.08-.026.165-.021.251v.129a.22.22 0 0 0-.051.239v.07c-.061.057-.057.129-.061.205c-.019.094-.052.189.004.286v.095c.024.058-.007.108 0 .156v.256c.002.373-.009.746.008 1.119l.018.083a.4.4 0 0 1 .025.126c.002.083 0 .172 0 .25c.006.105-.012.217.021.322c.013.074.004.152.029.225c.009.07-.005.147.062.203c-.004.03-.004.072-.006.104c-.007.149.041.284.08.428c.004.115.042.222.08.328h-.002");
}

.sm6xajuia {
  fill: var(--svg-color--30251f, #30251f);
  d: path("M16.654 26.749q.183-.034.364-.063c-.117.105.009.178.041.26q-.017.045-.037.004c-.115-.07-.215-.174-.364-.149c-.013-.011-.021-.024-.017-.031q.007-.02.013-.021");
}

.sm7h5yb3m {
  fill: var(--svg-color--d5d6d6, #d5d6d6);
  d: path("M19.04 27.575c.021-.066.037-.138.058-.205c.008-.117.064-.074.123-.039q.018.031.015.076c-.003.023-.007.051-.007.073c.007-.028.009-.054.027-.073c.028-.01.051-.014.077-.01c.151.125.013.275.043.414a.4.4 0 0 1-.026.114a.3.3 0 0 1-.064.098c-.041.032-.083.056-.137.039c-.053-.09-.1-.034-.146.005a.05.05 0 0 1-.063-.009c-.125-.069.041-.133.007-.2a.7.7 0 0 1 .093-.283");
}

.smf-mmben {
  d: path("M15.873 21.17c0 .021.002.034.007.052c0 .02-.005.035-.007.055a2 2 0 0 0-.216-.026c.063-.115.155-.047.216-.081");
}

.snwfetbnc {
  fill: var(--svg-color--eacf27, #eacf27);
  d: path("M18.741 22.854q-.05.03-.098.067c-.041-.109-.168-.118-.221-.208l.004-.023c.146-.094.313-.004.465-.047q.066.004.11.053c-.016.168-.09.245-.26.158");
}

.so13xueml {
  fill: var(--svg-color--3a3b3a, #3a3b3a);
  d: path("M23.316 31.637c-.114.142-.029.295-.029.444c0 .103.013.203.021.31c-.196-.133-.041-.347-.115-.501q-.042.013-.086.008c.041-.236-.073-.494.086-.712c.156.121.265.252.123.451");
}

.spmauul-h {
  fill: var(--svg-color--3a3622, #3a3622);
  d: path("M22.06 36.29c.002-.028.002-.063.002-.092c.07.023.164.004.211.088c-.071-.019-.141.064-.213.004");
}

.sqlvo41pc {
  fill: var(--svg-color--322c0c, #322c0c);
  d: path("M18.368 21.13c-.118-.142-.201.013-.298.06c.06-.259.153-.287.351-.113c-.016.018-.022.048-.053.053");
}

.sqwztpblp {
  fill: var(--svg-color--837115, #837115);
  d: path("M14.263 37.422c-.072-.029-.14-.048-.209-.071c.004-.061.047-.1.098-.121c.076.01.162-.017.225.051c-.013.07-.062.105-.114.141");
}

.sruawybkf {
  fill: var(--svg-color--686869, #686869);
  d: path("M18.411 38.24c-.023.018-.049.03-.076.049c-.007-.178-.05-.36.029-.535c.031.004.035.033.051.058q0 .21-.004.428");
}

.ss3wxcbwc {
  fill: var(--svg-color--414141, #414141);
  d: path("M20.09 28.16v.041c-.031.139.041.269.034.405c-.004.036-.019.071-.054.086c-.075-.047-.094.071-.157.063q-.042-.005-.058-.04c-.029-.157.055-.33-.037-.479a.1.1 0 0 1 .023-.103c.074-.06.149-.066.226-.005c.01.012.014.019.023.032");
}

.ssbb2crnc {
  fill: var(--svg-color--34230a, #34230a);
  d: path("M22.741 36.632c-.145-.027-.287-.079-.428.019q-.015.035-.032 0l-.062-.03c-.019-.004-.035-.012-.053-.012c0-.023-.004-.039-.004-.06c.02-.021.042-.032.066-.044c.125-.016.248 0 .371-.016q.044.014.082.03c.064.013.076.058.06.113");
}

.ssu31jbez {
  fill: var(--svg-color--48421f, #48421f);
  d: path("M21.854 18.604c.021-.043.057-.051.101-.051l.067.156l-.008.01c-.106.039-.202.063-.16-.115");
}

.st8kkl92y {
  fill: var(--svg-color--636465, #636465);
  d: path("m22 32.671l-.055.115c-.039-.08-.083-.164.013-.242c.046.033.054.078.042.127");
}

.stslcnb2e {
  fill: var(--svg-color--6e673f, #6e673f);
  d: path("M20.71 17.854c.047.009.1.009.113.065c.031.037.08.06.047.117c-.027.024-.063.028-.1.024a.3.3 0 0 1-.125-.063a.11.11 0 0 1-.047-.09c.02-.045.077-.037.112-.053");
}

.suty2d40d {
  fill: var(--svg-color--3c3d3d, #3c3d3d);
  d: path("M15.468 32.721c-.023.092.062.235-.113.257c-.066-.105.086-.161.063-.261q.024-.018.05.004");
}

.sv7e0ogiq {
  fill: var(--svg-color--212222, #212222);
  d: path("m17.7 29.2l-.007.06q-.025.001-.052-.004l-.033-.048c-.027-.16.021-.342-.121-.477c-.014-.007-.02-.023-.016-.039q.003-.017.008-.016c.056-.02.109 0 .168 0q.027.017.041.059c.017.154.114.307.012.465");
}

.sv7ghibji {
  fill: var(--svg-color--e1e3e5, #e1e3e5);
  d: path("M15.556 19.354c.019-.021.043-.043.063-.062c.067.095.081.224.144.322a1 1 0 0 0 .051.09c-.021.06-.043.113-.114.125c-.071-.02-.083-.082-.101-.138c-.018-.069-.053-.132-.073-.196c-.011-.049-.011-.097.03-.141");
}

.sv8s86bdi {
  fill: var(--svg-color--3e1d0b, #3e1d0b);
  d: path("m15.15 21.982l.006-.291c.088.103.072.199-.006.291");
}

.sw1ufxbds {
  fill: var(--svg-color--feee2c, #feee2c);
  d: path("M22.06 36.549q-.015-.024 0-.052q.027-.03.059-.008a.1.1 0 0 0 .012.03c-.007.013-.012.019-.016.03z");
}

.swqwdl6-h {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-4H0z");
}

.sx0vsbndx {
  fill: var(--svg-color--5e1c0d, #5e1c0d);
  d: path("M13.739 21.39q.034-.006.07-.007a.35.35 0 0 1 .203.098c-.008.043-.011.091-.019.134c-.053-.11-.164-.155-.254-.225");
}

.sx1q7gari {
  fill: var(--svg-color--fdfdfd, #fdfdfd);
  d: path("M14.775 33.872q.014-.023-.003-.043c-.041-.17-.143-.33-.067-.515a.7.7 0 0 1 .028-.157c.017-.053.035-.095.056-.143c.039-.117.048-.238.083-.355c.016-.084.049-.162.055-.246q0-.04.012-.072c.041-.098.025-.213.097-.301a.16.16 0 0 1 .097-.025q.061-.004.123-.02c.084-.008.149-.147.247-.028c.026.063.03.128.032.192c0 .105.002.211-.01.322c-.008.069-.043.141-.043.217c-.002.103-.068.188-.078.295a.3.3 0 0 1-.012.063c-.027.115-.051.229-.092.34c-.017.04-.054.075-.07.117c-.014.056-.053.104-.062.161c-.028.094-.075.179-.112.265q-.055.077-.108.155c-.183.013-.185-.101-.173-.222");
}

.sxags2tbu {
  fill: var(--svg-color--280909, #280909);
  d: path("m12.12 29.368l.012.112c.002.056.016.123-.06.149c.001-.095-.022-.185.048-.261");
}

.sxnbp_qeb {
  fill: var(--svg-color--181717, #181717);
  d: path("M23.948 30.25q-.008-.051-.012-.1c.016-.039.033-.07.048-.104c.101.09.168.044.224-.052c.014 0 .023 0 .037-.004c.02.196-.164.138-.25.205c.024.055-.003.067-.047.055");
}

.sy76ipw-o {
  fill: var(--svg-color--f2f2f1, #f2f2f1);
  d: path("M13.247 19.288c.061-.123.204-.075.283-.152c.083.011.125.07.154.146a.4.4 0 0 1 .039.211a.6.6 0 0 1-.119.226a.2.2 0 0 1-.068.022a.3.3 0 0 1-.143-.043c-.059-.031-.123-.047-.156-.113c-.052-.1-.088-.203.01-.297");
}

.sypg0bbdh {
  fill: var(--svg-color--64240d, #64240d);
  d: path("M22.11 21.237c.015-.01.029-.01.047-.01l-.002.158c-.073 0-.088.083-.146.104c-.046-.119.09-.158.101-.252");
}

.sz9f5obtt {
  fill: var(--svg-color--d5bd24, #d5bd24);
  d: path("M23.511 20.392c-.113.141-.185.326-.346.43c-.122.084 0 .191-.016.285c-.016 0-.03 0-.045-.012c-.034-.016-.064-.035-.1-.051c-.039-.104-.055-.201.035-.288c.102-.161.201-.322.372-.421c.061-.033.08.01.1.057");
}

.szwnu799w {
  fill: var(--svg-color--4b4831, #4b4831);
  d: path("M15.195 19.708q0-.03.003-.051c.045-.091.195-.035.219-.158l.079.053c.024.036.052.066.079.102c-.02.021-.043.039-.061.055c-.105-.07-.21-.067-.319-.001");
}

.t_vntdbkf {
  fill: var(--svg-color--531413, #531413);
  d: path("M24.18 25.694c-.129.045-.195-.068-.287-.115c-.02-.013-.023-.022-.02-.037q.009-.017.016-.016a.52.52 0 0 1 .291.168");
}

.t-982-xpn {
  fill: var(--svg-color--430905, #430905);
  d: path("M15.97 39.491c.028.067.06.138.086.207c-.248.071-.071-.15-.141-.207q.027-.033.055 0");
}

.t-t8tmkzu {
  fill: var(--svg-color--581d0a, #581d0a);
  d: path("M14.775 18.657q-.02-.09-.042-.179c.076.033.142.101.238.067c.023-.021.047-.018.067 0q.025.025.013.066c-.059.055-.135.063-.209.071c-.026.002-.046-.01-.067-.025");
}

.t0-x_-b4j {
  fill: var(--svg-color--252727, #252727);
  d: path("M19.826 37.848c.125.077.086.228.153.326c-.09.018-.066.104-.106.163c-.026.012-.051.008-.069-.021c-.035-.155-.135-.319.022-.468");
}

.t0eqj8bep {
  fill: var(--svg-color--313232, #313232);
  d: path("M19.696 39.854c-.184-.029-.123.068-.084.162q-.023.032-.047 0c-.053-.057-.051-.124-.055-.195c-.021-.056-.142-.029-.111-.129l.007.004c.041-.031.077-.072.134-.072c.109.037.188.094.156.23");
}

.t0eurwbxs {
  fill: var(--svg-color--562523, #562523);
  d: path("M23.411 34.69c.078.121.07.271.104.404c-.143-.107-.17-.242-.104-.404");
}

.t17z4dbme {
  fill: var(--svg-color--f7f8f8, #f7f8f8);
  d: path("M21.693 34.671c-.146 0-.294 0-.259-.217c.014-.013.016-.022.009-.045c.086-.068.174-.037.269-.018a.5.5 0 0 0 .098.01c.086.045.203 0 .269.096c.271.106.448.351.702.481c.119.039.082.104.016.165a1.4 1.4 0 0 1-.172.063c-.084-.004-.171.031-.255-.016c-.108-.074-.171-.197-.271-.279a.35.35 0 0 0-.186-.123a.4.4 0 0 1-.083-.037c-.051-.022-.101-.041-.137-.08");
}

.t1zywotsv {
  fill: var(--svg-color--eed228, #eed228);
  d: path("M15.09 36.678c-.005.006-.009.017-.012.022l-.004.004c-.291.104-.314.096-.391-.074h-.002c.153-.133.294-.155.409.048");
}

.t2a-f8bfj {
  fill: var(--svg-color--fbd629, #fbd629);
  d: path("M17.484 21.11c-.108.019-.218.023-.312-.033c-.104-.073-.078-.172-.066-.271c.109-.142.236-.188.383-.05h-.005c.104.066.094.165.058.263c-.02.027-.039.062-.058.091");
}

.t2czzykqs {
  fill: var(--svg-color--3d2727, #3d2727);
  d: path("M21.476 36.18c-.053.086-.028.177-.008.268c-.049-.021-.093-.035-.131-.055c-.027.027-.046.027-.066-.004c.055-.086.111-.178.164-.266c.025.019.037.035.041.057");
}

.t33tzac1f {
  fill: var(--svg-color--3b2f30, #3b2f30);
  d: path("M20.763 32.1q-.023.001-.043-.004c.035-.07.056-.139-.006-.209c.18.031.127.119.049.213");
}

.t3x4n7bet {
  fill: var(--svg-color--796c22, #796c22);
  d: path("M21.812 19.948c-.034.098-.098.017-.149.027a.36.36 0 0 1 .093-.264c.106.004.063.076.057.13a1 1 0 0 0-.001.107");
}

.t3zxf6b9c {
  fill: var(--svg-color--222323, #222323);
  d: path("m24.04 31.05l.049-.061q.033.21.063.42c-.106-.1-.106-.231-.112-.359");
}

.t55swsvts {
  fill: var(--svg-color--441707, #441707);
  d: path("M18.06 20.03c.02 0 .037-.005.056-.005c.261-.114.31-.095.387.105c-.088-.011-.218-.187-.239.067a8 8 0 0 1-.204-.167");
}

.t68mwrngk {
  fill: var(--svg-color--7b230e, #7b230e);
  d: path("M21.543 21.649c-.091-.07-.108.032-.153.066c-.037-.074-.069-.148-.006-.223c.063-.037.08.023.11.051c.019.02.033.039.052.059q.024.017.014.036a.02.02 0 0 1-.017.011");
}

.t77n7lr2c {
  fill: var(--svg-color--f4f4f4, #f4f4f4);
  d: path("M23.728 31.46c-.096.104-.096.253-.17.361c-.045.051-.09.039-.143.004c0-.08-.061-.123-.1-.188c.033-.159-.067-.298-.104-.447c-.033-.019-.043-.05-.045-.086c.004-.046.021-.09.028-.132c-.017-.134-.087-.266-.017-.395q.03-.059.088-.059a.16.16 0 0 0 .146-.094l.056-.02c.073.031.047.103.062.16c.065.09.022.217.075.307c.007.056-.012.106-.01.156c.032.149.063.301.135.438z");
}

.t8_m_7b0b {
  fill: var(--svg-color--4b2120, #4b2120);
  d: path("M17.597 34.549q-.16-.046-.33-.091c.014-.022.035-.034.06-.049c.098.033.231-.011.27.14");
}

.t8bf0-n4q {
  fill: var(--svg-color--282828, #282828);
  d: path("M24.466 36.958c-.1-.004-.102-.084-.115-.146c-.037-.04-.078-.07-.092-.124c-.018-.065-.016-.133.025-.188q.034-.028.075-.016c.122.107.112.262.134.401a.12.12 0 0 1-.027.073");
}

.t8o5ombwv {
  fill: var(--svg-color--252525, #252525);
  d: path("M23.938 27.838c-.043.012-.102.024-.105-.036c-.01-.188-.182-.337-.113-.545c.021-.02.035-.02.047.012c.041.197.24.346.17.573z");
}

.t8q8jf2sx {
  fill: var(--svg-color--6e6430, #6e6430);
  d: path("M21.736 19.441c-.031.091-.031.201-.142.24c.038-.081.022-.201.142-.24");
}

.tah9_4f0a {
  fill: var(--svg-color--41201f, #41201f);
  d: path("M20.396 38.14a.53.53 0 0 1-.103-.271c.011-.022.023-.022.038-.008c.063.087.1.173.065.279");
}

.tbpge7bzh {
  fill: var(--svg-color--584d11, #584d11);
  d: path("M15.813 22.329q.213-.048.425-.103c-.111.163-.264.154-.425.103");
}

.tbrqn4xcu {
  fill: var(--svg-color--cfb422, #cfb422);
  d: path("M18.423 22.714c-.084-.043-.174-.083-.259-.122c-.047-.035-.038-.086-.019-.138c.107-.039.223-.078.332-.112q.057.01.066.067c-.027.099-.104.172-.104.277q-.003.016-.016.028");
}

.tc-kg5w1b {
  fill: var(--svg-color--421514, #421514);
  d: path("M20.675 41.17c.006 0 .02-.007.028-.007c.058.072.038.143.017.22c-.115.106-.176 0-.242-.065c.104.011.244.048.197-.148");
}

.tck4ebchy {
  fill: var(--svg-color--39210c, #39210c);
  d: path("M24.25 37.868c-.002-.021-.004-.035-.004-.052c.078-.067.203.052.271-.063q.072-.018.089.058c-.102.121-.238.046-.356.057");
}

.td8ebjh7s {
  fill: var(--svg-color--333434, #333434);
  d: path("M23.361 29.16c.01.047.012.086-.052.104c-.022.022-.028.056-.041.09c-.135.22-.164.229-.284.079a.2.2 0 0 1 .034-.059c.064-.055.064-.186.195-.172l.098-.043c.019-.028.032-.028.05.001");
}

.tdd50zpoj {
  fill: var(--svg-color--6b0a09, #6b0a09);
  d: path("M21.425 26.11c.176-.084.354-.043.53.004a.65.65 0 0 1-.53-.004");
}

.tdsx5cc0r {
  fill: var(--svg-color--431b19, #431b19);
  d: path("M18.11 17.296c.014.037.03.066.046.104a.3.3 0 0 1-.02.205a.11.11 0 0 1-.086.063l-.146-.122c.183 0 .144-.147.167-.253c.01-.018.027-.018.039.003");
}

.tep21i_yu {
  fill: var(--svg-color--717171, #717171);
  d: path("M13.13 34.827c0-.386-.054-.777.034-1.16c.003.387.018.775-.034 1.16");
}

.tfewz36yc {
  fill: var(--svg-color--272829, #272829);
  d: path("M14.21 31.903c-.109-.068-.035-.181-.06-.271a.27.27 0 0 1-.07-.173a.09.09 0 0 1 .074-.078q.042 0 .073.021c.062.141.07.297.103.439l-.013.036a1 1 0 0 1-.107.026");
}

.tfp9mdb0h {
  fill: var(--svg-color--542d0d, #542d0d);
  d: path("m22.552 21.393l-.074-.007a.26.26 0 0 1-.061-.26c.122-.027.15.222.303.103z");
}

.th_iaxb9h {
  fill: var(--svg-color--242525, #242525);
  d: path("M24.14 35.554h-.04q-.024-.111-.049-.209c.016-.029.027-.029.043 0c.072.06.054.13.046.209");
}

.th4wovb4j {
  fill: var(--svg-color--48400f, #48400f);
  d: path("M13.188 37.921h.027q.044.024.008.061c.022.102-.016.161-.108.188c-.021-.012-.052-.016-.056-.049c.035-.045.14-.061.061-.149z");
}

.thd9e8bmf {
  fill: var(--svg-color--4d3535, #4d3535);
  d: path("M20.625 31.876c-.069.035-.077.177-.188.131c-.098-.044-.1-.146-.09-.245c.06.134.156.153.278.114");
}

.thdo36_pl {
  fill: var(--svg-color--332929, #332929);
  d: path("M18.431 41.684q-.034.035-.063.071l-.086.033c.007-.098.063-.164.145-.215q-.001.057.004.111");
}

.thme2ebgx {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("M17.647 31.944c-.006.016-.008.022-.006.039c-.086.088-.215.083-.318.129c-.064.012-.131-.008-.191.027c-.15.034-.293.07-.43-.031c-.083-.082-.105-.16.016-.229c.063-.074.099-.016.141.027c.127.112.158.004.184-.091c.041-.137-.053-.247-.104-.362c-.023-.094.011-.155.082-.207l-.004.004c.06-.086.016-.185.027-.274c-.091-.261-.16-.067-.236.013c-.043 0-.09-.004-.113-.049c-.059-.07-.118-.136-.008-.215c.136-.1.289-.035.435-.048c.084.048.179.007.263.026c.09.029.17.067.235.131l.065.015c-.051.368.018.734-.038 1.095");
}

.thp-x7b4f {
  fill: var(--svg-color--7b6a15, #7b6a15);
  d: path("M16.654 22.01q.001-.044-.004-.085c.106 0 .213-.009.315-.009c.03.021.03.035 0 .056c-.094.082-.206.038-.311.038");
}

.ti8rmjl_d {
  fill: var(--svg-color--f6f6f6, #f6f6f6);
  d: path("M21.546 35.644c-.003-.016-.009-.033-.009-.056c-.034-.144.047-.103.12-.069c.05.027.095.069.145.104c.103.072.176.16.192.295c.011.131.04.261-.017.39c-.016.134-.152.199-.178.326c-.218.136-.268-.043-.332-.187c-.115-.08-.07-.17-.025-.264a1.4 1.4 0 0 0 .104-.539");
}

.tjdumck4k {
  fill: var(--svg-color--7f7f7f, #7f7f7f);
  d: path("m17.578 28.14l.011.066c-.082.076-.014.195-.086.275c-.035.034-.078.07-.135.034c-.064-.104-.038-.207-.018-.315a.4.4 0 0 0-.018-.057c.076-.055.148-.09.217.01a.04.04 0 0 1 .029-.013");
}

.tjjgvxuif {
  fill: var(--svg-color--212727, #212727);
  d: path("M24.18 27.06c-.052-.146-.082-.25-.115-.354c.019-.008.039-.012.062-.021c.029.113.107.21.053.375");
}

.tjroydayv {
  fill: var(--svg-color--553939, #553939);
  d: path("M23.644 25.476a4 4 0 0 1-.244-.102q.181-.099.244.102");
}

.tkz06_b-b {
  fill: var(--svg-color--221f08, #221f08);
  d: path("M19.312 17.87a.1.1 0 0 0 .041 0q.093.058.129.156l-.127.051c-.108.006-.09-.074-.09-.145a.2.2 0 0 1 .047-.062");
}

.tl0l56b0o {
  fill: var(--svg-color--122036, #122036);
  d: path("M14.839 22.913c-.072.271-.039.304.307.314c-.012.057-.059.051-.092.059a.2.2 0 0 1-.065.025a.2.2 0 0 1-.062-.027c-.233-.127-.248-.196-.088-.371");
}

.tlu6zsezk {
  fill: var(--svg-color--39350e, #39350e);
  d: path("M14.418 38.803v-.034c.103-.083.204-.052.312-.01c.016.014.02.023.016.035c-.007.009-.014.019-.016.019a6 6 0 0 0-.312-.01");
}

.tlzpnbcpw {
  fill: var(--svg-color--554d1d, #554d1d);
  d: path("m15.353 36.489l-.055.021l-.031-.013c-.107-.051-.229-.025-.338-.063a.1.1 0 0 1-.056-.042q.03-.046.06-.101a.2.2 0 0 1 .056-.045a.57.57 0 0 1 .356.041c.045.068.037.136.008.202");
}

.tmbo0cc3k {
  fill: var(--svg-color--62160d, #62160d);
  d: path("M19.304 16.549a.1.1 0 0 1 .004.041c-.051.083-.084.208-.209.071c.086-.004.138-.071.205-.112");
}

.tnc9leb2t {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M24.05 34.827c.016-.006.028-.013.045-.017v.326c-.056.007-.07-.026-.074-.073c.01-.078-.038-.166.029-.236");
}

.tne677bit {
  fill: var(--svg-color--403333, #403333);
  d: path("M18.655 42.27c.076-.027.117-.12.212-.109c-.044.092-.079.198-.212.109");
}

.to1ptoqrc {
  fill: var(--svg-color--4a4735, #4a4735);
  d: path("M16.604 26.452c-.018-.004-.036-.008-.055-.021q-.053-.13-.105-.268c.013-.02.029-.023.047 0c.045.092.133.17.113.289");
}

.tpkjppb8o {
  fill: var(--svg-color--341b09, #341b09);
  d: path("M16.599 23.417c-.02-.012-.039-.03-.063-.039a.5.5 0 0 1 .327-.043a.1.1 0 0 0-.009.033c-.085.016-.169.035-.255.049");
}

.tpuerz3ss {
  fill: var(--svg-color--a9983b, #a9983b);
  d: path("M22.423 20.338a.3.3 0 0 0 .051.004c.008.063.021.118-.043.161q-.028-.03-.028-.063c-.001-.035-.001-.072.02-.102");
}

.tq_oysy5o {
  fill: var(--svg-color--f8d428, #f8d428);
  d: path("M18.499 20.13c-.088-.187-.262-.06-.387-.105l.042-.125c.047-.09-.032-.172-.015-.264c0-.022.006-.047.022-.067l.019-.066c.013-.055.002-.113.008-.17c.014-.432-.008-.864.012-1.295a.2.2 0 0 1 .027-.082c.146-.099.22.027.31.103a.15.15 0 0 1 .028.071a.66.66 0 0 0 .047.381c.012.066-.012.117-.049.166c-.051.056-.066.115-.018.177a.2.2 0 0 1 .026.067a.3.3 0 0 1-.036.204c-.057.07-.037.138.014.207q.019.03.022.063a.2.2 0 0 1 0 .104a.3.3 0 0 1-.044.092c-.047.066-.047.137-.027.212c.023.056.059.104.066.165c-.012.056.006.128-.067.162");
}

.tq2buwbmz {
  fill: var(--svg-color--191818, #191818);
  d: path("M22.587 30.624c-.027.082.02.248-.169.158c.039-.057.076-.105.112-.162c.018 0 .038.004.057.004");
}

.tqp9atbom {
  fill: var(--svg-color--4c3c12, #4c3c12);
  d: path("M17.695 18.15q.18-.01.36-.016c.139.016.123.129.125.217c.006.263.018.521-.01.786c-.033.083-.037.191-.158.204l.002-.677c-.002-.383-.002-.383-.379-.424c-.027-.057.021-.075.06-.09");
}

.tqybrf_lr {
  fill: var(--svg-color--1d1e1e, #1d1e1e);
  d: path("m23.267 30.517l-.062.053c-.028.047-.056.092-.116.047c-.029-.052-.021-.101.016-.147a.4.4 0 0 1 .06-.058c.033.034.066.066.102.105");
}

.trt712bfz {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M19.31 41.548c0 .025-.002.06-.006.086q-.029.151-.186.156v-.015l-.014-.006c-.03-.043-.073-.083-.098-.133l-.09-.175l-.031-.062c-.033-.071-.056-.149-.086-.227l-.023-.062c-.018-.07-.039-.138-.049-.203s-.021-.123-.039-.18a.44.44 0 0 1 .004-.227a.6.6 0 0 1 .097-.146c.056-.063.085-.138.118-.213c.031-.061.047-.138.132-.148c.065.019.095.074.126.129c.028.051.075.096.104.154c.053.094.048.207.07.31c.045.13.037.265.041.397c-.01.193.034.389-.07.565");
}

.trzeifb2l {
  fill: var(--svg-color--dbdcdc, #dbdcdc);
  d: path("M19.937 27.629c-.006.11-.034.216.019.315c-.015.073-.022.144-.099.184c-.156-.012-.129-.117-.112-.229c.019-.109-.017-.236.095-.318q.041.026.097.048");
}

.tsiubdecw {
  fill: var(--svg-color--373435, #373435);
  d: path("M17.01 35.36c.002-.013.004-.022 0-.04c.129.127.088.254.004.381c-.028-.037-.019-.074 0-.107z");
}

.tsxo4ig5u {
  fill: var(--svg-color--505151, #505151);
  d: path("M18.572 37.23c-.03.079-.032.169-.097.232c-.088-.096-.006-.161.033-.232q.037-.038.064 0");
}

.tt_jzgrnv {
  fill: var(--svg-color--ddd, #ddd);
  d: path("M19.464 27.327c-.097-.06.026-.119 0-.174c.092-.121.111.01.156.047c-.016.088-.064.135-.156.127");
}

.tt3k88b9y {
  fill: var(--svg-color--190303, #190303);
  d: path("m21.911 26.593l-.004-.109c.04-.012.098-.035.109.012c.019.068-.05.085-.105.097");
}

.ttudnrbja {
  fill: var(--svg-color--dfc226, #dfc226);
  d: path("M12.854 38.39c0-.019 0-.026.002-.046c.008-.014.017-.018.021-.029c.061-.02.114-.074.184-.029a.4.4 0 0 1 .05.056c.073.073.067.147-.002.221c-.066.03-.107-.008-.149-.048l-.104-.069c-.014-.004-.02-.021-.014-.036q.008-.022.012-.02");
}

.tu26svptj {
  fill: var(--svg-color--65170d, #65170d);
  d: path("M16.292 22.954q.001-.02-.004-.043c.105.021.227-.047.318.047c-.104.059-.209.031-.314-.004");
}

.tv7s6acbe {
  fill: var(--svg-color--574f2e, #574f2e);
  d: path("M15.769 20.432c-.06-.026-.115-.052-.115.051c0 .06.031.13-.04.171a.13.13 0 0 1-.118-.064a.15.15 0 0 1-.009-.071c.08-.278.104-.291.303-.161a.1.1 0 0 1-.021.074");
}

.tvdo41blp {
  fill: var(--svg-color--212121, #212121);
  d: path("m15.61 34.706l.003.056c-.106 0-.192.108-.312.056c.081-.099.194-.116.309-.112");
}

.tvpnnsqsy {
  fill: var(--svg-color--f5f6f6, #f5f6f6);
  d: path("M22.638 18.471c.086-.085.191-.07.295-.07c.117.046.164.142.174.255a.26.26 0 0 1-.037.125a.31.31 0 0 1-.313.075a.27.27 0 0 1-.152-.141a.2.2 0 0 1-.018-.083c.004-.059.035-.107.051-.161");
}

.twcq74b_v {
  fill: var(--svg-color--484226, #484226);
  d: path("M22.966 18.971c-.065-.104-.207-.004-.277-.099q.008-.054.062-.067c.109.047.201-.039.304-.043q.005.047.006.09c.024.09-.018.119-.095.119");
}

.twewtbbsk {
  fill: var(--svg-color--595958, #595958);
  d: path("M12.709 34.544c.056.089.042.187.034.277c-.041.23-.008.465-.018.696c-.004.049-.004.095-.067.087v-.947c.029-.035.001-.092.051-.113");
}

.twnnxcc5o {
  fill: var(--svg-color--5e2d0d, #5e2d0d);
  d: path("M22.16 38.16c-.05.091-.101.178-.147.272c-.043-.147 0-.241.147-.272");
}

.twp764zgu {
  fill: var(--svg-color--2b1e1e, #2b1e1e);
  d: path("M17.01 30.938h.051c.019.109.063.227-.047.313z");
}

.twsxl1b8d {
  fill: var(--svg-color--4f4c3c, #4f4c3c);
  d: path("M21.261 18.03q-.04.039-.076.079c-.024.005-.043-.004-.059-.019c-.017-.025-.013-.045.002-.061l.002-.015q.034.006.07.007z");
}

.txs22dfwx {
  fill: var(--svg-color--444545, #444545);
  d: path("M23.05 33.18c-.162-.082-.141-.215-.097-.354c.092.097.04.242.097.354");
}

.txyqhu74v {
  fill: var(--svg-color--272727, #272727);
  d: path("M20.296 28.835h-.044c-.05-.002-.069-.033-.081-.078q.002-.045.016-.09c.004-.021.013-.035.021-.055a.08.08 0 0 1 .039-.043q.034.005.074.004c-.008.086-.015.176-.025.262");
}

.ty07ssu8k {
  fill: var(--svg-color--572e2c, #572e2c);
  d: path("M13.841 25.431c-.078.066-.158.117-.267.1c.068-.094.15-.148.267-.1");
}

.tyayqvrij {
  fill: var(--svg-color--584b10, #584b10);
  d: path("m18.15 22.454l.018.138c-.043.009-.09 0-.098-.052c-.012-.053.047-.059.08-.086");
}

.tyfr_5_ll {
  fill: var(--svg-color--74260d, #74260d);
  d: path("M21.07 26.679c-.149.02-.216-.04-.185-.196c0-.1.071-.134.146-.161c.058-.027.1-.084.179-.055c.014.094.189.008.168.152c-.011.013-.023.031-.039.031c-.088.018-.109.043-.083.131c-.069.008-.17-.024-.186.098");
}

.tzl_t88zx {
  fill: var(--svg-color--311111, #311111);
  d: path("M25.25 29.364c-.021-.138-.047-.275-.068-.41c-.021-.043-.002-.063.041-.063c.017.16.094.311.063.477l-.02.016z");
}

.u_nikacpk {
  fill: var(--svg-color--5c220f, #5c220f);
  d: path("M19.623 20.812c.16.143.166.283 0 .426a.5.5 0 0 0 0-.426");
}

.u0nxbc5fy {
  fill: var(--svg-color--6b5f12, #6b5f12);
  d: path("M18.271 22.07v-.038h.927c-.306.086-.618.023-.927.038");
}

.u0u64itas {
  fill: var(--svg-color--fafbfb, #fafbfb);
  d: path("M17.44 17.497c.098-.004.129.09.193.133c.069.06.062.125.028.201c-.246.201-.325.201-.502-.008c-.015-.098-.035-.193.054-.279c.065-.059.14-.088.227-.047");
}

.u1g3hxbnq {
  fill: var(--svg-color--1b2020, #1b2020);
  d: path("M19.817 29.936c.033-.035.115-.007.117-.09c.072-.06.113.004.158.047l.037.043z");
}

.u1q624-yi {
  fill: var(--svg-color--e1e2e1, #e1e2e1);
  d: path("M16.96 29.838c-.049 0-.105.086-.16 0q.008-.054.01-.103q0-.055.002-.106c.006-.099.035-.192.055-.286c.014-.057.031-.1.096-.104l.075.027c.204.127.216.178.083.417c-.087.017-.092.12-.161.155");
}

.u1wtk9d4v {
  fill: var(--svg-color--d3d4d4, #d3d4d4);
  d: path("M17.646 28.682c.117-.051.146.138.254.103q.006.019.005.043c-.062.164.056.321 0 .481c-.101.021-.142-.065-.204-.114c-.016-.171-.08-.34-.055-.513");
}

.u2efv1sti {
  fill: var(--svg-color--500707, #500707);
  d: path("M14.163 27.18c-.002-.229-.126-.459.047-.667c-.029.221.061.452-.047.667");
}

.u2i_ny7il {
  fill: var(--svg-color--343434, #343434);
  d: path("M19.515 38.24q.005-.034.006-.068l.171.169c-.123.081-.127-.06-.177-.101");
}

.u31savbyz {
  fill: var(--svg-color--2f1807, #2f1807);
  d: path("M14.95 40.17q.047-.001.092.004a.7.7 0 0 0 .055.42c.021.021.02.052-.006.07c-.082-.066-.103-.22-.254-.185c.1-.081.226-.149.113-.309");
}

.u36qui8_o {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M17.427 39.487c.006-.104.01-.209.014-.307c.016-.131-.004-.271.1-.382l-.001-.022c-.008-.087.035-.164.06-.248c.022-.07.043-.148.133-.164c.09-.026.113-.187.248-.127c.052.078.063.178.084.266c.004.098-.041.188-.031.285a.5.5 0 0 0-.023.16c0 .17.004.33 0 .496c0 .104-.045.18-.103.26c-.05.061-.093.121-.165.15c-.055.021-.105.042-.16.057c-.063.035-.102.027-.104-.056c-.019-.12-.035-.247-.052-.368");
}

.u3tnpbb6y {
  fill: var(--svg-color--3c3c3c, #3c3c3c);
  d: path("m17.38 27.833l-.039-.117q.074.011.146.016v.213c-.02.016-.039.023-.061.012c-.038-.032-.042-.075-.046-.124");
}

.u4nf-2bss {
  fill: var(--svg-color--4e2825, #4e2825);
  d: path("M23.421 18.597a.55.55 0 0 0-.264-.04c.1-.094.192-.101.264.04");
}

.u5dlvkb6z {
  fill: var(--svg-color--fd2118, #fd2118);
  d: path("M16.17 22.644q.084-.077.166-.158c.18-.004.368-.09.541.047l.016.004c.123.047.111.143.076.24q-.005.022-.027.027c-.102.029-.188.104-.287.146a.06.06 0 0 1-.047.008c-.104-.004-.207-.004-.311-.023c-.134-.061-.26-.118-.127-.291");
}

.u6-wo81bc {
  fill: var(--svg-color--191818, #191818);
  d: path("M17.476 39.855c.021.056.059.063.104.056c.045.109-.036.1-.093.105c-.02-.057-.039-.105-.061-.161a.06.06 0 0 0 .05 0");
}

.u6hh95buu {
  fill: var(--svg-color--434343, #434343);
  d: path("M17.632 37.653h-.043c.01-.102 0-.216.158-.205c-.04.07-.074.135-.115.205");
}

.u6ll9zbev {
  fill: var(--svg-color--131414, #131414);
  d: path("M23.782 32.411c-.122-.199-.034-.424-.043-.633h.047q-.003.313-.004.633");
}

.u7m8vb_iv {
  fill: var(--svg-color--40270b, #40270b);
  d: path("M13.787 38.28c.007-.088-.041-.192.065-.256c-.006.09-.012.168-.016.252q-.023.027-.049.004");
}

.u7up80brz {
  fill: var(--svg-color--717272, #717272);
  d: path("M14.168 32.419c-.028-.07.011-.157-.051-.215c.008-.08-.056-.189.087-.205c.01.141.018.283-.036.42");
}

.u7y3djfwq {
  fill: var(--svg-color--ecebe6, #ecebe6);
  d: path("M22.02 18.23c-.021.04-.041.083-.056.114a.1.1 0 0 1-.079.023c-.15-.017-.275-.067-.293-.246c-.005-.098.055-.156.117-.219l-.012-.023q.171-.11.324.027q.026.032.055.063c.02.097.053.198-.056.261");
}

.u82h67bnw {
  fill: var(--svg-color--746414, #746414);
  d: path("m15.704 22.12l-.039-.035c.107.02.23-.047.332.039c-.101.125-.195-.002-.293-.004");
}

.u8nouy24f {
  fill: var(--svg-color--3e360d, #3e360d);
  d: path("M14.15 39.12c.002.104-.083.197-.045.309c-.076-.115-.086-.225.045-.309");
}

.u9_0c8b9n {
  fill: var(--svg-color--261a1a, #261a1a);
  d: path("m12.146 29.16l.039.058c-.004.094.006.185-.047.268c-.041-.034-.037-.073-.013-.112z");
}

.u9-n88xkv {
  fill: var(--svg-color--41230a, #41230a);
  d: path("M21.952 39.907h.061c0 .017-.006.027-.006.043a.08.08 0 0 1-.004.061q-.013.019-.037.04l-.004.065c-.082-.066-.096-.137-.01-.209");
}

.u90fgmdzk {
  fill: var(--svg-color--292b2b, #292b2b);
  d: path("m20.246 29.37l.062-.063c.022-.04.059-.051.104-.047c.03 0 .063-.004.089-.004a1 1 0 0 1-.052.09c-.061.055-.136.001-.203.024");
}

.u9ffolb5f {
  fill: var(--svg-color--9b9e9e, #9b9e9e);
  d: path("m23.99 27.944l-.054-.06l.002-.047l-.004.003c.063.008.119.029.123.105c-.02.003-.042-.001-.067-.001");
}

.u9mwcrbto {
  fill: var(--svg-color--4c1d0c, #4c1d0c);
  d: path("M15.404 39.9c0-.008 0-.02-.004-.026c.149.05.157.137.054.242v-.113l-.041-.053a.2.2 0 0 0-.009-.05");
}

.ua9p4wy1n {
  fill: var(--svg-color--483634, #483634);
  d: path("M13.166 20.11c.122-.015.243-.023.36-.039q.05.053.007.117c-.125-.047-.242-.015-.354.053l-.013-.104z");
}

.uabv3ns5j {
  fill: var(--svg-color--fbfbfb, #fbfbfb);
  d: path("m23.1 30.47l.013.146c.075.113.024.254.069.375c.008.037-.002.075.027.107c0 .03 0 .063.002.09c-.096.039-.066.141-.048.178c.099.19.021.351-.067.506c-.082-.016-.107-.09-.16-.146q.02-.043-.029-.054c-.077-.052-.082-.144-.114-.214c-.03-.106-.091-.209-.002-.315c.032-.038.058-.062.011-.125c-.125-.168-.078-.301.092-.345c.123-.016.115-.139.162-.208q.023-.015.044.005");
}

.uaygg_brj {
  fill: var(--svg-color--512523, #512523);
  d: path("M25.22 28.891c-.018.022-.027.047-.043.062c-.059-.102-.057-.215-.076-.326l.039-.062c.07.098.048.219.08.326");
}

.ubbjgxyyu {
  fill: var(--svg-color--c2c3c8, #c2c3c8);
  d: path("m18.16 19.566l.002.021a.35.35 0 0 1-.007.282c-.056.021-.146.063-.132-.031c.014-.091-.052-.259.137-.272");
}

.uc32hj9ot {
  fill: var(--svg-color--6f6013, #6f6013);
  d: path("M21.703 22.419c-.087-.026-.188-.012-.269-.074c-.016-.021-.021-.027-.016-.041q.009-.014.018-.016c.111.023.227.02.324.086c-.003.037-.034.037-.057.045");
}

.ud_mfirtq {
  fill: var(--svg-color--d6bd24, #d6bd24);
  d: path("M14.01 20.333c-.045.022-.056.072-.063.115c-.085-.043-.102-.143-.146-.215c.031-.062.066-.117.145-.047q.031.075.064.147");
}

.ud0p98k4z {
  fill: var(--svg-color--242425, #242425);
  d: path("M22.579 30.31h.053l.113.256c-.081.075-.107-.056-.17-.052c-.053-.072-.054-.137.004-.204");
}

.ue5984tju {
  fill: var(--svg-color--e7e7e7, #e7e7e7);
  d: path("m20.09 29.893l-.158-.047l-.06-.118c-.085-.148-.071-.283.062-.4c.054-.056.09-.129.176-.142c.061.017.1.048.115.108c-.051.179.08.383-.088.544c-.017.019-.03.03-.047.055");
}

.uf55unb_m {
  fill: var(--svg-color--313434, #313434);
  d: path("M16.543 29.833c.044.01.087.013.111.056c-.039.06-.099.047-.153.047c-.043-.063-.109-.03-.164-.051c.057-.056.137-.039.206-.052");
}

.ufa998b8j {
  fill: var(--svg-color--4c4c4c, #4c4c4c);
  d: path("m15.1 30.782l.162.004q-.001.02-.008.049c-.08-.008-.051.08-.093.105c-.028.021-.052.021-.08-.004q-.048-.086.019-.154");
}

.ui07iha2h {
  fill: var(--svg-color--461a19, #461a19);
  d: path("M17.737 25.63q.028.023.059.039c-.072.096.084.146.047.232c-.076-.027-.115-.086-.148-.152c-.028-.036-.03-.08.004-.109c.008-.018.025-.018.038-.01");
}

.uiexx2beg {
  fill: var(--svg-color--1e0505, #1e0505);
  d: path("M16.818 34.407q-.03-.024-.058-.043c.09-.014.188-.066.258.039q-.098-.001-.2.004");
}

.uijkx9bnm {
  fill: var(--svg-color--3b3b3b, #3b3b3b);
  d: path("M13.946 33.19h.105c-.052.098.073.256-.104.312c.001-.105-.001-.206-.001-.312");
}

.uipn_hbcj {
  fill: var(--svg-color--321f1f, #321f1f);
  d: path("M16.685 30.726c-.051.075-.016.146.009.215c-.144-.067-.142-.136-.009-.215");
}

.uj_zmz-lp {
  fill: var(--svg-color--261818, #261818);
  d: path("M17.438 30.69c-.021.016-.043.027-.065.042c-.085-.012-.179.015-.253-.056a.7.7 0 0 1 .318.014");
}

.ukaja_b4r {
  fill: var(--svg-color--212525, #212525);
  d: path("M17.487 31.857c.004-.259-.077-.521.051-.762c-.025.25.061.51-.051.762");
}

.ukhet845k {
  fill: var(--svg-color--282828, #282828);
  d: path("M24.985 32.827c-.004.121.011.252-.08.386c-.063-.153.023-.269.025-.386c.02-.014.034-.014.055 0");
}

.ukkol-byd {
  fill: var(--svg-color--737272, #737272);
  d: path("m13.02 35.987l-.051-.115a.28.28 0 0 1 .035-.219c.051.022.023.074.053.103a.3.3 0 0 1-.037.231");
}

.ukudhhbtu {
  fill: var(--svg-color--57210e, #57210e);
  d: path("M19.304 16.549c.049-.06.069-.121.03-.196c.16.094.091.169-.026.236l-.02-.02z");
}

.ulf-w7bxz {
  fill: var(--svg-color--f2f2f3, #f2f2f3);
  d: path("M16.14 18.18q-.023.007-.047.008q-.031.024-.062.012q-.023-.03.009-.062q.048-.006.098-.017q.024.019.016.041c-.006.009-.008.018-.014.018");
}

.uljj2obmv {
  fill: var(--svg-color--756514, #756514);
  d: path("M15.209 38.427c-.054-.008-.062-.048-.062-.078c.004-.021.025-.049.039-.049c.043 0 .054.037.052.07c-.001.017-.022.037-.029.057");
}

.ulrvp1jlp {
  fill: var(--svg-color--493a3c, #493a3c);
  d: path("M22.02 17.909a.45.45 0 0 0-.321-.028l.013-.07c.107 0 .253-.09.308.098");
}

.um10hkpgo {
  fill: var(--svg-color--414242, #414242);
  d: path("M14.479 31.727q.023.001.047-.004c-.043.093-.024.265-.209.157l-.008.004c.038-.074.071-.157.17-.157");
}

.umrx_vbwn {
  fill: var(--svg-color--4f4f4f, #4f4f4f);
  d: path("M16.907 29.36c-.027.092-.035.192-.096.27c-.105-.094.047-.184 0-.278v-.047c.054-.021.073.018.096.055");
}

.uncm7c0bw {
  fill: var(--svg-color--2b1919, #2b1919);
  d: path("M20.364 32.14c-.043.003-.086.003-.129.009c-.083-.006-.174.021-.24-.052a.52.52 0 0 1 .369.043");
}

.uoil_cntr {
  fill: var(--svg-color--c3c3c4, #c3c3c4);
  d: path("m24.343 27.577l.055-.035c.006.024.017.056.021.08c0 .016-.004.026-.008.039c-.022.108.043.234-.046.34q-.012-.208-.022-.424");
}

.uqzvbdc0b {
  fill: var(--svg-color--2d2d2d, #2d2d2d);
  d: path("M14.06 32.776h.056c-.026.139.03.291-.065.418c-.033.03-.07.026-.105 0a.8.8 0 0 0 .114-.418");
}

.ur1r1fbsi {
  fill: var(--svg-color--212222, #212222);
  d: path("M23.507 30.1c-.027.035-.055.065-.082.103c.06-.142-.15-.279-.01-.42c-.021.12.057.208.092.317");
}

.ur6lxdbfo {
  fill: var(--svg-color--222121, #222121);
  d: path("M17.651 40.971c0 .205-.004.41-.004.614c-.016.021-.028.021-.045.005c-.049-.078.037-.218-.115-.239c.109-.131.094-.29.109-.439c.051-.013.079.003.055.059");
}

.urh1jpb3e {
  fill: var(--svg-color--101212, #101212);
  d: path("M14.263 30.946c-.01.02-.01.041.004.053a4 4 0 0 1-.018.203l-.021-.008l-.019.008c-.019-.063-.04-.131-.055-.192c-.033-.146.056-.072.109-.064");
}

.urro_2bys {
  fill: var(--svg-color--432e2e, #432e2e);
  d: path("m15.361 33.559l.129.259c-.162-.012-.14-.152-.172-.255c.01-.033.027-.033.043-.004");
}

.us83zjb9u {
  fill: var(--svg-color--d0b423, #d0b423);
  d: path("M24.343 38.03c.017 0 .037-.004.057-.004c.105-.012.15.086.219.143a.5.5 0 0 1 .107.02c.008.021.008.048-.008.063c-.051.043-.115.031-.168.055c-.104-.016-.137-.124-.219-.17c-.011-.04-.011-.076.012-.107");
}

.utmpaltcp {
  fill: var(--svg-color--004994, #004994);
  d: path("M14.01 21.48c.153-.008.273.024.263.222c-.048.021-.063.121-.146.055q-.066-.07-.132-.143c-.022-.047-.032-.094.015-.134");
}

.uu1kcktnc {
  fill: var(--svg-color--6e6e6e, #6e6e6e);
  d: path("M18.06 41.475c-.004-.05.018-.112-.051-.146c.025-.174-.09-.373.094-.519v.675c-.016.004-.028-.005-.043-.01");
}

.uuj3ybbjy {
  fill: var(--svg-color--eacf27, #eacf27);
  d: path("M22.402 36.706H22.4c-.025.02-.054.02-.077 0c-.02-.022-.023-.057-.012-.092c.146-.109.291-.141.429.018h-.004c-.069.158-.087.17-.334.074");
}

.uuzllx1fh {
  fill: var(--svg-color--2c2e2e, #2c2e2e);
  d: path("M19.877 29.32c.16.031.097-.099.117-.16c.031.014.062.035.095.051c-.033.055-.063.104-.095.16c-.047.002-.089-.006-.117-.051");
}

.uvdfn1bok {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("M22.01 20.55c-.021 0-.035.004-.055.004c-.206.066-.117-.148-.199-.208q-.05.027-.104.051c-.163-.007-.112-.133-.124-.223a.2.2 0 0 1 .028-.079c.125-.1.26-.072.396-.033q.033.016.06.037a.8.8 0 0 1 .117.172c.041.071-.017.125-.025.189a1 1 0 0 0-.094.09");
}

.uwz4c0b8w {
  fill: var(--svg-color--69696a, #69696a);
  d: path("m12.496 30.942l-.004-.115l.01-.049c.052-.049.031-.113.052-.173c.033.111.09.224-.017.33h-.022z");
}

.uxbxz5baa {
  fill: var(--svg-color--50504d, #50504d);
  d: path("M18.524 18.892a.46.46 0 0 0 .367.003c-.004.039-.004.086-.01.129c-.125-.03-.25-.059-.357.052z");
}

.uxmatlb6d {
  fill: var(--svg-color--776715, #776715);
  d: path("M15.456 22.429a.35.35 0 0 1 .313-.044c-.084.083-.207.075-.313.098q-.026-.013-.018-.034c.008-.021.013-.02.018-.02");
}

.v_-8uy-ai {
  fill: var(--svg-color--ebebec, #ebebec);
  d: path("M21.488 19.969c.034.021.071.036.104.055q.028.018.02.031c-.004.017-.012.021-.016.021v.047c-.018.007-.035.007-.051.016c-.031-.009-.052 0-.062.035c-.043.074-.075.184-.187.16c-.064-.012-.056-.09-.031-.148c.074-.078.148-.144.223-.217");
}

.v_1iftbru {
  fill: var(--svg-color--40210d, #40210d);
  d: path("M14.946 39.43c.063.101.051.206.047.321c-.08-.073-.082-.17-.111-.256c.008-.039.028-.055.064-.065");
}

.v_fgt4twr {
  fill: var(--svg-color--707070, #707070);
  d: path("M12.644 34.35a.4.4 0 0 1-.041-.271c.017-.017.021-.049.052-.054c.056.065.056.142.039.224c-.031.026-.004.081-.05.101");
}

.v_o1x6bol {
  fill: var(--svg-color--c6c6c6, #c6c6c6);
  d: path("M17.589 27.629a.63.63 0 0 1 .051.421c-.027.033-.006.098-.063.122a.1.1 0 0 1-.067-.032a.6.6 0 0 1-.08-.221a.23.23 0 0 1 .059-.187q-.012-.026 0-.044c-.033-.038-.033-.085.008-.109c.036-.021.073.006.092.05");
}

.v_oeei1ck {
  fill: var(--svg-color--605612, #605612);
  d: path("m14.415 21.23l.008-.05c.125-.052.245-.063.311.09c-.104-.046-.212-.042-.319-.04");
}

.v-pi2dr9b {
  fill: var(--svg-color--57310d, #57310d);
  d: path("M22.01 26.1c.152-.195.241-.186.42.055c.02.018.027.028.02.041c-.004.012-.014.017-.021.017c-.122-.101-.243-.214-.419-.113");
}

.v0fdxxqmc {
  fill: var(--svg-color--354040, #354040);
  d: path("M25.386 32.765q-.001.213.004.424a.1.1 0 0 1-.043.014c.004-.145.004-.287.006-.434c.007 0 .02-.004.033-.004");
}

.v0i7gdjza {
  fill: var(--svg-color--2d1b1b, #2d1b1b);
  d: path("M20.712 30.991c.004-.093.084-.172.02-.266c.189.102.097.18-.02.266");
}

.v1qbqfb4k {
  fill: var(--svg-color--4f4f4b, #4f4f4b);
  d: path("M19.921 40.07h.059c.063.064.074.157.1.243c-.143-.024-.126-.149-.159-.243");
}

.v1wm6ccmb {
  fill: var(--svg-color--a8a9aa, #a8a9aa);
  d: path("M23.832 20.02q-.047.06-.099.119c-.109-.126-.096-.26.005-.387q.02.007.043.008c-.013.056-.002.094.054.109c0 .051-.003.105-.003.151");
}

.v20imvb0p {
  fill: var(--svg-color--4a3030, #4a3030);
  d: path("M17.12 28.1c-.002.016-.002.035-.002.049c-.141-.08-.042-.201-.042-.304c.03-.035.065-.035.104-.011a.55.55 0 0 1-.06.266");
}

.v20s_0zpp {
  fill: var(--svg-color--72641b, #72641b);
  d: path("M22.274 36.28c.068.021.111-.027.154-.068l.055.063c-.034.076.095.106.043.189c-.129.076-.278.011-.411.05a.2.2 0 0 1-.054-.021c-.033-.047-.063-.094-.1-.141c.012-.048.035-.083.086-.094c.075.007.155-.017.227.022");
}

.v2i417b5f {
  fill: var(--svg-color--181818, #181818);
  d: path("M13.06 35.755c-.018-.03-.033-.065-.053-.102q.008-.132.018-.25q.027.078.049.159z");
}

.v428yvbme {
  fill: var(--svg-color--ddc425, #ddc425);
  d: path("M15.97 26.38h.047c.095.027.187-.036.279-.02a.12.12 0 0 1 .061.09q-.002.034-.036.06c-.134.012-.257.103-.396.079l-.025-.004l-.023.004c-.077.059-.159.047-.243.021c-.076-.115.031-.092.08-.111c.088-.036.186-.047.256-.119");
}

.v4bktjbng {
  fill: var(--svg-color--181818, #181818);
  d: path("M17.55 28.16c-.07-.004-.142-.004-.216-.01c.039-.063.074-.128.11-.203h.043c.02.074.04.141.063.213");
}

.v523egb-y {
  fill: var(--svg-color--4b2b2b, #4b2b2b);
  d: path("M20.548 28.946c-.105-.067-.132-.166-.141-.279c.098.066.141.16.141.279");
}

.v5k4n3bbq {
  fill: var(--svg-color--f0f1f1, #f0f1f1);
  d: path("m20.712 29.394l-.004-.008c.084.1.186.18.27.277c.07.057.14.11.211.168c-.084.166-.207.048-.314.052c-.188-.038-.277-.164-.307-.349a.2.2 0 0 1-.008-.084c.004-.043.019-.082.056-.104c.046-.011.084-.006.096.048");
}

.v6n28ubvg {
  fill: var(--svg-color--373c3d, #373c3d);
  d: path("M21.71 34.393c-.089.019-.181-.042-.268.019c.057-.125.162-.047.246-.063a.1.1 0 0 1 .022.044");
}

.v7_oy_7bm {
  fill: var(--svg-color--535353, #535353);
  d: path("M24.04 31.05c-.063-.105-.045-.215-.041-.326c.056-.027.069.023.095.057q-.004.106-.005.213c-.014.018-.019.048-.049.056");
}

.v7-qxjtse {
  fill: var(--svg-color--50220c, #50220c);
  d: path("M22.12 40.571c.066.071.135.09.212.021c.003.073-.017.144-.099.144c-.085-.007-.121-.079-.113-.165");
}

.v8b-3hbgn {
  fill: var(--svg-color--665d2b, #665d2b);
  d: path("M15.4 18.651c.075-.104.048-.234.069-.357h.19c.033.027.042.06.046.1c-.008.085-.052.161-.087.23c-.028.051-.053.109-.099.152a.2.2 0 0 1-.068.016q-.058-.013-.075-.073c.001-.023.008-.052.024-.068");
}

.v8hjm14qq {
  fill: var(--svg-color--53300b, #53300b);
  d: path("M23.259 39.04c-.082-.08-.164-.153-.248-.231c.181-.029.235.077.248.231");
}

.v96flotlg {
  fill: var(--svg-color--070704, #070704);
  d: path("M19.06 21.269c-.02.023-.035.047-.056.066c-.062-.121-.09-.229.048-.313c.055-.031.059 0 .051.042c-.06.058-.051.134-.043.205");
}

.v9fzo1bue {
  fill: var(--svg-color--371515, #371515);
  d: path("M18.851 28.372c.004.052-.037.115.024.156c.063.106.026.149-.087.153h-.047c-.004-.116-.01-.233.11-.309");
}

.v9hu4rbxe {
  fill: var(--svg-color--303131, #303131);
  d: path("M15.09 32.05c-.031-.054-.062-.113-.09-.163c-.012-.021-.016-.028-.016-.048c-.03-.067.009-.101.061-.121a.86.86 0 0 1 .115.378z");
}

.v9rru0shz {
  fill: var(--svg-color--545b5b, #545b5b);
  d: path("M17.849 29.885a.1.1 0 0 1 .008-.052c.027-.035.064-.06.107-.06c.059.036.117.071.103.154c-.077.003-.16.041-.218-.042");
}

.v9tjlspyh {
  fill: var(--svg-color--583d3d, #583d3d);
  d: path("M14.468 34.03a.47.47 0 0 1 .102-.283c.021.117.021.224-.102.283");
}

.v9xzyucpi {
  fill: var(--svg-color--515149, #515149);
  d: path("M21.81 19.843c-.002-.047-.004-.104-.055-.13l.094-.224c.004.051.012.099.058.133l.003.065c-.035.054-.065.109-.1.156");
}

.vatjsig9x {
  fill: var(--svg-color--272828, #272828);
  d: path("M12.587 33.885c.018-.017.036-.042.055-.06q.005.098.013.2l-.052.054z");
}

.vbcoabmgy {
  fill: var(--svg-color--2c1616, #2c1616);
  d: path("M14.367 25.431c-.138-.113-.298-.04-.446-.051c.207-.094.356-.073.446.051");
}

.vbjjltbii {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M18.16 18.03c.021-.018.041-.033.061-.057c.039.471.031.943 0 1.418l-.037.105l-.062-.152c.091-.431.021-.875.038-1.314");
}

.vbp6hqbbe {
  fill: var(--svg-color--3f350d, #3f350d);
  d: path("M23.05 37.587q-.001-.02.004-.045q.015-.011.035-.004q.033.008.063.009c.031.098.125.118.268.134c-.221.129-.273-.048-.37-.094");
}

.vburc2b3x {
  fill: var(--svg-color--a28c1d, #a28c1d);
  d: path("M14.05 19.239h-.02l-.021-.01c-.037-.012-.07-.023-.053-.07l.014-.158q.028-.017.057-.03c.068-.065.145-.06.226-.024a.1.1 0 0 1 .043.067c-.015.149-.152.155-.246.225");
}

.vc-10ob-k {
  fill: var(--svg-color--3a3c3c, #3a3c3c);
  d: path("M15.397 35.2c-.041.104-.074.205-.109.309c-.004.038-.029.061-.063.07c-.024.004-.043-.008-.06-.022c.109-.101.041-.314.232-.357");
}

.vcngpbblv {
  fill: var(--svg-color--2c2c2c, #2c2c2c);
  d: path("M22.16 30.55c.02.063.041.119.061.18c-.037 0-.043.029-.049.057c-.098-.077-.027-.161-.012-.237");
}

.vcog4ribb {
  fill: var(--svg-color--5d2f2f, #5d2f2f);
  d: path("M17.603 41.59a.06.06 0 0 1 .045-.005c.047.091.123.088.201.049c-.113.18-.202.167-.246-.044");
}

.vdk90thti {
  fill: var(--svg-color--484544, #484544);
  d: path("M15.527 29.465c-.075-.031-.159-.031-.218-.095c.088 0 .196-.059.218.095");
}

.ve3prbc4z {
  fill: var(--svg-color--6e6013, #6e6013);
  d: path("M20.356 21.909c-.194.125-.389.037-.582 0q-.045-.052 0-.108c.025-.06.048-.017.066.004c.135.021.274-.047.4.043q.06.033.116.061");
}

.vflei7bar {
  fill: var(--svg-color--c1a41e, #c1a41e);
  d: path("M23.576 19.819c.071.104.083.207-.007.311z");
}

.vfu9zac_q {
  fill: var(--svg-color--221f08, #221f08);
  d: path("M15.929 18.298c.015-.008.026-.012.043-.008c.004.041-.008.056-.047.051z");
}

.vfyuzqbvg {
  fill: var(--svg-color--fde32b, #fde32b);
  d: path("M22.539 36.434q.024.031.052.062c-.121.061-.25.011-.371.031c-.021.01-.039.014-.058.021q-.025.001-.043-.004c-.004-.008-.004-.02-.004-.026c.119-.15.279-.068.424-.084");
}

.vglqdfbgi {
  fill: var(--svg-color--2c2609, #2c2609);
  d: path("M17.534 21.857a.4.4 0 0 0 .055-.055q.078.005.158.017c.023.034.125-.013.1.084c-.104-.009-.224.065-.313-.046");
}

.vgvmomkui {
  fill: var(--svg-color--343636, #343636);
  d: path("M13.642 35.07c.063-.072-.098-.232.098-.25c-.012.09.042.209-.098.25");
}

.vgwsmlb8d {
  fill: var(--svg-color--653212, #653212);
  d: path("M21.07 22.54a1.2 1.2 0 0 0-.5-.045c-.021.017-.035.017-.05-.004c.192-.076.385-.149.55.049");
}

.vicn4ffzs {
  fill: var(--svg-color--6c4241, #6c4241);
  d: path("M17.617 30.835a3 3 0 0 1-.244-.103c.007-.038.038-.038.065-.042c.087.016.166.036.179.145");
}

.vjaukgbth {
  fill: var(--svg-color--403f40, #403f40);
  d: path("M14.583 33.678c.09-.111-.004-.322.197-.378c-.079.173.016.354-.008.529c-.078-.027-.06-.184-.189-.151");
}

.vjtvunovd {
  fill: var(--svg-color--790807, #790807);
  d: path("M25.386 32.765c0-.016.004-.036.016-.052a.5.5 0 0 1-.012.476a.95.95 0 0 1-.004-.424");
}

.vkkancbyj {
  fill: var(--svg-color--242424, #242424);
  d: path("M17.323 27.421h-.041a.37.37 0 0 1-.059-.227c.087.051.105.135.1.227");
}

.vkky7-bfh {
  fill: var(--svg-color--0e0f0f, #0e0f0f);
  d: path("m19.731 29.79l.059.146q-.119.001-.234-.004c-.021-.036-.012-.067.01-.097c.046-.041.103-.049.165-.045");
}

.vkt0y3nha {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.562 28.26c-.004.079.011.168-.092.204q.024-.106.056-.204z");
}

.vlq1s5baq {
  fill: var(--svg-color--5b4e11, #5b4e11);
  d: path("M15.623 23.384c-.088.031-.174.07-.267.102c.041-.167.157-.131.267-.102");
}

.vm0c42bon {
  fill: var(--svg-color--3d1513, #3d1513);
  d: path("M20.763 35.605c-.02.005-.041.005-.062.009l-.19.065c.049-.141.129-.184.252-.074");
}

.vnc3l98xr {
  fill: var(--svg-color--fee22c, #fee22c);
  d: path("M22.17 36.606q-.025-.029-.051-.056l.004-.009q.03-.015.06 0c.009.028.008.048-.013.065");
}

.vo9smtemj {
  fill: var(--svg-color--939393, #939393);
  d: path("m19.817 29.936l-.017-.007l-.011.007c-.065-.03-.083-.09-.089-.157c.007-.039.033-.066.07-.082a.14.14 0 0 1 .111.008c.047.033.076.07.076.131c-.008.085-.093.069-.14.1");
}

.vpb9n_1cq {
  fill: var(--svg-color--cac9c4, #cac9c4);
  d: path("M21.736 19.441c.022-.034-.05-.067 0-.098c.075-.056.021-.142.05-.205c.02-.017.042-.028.064-.019c.033.035.041.086.08.121c.031.09-.008.168-.03.254a3 3 0 0 0-.106.226c-.049.083-.07.172-.105.263a.1.1 0 0 1-.086.063c-.06.008-.098-.022-.112-.079c-.007-.11.056-.195.106-.287c.076-.058.071-.167.139-.239");
}

.vpv46vbaf {
  fill: var(--svg-color--131516, #131516);
  d: path("m21.804 25.374l.002.052c-.061.007-.123.043-.185 0c.019-.035.035-.065.052-.103c.056-.016.094.02.131.051");
}

.vq4fl3bph {
  fill: var(--svg-color--2d0605, #2d0605);
  d: path("M17.02 35.59v.106c-.104.069-.168.027-.209-.084c.066-.022.151.09.209-.022");
}

.vr32zf7cj {
  fill: var(--svg-color--444545, #444545);
  d: path("M15.556 35.614c.055-.004.106-.004.16-.009c-.052.063-.103.122-.154.185c-.081-.059.037-.121-.006-.176");
}

.vr8hcfklr {
  fill: var(--svg-color--5e5e5e, #5e5e5e);
  d: path("m20.02 35.669l.065-.053q.007-.059.066-.062c.026.015.057.034.083.052c-.019.193-.129.096-.214.063");
}

.vreyosunj {
  fill: var(--svg-color--724511, #724511);
  d: path("M21.538 19.13a.4.4 0 0 1-.096.291a.4.4 0 0 1 .049-.287q.023-.034.047-.004");
}

.vrger1bnu {
  fill: var(--svg-color--281709, #281709);
  d: path("M18.06 21.45q.133-.032.265-.057c.002 0-.006-.004-.006-.004c-.048.08-.087.161-.196.161q-.034.025-.07 0c-.023-.033-.025-.07.007-.1");
}

.vrw6e72ou {
  fill: var(--svg-color--e3c226, #e3c226);
  d: path("M14.937 40.05a.48.48 0 0 1 .414.008a1.3 1.3 0 0 1-.414-.008");
}

.vryzoi7vb {
  fill: var(--svg-color--524f40, #524f40);
  d: path("M21.812 19.948c.029.075.162.066.147.181c-.11-.091-.247-.011-.362-.056c0-.02-.002-.031-.004-.051a.4.4 0 0 1 .068-.047c.046-.056.102-.019.151-.027");
}

.vsgitfual {
  fill: var(--svg-color--563a3b, #563a3b);
  d: path("m23.726 35.721l-.06-.008c-.032-.079-.122-.144-.038-.24c.062.069.079.161.098.248");
}

.vt1uewb-h {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M13.327 34.815c.1.074.023.178.04.266q-.024.001-.04.007z");
}

.vv-yjxb7s {
  fill: var(--svg-color--656666, #656666);
  d: path("M22.854 32.407c-.08-.082-.088-.164-.01-.246c.09.07.022.168.037.25z");
}

.vvx_e443w {
  fill: var(--svg-color--665912, #665912);
  d: path("M21.3 20.653a4 4 0 0 0 .022-.257a.14.14 0 0 1 .14-.075c.061.023.073.075.059.135c-.133-.004-.139.125-.199.197z");
}

.vwwrqbblq {
  fill: var(--svg-color--615411, #615411);
  d: path("M18.831 22.278c-.1-.098-.195-.02-.298 0c.021-.074.071-.102.138-.113c.025 0 .051.004.076.004c.104-.025.139.008.084.109");
}

.vxn678bdf {
  fill: var(--svg-color--2d0605, #2d0605);
  d: path("M12.854 36.815c.012.065.027.131.105.149c-.035.091-.191-.022-.201.116l-.012-.064c.026-.074-.044-.201.108-.201");
}

.vxxshy3le {
  fill: var(--svg-color--414545, #414545);
  d: path("m22.22 35.552l-.092-.044c-.003-.104-.119-.173-.066-.29c.123.076.102.226.158.334");
}

.vyxmhptmu {
  fill: var(--svg-color--474747, #474747);
  d: path("M19.361 29.29c-.085.096-.089.232-.149.338h-.055l.039-.282l-.012-.079c.067-.055.124-.01.177.023");
}

.vz7fa2bsh {
  fill: var(--svg-color--242525, #242525);
  d: path("M22.745 30.564q.077.055.152.113l.002.03c-.057.041-.119.048-.1.149c.019.103.133.224-.023.312a.12.12 0 0 1-.104-.016c-.09-.146-.033-.326-.13-.469c-.018-.02-.026-.042-.038-.063c-.01-.047-.003-.094.051-.127c.079-.023.126.041.19.071");
}

.w_uuhvb4j {
  fill: var(--svg-color--2e3030, #2e3030);
  d: path("M11.966 31.62q.024-.005.047-.004v.318c-.014 0-.028-.004-.043-.004z");
}

.w-uxh5bhm {
  fill: var(--svg-color--612514, #612514);
  d: path("M22.312 21.646c-.06.105-.034.232-.041.35c-.08-.13-.12-.255.041-.35");
}

.w00-bxqgj {
  fill: var(--svg-color--3b240c, #3b240c);
  d: path("M23.1 37.967c.043 0 .08.004.119.008c-.166.144-.383.092-.492-.108c.025-.035.059-.035.097-.027q.032.014.062.033c.056.063.161.023.214.094");
}

.w1qo-3b5k {
  fill: var(--svg-color--404242, #404242);
  d: path("M19.322 28.745c-.04.104-.081.211-.118.313c-.126-.125.023-.25.012-.38c.055-.007.082.02.106.067");
}

.w1sn9bfdj {
  fill: var(--svg-color--50450f, #50450f);
  d: path("M22.524 22.444a.8.8 0 0 1-.354-.125q0-.014-.003-.029c.169.023.341.066.517.033c.018.01.021.026.018.033c-.004.014-.014.018-.018.018c-.05.022-.124.002-.16.07");
}

.w2a27fbbn {
  fill: var(--svg-color--462424, #462424);
  d: path("m14.986 36.29l-.054.004c-.078-.174.023-.305.1-.443q.035.029.047.063c.021.11-.016.213-.043.313q-.023.035-.05.063");
}

.w2w89kbmz {
  fill: var(--svg-color--5d200b, #5d200b);
  d: path("M21.18 26.954c.117-.032.25-.014.361-.086c-.076.211-.22.148-.361.086");
}

.w3kn4sc3d {
  fill: var(--svg-color--343434, #343434);
  d: path("M13.325 36.29h.044c.005.06.009.115-.039.16h-.022l-.024-.004c-.013-.056.01-.109.041-.156");
}

.w5i2i601p {
  fill: var(--svg-color--d8bf24, #d8bf24);
  d: path("M15.79 20.08q-.063-.005-.125-.004c-.041-.08-.104-.172.051-.195c.028.066.151.104.069.203z");
}

.w5zul_74f {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M22.323 31.353c-.016.107.036.188.105.253a.47.47 0 0 0-.09.282a.5.5 0 0 1-.068.184c-.103-.019-.191-.049-.203-.172a.37.37 0 0 1-.131-.234c-.026-.094-.053-.182-.066-.278c-.01-.067-.023-.138.057-.177c.096-.094-.17-.153-.024-.252c.071.015.144.049.211-.014c.019-.057.037-.105.056-.158c-.037-.056.002-.066.041-.074c.02.016.04.035.049.062c.026.093-.002.198.039.292c.06.088-.03.194.024.286");
}

.w6_cgz78h {
  fill: var(--svg-color--490303, #490303);
  d: path("M25.03 35.731q.007-.19.011-.395h.03c.006.137.024.274-.041.395");
}

.w6gwa8b7t {
  fill: var(--svg-color--d5d6d9, #d5d6d9);
  d: path("M15.925 18.274a.1.1 0 0 1 0-.039l.002-.048c.028 0 .053-.008.082-.008l.082.008c-.041.037-.078.067-.117.103l-.019.023l-.022-.016c0-.011-.004-.015-.008-.023");
}

.w6hr-dh5c {
  fill: var(--svg-color--555, #555);
  d: path("m14.408 30.54l.017-.09c.069.056.077.143.09.217c-.078-.008-.118-.043-.107-.127");
}

.w6w3e2bkb {
  fill: var(--svg-color--d6d9da, #d6d9da);
  d: path("M21.261 18.02c.055.079.152.118.17.221c-.155.09-.254.055-.273-.138c.02-.047.063-.06.104-.075v-.008z");
}

.w70pvgbbj {
  fill: var(--svg-color--333434, #333434);
  d: path("M17.912 28.52h.052c.103 0 .121.072.113.158c-.057.112-.115-.103-.178 0h-.051q.035-.077.064-.158");
}

.w78wgzble {
  fill: var(--svg-color--6d5e13, #6d5e13);
  d: path("M15.255 38.807c-.072-.071-.062-.14-.017-.257c.088.105.042.186.052.263q-.014.002-.035-.006");
}

.w7ccchbad {
  fill: var(--svg-color--655c2a, #655c2a);
  d: path("m15.613 18.946l-.011-.146l.021-.125l.075-.013q-.04.144-.085.284");
}

.w7z7mgbsf {
  fill: var(--svg-color--181717, #181717);
  d: path("M13.429 34.719c.017.012.03.028.047.046c-.021.105-.034.214-.055.314h-.055c-.04-.082.02-.183-.04-.265c.013-.05.048-.089.103-.095");
}

.w84_vdjvy {
  fill: var(--svg-color--3f2525, #3f2525);
  d: path("M20.397 34.713h-.041c-.008-.068.011-.136.082-.164c.068-.023.113.013.121.088c-.081-.033-.128.006-.162.076");
}

.w8a9xf28t {
  fill: var(--svg-color--666565, #666565);
  d: path("M12.587 33.885c-.045-.052-.047-.109-.035-.173c.016-.021.02-.053.055-.061c.048.053.048.113.037.174c-.021.026-.025.056-.057.06");
}

.w8j3vab-q {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("m22.429 19.19l.053.147c-.035.061.006.131-.026.186c-.004.076-.024.137-.094.172c-.173.029-.312-.016-.396-.184a.36.36 0 0 1 .01-.243c.099-.119.226-.11.354-.08q.047.003.099.002");
}

.w9yden4py {
  fill: var(--svg-color--114c80, #114c80);
  d: path("M23.21 21.493q.069-.008.135-.021c.043-.004.09-.017.129.028c-.066.082-.125.172-.192.25c-.063.043-.101-.012-.14-.051l.006.004c-.051-.089.019-.145.062-.21");
}

.wan7q5ihd {
  fill: var(--svg-color--583232, #583232);
  d: path("M24.562 26.337a7 7 0 0 0-.108-.307c.127.072.211.158.108.307");
}

.waqkbyo9f {
  fill: var(--svg-color--282929, #282929);
  d: path("M20.339 28.05c.01.056.038.125-.043.161c-.039.031-.051.078-.089.104a.08.08 0 0 1-.067.016a.15.15 0 0 1-.084-.106v-.075c.021-.07.021-.152.049-.228q.016-.037.048-.043c.022-.005.039 0 .062.015c.031.037.047.088.088.118a.1.1 0 0 1 .036.038");
}

.wbj9veb9o {
  fill: var(--svg-color--efeff0, #efeff0);
  d: path("M24.21 19.708c.046.039.097.08.101.152q.057.13-.053.221v-.004c-.037.031-.06.086-.125.063c-.107-.032-.242.02-.32-.109a.23.23 0 0 1-.017-.16a.3.3 0 0 1 .091-.146c.104-.06.211-.09.323-.017");
}

.wbqyupbeo {
  fill: var(--svg-color--252626, #252626);
  d: path("M24.729 35.04c0 .1-.006.197-.006.297c.006.072.078.169-.051.211v-.773c.14.067.052.177.057.265");
}

.wcnz-yu3g {
  fill: var(--svg-color--504d4d, #504d4d);
  d: path("M18.312 33.72c-.021 0-.041.004-.06.004h-2.211q-.023-.051.022-.086c.087-.057.181-.057.277-.057c.553-.004 1.105-.012 1.657 0c.12 0 .268-.034.315.139");
}

.wdle_vbot {
  fill: var(--svg-color--514a0f, #514a0f);
  d: path("M17.484 21.11v.094c-.106-.027-.214-.047-.312.035c-.041-.031-.056-.066-.043-.117a.11.11 0 0 1 .073-.08c.1.004.195 0 .282.068");
}

.wf-fs4rxe {
  fill: var(--svg-color--3e3e3e, #3e3e3e);
  d: path("M20.14 27.24q.005.065.006.133c.053.09.095.188.072.299c-.035.074-.01.165-.078.223l.004-.002c-.078.035-.137.002-.18-.061c-.012-.043-.009-.082.034-.113c.125-.139.017-.342.142-.479");
}

.wfe6b138a {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M20.698 35.86c-.023.021-.049.038-.076.063c-.097.016-.191-.025-.287-.006c-.055-.049-.125-.049-.191-.049c-.107-.033-.226-.041-.326-.102c-.018-.035-.029-.063-.043-.091a5.3 5.3 0 0 1-.004-1.068c.004-.017.008-.026.011-.048c.099-.098.241-.09.362-.124c.084-.024.182.022.254-.052c.068-.021.127-.014.193-.01a.25.25 0 0 1 .17.14c-.024.112-.011.298-.205.121c-.114-.069-.129-.06-.186.104a.46.46 0 0 0 .075.303l.007.019a.18.18 0 0 1 .014.188c-.021.019-.039.031-.057.053a.4.4 0 0 0 .021.404l.076-.026c.049-.074.113-.112.207-.086c.081.095.138.185-.015.267m.631-.78l.01-.148c.026-.05.057-.092.11-.105c.104-.019.202.029.301.049c.156.07.271.179.341.34c.008.104.115.207.012.32a.34.34 0 0 1-.189.039a.5.5 0 0 1-.158-.023c-.143-.065-.302-.09-.423-.199h.005c-.075-.096-.051-.178-.009-.273");
}

.wgk10_b0s {
  fill: var(--svg-color--fce42b, #fce42b);
  d: path("M23.267 37.23a.28.28 0 0 1-.207.109c-.051-.055-.178-.064-.09-.187c.086-.046.168-.03.246.024a.2.2 0 0 0 .051.054");
}

.whvrnn94q {
  fill: var(--svg-color--533d3b, #533d3b);
  d: path("M24 20.758c.014-.009.021-.009.032-.009c-.004.091.051.192-.039.271q-.035.029-.071-.007c-.017-.098-.015-.192.078-.255");
}

.whvsvf7rz {
  fill: var(--svg-color--3e3f3f, #3e3f3f);
  d: path("M19.2 29.1q0 .073.005.149l-.012.091c-.039-.06-.086-.086-.149-.032c-.043-.004-.082-.012-.102-.063c.149.064.106-.215.258-.145");
}

.whw13eqzl {
  fill: var(--svg-color--554b12, #554b12);
  d: path("M20.294 23.07c.207.055.447-.029.621.151c-.193-.094-.449.045-.621-.151");
}

.wieat5btn {
  fill: var(--svg-color--4a4b4b, #4a4b4b);
  d: path("M24.345 34.24q-.02-.001-.037.004c.004-.125-.043-.256.037-.373z");
}

.wj_ckq09v {
  fill: var(--svg-color--3c3d3d, #3c3d3d);
  d: path("m18.21 29.31l-.02.005h-.016a.5.5 0 0 0 .034-.268a.08.08 0 0 1 .063-.016c.096.051.125.162.201.229q.021-.011.049-.004c-.047.09.136.18 0 .271c-.045-.154-.112-.287-.311-.217");
}

.wj_vwvb_t {
  fill: var(--svg-color--483f0e, #483f0e);
  d: path("M16.972 22.18c-.019-.021-.035-.036-.051-.055l.252-.013q-.003.022-.002.051q-.098.007-.199.017");
}

.wjfxevbrz {
  fill: var(--svg-color--575655, #575655);
  d: path("M24.502 31.19c.015.039.035.075.05.109c.01.079.018.157-.031.229a.14.14 0 0 1-.103-.08c-.022-.102-.051-.206.084-.258");
}

.wjxgh0xps {
  fill: var(--svg-color--625512, #625512);
  d: path("M22.277 39.692c-.017.021-.026.055-.04.059c-.039.004-.061-.03-.059-.064c.004-.021.03-.041.051-.046c.011-.001.028.028.048.051");
}

.wk2sl56nx {
  fill: var(--svg-color--f6f6f6, #f6f6f6);
  d: path("M17.487 40.02c-.02.066-.04.143-.059.217c-.062.079-.127.156-.096.268c-.02.033-.033.06-.055.087c-.098.171-.081.362-.131.543q-.002.054-.053.042c-.158-.023-.158.213-.313.201c-.161-.174-.009-.344-.004-.521c.017-.063.042-.123.06-.188c.036-.094.065-.185.104-.279c.014-.081.055-.156.094-.23c.046-.07.035-.156.074-.236c.052-.025.07-.073.08-.127c.061-.045.078-.144.17-.155c.092.038.083.136.121.209c.016.048.043.106.008.169");
}

.wkhzgeb_f {
  fill: var(--svg-color--1f1c1c, #1f1c1c);
  d: path("M21.458 32.622c.206.097.037.275.09.408q.038.04-.015.063c-.021-.019-.037-.027-.056-.045a.34.34 0 0 1-.104-.134c-.002-.008-.005-.021-.009-.028v-.031c.007-.014.011-.024.02-.032c.088-.043.037-.137.074-.201");
}

.wl3upcbqp {
  fill: var(--svg-color--3f3810, #3f3810);
  d: path("M13.433 20.991c.043.133.199.027.259.133h-.322q.032-.07.063-.133");
}

.wl9h40b4f {
  fill: var(--svg-color--770907, #770907);
  d: path("m17.07 27.1l.051.06a.6.6 0 0 1 .005.35c.004.016 0 .023-.013.031c-.09-.14-.011-.3-.043-.441");
}

.wl9ul95wm {
  fill: var(--svg-color--513834, #513834);
  d: path("M15.03 18.558q-.028-.007-.063-.012c-.004-.125-.012-.252.125-.311q.029.029.035.074c-.007.091-.011.188-.097.249");
}

.wlhpq6bxp {
  fill: var(--svg-color--707070, #707070);
  d: path("M23.472 33.634c.074.063.039.146.039.224c-.162-.052-.112-.138-.039-.224");
}

.wm527vbhk {
  fill: var(--svg-color--696868, #696868);
  d: path("M17.396 30.883c-.221.079-.043.312-.166.424c-.021-.006-.036-.026-.049-.05c.004-.092.023-.189.017-.268c-.021-.244.09-.162.198-.106");
}

.wmg2s8b9b {
  fill: var(--svg-color--282929, #282929);
  d: path("M19.214 27.366c.016.021.028.041.047.056c-.013.086.004.177-.09.243c.014-.103.026-.2.043-.299");
}

.wmp_u9tta {
  fill: var(--svg-color--241508, #241508);
  d: path("M22.966 39.439c.108.044.076.157.11.236c.082-.036.146-.083.138-.188l-.005.004c.021 0 .037 0 .058.004c.002.176-.107.258-.256.314a7 7 0 0 1-.045-.37");
}

.wnfi42bew {
  fill: var(--svg-color--574c10, #574c10);
  d: path("M19.569 21.905c-.123.008-.247.021-.363-.035c.035-.056.104-.02.148-.051h.318c.021.09-.073.051-.103.086");
}

.wnoda5b7f {
  fill: var(--svg-color--4a2a28, #4a2a28);
  d: path("M17.02 26.95q.02-.005.037-.004c.074.063.205.086.174.229a.1.1 0 0 0-.043-.012a.07.07 0 0 1-.059.02c-.027-.02-.041-.051-.057-.079a3 3 0 0 0-.052-.154");
}

.woovunb2v {
  fill: var(--svg-color--47420e, #47420e);
  d: path("M21.493 26.589h.262c.016.017.022.023.016.039q-.008.018-.016.017c-.103.049-.193.053-.262-.056");
}

.wp4jrmbjk {
  fill: var(--svg-color--333535, #333535);
  d: path("M19.987 30.935c-.092.294-.025.598-.045.893l.005-.004c-.118-.21-.096-.761.04-.889");
}

.wq25_8b1t {
  fill: var(--svg-color--2b556e, #2b556e);
  d: path("M17.604 22.592c-.004.071-.035.138-.113.142c-.086.006-.148-.047-.152-.137c-.002-.091.061-.143.146-.143c.078 0 .112.064.119.138");
}

.wqc1dz54w {
  fill: var(--svg-color--484747, #484747);
  d: path("M23.361 29.16h-.049v-.418c.074.143.136.24.111.365c-.024.016-.041.037-.062.053");
}

.wquxe5pph {
  fill: var(--svg-color--242424, #242424);
  d: path("M21.964 31.673h-.05c-.034-.086-.077-.165-.063-.264q.024-.032.05 0z");
}

.wqv71cb2l {
  fill: var(--svg-color--c7ae22, #c7ae22);
  d: path("M18.868 22.696c.055-.043.105-.08.161-.119a.28.28 0 0 0-.19-.152l.104-.09c.039.013.082.022.121.041c.082.035.178.074.166.18c-.018.117-.119.157-.236.143q-.063-.004-.126-.003");
}

.wqwfq-bfo {
  fill: var(--svg-color--62380f, #62380f);
  d: path("M14.897 21.702h.027c.006.18-.145.147-.25.184c-.025-.041-.051-.079.023-.071c.093.004.156-.041.2-.113");
}

.wr7nvibas {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("M15.558 30.946q-.001.025.004.045l-.098.158c.154.139.051.295.02.445c-.006.066-.028.13-.04.191c-.056.1-.093.213-.212.254q-.036.024-.072.055c-.104-.1-.105-.245-.163-.368a.35.35 0 0 1 0-.203a.8.8 0 0 0 .079-.376a.6.6 0 0 1 .031-.199c.031-.06.051-.135.145-.11l-.006-.009c.066.143.179.151.312.117");
}

.ws6jr_-nr {
  fill: var(--svg-color--4c2020, #4c2020);
  d: path("M17.05 34.661c-.015.018-.024.041-.039.058c-.043-.021-.035-.104-.104-.086c-.051-.027-.054-.071.013-.084c.087-.024.117.036.13.112");
}

.wsa7m8b4z {
  fill: var(--svg-color--483d0e, #483d0e);
  d: path("M13.956 37.487a.6.6 0 0 0 .307-.016a1 1 0 0 0 .057.075c-.014.022-.023.022-.043 0c-.109 0-.217.038-.327-.005z");
}

.wsasa4v4o {
  fill: var(--svg-color--322828, #322828);
  d: path("M17.226 17.557c-.068.078-.047.173-.053.265q-.024.021-.056 0c-.009-.088.017-.182-.035-.269l.146-.047q.024.018.012.036q-.006.016-.014.015");
}

.wsxaxxbkf {
  fill: var(--svg-color--6c5d2f, #6c5d2f);
  d: path("M19.31 18.18c.018-.008.029-.023.043-.039q.11.005.211.012c-.077.058-.167.034-.254.027");
}

.wukuzibfh {
  fill: var(--svg-color--4e4f4f, #4e4f4f);
  d: path("m15.61 32.23l.011-.052c.108-.021.126-.165.229-.196h-.004c-.005.153-.052.267-.236.248");
}

.wv1g3yb3c {
  fill: var(--svg-color--79797b, #79797b);
  d: path("M12.638 35.907c.019.035.037.076.058.114c.006.06-.027.127-.071.091c-.069-.05-.026-.138.013-.205");
}

.wvpsi8bfw {
  fill: var(--svg-color--191919, #191919);
  d: path("M12.396 31.575v.5c-.082-.203-.062-.401-.049-.604c.098-.001.06.057.049.104");
}

.ww3xi171i {
  fill: var(--svg-color--280b0b, #280b0b);
  d: path("m25.401 30.3l-.047-.312c.011-.026.027-.031.043-.004c.068.104.047.221.051.33q-.035.017-.047-.014");
}

.wwifklb_k {
  fill: var(--svg-color--e6c626, #e6c626);
  d: path("m15.302 40.612l-.009.02c-.093.098-.153.021-.222-.04a.41.41 0 0 1-.061-.425c.092-.108.193-.143.312-.038a.3.3 0 0 1 .041.116a.5.5 0 0 1-.002.16c-.014.073-.061.129-.059.207");
}

.wwsg8tbvu {
  fill: var(--svg-color--f8f9f9, #f8f9f9);
  d: path("M18.05 39.77c-.017-.021-.031-.048-.047-.071c-.064-.065-.035-.14-.025-.211c.002-.164-.006-.332.004-.5q.02-.047.068-.035z");
}

.wwzisi-fi {
  fill: var(--svg-color--c9aa21, #c9aa21);
  d: path("M22.22 36.528c.117-.058.248-.012.371-.031a.4.4 0 0 0 .041.053c-.138-.012-.276-.014-.412-.022");
}

.wx40dwb3k {
  fill: var(--svg-color--fbdf2b, #fbdf2b);
  d: path("M22.433 18.758c.002-.035-.09-.067-.004-.106q.1.007.198.008c.011.008.013.027.013.041a.11.11 0 0 1-.065.092c-.056.02-.103.016-.142-.035");
}

.wy5405b-i {
  fill: var(--svg-color--cbcbcb, #cbcbcb);
  d: path("M17.351 28.2c.074.103.022.215.039.321q-.01.158-.164.164c-.064-.016-.058-.065-.055-.114c.1-.102.084-.25.129-.373a.2.2 0 0 0 .051.002");
}

.wydmfufbl {
  fill: var(--svg-color--3c340b, #3c340b);
  d: path("m24.24 37.448l.108-.011q.042.027.084.05c.084.088.053.151-.035.217c-.156-.019-.086-.186-.157-.256");
}

.wyfjm04gk {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M15.298 29.85q-.015.07-.039.146c.055.101.023.192-.008.293c-.056.127-.016.283-.098.403c-.014.019-.023.044-.04.063a.25.25 0 0 1-.097.06q-.099.01-.157-.078c-.015-.021-.022-.043-.031-.066l-.044-.182c-.012-.078.023-.152.023-.231c.043-.122.019-.267.115-.369a.1.1 0 0 0 .012-.047c.126-.039.245.001.364.008");
}

.wzeq6zb9t {
  fill: var(--svg-color--ededed, #ededed);
  d: path("m18.524 29.25l.375.008c.037.07.004.152.008.229c-.02.131-.042.258-.15.357c-.113.031-.152-.067-.203-.13a.4.4 0 0 1-.054-.177c.019-.086-.021-.172.003-.265c.006-.007.014-.01.021-.022");
}

.wzy--or3w {
  fill: var(--svg-color--3f2e2e, #3f2e2e);
  d: path("M21.443 29.96c0-.047-.007-.09-.009-.133c-.004-.082.058-.099.113-.123a6 6 0 0 1-.104.256");
}

.x_24filih {
  fill: var(--svg-color--2c2608, #2c2608);
  d: path("M23.829 38.31c.158.033.249.087.292.184c.031.074.039.203-.051.229c-.104.023-.056-.089-.079-.143c-.033-.085-.092-.155-.162-.27");
}

.x-c974huw {
  fill: var(--svg-color--363636, #363636);
  d: path("m19.451 38.34l-.097.382q-.048-.066-.1-.131a.07.07 0 0 1-.016-.063c.05-.084.042-.203.146-.259c.049-.002.054.034.067.071");
}

.x-tkjxbcf {
  fill: var(--svg-color--3a1e0b, #3a1e0b);
  d: path("m14.411 38.02l.008-.052c.02-.039.061-.05.1-.067q.029-.013.055-.022l.121-.015c-.037.16-.154.17-.284.156");
}

.x02xg3bjg {
  fill: var(--svg-color--024793, #024793);
  d: path("M20.06 22.592c-.006.079-.045.131-.125.135c-.078.003-.125-.043-.125-.126c0-.076.037-.133.121-.138c.079 0 .12.052.129.129");
}

.x0rl3hldp {
  fill: var(--svg-color--303130, #303130);
  d: path("M25.403 31.618q.021-.001.041.004v.468q-.022.008-.043.006z");
}

.x118l2bct {
  fill: var(--svg-color--4d280a, #4d280a);
  d: path("M15.97 39.491h-.055c-.053-.039-.113-.074-.109-.152c.086.018.145.062.164.152");
}

.x1tmo-fxy {
  fill: var(--svg-color--343535, #343535);
  d: path("M14.47 29.31c.08.138.121.294.262.385q.015.04-.02.06c-.092-.012-.174.022-.262.055a.13.13 0 0 1-.061-.032c-.006-.016-.019-.03-.019-.047c0-.122.015-.249-.12-.319c.058-.078.106-.16.22-.102");
}

.x1uaysb2c {
  fill: var(--svg-color--3e3c2c, #3e3c2c);
  d: path("M21.267 20.18c0 .051-.01.125.037.129c.096.02.113-.104.181-.141q-.015.078-.037.156c-.024.06-.074.063-.125.066c-.097-.045-.193-.101-.056-.21");
}

.x2apdee5z {
  fill: var(--svg-color--d7d7d4, #d7d7d4);
  d: path("M23.2 21.13c-.02-.006-.036-.01-.057-.02c-.122-.117-.104-.24.006-.353c.109-.117.199-.255.304-.374c.039-.079.073-.153.144-.207a.13.13 0 0 1 .068-.014a.23.23 0 0 1 .102.041q.023.015.022.039q-.006.02-.012.021l.004.003c-.082.079-.03.212-.122.287c-.072.039-.117.11-.165.172c-.028.032-.069.051-.083.099c-.074.103-.169.181-.211.306");
}

.x2gr-omvx {
  fill: var(--svg-color--1a2321, #1a2321);
  d: path("M15.255 23.12c.065-.094.016-.168-.021-.254c.141.074.199.153.021.254");
}

.x38ly3--h {
  fill: var(--svg-color--232323, #232323);
  d: path("M24.916 30.3q.003.083.009.153q-.007.085-.011.162l-.05-.06c.005-.083.005-.169.011-.25q.022-.044.041-.005");
}

.x5h6g2x2j {
  fill: var(--svg-color--16140c, #16140c);
  d: path("m13.572 20.23l.058-.04c.057.063.086.133.063.225c-.092-.025-.079-.125-.121-.185");
}

.x6nr44z8b {
  fill: var(--svg-color--573130, #573130);
  d: path("m15.974 36.34l.047.061c-.035.067-.033.165-.145.165z");
}

.x6wf8iblu {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M22.11 29.979c0 .02.006.042.006.063c-.02.13.063.244.07.373c.011.043.005.09.009.138a1 1 0 0 0 .005.249c-.012.064-.032.125-.094.165q-.136.051-.194-.091l-.047-.06l-.063-.142c-.002-.066-.006-.129.029-.196c.051-.09-.039-.06-.072-.067c-.064-.164.1-.18.166-.26c.068-.054.092-.128.088-.216z");
}

.x77d_qb6o {
  fill: var(--svg-color--3e3f3f, #3e3f3f);
  d: path("M12.704 35.546c.021-.238-.043-.485.04-.725v.729q-.026.041-.04-.004");
}

.x7c_bd3ri {
  fill: var(--svg-color--572c2b, #572c2b);
  d: path("M17.02 38.13q-.021-.029-.039-.061c.02-.066.02-.143.111-.152c-.015.068-.007.154-.072.213");
}

.x7keotbtn {
  fill: var(--svg-color--291818, #291818);
  d: path("M17.05 34.661c.002.114.109.252-.076.317c.013-.086.021-.172.037-.265c-.029-.042 0-.052.039-.052");
}

.x7p4e2f-b {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M21.384 29.997v2.826c-.385.063-.77.022-1.149.022c-.361 0-.718.044-1.076-.022c-.003-.881-.003-1.761-.011-2.641c0-.141.043-.2.191-.195c.683.006 1.362.006 2.045.01");
}

.x80frpb7n {
  fill: var(--svg-color--dfe0e0, #dfe0e0);
  d: path("M20.411 29.26c-.016.055-.064.047-.104.047c-.021-.021-.039-.041-.06-.051c-.185-.09-.271-.232-.214-.438c.018-.066.047-.138.139-.08q.04.047.077.094c.013.1.021.192.093.269c.025.053.046.102.069.159");
}

.x95h37_rc {
  fill: var(--svg-color--282a2a, #282a2a);
  d: path("M12.917 36.45q-.032-.005-.063-.004c.017-.07.029-.141.047-.211q.037.005.072.004c-.009.074.011.149-.056.211");
}

.x98gabccl {
  fill: var(--svg-color--dedee2, #dedee2);
  d: path("M22.02 18.739c-.039.008-.075.02-.112.022c-.021.03-.031.067-.069.075c-.023 0-.041-.016-.053-.036c.004-.078-.046-.134-.07-.196c-.039-.059-.076-.126-.115-.188c.056-.008.115-.016.164.027q.048.083.096.16c-.006.126.084.11.16.115v.021z");
}

.x9al4cb3o {
  fill: var(--svg-color--7b6d16, #7b6d16);
  d: path("M14.988 23.592q0-.148.005-.304h.059c-.098.22.104.166.191.209c-.085.031-.167.059-.255.095");
}

.xah0-8kpl {
  fill: var(--svg-color--4a4b4b, #4a4b4b);
  d: path("M17.54 38.801c-.033.125-.066.255-.1.38a.2.2 0 0 1-.045-.061c.053-.1-.044-.277.145-.319");
}

.xb7fy4rfk {
  fill: var(--svg-color--242424, #242424);
  d: path("M14.784 33.03c.016 0 .034.004.055.004c.004.047-.013.092-.059.114c-.032-.028-.105-.01-.094-.079c.004-.017.063-.024.098-.039");
}

.xbb28sbwk {
  fill: var(--svg-color--eeeeed, #eeeeed);
  d: path("M15.513 20.557c-.074-.034-.117-.103-.162-.165c-.049-.079-.004-.154-.002-.229c.021-.105.092-.152.193-.168q.08 0 .154.02a.15.15 0 0 1 .093.066c-.04.104.099.205-.021.299c-.281-.234-.136.164-.255.177");
}

.xbt06cceo {
  fill: var(--svg-color--391e1d, #391e1d);
  d: path("M16.712 35.614c-.076.065-.051.156-.053.242c-.077-.105-.15-.209.053-.242");
}

.xc7rmzbmx {
  fill: var(--svg-color--262626, #262626);
  d: path("M23.21 34.03q-.018.026-.041.047c-.011-.103-.083-.195-.056-.312h.032a.42.42 0 0 1 .065.265");
}

.xcffumbgm {
  fill: var(--svg-color--462e0c, #462e0c);
  d: path("M12.591 38.435c-.025.073-.098.157.002.232c-.002.046-.02.061-.063.037c-.056-.104-.107-.213.061-.269");
}

.xcjcd4tcx {
  fill: var(--svg-color--3e1b0c, #3e1b0c);
  d: path("M15.05 37.39a1 1 0 0 0-.109.088c-.004-.161-.102-.137-.205-.107q-.05-.033-.004-.082l-.004.004c.113.014.258-.081.322.097");
}

.xcyj0y_yt {
  fill: var(--svg-color--780503, #780503);
  d: path("m24.985 36.665l.007-.543a.1.1 0 0 0 .028.004c.001.187.036.363-.035.539");
}

.xd-ms1gfu {
  fill: var(--svg-color--3d3c3c, #3d3c3c);
  d: path("M17.437 35.647c-.004-.016-.004-.029-.008-.05c.02-.052.033-.101.056-.149h.045c.012.086-.003.166-.093.199");
}

.xdf3k3b1g {
  fill: var(--svg-color--4c4b4b, #4c4b4b);
  d: path("m24.64 28.765l-.082-.354c.127.125.129.138.082.354");
}

.xdimn6utz {
  fill: var(--svg-color--a2100f, #a2100f);
  d: path("M19.664 21.544h-.31q.054-.05.109-.104c.018-.004.032-.012.051-.016c.031.079.104.061.166.066c-.003.024-.011.033-.016.054");
}

.xduq_7bqn {
  fill: var(--svg-color--2a2b2b, #2a2b2b);
  d: path("M19.664 40.22h-.045c-.066-.056-.045-.14-.055-.206h.048c.028.062.071.125.052.206");
}

.xe4o_abkn {
  fill: var(--svg-color--fad528, #fad528);
  d: path("m15.816 18.405l.061-.063a.13.13 0 0 0 .039-.048l.052-.065a.3.3 0 0 1 .105-.055c.025-.009.043-.011.063-.015c.03-.021.058-.047.092-.047c.055.004.1-.021.147-.027c.056-.014.11.004.166 0c.216.011.444-.11.642.07c-.047.133-.178.06-.26.103c-.057.012-.113.021-.17-.009l-.242.101a.8.8 0 0 0-.277.095l-.254.184a.46.46 0 0 0-.08.248c.025.139-.049.283.047.418c.01.015.02.025.029.047c-.027.113.072.18.103.273q.13.2.269.394c.09.09.135.192.047.306c.007.079-.059.109-.098.158a.4.4 0 0 0-.041.136c-.013.052-.035.105-.09.11c-.063.004-.043-.082-.083-.11c0-.06 0-.112-.005-.173q-.017-.029-.004-.063c.035-.055.043-.105.009-.162c-.05-.084-.133-.141-.188-.227a4 4 0 0 1-.121-.244c-.022-.039-.041-.086-.057-.125c-.033-.102-.065-.207-.104-.307l-.022-.066a.6.6 0 0 1-.021-.308c.034-.094.048-.192.079-.287c.03-.101.063-.201.167-.242");
}

.xeha01y2w {
  fill: var(--svg-color--554b10, #554b10);
  d: path("M17.18 22.12c.201-.076.412-.043.618-.052c.062-.011.136-.075.155.048q-.386.024-.775.055q-.023-.018-.015-.034c.004-.015.011-.017.017-.017");
}

.xeoklhbxw {
  fill: var(--svg-color--353535, #353535);
  d: path("M22.688 29.677c.047.138-.192.07-.148.208a.1.1 0 0 1-.068.028c-.086-.008-.176-.008-.25-.063c-.02-.021-.018-.047 0-.067c.158-.04.314-.071.466-.106");
}

.xepgp9xoo {
  fill: var(--svg-color--565e5e, #565e5e);
  d: path("m12.261 34.3l.012-.104c.107.148.027.317.061.476q-.018-.002-.035-.009c-.085-.12-.024-.24-.038-.363");
}

.xeqzf3mvo {
  fill: var(--svg-color--606060, #606060);
  d: path("M23.785 32.51q.022-.018.002-.031c.062.147.05.304.038.455c-.032.036-.004.086-.051.108c-.043-.178-.095-.356.011-.532");
}

.xerd80bon {
  fill: var(--svg-color--4e3232, #4e3232);
  d: path("m18.421 28.05l.057-.013c.066.06.045.143.056.212c.019.028.017.048-.006.071c-.134-.031-.134-.134-.13-.24c.009-.008.017-.023.023-.03");
}

.xflxsqbzo {
  fill: var(--svg-color--232323, #232323);
  d: path("M13.11 29.846q.026-.064.05-.114c.021.104.04.213.06.318c-.105-.032-.099-.12-.11-.204");
}

.xg3iss5me {
  fill: var(--svg-color--42250a, #42250a);
  d: path("M22.17 37.558c.097-.006.196-.044.28.039c-.004.02-.014.038-.018.061c-.084-.023-.172-.063-.258 0c-.026-.04-.03-.063-.004-.1");
}

.xg7rohbpo {
  fill: var(--svg-color--4e2727, #4e2727);
  d: path("m15.983 29.829l.002.105c.066.166.123.33-.02.486c-.055.013-.093.004-.093-.063c.166-.181.019-.396.06-.59z");
}

.xg88u1dih {
  fill: var(--svg-color--660908, #660908);
  d: path("M13.802 38.446c-.011-.021-.027-.043-.039-.063q.012-.045.023-.102l.051-.004c.01.064.01.121-.035.169");
}

.xh95xxb9n {
  fill: var(--svg-color--ececec, #ececec);
  d: path("M16.226 17.605c.104-.128.225-.132.356-.05c.071.059.123.121.067.215l.004-.008c-.031.098-.027.229-.17.238c-.098-.008-.199-.004-.27-.098c.009-.091-.032-.196.013-.297");
}

.xhz137o6b {
  fill: var(--svg-color--b69c1b, #b69c1b);
  d: path("M13.942 20.19c-.049.012-.096.031-.145.047q-.012-.018-.007-.044c-.039-.069-.024-.14-.017-.212q.033-.038.074-.011c.071.055.056.144.095.22");
}

.xi884fbxc {
  d: path("M19.353 21.819c-.051.016-.1.03-.146.051l-.018.002l-.021-.002c.009-.051.052-.058.091-.067z");
}

.xiu0-vx2t {
  fill: var(--svg-color--bcbebe, #bcbebe);
  d: path("m18.218 17.893l.055.036q-.005.024-.012.043a.1.1 0 0 1-.031.041a.1.1 0 0 1-.072.02l-.025-.004h-.023c-.006-.198-.006-.198.108-.136");
}

.xje3tuqec {
  fill: var(--svg-color--dadada, #dadada);
  d: path("M19.09 28.624c-.064-.055-.037-.133-.043-.209c.069-.051.063-.133.09-.205c.037-.053.082-.104.119-.155c.102.079.023.172.021.259c.039.137-.004.236-.116.311z");
}

.xkpgi9m-t {
  fill: var(--svg-color--450504, #450504);
  d: path("m12.328 34.702l.015.153c.026.086.039.163-.015.243c-.049-.127-.091-.267 0-.396");
}

.xkrerdbuw {
  fill: var(--svg-color--ec1e17, #ec1e17);
  d: path("M15.15 21.982q0 .032-.022.033c-.12.062-.243.035-.362.004c-.052-.028-.105-.06-.086-.132c.053-.096.223-.021.238-.174c.064-.066-.074-.244.122-.244c.038.012.06.043.067.083c.018.047.031.101.049.142q.048.15-.006.288");
}

.xljc6oayd {
  fill: var(--svg-color--c8b022, #c8b022);
  d: path("M23.511 20.392a.5.5 0 0 0-.099-.055c-.004-.092.078-.133.106-.208c.018-.011.035-.017.055-.007a.1.1 0 0 1 .031.051c.016.091-.062.14-.093.219");
}

.xlyvrebax {
  fill: var(--svg-color--fbfbfb, #fbfbfb);
  d: path("M20.14 40.485c-.02-.054-.039-.117-.062-.173c-.058-.071-.082-.161-.122-.239c-.061-.078-.039-.158-.012-.24c.037-.068.029-.176.134-.2c.084.038.09.132.144.192a.4.4 0 0 0 .129.191l.012.008c-.012.104.041.184.093.262c.019.022.033.052.052.074c-.008.109.047.199.075.301c.017.057.039.109.058.178c.045.111.041.238.069.354c.017.217-.084.221-.229.127c-.004-.062-.057-.074-.1-.1c-.039-.016-.092-.016-.082-.079q-.024-.027-.053-.05a2.4 2.4 0 0 0-.041-.324c-.024-.092-.071-.184-.065-.282m.733-4.488c.065-.106.138-.215.202-.321c.003-.068.059-.12.053-.19q.058-.064.109-.135c.023-.035.055-.039.09-.035c.023.008.043.023.063.035c.08.074.121.172.178.266q.01.03.008.073a3 3 0 0 1-.09.433a.64.64 0 0 1-.182.277c-.082.067-.129.18-.248.205c-.164.061-.094-.1-.139-.152a.3.3 0 0 1-.068-.201c.002-.089-.02-.171.024-.255");
}

.xm17en4tj {
  fill: var(--svg-color--191a1a, #191a1a);
  d: path("M13.527 34.35a.67.67 0 0 1-.052.417c-.041.007-.066 0-.045-.049q.004-.046.004-.093c.072-.073-.061-.229.1-.275z");
}

.xm5vy6b0z {
  fill: var(--svg-color--2a2a2b, #2a2a2b);
  d: path("M19.826 28.18c-.021.046-.037.089-.058.133c-.019.012-.035.016-.057 0c-.043-.043-.045-.113-.078-.169q-.001-.136.08-.255h.047c.039.07-.074.232.119.216l.004.031q-.029.024-.057.044");
}

.xmeeb1o7c {
  fill: var(--svg-color--484545, #484545);
  d: path("M19.12 41.79c.064-.047.154-.069.186-.156c.049.189-.071.167-.186.156");
}

.xmk57ez-f {
  fill: var(--svg-color--13110c, #13110c);
  d: path("m23.527 20.763l-.06-.057c.034-.069.073-.142.155-.156q0 .024.004.055a4 4 0 0 1-.099.158");
}

.xmvtafbjl {
  fill: var(--svg-color--393b3b, #393b3b);
  d: path("M24.45 30.13c-.123-.036-.126-.103-.048-.188q.025.093.048.188");
}

.xo6qppbqz {
  fill: var(--svg-color--402009, #402009);
  d: path("M24.14 37.967c-.061-.017-.11-.042-.143-.121c.083-.042.178.03.251-.026c.017.008.024.022.019.03c-.004.017-.01.021-.015.021v.1c-.034.032-.075.026-.112-.004");
}

.xoq4i3ban {
  fill: var(--svg-color--4e4f4f, #4e4f4f);
  d: path("m12.08 32.667l-.045-.117c.049 0 .085-.117.132-.044c.03.05-.028.12-.087.161");
}

.xp5_tl-wz {
  fill: var(--svg-color--290b04, #290b04);
  d: path("M22.681 36.521a.4.4 0 0 0-.051.026c-.021-.022-.048-.026-.066-.042c-.021-.021-.033-.042-.023-.071c-.044-.046-.109-.078-.054-.157a.48.48 0 0 1 .194.244");
}

.xpe_svbyx {
  fill: var(--svg-color--4d0e0b, #4d0e0b);
  d: path("M19.822 36.98c-.017-.019-.035-.034-.054-.054c-.014-.028-.051-.042-.059-.076c.092-.047.184-.1.277-.146c.027.143-.2.133-.164.276");
}

.xpko25byx {
  fill: var(--svg-color--58280c, #58280c);
  d: path("M21.388 26.792c-.082.068-.131.008-.179-.051c.08-.054.128.004.179.051");
}

.xpm1--bnp {
  d: path("M16.187 18.03a.05.05 0 0 0-.004.04q-.016.042-.049.017h-.054c.007-.07.056-.067.107-.057");
}

.xpyzskl1j {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M20.09 38.23q-.057-.024-.117-.056c-.123-.054-.105-.199-.172-.292q-.011-.03-.013-.064a.6.6 0 0 0-.067-.285q-.04-.09-.086-.174a.8.8 0 0 0-.112-.16c-.038-.061-.081-.115-.083-.188q.015-.06.076-.063c.078-.02.152-.07.24-.058c.033.019.047.058.062.092c.073.251.261.438.381.662c.032.084.071.151.114.228c.049.082.047.182.08.269l-.004.082c-.098.09-.198.07-.299.007");
}

.xqfribb0i {
  fill: var(--svg-color--e0e1e1, #e0e1e1);
  d: path("M23.525 19.708c.011-.166-.109-.236-.212-.321c-.071-.048-.137-.104-.221-.142c-.063-.047-.125-.096-.199-.123c-.123-.056-.268-.056-.377-.148c-.021-.055-.008-.104.047-.134a.2.2 0 0 1 .113-.013c.088.063.203.021.291.08c.058.043.125.063.187.099c.116.059.211.149.313.229c.031.063.104.074.157.109a.2.2 0 0 1 .05.051l.002.114a.19.19 0 0 1 .053.167a.15.15 0 0 1-.026.07c-.04.047-.083.033-.13.012c-.015-.013-.031-.033-.048-.05");
}

.xsb5ygb1b {
  fill: var(--svg-color--f9d428, #f9d428);
  d: path("M21.13 18.09c.021.004.035.011.058.019c.019.165.146.125.25.134a.37.37 0 0 0 .156.153l.008.022c.109.026.135.129.166.216c.086.208.071.429.043.647c-.039.047-.033.103-.035.161a3 3 0 0 0-.116.244c-.05.097-.085.188-.126.292c-.049.089-.137.153-.204.23c-.069.084.021.135.043.201c.011.086-.035.156-.056.24c-.062.133-.098.047-.135-.016c-.019-.067-.063-.121-.086-.188q-.035-.045-.068-.095c-.047-.095-.119-.188 0-.284q.253-.3.425-.646c.026-.106.063-.204.075-.307c-.012-.125.027-.244-.028-.361a1.03 1.03 0 0 0-.414-.357c-.091-.031-.179-.08-.288-.08c-.093-.063-.205-.039-.306-.063c-.099-.016-.2-.016-.298-.043c-.047-.012-.067-.039-.041-.09c.209-.078.418-.063.632-.035c.106-.012.209.051.315.012q.012-.001.03-.006");
}

.xsdaqnc8l {
  fill: var(--svg-color--f4f4f4, #f4f4f4);
  d: path("M15.873 30.36q.016.031.035.059a.3.3 0 0 1 .063.063c.016.251.117.517-.119.724c-.113.031-.156-.043-.189-.135c-.014-.062-.025-.133-.045-.199a.6.6 0 0 1 0-.25c.063-.092-.018-.284.188-.269q.031.005.067.007");
}

.xtcdpyb4a {
  fill: var(--svg-color--191818, #191818);
  d: path("M17.542 35.823c-.039-.004-.08-.004-.117-.011l.217-.104c-.002.063-.034.105-.1.115");
}

.xtowobcmy {
  fill: var(--svg-color--2b1812, #2b1812);
  d: path("M14.724 19.13c.033-.047.082-.047.127-.047c.045.062.041.129.004.195q-.033.035-.075.012h-.047z");
}

.xtxtshmdd {
  fill: var(--svg-color--553130, #553130);
  d: path("M21.07 40.812a.5.5 0 0 1-.1-.232c.138.032.152.118.1.232");
}

.xutshwblt {
  fill: var(--svg-color--62380e, #62380e);
  d: path("M16.17 22.644c-.063.137.012.203.118.268c.019.006.024.02.021.027q-.008.017-.017.016c-.245-.107-.268-.161-.122-.311");
}

.xw9ce4o5g {
  fill: var(--svg-color--313725, #313725);
  d: path("M21.541 21.19q.002.025 0 .046c-.133 0-.278.041-.366-.105l.024.005c.104-.071.196-.028.292.028c.02.009.034.019.05.026");
}

.xwa2_q93i {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("M19.778 40.763c0-.048-.006-.086-.008-.132c-.084-.119-.07-.269-.121-.397c-.031-.07-.038-.146-.061-.217c-.054-.09-.086-.172.057-.203a.2.2 0 0 1 .074.016c.078.071.16.143.234.222c.063.078.083.187.157.265a.36.36 0 0 1 .06.165c.004.107.031.224.061.328c.025.08.021.163.061.241a.16.16 0 0 1 .01.143c-.078.104.021.264-.103.354c-.187.094-.187-.135-.297-.172c-.132-.102-.095-.242-.103-.375a1.2 1.2 0 0 1-.021-.238");
}

.xwcl2lbev {
  fill: var(--svg-color--3a3b3b, #3a3b3b);
  d: path("M24.343 27.577c-.02.004-.035.004-.055.004c-.046-.047-.035-.104-.031-.16c.049.035.123.043.141.121a.07.07 0 0 1-.055.035");
}

.xwzvrddkf {
  fill: var(--svg-color--5c2f2e, #5c2f2e);
  d: path("M15.05 33.94c-.021-.111.041-.193.092-.279q.037.02.043.056c-.03.085-.047.172-.135.223");
}

.xy_9uvb9f {
  fill: var(--svg-color--8b7917, #8b7917);
  d: path("M19.2 22.03c.146-.006.294-.029.433.032c-.066.097-.186.071-.275.115c-.201.04-.406.012-.607.028a.12.12 0 0 1-.076-.041c-.143-.109-.303-.008-.455-.056c-.004-.062.047-.058.092-.062c.294-.01.59.022.888-.016");
}

.xy_x-ebji {
  fill: var(--svg-color--e2c725, #e2c725);
  d: path("M21.03 26.321c-.048.06-.095.11-.146.161c-.021-.024-.048-.04-.07-.063a.2.2 0 0 1 .019-.043c.058-.031.058-.121.138-.125c.016.022.041.047.059.07");
}

.xyjj2xbuj {
  fill: var(--svg-color--292929, #292929);
  d: path("M18.687 28.726c-.004.043-.006.083-.014.126c-.105-.017-.111-.123-.16-.192a.14.14 0 0 1-.01-.067c.016-.043.053-.066.096-.075c.008-.004.021-.004.031-.004c.067.055.036.136.057.212");
}

.xyulynbdt {
  fill: var(--svg-color--443d18, #443d18);
  d: path("M15.983 20.325c.107.017.185-.011.166-.141c.07.094.07.168-.059.211c-.044-.005-.097-.005-.107-.07");
}

.xze268bqf {
  fill: var(--svg-color--615f56, #615f56);
  d: path("M22.02 18.739c.084.125-.055.248 0 .373c.021.027.02.059-.002.082q-.072.038-.129-.016a.45.45 0 0 1-.002-.41c.037-.035.086-.029.133-.029");
}

.xzs7mwb4v {
  fill: var(--svg-color--4d4310, #4d4310);
  d: path("M16.347 22.23c.131-.066.27-.055.406-.063c.055-.023.063 0 .053.047c-.156-.023-.304.114-.459.016");
}

.y_9zuhb9a {
  fill: var(--svg-color--424545, #424545);
  d: path("M22.22 30.27q-.033.083-.061.16c-.037-.124-.128-.248-.046-.386c.089.053.009.183.107.226");
}

.y_n0aughh {
  fill: var(--svg-color--573434, #573434);
  d: path("m12.09 33.825l.047-.062a.2.2 0 0 1 .041.169q-.03-.001-.058-.008q-.015-.045-.03-.099");
}

.y-2xx2scb {
  fill: var(--svg-color--2d2424, #2d2424);
  d: path("m20.15 34.458l-.055-.039c.084-.014.17-.021.254-.031c.023-.016.047-.006.063.018c-.081.052-.171.052-.262.052");
}

.y-gwllb8c {
  fill: var(--svg-color--451b0f, #451b0f);
  d: path("M16.595 21.646c.119-.055.267-.008.375-.104c-.08.199-.225.171-.375.104");
}

.y-zg8bbfe {
  fill: var(--svg-color--5e5213, #5e5213);
  d: path("M22.281 36.65h.032q.009.032.01.056l-.021-.008h-.021a.1.1 0 0 0 0-.048");
}

.y0k_8dqpi {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M22.371 30.782h.047c.106.004.106-.113.169-.158c.135.158.075.346.11.52c.073.104.085.234.128.352c.01.035.01.074.004.109c-.008.066-.085.12-.04.199V31.8c-.039.104-.112.117-.208.078h-.051c-.034-.074-.044-.155-.118-.207c-.02-.021-.033-.04-.05-.057a.37.37 0 0 1-.095-.277a.66.66 0 0 0-.006-.33c.008-.094-.027-.202.11-.225");
}

.y0rwezb0g {
  fill: var(--svg-color--f7d328, #f7d328);
  d: path("M14.155 39.487c-.018-.021-.03-.043-.047-.062c-.072-.114-.006-.213.045-.31q.004-.032.011-.06c.052-.132.125-.251.28-.281c.09-.036.18 0 .268.007c.057.041.152.053.149.15c.026.05-.149.078-.009.155c.063.028.027.144.056.213c.004.067-.008.123-.086.134q-.017-.007-.029-.008c-.089-.078-.174-.122-.272-.018c-.033.018-.066.032-.103.053c-.028.084.011.186-.079.246c-.088-.049-.19-.09-.184-.219");
}

.y1k51ulfg {
  fill: var(--svg-color--ededed, #ededed);
  d: path("M22.959 29.677c.022-.083-.062-.186.034-.255c.191.231.156-.128.266-.106c.11.113.032.303.157.413v.056c-.085.146.076.26.062.393c.002.086-.027.173-.031.259c-.033.083-.083.129-.176.108a.3.3 0 0 1-.144-.116c-.104-.142-.083-.317-.112-.479a.6.6 0 0 1-.056-.273");
}

.y2hi2wbhq {
  fill: var(--svg-color--cdb322, #cdb322);
  d: path("m22.423 20.419l.01.084c-.006.039-.006.078-.055.085q.005-.083.012-.165q.012-.005.033-.004");
}

.y2nvsub1j {
  fill: var(--svg-color--857416, #857416);
  d: path("M21.81 22.22a9 9 0 0 1-.422-.094c-.02-.012-.022-.021-.02-.033c.005-.01.014-.016.018-.016q.286.001.573-.004c.06.166-.062.139-.149.147");
}

.y3aj6uaid {
  fill: var(--svg-color--291919, #291919);
  d: path("M21.546 25.2c-.232-.146-.484-.1-.736-.086c.018-.061.063-.061.111-.061a.85.85 0 0 1 .418 0c.094.014.19.024.207.147");
}

.y3c3n7bhn {
  fill: var(--svg-color--4d430f, #4d430f);
  d: path("M15.513 22.23c-.125.09-.276.098-.422.137v-.037q.1-.06.197-.112c.075-.031.148-.06.219 0z");
}

.y3hmb8hdi {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("m15.933 31.673l-.012.081c0 .092-.053.157-.08.235c-.05.104-.104.201-.229.227c-.051-.018-.102-.032-.12-.088c.034-.174-.099-.338-.042-.516c.031-.146.081-.287.094-.441c.022-.09.041-.18.165-.143c.005.086.036.143.125.16c.083-.025.114.025.114.092c-.001.129.022.258-.015.393");
}

.y4_97teip {
  fill: var(--svg-color--222, #222);
  d: path("M22.854 32.407q.01.008.027.004q.033.151.064.309c-.161-.065-.087-.205-.091-.313");
}

.y4-5dnbdh {
  fill: var(--svg-color--6b2711, #6b2711);
  d: path("m20.236 21.245l.013-.086a.6.6 0 0 1 .086.282c-.086-.04-.101-.11-.099-.196");
}

.y41qtmgai {
  fill: var(--svg-color--3e3d18, #3e3d18);
  d: path("M23.415 20.821c-.029-.062.014-.086.053-.115c.031.01.051.021.06.057c.016.09.026.179.043.271c-.099-.041-.052-.179-.156-.213");
}

.y4bocf94d {
  fill: var(--svg-color--1d1e1d, #1d1e1d);
  d: path("M20.05 39.35a.2.2 0 0 0-.063-.015c-.053-.041-.053-.088-.029-.144c.018-.022.037-.022.063-.019c.017.08.136.105.104.207z");
}

.y4fg-9beh {
  fill: var(--svg-color--2e3131, #2e3131);
  d: path("M23.556 28.628c-.015.005-.047.02-.056.013c-.017-.017-.022-.043-.024-.067c-.006-.022.004-.055.037-.039c.037.014.054.042.043.093");
}

.y4kbnacry {
  fill: var(--svg-color--7f6c15, #7f6c15);
  d: path("M17.544 21.751c-.115.068-.164.022-.158-.103c.052.034.105.074.158.103");
}

.y5cmhjbkd {
  fill: var(--svg-color--404040, #404040);
  d: path("M18.11 40.71c-.138-.166.039-.322.012-.487c.043-.008.066.013.079.056z");
}

.y6d2t6bfe {
  fill: var(--svg-color--f1f2f2, #f1f2f2);
  d: path("M19.31 17.93c-.105.267-.033.542-.051.813c-.011.217.002.432.006.647q-.052.027-.086-.017c-.021-.026-.031-.06-.041-.09c-.02-.369-.004-.742-.008-1.115c0-.103.018-.192.076-.271h-.002c.033-.025.061-.083.111-.025c-.005.021-.005.037-.005.058");
}

.y6h3q8flo {
  fill: var(--svg-color--3e3d18, #3e3d18);
  d: path("m22.423 20.419l-.016.005h-.02c-.008-.035-.011-.074.033-.085c.003.023.003.053.003.08");
}

.y78wu3bau {
  fill: var(--svg-color--212222, #212222);
  d: path("M24.509 36.497h.043c.018.113.098.217.063.344c-.098-.096-.102-.219-.106-.344");
}

.y7mpudbph {
  fill: var(--svg-color--53230c, #53230c);
  d: path("M24.724 38.25v-.063c.146.04.08.165.099.257c-.035-.033-.074-.063-.11-.1c-.001-.029-.012-.063.011-.094");
}

.y7o8gtwlv {
  fill: var(--svg-color--1b1111, #1b1111);
  d: path("M21.392 34.454h.043a.7.7 0 0 0 .265.191c.03.063-.011.082-.056.113c-.051.021-.109.021-.152.061c-.02.012-.035.027-.053.043a1 1 0 0 0-.102.063q.029-.236.055-.471");
}

.y7pyh7xui {
  fill: var(--svg-color--201f1c, #201f1c);
  d: path("M20.761 26.749v.048c-.084.016-.17.024-.256.038v-.108q.131.017.256.022");
}

.y7qumyb5t {
  fill: var(--svg-color--660f0d, #660f0d);
  d: path("M22.22 23.708c.099-.043.223.095.314-.021c-.081.243-.206.078-.314.021");
}

.y82nh--tu {
  fill: var(--svg-color--f4d027, #f4d027);
  d: path("M18.382 20.342c-.041-.052-.08-.095-.121-.146c-.056-.162.055-.162.158-.162a.4.4 0 0 0 .065.004c.067-.022.086-.094.126-.141c.035-.035.074-.063.125-.063q.073.006.119.072c.037.051.004.164.125.14c.099-.017.201-.035.221.11a1 1 0 0 0-.26.368c.018.035.063.052.056.101c-.085.039.009.176-.108.203c-.203-.215-.203-.215-.357.031c-.078-.047-.051-.125-.051-.191c-.064-.104-.012-.236-.098-.326");
}

.y8jze_y7f {
  fill: var(--svg-color--4a2929, #4a2929);
  d: path("M19.298 26.626c.012.1-.033.171-.094.242c-.053-.119.012-.185.094-.242");
}

.y9n9338ei {
  fill: var(--svg-color--e7c726, #e7c726);
  d: path("M22.12 40.571c.004-.048-.01-.086-.053-.108c-.075-.109-.047-.209.009-.313c.114-.122.222-.106.329.013c.084.16.017.303-.076.432h.003c-.081.103-.151.107-.212-.024");
}

.y9zaxubxw {
  fill: var(--svg-color--44211e, #44211e);
  d: path("M19.16 32.825h2.228v.06c-.688 0-1.375 0-2.059-.009c-.074 0-.172.065-.221-.051z");
}

.y9zcelbri {
  fill: var(--svg-color--503534, #503534);
  d: path("M22.22 33.555c.063.06.08.146.1.229c-.127-.037-.116-.136-.1-.229");
}

.yb2dfnboz {
  fill: var(--svg-color--5f290c, #5f290c);
  d: path("M15.456 39.23a.1.1 0 0 1 .043 0c-.043.151.085.129.162.159a2 2 0 0 0-.15.1a.12.12 0 0 1-.099-.052c-.005-.074-.015-.148.044-.207");
}

.ybblv5xvi {
  fill: var(--svg-color--230f0e, #230f0e);
  d: path("M16.08 25.06v.042c-.085.04-.172.076-.258.118c.056-.105.137-.172.258-.16");
}

.ybg-5-bhy {
  fill: var(--svg-color--fbdc2b, #fbdc2b);
  d: path("M16.353 23.23c.029-.021.055-.036.084-.056c.089.039.17-.016.258-.023q.192 0 .381-.039q.095-.02.189-.043c.14.023.279.006.42-.023c.183 0 .365.012.547-.023c.332.003.664-.041.996-.027c.146.006.295-.004.445.015c.143.048.28.048.428.028c.074.004.147-.017.225.008c.184.094.398.052.593.113a1 1 0 0 1 .109.021c.146.043.292.047.438.087c.082.011.159.038.243.033c.022 0 .048.005.066.018a.9.9 0 0 0 .358.133c.102.034.217.038.311.109a.2.2 0 0 1 .037.066q.028.03.053.06c-.09.188-.21.017-.316.028c-.043-.008-.088-.012-.133-.021c-.091-.098-.234-.077-.338-.146a2 2 0 0 0-.148-.008c-.104-.021-.205-.071-.312-.052c-.087-.016-.163-.073-.252-.051c-.106-.022-.208-.074-.323-.05c-.054-.008-.119.004-.158-.057c-.084-.045-.178.014-.265-.027c-.065 0-.138.008-.202-.004c-.123-.039-.257 0-.379-.039c-.135-.012-.27-.004-.4-.008c-.408-.051-.819 0-1.229 0c-.118.004-.237-.004-.354.004c-.123.043-.25.004-.377.039c-.043.012-.084.016-.123-.008c-.029.012-.06.022-.09.039c-.103-.041-.192.018-.289.027a.64.64 0 0 0-.297.052c-.104.023-.234-.04-.314.082c-.068-.077-.131.021-.2.009c-.101.051-.215-.013-.315.039c-.135.094-.314.06-.449.166c-.072.026-.156 0-.221.06c-.047.043-.086.03-.125-.009c-.048-.056-.012-.086.02-.125a.12.12 0 0 1 .041-.061c.083-.047.175-.055.267-.066c.031-.063.075-.017.114-.013c.063-.104.173-.082.266-.102h.038c.128-.083.281-.083.421-.126c.079.003.171-.025.261-.029");
}

.yc73ospth {
  fill: var(--svg-color--31250a, #31250a);
  d: path("M15.09 36.678c-.123-.136-.269-.071-.408-.048c-.026-.088.02-.125.097-.143c.146.008.299-.063.428.06a2 2 0 0 1-.117.131");
}

.yd47qfbbm {
  fill: var(--svg-color--404040, #404040);
  d: path("m19.31 40.587l-.022.004h-.022a10 10 0 0 0-.055-.313c.018-.043.042-.062.083-.056c.016.121.04.248.016.365");
}

.ydh626t8v {
  fill: var(--svg-color--4e470e, #4e470e);
  d: path("M19.1 17.348c-.073.047-.143-.013-.211-.013l.002-.047c.07.008.152-.008.209.06");
}

.yeoubkbdr {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("m17.454 29.32l-.072-.06a.4.4 0 0 1-.07-.208c-.002-.102-.006-.207.007-.303c.043-.166.12-.146.215-.047c.131.143.146.308.106.492c-.047.068-.066.167-.186.126");
}

.yepywjjcq {
  fill: var(--svg-color--734646, #734646);
  d: path("M12.399 35.387c.057.117.025.243.051.36q-.014.063-.078.063c-.044-.083-.029-.171-.021-.257c.029-.049-.019-.12.048-.166");
}

.yeu9iibat {
  fill: var(--svg-color--2c1a06, #2c1a06);
  d: path("M22.636 39.43q-.002-.025-.002-.054c.101-.068.192-.068.287.008c-.095.012-.187.033-.285.046");
}

.yfwsisbek {
  fill: var(--svg-color--584d11, #584d11);
  d: path("M21.02 23.23c.168-.09.318.013.474.052c.021.012.024.02.021.03c-.008.013-.013.013-.021.013c-.161-.036-.327-.02-.474-.095");
}

.yhrl4sg7f {
  fill: var(--svg-color--e4e4e5, #e4e4e5);
  d: path("M21.55 31.14c-.162-.255-.125-.521-.043-.789l.131-.1c.065.027.082.095.104.154c.022.084.039.176.062.258a.5.5 0 0 1-.004.185c-.031.084-.016.168-.033.251a.14.14 0 0 1-.082.076c-.047.012-.1.012-.135-.035");
}

.yildnbbfx {
  fill: var(--svg-color--473e0d, #473e0d);
  d: path("M23.09 37.538c.059-.102-.064-.129-.082-.201a.14.14 0 0 1 .045-.047c.067-.029.137-.062.215-.062c.064.052.147.095.147.196c-.063.04-.153.021-.211.078a.3.3 0 0 0-.048.048l-.005-.005q-.03.04-.061-.007");
}

.yivinlbxq {
  fill: var(--svg-color--48100f, #48100f);
  d: path("M15.613 36.628c.073-.01.125.094.208.05c-.074.124-.105.112-.208-.05");
}

.yj3s_5vti {
  fill: var(--svg-color--4e3434, #4e3434);
  d: path("M22.847 33.762a.46.46 0 0 1 .097.231c-.134-.037-.116-.131-.097-.231");
}

.yjunbbufq {
  fill: var(--svg-color--323131, #323131);
  d: path("M15.09 19.14a1 1 0 0 0-.043.1c.027.051-.007.078-.042.108a.08.08 0 0 1-.065-.008v-.267q.073.037.15.067");
}

.yklofdewi {
  fill: var(--svg-color--444545, #444545);
  d: path("M17.632 37.653a2.2 2.2 0 0 0-.047.618a4 4 0 0 0-.197-.042c.11-.177.106-.396.201-.576q.023-.044.043 0");
}

.ykt835rth {
  fill: var(--svg-color--4d4310, #4d4310);
  d: path("M19.822 23.02q-.053.03-.104.051a12 12 0 0 1-.459-.016c-.002-.012 0-.02.002-.032q.032-.008.053-.02q.253.01.508.017");
}

.yl-nrexpi {
  fill: var(--svg-color--5a542f, #5a542f);
  d: path("M18.896 19.532c.172.075.115.186.051.295c-.02-.099.01-.201-.051-.295");
}

.ylk3t7bke {
  fill: var(--svg-color--151616, #151616);
  d: path("M18.423 28.997c.146-.047.105.103.156.153l-.055.099v.009c-.024.01-.047.015-.069-.004c-.048-.079-.073-.163-.032-.257");
}

.ylr8stb3v {
  fill: var(--svg-color--3b3b3b, #3b3b3b);
  d: path("m16.502 36.29l-.002-.334a.37.37 0 0 1 .154.16c-.095.021-.069.119-.106.174l-.021-.004z");
}

.ymkk1x20e {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("M15.339 18.786c.062.1.078.195.021.303c.009.031 0 .051-.021.07c-.07.039-.147.035-.226.031a.3.3 0 0 1-.171-.063c-.028-.026-.038-.063-.043-.103a.1.1 0 0 1-.02-.043c.02-.038.036-.077.059-.112c.045-.053.095-.1.142-.146z");
}

.ymq1fdb5o {
  fill: var(--svg-color--fde32b, #fde32b);
  d: path("M15.183 36.497c-.119-.021-.25.056-.352-.061a.2.2 0 0 0 .043-.046l.012.013c.08.029.164.008.244.02c.038.003.086.011.053.074");
}

.ymsz-hb3x {
  fill: var(--svg-color--1e2121, #1e2121);
  d: path("M20.453 40.29c-.095-.063-.144-.145-.093-.262c.042.083.106.158.093.262");
}

.ymt1nvjft {
  fill: var(--svg-color--2d2d2e, #2d2d2e);
  d: path("M14.302 29.1c-.076.076-.018.168-.043.251c-.058.043-.088 0-.121-.04a.05.05 0 0 1 .024-.059l-.002-.043c.069-.006-.009-.207.142-.109");
}

.yn6cscb_b {
  fill: var(--svg-color--ececec, #ececec);
  d: path("M20.71 17.854c.059-.071.059-.153.051-.231c.127-.186.271-.146.416-.037c.086.123.086.242-.02.351c-.102.067-.208.063-.318.041c-.059-.026-.111-.056-.129-.124");
}

.ynhlnj3-j {
  fill: var(--svg-color--4e2f2f, #4e2f2f);
  d: path("M21.962 29.417a.1.1 0 0 1 0-.043a.32.32 0 0 1 .248-.074c-.057.094-.152.109-.248.117");
}

.yonewwbsp {
  fill: var(--svg-color--e1c425, #e1c425);
  d: path("M23.569 21.03q.011.011.004.027c-.059.193-.137.023-.208.016c-.052.021-.103.037-.153.056c-.007-.009-.01-.024-.019-.032a.34.34 0 0 1 .237-.307c.097.052.073.174.139.24");
}

.yow9j8bfr {
  fill: var(--svg-color--6d4011, #6d4011);
  d: path("M16.231 18.438c.078-.076.156-.152.277-.093a.4.4 0 0 1-.277.093");
}

.yp8u6ccia {
  fill: var(--svg-color--503637, #503637);
  d: path("M25.08 28.12a.67.67 0 0 1-.101-.351c.126.093.129.218.101.351");
}

.ypbgq-bsa {
  fill: var(--svg-color--373030, #373030);
  d: path("m15.05 35.932l-.015-.083c.017-.124-.151-.029-.16-.128c.078-.015.158 0 .224-.062c.051-.017.071.021.088.062c.002.102-.015.19-.137.211");
}

.ypk88-e-g {
  fill: var(--svg-color--5b5b5b, #5b5b5b);
  d: path("M13.162 20.286q.033.171.062.342c-.112-.098-.164-.209-.062-.342");
}

.ypotnublz {
  fill: var(--svg-color--401413, #401413);
  d: path("M14.829 35.504c-.002.077-.135.108-.083.209c-.056.038-.08.004-.08-.044c.005-.102.063-.157.163-.165");
}

.yqmm87tod {
  fill: var(--svg-color--59310e, #59310e);
  d: path("M21.956 21.563a.4.4 0 0 0 .051-.075c.045-.056.055-.149.157-.133q.058.01.079.074c.004.023-.007.047-.021.07c-.102-.034-.164.103-.266.064");
}

.yqplbv6ji {
  fill: var(--svg-color--363737, #363737);
  d: path("M19.771 34.607c0 .355.002.708.004 1.068a1.84 1.84 0 0 1-.004-1.068");
}

.ys-8jkb9w {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("m14.315 30.62l-.063-.162q.005-.015.006-.023c.094-.113.114 0 .153.051c.041.055.047.135.103.182l.1.012c.042-.04.068-.008.092.021c.109.203-.097.396-.02.602c-.004.076-.033.146-.055.223a.4.4 0 0 1-.121.149c-.033.004-.041.022-.033.054q-.081.08-.168.159a.8.8 0 0 1-.113-.476c-.032-.082.023-.153.04-.232c.012-.063-.021-.135.012-.199c.075-.113-.046-.263.067-.361");
}

.ys9axjbtr {
  fill: var(--svg-color--49180d, #49180d);
  d: path("m20.04 23.319l.002-.027q.009-.053.052-.021c.063.005.133.005.201.013q.002.024.006.043z");
}

.ysk2c7qqs {
  fill: var(--svg-color--601413, #601413);
  d: path("M19.16 33.724q-.007 1.541-.011 3.092c0 .077 0 .161.107.17l-.006.045a.1.1 0 0 1-.041.025c-.076.012-.131-.008-.162-.079c-.074-1.049-.041-2.101-.02-3.147a.2.2 0 0 1 .043-.09c.029-.036.056-.04.09-.016");
}

.yt6020b4c {
  fill: var(--svg-color--331d0b, #331d0b);
  d: path("M12.89 37.758c.086.118.252-.031.33.1q.028.027.019.056q-.022.026-.052.011c-.104-.119-.284.026-.387-.111c.018-.04.047-.065.09-.056");
}

.yt8gp5bjj {
  fill: var(--svg-color--56290d, #56290d);
  d: path("M20.519 22.491q.024.005.05.004c-.093.074-.125.168-.114.287q-.164-.19.064-.291");
}

.ytcy64btm {
  fill: var(--svg-color--ededed, #ededed);
  d: path("M15.625 30.626q-.064.126-.122.257c-.074.136-.154.075-.229.008a.2.2 0 0 1-.041-.056c-.01-.023-.01-.043-.01-.063c.014-.073-.008-.132-.025-.194a.6.6 0 0 1 .006-.221c.04-.105.036-.236.139-.314q.03-.052.064-.104c.021.095-.023.231.154.212c.182.133-.011.319.064.475");
}

.yto2k4b1p {
  fill: var(--svg-color--5e2f2e, #5e2f2e);
  d: path("M20.921 40.454c-.031-.078-.066-.151-.099-.231q.026-.033.043 0c.068.065.128.133.056.231");
}

.yu6hz8fzo {
  fill: var(--svg-color--402709, #402709);
  d: path("M15.308 40.442c.054 0 .129-.104.156.035c-.104-.012-.104.098-.164.135c-.06-.06.018-.113.008-.17");
}

.yu8ac25vg {
  fill: var(--svg-color--4b400e, #4b400e);
  d: path("M22.528 39.28h-.09c.102-.102-.023-.299.148-.375c-.013.08.033.108.104.112l-.002-.004c-.091.072-.12.17-.16.267");
}

.yubxbbcmi {
  fill: var(--svg-color--bfbfbf, #bfbfbf);
  d: path("M23.21 29.2c-.107.032-.05.186-.158.219c-.027-.026-.074-.039-.057-.094c.021-.094.036-.203.159-.221c.058-.003.048.055.056.096");
}

.yuwlm6vrj {
  fill: var(--svg-color--161507, #161507);
  d: path("M24.21 38.493h.087l.057.057l-.067.063c-.064-.017-.099-.051-.077-.12");
}

.yvhmznb2w {
  fill: var(--svg-color--535454, #535454);
  d: path("M13.688 28.52h-.059c.008-.089.016-.185.084-.258c.061.094.022.182-.025.258");
}

.yw446n1ox {
  fill: var(--svg-color--dbdbd5, #dbdbd5);
  d: path("M14.79 18.864q.077-.053.145.004c.025.056-.002.095-.041.125c-.119.066-.26.047-.371.129c-.035.004-.069.013-.104.016q-.03.016-.057.04c-.013 0-.027.008-.041.012c-.046.028-.079.104-.155.052q-.059.001-.122-.004c.046-.103.134-.149.212-.207a.32.32 0 0 1 .213-.106c.07-.017.16.022.205-.067c.04-.003.078.002.116.006");
}

.ywm66jbyt {
  fill: var(--svg-color--bdbfc2, #bdbfc2);
  d: path("m15.625 18.677l-.059-.066q.052-.11.106-.217l.143.012c-.039.09-.078.174-.117.26q-.03.031-.073.011");
}

.yxccbqbih {
  fill: var(--svg-color--4a5353, #4a5353);
  d: path("M25.401 30.3c.013.004.031.013.047.017l-.01.244c-.052-.088-.048-.171-.037-.261");
}

.yxk73qt4x {
  fill: var(--svg-color--2d2e2e, #2d2e2e);
  d: path("M16.556 25.11c-.155-.005-.317-.005-.476-.009q-.025-.018-.017-.026q.01-.018.017-.017l-.004-.005a.9.9 0 0 1 .425 0c.02.018.035.037.055.057");
}

.yxm4qwn5n {
  fill: var(--svg-color--191919, #191919);
  d: path("m17.962 37.921l.051.054c0 .179.004.351.045.521q-.026.025-.049-.004c-.066-.072-.051-.166-.06-.248c-.017-.028-.052-.037-.058-.07c.06-.075.064-.167.071-.253");
}

.yxv253byw {
  fill: var(--svg-color--481007, #481007);
  d: path("M21.998 40.43c.003-.071.07-.149-.032-.205c-.082.019-.172.078-.221-.051c.076-.009.167.039.217-.058a1 1 0 0 1 .141.058q-.017.139-.039.286z");
}

.yxwmk8b0j {
  fill: var(--svg-color--292a2a, #292a2a);
  d: path("M21.476 36.18c-.012-.016-.026-.03-.041-.057c.045-.156.033-.33.111-.479c.08.194.02.367-.07.536");
}

.yxxn1u1gn {
  fill: var(--svg-color--483636, #483636);
  d: path("M22.08 34.497c-.091-.031-.181-.059-.269-.096c.099.01.227-.072.269.096");
}

.yy0rmybvh {
  fill: var(--svg-color--626263, #626263);
  d: path("M20.14 31.882c.051-.128-.102-.307.109-.385q-.005.146-.012.281c-.033.037.003.137-.097.104");
}

.yy2iofbig {
  fill: var(--svg-color--535353, #535353);
  d: path("M17.8 39.905c.016-.051.057-.051.096-.051c.004.141-.061.253-.094.383c-.146-.109.043-.22-.002-.332");
}

.yybxlub6g {
  fill: var(--svg-color--534c1d, #534c1d);
  d: path("m19.21 19.603l.058.055c.013.086-.031.186.054.256l-.062.004c-.104-.091-.031-.21-.05-.315");
}

.yydke_nlc {
  fill: var(--svg-color--f1f2f3, #f1f2f3);
  d: path("M19.317 19.588c-.02.022-.035.047-.053.069c-.037 0-.039-.035-.059-.055q-.001-.104.004-.208c.018 0 .033-.004.055-.004l.033.013c.011.063.013.12.02.185");
}

.yykj79bie {
  fill: var(--svg-color--380909, #380909);
  d: path("m12.784 26.64l-.039-.059c.008-.098 0-.201.059-.291l.006.197z");
}

.yyx2r7blk {
  fill: var(--svg-color--4a4b4b, #4a4b4b);
  d: path("M17.992 38.803q.03-.001.06.004c.002.048.002.101.002.146q-.018.014-.041.021c-.033-.004-.035-.032-.051-.058c-.011-.042-.009-.081.03-.113");
}

.z_n0bibyq {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M19.517 21.426c.039-.062.113-.103.107-.188c.116-.142.121-.283 0-.425c-.021-.112-.083-.192-.205-.22c-.144-.161-.31-.029-.465-.029c-.104-.223.104-.31.196-.451c.055-.048.116-.084.179-.123c.018-.012.034-.026.057-.039c.104-.09.043-.188.021-.287c-.015-.109-.047-.217-.065-.321c-.007-.274-.002-.55-.004-.825c0-.152.051-.271.205-.322c.075-.023.151-.023.229-.027c.15-.004.302-.012.453.012c.187.066.392.012.58.091c.096.011.187.056.279.071c.213.083.381.216.467.439c.02.109.018.219.006.33c-.021.09-.049.18-.051.271c-.08.278-.252.491-.437.708c-.095.08-.068.156-.002.232a.4.4 0 0 1 .071.133c.104.308-.17.23-.304.304a.9.9 0 0 0-.245.196c-.082.084-.093.185-.031.287c.069.138.246.164.308.307c-.035.027-.071.059-.104.087c-.113.104-.203-.021-.297-.043l-.127-.149c-.055-.08-.051-.177-.102-.256c-.023-.047 0-.09.015-.137a.3.3 0 0 0 .026-.2q-.027-.102-.125-.123c-.063-.008-.129-.008-.184.033c-.07.05-.074.118-.047.192c.014.039.03.082.038.127a.12.12 0 0 1-.008.067c-.056.075-.028.188-.118.24c-.027.071-.074.11-.15.106c-.079.026-.166.085-.166-.068m-1.783.118c-.117-.086-.271-.15-.25-.338l-.03-.063a.25.25 0 0 1 .033-.137c.035-.067.049-.138-.012-.205l-.049-.042c-.119-.061-.215-.043-.276.082a.5.5 0 0 0 .019.263c.018.043.006.091.004.138c.004.017 0 .028-.011.043c-.047.099-.096.201-.194.268l.002-.008c-.097.142-.242.104-.375.104c-.033-.023-.064-.051-.096-.074c-.025-.162.112-.104.18-.139a.22.22 0 0 0 .174-.125q.015-.03.025-.059c.033-.075.018-.146-.031-.213a.3.3 0 0 1-.018-.059q-.014-.148-.148-.189a.2.2 0 0 1-.062-.022c-.081-.06-.181-.041-.269-.063c-.084-.031-.116-.099-.114-.184c.014-.09.069-.166.116-.236c.101-.095.058-.174-.039-.236c-.105-.133-.225-.254-.282-.42a2 2 0 0 0-.121-.271a.4.4 0 0 1-.04-.109a1.4 1.4 0 0 1-.008-.404a1 1 0 0 1 .079-.229a1 1 0 0 1 .271-.211c.092-.037.186-.061.271-.115a.6.6 0 0 1 .291-.082a.9.9 0 0 0 .436-.023c.148-.02.297-.012.448-.012c.366.035.417.091.418.443c.002.221.006.44-.001.657a6 6 0 0 1-.084.407c-.027.113-.014.209.082.287c.072.063.158.113.227.189a.5.5 0 0 1 .129.188c.01.083.084.184-.065.212c-.146-.06-.287-.036-.433-.005a3 3 0 0 1-.09.15c-.086.073-.109.181-.143.278c.043.161.059.337.188.464c.013.135-.092.084-.152.1m-2.967-.26q-.017 0-.037-.016c-.096-.113-.225-.07-.346-.07c-.06-.041-.065-.096-.049-.16c.043-.084.096-.17 0-.252c-.105-.157-.244-.283-.359-.424a2 2 0 0 1-.084-.162a1.2 1.2 0 0 1-.08-.235c-.014-.078.011-.146.033-.216c.041-.086.088-.168.11-.264a.23.23 0 0 1 .122-.13c.094-.022.169-.065.205-.168a.3.3 0 0 1 .053-.051a.4.4 0 0 1 .104-.047a.5.5 0 0 1 .117-.019c.069 0 .133.008.191.053a.3.3 0 0 1 .045.162c-.047.217-.076.434.024.646c.026.095.05.185.097.271c.025.056.063.109.086.168a.2.2 0 0 1 .004.063c-.039.032.02.037.02.056a.6.6 0 0 1 .066.103a.3.3 0 0 0 .079.091c.046.042.103.074.157.105c.079.043.118.104.079.199a.2.2 0 0 1-.029.061c-.041.094-.133.09-.207.117c-.071.023-.149.033-.213.084c-.054.043-.108.086-.188.035m7.945-.054l.008-.004c-.125.104-.224.033-.322-.047c-.055-.003-.106-.003-.161-.016a.4.4 0 0 1-.238-.125a.3.3 0 0 1-.063-.118a.13.13 0 0 1 .018-.07c.016-.021.035-.03.055-.041c.078-.036.16-.062.213-.137a.7.7 0 0 1 .104-.11a.3.3 0 0 0 .073-.102c.021-.047.037-.104.068-.146a.37.37 0 0 0 .107-.246a1 1 0 0 1 .025-.106q.022-.072.047-.142a1 1 0 0 0-.004-.482a.25.25 0 0 1 .02-.193c.072-.066.148-.023.221-.011c.084.034.159.075.235.118c.067.055.151.078.233.102a.4.4 0 0 1 .236.35q.01.208-.029.42a.6.6 0 0 1-.113.228c-.137.126-.243.284-.361.424c-.059.063-.083.13-.033.208c.037.043.084.086.076.148c-.013.04-.031.063-.076.052h-.038c-.1.004-.203-.006-.301.046");
}

.z_u1skmvg {
  fill: var(--svg-color--fcda2a, #fcda2a);
  d: path("M14.827 36.864c-.129.09-.271.043-.413.043l.062-.092a.3.3 0 0 1 .115-.056c.088.016.209-.053.236.105");
}

.z-xe7rbse {
  fill: var(--svg-color--3c3c3c, #3c3c3c);
  d: path("M17.792 28.13c.104-.048.037-.183.111-.245c.046.063.031.156.107.204q.015.023.015.041q-.006.023-.007.021c-.071-.029-.096.019-.125.069c-.037 0-.06-.017-.059-.062c-.014-.014-.027-.023-.042-.037z");
}

.z1v3adbze {
  fill: var(--svg-color--403f3f, #403f3f);
  d: path("M21.964 31.673q.05.106.104.229c-.038.004-.084-.004-.104.045c-.113-.074-.02-.187-.048-.271q.023-.044.048-.003");
}

.z2rbrunzh {
  fill: var(--svg-color--67140e, #67140e);
  d: path("M15.945 19.288c-.129-.143-.093-.307-.069-.467q.02-.04.047-.005q.013.23.022.472");
}

.z31kh1-xf {
  fill: var(--svg-color--4c4f4f, #4c4f4f);
  d: path("M25.03 30.2c-.031.127.023.246.049.367c-.107.051-.08-.109-.154-.109c-.039-.043-.021-.098-.022-.15c.009-.071.033-.13.127-.108");
}

.z3euofbwm {
  fill: var(--svg-color--493234, #493234);
  d: path("M20.09 25.378v-.043c.076-.06.16-.094.258-.063a.4.4 0 0 1-.258.106");
}

.z3v69m53v {
  fill: var(--svg-color--3a3535, #3a3535);
  d: path("M14.64 28.676c-.188-.192-.17-.444-.217-.685c.019-.02.034-.013.051.012q.08.338.166.673");
}

.z48m29r-p {
  fill: var(--svg-color--907d18, #907d18);
  d: path("M19.822 23.02c.106-.011.216-.025.312.036c-.135.103-.275.079-.416.017c.018-.05.072-.021.104-.053");
}

.z4ci9ke2v {
  fill: var(--svg-color--313232, #313232);
  d: path("M21.902 31.409h-.05c-.043-.047-.035-.103-.035-.162l.111-.039q-.014.096-.026.201");
}

.z5a36t2wv {
  fill: var(--svg-color--dbdbdb, #dbdbdb);
  d: path("M19.781 28.887c-.038.123-.077.251-.116.37c-.044.027-.08.07-.14.037c-.026-.092-.06-.187-.013-.285a.1.1 0 0 1 .004-.047c.004-.063-.004-.122.02-.174a.4.4 0 0 1 .135-.113c.178.001.064.15.11.212");
}

.z6m09956l {
  fill: var(--svg-color--6a330f, #6a330f);
  d: path("m14.163 21.18l.047-.057c.025-.043.042-.098.098-.121q.016.001.029-.004q.015.012.031.016c0 .064-.027.132.055.165q.024.018.012.036q-.01.013-.02.015c-.098.067-.197.102-.252-.05");
}

.z6yj58bvm {
  fill: var(--svg-color--462a2a, #462a2a);
  d: path("M21.652 33.382c.06.091.108.188.104.304c-.083-.085-.178-.164-.104-.304");
}

.z7826yb8t {
  fill: var(--svg-color--2b2c2c, #2b2c2c);
  d: path("M18.421 37.08c-.078-.012-.104.063-.156.101q-.02.03-.041.004c.059-.138-.082-.108-.125-.157c.078-.004.152-.008.23-.015q.05.009.092.019c.012.015.018.023.012.033q-.003.014-.012.015");
}

.z7p_f272z {
  fill: var(--svg-color--383838, #383838);
  d: path("M21.382 32.884c.065.033.088.102.098.166c-.063.197 0 .402-.031.609c-.018 0-.031.008-.045.015l-.021-.015a.89.89 0 0 1-.001-.775");
}

.z85depied {
  fill: var(--svg-color--260c0c, #260c0c);
  d: path("M15.03 35.14c.058.075.015.123-.041.165c-.077-.116-.231-.021-.317-.116c.038-.034.079-.03.12-.008c.08-.017.166.018.238-.041");
}

.z8hebib1m {
  fill: var(--svg-color--434442, #434442);
  d: path("m24.815 30.921l.008.07c-.154.014-.18-.102-.208-.211h.041c.064.032.073.129.159.141");
}

.z8m788baf {
  fill: var(--svg-color--676767, #676767);
  d: path("M23.15 31.05c-.071-.143-.04-.286-.036-.432l.091-.047c-.043.148.047.282.063.424c-.051 0-.079.035-.118.055");
}

.z936i5nlu {
  fill: var(--svg-color--150b04, #150b04);
  d: path("M13.948 37.542c-.197-.022-.393.177-.596.01c.223.023.422-.066.631-.118a.1.1 0 0 1 .004.062a.1.1 0 0 1-.039.046");
}

.z98bvt-ao {
  fill: var(--svg-color--675d13, #675d13);
  d: path("M21.3 20.653h.021c.006.041.008.082-.03.104c-.038.031-.076.027-.113.005v.004c.006-.06.008-.112.01-.178c.038.016.028.128.112.065");
}

.z9h4ubn6g {
  fill: var(--svg-color--262a2a, #262a2a);
  d: path("M12.8 28.573c-.022.18-.035.361-.137.582c-.018-.24.038-.408.094-.578c.012-.028.027-.023.043-.004");
}

.z9j66i3ie {
  fill: var(--svg-color--222, #222);
  d: path("M24.26 27.421c-.016-.071-.031-.133-.045-.204c.077.129.313.142.252.354c.025.047-.002.066-.041.079a.15.15 0 0 1-.072-.079c-.027-.051-.072-.094-.094-.15");
}

.z9nq5ab5i {
  fill: var(--svg-color--7b702e, #7b702e);
  d: path("M23.1 19.301q0-.034.004-.071c.104.014.201.028.209.157q-.141.037-.213-.086");
}

.za2m7ulsv {
  fill: var(--svg-color--d4d5d5, #d4d5d5);
  d: path("M14.899 19.02q.02.025.039.053a.28.28 0 0 1 .053.211c-.014.069-.051.148-.014.228q.027.06.035.122c-.021.051.004.1.004.152c-.021.115.09.225.02.338l-.055.066l-.053-.013c-.033-.094-.068-.181-.104-.271q0-.048.003-.099a1.8 1.8 0 0 1-.003-.526q.016-.105.028-.203c.015-.019.03-.033.047-.058");
}

.za8r20b7g {
  fill: var(--svg-color--50460f, #50460f);
  d: path("M14.321 37.601c-.074.111-.15.217-.322.088c.094-.058.195-.021.256-.092c.022-.022.047-.018.066.004");
}

.zajvxwo3l {
  fill: var(--svg-color--fbfcfc, #fbfcfc);
  d: path("M20.09 18.09q-.127.001-.248.008l-.009-.062q.125-.013.255-.021h.201q.04-.024.072.013q.011.047-.029.07a.6.6 0 0 1-.242-.008");
}

.zaqd45bfy {
  fill: var(--svg-color--e9cc27, #e9cc27);
  d: path("m24.558 38.39l.004-.046c.008-.004.015-.018.021-.029a.17.17 0 0 1 .137-.004c.056.029.062.091.104.131v-.004c.07.051.105.127.057.199c-.045.063-.113.07-.16-.008c-.018-.016-.031-.022-.045-.038c-.032-.073-.193-.067-.118-.201");
}

.zavxgzb3e {
  fill: var(--svg-color--4f4f4f, #4f4f4f);
  d: path("M13.89 30.458c-.014.125-.023.248-.041.375c-.03.027-.061.055-.108.055c-.002-.152.065-.283.101-.424q.02-.008.048-.006");
}

.zb1sv5vhf {
  fill: var(--svg-color--f3d228, #f3d228);
  d: path("M18.206 17.13c.014-.094.085-.139.164-.168c.045-.063.092-.118.18-.076c.051.125.03.257.016.385c-.055.098-.164.08-.248.114a.3.3 0 0 1-.146.04c-.051-.02-.07-.067-.076-.113a.6.6 0 0 1 .11-.182");
}

.zb6c7tbil {
  fill: var(--svg-color--232525, #232525);
  d: path("m15.974 34.827l-.098-.013c-.072-.101-.174-.039-.263-.056c-.021-.016-.024-.027-.021-.039q.01-.015.018-.016c.113-.074.24-.037.355-.054c.005.064.007.118.009.178");
}

.zbkae1bei {
  fill: var(--svg-color--fdfdfd, #fdfdfd);
  d: path("M18.476 37.495a.1.1 0 0 0 0-.033c-.006-.092.035-.168.078-.241c.016-.05.033-.099.084-.123c.114-.042.188.032.27.104a.24.24 0 0 1 .074.123c.009.116.023.238.063.354q.022.086.02.182c-.018.172.035.344.009.518c-.093.063-.101.187-.172.259l-.013.129c-.098.125-.193.233-.307.019a6 6 0 0 1-.156-.271c-.019-.105-.068-.206-.052-.314c.002-.125-.003-.25.007-.377c.03-.112-.001-.241.095-.329");
}

.zcn6evgfg {
  fill: var(--svg-color--f7f7f6, #f7f7f6);
  d: path("M15.513 19.708a.31.31 0 0 1 .035.317c-.052.044-.15.048-.142.153c-.093.027-.146-.043-.211-.09a.6.6 0 0 1-.063-.271c-.004-.062.023-.105.071-.142c.109-.049.22-.128.31.033");
}

.zcq1isncp {
  fill: var(--svg-color--6e270e, #6e270e);
  d: path("m20.19 20.719l-.002-.058c.084.02.123.078.146.151q-.023.032-.051 0c-.032-.03-.059-.063-.093-.093");
}

.zcq2jab8k {
  fill: var(--svg-color--491f1e, #491f1e);
  d: path("M19.409 26.428c0 .047.006.094-.049.123c-.088-.097-.266-.181-.012-.287c.006.017.008.03.008.05c.03.031.09.054.053.114");
}

.zdjs1t3kq {
  fill: var(--svg-color--d4d1d1, #d4d1d1);
  d: path("M18.364 28.28c-.01-.082-.154-.203.063-.228c-.004.103.043.185.1.263l.097.221a.4.4 0 0 1-.097.035c-.07-.035-.162-.035-.192-.13c-.022-.059.014-.11.029-.161");
}

.zdm6bfbzv {
  fill: var(--svg-color--edcd28, #edcd28);
  d: path("M23.15 37.508c.041-.188.158-.118.267-.082c-.034.184-.171.065-.267.082");
}

.zdojf3btk {
  fill: var(--svg-color--776814, #776814);
  d: path("M22.269 38.34c0 .042-.01.078-.047.092c-.051.008-.051-.036-.047-.068c0-.024.012-.068.055-.063c.015-.002.029.025.039.039");
}

.zdt0umvqx {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M13.948 29.14c.068.017.098.06.111.122a.36.36 0 0 1 .007.396c-.103.112.017.278-.079.4c-.051.102-.09.208-.18.287c-.115.066-.178.008-.221-.092c-.074-.207-.053-.42 0-.633l-.006-.059c0-.113.077-.191.115-.291l.074-.268c.095 0 .052.189.179.138");
}

.zf37wv0qn {
  fill: var(--svg-color--323433, #323433);
  d: path("M24.712 35.827c.018-.021.033-.045.051-.061q.014.17.033.334c-.098-.079-.076-.178-.084-.273");
}

.zffekz1xy {
  fill: var(--svg-color--141008, #141008);
  d: path("M15.31 40.18c-.088-.091-.176-.07-.269-.005q-.051.044-.092-.004h-.021c-.014-.039-.025-.082-.037-.117a.2.2 0 0 1 .07-.033c.116-.029.236-.016.352-.021c.051-.004.104-.021.154.018c.017.029.023.07-.013.105l-.002.002c-.031.057-.064.108-.142.055");
}

.zfubapbfb {
  fill: var(--svg-color--756514, #756514);
  d: path("M17.698 23.23c-.003.017-.003.028-.003.043q-.187.001-.377-.004c.122-.064.252-.043.38-.039");
}

.zg7_6dpzu {
  fill: var(--svg-color--5a4f11, #5a4f11);
  d: path("M17.75 21.552c.103 0 .202-.008.306-.008c.021 0 .045.005.063.008a.34.34 0 0 1-.369 0");
}

.zgl22ib6m {
  fill: var(--svg-color--2a2d2d, #2a2d2d);
  d: path("m17.742 40.44l-.058.364c-.047.004-.076-.004-.051-.063c.008-.105.012-.209.063-.302q.023-.042.046.001");
}

.zhv5rt2ak {
  fill: var(--svg-color--110c0c, #110c0c);
  d: path("M20.466 39.475c.07.005.137.005.209.009q.043.005.028.053c-.125 0-.187.054-.151.185l-.146-.185c-.01-.058.007-.077.06-.062");
}

.zisoeyluo {
  fill: var(--svg-color--0b5192, #0b5192);
  d: path("M18.54 22.396a.4.4 0 0 1 .299.027c.11-.04.188.011.209.114c.03.138-.103.117-.18.158c-.148.127-.294-.01-.441-.006c-.155-.171.049-.208.113-.293");
}

.zjn33cc5z {
  fill: var(--svg-color--252525, #252525);
  d: path("M17.623 27.27c.052-.026.076.021.11.04c.058-.031.099 0 .133.04c.01.022.018.052.018.076a.2.2 0 0 1-.027.069c-.195.183-.055.387-.029.586c0 .023-.014.047-.023.067c-.055.036-.1.013-.145-.016a.14.14 0 0 1-.066-.091c-.027-.133-.023-.266-.039-.393q.003-.088.086-.121c-.002-.086-.008-.173-.01-.256h-.009v-.003h.001z");
}

.zklyx7hfj {
  fill: var(--svg-color--0c0d0d, #0c0d0d);
  d: path("M13.731 31.563c-.031 0-.063.004-.094.004l.06-.158h.034z");
}

.zkoq3hixe {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M16.488 36.528c-.103.155-.168-.008-.25-.022c-.091-.125-.181-.245-.271-.374a.6.6 0 0 1-.09-.23c-.002-.086-.017-.176.051-.246v-.039c-.035-.063-.004-.119.004-.183a.22.22 0 0 1 .142-.129q.113-.015.153.095c.021.022.039.053.062.074c-.005.102.069.165.101.252c-.017.102.115.137.113.232a.33.33 0 0 1 .002.334z");
}

.zkpmg2b5u {
  fill: var(--svg-color--473737, #473737);
  d: path("M16.941 25.17c-.13.079-.229-.011-.337-.056a.45.45 0 0 1 .337.056");
}

.zku6q0mev {
  fill: var(--svg-color--242424, #242424);
  d: path("M14.634 31.31h.053a.37.37 0 0 1-.063.209h-.049q.032-.108.059-.209");
}

.zkv5td-0l {
  fill: var(--svg-color--490d08, #490d08);
  d: path("m14.925 38.536l-.037.271q-.037.029-.068-.008c.027-.095-.007-.203.105-.263");
}

.zky7uibwb {
  fill: var(--svg-color--381716, #381716);
  d: path("M20.698 35.86c.064-.082.09-.162.003-.246c.021-.031.04-.031.062-.009c.091.12.119.218-.065.255");
}

.zl5ll9b3z {
  fill: var(--svg-color--6b5e12, #6b5e12);
  d: path("m20.09 23.271l-.052.021a11 11 0 0 0-.319-.021c0-.016 0-.026-.002-.043c.125-.003.252-.02.373.043");
}

.zlg-4toem {
  fill: var(--svg-color--463d0e, #463d0e);
  d: path("M22.17 38.751h-.046c-.001-.067-.028-.146.058-.207c.064.078.01.145-.012.207");
}

.zmg1ltb4l {
  fill: var(--svg-color--7e7f84, #7e7f84);
  d: path("M21.847 18.829c.004.098.004.201.008.297c-.014.004-.023.009-.041.012q0-.162-.004-.323q.018.009.037.014");
}

.zmghlac7w {
  fill: var(--svg-color--454646, #454646);
  d: path("M19.399 39.692c.025.051.104.061.109.129c-.133.033-.047.195-.148.248l-.021.004l-.02-.004z");
}

.zmptzq46n {
  fill: var(--svg-color--0d0e0e, #0d0e0e);
  d: path("m15.677 30.874l-.113.115c-.021-.01-.035-.029-.049-.043a.2.2 0 0 1-.027-.099c.02-.09.042-.181.139-.22c.014.005.032 0 .047-.004c-.001.083.001.174.003.251");
}

.zmqny_boj {
  fill: var(--svg-color--4a2e22, #4a2e22);
  d: path("M21.8 36.632c-.041-.143.111-.217.115-.344c.039-.013.063.01.09.028c.039.056.082.105.09.173c-.002.026-.015.043-.031.06c-.126-.086-.191.01-.264.083");
}

.zn0kc5kox {
  fill: var(--svg-color--391d0b, #391d0b);
  d: path("M15.617 26.577q.001.03-.004.059c-.04.003-.084 0-.106-.039q-.041-.061.002-.114q.103-.007.205-.008c.045-.022.059-.004.055.036c-.049.029-.123-.01-.152.066");
}

.znocqxb_m {
  fill: var(--svg-color--3a3838, #3a3838);
  d: path("M16.958 35.03a.6.6 0 0 0 .053.289c.018.014.023.021.018.031c-.004.009-.014.009-.018.009c-.121-.093-.191-.196-.053-.329");
}

.zo32_ebbr {
  fill: var(--svg-color--464124, #464124);
  d: path("M15.769 20.432q.002-.03 0-.052c.018-.094-.075-.172-.03-.274a.1.1 0 0 1 .052-.051c.023 0 .049.012.071.024a.2.2 0 0 1 .063.102c.021.09.026.182-.029.271c-.049.062-.084-.008-.127-.02");
}

.zp_zuebhb {
  fill: var(--svg-color--424242, #424242);
  d: path("M13.739 34.737c.066-.143-.064-.361.156-.443c-.066.142.016.339-.156.443");
}

.zp3pucylr {
  fill: var(--svg-color--383939, #383939);
  d: path("m17.636 35.713l.012-1.107c.089.367.111.733-.012 1.107");
}

.zq3f-xbmz {
  fill: var(--svg-color--543b3b, #543b3b);
  d: path("M13.856 35.29q.018.001.035-.004c-.051.104-.031.229-.109.318q-.025.024-.042 0c.019-.109.032-.228.116-.314");
}

.zqa6ttury {
  fill: var(--svg-color--4c1707, #4c1707);
  d: path("M19.308 20.02a.1.1 0 0 0 .047.005l-.153.129c-.071-.11-.16-.104-.254-.052c-.03-.04-.028-.079.015-.114c.118-.062.234-.039.345.032");
}

.zs0oeeb0e {
  fill: var(--svg-color--302522, #302522);
  d: path("M19.822 40.963c-.013.144.045.274.083.409c-.12.033-.049.147-.089.218q-.023.028-.044-.005c-.002-.209-.004-.413-.004-.622q.024-.033.054 0");
}

.zso23li_q {
  fill: var(--svg-color--2e270b, #2e270b);
  d: path("M21.541 21.19c.103-.008.216-.04.269.099h-.269c.005-.016.002-.031 0-.051c-.021-.012-.022-.023-.019-.031q.014-.019.019-.017");
}

.zt6c4w44e {
  fill: var(--svg-color--e3c927, #e3c927);
  d: path("M22.649 37.38c-.155-.012-.066.213-.204.217c-.089 0-.177-.041-.267-.012c-.039-.012-.074-.035-.08-.079c.031-.056.065-.115.142-.115q.065-.004.129-.003c.093-.039.183-.151.28-.008");
}

.zte4e24tr {
  fill: var(--svg-color--1a1616, #1a1616);
  d: path("M12.02 30.14a.63.63 0 0 1-.034.318c-.072-.041-.037-.104-.024-.157c.004-.062-.011-.125.058-.161");
}

.zti36gbgw {
  fill: var(--svg-color--232424, #232424);
  d: path("M19.1 28.05h.051q.051-.027.104-.052v.056c.021.09-.031.142-.104.172c-.043-.004-.076-.017-.054-.073z");
}

.ztxzerbtl {
  fill: var(--svg-color--8c8046, #8c8046);
  d: path("M15.04 20.13c-.023-.122-.146-.229-.05-.365a1 1 0 0 0 .133.021c.021.012.04.022.056.039a.7.7 0 0 1 .059.231c0 .028-.01.047-.018.067c-.035.039-.084.035-.127.041q-.027-.016-.053-.034");
}

.zuctt0bze {
  fill: var(--svg-color--2d2f2f, #2d2f2f);
  d: path("M19.89 35.448c-.006-.193-.013-.379-.01-.569c.002-.064-.029-.173.104-.159c.009.016.015.025.021.043c-.007.225.033.447-.043.667q-.031.038-.072.018");
}

.zuxdprhmw {
  fill: var(--svg-color--2a2b2b, #2a2b2b);
  d: path("M23.774 28.52h-.044c-.059-.065-.07-.147-.036-.267c.048.1.091.178.08.267");
}

.zvlz_lb6z {
  fill: var(--svg-color--232120, #232120);
  d: path("M20.296 27.421c-.004.035-.004.074-.008.109c-.167-.082-.057-.209-.049-.322c.021 0 .041-.008.057-.008z");
}

.zw8cbybna {
  fill: var(--svg-color--774612, #774612);
  d: path("M16.968 21.552c.064-.09.094-.203.194-.268c-.02.121-.028.256-.194.268");
}

.zwmk4bcml {
  fill: var(--svg-color--201c07, #201c07);
  d: path("M15.517 20.604c.045-.012.082 0 .097.047c.042.138.042.263-.154.263c0-.03 0-.066-.002-.099c.052-.054-.002-.129.034-.188c.007-.007.015-.011.025-.023");
}

.zxboezjsz {
  fill: var(--svg-color--202423, #202423);
  d: path("M18.478 29.838c.009-.074.035-.138.103-.177c.08.035.029.196.161.177q.065-.015.045.047c-.132.161-.192-.138-.309-.047");
}

.zy_h7xulz {
  fill: var(--svg-color--414141, #414141);
  d: path("m17.904 28.827l.094.274c-.019.052.019.119-.039.161c-.019.021-.04.031-.06.043l-.028-.027c-.024-.156-.142-.308.033-.451");
}

.zy1jd49dl {
  fill: var(--svg-color--232929, #232929);
  d: path("M25.08 30.659a.46.46 0 0 1 .09.275q-.016.04-.039.004c-.076-.088-.146-.167-.051-.279");
}

.zyxnovb-p {
  fill: var(--svg-color--6d0606, #6d0606);
  d: path("M16.5 25.06h-.425a.44.44 0 0 1 .425 0");
}

.zzr7_1bvf {
  fill: var(--svg-color--624311, #624311);
  d: path("M15.562 21.771c.123.003.25.075.371-.016q.03-.037.054.004q-.21.225-.425.012");
}

</style>
