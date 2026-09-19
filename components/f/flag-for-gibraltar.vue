<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r9y_yosgd"/><path class="ftmfe9vgc"/><g class="d2kvgvbvc"><path class="a6zjm6b1d"/><path class="wo8o4lcba"/><path class="e2ry6bc3z"/><path class="qfjcmuwdg"/><path class="qa_bt6g-l"/><path class="mq_jmtbfr"/><path class="tckys5ykf"/><path class="u3gtt3bhe"/><path class="qvbop4bmi"/><path class="e88um79-k"/><path class="a6vb95p1q"/><path class="rmn-dyo-k"/><path class="uk35dwb6e"/><path class="fbaw67b_p"/><path class="te29gwklq"/><path class="yhxg62n4y"/><path class="gam5k7brk"/><path class="t7ul9dwso"/><path class="dj2jk3l7g"/><path class="j08v0mbfg"/><path class="zixegbclb"/><path class="hriyr6bzv"/><path class="arqprfbio"/><path class="ujpjyac4z"/><path class="rx7wq1bxj"/><path class="b9hzi5b-v"/><path class="w-s452bsw"/><path class="h0bj2gbwk"/><path class="ujr97ccby"/><path class="k35_wbc8a"/><path class="wse-it1py"/><path class="n4bjv2b8v"/><path class="x9vgv7yao"/><path class="tq7tv-lvt"/><path class="zivd2-eyi"/><path class="sger-rbvr"/><path class="vhsqu8b2m"/><path class="vhwpb8-ey"/><path class="b3rat6bqn"/><path class="ogx_xgu7y"/><path class="oreaxs6jp"/><path class="ba5c54bqt"/><path class="jrdswybwx"/><path class="orso23b7k"/><path class="phvu3vbol"/><path class="wmfji_bpl"/><path class="on_cujbwq"/><path class="u_it44t3n"/><path class="j23nzubtb"/><path class="t_0x0rbio"/><path class="byppzybgq"/><path class="zi0nk2bmt"/><path class="csp4fqbss"/><path class="epmcdpbfx"/><path class="suakruc1f"/><path class="f6m8e8yet"/><path class="k9d8hobph"/><path class="mq1o2ob_c"/><path class="bpj2vpbpm"/><path class="tesv_cbqg"/><path class="dqvltbb_f"/><path class="noduqqb9g"/><path class="epeycyxme"/><path class="xj60ps-1g"/><path class="x5nzi2bws"/><path class="if943jozz"/><path class="w52a-9b1v"/><path class="qu0v4ea2u"/><path class="o9nj2qb1a"/><path class="louwefush"/><path class="goyu39xul"/><path class="dwaxxvirj"/><path class="c7oeo4bdl"/><path class="g75p31gwd"/><path class="vjf4klw0n"/><path class="r_u44ab8l"/><path class="ci7z0ib2b"/><path class="gz7gz-uhc"/><path class="wc7jfvn5k"/><path class="vu9a_-wpy"/><path class="ujgid--jj"/><path class="nr4orw_nu"/><path class="x--lnxb5y"/><path class="i1ciwlqff"/><path class="o8y3omhxd"/><path class="y2zy0kecl"/><path class="qpr39it-z"/><path class="tewtk3b0w"/><path class="t58ta-o8g"/><path class="ko1gguciw"/><path class="mub8zcujq"/><path class="ktevhqr1i"/><path class="ds0c7h_cg"/><path class="d9ae4r7_t"/><path class="iyq6l_bih"/><path class="zgisxdhit"/><path class="zbo16t5_r"/><path class="gepsj4b1n"/><path class="ihqmntbmn"/><path class="skveb8b-p"/><path class="bo3d4hbwo"/><path class="qi259qbwc"/><path class="iqjxv8b5o"/><path class="gvavrsbsr"/><path class="ych38ym4o"/><path class="q1igj_bym"/><path class="fuzj1gb3j"/><path class="vwx169bvd"/><path class="o8ls_s02r"/><path class="wvzxrpbgy"/><path class="t4btdzs-g"/><path class="gbw8eo-8v"/><path class="kt0jcdbor"/><path class="hw8l-sw0s"/><path class="yeupdjbzk"/><path class="akd784brj"/><path class="h-lfwvb9e"/><path class="hswaiuy7l"/><path class="yzfmk1b9v"/><path class="q5hngu-zk"/><path class="x_v9mmb7j"/><path class="gaw1tvxvj"/><path class="nitkigb_s"/><path class="e5a75ccmn"/><path class="wx39vnh-c"/><path class="ahvuvmiqe"/><path class="tfq59lbhy"/><path class="u_if08bng"/><path class="fzd9mj6tu"/><path class="w3ztqxbhc"/><path class="acj9-9bnv"/><path class="rsq44n82o"/><path class="fzh1iqywv"/><path class="fu9nfdc0s"/><path class="bxt79-bos"/><path class="f_is4xbmt"/><path class="e2n8139zm"/><path class="gus6yquli"/><path class="ky10skl3y"/><path class="ebdk2bqoz"/><path class="a04dptf6n"/><path class="f1o5rrwzv"/><path class="k-6xh9_5s"/><path class="hwbt4vn1p"/><path class="b8ytiibqk"/><path class="qztwr7bex"/><path class="aleh_1fqu"/><path class="x79uhu9pp"/><path class="mipdsybyn"/><path class="pw2pwfcqo"/><path class="p8epoob0x"/><path class="u0xtsgb3c"/><path class="ptn9-g2gx"/><path class="ja377gbsb"/><path class="ajq63_bic"/><path class="itkcc7bmu"/><path class="arjpd2bhy"/><path class="r-vgk9qql"/><path class="y0_7i0yyl"/><path class="ucccejbvq"/><path class="agpyf_bok"/><path class="vkizorbrz"/><path class="i0m0ggbwg"/><path class="y3pv4s6yb"/><path class="e77vg0baq"/><path class="e9xrukb4s"/><path class="o39q0dw_x"/><path class="ezeyrebxt"/><path class="e5k9sey3y"/><path class="maml8gy7b"/><path class="zwicqdfbu"/><path class="tzkomgyxz"/><path class="ru544ksub"/><path class="wm0m7rbgk"/><path class="o2y1dpbsk"/><path class="lke2-u8_o"/><path class="t4jh_abhn"/><path class="p-hq5mbno"/><path class="ftvt_4djz"/><path class="mlekpl8kk"/><path class="qnz2gj1mx"/><path class="vf1mr1hlb"/><path class="mn-eth-vv"/><path class="ss366lbpg"/><path class="qy0oc_6bd"/><path class="i5dsufikf"/><path class="hyoie0_jn"/><path class="uf1_3yb_o"/><path class="c31rtobge"/><path class="gpa9p_ydd"/><path class="z7etcebbq"/><path class="hj6nbo_9i"/><path class="jomn98bbx"/><path class="t7gh09bjp"/><path class="joakf_7xh"/><path class="tho47bbah"/><path class="fqi9-2gbt"/><path class="vmbkrwx-c"/><path class="zbr_i0mkn"/><path class="yadj_y75b"/><path class="s7_9261ac"/><path class="drv7idb6e"/><path class="uv0_cac4p"/><path class="hfee_5bdg"/><path class="v7pelh1pd"/><path class="k9njirbsh"/><path class="qldmlwb7a"/><path class="ofpj3mbom"/><path class="scw51dbzn"/><path class="m7oslx4zt"/><path class="rkqeb-bsj"/><path class="n8ll9jb3c"/><path class="oebz-db1b"/><path class="rt2h3xb5x"/><path class="yqilb5sbk"/><path class="juaf769bz"/><path class="sbxxxhqux"/><path class="w3zc6pbra"/><path class="th4xu4b6e"/><path class="kj4av0bxn"/><path class="d-1uckb2n"/><path class="snjrjed8x"/><path class="luxx1mbrn"/><path class="ijt5tubbc"/><path class="vy1j_obms"/><path class="du7ecw8_c"/><path class="jfbcvn-0g"/><path class="y_ycssxtv"/><path class="sfw-f1bao"/><path class="kgmxt1x-h"/><path class="e23h9e7ct"/><path class="pr12jryhe"/><path class="fwil93bxj"/><path class="lkjt6cc8y"/><path class="w7s__9bmq"/><path class="lm8dp-8nv"/><path class="jnvm-9o9g"/><path class="s3fmjrkvo"/><path class="gxj0jobrq"/><path class="nifd5vbrq"/><path class="num9hhvng"/><path class="daqfa06gt"/><path class="y4e8a1b6t"/><path class="k_4vrl_xk"/><path class="oe4qp44ry"/><path class="edonufelt"/><path class="b4_orxbzu"/><path class="zrxbmke-u"/><path class="axyed2bew"/><path class="d3a4v59rw"/><path class="unmhpucvu"/><path class="ofdrrsbrt"/><path class="oj_bwjbbr"/><path class="ieg15ac5g"/><path class="wagn8ibzz"/><path class="z_9fx_b4d"/><path class="rhc82yo9f"/><path class="at4y1qbvj"/><path class="hg00h4bll"/><path class="ppohdr45t"/><path class="vm4tb451s"/><path class="e_3gljbsx"/><path class="fm-jlfucm"/><path class="eva4-fall"/><path class="msfe7ccau"/><path class="joyj03urz"/><path class="i_vr7kyhk"/><path class="vu6od9r4i"/><path class="ndeu4lbqx"/><path class="if1xngbwu"/><path class="dzx34wobo"/><path class="n5jpzybbx"/><path class="i-gm8u2mi"/><path class="dw8qbbcoh"/><path class="rx09_cbtc"/><path class="mofw0acui"/><path class="v4vnp01od"/><path class="wxxye6b7n"/><path class="m9_32yblg"/><path class="wyupfzb5a"/><path class="ouu68ebxt"/><path class="imd8vf0xg"/><path class="dxsv_-b3h"/><path class="v03z67shi"/><path class="u7su8offd"/><path class="xl24-ebmc"/><path class="p03g1bc0d"/><path class="tyr69hl9x"/><path class="umya9db-n"/><path class="ip5wdebhp"/><path class="lujgmtbvr"/><path class="ryfgftb_f"/><path class="jlhuqexav"/><path class="bfyqjcc_y"/><path class="kagyvlsex"/><path class="dsucc019u"/><path class="ddvbcyb7u"/><path class="nb5783xyw"/><path class="at7gtelxx"/><path class="wmoyyhzxa"/><path class="zd9q6ob9z"/><path class="g1lzb4b4j"/><path class="i01247b5r"/><path class="gb5-nsbmn"/><path class="taye5rbui"/><path class="a7xlpsbaf"/><path class="ss-4byb2n"/><path class="qiu9sxbpj"/><path class="dsivjbcid"/><path class="g3q0_k47t"/><path class="da3xcvz9q"/><path class="zfmsw5c4v"/><path class="x79yrfbvp"/><path class="tcgdayxyc"/><path class="qvgff8n8c"/><path class="ubu8chb1f"/><path class="unp1e-soa"/><path class="mzdknsbpw"/><path class="yjr8-ac6a"/><path class="je32rhciw"/><path class="sk68d-b3p"/><path class="dgqaxqrjk"/><path class="v8r_c2b1i"/><path class="swxur49kt"/><path class="vt9u718fn"/><path class="n5b-a2b5m"/><path class="kqxa16b_w"/><path class="mcp-kkbib"/><path class="s3lwdznxj"/><path class="j8octebpz"/><path class="cj8e95byo"/><path class="h-6snheke"/><path class="b_u88jb5l"/><path class="c_pq5_cmr"/><path class="jj_2vm05h"/><path class="r-y1p9bqr"/><path class="eawy83dcf"/><path class="v16bdhhwz"/><path class="cgamswbii"/><path class="w_9fe_a2n"/><path class="eo2bd5wlx"/><path class="jv8yrcbwz"/><path class="bjj7vbskt"/><path class="j4jtnedre"/><path class="j6k3xg4kg"/><path class="lim2n0fud"/><path class="ql9e6tijt"/><path class="y6wmsjp6b"/><path class="n-krv6tud"/><path class="g74xymdtf"/><path class="vwedo7bxu"/><path class="lxtf-9yqo"/><path class="ggk66bb2w"/><path class="f_1wmd3_v"/><path class="w4ldrtlor"/><path class="iiqrshb-w"/><path class="zdng0-bsh"/><path class="ww_xhl_sm"/><path class="c2-2rxi_q"/><path class="b0rg8tb8p"/><path class="f8nto_bst"/><path class="h28810b6w"/><path class="pvw428ber"/><path class="i-q29tbik"/><path class="aeve9ygxv"/><path class="vxpxynrjo"/><path class="nsc5bmbzm"/><path class="ilj3m0b7d"/><path class="uj9lri19y"/><path class="n1xw9566k"/><path class="gs5iy1bvx"/><path class="o7e0a7xph"/><path class="u637l20ct"/><path class="wb5o4966q"/><path class="nsyd7fbct"/><path class="k6vmrac5i"/><path class="jelrlroke"/><path class="r02sf1bht"/><path class="eoigc0b8g"/><path class="jw41o-b6w"/><path class="a-0gftbdq"/><path class="r41cvqb8f"/><path class="ylkxorqyg"/><path class="bfkhlhb1s"/><path class="zqmmthbye"/><path class="f4pjl4utp"/><path class="lo--nvb5j"/><path class="jvt_9515y"/><path class="k70n8q8ay"/><path class="imijv2bmd"/><path class="pvw1kebup"/><path class="n_t1_9b0l"/><path class="ruavjcclk"/><path class="jy7xe___z"/><path class="t-2il32qk"/><path class="faputkb3t"/><path class="e4gu76dgp"/><path class="vgz751b_f"/><path class="dizga2o-a"/><path class="i5k3xscit"/><path class="ututh_bve"/><path class="bb87-7bgb"/><path class="qzex7do5g"/><path class="i9cqz6alm"/><path class="le-3xokhl"/><path class="v9ru6hbyx"/><path class="n3atg2b8h"/><path class="e9z2cmblw"/><path class="abaisibmg"/><path class="oklv47wqe"/><path class="qdwvmn60t"/><path class="xmj09uikf"/><path class="cm1dlk9nx"/><path class="gxbn1tb9g"/><path class="q4gsw1yqc"/><path class="z45zz-bqs"/><path class="b6db5_bjz"/><path class="wznq4j3gt"/><path class="l99cz7ube"/><path class="mbcdsacyp"/><path class="tyix493an"/><path class="plwpwsb0t"/><path class="s62732b2n"/><path class="n_1_hpt8e"/><path class="bre76w7rz"/><path class="wl0b6yb_i"/><path class="d_iqgm5gr"/><path class="nec4scbcg"/><path class="z2og57b2y"/><path class="cskm728bp"/><path class="qvmmnvzcz"/><path class="t-b9n-b0p"/><path class="kk1w0quob"/><path class="yyntohoua"/><path class="g-8r6qjnk"/><path class="vyp0r4bql"/><path class="j-x3kacbz"/><path class="bduedtvph"/><path class="tz6fo_f_r"/><path class="l9inc97hz"/><path class="ir2sr-b2y"/><path class="p11y4pb5o"/><path class="uolpueb_d"/><path class="vileadb9t"/><path class="f14ox_e2i"/><path class="rntc0jbnq"/><path class="gpbi5iv5o"/><path class="vwyk2gufj"/><path class="gsglq6b5p"/><path class="jvz-3lb7q"/><path class="w_0owbc8f"/><path class="w3-7rj__j"/><path class="g053kv0jw"/><path class="dk8l5zbrh"/><path class="soi4t8bpj"/><path class="fk6rypvvv"/><path class="shpx860pu"/><path class="rv47dp-vo"/><path class="zv3y8gbde"/><path class="j0uqeubgi"/><path class="m_mm-84od"/><path class="n9l9yac9a"/><path class="f29kanbqr"/><path class="h45czbcvh"/><path class="eddembcyf"/><path class="lv1nzibnm"/><path class="b00awvbsc"/><path class="t0ueklf-p"/><path class="czylldbdq"/><path class="vkrsz3kfx"/><path class="rv2x5ccuy"/><path class="hg8r0jchr"/><path class="u65_2ubwn"/><path class="qvvk1pb0q"/><path class="hpnqq3b7u"/><path class="iba_bccdw"/><path class="vf8t5-jzb"/><path class="ry0t_b62q"/><path class="ylme6mi_a"/><path class="hekpsdx-s"/><path class="d1_xzukou"/><path class="czelk6q9s"/><path class="eev6_5b7l"/><path class="vn67v2byj"/><path class="lrlk_ccty"/><path class="hov2xubwv"/><path class="ibwyqn10s"/><path class="cmvu6bcqf"/><path class="y4nv5707k"/><path class="t080y8b9e"/><path class="q-4paybnu"/><path class="hx6xn49ae"/><path class="nnx0v2bbe"/><path class="y3q7lhble"/><path class="acm5arf6q"/><path class="xe8a1e11o"/><path class="q77ixibvb"/><path class="bfvdwccmi"/><path class="pk9xg-r0j"/><path class="f73sx0blu"/><path class="k-zfkfbxx"/><path class="c8my2na9q"/><path class="xg0w983or"/><path class="m-arvaqoo"/><path class="od3e5iydv"/><path class="ifb7m6bhm"/><path class="pujrdkbwn"/><path class="y1ukk5bls"/><path class="fqs-mbc-c"/><path class="l7lf1ha2e"/><path class="mn13xsb2c"/><path class="zfza_7b2h"/><path class="bllxtvb_g"/><path class="eb6s9fb2g"/><path class="a18flnyfn"/><path class="llbwg9bnd"/><path class="y6psvfy9r"/><path class="rzo03q2dk"/><path class="nv46cncas"/><path class="usugfeb7r"/><path class="a2u4w7e_l"/><path class="yvbcxhbdw"/><path class="atrv4lzfs"/><path class="iag7e_bgz"/><path class="kxvm-sb1h"/><path class="o-8smvbio"/><path class="gbmg8nknk"/><path class="b7tlidc4w"/><path class="m_2bxabsn"/><path class="ocu36chmg"/><path class="a3m2h7bhk"/><path class="c-v642jsm"/><path class="wxpn03o9p"/><path class="va62r9bea"/><path class="fr8lh7b4o"/><path class="wdg38l4ik"/><path class="zlrn7wbtc"/><path class="d9ipo5khc"/><path class="t5qx0kbau"/><path class="a8ezu1s2b"/><path class="sre2b136g"/><path class="yh37l7brs"/><path class="iu069b9cz"/><path class="zwz5uupji"/><path class="zrhjsob9b"/><path class="b333ytblt"/><path class="ddahwxg4t"/><path class="jm8i941_w"/><path class="okfvxl8em"/><path class="ji0yv8blg"/><path class="u5x0o3mff"/><path class="kvxcsp9iv"/><path class="ht3tlvjxq"/><path class="wev3glbvx"/><path class="f-3xhiqqz"/><path class="rq0g5qbca"/><path class="dy4c_hniv"/><path class="xh6z57bvn"/><path class="iwgzh48hb"/><path class="b0wo5acpi"/><path class="r3no7gbcr"/><path class="y0-ka7bla"/><path class="p9e_uvb2w"/><path class="hw5uz3bis"/><path class="jngu3qb_w"/><path class="mp5hlty4t"/><path class="h0ur2slpr"/><path class="lb6fpbb2k"/><path class="nmdo46bps"/><path class="vxjvnhbih"/><path class="myldcsakn"/><path class="uaw5f4dtq"/><path class="ao_vfsbvl"/><path class="w528eebnh"/><path class="yrg3ynu1a"/><path class="h9sb79erx"/><path class="khge7qbnx"/><path class="s699b3bzx"/><path class="pj0wtiv6n"/><path class="ri_i_gb1n"/><path class="ijshzb44u"/><path class="itcv-fdln"/><path class="aakjd9b3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-gibraltar" /></template>
<style>
.a-0gftbdq {
  fill: var(--svg-color--d7020c, #d7020c);
  d: path("M22.07 34.769c-.326-.88-.403-1.769-.096-2.67c.053-.147-.084-.204-.126-.308c-.078-.195-.17-.467.079-.55c.206-.073.405.088.433.354c.194.141.09.431.283.574c0 .687-.019 1.369.012 2.053c.019.452-.17.599-.585.547");
}

.a04dptf6n {
  fill: var(--svg-color--5c180a, #5c180a);
  d: path("M32.909 40.854c.275-.661-.155-.62-.582-.583q-.018-.034-.034-.069a.23.23 0 0 1 .073-.134a.5.5 0 0 1 .146-.063q.076-.022.157-.034c.107-.022.214-.059.327-.059a.94.94 0 0 1 .418.165c.174.189.435.375.059.615c-.16.15-.363.152-.564.162");
}

.a18flnyfn {
  fill: var(--svg-color--2d0c03, #2d0c03);
  d: path("M34.503 35.643q-.286.014-.57.024c-.06-.015-.118-.026-.178-.043a.18.18 0 0 1 .009-.179c.147-.167.137-.342.02-.521c.351-.232.45-.552.432-.973c-.039-.878-.024-1.761-.032-2.641c-.066-.132-.061-.242.076-.322c.459.195.407.616.436 1c.04.893.038 1.781.005 2.67c-.008.244-.005.482-.177.68z");
}

.a2u4w7e_l {
  fill: var(--svg-color--412e0a, #412e0a);
  d: path("M33.783 34.925c.167.111.407.19.367.444c-.029.172-.226.113-.354.129c-.149-.118-.127-.254-.034-.395q.008-.088.021-.178");
}

.a3m2h7bhk {
  fill: var(--svg-color--bd0f1d, #bd0f1d);
  d: path("M32.477 18.301c-.031.22.09.512-.263.591q-.046-.04-.099-.079c-.243-.781-.152-1.571-.062-2.359a.36.36 0 0 1 .161-.189c.432.16.228.529.249.811c.033.405.014.817.014 1.225");
}

.a6vb95p1q {
  fill: var(--svg-color--6d0708, #6d0708);
  d: path("M43.45 23.934q.004-.113.015-.23q-.004-.1-.01-.199q-.13-.147.003-.291q0-.07-.003-.145l.146-.124c.106.046.205.102.254.216c.09.305.106.607-.047.898c-.09.096-.195.11-.314.071q-.113-.074-.044-.196");
}

.a6zjm6b1d {
  fill: var(--svg-color--5b0000, #5b0000);
  d: path("m42.28 16.271l-.07-.004l-.061.026a.54.54 0 0 1-.275.118a2 2 0 0 1-.205-.002c-.18-.036-.353.001-.527.04a41 41 0 0 1-4.062.004c-.143-.023-.281-.08-.43-.068a.8.8 0 0 1-.221.004c-.146-.05-.289-.104-.201-.311a.8.8 0 0 1 .4-.234c.442-.094.893-.037 1.336-.058c.331.009.662-.009.993 0c.25 0 .5.009.75-.011c.708.034 1.415-.004 2.123.02q.127.006.246.031a.55.55 0 0 1 .219.115c.071.112.1.223-.015.33");
}

.a7xlpsbaf {
  fill: var(--svg-color--251400, #251400);
  d: path("m31.485 48.934l-.16.156l-.08-.07a.8.8 0 0 1-.075-.195a2 2 0 0 1-.026-.214c.012-.317-.081-.652.147-.935l.034-.184h.114l.043-.012c.295.485.204.969.003 1.454");
}

.a8ezu1s2b {
  fill: var(--svg-color--ad0a14, #ad0a14);
  d: path("M32.21 18.892c-.065.256.298.321.261.565q-.51-.01-1.018-.016l.115-.552l.034-.011q.289-.232.578-.002z");
}

.aakjd9b3f {
  fill: var(--svg-color--080000, #080000);
  d: path("M30.511 17.14c.115.436.098.717.022 1.156c-.115-.435-.097-.72-.022-1.156");
}

.abaisibmg {
  fill: var(--svg-color--dd000a, #dd000a);
  d: path("M23.513 18.301c.168-.063.403-.225.481-.17c.178.127.029.311-.051.486c-.133.291.271.523.15.838h-.581c-.213-.385-.205-.769.001-1.154");
}

.acj9-9bnv {
  fill: var(--svg-color--400101, #400101);
  d: path("M26.11 36.484a2 2 0 0 1-.129.037q-.075-.01-.15-.023c.001-.309.032-.572.427-.283c.01.125-.053.206-.148.269");
}

.acm5arf6q {
  fill: var(--svg-color--d70211, #d70211);
  d: path("M25.801 31.02a13 13 0 0 0-.267-.298q.005-.074.007-.146c.518-.09.667.479 1.152.643v-4.802q.143.003.285.002l-.002 7.769q-.136.131-.274-.002a458 458 0 0 1-.011-2.02c-.193-.141-.076-.449-.309-.57c-.289-.095-.259-.511-.581-.578");
}

.aeve9ygxv {
  fill: var(--svg-color--b00811, #b00811);
  d: path("M37.688 35.25q1.583-.027 3.167-.049c.385.062.801-.121 1.163.137c-1.44-.033-2.89.127-4.33-.088");
}

.agpyf_bok {
  fill: var(--svg-color--592d00, #592d00);
  d: path("m28.568 49.637l-.002 1.031q-.07 0-.138-.008c.03-.344-.15-.713.14-1.023");
}

.ahvuvmiqe {
  fill: var(--svg-color--c10b12, #c10b12);
  d: path("m43.749 23.1l.56.125l-.009 1.146c-.164.154-.3.047-.437-.047a.4.4 0 0 1-.143-.252z");
}

.ajq63_bic {
  fill: var(--svg-color--d4020c, #d4020c);
  d: path("M37.951 36.797q0 .143-.005.287c-.296.24-.646.137-.973.141a82 82 0 0 1-2.804-.002c-.294-.005-.694.146-.838-.216c-.149-.385.472-.256.496-.581c.606-.208 1.222-.121 1.838-.072c.291.106.559.294.893.244c.279.007.555 0 .831.005c.209.005.412.03.562.194");
}

.akd784brj {
  fill: var(--svg-color--c30e19, #c30e19);
  d: path("M19.613 23.502q.004-.224.003-.449c.079 0 .154 0 .235.003c.191.104.335.232.208.476c-.157.105-.305.085-.446-.03");
}

.aleh_1fqu {
  fill: var(--svg-color--360e00, #360e00);
  d: path("m31.31 47.19l.013-4.33l.129-.027c.07.059.12.128.152.215c.069 1.436.136 2.873-.036 4.306a.32.32 0 0 1-.199.158c-.165-.081-.131-.198-.059-.322");
}

.ao_vfsbvl {
  fill: var(--svg-color--cd0718, #cd0718);
  d: path("M33.612 16.588q-.276-.003-.554-.01c.006-.183.086-.292.287-.291c.201.004.273.113.267.301");
}

.arjpd2bhy {
  fill: var(--svg-color--d60410, #d60410);
  d: path("M33.771 36.529c.097.063.192.122.316.201c-.201.152-.478-.031-.811.354h4.669q.005.136.005.268q-2.438.009-4.879.012c-.345-.285-.251-.586-.03-.888a.6.6 0 0 1 .321-.12c.163-.001.313.024.409.173");
}

.arqprfbio {
  fill: var(--svg-color--661f0e, #661f0e);
  d: path("m31.475 51.54l.705-.01c.107.209-.079.24-.189.312l-.088.011l-.586-.029q.081-.138.158-.284");
}

.at4y1qbvj {
  fill: var(--svg-color--dd0110, #dd0110);
  d: path("M23.513 24.368h-.576c-.227-.278-.926-.057-.821-.591c.111-.559.685-.16 1.033-.273c.019-.004.045 0 .07.002l.002.283q-.206.147.006.291q.154-.016.31-.026l-.005.002c.069.11.069.214-.019.312");
}

.at7gtelxx {
  fill: var(--svg-color--cfab5d, #cfab5d);
  d: path("M32.33 40.26a1 1 0 0 1-.124-.009q-.054-.09.027-.151c.033.002.063.009.096.011z");
}

.atrv4lzfs {
  fill: var(--svg-color--bcaa7a, #bcaa7a);
  d: path("M33.762 35.1q.015.2.034.395a.5.5 0 0 0-.044.126c-.18.017-.219-.126-.271-.253l.17-.299c.037.006.074.02.111.031");
}

.axyed2bew {
  fill: var(--svg-color--c80912, #c80912);
  d: path("M29.01 15.12c-.329.04-.245-.328-.426-.433a1 1 0 0 1-.008-.14q.039-.035.076-.072c.144-.06.281-.051.399.054a.5.5 0 0 1 .094.308a.46.46 0 0 1-.135.283");
}

.b_u88jb5l {
  fill: var(--svg-color--7c2e26, #7c2e26);
  d: path("m31.17 49.08l-.004.275q-.071.012-.138.02l.003-.02a.2.2 0 0 1-.082-.144l.011-.086q.028-.034.053-.069a.15.15 0 0 1 .157.024");
}

.b00awvbsc {
  fill: var(--svg-color--d4020e, #d4020e);
  d: path("M33.626 24.08c-.021.199-.138.287-.339.287h-2.514c-.203 0-.306-.107-.307-.312h2.832z");
}

.b0rg8tb8p {
  fill: var(--svg-color--4c0d0c, #4c0d0c);
  d: path("M36.51 24.07c-.328-.033-.686.157-.984-.122c.329.042.68-.122.984.122");
}

.b0wo5acpi {
  fill: var(--svg-color--ddcb5e, #ddcb5e);
  d: path("m30.3 35.22l-.008.402a1 1 0 0 0-.11.01q-.02-.052-.045-.108c-.032-.15-.117-.324.163-.304");
}

.b333ytblt {
  fill: var(--svg-color--d7010e, #d7010e);
  d: path("M35.652 26.373q.284.017.566.038l.006.56c-.186.158-.396.16-.616.072c-.233-.154-.497-.156-.763-.156c-1.95-.005-3.898.002-5.848-.007c-.481-.005-.764.059-.822.679a28.7 28.7 0 0 0 .087 6.108c.06.241.072.481-.004.724c-.077.188-.217.319-.382.431c-.114.043-.217.036-.312-.05l.007-8.354l-.013-.033c.371-.205.784-.188 1.185-.192c2.029-.009 4.059-.007 6.089-.003c.287.002.58-.018.82.183");
}

.b3rat6bqn {
  fill: var(--svg-color--570000, #570000);
  d: path("M29.987 13.673c-.241.575-.72.23-1.079.243c-.245.004-.213-.243-.034-.4c.333.322.747.071 1.113.157");
}

.b4_orxbzu {
  fill: var(--svg-color--da0511, #da0511);
  d: path("M26.709 15.41c.355-.037.258-.402.421-.58c.047-.006.089-.01.136-.013l-.012.881l-.574-.001q-.063-.048-.046-.101q.016-.053.036-.052a.6.6 0 0 1 .039-.134");
}

.b6db5_bjz {
  fill: var(--svg-color--3e2e00, #3e2e00);
  d: path("M32.04 36.498v.299h-.589c-.12-.059-.121-.17-.139-.278a.28.28 0 0 1 .185-.214a.66.66 0 0 1 .543.193");
}

.b7tlidc4w {
  fill: var(--svg-color--d7030b, #d7030b);
  d: path("M33.02 19.756c-.184-.1-.366-.197-.548-.299c-.153-.165-.441-.244-.341-.562c.122-.192.153-.44.343-.595h.275c.199.251.404.479.772.385c.396-.234.07-.75.396-1.01c.103-.043.201-.035.285.044v1.446c-.077.086-.214.172-.22.266c-.074.868-.533.543-.962.323");
}

.b8ytiibqk {
  fill: var(--svg-color--f3d738, #f3d738);
  d: path("M33.635 40.705c.279-.025.42-.184.436-.462q.072 0 .145-.005c.021.017.047.029.07.046c.078.077.113.188.188.271l.058-.012a.55.55 0 0 1-.467.321l-.276-.016z");
}

.b9hzi5b-v {
  fill: var(--svg-color--400c00, #400c00);
  d: path("M30.16 39.814q-.283.133-.571.262c.01-.281.181-.383.433-.395q.065-.077.15-.026a.14.14 0 0 1-.012.159");
}

.ba5c54bqt {
  fill: var(--svg-color--431310, #431310);
  d: path("M34.93 13.12c.342-.304.843-.264 1.062-.053c.229.229.238.725-.038 1.078a.4.4 0 0 1-.159-.247c-.038-.155-.04-.317-.137-.448c-.185-.237-.511-.172-.728-.33");
}

.bb87-7bgb {
  fill: var(--svg-color--c60910, #c60910);
  d: path("m34.785 15.12l.15-.435h.137c.006.212.021.431-.287.435");
}

.bduedtvph {
  fill: var(--svg-color--fbdd22, #fbdd22);
  d: path("M31.622 47.928c.217.133.038.449.271.572l-.001.146l-.267-.003q-.004-.357-.003-.715");
}

.bfkhlhb1s {
  d: path("M23.08 32.17q.007-.067.012-.138c.575-.022.945-.389 1.245-.813c.267-.378.573-.533 1.017-.362a.9.9 0 0 1 .311.157c.514.399.742.905.676 1.572a7.2 7.2 0 0 0 .002 1.512c.072.646-.164.943-.803.948l-2.301.002c-.25-.221-.24-.512-.225-.801c.035-.692-.084-1.389.066-2.077");
}

.bfvdwccmi {
  fill: var(--svg-color--c30711, #c30711);
  d: path("M26.702 34.19q.14 0 .274.002c-.026.17.094.381-.139.508c-.229-.131-.11-.342-.135-.51");
}

.bfyqjcc_y {
  fill: var(--svg-color--530e01, #530e01);
  d: path("m31.33 40.25l.136-.138c.237-.175.464-.032.696.022q.09.052.161.129v.008c-.342.527-.672.364-.993-.021");
}

.bjj7vbskt {
  fill: var(--svg-color--8b170e, #8b170e);
  d: path("M32.04 38.555q.074.199.144.395c-.096.007-.191.01-.286.021c-.056-.125-.163-.15-.28-.15l.013-.312c.149-.099.286-.106.409.046");
}

.bllxtvb_g {
  fill: var(--svg-color--430f05, #430f05);
  d: path("M30.18 35.627q-.157.02-.312.031c-.188-.006-.378-.018-.566-.027q-.006-.141-.016-.282c-.175-.194-.188-.437-.188-.677c.003-1.037-.027-2.068.017-3.103q.015-.13.063-.253c.116-.15.169-.418.458-.254c.027.275.107.553-.048.821l-.007 2.224c-.006.268-.014.535.29.666a.5.5 0 0 1 .11.141c.041.106.063.223.111.328c.04.077.086.149.119.227c.02.06.007.115-.031.158");
}

.bo3d4hbwo {
  fill: var(--svg-color--c60810, #c60810);
  d: path("M40.855 23.22c-.245.251-.155.742-.611.837l.063-.83q.276-.002.548-.007");
}

.bpj2vpbpm {
  fill: var(--svg-color--6a0101, #6a0101);
  d: path("M43.615 35.6a.3.3 0 0 1 .129.053c.162.226.354.449.018.688c-1.828.1-3.653.21-5.478-.061c-.116-.111-.118-.238-.048-.377c.306-.244.676-.189 1.027-.193c1.285-.018 2.572.021 3.856-.025c.159-.066.324-.099.496-.085");
}

.bre76w7rz {
  fill: var(--svg-color--510300, #510300);
  d: path("m31.04 49.07l.255-.163c.007.048.01.094.018.143l-.145.031z");
}

.bxt79-bos {
  fill: var(--svg-color--9f0206, #9f0206);
  d: path("M20.335 24.662v.145q-.14-.003-.278-.008c-.15-.211-.378-.116-.572-.148a.4.4 0 0 1 .014-.145c.278-.096.559-.125.835.007v.005q.078.046.054.096q-.029.046-.053.048");
}

.byppzybgq {
  fill: var(--svg-color--530000, #530000);
  d: path("m37.25 14.732l-.02.045c-.166.248-.399.221-.644.164a.36.36 0 0 1-.23-.26a.3.3 0 0 0 .009-.143c.308-.001.641-.104.885.194");
}

.c_pq5_cmr {
  fill: var(--svg-color--a78d6b, #a78d6b);
  d: path("m31.19 39.682l.104-.002q.008.079.018.156l-.071.008l-.066-.014z");
}

.c-v642jsm {
  fill: var(--svg-color--b00814, #b00814);
  d: path("M31.03 17.722q.004.146.003.294c-.003.32-.005.641-.305.855c-.092-.059-.192-.111-.208-.236c.02-.49.041-.979.02-1.468c.014-.237-.185-.288-.334-.383l-.059-.073c0-.051.005-.099.005-.146l.586-.018c.104-.066.197-.066.285.025z");
}

.c2-2rxi_q {
  fill: var(--svg-color--c20915, #c20915);
  d: path("M33.635 23.22q-.004.141-.003.283a.5.5 0 0 1 .13.314a.42.42 0 0 1-.149.31c-.118.041-.226.032-.313-.072q.036-.416.076-.837z");
}

.c31rtobge {
  fill: var(--svg-color--8b0a0c, #8b0a0c);
  d: path("M37.949 21.04c.005.792.007 1.578.022 2.365c.002.232-.058.484.14.678c.12.109.176.254.212.406a.8.8 0 0 1 .002.192a4 4 0 0 1-.086.394c-.036.104-.089.192-.202.231c-.119.018-.221-.009-.294-.106c-.269-.523.029-1.125-.216-1.646c-.205-.099-.271.088-.382.182c-.13.113-.232.107-.265-.092c.006-.225-.019-.446.062-.662l-.01-.027c.11-.092.075-.243.142-.354a.7.7 0 0 1 .248-.136c.39-.143.199-.453.206-.706c0-.104.018-.199.047-.299c.091-.17.085-.426.374-.42");
}

.c7oeo4bdl {
  fill: var(--svg-color--ce050b, #ce050b);
  d: path("M37.967 15.977q.004-.134.003-.27c.124-.221.45-.078.56-.321a1 1 0 0 1 .015-.117c.097-.087.201-.087.311-.027c.046.244.299.452.122.733l-1.01.002");
}

.c8my2na9q {
  fill: var(--svg-color--ca0917, #ca0917);
  d: path("m27.56 26.13l-.571-.003c-.198-.084-.555.128-.563-.308h1.714a.27.27 0 0 1 .073.201a.26.26 0 0 1-.128.172a.49.49 0 0 1-.525-.062");
}

.cgamswbii {
  fill: var(--svg-color--3b0500, #3b0500);
  d: path("M32.614 36.521c-.165-.107-.01-.199.017-.297c.093-.096.188-.093.285-.01c.106.063.135.156.12.271q-.212.021-.422.036");
}

.ci7z0ib2b {
  fill: var(--svg-color--380705, #380705);
  d: path("M36.793 17.03c-.326-.17-.164-.452-.163-.699c.047-.105.101-.168.194-.038q-.005.265-.007.534q.08.112-.024.203");
}

.cj8e95byo {
  fill: var(--svg-color--61130a, #61130a);
  d: path("M31.33 49.35a3 3 0 0 1-.166.006c-.08-.083-.08-.176-.031-.273a.16.16 0 0 1 .18-.033l.013.041z");
}

.cm1dlk9nx {
  fill: var(--svg-color--b8151c, #b8151c);
  d: path("M27.11 35.923q.08-.073.163-.143c.649-.101 1.288-.347 1.954-.081q.121.076.094.222c-.253.242-.575.118-.867.149c-.212-.002-.43.019-.605-.141z");
}

.cmvu6bcqf {
  fill: var(--svg-color--c7050d, #c7050d);
  d: path("M25.537 30.438q.004.069.004.145q.07.11-.027.202a.54.54 0 0 1-.326.075c-.338-.141-.666.063-1 .042a.8.8 0 0 1-.328-.101l-.073-.09l.017-.273c.095-.077.19-.086.289-.006c.481-.369.961.158 1.444.006M23.2 31.564c-.084.019-.17.033-.256.05c.153-.419.202-.935.839-.903l.024.025c.082.299-.201.426-.305.637c-.08.099-.159.196-.302.191");
}

.cskm728bp {
  fill: var(--svg-color--441d07, #441d07);
  d: path("m32.475 35.645l.304-.004c.194.155.108.377.138.574c-.092 0-.191.005-.285.006q-.08-.079-.156-.158q-.181-.209-.001-.418");
}

.csp4fqbss {
  fill: var(--svg-color--3d120c, #3d120c);
  d: path("M40.15 15.386a.25.25 0 0 0-.019-.122q.067-.098.146-.005c.26.075.506.021.742-.091l.23.103c.074.169-.055.215-.163.272c-.329.061-.663.139-.936-.157");
}

.czelk6q9s {
  fill: var(--svg-color--d9010c, #d9010c);
  d: path("M37.39 27.26q-.299-.028-.28-.325c.013-.177.126-.237.28-.258z");
}

.czylldbdq {
  fill: var(--svg-color--d80b14, #d80b14);
  d: path("M34.35 14.558c-.379.208-.76.204-1.143.005c.383-.003.761-.005 1.143-.005");
}

.d_iqgm5gr {
  fill: var(--svg-color--eed214, #eed214);
  d: path("M30.583 48.2c.158-.174.354-.213.572-.141c.009.195.012.389.018.586c-.201.158-.382.018-.569-.039l-.033-.253q-.053-.079.012-.153");
}

.d-1uckb2n {
  fill: var(--svg-color--560105, #560105);
  d: path("M37.959 35.955h.289q.01.141.016.282c-.003.124-.027.239-.152.304l-.149-.052c-.15-.178-.156-.357-.004-.534");
}

.d1_xzukou {
  fill: var(--svg-color--d4020c, #d4020c);
  d: path("M39.12 30.15c-.294.076-.508.398-.866.289c-.141-1.01.511-.42.866-.432zm0-.14c.269-.234.529-.178.854-.015c-.334.273-.587-.079-.854.015");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d3a4v59rw {
  fill: var(--svg-color--520001, #520001);
  d: path("M28.421 14.275c.191-.002.388-.002.578-.005q.053.05.036.108c-.005.034-.017.055-.027.055c-.133.08-.316-.025-.435.115l-.001-.002l-.144-.134z");
}

.d9ae4r7_t {
  fill: var(--svg-color--200304, #200304);
  d: path("M23.513 23.07c.283.639.768.773 1.44.748c.499-.019.725-.188.861-.607c.252.252.215.534.097.826a.44.44 0 0 1-.19.163a1.4 1.4 0 0 1-.488.077c-.526-.022-1.053.053-1.574-.059a.5.5 0 0 1-.202-.141c-.106-.197-.115-.394.029-.576q.011-.216.027-.431");
}

.d9ipo5khc {
  fill: var(--svg-color--d6010f, #d6010f);
  d: path("M33.918 21.768v-.577q.3.024.279.324c-.013.175-.125.237-.279.253");
}

.da3xcvz9q {
  fill: var(--svg-color--680000, #680000);
  d: path("M37.39 36.498q-.796.012-1.592.029l-2.02.002a21 21 0 0 0-.434-.036q-.055-.15.085-.226a14.5 14.5 0 0 1 3.889.002q.135.084.074.229");
}

.daqfa06gt {
  fill: var(--svg-color--6f0000, #6f0000);
  d: path("M25.54 25.521c-1.245 0-2.488-.004-3.731.008c-.253.002-.533-.098-.744.141q-.078-.005-.151-.006c0-.097.002-.189.004-.285q2.304-.005 4.61-.008q.057.045.043.096q-.013.053-.031.054");
}

.ddahwxg4t {
  fill: var(--svg-color--d7020c, #d7020c);
  d: path("m34.522 35.34l-.017-3.458c.088-.081.188-.089.293-.052c.391.227.408.595.426.992c.029.623-.132 1.26.107 1.867c-.272-.469-.074-.986-.107-1.481c-.035-.524-.046-1.042.373-1.477c.28-.291.258-.701.244-1.086c.055-.206.141-.354.383-.208c.004 1.393-.018 2.786.018 4.176c.012.541-.113.82-.713.744c-.332-.044-.672-.015-1.01-.017");
}

.ddvbcyb7u {
  fill: var(--svg-color--420000, #420000);
  d: path("m32.485 39.867l.267-.02q.07.082.142.16q-.129.055-.258.106q-.077-.05-.159-.093l-.042-.077z");
}

.dgqaxqrjk {
  fill: var(--svg-color--581f00, #581f00);
  d: path("M29.612 50.07c.433.044.758-.071.839-.556q.082-.086.197-.03a.35.35 0 0 1 .156.28c-.024.295-.134.53-.446.621a1.56 1.56 0 0 1-1.06-.134l-.002-.056q-.064-.057-.033-.094q.031-.032.059-.032z");
}

.dizga2o-a {
  fill: var(--svg-color--d60912, #d60912);
  d: path("M34.35 14.558c.203.002.431-.083.59.129c.028.169.049.341-.15.435q-1.301 0-2.601.002c-.127-.145-.274-.236-.473-.211c-.387-.011-.775.078-1.152-.072c-.049-.104-.049-.198.038-.28l2.607.003a2.3 2.3 0 0 0 1.141-.006");
}

.dj2jk3l7g {
  fill: var(--svg-color--850504, #850504);
  d: path("M44.41 37.12a.3.3 0 0 1 .018.084q-2.8.015-5.599.032c-.267-.1-.491-.012-.707.14q-.09.086-.194.015a.52.52 0 0 1-.116-.305a.7.7 0 0 1 .053-.334a.33.33 0 0 1 .281-.184c.164.006.314.072.464.131c1.498.087 2.997.012 4.496.037c.307.004.616-.021.923.05c.184.046.292.177.381.334");
}

.dk8l5zbrh {
  fill: var(--svg-color--ca040e, #ca040e);
  d: path("M29.3 22.345q.432 0 .863.005c-.289.435-.577.452-.863-.005");
}

.dqvltbb_f {
  fill: var(--svg-color--84292b, #84292b);
  d: path("m43.03 35.494l.155-.191c.221-.014.45-.04.43.297c-.052.139-.171.168-.301.186c-.244.049-.332-.056-.284-.292");
}

.drv7idb6e {
  fill: var(--svg-color--ca050e, #ca050e);
  d: path("M31.32 14.11q.145.049.289.104c-.425.356-.857.327-1.293.022l-.009-.125z");
}

.ds0c7h_cg {
  fill: var(--svg-color--d0030d, #d0030d);
  d: path("M21.471 24.05c.053-.003.104-.003.157-.009c.184-.949.929-.803 1.593-.817c.086.091.082.19.034.294c-.229.242-.604.059-.808.251c-.138.39.852.172.323.731c-.562.12-1.125.067-1.69.048c-.253-.012-.543-.05-.5-.435c.285-.195.589-.105.891-.063");
}

.dsivjbcid {
  fill: var(--svg-color--552b00, #552b00);
  d: path("M28.578 48.783q-.069 0-.136-.01q0-.5.002-.994q.046-.001.093.004l.064-.004c.243.34.16.674-.023 1");
}

.dsucc019u {
  fill: var(--svg-color--520100, #520100);
  d: path("M31.344 41.24a.3.3 0 0 1-.016-.088q.065.058.129.123a.3.3 0 0 1-.113-.035");
}

.du7ecw8_c {
  fill: var(--svg-color--710001, #710001);
  d: path("m42.878 35.34l-.859.002c-.387-.174-.813.038-1.202-.125a.6.6 0 0 1-.122-.225c-.034-.822-.138-1.646.068-2.461a.2.2 0 0 1 .203-.106c.413.462.165 1.03.222 1.548c.036.321-.041.688.426.756q.11.017.211.045c.332.162.697.027 1.038.127z");
}

.dw8qbbcoh {
  fill: var(--svg-color--d9010d, #d9010d);
  d: path("M22.938 19.17c.053-.677-.181-1.393.289-2.01h.573c.652.259 1.329.109 1.992.115c.553.004.773.191.765.757c-.029 1.417-.005 2.835-.013 4.252c-.043.23-.064.488-.419.346l-.008-.011c-.152-.34-.059-.703-.065-1.055c-.004-.293-.024-.572-.212-.809a.17.17 0 0 1-.025-.113c.025-.287.05-.552-.328-.658c-.242-.072-.239-.316-.237-.531c.103-.103.183-.219.056-.344s-.243-.043-.344.057c-.23.025-.533-.1-.58.287h-.287c-.201-.277-.408-.541-.32-.931c.034-.161-.113-.047-.179-.04c-.288.139-.126.522-.371.684h-.287");
}

.dwaxxvirj {
  fill: var(--svg-color--5b0102, #5b0102);
  d: path("m36.51 14.801l.006 1.196c-.058.108-.153.134-.262.138c.016-.486-.176-.986.1-1.453z");
}

.dxsv_-b3h {
  fill: var(--svg-color--620003, #620003);
  d: path("M21.77 35.951a8 8 0 0 0-.133.25c-.146.01-.287.025-.433.039q-.144-.022-.289-.041q0-.126.002-.248z");
}

.dy4c_hniv {
  fill: var(--svg-color--d7010e, #d7010e);
  d: path("M28.426 35.06c.012-.084.029-.217.127-.18c.204.086.152.297.162.472q-.142.002-.279.009q-.004-.153-.01-.301");
}

.dzx34wobo {
  fill: var(--svg-color--cb0e16, #cb0e16);
  d: path("M40.855 20.613V18.3h.142c-.076.768.161 1.555-.142 2.313");
}

.e_3gljbsx {
  fill: var(--svg-color--d8010c, #d8010c);
  d: path("M37.68 21.485a7 7 0 0 0-.005.282c-.136.092-.26.08-.363-.057c-.147-1.428-.052-2.859-.048-4.293c0-.096.064-.177.128-.248c1.15 0 2.304-.003 3.454-.005c.005.378.005.756.01 1.136q.166 1.155 0 2.313l-.005.002c-.124.062-.008.373-.286.285c-.119-.265-.196-.576-.583-.568c-.568-.311-1.141-.34-1.708 0c-.548.205-.452.74-.594 1.153");
}

.e23h9e7ct {
  fill: var(--svg-color--b00004, #b00004);
  d: path("m43.46 24.666l-5.2-.013q-.002-.071 0-.139c.44-.351.976-.248 1.439-.183c1.044.156 2.081.084 3.123.11c.118.003.237-.001.342.07h.293c.191.021.407-.061.564.124c-.142.007-.282.021-.423.033l-.069-.01z");
}

.e2n8139zm {
  fill: var(--svg-color--ca0610, #ca0610);
  d: path("M26.701 16.873H22.64l-.258-.039l-.02-.541q2.032-.01 4.066-.009c.223 0 .501-.077.549.276v.287c-.082.096-.176.096-.276.026");
}

.e2ry6bc3z {
  fill: var(--svg-color--811313, #811313);
  d: path("M41.41 22.697v.059l.057.021c.864-.029.916.016.914.851c-.08.136-.197.216-.365.202a1.4 1.4 0 0 0-1.24-.431c-.193-.007-.387-.029-.543-.161c-.164-.252-.161-.521-.062-.795c.171-.245.295-.071.427.046c.119.172.313.177.49.216c.207.244.095-.168.213-.109c.07-.002.109.032.109.101");
}

.e4gu76dgp {
  fill: var(--svg-color--d4020e, #d4020e);
  d: path("m28.72 23.21l1.708.017l.044.828c-.239.241-.464.189-.677-.038a1 1 0 0 1-.08-.191c-.012-.049-.066-.112-.083-.099c-.097.079.071.072.054.138c.197.452.236 1 .951 1.029c.283.012.447.304.023.498c-1.309.033-2.618.164-3.917-.074c-.123-.091-.141-.211-.098-.349c.213-.247.509-.208.79-.22c.547.048 1.079-.009 1.575-.287c-.501.039-.996.135-1.499.104c-.267 0-.535.014-.787-.102c-.109-.123-.354-.244-.019-.391l.145-.027c.044.014.087.02.134.01c.48 0 .962-.004 1.444-.004c.258-.227.023-.62.292-.842");
}

.e5a75ccmn {
  fill: var(--svg-color--4b0b0c, #4b0b0c);
  d: path("M20.626 24.1q-.14-.019-.277-.035c.371-.21.745-.191 1.122-.013q-.423.021-.845.048");
}

.e5k9sey3y {
  fill: var(--svg-color--d0b730, #d0b730);
  d: path("M30.882 39.826c-.003-.131-.04-.244-.173-.303c.063-.135.182-.126.302-.12c.134.114.144.252.067.403q-.088.097-.196.02");
}

.e77vg0baq {
  fill: var(--svg-color--b2a663, #b2a663);
  d: path("M31.452 49.38c.325.443.075.949.159 1.422c.054.127-.012.154-.121.143z");
}

.e88um79-k {
  fill: var(--svg-color--82070a, #82070a);
  d: path("M42.29 23.648c.068.115.155.181.295.133c.299.063.591.045.876-.078c.063.119.053.224-.057.309c-.365.187-.779.068-1.154.188c-.173.005-.35-.002-.421-.185c-.049-.128.011-.229.171-.227q.147-.068.29-.14");
}

.e9xrukb4s {
  fill: var(--svg-color--ae9555, #ae9555);
  d: path("m31.49 50.945l.121-.143a.3.3 0 0 0 .138-.007a.26.26 0 0 1 .252-.056c.089.047.121.131.147.221q-.049.071-.097.147c-.18.093-.362.153-.552.019c0-.059-.006-.118-.009-.181");
}

.e9z2cmblw {
  fill: var(--svg-color--e1000c, #e1000c);
  d: path("M24.961 19.17c.074-.34.305-.39.502-.168c.16.182.088.412-.214.455c-.007-.188-.103-.281-.288-.287");
}

.eawy83dcf {
  fill: var(--svg-color--222500, #222500);
  d: path("M31.442 36.898a.3.3 0 0 1 .007-.102c.152-.178.363-.184.575-.182a.58.58 0 0 1 .439.197a.36.36 0 0 0-.005.41c-.186.232-.658-.005-.716.437c-.198.003-.276-.109-.278-.294l.002-.09c-.01-.025-.015-.049-.024-.073a.4.4 0 0 1 .132-.054a.25.25 0 0 0 .107-.085c-.053-.024-.047.048-.086.05l-.071.021a.16.16 0 0 1-.122-.086a.34.34 0 0 1 .04-.149");
}

.eb6s9fb2g {
  fill: var(--svg-color--ce0914, #ce0914);
  d: path("m36.515 35.934l.001.271h-2.31v-.271z");
}

.ebdk2bqoz {
  fill: var(--svg-color--c6090a, #c6090a);
  d: path("M32.455 41.25a.15.15 0 0 1-.106.029c-.285.025-.564.115-.858.086a1 1 0 0 1-.288-.115c-.237-.156-.509-.283-.588-.6a.5.5 0 0 1 .104-.426c.168-.119.352-.125.541-.075c.393.247.785.281 1.182 0c.748.007.809.103.468.709l.013-.009c-.176.112-.344.231-.468.401");
}

.eddembcyf {
  fill: var(--svg-color--690101, #690101);
  d: path("M37.09 26.09c.203.021.285-.09.301-.273h.275q0 .284-.002.565c-.212.206-.464.194-.726.138a.45.45 0 0 1-.181-.126a.31.31 0 0 1 .025-.315c.106-.061.206-.061.308.011");
}

.edonufelt {
  fill: var(--svg-color--5d090c, #5d090c);
  d: path("M27.01 23.729c.129.057.258.121.401.055h.577c.16-.111.318-.128.473.013c.052.138.041.259-.078.358c-.486.17-.963.214-1.434-.053c-.062-.137-.061-.26.061-.373");
}

.eev6_5b7l {
  fill: var(--svg-color--d5020f, #d5020f);
  d: path("M41.712 34.792c-.396.024-.627-.098-.584-.551c.03-.305.009-.61.012-.915c.13.076.31.352.296-.092c-.017-.511-.004-1.021-.004-1.593c.386.108.247.36.289.532z");
}

.eo2bd5wlx {
  fill: var(--svg-color--2c0700, #2c0700);
  d: path("M31.463 37.05a.3.3 0 0 1-.138.032l-.002-.128a1 1 0 0 1 .119-.05c.01.046.012.098.021.146");
}

.eoigc0b8g {
  fill: var(--svg-color--d9000e, #d9000e);
  d: path("M22.07 34.769c-.685.127-.898-.144-.883-.844c.046-2.124.018-4.252.021-6.377c.126-.104.156-.278.274-.39c.119-.119.232-.244.396-.308c.572-.108 1.146-.141 1.7.072c.323.122.557.052.732-.235a.33.33 0 0 1 .282-.082c.236.064.209.375.422.463q.12.049.237.105c.199.109.338-.05.498-.115c.521-.299.808-.109.914.439c.149.763.101 1.529.054 2.293c-.042.648-.679.471-1.04.676c-.489.299-1-.022-1.503.053c-.094.053-.199-.24-.285.016a.35.35 0 0 1-.097.234c-.388.172-.573.494-.693.874a.4.4 0 0 1-.181.233l-.271.007c-.154-.048-.264-.168-.39-.255c-.062-.023-.183-.069-.173 0c.094.961-.33 1.932.07 2.881c.038.091-.013.186-.084.26");
}

.epeycyxme {
  fill: var(--svg-color--430c0f, #430c0f);
  d: path("m43.729 25.492l-.066.021l-.068-.011c-.086-.043-.178-.076-.226-.17a.8.8 0 0 1-.063-.378a.6.6 0 0 1 .088-.276a.24.24 0 0 1 .173-.072q.155.048.193.201z");
}

.epmcdpbfx {
  fill: var(--svg-color--790000, #790000);
  d: path("M32.496 13.14q.062.013.121.022q.074.053.107.143a.7.7 0 0 1-.018.448a.25.25 0 0 1-.128.122a.27.27 0 0 1-.17-.044a.3.3 0 0 1-.083-.157c.124-.157-.085-.421.171-.534");
}

.eva4-fall {
  fill: var(--svg-color--c70911, #c70911);
  d: path("M40.27 24.368q-.607-.001-1.216.003c-.267 0-.534.01-.662-.297l1.854-.027z");
}

.ezeyrebxt {
  fill: var(--svg-color--dab935, #dab935);
  d: path("M30.18 39.699q.206-.093.411-.189a.2.2 0 0 0 .113.014c.263-.059.252.129.268.295c-.135.307-.328.475-.673.283l-.146-.287a.5.5 0 0 0 .027-.116");
}

.f_1wmd3_v {
  fill: var(--svg-color--670607, #670607);
  d: path("M37.26 25.287q.204-.034.413-.064c.052-.064.098-.059.145.005l.303-.002l.146.144l-.008.152c-.095.131-.252.157-.382.23l-.072.053a.6.6 0 0 1-.158.084a.35.35 0 0 1-.262-.027a.4.4 0 0 1-.102-.145a1 1 0 0 1-.05-.172c-.014-.089-.019-.179.027-.258");
}

.f_is4xbmt {
  fill: var(--svg-color--c30711, #c30711);
  d: path("M20.917 35.951c-.251-.021-.506-.008-.716-.184c.118-.139.303-.236.301-.455q.195.005.389.013c.226-.171.49-.176.755-.176c1.657.002 3.308-.021 4.96.011a.7.7 0 0 1 .245.057c.417.354.082.505-.188.675q-.053.015-.111.034q-.503.007-1.01.021c-.675.258-1.37.086-2.054.119c-.549.032-1.099 0-1.648.013c-.323.038-.644.1-.927-.128");
}

.f-3xhiqqz {
  fill: var(--svg-color--d8010e, #d8010e);
  d: path("M28.426 35.06c-.227-.027-.527.1-.577-.287q.008-.283.29-.29c.072-.067.143-.136.222-.196c.283-.574.224-1.156.054-1.738c-.226.378.073.871-.275 1.213c-.262-.554-.229-1.166-.263-1.74c-.082-1.321-.017-2.645-.032-3.971c-.006-.35.306-.646.048-1.06c-.146-.231.192-.308.417-.308q3.463-.005 6.927 0c.096 0 .207.004.276.054c.068.044.094.151.141.233h-.004c-.279.246-.628.209-.959.213c-1.612.002-3.224-.01-4.835.013c-.192.003-.548-.222-.574.236c.253.346.129.657-.195 1.052c.522-.283.186-.814.545-1.032c.564-.165 1.08-.208 1.34.482c.099.258.37.271.578.362c.333.271.767.17 1.138.294c.224.124.409.29.537.516c.01.126-.025.208-.175.177c-.236 0-.511.07-.701-.021c-.2-.105-.693.461-.61-.254c-.071-.002-.145-.02-.212-.012c-.372.043-.675.18-.769.591l-.004-.003c-.455.16-.809.461-1.068.852c-.157.232-.279.193-.44.043c-.099-.076-.099-.328-.259-.244c-.129.074-.16.291.037.389c.115.057.28.01.352.168a.77.77 0 0 1-.075.518v.005c-.265.341-.116.737-.149 1.112c-.081.973.16 1.961-.146 2.918c-.096.005-.192.005-.289.009c-.113-.084-.123-.269-.291-.294");
}

.f14ox_e2i {
  fill: var(--svg-color--d5020d, #d5020d);
  d: path("M30.16 15.711q2.162 0 4.323.004q.003.137.009.273c-.232.282-.108.796-.591.911c-.176-.026-.215-.149-.227-.296c.076-.377-.139-.439-.445-.43c-.465.008-.254.338-.277.563c-.032.52.123 1.053-.135 1.551c-.102.094-.213.104-.338.057c-.301-.324-.168-.727-.2-1.103c-.024-.26.036-.53-.091-.778c-.159-.232-.33-.375-.57-.086c-.165.288-.07.606-.124.906c-.051.281-.075.609-.514.438c-.216-.313-.125-.671-.151-1.01c.114-.578-.442-.49-.698-.703c-.052-.107-.052-.206.029-.296");
}

.f1o5rrwzv {
  fill: var(--svg-color--eacd2f, #eacd2f);
  d: path("M33.473 40.693c.295-.279-.063-.381-.149-.553q-.143-.245.109-.372c.212-.025.36.075.479.239l.158.235c.115.403-.022.563-.436.462a3 3 0 0 0-.161-.011");
}

.f29kanbqr {
  fill: var(--svg-color--e3000b, #e3000b);
  d: path("M35.36 24.947v-.576q.298.022.279.322c-.012.176-.126.236-.279.254");
}

.f4pjl4utp {
  fill: var(--svg-color--8e0000, #8e0000);
  d: path("M26.84 35.06c.264-.188.292-.45.292-.754c-.011-2.631-.011-5.264-.014-7.894q.18-.15.354.003c.18.289.134.598.079.91c-.157.635-.075 1.285-.071 1.928c.011 1.795-.064 3.591.044 5.383c.059.215.072.424-.034.63a.2.2 0 0 1-.218.088c-.008-.302-.223-.29-.432-.294");
}

.f6m8e8yet {
  fill: var(--svg-color--60120b, #60120b);
  d: path("m33.652 13.386l.232-.007l.04.278v.275c-.146.126-.251.021-.36-.059c-.119-.151-.178-.3-.008-.457z");
}

.f73sx0blu {
  fill: var(--svg-color--930000, #930000);
  d: path("M27.412 27.26v7.51c-.178-.141-.139-.342-.139-.53a3466 3466 0 0 1 0-6.449c0-.191-.039-.391.139-.531");
}

.f8nto_bst {
  fill: var(--svg-color--781315, #781315);
  d: path("M28.573 14.549c.099-.182.271-.145.429-.154c.857-.145 1.717-.043 2.579-.063c.885-.018 1.771.012 2.655-.068c.28-.027.584-.064.832.136c.049.05.092.104.14.155l-.136.132a.3.3 0 0 1-.197.075c-.221-.025-.44-.029-.664-.025c-.361.007-.722-.004-1.08.025c-.82.004-1.641-.029-2.462-.017q-.196.005-.39 0c-.427-.043-.882.104-1.271-.186z");
}

.faputkb3t {
  fill: var(--svg-color--c1050f, #c1050f);
  d: path("M26.67 22.06q-.06.005-.121.004c0-1.313-.005-2.623.003-3.934c0-.23-.074-.483.114-.681c0 1.534.004 3.075.004 4.611");
}

.fbaw67b_p {
  fill: var(--svg-color--5d1319, #5d1319);
  d: path("M41.43 16.287c.099-.17.203-.033.305-.005c.191.246.139.479-.023.712q-.133.01-.273.018l-.016-.018c-.139-.236-.197-.473.007-.707");
}

.fk6rypvvv {
  fill: var(--svg-color--dd0107, #dd0107);
  d: path("M29.583 15.988c.388.047.26.354.29.58c.26.385.282.77-.003 1.153c-.43-.084-.266-.431-.283-.681c-.021-.349-.004-.701-.004-1.052");
}

.fm-jlfucm {
  fill: var(--svg-color--c31019, #c31019);
  d: path("M43.16 24.513q-2.451.002-4.904.002c-.169-.101-.142-.271-.149-.431l.286-.01c.323.241.696.119 1.048.153c.28.021.582-.072.83.141h2.02c.292.048.613-.115.868.145");
}

.fqi9-2gbt {
  fill: var(--svg-color--600001, #600001);
  d: path("M35.38 23.764a.5.5 0 0 0-.01.133c-.317-.219-.063-.578-.21-.839c.423.127.14.473.22.706");
}

.fqs-mbc-c {
  fill: var(--svg-color--441200, #441200);
  d: path("m30.457 35.916l-.006-.269c-.088-.096-.085-.196-.023-.304a.18.18 0 0 1 .207.014c.086.146.084.285-.034.412l-.012.177a1 1 0 0 1-.132-.03");
}

.fr8lh7b4o {
  fill: var(--svg-color--de010b, #de010b);
  d: path("M31.03 16.572a5 5 0 0 1-.285-.025c.01-.396-.608-.145-.579-.559c.416.008.906-.101.864.584");
}

.ftmfe9vgc {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M64 21c0-6.075-3.373-11-10-11H10C3.373 10 0 14.925 0 21v18h64z");
}

.ftvt_4djz {
  fill: var(--svg-color--62220d, #62220d);
  d: path("M31.33 37.959q.069.002.141.01c.067.051.16.08.209.158a.7.7 0 0 1 .056.173c.016.091.018.187.016.278a.8.8 0 0 1-.056.28c-.051.085-.116.149-.231.118c-.29-.306-.108-.676-.135-1.017");
}

.fu9nfdc0s {
  fill: var(--svg-color--710000, #710000);
  d: path("M25.677 24.949c-1.779-.049-3.556-.15-5.334 0a1 1 0 0 1-.008-.143q-.068-.14.069-.207c1.6-.028 3.203-.004 4.802-.01q.123-.002.246.002c.175.055.284.155.225.358");
}

.fuzj1gb3j {
  fill: var(--svg-color--c50916, #c50916);
  d: path("m41.12 18.299l-.122.002q-.13.068-.216-.05c-.161-.374-.197-.741.064-1.086l.282-.003q-.006.57-.008 1.137");
}

.fwil93bxj {
  fill: var(--svg-color--9f0c19, #9f0c19);
  d: path("M24.957 14.99c-.29-.288-.648-.096-.975-.143a.4.4 0 0 1 0-.141q.619 0 1.238.005c.016.124-.011.222-.138.267c-.041.012-.082.012-.125.012");
}

.fzd9mj6tu {
  fill: var(--svg-color--b80c12, #b80c12);
  d: path("M19.493 36.791q-.005-.278-.014-.558l.278-.04l-.002.053c.125.098.18.238.211.388a.2.2 0 0 1-.064.161c-.134 0-.272-.004-.409-.004");
}

.fzh1iqywv {
  fill: var(--svg-color--b60e16, #b60e16);
  d: path("M20.917 25.379c-.191-.047-.388-.092-.579-.138c0-.097.005-.194.005-.292c.247-.229.558-.292.871-.283c1.271.041 2.536.111 3.807.023a.9.9 0 0 1 .671.215c.083.115.087.24.035.369a.54.54 0 0 1-.309.25c-1.298.121-2.595.044-3.892.046a.9.9 0 0 1-.609-.19");
}

.g-8r6qjnk {
  fill: var(--svg-color--340c00, #340c00);
  d: path("M29.16 48.21c.44.052.906-.149 1.322.138c-.386.07-.805-.105-1.168.148z");
}

.g053kv0jw {
  fill: var(--svg-color--d4020f, #d4020f);
  d: path("M29.3 20.613c.456.385.46.771-.002 1.154c.002-.382.002-.771.002-1.154");
}

.g1lzb4b4j {
  fill: var(--svg-color--f7d642, #f7d642);
  d: path("m31.04 41.3l-.023.299c-.154.106-.299.05-.444-.012a11 11 0 0 1-.275-.305c.122-.062.152-.175.161-.3c.282-.058.383.215.581.318");
}

.g3q0_k47t {
  fill: var(--svg-color--ecd93f, #ecd93f);
  d: path("M29.3 40.549q.142-.001.286.005c-.003.056-.012.118-.014.179l-.279-.059c0-.041.005-.082.007-.125");
}

.g74xymdtf {
  fill: var(--svg-color--930000, #930000);
  d: path("m34.648 22.489l-.017-6.774l.143-.159c-.002 2.313-.005 4.621-.005 6.934z");
}

.g75p31gwd {
  fill: var(--svg-color--db0315, #db0315);
  d: path("M38.977 15.975q-.076-.356-.146-.711c-.116-.141-.119-.285.004-.424h.289c-.205.574.002.944.566 1.135z");
}

.gam5k7brk {
  fill: var(--svg-color--340b0d, #340b0d);
  d: path("m22.07 16.996l.025-.144a.4.4 0 0 1 .266-.127a.43.43 0 0 1 .283.093a.155.155 0 0 1-.009.182a7 7 0 0 0-.153.185z");
}

.gaw1tvxvj {
  fill: var(--svg-color--c60d16, #c60d16);
  d: path("m25.25 24.09l.43.008c.173.246.088.42-.158.546c-1.621.15-3.241.05-4.863.057a1 1 0 0 1-.244-.05c-.192-.079-.372-.169-.429-.391a.21.21 0 0 1 .075-.204l.291.011c.103-.063.198-.076.277.035c.067.354.353.262.577.266c.577.01 1.156.001 1.733.001c.158-.175.37-.134.57-.141c.578-.068 1.179.139 1.741-.138");
}

.gb5-nsbmn {
  fill: var(--svg-color--970f0d, #970f0d);
  d: path("M30 41.15c.105-.027.148.041.186.123A5 5 0 0 0 30 41.15");
}

.gbmg8nknk {
  fill: var(--svg-color--3e3000, #3e3000);
  d: path("m31.609 35.934l.018.152q-.085.068-.17.139a.3.3 0 0 0-.005-.136l.007-.155q.074-.069.143-.141q.06.044.045.092q-.02.048-.038.049");
}

.gbw8eo-8v {
  fill: var(--svg-color--640102, #640102);
  d: path("M22.638 17q.005-.063.003-.127c.06-.076.138-.156.231-.162c1.262-.099 2.526-.223 3.78.073c.123.111.128.239.064.381c-.584.342-1.223.122-1.835.177c-.31.027-.627.006-.937.004c-.208.002-.414.009-.618-.006c-.156-.008-.314-.013-.466-.059a.6.6 0 0 1-.197-.116z");
}

.gepsj4b1n {
  fill: var(--svg-color--d8020b, #d8020b);
  d: path("M42 23.789c-.111.27-.109.275.311.279l.052.114c.013.146-.055.246-.183.308c-.641.09-1.279.188-1.906-.074c-.091-.117-.091-.24-.025-.369l-.008.009c.266-.231.201-.708.611-.837c.47.009 1.031-.155 1.148.57");
}

.ggk66bb2w {
  fill: var(--svg-color--d8020f, #d8020f);
  d: path("m36.929 23.94l.026-.147c.186-.253.186-.742.713-.567c.162.633.039 1.276.073 1.911c-.045.209-.214.228-.378.248a.8.8 0 0 1-.229-.025c-.436-.215-.872-.319-1.305.01c-.479.08-.954.129-1.424-.044a.27.27 0 0 1-.122-.202c.021-.252.211-.305.411-.346c.172-.023.345-.011.517-.024c.061-.014.143-.019.151-.091c.01-.076-.069-.091-.132-.107c-.158-.029-.323-.04-.456-.145a.33.33 0 0 1-.06-.3c.074-.141.175-.231.348-.17c.094.132.188.167.291.015l.172-.011c.313.166.67-.029.984.122c.152.001.331.087.42-.127");
}

.goyu39xul {
  fill: var(--svg-color--be0b12, #be0b12);
  d: path("M36.51 14.801q.357-.01.718-.023c-.014.21-.194.391-.11.619a.34.34 0 0 0 .138.125c.242.089.535-.047.748.172c.048.104.044.199-.036.283c-.481.008-.968.016-1.451.021c-.214-.398-.206-.796-.007-1.197");
}

.gpa9p_ydd {
  fill: var(--svg-color--2f181e, #2f181e);
  d: path("M34.774 15.556q.08.007.157.016c-.002 2.282-.01 4.562-.01 6.843c0 .161.051.33.076.49c-.376.086-.34-.218-.402-.426c-.031-2.033-.007-4.064-.016-6.095c.001-.296.053-.571.195-.828");
}

.gpbi5iv5o {
  fill: var(--svg-color--d6010f, #d6010f);
  d: path("M34.493 19.746c-.251.025-.318.201-.282.403c.08.403-.139.711-.293 1.041a.27.27 0 0 1-.306.032c-.249-.252 0-.65-.267-.898c-.068-.125-.133-.259-.292-.295c-.079-.082-.089-.176-.044-.275c.622.178.775-.489 1.201-.663c.108-.022.205-.003.282.077z");
}

.gs5iy1bvx {
  fill: var(--svg-color--d9010c, #d9010c);
  d: path("m37.702 25.825l4.874-.007l.015.283l-.005 1.158c-.481.245-.988.014-1.479.082c-.188.027-.407-.088-.564.043c-.746.613-1.616.316-2.436.326c-.665.008-.615-.539-.627-1a10 10 0 0 1 0-.349c0-.203.053-.392.189-.547l.033.012");
}

.gsglq6b5p {
  fill: var(--svg-color--d7020e, #d7020e);
  d: path("M34.491 16.854q-.279.01-.285.29q-.067.074-.157.036a.38.38 0 0 1-.131-.326c.318-.201.137-.737.573-.866z");
}

.gus6yquli {
  fill: var(--svg-color--610000, #610000);
  d: path("M32.504 42.01a.5.5 0 0 0-.029.128c-.304.511-.076 1.065-.138 1.595q-.01 3.032-.014 6.068q-.147.061-.233-.075c-.148-.288-.106-.603-.106-.911c-.003-1.884-.007-3.768 0-5.647c.002-.215.013-.435-.114-.627a.7.7 0 0 1-.068-.19a.5.5 0 0 1 .026-.199c.077-.119.177-.197.331-.162q.172.007.345.02");
}

.gvavrsbsr {
  fill: var(--svg-color--230c0d, #230c0d);
  d: path("M19.493 36.791a.3.3 0 0 0-.006.141l-.111.178c-.133-.344-.067-.69-.04-1.039c.047.057.097.106.144.163c.147.183.147.369.013.557");
}

.gxbn1tb9g {
  fill: var(--svg-color--d20611, #d20611);
  d: path("M27.85 35.93h.574a.2.2 0 0 1 .082.136a.2.2 0 0 1-.082.139q-.285 0-.572.003q-.003-.142-.002-.278");
}

.gxj0jobrq {
  fill: var(--svg-color--8f0406, #8f0406);
  d: path("M20.913 35.2c1.725 0 3.446-.006 5.171.003c.254 0 .531-.081.756.122q-2.973 0-5.949-.003a1 1 0 0 0 .022-.122m2.024-.14q-1.01-.004-2.02-.004c.007-.098.011-.191.017-.289c.495.286 1.031.133 1.548.135c.353.002.294-.303.314-.533c.059-.73-.142-1.477.116-2.195c.035.027.069.061.103.09c.166.936.271 1.874-.078 2.796");
}

.gz7gz-uhc {
  fill: var(--svg-color--ad0007, #ad0007);
  d: path("M20.936 34.623c-.006-2.612-.011-5.23-.027-7.842c-.003-.272.107-.576-.123-.82q-.008-.14-.012-.282a.27.27 0 0 1 .188-.104a.4.4 0 0 1 .225.05q.086.09.093.217c-.002.087-.008.167-.012.253c-.018 2.539.004 5.074-.015 7.609c-.003.325.137.734-.317.919");
}

.h-6snheke {
  fill: var(--svg-color--630000, #630000);
  d: path("M31.03 49.48q-.215.02-.426.036q-.075-.001-.152-.006l.006-.148c.146-.142.314-.162.495-.071l.074.079q.004.055.003.11");
}

.h-lfwvb9e {
  fill: var(--svg-color--3f0a09, #3f0a09);
  d: path("M20.03 23.504c.041-.193-.092-.313-.18-.448q.17 0 .342.009c-.044.238.08.507-.13.717c-.021-.018-.044-.031-.069-.049c-.035-.085-.029-.162.037-.229");
}

.h0bj2gbwk {
  fill: var(--svg-color--feda4c, #feda4c);
  d: path("M29.18 40.554q-.004-.145-.003-.288a1 1 0 0 0 .111-.021l.019.034a.17.17 0 0 1 .069.127a.25.25 0 0 1-.06.136q-.064.05-.136.012");
}

.h0ur2slpr {
  fill: var(--svg-color--d6030b, #d6030b);
  d: path("M33.04 29.582c.656.107 1.168.363 1.17 1.143c-.346-.33-.585-.801-1.127-.887z");
}

.h28810b6w {
  fill: var(--svg-color--690002, #690002);
  d: path("M35.07 14.399L29 14.394q.002-.06-.003-.124q.656-.018 1.313-.034q.643-.012 1.293-.022l.869.015q.57.001 1.147.008a4.5 4.5 0 0 1 1.453-.006l-.002.029q.001.07-.004.139");
}

.h45czbcvh {
  fill: var(--svg-color--bb1619, #bb1619);
  d: path("M26.426 25.67q5.47.007 10.941.009q.017.068.027.136c.118.301-.043.367-.299.359c-.505-.27-1.052-.129-1.581-.158c-2.442 0-4.889 0-7.33.002c-.591-.031-1.197.076-1.76-.203z");
}

.h9sb79erx {
  fill: var(--svg-color--db000b, #db000b);
  d: path("M35.652 27.404c-.459.295-.967.121-1.45.133c-.499.011-.915.021-.888.688c.005.136-.143.172-.265.189c-.519.347-.647-.081-.823-.432c-.285.031-.156.678-.62.432c-.431-.006-.835.118-.925-.607c-.065-.512-.721-.158-1.099-.259q-.145.13-.288 0c-.217-.036-.549.099-.551-.274c-.006-.418.36-.299.592-.299c2.106-.009 4.212-.004 6.314-.004q.004.217.003.433");
}

.hekpsdx-s {
  fill: var(--svg-color--de000b, #de000b);
  d: path("M41.15 30.728a.75.75 0 0 0-.58-.577c.066-.396.389-.331.607-.266c.459.135.184.555.26.843z");
}

.hfee_5bdg {
  fill: var(--svg-color--af1820, #af1820);
  d: path("M31.03 13.39h-.578c-.104 0-.206-.007-.306-.009q.02-.062.037-.127c.272-.141.552-.086.833-.038l.179.042z");
}

.hg00h4bll {
  fill: var(--svg-color--cc0710, #cc0710);
  d: path("m23.513 24.368l.019-.313c.572.013 1.143.021 1.716.034c-.089.425-.435.256-.685.273c-.348.027-.699.006-1.05.006");
}

.hg8r0jchr {
  fill: var(--svg-color--b60911, #b60911);
  d: path("M36.657 34.782q.005-4.183.012-8.364c.032-.063.078-.081.144-.045l-.007.05c.298.325.188.728.207 1.103c.067 1.416-.168 2.832.005 4.25c.025.965-.111 1.938.086 2.902a.23.23 0 0 1-.008.236c-.161.004-.33.045-.439-.132");
}

.hj6nbo_9i {
  fill: var(--svg-color--830001, #830001);
  d: path("M34.77 22.489c.037.157-.029.378.229.415c.109-.01.135.065.149.151c-.546.362-1.134.222-1.715.124c-.132-.065-.175-.178-.159-.316c.316-.479.892-.129 1.275-.393a.22.22 0 0 1 .221.019");
}

.hov2xubwv {
  fill: var(--svg-color--d7020a, #d7020a);
  d: path("m25.537 26.394l.145-.147c.155.023.191.455.443.127q.286.028.568.052c.152.151.142.349.142.539q.008 1.87-.003 3.74c0 .21.06.48-.172.581c-.234.103-.395-.113-.542-.269c-.153-.159-.372-.214-.541-.344q-.11-.103-.04-.235c.02-.123.07-.283.194-.261c.919.13.843-.474.82-1.065c-.026-.684.082-1.381-.244-2.068c-.242.098-.476.287-.771.217c-.18-.193-.146-.385 0-.579z");
}

.hpnqq3b7u {
  fill: var(--svg-color--c10c1c, #c10c1c);
  d: path("M34.2 35.93c.66-.303 1.356-.065 2.034-.149c.115.001.225.026.291.136l-.098.092c-.745.064-1.493.186-2.226-.074zm3.03.28l-.714-.005q-.126-.135-.001-.271l.015-.018c.27.019.562-.028.7.294");
}

.hriyr6bzv {
  fill: var(--svg-color--b39422, #b39422);
  d: path("M31.457 51.26a.6.6 0 0 1 .043-.129c.221-.104.439-.162.653.009c.096.167.163.331-.027.482c-.23.089-.453.086-.651-.083c-.007-.092-.01-.186-.018-.279");
}

.hswaiuy7l {
  fill: var(--svg-color--3c2524, #3c2524);
  d: path("m19.329 24.657l.155-.007c.24-.133.467-.224.572.148l-.02.008c-.234-.053-.526.159-.707-.149");
}

.ht3tlvjxq {
  fill: var(--svg-color--5a0000, #5a0000);
  d: path("M35.652 26.373q-4.047.005-8.093.012v-.26c.19-.017.387-.028.579-.044c2.505-.083 5.01-.077 7.52-.002l-.014.046z");
}

.hw5uz3bis {
  fill: var(--svg-color--383006, #383006);
  d: path("M30.02 35.07q-.02.14-.034.274c-.151-.122-.116-.292-.114-.452c.05.058.098.12.148.178");
}

.hw8l-sw0s {
  fill: var(--svg-color--bf060b, #bf060b);
  d: path("M19.498 23.06q.053-.065.118-.005a.6.6 0 0 1 .165.383c.014.104.019.209.024.316c-.018.213.196.392.094.619c-.188.124-.363.162-.494-.078c.036-.409-.111-.837.093-1.235");
}

.hwbt4vn1p {
  fill: var(--svg-color--e9cb2c, #e9cb2c);
  d: path("M31.614 41.688c.147-.045.294-.082.441-.125l.295.158l-.192.266l-.261.179c-.07.073-.133.155-.249.142c-.143-.076-.172-.205-.174-.352c.011-.11.048-.202.14-.268");
}

.hx6xn49ae {
  fill: var(--svg-color--df010a, #df010a);
  d: path("M24.09 30.432c-.098 0-.194.006-.289.006c-.074-.043-.196-.072-.209-.129c-.025-.105.087-.141.18-.149c.193-.014.304.074.318.272");
}

.hyoie0_jn {
  fill: var(--svg-color--ebce2f, #ebce2f);
  d: path("m32.9 39.557l-.148.291a.35.35 0 0 1-.273.097a.6.6 0 0 1-.188-.065c-.092-.096-.201-.188-.092-.337l.3-.159c.172-.032.272.103.401.173");
}

.i_vr7kyhk {
  fill: var(--svg-color--db0215, #db0215);
  d: path("M21.777 36.24c.175.157.35.261.62.195c.311-.071.224.201.248.364q-.503-.005-1.01-.006c-.158-.195-.638-.144-.462-.598c.124-.111.272-.115.423-.09a.3.3 0 0 1 .18.135");
}

.i-gm8u2mi {
  fill: var(--svg-color--a91c24, #a91c24);
  d: path("M26.67 15.545q.006.075.01.152c-.377-.061-.787.142-1.143-.135c.379-.004.756-.013 1.133-.017");
}

.i-q29tbik {
  fill: var(--svg-color--560001, #560001);
  d: path("m40.834 35.04l.021.169c-1.055.147-2.112.053-3.167.049q-.085.004-.171.004c-.238.009-.475.025-.68.174a.6.6 0 0 1-.213.01a.37.37 0 0 1-.176-.116c-.093-.212-.098-.407.093-.576c.148-.069.325-.003.476-.082c.157-.122.297-.349.511-.083c.155.285.423.273.692.275c.62.006 1.242-.004 1.865.006c.261.001.53-.024.749.17");
}

.i01247b5r {
  fill: var(--svg-color--832106, #832106);
  d: path("m30.568 41.585l.444.012a.5.5 0 0 0 .019.099l-.002.295c-.276.003-.338-.237-.461-.406");
}

.i0m0ggbwg {
  fill: var(--svg-color--988202, #988202);
  d: path("M31.3 49.557c.007.369.01.739.018 1.109a.5.5 0 0 0-.111.043a.3.3 0 0 1-.035-.067c-.232-.269-.183-.581-.15-.892a.6.6 0 0 1 .096-.209q.1-.104.182.016");
}

.i1ciwlqff {
  fill: var(--svg-color--6c0000, #6c0000);
  d: path("M21.483 14.924c.292.303.104.689.175 1.028l-.162.174c-.095-.4-.07-.804-.013-1.202");
}

.i5dsufikf {
  fill: var(--svg-color--883e38, #883e38);
  d: path("M31.602 38.12q.363-.016.726-.036q.069.085.13.17l-.279-.002c-.185.136-.367.151-.551 0q-.014-.065-.026-.132");
}

.i5k3xscit {
  fill: var(--svg-color--d70211, #d70211);
  d: path("M30.592 14.83c.364-.223.79.053 1.159-.141c.145.111.314.212.145.432q-1.446 0-2.89-.002v-.289c.356-.316.767-.223 1.175-.146c.15.007.298.033.411.146");
}

.i9cqz6alm {
  fill: var(--svg-color--d7020b, #d7020b);
  d: path("m26.693 24.949l-.002.289c-.203.18-.403.115-.607-.004c-.054-.389-.086-.778.023-1.166c0-.041 0-.087.006-.128c.092-.201.102-.44.294-.591c.335.143.281.448.299.723c-.175.092-.029.197-.013.296c.194.193-.109.387 0 .581");
}

.iag7e_bgz {
  fill: var(--svg-color--09030e, #09030e);
  d: path("M33.34 34.918c-.063.115-.168.139-.289.143q.03-.222.055-.445c.158.04.164.194.234.302");
}

.iba_bccdw {
  fill: var(--svg-color--d6020c, #d6020c);
  d: path("M36.817 31.887q-.003-2.73-.012-5.464q.435-.019.862-.043l.007.299h-.289q-.282.292 0 .583v.286c-.256.347-.1.746-.145 1.12c-.048.396.114.82-.144 1.191c.154.471-.327 1.067.288 1.443c.058-.046.111-.046.165.011c-.057.093-.108.186-.162.278c-.126.135-.066.383-.271.473c-.157.04-.228-.07-.299-.177");
}

.ibwyqn10s {
  fill: var(--svg-color--db0011, #db0011);
  d: path("M24.381 26.679c-.154-.019-.287-.072-.264-.261c.029-.191.166-.285.348-.306c.429-.044.66.188.784.566c.143.196.175.388 0 .581h-.292c-.19-.145-.089-.438-.287-.581z");
}

.ieg15ac5g {
  fill: var(--svg-color--2c0404, #2c0404);
  d: path("M23.997 20.06c.421.092.933-.282 1.265.252h-1.277a.2.2 0 0 1-.073.018c-.048-.114-.056-.215.085-.27");
}

.if1xngbwu {
  fill: var(--svg-color--c60c14, #c60c14);
  d: path("m37.39 17.17l-.006 4.598q.326.431.003.864c-.089-.002-.184-.004-.271-.011q-.004-2.725-.004-5.456q.138.004.278.005");
}

.if943jozz {
  fill: var(--svg-color--d9010a, #d9010a);
  d: path("M25.419 15.13q-.01.066-.015.129a.23.23 0 0 1 .035.213a.66.66 0 0 1-.199.275c-.372.146-.743.125-1.12.021c-.094-.08-.116-.18-.098-.297c.22-.288.583-.352.86-.548a.6.6 0 0 1 .207-.025c.14.037.261.097.33.232");
}

.ifb7m6bhm {
  fill: var(--svg-color--ca0d16, #ca0d16);
  d: path("M28.426 36.08c.48.059.98-.143 1.44.131l-1.442-.003z");
}

.ihqmntbmn {
  fill: var(--svg-color--c50713, #c50713);
  d: path("M40.29 22.345c-.023-.683.072-1.384-.31-2.01c.016-.26.173-.169.284-.096c.247.162.419.387.47.691c.061.484-.064.998.194 1.459c-.01.257-.103.396-.378.257q-.13-.151-.26-.298");
}

.iiqrshb-w {
  fill: var(--svg-color--be070f, #be070f);
  d: path("m37.813 25.23l-.073.003l-.071-.008v-1.997c.315.649.081 1.338.144 2");
}

.ijshzb44u {
  fill: var(--svg-color--de0013, #de0013);
  d: path("M32.762 28.704h.288c.378.036.228.245.146.433c-.184-.105-.429-.149-.434-.433");
}

.ijt5tubbc {
  fill: var(--svg-color--ad0008, #ad0008);
  d: path("M42.605 25.805a10 10 0 0 0 .272-.137l-.025 8.811c-.452-.152-.313-.549-.313-.848c-.021-2.134-.009-4.264-.013-6.396c0-.313.013-.625-.027-.935a.64.64 0 0 1 .018-.396q.047-.05.088-.099");
}

.ilj3m0b7d {
  fill: var(--svg-color--b71120, #b71120);
  d: path("M36.806 35.34c.1.004.199.013.3.018l-.018.295c-.196-.019-.344-.104-.413-.295q.064-.011.131-.018");
}

.imd8vf0xg {
  fill: var(--svg-color--d20815, #d20815);
  d: path("M20.625 36.36q-.364.146-.723.287c-.166-.093-.143-.257-.146-.405l.869-.013z");
}

.imijv2bmd {
  fill: var(--svg-color--690304, #690304);
  d: path("M26.11 25.67h.275q.036.02.077.04q.066.058.125.12c.126.131.338.127.444.287c.031.096.026.186-.053.26l-.004.049a.7.7 0 0 1-.333.135c-.212.014-.417-.006-.58-.16c-.124-.201-.11-.396.027-.586q.013-.069.022-.145");
}

.ip5wdebhp {
  fill: var(--svg-color--553804, #553804);
  d: path("m32.18 42.868l-.074-.007l-.065.016a.42.42 0 0 1-.383.101a.6.6 0 0 1-.173-.103l-.057-.014c.057-.183.021-.435.325-.432c.046-.07.093-.074.142-.003c.298.017.295.227.285.442");
}

.iqjxv8b5o {
  fill: var(--svg-color--820000, #820000);
  d: path("M19.758 36.946h2.02q.004.057.003.117c-.674-.029-1.363.164-2.023-.117");
}

.ir2sr-b2y {
  fill: var(--svg-color--aca774, #aca774);
  d: path("M31.605 37.2q0-.055.01-.108a1 1 0 0 1 .131-.012c-.011.08-.043.137-.141.12");
}

.itcv-fdln {
  fill: var(--svg-color--e4000f, #e4000f);
  d: path("M34.785 31.02q.297.022.277.321c-.01.177-.124.236-.277.254c.05-.194-.262-.383 0-.575");
}

.itkcc7bmu {
  fill: var(--svg-color--d10612, #d10612);
  d: path("M43.89 36.2q.069.015.138.034q.143.186-.033.344c-.536.239-1.104.084-1.654.13c-.848.088-1.695.018-2.54-.004c-.404.021-.819-.081-1.208.111c-.07.048-.138.039-.196-.02q-.141-.085-.284-.168a.15.15 0 0 1-.047-.146c.041-.103.092-.197.199-.243z");
}

.iu069b9cz {
  fill: var(--svg-color--cb0514, #cb0514);
  d: path("M28.14 25.959v-.145h7.514q.062.157-.082.237c-.271.138-.563.108-.851.108q-2.81.007-5.62 0c-.33-.001-.679.052-.961-.2");
}

.iwgzh48hb {
  fill: var(--svg-color--8e791f, #8e791f);
  d: path("M30.29 35.1q.07-.001.135.025l.077.222l-.049.304c-.057-.007-.108-.021-.163-.03a.6.6 0 0 1-.092-.357a.4.4 0 0 1 .092-.164");
}

.iyq6l_bih {
  fill: var(--svg-color--c40a14, #c40a14);
  d: path("m23.485 23.5l.051.551c-.083.105-.187.115-.304.072a.4.4 0 0 1-.14-.305a.5.5 0 0 1 .126-.313l.002-.278c.089.093.178.181.265.273");
}

.j-x3kacbz {
  fill: var(--svg-color--e2b76c, #e2b76c);
  d: path("M30.445 50.37q-.504.01-1.01.014a4 4 0 0 1-.139-.134l1.156.002a1 1 0 0 1-.009.118");
}

.j08v0mbfg {
  fill: var(--svg-color--510e02, #510e02);
  d: path("M28.429 50.954v-.294l.104-.057q.059-.008.115-.012c.824.044 1.646.037 2.469 0q.126 0 .23.061c.129.191.138.381-.019.558c-.267-.316-.636-.245-.985-.247c-.636-.006-1.274-.004-1.914-.009");
}

.j0uqeubgi {
  fill: var(--svg-color--db0010, #db0010);
  d: path("M34.35 25.09c-.289-.357-.079-.771-.143-1.158c.115-.125.239-.238.433-.143c.002.117.031.229.145.289v.288q.225.289 0 .579c-.163.006-.329-.025-.435.145");
}

.j23nzubtb {
  fill: var(--svg-color--432a2a, #432a2a);
  d: path("M39.829 14.841q.001-.086.005-.172c.041-.166.167-.132.287-.122c.156.198.048.43.079.643a.4.4 0 0 1-.038.221a.23.23 0 0 1-.215.028c-.218-.164-.275-.361-.118-.598");
}

.j4jtnedre {
  fill: var(--svg-color--542107, #542107);
  d: path("M32.06 39.516c-.098.184-.279.166-.446.184q-.073-.047-.054-.104q.015-.06.04-.061q0-.055.004-.115c.169-.041.334-.079.456.096");
}

.j6k3xg4kg {
  fill: var(--svg-color--ca0816, #ca0816);
  d: path("M32.04 38.555q-.204-.022-.41-.047l-.001-.256h.551c.004.123-.03.23-.14.303");
}

.j8octebpz {
  fill: var(--svg-color--b6a663, #b6a663);
  d: path("M31.625 48.644v.147q-.072.072-.14.143l-.003-1.453c.035.002.071.008.107.008c.1.069.14.17.152.286c.004.077.007.149.007.226c-.006.22.032.448-.123.643");
}

.ja377gbsb {
  fill: var(--svg-color--eed223, #eed223);
  d: path("M30.02 40.542c-.093.163-.319.235-.302.466a.4.4 0 0 0-.115-.024a.5.5 0 0 0-.049-.128a1 1 0 0 0 .016-.123a1 1 0 0 1-.085-.152a.36.36 0 0 1-.002-.172a.35.35 0 0 1 .101-.141q.224 0 .452.003c.069.096.069.185-.016.271");
}

.je32rhciw {
  fill: var(--svg-color--e3bc6b, #e3bc6b);
  d: path("M28.729 47.791v.898q-.077.047-.15.094c.008-.334.02-.67.023-1a1 1 0 0 1 .127.012");
}

.jelrlroke {
  fill: var(--svg-color--d5020f, #d5020f);
  d: path("M40.87 32.445c.132-.791-.524-1.168-.894-1.697c-.078-.105-.078-.209.01-.311l.289.002c.303.053.559.301.896.203a.29.29 0 0 1 .26.085c-.158.567-.387 1.128-.292 1.739q-.069.097-.146.008a1 1 0 0 1-.123-.029");
}

.jfbcvn-0g {
  fill: var(--svg-color--aa2224, #aa2224);
  d: path("M42.862 34.9c-.33.078-.653.293-.995.041c-.075-.159.033-.218.144-.281a.56.56 0 0 1 .575.111l.25.002q.032.06.026.127");
}

.ji0yv8blg {
  fill: var(--svg-color--d30303, #d30303);
  d: path("M36.23 27.26c-.119.004-.227.029-.286.145c-.087.084-.187.089-.294.041c-.115-.113-.121-.249-.068-.394q.036-.042.072-.079h.572q.005.141.004.287");
}

.jj_2vm05h {
  fill: var(--svg-color--4a2906, #4a2906);
  d: path("M32.483 39.955c-.101.012-.157.061-.149.17c-.104-.016-.126.048-.131.13c-.246-.046-.487-.095-.733-.143q-.007-.076-.016-.147l.073-.061a.5.5 0 0 1 .17-.068c.209-.018.418-.106.63-.008l.158.039a.3.3 0 0 1-.002.088");
}

.jlhuqexav {
  fill: var(--svg-color--65260e, #65260e);
  d: path("M30.18 40.693q.064-.078.128-.148c.216-.15.322-.003.422.16l.594.449q.011.042.016.088l-.042.047a.34.34 0 0 1-.28.092c-.256-.037-.407-.225-.567-.4z");
}

.jm8i941_w {
  fill: var(--svg-color--d4030a, #d4030a);
  d: path("M36.23 30.438q-.278.01-.282.29c.138.475-.193.429-.46.386c-.225-.035-.418-.189-.631-.271a.4.4 0 0 1-.152-.158c-.102-.375-.018-.605.431-.609c.454-.006.61-.293.621-.714c.017-.667-.032-1.34.095-2c.098-.145.215-.222.383-.1q-.006 1.587-.005 3.179");
}

.jngu3qb_w {
  fill: var(--svg-color--d4030a, #d4030a);
  d: path("M34.785 31.882h-.279c-.044-.308-.026-.634-.3-.862l.002-.292c.19-.177.386-.144.577 0c.075.067.1.153.1.251c-.036.222.045.436.033.654a.37.37 0 0 1-.133.249");
}

.jnvm-9o9g {
  fill: var(--svg-color--be1118, #be1118);
  d: path("M20.936 34.623c.206-.227.118-.501.118-.753c.009-2.44.002-4.877.009-7.315c0-.249-.1-.53.138-.74q.047.046.093.096c.211.549.059 1.125.118 1.685c.031 2.02 0 4.03.018 6.05c.005.396-.069.868.541.915c.45.002.456-.324.47-.639c.019-.565-.023-1.134.023-1.701a.7.7 0 0 1 .146-.344q.179-.121.361.004a.53.53 0 0 1 .063.385c-.074.574-.032 1.151-.038 1.732c-.019 1.021-.145 1.146-1.187 1.121c-.332-.008-.692.043-.875-.348q.003-.071.002-.145");
}

.joakf_7xh {
  fill: var(--svg-color--4f070a, #4f070a);
  d: path("m35.21 15.369l.004-.049c-.02-.219-.039-.436-.109-.643a1.2 1.2 0 0 1-.081-.274a.28.28 0 0 1 .07-.175c.091-.054.177-.064.267.006q.083.086.165.174c-.252.272.235.789-.316.961");
}

.jomn98bbx {
  fill: var(--svg-color--ac0c15, #ac0c15);
  d: path("m33.378 23.08l1.77-.022l.01.002c.282.214.021.555.188.797a.18.18 0 0 1 .032.199c-.203.174-.322.057-.422-.122c-.048-.388-.235-.587-.656-.537a2.6 2.6 0 0 1-.634-.012a.6.6 0 0 1-.302-.119c-.063-.069-.055-.131.014-.186");
}

.joyj03urz {
  fill: var(--svg-color--e0010b, #e0010b);
  d: path("M40.564 20.9c.098-.095.191-.191.289-.285l.003.285q0 .724-.003 1.444c-.609-.377-.134-.972-.289-1.444");
}

.jrdswybwx {
  fill: var(--svg-color--500, #500);
  d: path("M33.925 13.657c.338-.046.702.157 1.014-.114c.296.01.196.188.154.348c-.36.344-.759.328-1.179.119c-.082-.119-.084-.24.011-.353");
}

.juaf769bz {
  fill: var(--svg-color--c9060b, #c9060b);
  d: path("m32.475 13.967l.014-.133l.129-.027q.092.024.173.059c.243.057.552-.086.694.244q.077.004.15.004q.059.136-.065.223c-.384.136-.758.217-1.095-.107z");
}

.jv8yrcbwz {
  fill: var(--svg-color--951008, #951008);
  d: path("M32.33 39.828c-.224.162-.478.148-.733.137c-.069-.096-.063-.193-.013-.293c.14-.121.314-.13.484-.156q.07.01.134.026z");
}

.jvt_9515y {
  fill: var(--svg-color--260205, #260205);
  d: path("M23.08 32.17c.071.958-.15 1.932.158 2.879l-.3.014l.026-2.893q.057.003.116 0");
}

.jvz-3lb7q {
  fill: var(--svg-color--d5020b, #d5020b);
  d: path("m29.3 22.345l-.002-.577c.221-.383.215-.77.002-1.154v-1.445c.693-.314.932.219 1.227.652c-.282.47-.2.994-.224 1.504c-.019.344.104.711-.14 1.025c-.289.187-.577.192-.863-.005");
}

.jw41o-b6w {
  fill: var(--svg-color--d9010c, #d9010c);
  d: path("M24.381 26.679c.064.488-.226.758-.605.543c-.656-.369-1.328-.197-1.995-.251c-.268-.078-.126.256-.29.289c-.004.184-.098.283-.283.288c0-.577 0-1.15.003-1.727h4.327a.67.67 0 0 1 .17.54a.66.66 0 0 1-.114.319c-.088.075-.19.097-.302.075c-.2-.072-.3-.289-.49-.371c-.293-.128-.448-.036-.421.295");
}

.jy7xe___z {
  fill: var(--svg-color--6b0000, #6b0000);
  d: path("m26.851 24.05l-.005-1.046c.354.175.164.474.168.729a10 10 0 0 0-.029.326c-.049.051-.094.051-.134-.009");
}

.k_4vrl_xk {
  fill: var(--svg-color--2a130a, #2a130a);
  d: path("M28.845 22.489v-6.968c.349.051.05.336.17.467c.175.193.19.432.19.672c-.009 1.934.04 3.867-.025 5.8c-.029.139-.083.263-.211.333c-.113.005-.155-.045-.121-.158q0-.07-.003-.146");
}

.k-6xh9_5s {
  fill: var(--svg-color--781b0a, #781b0a);
  d: path("M31.457 41.28c.298-.024.595-.236.892-.002l-.293.287c-.06.344-.32.137-.488.182a.55.55 0 0 1-.297-.374c.008-.034.011-.067.019-.102q.087-.076.167.009");
}

.k-zfkfbxx {
  fill: var(--svg-color--700000, #700000);
  d: path("M27.415 35.36q.079-.007.159-.011c.25-.258.571-.055.85-.126q.148-.028.303-.037q.156-.01.314.01c.107.02.206.057.288.133c.053.107.053.208-.029.301q-.727 0-1.456.003a28 28 0 0 0-.429-.273");
}

.k35_wbc8a {
  fill: var(--svg-color--580000, #580000);
  d: path("M33.05 37.525c1.684-.002 3.363-.002 5.05-.007c-.015.172-.146.155-.258.155q-2.395-.015-4.788-.025c-.05-.031-.063-.057-.048-.086q.025-.036.049-.037");
}

.k6vmrac5i {
  fill: var(--svg-color--d9010b, #d9010b);
  d: path("M42.3 32.459c-.072.775.201 1.594-.293 2.314l-.141.168l-.174-.017a1 1 0 0 1-.128-.239c-.084-.847-.06-1.686.155-2.512z");
}

.k70n8q8ay {
  fill: var(--svg-color--620101, #620101);
  d: path("m27.27 35.35l.144-.002c.033-.005.07-.005.103-.007c.169.07.508.024.268.378a.44.44 0 0 1-.507-.072c-.117-.066-.146-.175-.143-.299z");
}

.k9d8hobph {
  fill: var(--svg-color--500, #500);
  d: path("M32.33 13.673q.067.068.133.14c-.369.227-.721.372-.996-.127l-.004-.013z");
}

.k9njirbsh {
  fill: var(--svg-color--c90914, #c90914);
  d: path("M38.834 14.84c-.004.139-.004.283-.004.424l-.286.005l-.004-.446c.1.003.196.013.294.017");
}

.kagyvlsex {
  fill: var(--svg-color--b1100f, #b1100f);
  d: path("M30.734 40.705q-.21-.084-.424-.16a.414.414 0 0 1 .431-.274q-.002.213-.007.434");
}

.kgmxt1x-h {
  fill: var(--svg-color--6d0000, #6d0000);
  d: path("M43.45 24.942c-.722-.272-1.458 0-2.195-.059c-1.036-.085-2.095.038-3.143.072c0-.126.032-.235.148-.303c.279-.251.625-.208.952-.192q1.745.064 3.489.057c.261 0 .519.024.759.148a7 7 0 0 0-.01.277");
}

.khge7qbnx {
  fill: var(--svg-color--d6030b, #d6030b);
  d: path("M31.606 28.414c.308-.031.285-.264.289-.479c.005-.212.056-.386.319-.364c.228.016.266.186.251.359c-.037.453.235.514.584.484v.29c-.095.077-.192.088-.288 0c-.378-.124-.892.289-1.155-.29");
}

.kj4av0bxn {
  fill: var(--svg-color--cc070f, #cc070f);
  d: path("M43.03 35.494c.051.14.149.232.284.291c-.207.247-.491.131-.741.138c-1.442.019-2.884.023-4.325.032a.65.65 0 0 1-.276.123a1.5 1.5 0 0 1-.312.008a1 1 0 0 1-.307-.072c-.171-.084-.313-.186-.361-.385a.43.43 0 0 1 .08-.32c.157-.127.345-.18.546-.205a1 1 0 0 1 .247.025c1.373.049 2.75.008 4.125.018c.307.014.626-.029.888.193z");
}

.kk1w0quob {
  fill: var(--svg-color--0b0703, #0b0703);
  d: path("M33.48 35.37c-.094.009-.189.01-.285.016q-.073-.02-.147-.038c-.011-.097-.156-.194.003-.288c.078-.09.168-.146.289-.143c.104.049.208.103.311.154c.039.157-.039.244-.171.299");
}

.ko1gguciw {
  fill: var(--svg-color--560303, #560303);
  d: path("M27.28 14.666q-.005.074-.013.151a.46.46 0 0 1-.187.13c-.164.043-.302-.014-.427-.111a4 4 0 0 0-.101-.256c.253-.043.513-.167.728.086");
}

.kqxa16b_w {
  fill: var(--svg-color--b69222, #b69222);
  d: path("m31.16 49.676l-.063-.014l-.064.005l-.302-.011c-.044-.044-.081-.086-.126-.135q.196-.2.426-.036l.138.062a1 1 0 0 1-.009.129");
}

.kt0jcdbor {
  fill: var(--svg-color--c2030f, #c2030f);
  d: path("M22.664 17.16a.3.3 0 0 1 .13.007c.151.143.188.33.191.526c.007 1.456.093 2.917-.194 4.361h-.121z");
}

.ktevhqr1i {
  fill: var(--svg-color--cf0411, #cf0411);
  d: path("M23.984 20.314c-.743.537-.388 1.344-.49 2.035q-.131.145-.265.285c-.334.188-.406-.123-.554-.288q-.002-.144-.006-.287a.3.3 0 0 1 .124-.089c.046-.283-.068-.586.095-.857c.24-.373.123-1.1.916-.918c.073.02.133.065.18.119");
}

.kvxcsp9iv {
  fill: var(--svg-color--320304, #320304);
  d: path("M24.1 30.748c-.131.33-.338.561-.725.559c.021-.287.367-.323.438-.57z");
}

.kxvm-sb1h {
  fill: var(--svg-color--0d0303, #0d0303);
  d: path("M30.88 30.983c.11-.017.142.046.126.11c-.016.057-.057.127-.104.145c-.07.025-.132-.029-.112-.11c.011-.057.064-.103.09-.145");
}

.ky10skl3y {
  fill: var(--svg-color--690301, #690301);
  d: path("M32.2 49.799h.118l-.002 2c-.144.004-.283.012-.429.016l.287-.291q-.064-.213-.128-.419c-.022-.112-.054-.224-.056-.337c.033-.334-.099-.701.21-.973");
}

.l7lf1ha2e {
  fill: var(--svg-color--665706, #665706);
  d: path("M31.19 36.08q-.08-.004-.157-.013q-.15-.12-.295-.241l.006-.09a.4.4 0 0 1 .107-.25a.23.23 0 0 1 .182-.025c.213.098.389.24.488.462a.24.24 0 0 1-.051.184c-.1.042-.196.051-.28-.027");
}

.l99cz7ube {
  fill: var(--svg-color--a00101, #a00101);
  d: path("m37.38 25.536l-.018.143c-.26.243-.584.192-.892.192q-4.578.006-9.159 0c-.309 0-.635.047-.889-.201h-.037a1 1 0 0 0 .019-.143l.11-.09c.281-.09.57-.059.856-.053c2.706.039 5.408-.157 8.112-.006c.635.036 1.292-.228 1.898.158");
}

.l9inc97hz {
  fill: var(--svg-color--c2b153, #c2b153);
  d: path("M31.468 37.22v-.107a.4.4 0 0 1 .138-.021l.01.01l.039.059l-.049.05l-.068.017z");
}

.lb6fpbb2k {
  fill: var(--svg-color--420000, #420000);
  d: path("m31.609 35.934l-.008-.143q.079.057.151.114z");
}

.le-3xokhl {
  fill: var(--svg-color--ba0610, #ba0610);
  d: path("M25.84 20.758c.559.551.158 1.252.277 1.863c-.368-.476.068-1.092-.271-1.576a7 7 0 0 1-.006-.287");
}

.lim2n0fud {
  fill: var(--svg-color--2c1100, #2c1100);
  d: path("M31.605 39.535c.004.059.01.109.014.164l-.025.266c-.041 0-.088 0-.129.007a.4.4 0 0 0-.011-.132c.014-.119.018-.244.151-.305");
}

.lke2-u8_o {
  fill: var(--svg-color--454016, #454016);
  d: path("m31.743 37.659l.149.151c-.074.167-.198.261-.391.242a.4.4 0 0 1-.168-.094c-.029-.124-.02-.264-.17-.32l.006-.135c.061-.117.146-.186.284-.168c.147.065.176.229.29.324");
}

.lkjt6cc8y {
  fill: var(--svg-color--870001, #870001);
  d: path("m25.537 15.563l-.282-.02l.153-.131q.625-.004 1.254-.006l.064.093q-.038.122-.167.122c-.34-.024-.686.072-1.022-.058");
}

.llbwg9bnd {
  fill: var(--svg-color--d6030b, #d6030b);
  d: path("m32.18 29.587l-.57-.003c-.256.17-.527.162-.804.062c-.288-.299-.038-.468.169-.618c.242-.177.554-.287.788-.086c.128.113.122.273.386.201c.307-.088.661-.111.942.143a.31.31 0 0 1-.069.331c-.288.174-.565.049-.842-.03");
}

.lm8dp-8nv {
  fill: var(--svg-color--b80a12, #b80a12);
  d: path("M39.988 15.547q.576.003 1.153.002c-.385.228-.769.237-1.153-.002");
}

.lo--nvb5j {
  fill: var(--svg-color--160304, #160304);
  d: path("M26.443 32.17a.4.4 0 0 0-.021.123c-.01.639-.063 1.285-.01 1.924c.059.699-.18.973-.875.824c.593-.12.811-.475.73-1.07a5 5 0 0 1-.004-1.079c.071-.754-.311-1.317-.734-1.865c.077-.098.181-.127.299-.118c.374.096.52.412.682.713a.58.58 0 0 1-.067.548");
}

.louwefush {
  fill: var(--svg-color--ce050b, #ce050b);
  d: path("m41.15 15.426l.094-.155h.058c.302.04.493.278.742.419c.043.104.045.197-.052.273c-.771.002-1.537.008-2.307.012c-.831-.197-.953-.441-.566-1.135l.706.001a.83.83 0 0 0 .175.556a.35.35 0 0 0 .135.125c.284.053.571.05.858.005a1 1 0 0 0 .157-.101");
}

.lrlk_ccty {
  fill: var(--svg-color--b60911, #b60911);
  d: path("m37.1 32.03l.293-.435q-.015.292-.025.582q-.131.147-.264.289c-.13-.142-.123-.288-.004-.436");
}

.lujgmtbvr {
  fill: var(--svg-color--1c1000, #1c1000);
  d: path("M31.755 42.3c.003-.092.042-.146.143-.13l-.006.13q-.078.066-.146-.015z");
}

.luxx1mbrn {
  fill: var(--svg-color--5b0003, #5b0003);
  d: path("m43.08 25.557l-.206-.178c.19-.209.38-.291.575-.006q.073.069.146.129q-.255.029-.515.055");
}

.lv1nzibnm {
  fill: var(--svg-color--040101, #040101);
  d: path("m30.737 20.04l.024-.281c.268-.027.408-.328.695-.313c.282-.221.608-.188.935-.165c.298.045.535.169.631.479l.031.273c.045 1-.065 2.01.071 3.01c.064.436-.105.854-.731.759c-.306-.044-.622-.005-.935-.007c-.645-.006-.971-.324-.833-.967c.201-.928.057-1.858.112-2.786");
}

.lxtf-9yqo {
  fill: var(--svg-color--ae0914, #ae0914);
  d: path("m29.583 15.711l-.423.002c.033-.033.063-.096.097-.1a50 50 0 0 1 5.134-.006c.035.003.07.057.104.09l-.012.018c-.672.375-1.403.146-2.104.189c-.71.043-1.426.029-2.144-.005c-.235.001-.464-.022-.652-.188");
}

.m_2bxabsn {
  fill: var(--svg-color--c8060d, #c8060d);
  d: path("M31.57 18.89c-.431-.134-.173-.695-.534-.874q-.125-.148-.003-.294c.441-.096.245-.448.279-.7c.043-.318-.101-.688.28-.895a.44.44 0 0 1 .15.202c.106.79.118 1.581-.005 2.374a.37.37 0 0 1-.167.187");
}

.m_mm-84od {
  fill: var(--svg-color--d80209, #d80209);
  d: path("M34.785 24.947v-.579l.579.003q.228.285 0 .576z");
}

.m-arvaqoo {
  fill: var(--svg-color--dc010f, #dc010f);
  d: path("M27.56 24.371v.576l-.866.002c-.888-.194.285-.389 0-.581z");
}

.m7oslx4zt {
  fill: var(--svg-color--840001, #840001);
  d: path("M37.1 15.535q.003-.07.014-.139a108 108 0 0 1 1.138-.006q.07.016.143.021c-.398.409-.853.202-1.295.124");
}

.m9_32yblg {
  fill: var(--svg-color--c30a19, #c30a19);
  d: path("M26.56 36.22c-.003-.098-.003-.193-.008-.289l-.006.004c.165-.153.38-.143.579-.186c.25-.01.502-.022.724.134a.3.3 0 0 1 .039.343c-.236.219-.525.113-.795.141c-.116 0-.23-.002-.345-.021a.4.4 0 0 1-.188-.126");
}

.maml8gy7b {
  fill: var(--svg-color--331600, #331600);
  d: path("m31.01 39.805l.005-.401q.067-.005.138-.004l.053-.013c.063.09.101.188.101.3a.5.5 0 0 1-.061.201c-.125.099-.244.188-.236-.083");
}

.mbcdsacyp {
  fill: var(--svg-color--690304, #690304);
  d: path("M25.971 25.25a2 2 0 0 1 .15-.023c.193.003.38.008.57.014q2.096-.006 4.19-.008c.202-.213.475-.233.732-.213c.912.067 1.854-.232 2.734.213q.795 0 1.591.004c.264-.162.518-.224.75.055c-.183.304-.482.152-.716.152c-2.934.013-5.863.008-8.793.013c-.258 0-.53-.077-.773.075v-.002z");
}

.mcp-kkbib {
  fill: var(--svg-color--fdd93d, #fdd93d);
  d: path("M32.02 43.31c.006 2.501.014 5 .019 7.507q-.146-.012-.289-.021q.003-.06.002-.125c.129-.673.11-1.345-.002-2.02a1 1 0 0 1-.05-.262c.079-1.502.039-3.01.058-4.515c.004-.214-.09-.501.262-.566");
}

.mipdsybyn {
  fill: var(--svg-color--290800, #290800);
  d: path("m31.426 42.861l-.101.002l-.03-.712c-.04-.126.03-.183.135-.222a.18.18 0 0 1 .164.086c.012.12-.02.258.161.279l.048.075a.35.35 0 0 1-.061.171c-.096.118-.154.273-.316.321");
}

.mlekpl8kk {
  fill: var(--svg-color--e9d142, #e9d142);
  d: path("M31.468 38.977q.076-.078.147-.157c.171-.095.289-.097.28.15c.13.5-.28.192-.428.286z");
}

.mn-eth-vv {
  fill: var(--svg-color--dfbe3b, #dfbe3b);
  d: path("M33.48 39.832c-.126.064-.145.184-.157.309q-.215-.068-.43-.133c-.118.016-.179-.053-.204-.156c-.002-.152.074-.244.211-.295l.142-.033a.15.15 0 0 0 .109.029c.168.025.387-.014.329.279");
}

.mn13xsb2c {
  fill: var(--svg-color--c9b16f, #c9b16f);
  d: path("M30.601 35.77v-.408c.181-.129.29-.086.324.137a.2.2 0 0 0-.093.012c-.024.085-.018.184-.091.254l-.007.061z");
}

.mofw0acui {
  fill: var(--svg-color--b3151a, #b3151a);
  d: path("M20.333 24.513q-.416 0-.835-.007a.22.22 0 0 1-.005-.139c.153-.001.313.021.409-.14h.144q.145.143.287.286");
}

.mp5hlty4t {
  fill: var(--svg-color--d9000e, #d9000e);
  d: path("M34.785 30.728h-.577l-.002-.003c-.146-.631-.694-.853-1.17-1.143l-.009.009l.022-.308q.075-.077.146-.146c-.039-.195-.186-.345-.234-.539a.7.7 0 0 1 .055-.326c.175-.721.641-1 1.363-.93c.423.038.854-.055 1.273.063l.29-.002c0 .713-.05 1.429.015 2.139c.055.625-.502.854-.757.77c-.602-.196-.358.208-.415.416");
}

.mq_jmtbfr {
  fill: var(--svg-color--66080a, #66080a);
  d: path("M21.49 16.273q.005-.075.006-.147c.068-.086.107-.19.184-.269a.5.5 0 0 1 .324-.098c.725.045 1.449.033 2.172.026c.924.073 1.859-.163 2.768.146c.074.069.084.152.028.24c-.271.212-.593.16-.896.16c-1.149.007-2.296.002-3.442.005c-.165-.003-.323.04-.487.045a.54.54 0 0 1-.226-.082c-.144-.006-.284-.017-.431-.026");
}

.mq1o2ob_c {
  fill: var(--svg-color--be0810, #be0810);
  d: path("M35.01 13.373q.18.012.36.028c.08.089.088.189.047.294c-.095.12-.199.208-.361.12c.007-.11.005-.213-.114-.272c-.064-.088-.051-.15.068-.17");
}

.msfe7ccau {
  fill: var(--svg-color--d2020b, #d2020b);
  d: path("M37.68 21.485c.067-.452-.247-1.099.594-1.153c-.031.272-.375.402-.324.709q-.137.222-.27.444");
}

.mub8zcujq {
  fill: var(--svg-color--040101, #040101);
  d: path("m23.513 23.07l-.019-.719c-.391-.919-.25-1.62.424-2.116c.428-.158.867-.108 1.306-.084c.233.04.396.163.462.398c.04.199.038.394-.079.572c-.354.302-.166.718-.216 1.079c-.039.281 0 .659-.479.383c-.04-.023-.073-.098-.095-.084c-.083.046.018-.023.004.066c-.014.115-.043.242.021.349c.062.099.166.089.258.057c.283-.104.27-.358.296-.596c.045-.392-.134-.814.146-1.179c.383.018.296.364.406.572c-.061.51.08 1.02-.009 1.527c-.149.811-.788.641-1.347.704c-.736.087-.946-.358-1.079-.929");
}

.myldcsakn {
  fill: var(--svg-color--110303, #110303);
  d: path("M30.589 18.732c-.094-.004-.185-.013-.278-.018c-.16-.536-.083-1.08-.058-1.618c.021-.44.265-.354.488-.097c-.032.581.163 1.18-.152 1.733");
}

.mzdknsbpw {
  fill: var(--svg-color--660508, #660508);
  d: path("M37.676 35.946c-.148.183-.01.364.004.545l-.294.007l-.003-.137a.4.4 0 0 1-.097-.168c-.009-.104.015-.201.1-.268c.094.007.194.013.29.021");
}

.n_1_hpt8e {
  fill: var(--svg-color--7c5805, #7c5805);
  d: path("M30.607 49.07q-.005-.233-.004-.465c.197-.094.384-.054.569.039q.06.065.12.127a.5.5 0 0 1 .002.133c-.039.123-.189.072-.255.163l-.017.011c-.14.111-.281.121-.415-.008");
}

.n_t1_9b0l {
  fill: var(--svg-color--dc0211, #dc0211);
  d: path("M25.821 25.818c-.047.143-.095.283-.14.428c.058.154-.015.177-.145.147v-.572q.144-.004.285-.003");
}

.n-krv6tud {
  fill: var(--svg-color--d6020e, #d6020e);
  d: path("M29.3 18.592c-.088-.914.16-1.846-.143-2.748a1 1 0 0 1 .004-.131c.144-.13.297-.092.452-.029c.088.092.13.203.146.327c.088.577-.133 1.197.225 1.74c.09.296.117.589-.075.862c-.21.147-.412.133-.609-.021");
}

.n1xw9566k {
  fill: var(--svg-color--9f0000, #9f0000);
  d: path("M42.589 25.668q-2.448.01-4.893.016c.133-.24.365-.123.557-.162c1.218.002 2.441 0 3.663.008c.229-.001.484-.085.673.138");
}

.n3atg2b8h {
  fill: var(--svg-color--c50911, #c50911);
  d: path("M26.11 24.07q.009.578.014 1.154q-.062.096-.15.025v-.014c.067-.383-.143-.801.136-1.165m.02-.84c-.004.234-.012.473-.015.71c-.19-.243-.212-.479.015-.71");
}

.n4bjv2b8v {
  fill: var(--svg-color--86692a, #86692a);
  d: path("m32.479 37.787l.324.023c.143.048.108.163.104.267l-.129.177c-.243.072-.287-.121-.358-.276a.26.26 0 0 1 .059-.191");
}

.n5b-a2b5m {
  fill: var(--svg-color--f1df46, #f1df46);
  d: path("M31.03 50.646c0-.328 0-.651.002-.979q.07-.1.128.009q.006.481.007.966l-.07.019z");
}

.n5jpzybbx {
  fill: var(--svg-color--b92229, #b92229);
  d: path("M22.651 15.564c.335.043.701-.137 1 .134c-.333-.05-.698.131-1-.134");
}

.n8ll9jb3c {
  fill: var(--svg-color--af1a24, #af1a24);
  d: path("m32.765 13.25l.846.01c.012.044.027.083.042.126l-.053.004c-.252.185-.521.218-.804.065q-.118-.09-.031-.205");
}

.n9l9yac9a {
  fill: var(--svg-color--d0050f, #d0050f);
  d: path("m37.1 25.24l-.434.053a61 61 0 0 1-.725-.057c.387-.556.775-.278 1.159.004");
}

.nb5783xyw {
  fill: var(--svg-color--5e4b1e, #5e4b1e);
  d: path("M32.479 39.97q.078.075.157.145l-.159.002c-.034-.032-.045-.067-.034-.097q.017-.051.036-.05");
}

.ndeu4lbqx {
  fill: var(--svg-color--ce0409, #ce0409);
  d: path("M20.625 36.36c-.024.224.201.28.288.427c-.338 0-.675.004-1.01.004v-.144c.176-.251.42-.338.723-.287");
}

.nec4scbcg {
  fill: var(--svg-color--72070a, #72070a);
  d: path("M37.23 36.21c.054.002.103.006.155.006q0 .076-.002.146h-4.04c.002-.115.025-.221.136-.291c.276-.064.561-.045.846-.053c.72.017 1.44-.038 2.159.031c.254.042.523.005.749.161");
}

.nifd5vbrq {
  fill: var(--svg-color--9f0000, #9f0000);
  d: path("m21.21 25.679l-.143-.009c.061-.405.374-.2.56-.203c1.287-.025 2.572-.004 3.859-.017c.251-.042.547-.188.578.26c-.201.165-.442.157-.681.159c-1.146.006-2.286.006-3.43.002c-.262-.004-.528 0-.743-.192");
}

.nitkigb_s {
  fill: var(--svg-color--cf0817, #cf0817);
  d: path("M20.06 24.06a2 2 0 0 1-.012.172q-.071.085-.144.002c-.188-.086-.291-.229-.289-.438c.143-.115.283-.122.424.002l.026-.012q0 .139-.005.274");
}

.nmdo46bps {
  fill: var(--svg-color--3b0305, #3b0305);
  d: path("m32.19 18.877l-.578.002q0-1.308-.005-2.617c.195-.012.395-.124.586.016q0 1.3-.003 2.599");
}

.nnx0v2bbe {
  fill: var(--svg-color--050207, #050207);
  d: path("M23.2 31.564q.088-.128.17-.258c.276-.143.465-.395.725-.559l1.145-.004c.092.088.091.178.009.269c-.258-.036-.428-.097-.692.192c-.362.398-.577 1.299-1.469.825c.048-.15.164-.289.112-.465");
}

.noduqqb9g {
  fill: var(--svg-color--2a0808, #2a0808);
  d: path("M44.34 23.01c.346.523.112 1.094.131 1.644c-.077.062-.145.05-.207-.021a.7.7 0 0 1-.117-.346c-.02-.364-.053-.727.044-1.086a.4.4 0 0 1 .149-.191");
}

.nr4orw_nu {
  fill: var(--svg-color--422b2c, #422b2c);
  d: path("m23.663 14.547l.288.011a.5.5 0 0 1 .109.157c.02.064.027.126.033.193a.62.62 0 0 1-.107.377a.36.36 0 0 1-.184.064a.27.27 0 0 1-.17-.098z");
}

.nsc5bmbzm {
  fill: var(--svg-color--b00811, #b00811);
  d: path("M36.806 35.34c.22-.201.468-.129.712-.082c-.114.122-.268.091-.412.1c-.104.078-.205.08-.3-.018");
}

.nsyd7fbct {
  fill: var(--svg-color--090102, #090102);
  d: path("M40.834 35.04c-.963.009-1.923-.011-2.885.031c-.471.019-.596-.187-.575-.589c-.377-.707-.106-1.469-.188-2.201c.004-.217-.003-.43.053-.641c.048-.17.188-.271.289-.402c.662-.809 1.532-.781 2.438-.596c.541.48 1.325.844.904 1.807q-.017 1.296-.036 2.591");
}

.num9hhvng {
  fill: var(--svg-color--bd171c, #bd171c);
  d: path("m21.21 25.679l4.891-.001a1 1 0 0 0 .052.091a.3.3 0 0 1-.144.155a1.2 1.2 0 0 1-.334.072c-.12.012-.244.016-.365.028c-1.05-.019-2.098.036-3.147.013c-.33-.008-.673.027-.949-.216l-.01-.007z");
}

.nv46cncas {
  fill: var(--svg-color--0b0703, #0b0703);
  d: path("M30.925 35.498c-.08-.111-.193-.149-.324-.137a.24.24 0 0 0-.101-.018c-.123-.039-.146-.136-.15-.244a.34.34 0 0 1 .102-.182c.453.275.861.703 1.482.412c.279-.133.287.16.393.291c-.197.021-.439-.021-.438.295a.13.13 0 0 1-.131.062a1 1 0 0 0-.146-.044a1 1 0 0 0-.152 0z");
}

.o-8smvbio {
  fill: var(--svg-color--927404, #927404);
  d: path("M31.753 35.905a.23.23 0 0 0 .136.011q.013.065.035.127q-.148.02-.297.043q-.092-.062-.053-.165q.083-.076.179-.016");
}

.o2y1dpbsk {
  fill: var(--svg-color--493e0f, #493e0f);
  d: path("M32.459 37.22q.092.08.178.164l-.158.4l-.025.154a.5.5 0 0 0-.123.02c-.182.137-.354.114-.517-.039a.64.64 0 0 1-.148-.309c.083-.5.438-.445.793-.39");
}

.o39q0dw_x {
  fill: var(--svg-color--490100, #490100);
  d: path("m31.3 49.557l-.064-.014l-.063.004a.14.14 0 0 1-.158-.021a.18.18 0 0 1 .013-.163a.3.3 0 0 1 .154-.076a.26.26 0 0 1 .154.063l-.002.009a4 4 0 0 0-.034.198");
}

.o7e0a7xph {
  fill: var(--svg-color--d9000e, #d9000e);
  d: path("M37.675 26.679c-.117.692.155.968.86.876c.377-.046.768-.004 1.151-.007c.146-.003.36.032.419-.043c.65-.86 1.45-.292 2.191-.254c.096.007.193.007.289.009q0 1.298-.003 2.6c-.123.103-.152.266-.252.384a.65.65 0 0 0-.138.312c-.064.586-.357.545-.734.268a.5.5 0 0 1-.126-.149c-.119-.327-.091-.867-.694-.464c-.132.107-.244.233-.395.319a1 1 0 0 1-.311.083c-.348.01-.684.005-.854-.377a.26.26 0 0 1 .018-.199c.088-.077.177-.134.303-.075c.007.002.015-.055.015-.055c-.099.053-.229.011-.307.112c-.306.128-.762-.008-.846.497c-.348.288-.541.774-1.063.851c-.508-.433-.276-.971-.211-1.484c.392-.725.118-1.502.201-2.25c-.003-.122-.006-.244.003-.365c.009-.205.014-.41.146-.587c.116-.081.227-.093.338-.002");
}

.o8ls_s02r {
  fill: var(--svg-color--ce0710, #ce0710);
  d: path("m24.09 15.972l.002-.273c.387-.065.81.153 1.161-.155c.103-.068.214-.058.323-.023c.375.065.752.036 1.131.02a.61.61 0 0 1 .545.159c.037.214-.091.282-.271.303q-1.448-.014-2.891-.031");
}

.o8y3omhxd {
  fill: var(--svg-color--96514e, #96514e);
  d: path("M23.633 15.252c.057.017.11.029.17.046q.05.133-.076.203c-.327.122-.647.163-.943-.075l.001-.155c.281-.007.566-.009.848-.019");
}

.o9nj2qb1a {
  fill: var(--svg-color--ca0511, #ca0511);
  d: path("m41.43 16.287l-.008.707a8 8 0 0 1-.268-.121c-.221.182-.482.186-.746.183c-1.072-.001-2.145.019-3.215-.011a.8.8 0 0 1-.387-.136c-.164-.212-.161-.415.02-.613z");
}

.ocu36chmg {
  fill: var(--svg-color--a90813, #a90813);
  d: path("M33.635 18.879c-.412-.015-.957.176-.881-.578l.01-1.73c.106-.09.211-.072.315.006c.253.361.155.774.169 1.166c.01.363.016.713.374.93q.087.099.013.206");
}

.od3e5iydv {
  fill: var(--svg-color--e5000d, #e5000d);
  d: path("M29.87 23.789h-.287q-.085-.04-.175-.077c.074-.05.136-.118.215-.144c.204-.072.227.08.247.221");
}

.oe4qp44ry {
  fill: var(--svg-color--2d0908, #2d0908);
  d: path("M26.982 17.14c-.245.548-.084 1.124-.102 1.686c-.039 1.177-.028 2.355-.039 3.531c-.247 0-.278-.19-.324-.369a91 91 0 0 1-.01-4.461a.6.6 0 0 1 .167-.366l.026-.292l.277-.025l.151.107z");
}

.oebz-db1b {
  fill: var(--svg-color--d70407, #d70407);
  d: path("M35.645 13.963c-.189-.004-.277-.104-.285-.288q.006-.139.008-.273q.138-.003.276-.002z");
}

.ofdrrsbrt {
  fill: var(--svg-color--010105, #010105);
  d: path("M25.537 21.19v1.149c-.003.959-.023.976-1.128.781c.403-.357.165-.852.346-1.283c.364.141.049.572.37.717c.384-.384-.24-1.08.415-1.364z");
}

.ofpj3mbom {
  fill: var(--svg-color--af0910, #af0910);
  d: path("m35.917 13.822l-.26.145q-.038-.039-.077-.074a.42.42 0 0 1 .063-.493c.057-.01.112-.014.167-.021c.161.117.12.285.107.443");
}

.ogx_xgu7y {
  fill: var(--svg-color--5b0607, #5b0607);
  d: path("M38.42 14.689c.468-.295.942-.215 1.417-.021q.074.096.005.2c-.186.147-.41.137-.628.144c-.104 0-.211-.002-.315-.014a.8.8 0 0 1-.301-.07c-.099-.047-.146-.137-.178-.239");
}

.oj_bwjbbr {
  fill: var(--svg-color--d40313, #d40313);
  d: path("M25.545 20.602c-.011-.18-.097-.283-.283-.287c-.387-.266-.832-.07-1.242-.149c-.33-.138-.402-.323-.059-.52c.163-.091.345-.132.348-.367c.142-.292.401-.285.667-.27a.53.53 0 0 1 .423.356c.05.241.204.411.371.576c.208.201.253.437.084.688c-.112.063-.215.068-.309-.027");
}

.okfvxl8em {
  fill: var(--svg-color--720000, #720000);
  d: path("M36.23 35.643q-.8 0-1.599-.002c.532-.236 1.067-.243 1.599.002");
}

.oklv47wqe {
  fill: var(--svg-color--d80110, #d80110);
  d: path("M23.513 18.301v1.154c-.354.162-.274-.106-.289-.287c.099-.289-.232-.721.289-.867");
}

.on_cujbwq {
  fill: var(--svg-color--91070a, #91070a);
  d: path("M34.93 13.12c.305.051.711-.244.881.258a.4.4 0 0 1-.18.133a.8.8 0 0 1-.334.027a.5.5 0 0 1-.29-.166c-.009-.09-.176-.13-.077-.252");
}

.oreaxs6jp {
  fill: var(--svg-color--450f0e, #450f0e);
  d: path("M30.15 13.381a5 5 0 0 0-.149.147c-.206-.335-.208-.608.273-.548c.354.043.771-.236 1.064.177a.2.2 0 0 1-.106.155a.6.6 0 0 1-.194.019c-.244-.031-.487-.115-.738-.052a.7.7 0 0 0-.15.102");
}

.orso23b7k {
  fill: var(--svg-color--490c0b, #490c0b);
  d: path("M37.25 14.732c.068.68.532.604 1 .523q.07.119-.031.214c-.344.187-.695.159-1.051.041c-.247-.175-.207-.397-.094-.628a.6.6 0 0 1 .175-.15");
}

.ouu68ebxt {
  fill: var(--svg-color--b30003, #b30003);
  d: path("M25.534 24.521a1 1 0 0 1-.002.132q-2.597.002-5.197.009q0-.073-.002-.145q2.604 0 5.201.004");
}

.p-hq5mbno {
  fill: var(--svg-color--e4c134, #e4c134);
  d: path("M32.33 38.963c.059.143.112.279.169.42c-.035.141-.14.211-.271.245a.6.6 0 0 1-.189-.001c-.151-.039-.309-.072-.455-.129a.26.26 0 0 1-.124-.131l.011-.111c.13-.133.356-.138.426-.339c.085-.057.181-.07.278-.057a.33.33 0 0 1 .155.103");
}

.p03g1bc0d {
  fill: var(--svg-color--5b0001, #5b0001);
  d: path("M25.821 25.24q-.067.001-.136-.004a9 9 0 0 1-.009-.285l-.131-.283l.275-.002z");
}

.p11y4pb5o {
  fill: var(--svg-color--510f05, #510f05);
  d: path("M32.475 35.645v.418a7 7 0 0 0-.319.016a.3.3 0 0 1-.192.064a.25.25 0 0 1-.152-.141a.5.5 0 0 1-.014-.215c.107-.279.3-.285.529-.166c.048.008.097.02.148.024");
}

.p8epoob0x {
  fill: var(--svg-color--906f02, #906f02);
  d: path("M29.554 40.855a.5.5 0 0 0-.12.014c-.108-.037-.236-.044-.264-.189a.6.6 0 0 1 .176-.078a.29.29 0 0 1 .265.092a.14.14 0 0 1-.057.161");
}

.p9e_uvb2w {
  fill: var(--svg-color--9e8f4f, #9e8f4f);
  d: path("M30.3 35.22c-.149.05-.141.184-.163.304l-.144-.17c-.046-.099-.06-.192.034-.274c.087.008.178.019.265.022c.005.04.007.075.008.118");
}

.phvu3vbol {
  fill: var(--svg-color--721419, #721419);
  d: path("M27.743 13.08c.349-.237.744-.062 1.112-.119l.015.305c-.294-.021-.552.113-.823.188a.4.4 0 0 1-.188-.02c-.109-.096-.067-.241-.116-.354");
}

.pj0wtiv6n {
  fill: var(--svg-color--d5030e, #d5030e);
  d: path("M29.3 27.548h.288c0 .165-.014.333.002.495c.063.594-.19.783-.784.59c.074-.403.645-.594.494-1.085");
}

.pk9xg-r0j {
  fill: var(--svg-color--b2181f, #b2181f);
  d: path("M27.426 26.409q.072.001.146.009c.193.188.188.433.188.672c-.009 2.512.027 5.02.002 7.537c-.011.229.003.457-.117.665c-.059.088-.134.106-.23.069v-.013l-.003-.577c-.15-.711-.064-1.428-.059-2.139c.016-1.792-.092-3.583.059-5.371q.006-.428.014-.852");
}

.plwpwsb0t {
  fill: var(--svg-color--f4d51c, #f4d51c);
  d: path("m31.622 47.928l.003-.158c.126-1.375.015-2.758.064-4.133c.005-.2-.175-.6.332-.484c0 .055 0 .105-.002.159c-.239.294-.115.644-.117.965c-.016 1.407-.007 2.815-.01 4.224c-.4-.044-.091-.423-.27-.573");
}

.ppohdr45t {
  fill: var(--svg-color--790000, #790000);
  d: path("m25.811 24.05l.011.613c-.091.082-.183.073-.275.002l-.014-.013c-.044-.029-.06-.062-.042-.089q.022-.045.044-.043c.159-.105.13-.273.143-.424c.04-.017.087-.031.133-.046");
}

.pr12jryhe {
  fill: var(--svg-color--d20408, #d20408);
  d: path("M24.09 15.41a4 4 0 0 1-.165-.154l.054-.408c.343-.07.707-.29.975.143c-.236.245-.47.497-.864.419");
}

.ptn9-g2gx {
  fill: var(--svg-color--fedf40, #fedf40);
  d: path("m30.29 41.28l-.105-.003c-.06-.048-.117-.096-.186-.123l-.063-.017l-.068.019a4 4 0 0 0-.152-.148c-.144-.275.024-.398.24-.497a.35.35 0 0 1 .304.081c.143.115.271.244.287.443c-.027.143-.034.306-.257.245");
}

.pujrdkbwn {
  fill: var(--svg-color--b21824, #b21824);
  d: path("M29.3 35.787q.29-.004.58-.011c.169-.085.289-.085.287.149H29.3z");
}

.pvw1kebup {
  fill: var(--svg-color--c6091c, #c6091c);
  d: path("m26.09 25.814l.032.559c.042.156-.046.224-.182.215c-.162-.012-.235-.136-.279-.279c-.069-.202.04-.348.157-.49q.138-.006.272-.005");
}

.pvw428ber {
  fill: var(--svg-color--ae000b, #ae000b);
  d: path("M35.08 14.23q-.728.001-1.453.006c.004-.043.01-.081.013-.123c.476.051.976-.129 1.44.117");
}

.pw2pwfcqo {
  fill: var(--svg-color--6a2808, #6a2808);
  d: path("m31.467 41.99l-.172.161l-.067-.007h-.07a5 5 0 0 0-.128-.154c-.087-.097-.082-.197-.019-.299c.245-.043.452-.023.456.299");
}

.q-4paybnu {
  fill: var(--svg-color--d30311, #d30311);
  d: path("M24.67 26.679c.389.05.264.354.287.581c-.385-.047-.261-.351-.287-.581");
}

.q1igj_bym {
  fill: var(--svg-color--c0030b, #c0030b);
  d: path("m41.12 21.19l-.265-.285c-.085-.08-.106-.188-.102-.299q.008-.11.034-.219c.087-.676-.104-1.364.131-2.027q.075-.112.199-.057z");
}

.q4gsw1yqc {
  fill: var(--svg-color--c70810, #c70810);
  d: path("M28.426 36.08q0-.076-.002-.146q.437 0 .871-.004c.217-.202.487-.184.754-.184c.11 0 .225.012.334.035a.6.6 0 0 1 .2.096q.084.092.028.203c-.065.119-.184.139-.303.157c-.149-.009-.293-.019-.442-.026c-.467-.182-.973.058-1.44-.131");
}

.q5hngu-zk {
  fill: var(--svg-color--510405, #510405);
  d: path("M25.516 36.531c-.172-.104-.007-.195.003-.294a.3.3 0 0 1 .011-.351c.311-.195.625-.182.948-.041a.31.31 0 0 1 .136.302c-.048.12-.145.157-.255.169c-.202-.014-.397-.012-.527.182q-.075.01-.149.023z");
}

.q77ixibvb {
  fill: var(--svg-color--500101, #500101);
  d: path("M26.982 26.377q0-.129.006-.252c.13-.184.309-.166.491-.121c.108.05.159.141.161.258l-.029.1q-.076.09-.186.048q-.153.001-.308-.005q-.068-.013-.135-.028");
}

.qa_bt6g-l {
  fill: var(--svg-color--2d0706, #2d0706);
  d: path("M41.31 22.632c-.065.042.034.306-.185.134c-.322-.496-.124-1.057-.183-1.582c.004-.934 0-1.862.002-2.793c.005-.38-.005-.758.017-1.135a.7.7 0 0 1 .111-.352c.104-.127.208-.082.313.002l.055.105c-.004.047-.008.092-.004.135c-.162 1.043-.031 2.09-.074 3.131c-.033.786.061 1.571-.052 2.355");
}

.qdwvmn60t {
  fill: var(--svg-color--d3040a, #d3040a);
  d: path("M24.686 18.299c.048.031.16.063.18.127c.042.127-.086.14-.174.148c-.097.018-.203 0-.229-.104c-.033-.134.093-.134.223-.171");
}

.qfjcmuwdg {
  fill: var(--svg-color--750000, #750000);
  d: path("M25.398 37.34c-.252-.17-.539-.134-.82-.134q-2.607 0-5.213-.003q-.129-.048-.057-.165a.4.4 0 0 1 .26-.196a.8.8 0 0 1 .351.018c.654.063 1.308.02 1.962.027c.967.006 1.938-.021 2.906.016c.267.006.682-.085.611.437");
}

.qi259qbwc {
  fill: var(--svg-color--9c2223, #9c2223);
  d: path("M25.387 36.795c-.535.293-1.115.107-1.673.137c-.644.033-1.288.012-1.937.015a6.6 6.6 0 0 1-2.02 0l-.271-.015q-.102-.103.006-.198c.144-.095.302-.118.466-.127c.322-.011.644.002.969-.019c.247 0 .497.017.744.004c.345-.012.691.013 1.038-.004c.646-.037 1.296-.018 1.94-.011c.264.001.535.001.738.218");
}

.qiu9sxbpj {
  fill: var(--svg-color--997e07, #997e07);
  d: path("M31.15 47.916c.01-.078.014-.159.024-.236a.2.2 0 0 1 .112-.006l.002 1.1c-.134.031-.188-.055-.236-.152a1 1 0 0 1-.017-.527a.5.5 0 0 1 .115-.179");
}

.ql9e6tijt {
  fill: var(--svg-color--b2171d, #b2171d);
  d: path("M34.648 22.489c-.317.594-.857.161-1.28.28c-.155-.126-.149-.275-.062-.434c.104-.075.218-.079.338-.05c.469.241.649.063.649-.428q.008-1.067 0-2.138c-.021-.201.005-.401 0-.603c.005-.718 0-1.436.003-2.149q-.005-.425.016-.848a.8.8 0 0 1 .099-.342q.04-.043.083-.082l.138.018c.16.416.078.85.072 1.269c-.022 1.839.083 3.677-.056 5.507");
}

.qldmlwb7a {
  fill: var(--svg-color--8c0000, #8c0000);
  d: path("M31.02 13.216q-.418.018-.833.038c.268-.254.547-.206.833-.038");
}

.qnz2gj1mx {
  fill: var(--svg-color--59411c, #59411c);
  d: path("M31.459 39.37c.052.016.102.039.15.053a.17.17 0 0 1 .043.16a.6.6 0 0 1-.185.292a.16.16 0 0 1-.157-.044l.006.008a.23.23 0 0 1-.068-.17c.003-.096-.016-.194.063-.271a2 2 0 0 1 .148-.028");
}

.qpr39it-z {
  fill: var(--svg-color--5f0b09, #5f0b09);
  d: path("M27.558 16.12c-.479.107-.208.596-.428.834c-.099-.008-.179-.043-.224-.137a.5.5 0 0 1-.008-.268c.027-.14.063-.277.08-.42q.005-.063.004-.127c.043-.152.105-.293.104-.455c.014-.238-.016-.484.062-.719a.4.4 0 0 1 .131-.164c.565.396.178.972.279 1.456");
}

.qu0v4ea2u {
  fill: var(--svg-color--320d11, #320d11);
  d: path("M25.419 15.13q-.168-.075-.337-.154q0-.154.061-.304a.4.4 0 0 1 .102-.117l.29-.011c-.032.198.116.43-.116.586");
}

.qvbop4bmi {
  fill: var(--svg-color--680609, #680609);
  d: path("M20.19 23.06c-.019-.095.051-.109.117-.124c.076.285-.229.742.193.837c.3.066.807.31.992-.275c.206.141.121.356.132.543a.22.22 0 0 1-.174.097c-.378-.029-.753-.048-1.128.041a.45.45 0 0 1-.31-.081a.48.48 0 0 1-.068-.318c.06-.249.04-.524.246-.72");
}

.qvgff8n8c {
  fill: var(--svg-color--d9020e, #d9020e);
  d: path("M39.696 36.506v.282l-1.15-.003c.274-.556.774-.16 1.15-.279");
}

.qvmmnvzcz {
  fill: var(--svg-color--701506, #701506);
  d: path("M33.518 35.941c-.232-.113-.17-.396-.322-.555c.046-.104.135-.115.23-.107c.151.051.262.166.398.236a.44.44 0 0 1 .135.137c.019.15-.052.25-.168.327c-.099.039-.191.035-.273-.038");
}

.qvvk1pb0q {
  fill: var(--svg-color--af0c10, #af0c10);
  d: path("m34.503 35.643l.131-.002a3.85 3.85 0 0 1 1.599.002l-.004-.002l.01.14c-.654.367-1.351.183-2.034.149l-.443-.014l.172-.249c.179-.208.373-.165.569-.024");
}

.qy0oc_6bd {
  fill: var(--svg-color--fec6c9, #fec6c9);
  d: path("M31.602 38.12c-.041-.049-.084-.104-.127-.151q.211-.082.418-.158c.093.206.299.09.438.15c.004.042 0 .085-.003.123c-.234.168-.474.216-.726.036");
}

.qzex7do5g {
  fill: var(--svg-color--d50912, #d50912);
  d: path("M30.16 14.83c-.387-.26-.771-.094-1.156 0l.002-.271q.646-.003 1.291-.002c.085.158-.065.195-.137.273");
}

.qztwr7bex {
  fill: var(--svg-color--772c0e, #772c0e);
  d: path("M32.455 41.25c-.021-.34.168-.433.467-.4c-.035.273-.251.336-.467.4");
}

.r_u44ab8l {
  fill: var(--svg-color--650000, #650000);
  d: path("m42.15 15.969l.001-1.105q0-.076.005-.156c.415.385.124.851.143 1.277z");
}

.r-vgk9qql {
  fill: var(--svg-color--ac1c20, #ac1c20);
  d: path("m44.03 36.506l-.006-.272q.141 0 .276.004c-.009.239.11.505-.13.704c-1.679 0-3.354.002-5.03-.005c-.252-.002-.533.096-.745-.142c.051-.007.101-.007.15-.014c.37-.23.78-.091 1.173-.13c.83-.007 1.662.104 2.49 0c.609-.073 1.24.157 1.825-.145");
}

.r-y1p9bqr {
  fill: var(--svg-color--bfa37b, #bfa37b);
  d: path("m31.31 39.828l.144.012q.057.04.045.084q-.016.047-.034.048l-.011-.007c-.084-.01-.147-.039-.144-.137");
}

.r02sf1bht {
  fill: var(--svg-color--a02529, #a02529);
  d: path("M40.993 32.475q.074 0 .146-.008v.859c.271.457.077 1.096.572 1.466c-.003.043-.006.087-.018.133c-.579.095-.756-.167-.711-.728c.046-.57.011-1.146.011-1.722");
}

.r3no7gbcr {
  fill: var(--svg-color--fef082, #fef082);
  d: path("m30.741 35.764l.091-.254c.042.111.105.228-.091.254");
}

.r41cvqb8f {
  fill: var(--svg-color--e10009, #e10009);
  d: path("M22.643 32.17c-.386-.049-.256-.35-.283-.574c.188.004.281.103.287.288q0 .142-.004.286");
}

.r9y_yosgd {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M10 54h44c6.627 0 10-4.925 10-11v-4H0v4c0 6.075 3.373 11 10 11");
}

.rhc82yo9f {
  fill: var(--svg-color--c90a17, #c90a17);
  d: path("M22.938 19.17v2.02l-.026.858s-.036.033-.054.033c-.021.003-.045-.016-.066-.022l.003-4.888l.433-.01c-.04.679.004 1.368-.29 2.01");
}

.ri_i_gb1n {
  fill: var(--svg-color--d7020a, #d7020a);
  d: path("M29.3 30.438c-.002.098-.002.191-.002.29l-.578.188c.083-.377-.243-.854.245-1.013c.399-.13.302.3.335.535");
}

.rkqeb-bsj {
  fill: var(--svg-color--8d0003, #8d0003);
  d: path("m32.623 13.203l-.006-.042c.338-.044.689-.194.993.099c-.249.197-.526.195-.813.107a.44.44 0 0 1-.174-.164");
}

.rmn-dyo-k {
  fill: var(--svg-color--481c1c, #481c1c);
  d: path("M19.329 35.936c.194-.094.39-.193.59-.288c.157-.073.23.026.29.148c-.014.274-.279.309-.428.454a.4.4 0 0 1-.275.042a.34.34 0 0 1-.209-.186q-.046-.096.032-.17");
}

.rntc0jbnq {
  fill: var(--svg-color--d2040a, #d2040a);
  d: path("M34.493 19.746c0 .783.005 1.568 0 2.355c0 .201.062.474-.246.508c-.238.031-.548.143-.621-.26l.034-.089c.123-.146.128-.341.2-.507c.167-.193.132-.382-.005-.57q-.029-.104-.02-.206c.099-.291.164-.588.213-.894c.038-.216.078-.513.445-.337");
}

.rq0g5qbca {
  fill: var(--svg-color--d2040d, #d2040d);
  d: path("M29 35.34c0-1.139-.005-2.281.004-3.422c.003-.236-.115-.559.292-.608q-.006 2.016-.016 4.04c-.095 0-.187-.005-.28-.005");
}

.rsq44n82o {
  fill: var(--svg-color--2b0805, #2b0805);
  d: path("m44.3 36.24l.146-.172c.038.354.097.706-.032 1.057a9 9 0 0 1-.244-.181c-.046-.251-.049-.494.13-.704");
}

.rt2h3xb5x {
  fill: var(--svg-color--731316, #731316);
  d: path("m32.475 13.967l-1.16-.031c.011-.105.029-.206.148-.25c.304.26.663.09.996.127l.029.025c.034.045.03.091-.013.129");
}

.ru544ksub {
  fill: var(--svg-color--f3d60d, #f3d60d);
  d: path("M29.3 40.41h.279v.146c-.097.085-.192.087-.286-.005l-.004.005q.002-.075.011-.146");
}

.ruavjcclk {
  fill: var(--svg-color--ba0610, #ba0610);
  d: path("M26.403 22.347c.116-.061.141-.171.146-.287q.06-.096.121-.004c.027.12.031.253.172.306l-.002.258c-.238-.019-.471.328-.715.013c.183-.008.273-.106.278-.286");
}

.rv2x5ccuy {
  fill: var(--svg-color--a4070a, #a4070a);
  d: path("m36.51 35.36l-.281.283c-.037.004-.074.012-.108.016c-.512.039-1.021.018-1.534.049a.2.2 0 0 1-.158-.158c-.014-.14.033-.242.158-.308a.9.9 0 0 1 .278-.079c1.144-.127 1.149-.127 1.144-1.266c-.006-1.154.031-2.31.014-3.466c.01-1.019.004-2.039.009-3.056q-.003-.206.001-.402c.001-.235.023-.462.211-.634c.189-.073.364-.086.489.12c.146.21.134.457.134.693c.002 2.275.005 4.552 0 6.824c-.003.283.036.584-.208.808c-.206.151-.132.377-.149.576");
}

.rv47dp-vo {
  fill: var(--svg-color--d9010a, #d9010a);
  d: path("M34.35 25.23h-3.467c-.081-.08-.179-.24-.245-.229c-1.01.16-.988-.562-1.054-1.213c.097-.086.192-.082.287 0c.065.402.36.27.602.265l-.005.002c.245.272.576.179.863.161c.767-.051 1.548.172 2.296-.137l.006-.291c.247-.172.472-.172.667.086c.199.398.041.808.052 1.217q0 .07-.002.139");
}

.rx09_cbtc {
  fill: var(--svg-color--c40a13, #c40a13);
  d: path("M26.403 22.347c0-1.409-.021-2.817.013-4.227c.01-.528-.136-.747-.682-.697c-.452.043-.909.016-1.361.007c-.226-.005-.504.08-.573-.268q1.438.004 2.875.003l-.009.28c-.109 1.5-.018 3.01-.048 4.515c-.025.154.079.383-.215.387");
}

.rx7wq1bxj {
  fill: var(--svg-color--e8d22b, #e8d22b);
  d: path("M29.29 40.24c.049-.149.207-.108.302-.169c.157-.18.335-.308.588-.287c.127.078.195.183.173.338a.5.5 0 0 1-.307.254a1.3 1.3 0 0 1-.406.037a.65.65 0 0 1-.289-.09a1 1 0 0 0-.061-.083");
}

.ry0t_b62q {
  fill: var(--svg-color--d9010c, #d9010c);
  d: path("M37.1 29.859c0-.59-.004-1.178 0-1.768c.002-.227-.059-.496.288-.544c0 .588.003 1.179-.001 1.767c-.002.229.058.499-.287.545");
}

.ryfgftb_f {
  fill: var(--svg-color--ab9124, #ab9124);
  d: path("M31.746 42.28q.074.01.146.015a1 1 0 0 1 .001.132l-.069.003h-.072z");
}

.rzo03q2dk {
  fill: var(--svg-color--0e0204, #0e0204);
  d: path("M34.21 31.02q-.013.145-.023.292c-.351-.607-.859-1.05-1.423-1.439c.062-.095.152-.132.26-.146c.58.021.927.376 1.205.834a.8.8 0 0 1 .074.188c.012.106-.008.202-.093.271");
}

.s3fmjrkvo {
  fill: var(--svg-color--560000, #560000);
  d: path("m26.982 35.33l-.07-.003l-.072.003c-1.717-.113-3.438-.02-5.155-.055c-.256-.007-.526.07-.771-.07l.004-.146c.644-.178 1.314.047 1.958-.127a1.2 1.2 0 0 1 .391-.072c.74-.036 1.479-.01 2.218-.016c.537.094.725-.132.732-.672c.011-.611-.162-1.25.148-1.838c.514.011.338.418.374.682c.079.586-.109 1.194.128 1.769c.157.128.396.149.474.374a.33.33 0 0 1-.025.184c-.117.123-.223-.001-.334-.013");
}

.s3lwdznxj {
  fill: var(--svg-color--efd716, #efd716);
  d: path("M31.892 48.646c-.068.674.162 1.366-.141 2.025c-.073-.625.151-1.27-.126-1.881c-.046-.034-.062-.072-.057-.115q.009-.065.027-.065c.108-.053.206-.05.297.036");
}

.s62732b2n {
  fill: var(--svg-color--f8da23, #f8da23);
  d: path("M32.02 43.15c-.393.087-.265.404-.267.644c-.012 1.097 0 2.195-.006 3.294c-.003.228.077.483-.124.68l-.035-.281q.016-2.296.027-4.6q.208-.008.421-.012c-.004.094-.012.186-.016.275");
}

.s699b3bzx {
  fill: var(--svg-color--d7010e, #d7010e);
  d: path("M28.426 34.483v-2.31c.2.025.289.137.287.334v1.639c.002.2-.087.313-.287.337");
}

.s7_9261ac {
  fill: var(--svg-color--a41019, #a41019);
  d: path("m28.426 14.11l-.276.119c-.575-.109-.188-.564-.296-.841q.067-.005.134-.017c.016.157-.021.328.126.449c.136-.02.23.052.311.148q-.002.071.001.142");
}

.sbxxxhqux {
  fill: var(--svg-color--982124, #982124);
  d: path("M32.617 13.965v-.158l.006-.604q.068.021.142.047l.002.143c.12.237.245.472-.15.572");
}

.scw51dbzn {
  fill: var(--svg-color--c80c19, #c80c19);
  d: path("M35.36 14.234c-.097.008-.189.018-.284.025q-.052.008-.103.018c-.432.022-.861.039-1.29-.025a.5.5 0 0 1-.196-.102c-.082-.18.005-.28.158-.352c.093.044.188.092.282.134c.38.015.77.106 1.128-.117l.307-.141c.145.048.178.201.285.288l.013.004c-.099.089-.202.179-.3.268");
}

.sfw-f1bao {
  fill: var(--svg-color--b50f17, #b50f17);
  d: path("M43.45 25.373c-.194-.122-.384-.009-.575.006q-2.305-.007-4.612-.01q-.128-.015-.146-.144l-.003-.27c.321-.302.735-.213 1.103-.217c1.197-.013 2.395-.002 3.59-.057c.252-.011.475.057.646.26q-.004.217-.003.432");
}

.sger-rbvr {
  fill: var(--svg-color--220a00, #220a00);
  d: path("M32.471 38.951q.142.004.279.005l.14.153c.065.133.187.244.152.414a.26.26 0 0 1-.165.098a.8.8 0 0 1-.468-.182c-.131-.133-.21-.279-.122-.467c.057-.05.115-.057.184-.021");
}

.shpx860pu {
  fill: var(--svg-color--c60b15, #c60b15);
  d: path("M29.87 17.722q0-.576.003-1.153l.282-.004a.5.5 0 0 1 .069.233c-.099.643.175 1.322-.205 1.935q-.075-.073-.149-.141z");
}

.sk68d-b3p {
  fill: var(--svg-color--f7d825, #f7d825);
  d: path("m29.58 50.642l-.854.007c0-.33-.086-.672.139-.971q.142-.015.285-.027c.121.127.037.297.084.439a.5.5 0 0 0 .134.12a1 1 0 0 1 .134.11c.068.1.142.193.078.322");
}

.skveb8b-p {
  fill: var(--svg-color--c40914, #c40914);
  d: path("M40.552 22.644c.188-.012.299-.102.302-.299c-.254-.427-.132-.885-.104-1.338c.309-.33.281.053.371.179v1.58c-.193-.028-.472.336-.569-.122");
}

.snjrjed8x {
  fill: var(--svg-color--6f0101, #6f0101);
  d: path("m43.01 25.686l-.136-.018c-.088.145-.203.217-.378.153a1.2 1.2 0 0 0-.222-.073c-1.03-.053-2.06-.008-3.089-.025c-.305-.006-.625.046-.905-.142a.205.205 0 0 1-.045-.237c.062-.078.135-.16.228-.16c1.451.018 2.904-.125 4.352.08c.132.06.225.152.261.293z");
}

.soi4t8bpj {
  fill: var(--svg-color--d50208, #d50208);
  d: path("M30.16 15.711q0 .139.003.277c.15.25.796.022.591.615c-.161.133-.351.145-.546.135a.7.7 0 0 1-.314-.096c-.23-.158-.097-.489-.31-.654v-.277z");
}

.sre2b136g {
  fill: var(--svg-color--bf030f, #bf030f);
  d: path("M30.02 18.732c.062-.676-.149-1.363.131-2.02l.034.018c.298.592.173 1.21.108 1.821a.38.38 0 0 1-.163.186c-.035-.004-.075-.004-.11-.004");
}

.ss-4byb2n {
  fill: var(--svg-color--b78251, #b78251);
  d: path("M28.537 47.783c.869-.305 1.759-.117 2.642-.104c.074.113.074.213-.055.291c-.498.029-.998-.021-1.495 0c-.267-.008-.53.006-.795-.029a.7.7 0 0 1-.215-.078z");
}

.ss366lbpg {
  fill: var(--svg-color--8d2323, #8d2323);
  d: path("M32.33 38.963q-.076-.005-.148-.014c-.124-.111-.227-.24-.202-.424a.53.53 0 0 1 .208-.338c.102-.027.197-.027.27.066l.014.697a1 1 0 0 1-.142.013");
}

.suakruc1f {
  fill: var(--svg-color--580000, #580000);
  d: path("M38.26 15.391q0-.068-.007-.135a.66.66 0 0 1 .169-.566l.123.133a.43.43 0 0 1 .134.375a.6.6 0 0 1-.066.193a.3.3 0 0 1-.179.095a.25.25 0 0 1-.174-.095");
}

.swxur49kt {
  fill: var(--svg-color--f4d427, #f4d427);
  d: path("M30.455 50.26q.134-.298.274-.599c.112-.086.227-.086.337.008c.029.331.093.659-.037.982q-.36 0-.719-.002c-.055-.089-.03-.175.012-.261a1 1 0 0 1 .133-.128");
}

.t_0x0rbio {
  fill: var(--svg-color--a91c22, #a91c22);
  d: path("M27.987 13.373c.276-.17.565-.252.883-.105q.005.07.007.137c-.148-.001-.304-.005-.453-.008c-.181.105-.093.436-.382.448c-.193-.134-.179-.297-.055-.472");
}

.t-2il32qk {
  fill: var(--svg-color--7e0102, #7e0102);
  d: path("M30.425 22.77q.004.226.003.456c-.526.31-1.078.203-1.631.11a.4.4 0 0 1-.247-.285c-.005-.235.245-.158.336-.273l.129-.143q.066 0 .13-.002c.402.289.853.099 1.28.137");
}

.t-b9n-b0p {
  fill: var(--svg-color--d2010b, #d2010b);
  d: path("m33.518 35.941l.243-.025a.5.5 0 0 1 .355-.081q.09.034.146.114c.031.096.022.183-.057.255c-.249-.015-.523.11-.73-.134c.009-.043.027-.088.043-.129");
}

.t080y8b9e {
  fill: var(--svg-color--e00014, #e00014);
  d: path("M21.49 27.26c.022-.256-.057-.521.085-.793c.319.071.153.336.205.504q-.006.28-.29.289");
}

.t0ueklf-p {
  fill: var(--svg-color--dd010d, #dd010d);
  d: path("M34.641 23.791q-.219.074-.433.143c-.151-.208-.378-.123-.576-.145v-.285c.303.002.61-.012.913.014c.187.011.244.121.096.273");
}

.t4btdzs-g {
  fill: var(--svg-color--641216, #641216);
  d: path("M22.357 16.13q.005.079.006.16c.141.175.164.355.02.541c-.095.005-.191.014-.285.019l-.039-.57z");
}

.t4jh_abhn {
  fill: var(--svg-color--500000, #500000);
  d: path("m31.465 37.37l-.295.139a4 4 0 0 0-.13-.13l.004-.261c.042-.102.084-.211.221-.217a.22.22 0 0 1 .133.086a1 1 0 0 1 .102.23a.24.24 0 0 1-.035.153");
}

.t58ta-o8g {
  fill: var(--svg-color--311519, #311519);
  d: path("M28.429 14.413h-.141c-.436.069-.674-.062-.599-.558c.039-.255.039-.516.055-.773l.11.308c.134.222-.008.581.354.685c.085.044.163.104.241.154a.2.2 0 0 1-.02.184");
}

.t5qx0kbau {
  fill: var(--svg-color--df000b, #df000b);
  d: path("M33.921 17.722c.018-.198-.071-.426.141-.577h.145v.577z");
}

.t7gh09bjp {
  fill: var(--svg-color--5c1012, #5c1012);
  d: path("M35.38 23.764c.47.068.939.093 1.404-.021c.1.062.175.136.206.249c-.088.225-.28.213-.468.201c-.319-.098-.657-.041-.979-.117a.4.4 0 0 1-.188-.121l.014-.059q-.062-.05-.038-.092q.026-.04.049-.04");
}

.t7ul9dwso {
  fill: var(--svg-color--f6d334, #f6d334);
  d: path("M33.08 41.44a.2.2 0 0 0-.025.098c-.155.248-.407.281-.665.297a.48.48 0 0 1-.36-.204c-.081-.216.079-.308.215-.409c.055-.037.109-.066.168-.098q.21-.096.373-.26a.7.7 0 0 1 .152-.104c.174-.068.346-.127.532-.153a.5.5 0 0 1 .184.043a.36.36 0 0 1 .168.23c-.011.105-.071.179-.153.244c-.165.159-.439.118-.589.316");
}

.taye5rbui {
  fill: var(--svg-color--c69e65, #c69e65);
  d: path("M31.482 42.875a.3.3 0 0 1 .135.014a.63.63 0 0 1 .178.461c-.006 1.32.082 2.645-.049 3.968a.4.4 0 0 1-.172.204a1 1 0 0 1-.135-.029z");
}

.tcgdayxyc {
  fill: var(--svg-color--d10510, #d10510);
  d: path("M42.3 36.791q.005-.14.004-.285h1.732c-.039.356-.313.285-.537.289c-.398.006-.799 0-1.199-.004");
}

.tckys5ykf {
  fill: var(--svg-color--2d0807, #2d0807);
  d: path("M22.673 22.766c-.077.132-.146.079-.21-.01l.021-5.571q-.048-.282.211-.157a.6.6 0 0 1 .119.234c.076 1.548.015 3.101.033 4.646q0 .193-.008.387a.74.74 0 0 1-.166.471");
}

.te29gwklq {
  fill: var(--svg-color--410a09, #410a09);
  d: path("m20.04 25.09l-.002-.285l.068-.063a.28.28 0 0 1 .269.04a.5.5 0 0 1 .079.171q.029.143-.004.284c-.035.135-.135.205-.25.264q-.08.022-.153.04q-.002-.227-.007-.451");
}

.tesv_cbqg {
  fill: var(--svg-color--5b0e0f, #5b0e0f);
  d: path("M43.89 36.2a.85.85 0 0 1-.146-.547c.308-.082.448.262.718.279a.14.14 0 0 1-.012.134c-.046.077-.075.163-.15.222a.42.42 0 0 1-.272.027a.25.25 0 0 1-.138-.115");
}

.tewtk3b0w {
  fill: var(--svg-color--710000, #710000);
  d: path("M28.472 15.301c-.066.31-.23.107-.206.011c.074-.263.08-.511.011-.769a.13.13 0 0 0 .011-.13a.17.17 0 0 1 .171-.044a.46.46 0 0 1 .192.205a.77.77 0 0 1-.009.663a.17.17 0 0 1-.17.064");
}

.tfq59lbhy {
  fill: var(--svg-color--c10813, #c10813);
  d: path("m43.721 24.07l.168.161c-.067.245-.291.272-.48.356a.6.6 0 0 1-.311.027c-.264-.092-.582-.002-.801-.245l-.003-.284q.58-.013 1.154-.021z");
}

.th4xu4b6e {
  fill: var(--svg-color--cd060b, #cd060b);
  d: path("M32.617 13.965c.201-.15.119-.374.149-.572l.833-.003c-.041.141-.088.283.043.411l-.158.309c-.243-.313-.627.203-.867-.145");
}

.tho47bbah {
  fill: var(--svg-color--6e0000, #6e0000);
  d: path("m36.929 23.94l-.147-.197c-.002-.265-.191-.572.161-.761l.013.811c.038.059.033.108-.027.147");
}

.tq7tv-lvt {
  fill: var(--svg-color--c2a26f, #c2a26f);
  d: path("M31.15 39.4c.006-.486.016-.972.02-1.458l-.001-.229q-.046-.035-.003-.074c.201-.027.249.122.303.266c.07.316 0 .65.09.965a1 1 0 0 1 .031.316a.5.5 0 0 1-.07.199a.3.3 0 0 1-.182.092c-.034-.005-.069-.007-.104-.016q-.043-.029-.084-.061");
}

.tyix493an {
  fill: var(--svg-color--9d0002, #9d0002);
  d: path("m29.3 35.787l-2.02-.007q-.002-.068.004-.133c.188-.005.376-.007.565-.014c.422-.329.915-.144 1.376-.192c.214.002.427.01.613.133c.071.066.087.137.06.229c-.203.068-.4.093-.597-.016");
}

.tyr69hl9x {
  fill: var(--svg-color--790304, #790304);
  d: path("m27.11 35.923l-.565.007c-.048-.342.511-.244.437-.602c.064-.078.11-.053.153.021c.075.081.157.157.19.269a.3.3 0 0 1-.008.168c-.054.067-.137.087-.207.137");
}

.tz6fo_f_r {
  fill: var(--svg-color--a8ab73, #a8ab73);
  d: path("M31.605 37.09c.043-.083.117-.158.195-.108c.088.06-.006.086-.055.106l-.068.059z");
}

.tzkomgyxz {
  fill: var(--svg-color--fde018, #fde018);
  d: path("M29.583 40.27v.141q-.142.126-.279 0a.5.5 0 0 1 0-.131q.137-.007.279-.01");
}

.u_if08bng {
  fill: var(--svg-color--6c0103, #6c0103);
  d: path("M19.758 36.19c-.027-.295.336-.211.406-.408l.037-.018c.258-.004.528-.059.747.145a.32.32 0 0 1-.004.328a.6.6 0 0 1-.314.143c-.271.021-.545.045-.797-.096a1 1 0 0 1-.075-.094");
}

.u_it44t3n {
  fill: var(--svg-color--700, #700);
  d: path("m31.19 13.258l.14-.104c.172.143.031.361.125.519v.087a.5.5 0 0 1-.071.157q-.033.027-.071.053c-.094-.103-.189-.2-.287-.304c-.075-.068-.087-.156-.061-.256c.048-.088.144-.111.225-.152");
}

.u0xtsgb3c {
  fill: var(--svg-color--fed271, #fed271);
  d: path("m29.29 40.674l-.062.013l-.058-.007c-.02-.045-.014-.084.007-.126q.058.003.116 0l.047.06z");
}

.u3gtt3bhe {
  fill: var(--svg-color--800, #800);
  d: path("M25.398 37.34c-.108-.376-.423-.244-.665-.248c-.983-.018-1.968-.02-2.953-.024c-.037-.09-.011-.163.069-.214c.742-.219 1.501-.062 2.248-.109c.354-.021.709.045 1.056-.059c.141-.064.261-.166.408-.22q.126-.012.201.101c.118.328.143.63-.23.82a.18.18 0 0 1-.134-.047");
}

.u5x0o3mff {
  fill: var(--svg-color--d9000e, #d9000e);
  d: path("m37.1 32.03l.004.437l-.015 2.295c-.31-.135-.272-.41-.272-.668l.005-2.203z");
}

.u637l20ct {
  fill: var(--svg-color--dd000f, #dd000f);
  d: path("M41.43 30.728c.199-.036.36.067.518.161c.18-.223-.137-.671.352-.738c.249.349.184.74.068 1.095c-.084.272.119.252.217.351v.578c-.131.102-.155.298-.331.354c-.259.046-.404-.129-.56-.278c-.183.306-.025.649-.1.965c-.039.162-.046.385-.242.391c-.191.007-.238-.205-.279-.371c-.01-.266.017-.531-.021-.793c-.224-.652-.101-1.225.378-1.715");
}

.u65_2ubwn {
  fill: var(--svg-color--95060f, #95060f);
  d: path("M37.1 34.914c-.005-.055-.006-.104-.011-.156c-.257-.707-.091-1.438-.118-2.158c.05-.218.123-.414.396-.426l.011 2.305z");
}

.u7su8offd {
  fill: var(--svg-color--c00914, #c00914);
  d: path("M30.449 36.523q.15-.017.299-.037q.126-.071.271-.106q.15-.014.283.06a.6.6 0 0 1 .212.32a.3.3 0 0 1-.022.187q-.082.065-.169.004l-.279.163c.034-.432-.593-.195-.595-.591");
}

.uaw5f4dtq {
  fill: var(--svg-color--270707, #270707);
  d: path("M30.741 17c-.27-.139-.445-.127-.435.244c.007.488.004.98.004 1.471a.6.6 0 0 1-.123.014c0-.67-.003-1.333-.003-2c.229.007.521-.125.557.271");
}

.ubu8chb1f {
  fill: var(--svg-color--600d0e, #600d0e);
  d: path("m33.34 36.36l-.002.132l-.284.028l-.018-.035c-.091-.092-.19-.174-.229-.301a2.3 2.3 0 0 1-.109-.57a.4.4 0 0 1 .314-.349a.4.4 0 0 1 .196.024c.216.129.276.354.34.575a.6.6 0 0 1 .006.19c-.029.134-.124.216-.214.306");
}

.ucccejbvq {
  fill: var(--svg-color--e0b366, #e0b366);
  d: path("m28.591 49.563l.274.115c.098.34.055.666-.096.982q-.095.096-.189-.004l-.014.012a1.77 1.77 0 0 1 .002-1.031q.036-.03.023-.074");
}

.uf1_3yb_o {
  fill: var(--svg-color--890003, #890003);
  d: path("m28.472 15.301l.052-.039a1.02 1.02 0 0 1 .602-.195c1.891-.004 3.779-.02 5.667.012a.7.7 0 0 1 .276.07q.142.062.139.221q-.14.1-.275.202l-.159.129a.56.56 0 0 1-.307.084a4 4 0 0 0-.224-.021c-1.577-.007-3.155-.036-4.728.016a.6.6 0 0 0-.175.111q-.076.074-.158.129a.26.26 0 0 1-.188-.005c-.117-.093-.084-.262-.176-.366a.22.22 0 0 1-.104-.1c-.107-.059-.276-.05-.242-.248");
}

.uj9lri19y {
  fill: var(--svg-color--bc171c, #bc171c);
  d: path("M37.702 25.825a1 1 0 0 1-.006-.142c.894-.193 1.796-.062 2.692-.074c.731-.011 1.467-.092 2.2.059a1 1 0 0 0 .017.137l-.029.014c-1.625.373-3.25.365-4.874.006");
}

.ujgid--jj {
  fill: var(--svg-color--820000, #820000);
  d: path("M22.379 14.973q.063-.073.129-.143c.082-.078.16-.078.217.031l.06.409q.08.114-.027.197a.4.4 0 0 1-.341.004c-.183-.155-.215-.319-.038-.498");
}

.ujpjyac4z {
  fill: var(--svg-color--451c02, #451c02);
  d: path("M30.731 38.14q.22-.096.437-.197c.317.395.193.842.145 1.277a.5.5 0 0 1-.118.199a.9.9 0 0 1-.399.185a.4.4 0 0 1-.206-.03q-.052-.06-.035-.121q.02-.062.034-.063c.295-.387.802-.75.142-1.25");
}

.ujr97ccby {
  fill: var(--svg-color--79181c, #79181c);
  d: path("m37.951 37.35l.176.026q-.014.072-.031.141c-1.643.157-3.291.027-4.934.069c-.152-.004-.284-.033-.269-.227a.6.6 0 0 1 .235-.146c1.43-.095 2.862-.027 4.291-.036c.196 0 .382.039.532.173");
}

.uk35dwb6e {
  fill: var(--svg-color--8b0607, #8b0607);
  d: path("M25.532 37.38c.17-.266.155-.564.149-.861a.25.25 0 0 1 .191-.082q.112.015.165.121c.066.26-.028.506-.071.758c-.068.121-.09.318-.311.2c-.037.005-.075-.005-.11-.012a.6.6 0 0 0-.013-.124");
}

.umya9db-n {
  fill: var(--svg-color--ba9500, #ba9500);
  d: path("M32.15 50.961a2 2 0 0 0-.11-.143c-.292-.906-.146-1.844-.185-2.763c-.063-1.501-.023-3.01-.015-4.515c0-.084.001-.175.011-.26a.7.7 0 0 1 .111-.367q.087-.116.217-.046q.016 3.466.027 6.931c-.016.387-.038.774-.056 1.163");
}

.unmhpucvu {
  fill: var(--svg-color--8a0a0b, #8a0a0b);
  d: path("M26.84 22.619c.052.125.069.252.006.38c.113.302.042.618.061.923a.2.2 0 0 1-.08.188c-.367-.013-.252-.407-.438-.556c-.056-.051-.113-.099-.196-.071c-.079.145-.015.286 0 .425l.013.102c0 .07-.008.134-.02.203c-.083.339.055.721-.21 1.02c-.077.043-.141.032-.201-.031c-.019-.19-.035-.383-.064-.573c.066-.188.005-.394.101-.577l.004-.842c.021-.48-.189-.961-.009-1.443c-.079-.225-.066-.455-.027-.686c.352-.129.314.172.353.342c.066.294.01.602.047.9a.4.4 0 0 0 .078.162c.167.159.417-.028.582.134");
}

.unp1e-soa {
  fill: var(--svg-color--420305, #420305);
  d: path("m37.959 35.955l.003.534l-.282.002c-.175-.181-.332-.362-.004-.545z");
}

.uolpueb_d {
  fill: var(--svg-color--c6b232, #c6b232);
  d: path("M31.924 36.04a1 1 0 0 0 .127.027q.038.042.033.086q-.004.049-.016.048c-.011.099-.018.196-.03.294c-.199.004-.398-.014-.568-.139l-.003-.148q.014-.046.026-.094a.4.4 0 0 1 .149-.125a.37.37 0 0 1 .282.051");
}

.usugfeb7r {
  fill: var(--svg-color--3b0608, #3b0608);
  d: path("M31.03 29.874a11 11 0 0 1-.317-.031a.22.22 0 0 1-.025-.188l.069-.067l.854-.003c-.058.364-.364.239-.581.289m2.05-.036c-.106.014-.215.024-.319.034c-.222-.039-.423-.116-.578-.285l.846.004q.035.032.074.063a.22.22 0 0 1-.023.184");
}

.ututh_bve {
  fill: var(--svg-color--c80912, #c80912);
  d: path("m31.896 15.12l-.145-.432q.414.02.434.434q-.147-.003-.289-.002");
}

.uv0_cac4p {
  fill: var(--svg-color--de020a, #de020a);
  d: path("M28.424 13.971c-.125-.004-.238-.033-.311-.148c.032-.192 0-.437.311-.426z");
}

.v03z67shi {
  fill: var(--svg-color--6a0001, #6a0001);
  d: path("M26.691 36.493v-.26c.097 0 .196-.005.296-.005c1.05.074 2.095-.125 3.143-.104c.146-.057.295-.102.452-.117c.343.085.457.25.182.547a.3.3 0 0 1-.314-.031z");
}

.v16bdhhwz {
  fill: var(--svg-color--4f3f18, #4f3f18);
  d: path("M32.464 36.813a20 20 0 0 0-.426-.016a.45.45 0 0 1-.134-.27a.66.66 0 0 1 .051-.303a.54.54 0 0 1 .211-.221a.5.5 0 0 1 .298-.035a.31.31 0 0 1 .216.186c.044.136-.043.246-.065.367q-.073.145-.151.292");
}

.v4vnp01od {
  fill: var(--svg-color--c70b0f, #c70b0f);
  d: path("m20.04 23.793l-.424-.002v-.289q.209.003.418.002c.003.1.003.193.006.289");
}

.v7pelh1pd {
  fill: var(--svg-color--d40108, #d40108);
  d: path("M41.864 14.828c.043.289.198.563.128.865c-.379.1-.547-.14-.687-.423c-.097-.504.242-.457.559-.442");
}

.v8r_c2b1i {
  fill: var(--svg-color--842e06, #842e06);
  d: path("M29.322 50.07a1 1 0 0 0-.025.126c-.214-.141-.068-.373-.146-.547c.292.046.08.293.171.421");
}

.v9ru6hbyx {
  fill: var(--svg-color--dd030b, #dd030b);
  d: path("M26.407 23.35c-.031.23.094.536-.294.591h-.003c-.093-.24-.117-.476.015-.71c.117-.018.22.003.282.119");
}

.va62r9bea {
  fill: var(--svg-color--db010a, #db010a);
  d: path("M33.771 16.566a3 3 0 0 0-.163.028l-.081-.028a.32.32 0 0 0-.376.002l-.079.023l-.309-.021c.05-.186-.27-.458.039-.537c.303-.084.666-.072.965.02c.236.073.186.336.004.513");
}

.vf1mr1hlb {
  fill: var(--svg-color--b5b375, #b5b375);
  d: path("M31.31 39.4q-.008.142-.014.285q-.046.082-.103.002l.007-.295a1 1 0 0 0 .11.008");
}

.vf8t5-jzb {
  fill: var(--svg-color--d1050a, #d1050a);
  d: path("M37.551 31.31c-.057-.005-.111-.005-.165-.011q.259-.605.867-.865c.26-.181.492-.449.866-.289c.215.327.541.303.867.289l-.01.311c-.891-.166-1.723-.075-2.425.565");
}

.vgz751b_f {
  fill: var(--svg-color--5c0002, #5c0002);
  d: path("M28.72 23.21c-.079.287.146.679-.291.842l-.013-.282c.046-.239-.148-.524.134-.718z");
}

.vhsqu8b2m {
  fill: var(--svg-color--c90811, #c90811);
  d: path("M29.987 13.673q.003-.072.009-.145c-.025-.136.057-.197.162-.235a.4.4 0 0 1 .303.047c.142.227.283.448.609.294c.214.056.281.216.294.415a.27.27 0 0 1-.149.172c-.313.123-.644.07-.965.09c-.592-.045-1.191.098-1.776-.107a.43.43 0 0 1-.165-.203c-.07-.225-.065-.442.088-.638c.17-.108.332-.097.48.042q.06.059-.003.111c-.133.25.058.3.223.293c.3-.01.63.129.89-.136");
}

.vhwpb8-ey {
  fill: var(--svg-color--4f090f, #4f090f);
  d: path("M41.02 15.168q-.007-.314-.021-.627c.4-.08.795-.078 1.168.109l-.015.057q.053.056.041.113q-.018.058-.033.057a.55.55 0 0 1-.269.102c-.22.012-.399.088-.526.277a.34.34 0 0 1-.167.082c-.101-.013-.185-.04-.178-.17");
}

.vileadb9t {
  fill: var(--svg-color--2c0000, #2c0000);
  d: path("M32.07 36.2a.24.24 0 0 1-.018-.134a1 1 0 0 0 .104.008z");
}

.vjf4klw0n {
  fill: var(--svg-color--b80a12, #b80a12);
  d: path("m41.996 15.963l-.006-.27c-.178-.268-.321-.541-.126-.865l.281.035a1.7 1.7 0 0 1-.001 1.105z");
}

.vkizorbrz {
  fill: var(--svg-color--915329, #915329);
  d: path("M28.58 50.656q.072-.005.146-.008c.236-.203.525-.17.806-.179c.228 0 .457.005.684.005c.216.008.433.009.65.029a.7.7 0 0 1 .204.052a.26.26 0 0 1 .131.153c-.879.131-1.754.228-2.621-.052");
}

.vkrsz3kfx {
  fill: var(--svg-color--c80912, #c80912);
  d: path("M30.16 14.83c.045-.09.094-.18.137-.272c.101 0 .198 0 .299.002l-.006.271z");
}

.vm4tb451s {
  fill: var(--svg-color--d0030d, #d0030d);
  d: path("M23.23 24.08c-.169-.035-.381.084-.504-.145c.117-.229.333-.106.498-.146z");
}

.vmbkrwx-c {
  fill: var(--svg-color--ca050e, #ca050e);
  d: path("M31.03 13.39v.276c-.025.242-.168.34-.388.267c-.278-.09-.16-.346-.19-.543c.193-.179.387-.15.578 0");
}

.vn67v2byj {
  fill: var(--svg-color--010000, #010000);
  d: path("M37.675 33.1c.101-.499-.178-1.101.299-1.663c.428-.507.956-.52 1.417-.38c.42.129.867.286 1.02.993c.16.746.056 1.459.15 2.18c.055.395-.115.566-.527.552c-.55-.024-1.107-.048-1.656.002c-.602.057-.764-.201-.709-.744c.032-.286.006-.58.006-.94");
}

.vt9u718fn {
  fill: var(--svg-color--f9d92d, #f9d92d);
  d: path("M30.445 50.37c-.043.09-.091.183-.135.273q-.366-.004-.73-.005l-.143-.255c.334-.133.67-.107 1.01-.013");
}

.vu6od9r4i {
  fill: var(--svg-color--d30312, #d30312);
  d: path("M21.2 36.24c-.029.318.474.22.433.551h-.724c-.151-.105-.422-.092-.386-.384a.35.35 0 0 1 .098-.174c.098-.014.192-.022.29-.034c.106-.07.206-.056.289.041");
}

.vu9a_-wpy {
  fill: var(--svg-color--560000, #560000);
  d: path("M21.481 14.883c.11-.6.562-.279.878-.325c.122.067.23.141.21.304a.235.235 0 0 1-.218.176c-.199-.006-.394-.031-.593-.047a.8.8 0 0 1-.277-.108");
}

.vwedo7bxu {
  fill: var(--svg-color--950001, #950001);
  d: path("M29.14 15.984q0 3.327.003 6.648c-.043.061-.085.059-.13.002v-6.646q.064.001.127-.004");
}

.vwx169bvd {
  fill: var(--svg-color--d40616, #d40616);
  d: path("M23.796 15.393a1 1 0 0 0 .007-.095a.3.3 0 0 1 .126-.042c.143-.047.188.02.165.154v.288q.128.142-.002.273c-.771-.05-1.564.198-2.314-.162l.024-.958c.204-.023.421-.1.577.121c-.021.166-.047.332.125.443c.072.064.164.088.251.119c.251.039.5.019.747.019c.124-.006.227-.052.294-.16");
}

.vwyk2gufj {
  fill: var(--svg-color--d2040a, #d2040a);
  d: path("M34.493 19.17h-.287c-.344-.422-.145-.924-.198-1.385c.001-.215-.005-.431.033-.646c.072-.214.149-.428.45-.282q.003 1.155.002 2.313m-1.143 1.154c.517.151.186.58.286.866c.262.385.191.77 0 1.154l-.006.005a8 8 0 0 0-.263-.005z");
}

.vxjvnhbih {
  fill: var(--svg-color--400406, #400406);
  d: path("M33.608 16.595q.004 1.055.004 2.118c-.445.09-.616-.1-.59-.543c.031-.523.033-1.051.05-1.578l-.014-.014c.189-.167.374-.176.554.01z");
}

.vxpxynrjo {
  fill: var(--svg-color--770608, #770608);
  d: path("M36.51 35.36c.057 0 .108 0 .165.004c.138.094.324.121.413.291q.15.135.298.273l-.001.289q-.069.078-.162.041a3.6 3.6 0 0 0-.675-.232a1 1 0 0 1-.315-.182a.25.25 0 0 1-.043-.177c.052-.158.153-.272.32-.307");
}

.vy1j_obms {
  fill: var(--svg-color--be1019, #be1019);
  d: path("M42.591 26.1c.232.215.138.495.138.744c.007 2.293 0 4.586.007 6.878c.003.251-.085.531.117.755l-.017.295c-.134.082-.25.07-.341-.066c-.227-.823-.056-1.662-.11-2.49c-.006-.219.003-.438-.002-.654c.002-.573.009-1.149-.004-1.721a47 47 0 0 1-.002-2.559c.015-.406-.101-.832.214-1.182");
}

.vyp0r4bql {
  fill: var(--svg-color--88211e, #88211e);
  d: path("m30.459 49.23l.567-.005q.004.068.003.135q-.284.008-.572.012a.5.5 0 0 1 .002-.142");
}

.w_0owbc8f {
  fill: var(--svg-color--d9020b, #d9020b);
  d: path("M30.449 19.746c-.437-.088-.597-.728-1.15-.578v-.576h.571a.6.6 0 0 1 .248.035l.155.047a.57.57 0 0 0 .393-.025c.229-.168.139-.526.4-.674c.447.143.376.627.599.915c.07.232-.008.43-.156.604c-.24.158-.456.361-.768.381a.46.46 0 0 1-.292-.129");
}

.w_9fe_a2n {
  fill: var(--svg-color--655400, #655400);
  d: path("M31.467 37.27a4 4 0 0 1-.139-.197a.12.12 0 0 1 .135-.032l.005.062q.068.036.046.071t-.046.036z");
}

.w-s452bsw {
  fill: var(--svg-color--530000, #530000);
  d: path("M30.18 39.699a3 3 0 0 1-.165-.018c.11-.258.328-.293.568-.293q.006.063.008.121c-.067.217-.192.304-.411.19");
}

.w3-7rj__j {
  fill: var(--svg-color--ca040e, #ca040e);
  d: path("M30.449 19.746q.155.006.313.008c.066.1.054.193-.024.281c-.324.154-.278.463-.286.741c-.016.612-.021 1.227-.034 1.843l-.255-.27c0-.449.011-.898-.004-1.345c-.016-.447-.004-.884.29-1.258");
}

.w3zc6pbra {
  fill: var(--svg-color--b80a12, #b80a12);
  d: path("M37.1 15.535c.432-.018.885.158 1.294-.123a1 1 0 0 0 .132-.026c-.01.413-.33.286-.56.321c-.286-.07-.627.132-.866-.172");
}

.w3ztqxbhc {
  fill: var(--svg-color--d2030d, #d2030d);
  d: path("m31.04 37.37l-4.515.015c-.243.002-.479-.002-.688-.146c-.068-.26.113-.477.145-.721a.4.4 0 0 1 .204-.142c.211-.015.42-.029.632-.065c1.17.012 2.34-.072 3.51.05c.287.212.735.224.828.673c.01.126-.016.247-.116.336");
}

.w4ldrtlor {
  fill: var(--svg-color--d30310, #d30310);
  d: path("M37.39 22.632q0-.431-.003-.864h.289c.041.334.301.738-.286.864");
}

.w528eebnh {
  fill: var(--svg-color--db000a, #db000a);
  d: path("M28.14 33.762q.002-.56 0-1.124c-.003-.214-.007-.433.287-.464q.345 1.153 0 2.31h-.287z");
}

.w52a-9b1v {
  fill: var(--svg-color--520f10, #520f10);
  d: path("M25.408 15.412q.001-.077-.004-.15c.456-.053 1.219.363 1.021-.674a.3.3 0 0 1 .126-.008c.125.098.234.206.266.371c.033.215 0 .408-.19.548c-.419.13-.832.208-1.219-.087");
}

.w7s__9bmq {
  fill: var(--svg-color--ba0e13, #ba0e13);
  d: path("M26.652 14.836q.24-.005.478-.006c-.032.273.13.688-.421.58l-.047-.004z");
}

.wagn8ibzz {
  fill: var(--svg-color--200304, #200304);
  d: path("M25.545 20.602q.133.02.27.043a.24.24 0 0 1 .105.143c.015.098 0 .187-.073.258q-.017.36-.041.721c-.206-.136-.037-.451-.269-.575h.003c0-.2.001-.393.005-.59");
}

.wb5o4966q {
  fill: var(--svg-color--d5020f, #d5020f);
  d: path("M42.3 32.459c.004-.184.097-.283.285-.285v2.598l-.578.002c.062-.774-.051-1.573.293-2.315m.286-.863c-.207-.047-.33.32-.492.17c-.197-.189.031-.369.126-.561c.17-.328.049-.702.081-1.055q.005-.282.282-.291q0 .87.003 1.737");
}

.wc7jfvn5k {
  fill: var(--svg-color--5b0103, #5b0103);
  d: path("m20.913 25.664l-.14.015c-.154-.187-.401-.054-.574-.177q.067-.13.139-.261c.252-.091.479-.091.646.165a.26.26 0 0 1-.071.258");
}

.wdg38l4ik {
  fill: var(--svg-color--ae0914, #ae0914);
  d: path("M31.602 16.262a1 1 0 0 0-.008-.135c.261-.205.487-.24.621.137l-.027.014c-.198.092-.395.171-.586-.016");
}

.wev3glbvx {
  fill: var(--svg-color--d2040d, #d2040d);
  d: path("m27.565 34.771l.283.002c.226.063.46.118.629.299a.26.26 0 0 1-.042.289c-.288.201-.576-.082-.861-.011z");
}

.wl0b6yb_i {
  fill: var(--svg-color--f1d529, #f1d529);
  d: path("M29.583 48.04v-.246c.524.013 1.065-.152 1.571.118l.001.145c-.219.018-.411.137-.626.176c-.308-.1-.679.108-.946-.193");
}

.wm0m7rbgk {
  fill: var(--svg-color--732f08, #732f08);
  d: path("M33.05 36.521c-.03.281-.127.566.019.842q-.085.003-.163.011a6 6 0 0 0-.271.013a.38.38 0 0 1-.245-.128c-.143-.169-.13-.349-.039-.534a.66.66 0 0 1 .258-.288a.41.41 0 0 1 .378.011q.032.034.063.073");
}

.wmfji_bpl {
  fill: var(--svg-color--432222, #432222);
  d: path("M32.496 13.14c.64-.351 1.279-.237 1.389.24c-.07.09-.158.082-.249.053a1.4 1.4 0 0 1-.165-.085c-.258-.131-.545-.048-.813-.114a.5.5 0 0 1-.162-.094");
}

.wmoyyhzxa {
  fill: var(--svg-color--cda85b, #cda85b);
  d: path("M32.479 39.97q-.003.075-.002.146q-.076 0-.15-.002l.008.011q-.068-.212.149-.17z");
}

.wo8o4lcba {
  fill: var(--svg-color--831b1c, #831b1c);
  d: path("M21.496 23.502c-.193-.917.619-.529.967-.746c.1.055.178.017.24-.066c.16-.068.341-.094.478-.217c.128-.08.243-.269.416-.063c.104.199.104.414.101.634a.8.8 0 0 1-.111.417c-.173.172-.32-.014-.478-.034c-.638-.095-1.124.155-1.489.669c-.191-.169.038-.42-.124-.594");
}

.wse-it1py {
  fill: var(--svg-color--370607, #370607);
  d: path("m33.05 37.525l-.001.123c-.079.061-.257-.031-.247.162c-.102.084-.212.09-.326.034c-.15-.208-.067-.368.103-.511a.29.29 0 0 1 .33.04q.068.077.141.152");
}

.wvzxrpbgy {
  fill: var(--svg-color--5e0001, #5e0001);
  d: path("M26.979 16.13q.277.218 0 .43c-1.189-.115-2.384-.041-3.577-.066c-.331-.006-.673.034-.981-.133c-.083-.062-.106-.135-.063-.229z");
}

.ww_xhl_sm {
  fill: var(--svg-color--cd050f, #cd050f);
  d: path("m35.06 23.94l-.277.14c-.182.062-.21-.09-.273-.194c-.205-.378-.689-.081-.926-.384c-.046-.107-.038-.199.049-.281c.231-.002.469.018.697-.012c.574-.076.839.136.73.731");
}

.wx39vnh-c {
  fill: var(--svg-color--4e0b0f, #4e0b0f);
  d: path("M43.45 23.934q.001.066-.002.129c-.381.314-.765.271-1.154.021l.021-.016c.352-.263.759-.076 1.135-.134");
}

.wxpn03o9p {
  fill: var(--svg-color--d2040a, #d2040a);
  d: path("m33.635 18.879l-.022-.166c-.33-.674-.242-1.36-.066-2.048a.22.22 0 0 1 .226-.099c.004.119.029.227.146.288c.115.062.142.169.144.29c-.007.201.031.416-.141.577c-.087.386.187.867-.287 1.158");
}

.wxxye6b7n {
  fill: var(--svg-color--760103, #760103);
  d: path("M21.777 36.24q-.07-.02-.141-.036c-.076-.148.05-.189.133-.25q1.889-.006 3.776-.005l-.027.291z");
}

.wyupfzb5a {
  fill: var(--svg-color--5b0203, #5b0203);
  d: path("M26.56 36.22a1 1 0 0 1 .132.021q.129.127 0 .258l-.581-.007c.011-.111.036-.213.147-.271z");
}

.wznq4j3gt {
  fill: var(--svg-color--3b0b01, #3b0b01);
  d: path("M31.47 36.36q-.078.081-.159.159l-.277-.032l-.004-.421a.17.17 0 0 1 .152-.052a.64.64 0 0 1 .286.186a.15.15 0 0 1 .002.16");
}

.x_v9mmb7j {
  fill: var(--svg-color--560000, #560000);
  d: path("m23.982 14.707l-.031-.149h1.293l-.023.154c-.413.196-.826.273-1.239-.005");
}

.x--lnxb5y {
  fill: var(--svg-color--b92229, #b92229);
  d: path("m21.481 14.883l.32-.031c.218.324.233.647-.024.958q-.058.075-.119.143c-.229-.315.035-.711-.175-1.028z");
}

.x5nzi2bws {
  fill: var(--svg-color--3b1d21, #3b1d21);
  d: path("m43.76 24.807l-.16-.137c.098-.137.238-.157.392-.157a.46.46 0 0 1 .292.138l.184.007c-.182.309-.477.09-.708.149");
}

.x79uhu9pp {
  fill: var(--svg-color--4e0e01, #4e0e01);
  d: path("m31.31 47.19l.013.299q.057.127-.055.212a.7.7 0 0 1-.218.094c-.795.072-1.59-.007-2.381.054a.45.45 0 0 1-.236-.036c-.086-.103-.101-.208.007-.31c.706-.01 1.417-.027 2.126-.023c.297.003.564-.016.744-.29");
}

.x79yrfbvp {
  fill: var(--svg-color--d1030c, #d1030c);
  d: path("m42.3 36.791l-2.601-.003q-.127-.14 0-.282c.868-.01 1.735.15 2.604 0c.083.097.085.193-.003.285");
}

.x9vgv7yao {
  fill: var(--svg-color--590000, #590000);
  d: path("M25.656 37.519c.133-.042.172-.149.181-.272c.632-.207 1.281-.08 1.922-.086c1.029-.008 2.057-.051 3.086.029c.13.025.247.073.342.176a.34.34 0 0 1 .046.242c-.021.037-.043.068-.065.105c-1.598-.014-3.197-.021-4.796-.049c-.239-.002-.53.147-.716-.145");
}

.xe8a1e11o {
  fill: var(--svg-color--c1060e, #c1060e);
  d: path("M26.383 31.604c.414.021.28.338.309.57h-.248q-.032-.287-.061-.57");
}

.xg0w983or {
  fill: var(--svg-color--d7020b, #d7020b);
  d: path("M27.56 24.371c.433-.051.901.135 1.288-.234c.094-.092.309-.081.375.068c.062.139.065.32.052.479c-.015.208-.175.093-.283.122c-.475.134-.949.149-1.432.141q-.23-.287 0-.576");
}

.xh6z57bvn {
  fill: var(--svg-color--d00a19, #d00a19);
  d: path("m35.658 26.08l-7.52.004v-.124h7.514q.001.06.006.12");
}

.xj60ps-1g {
  fill: var(--svg-color--680000, #680000);
  d: path("m44.34 23.01l-.027.207c-.234.174-.412.088-.56-.125c-.048-.052-.1-.102-.147-.151c.257-.095.513-.201.734.069");
}

.xl24-ebmc {
  fill: var(--svg-color--570000, #570000);
  d: path("M25.821 25.24c.052 0 .101-.004.149-.004c.032 0 .064.004.096.004a.47.47 0 0 1 .358.288a.21.21 0 0 1-.054.173c-.093.051-.18.053-.258-.029l-.012.008c-.136-.238-.373-.117-.56-.156l-.013-.15q.077-.07.158-.137c.046-.073.093-.069.136.003");
}

.xmj09uikf {
  fill: var(--svg-color--74070a, #74070a);
  d: path("M30.31 36.23a8.7 8.7 0 0 1-3.321-.005l.864-.021c.174-.15.381-.184.6-.186c.465 0 .934-.01 1.398.006c.175.016.345.049.459.206");
}

.y_ycssxtv {
  fill: var(--svg-color--a61c27, #a61c27);
  d: path("m43.46 24.513l.431-.283l.411.138a9 9 0 0 0-.014.283q-.13-.01-.264-.014c-.17-.124-.399.027-.564-.124");
}

.y0_7i0yyl {
  fill: var(--svg-color--c8040e, #c8040e);
  d: path("M38.11 36.541v.086l-.16.17l-.565-.002a1.1 1.1 0 0 0-.867 0c-.276.002-.565.043-.725-.268c.436-.385.962-.152 1.444-.217q.18 0 .359.008c.118.004.235.023.349.066q.112.048.165.157");
}

.y0-ka7bla {
  fill: var(--svg-color--d2040d, #d2040d);
  d: path("M29.3 31.31a38 38 0 0 0-.007-.581c-.086-.099-.075-.192.002-.29c.205.113.233-.048.347-.17c.303-.32.531-.807 1.112-.684l-.04.259c-.604.171-.972.567-1.138 1.165q-.137.153-.276.301");
}

.y1ukk5bls {
  fill: var(--svg-color--7a1203, #7a1203);
  d: path("m30.16 35.926l-.287-.149l-.009-.118c.054-.096.146-.129.252-.148a.7.7 0 0 1 .202.013a.5.5 0 0 1 .172.108c.041.102.037.199-.035.285z");
}

.y2zy0kecl {
  fill: var(--svg-color--410101, #410101);
  d: path("M22.725 14.861q-.11-.013-.217-.031l-.148-.272c.248-.05.451-.044.365.303");
}

.y3pv4s6yb {
  fill: var(--svg-color--f9e120, #f9e120);
  d: path("M31.452 49.38a.6.6 0 0 0-.124-.022q-.035-.04-.069-.083a.4.4 0 0 1 .008-.211a.65.65 0 0 1 .21-.256c.111-.066.218-.074.32.018c.261.578.137 1.183.107 1.782a.55.55 0 0 1-.12.21a.18.18 0 0 1-.221-.029c-.106-.465.089-.952-.111-1.409");
}

.y3q7lhble {
  fill: var(--svg-color--320304, #320304);
  d: path("m25.25 31.01l-.009-.269q.146-.01.292-.017c.157.038.364.031.267.298l-.269.005q-.142-.006-.281-.017");
}

.y4e8a1b6t {
  fill: var(--svg-color--bc0d15, #bc0d15);
  d: path("M23.796 15.393c.009.129-.01.242-.14.306c-.313-.188-.687.031-1-.134a3 3 0 0 1-.147-.148l.279.008a84 84 0 0 1 1.013-.032");
}

.y4nv5707k {
  fill: var(--svg-color--de000b, #de000b);
  d: path("M25.25 27.26v-.581l.288.002v.579c-.021.103-.019.249-.175.213c-.051-.011-.077-.139-.113-.213");
}

.y6psvfy9r {
  fill: var(--svg-color--0d0303, #0d0303);
  d: path("m29.587 31.884l-.011-.876c-.055-.689.336-1.123 1.153-1.292c.118.016.227.054.302.158c-.025.12-.07.21-.2.26c-.676.261-1.091.714-1.017 1.48c.02.208-.074.247-.227.27");
}

.y6wmsjp6b {
  fill: var(--svg-color--b2141b, #b2141b);
  d: path("m29.14 15.984l.015-.141c.376.057.322.373.326.609c.012.688.048 1.375.02 2.063c.006.22.016.437-.002.658c.01.465.015.931 0 1.398c-.012.362-.006.721-.008 1.086c.002.176-.008.354.005.533c.095.404.344.232.57.148a.32.32 0 0 1 .202-.024c.175.113.27.26.207.476a.5.5 0 0 1-.203.131c-.44.005-.975.299-1.195-.385q-.001-2.92.005-5.841c-.001-.236-.054-.478.058-.711");
}

.yadj_y75b {
  fill: var(--svg-color--bd1320, #bd1320);
  d: path("M31.32 14.11v-.14l-.002-.034c.375-.08.751-.036 1.127-.02c.117.09.121.205.074.334c-.239.235-.527.192-.816.141c-.162-.046-.3-.126-.383-.281");
}

.ych38ym4o {
  fill: var(--svg-color--650101, #650101);
  d: path("M37.09 16.868q2.031.004 4.062.005l-.024.289a.7.7 0 0 1-.359.165c-1.093.063-2.183.046-3.278.013a.73.73 0 0 1-.367-.127c-.108-.105-.123-.219-.034-.345");
}

.yeupdjbzk {
  fill: var(--svg-color--2a080c, #2a080c);
  d: path("M19.498 23.06c0 .438-.005.874-.005 1.31a.3.3 0 0 1 .064.162a.3.3 0 0 1-.07.162a.14.14 0 0 1-.158-.034c.028-.535-.251-1.103.169-1.6");
}

.yh37l7brs {
  fill: var(--svg-color--851115, #851115);
  d: path("M30.589 18.732q.071.073.143.139c-.212-.002-.436.061-.602-.136l.058-.007a.35.35 0 0 1 .156-.094c.097-.007.184.018.245.098");
}

.yhxg62n4y {
  fill: var(--svg-color--5e342e, #5e342e);
  d: path("M20.16 35.785q-.123-.071-.245-.138q.14-.143.274-.29q.153-.056.298-.113a.34.34 0 0 1 .084.182c-.009.201-.118.314-.31.355q-.049.005-.101.004");
}

.yjr8-ac6a {
  fill: var(--svg-color--f6d928, #f6d928);
  d: path("M29.32 48.5a.3.3 0 0 0-.03.127l-.56.063a1.1 1.1 0 0 1 0-.898l.854.007c.076.067.086.151.057.244c-.057.108-.175.146-.255.229c-.032.07-.037.154-.066.228");
}

.ylkxorqyg {
  fill: var(--svg-color--400407, #400407);
  d: path("m22.918 31.877l.029-.263c.064-.104.159-.104.261-.071c.156.143.104.3.045.463a.6.6 0 0 1-.114.162q-.085.062-.176 0l-.051.006c.003-.101.006-.197.006-.297");
}

.ylme6mi_a {
  fill: var(--svg-color--d4020c, #d4020c);
  d: path("M41.15 30.728q-.367.292-.869-.288q.008-.282.289-.289c.48-.096.669.099.58.577");
}

.yqilb5sbk {
  fill: var(--svg-color--870000, #870000);
  d: path("M41.15 15.426q-.01.064-.013.123c-.386.119-.77.127-1.153-.002l.016-.15l.145-.011q.504.019 1 .04");
}

.yrg3ynu1a {
  fill: var(--svg-color--dc000f, #dc000f);
  d: path("M34.785 31.882v-.29c.231-.193.063-.387 0-.575v-.289c.235-.005.439.017.646.188c.209.176.443.155.511-.188c.19.421.067.771-.216 1.11c-.486.58-.524 2.096-.074 2.736c.099.143.105.332.034.396c-.274.24-.354-.213-.596-.206c-.227.004-.194-.108-.145-.327c.201-.859.302-1.73-.16-2.555");
}

.yvbcxhbdw {
  fill: var(--svg-color--0d0303, #0d0303);
  d: path("M30.451 34.918q-.016.1-.028.204a.4.4 0 0 1-.163.057a.44.44 0 0 1-.252-.062c-.061-.063-.081-.15-.133-.221q0-.062-.005-.123c.188.071.5-.361.581.145");
}

.yyntohoua {
  fill: var(--svg-color--c39d53, #c39d53);
  d: path("m30.583 48.2l-.013.153l-.084-.003c-.425-.199-.897.063-1.322-.138c.078-.208.271-.127.419-.165c.326.085.7-.118 1 .153");
}

.yzfmk1b9v {
  fill: var(--svg-color--cc0811, #cc0811);
  d: path("m25.387 36.795l-2.741.002c-.148-.232-.432-.132-.623-.247c-.202-.124-.464-.256-.067-.472c1.123-.109 2.241-.08 3.365-.021c.271.072.287.25.195.475c.004.111-.02.206-.129.263");
}

.z_9fx_b4d {
  fill: var(--svg-color--d80208, #d80208);
  d: path("M23.997 20.06q-.045.135-.086.27c-.39-.039-.749-.047-.69.518c.02.195-.076.32-.283.341c-.153-.628-.033-1.267-.069-1.9c.016-.139.104-.188.23-.197c.196-.021.169.437.462.218a1.7 1.7 0 0 1 .534-.01a.6.6 0 0 1 .286.154c.363.158.27.223-.045.299c-.131.033-.637-.229-.339.307");
}

.z2og57b2y {
  d: path("m33.05 35.35l-.27.292a.36.36 0 0 1-.279.117a.6.6 0 0 1-.199-.053c-.138-.081-.267-.221-.448-.169c-.61.165-1.047-.153-1.469-.519c-.208-.206-.536-.051-.748-.249c-.406-.45-.218-1.01-.244-1.515c-.022-.406-.044-.815.043-1.217c.066-.203.163-.396.179-.62c.065-.862.684-1.267 1.364-1.618c.215-.105.45-.17.646-.316a.8.8 0 0 1 .528-.024c.241.083.463.199.676.333c.734.334 1.222.894 1.52 1.635c.118.922.046 1.852.046 2.779c-.001.273-.124.504-.317.697a5 5 0 0 1-.174.154a.46.46 0 0 1-.201.09a.52.52 0 0 1-.372-.117c-.077-.076-.155-.111-.212.024c-.156.069.022.212-.069.296");
}

.z45zz-bqs {
  fill: var(--svg-color--590703, #590703);
  d: path("M30.611 36.08a.5.5 0 0 1-.022-.13q-.053-.056-.043-.116q.013-.062.028-.063a.36.36 0 0 1 .203-.025c.181.054.314.16.366.351a.42.42 0 0 1-.11.394h-.285c.11-.186.067-.326-.137-.411");
}

.z7etcebbq {
  fill: var(--svg-color--2f1113, #2f1113);
  d: path("M37.12 22.621c-.023.135-.045.265-.185.334c-.005-1.717-.009-3.426-.027-5.141c-.003-.223.12-.477-.104-.668a1 1 0 0 0-.008-.113l.024-.203c.089.014.182.022.273.033l.022.302c.18.192.18.435.184.679q.009 2.049 0 4.101c.001.241-.004.484-.179.676");
}

.zbo16t5_r {
  fill: var(--svg-color--060101, #060101);
  d: path("m40.29 22.345l.017.881c.188.267.172.543.042.825a.4.4 0 0 1-.191.154c-.587.133-1.18.055-1.771.064a.8.8 0 0 1-.376-.115c-.257-.207-.235-.501-.245-.784c-.027-.735.005-1.47 0-2.206c-.005-.365.153-.654.418-.899c.65-.497 1.287-.501 1.911.05c.478.636.508 1.317.195 2.03");
}

.zbr_i0mkn {
  fill: var(--svg-color--af020d, #af020d);
  d: path("m28.421 14.275l-.271-.045c.017-.213.123-.221.276-.119h1.878q.07.126-.048.215c-.396.201-.824.098-1.239.123a.92.92 0 0 1-.596-.174");
}

.zd9q6ob9z {
  fill: var(--svg-color--fce45a, #fce45a);
  d: path("M31.04 41.3q.132-.007.266-.009l.313.398l-.021.328l-.126-.025q-.216-.149-.437-.295a.3.3 0 0 1-.098-.153c-.008-.101.014-.185.103-.244");
}

.zdng0-bsh {
  fill: var(--svg-color--2a0204, #2a0204);
  d: path("m30.425 22.77l-.008-.15c-.239-.641-.172-1.311-.155-1.971c.008-.293.069-.574.427-.648c.293.189.248.498.254.773c.016.67.014 1.336-.061 2.01c-.054.523.175.82.735.797q.29-.014.574 0c.537.021.73-.258.686-.76c-.059-.645-.038-1.289-.035-1.936c.002-.283-.018-.578.168-.828c.297-.119.382.096.479.297c.036.67.192 1.346-.125 1.991q.004.213.005.425q.006.152.01.309a.23.23 0 0 0-.003.141q.294.448-.002.898c-.902.316-1.828.14-2.744.112a.6.6 0 0 1-.223-.132c-.174-.268-.153-.568-.145-.866a.8.8 0 0 1 .163-.462");
}

.zfmsw5c4v {
  fill: var(--svg-color--d30713, #d30713);
  d: path("M36.519 36.795c.287-.218.579-.218.867 0z");
}

.zfza_7b2h {
  fill: var(--svg-color--b0a160, #b0a160);
  d: path("m31.19 36.08l.266.011q.063.041.043.088q-.019.048-.038.048l.01-.014c-.115-.002-.243.029-.281-.133");
}

.zgisxdhit {
  fill: var(--svg-color--c90a17, #c90a17);
  d: path("M22.676 22.347q.275.145.554.288c-.146.215-.361.126-.557.131q.004-.209.003-.419");
}

.zi0nk2bmt {
  fill: var(--svg-color--a00208, #a00208);
  d: path("M35.917 13.822q.02.161.036.324a.2.2 0 0 0 .038.105c-.095.236-.298.145-.469.156a.24.24 0 0 1-.201-.166c-.002-.181.139-.258.261-.35c.102-.061.205-.133.335-.069");
}

.zivd2-eyi {
  fill: var(--svg-color--a0711b, #a0711b);
  d: path("m32.451 37.941l.327.313q-.013.353-.028.705c-.083.09-.182.086-.286.043c-.163-.162-.147-.37-.164-.574l-.036-.284a.4.4 0 0 1 .027-.181c.05-.051.103-.055.16-.022");
}

.zixegbclb {
  fill: var(--svg-color--221800, #221800);
  d: path("M31.33 51.21c-.006-.177-.013-.364-.017-.544c-.273-.33-.188-.703-.143-1.076a.5.5 0 0 1 .129-.209q.12-.076.219.021c.239.457.104.949.129 1.426a1 1 0 0 1-.045.237a.4.4 0 0 1-.145.192a.2.2 0 0 1-.127-.047");
}

.zlrn7wbtc {
  fill: var(--svg-color--dd000c, #dd000c);
  d: path("M33.632 22.345v-1.154h.286q.231.29 0 .577c.039.257.184.57-.286.577");
}

.zqmmthbye {
  fill: var(--svg-color--a91619, #a91619);
  d: path("M26.84 35.06c-.404-.05-.274-.371-.296-.602c-.073-.721.136-1.451-.122-2.158q-.082-.13.06-.185c.134-.025.242.003.307.134c.103.58.024 1.167.05 1.74c0 0-.003-.005.002 0c-.002-.098 0 .022 0-.078c-.039-2.166-.084-4.321-.063-6.48c.006-.287-.02-.577.063-.857a.5.5 0 0 1 .175-.213a.23.23 0 0 1 .222.139c.105.229.092.472.092.712c.002 2.286.005 4.571 0 6.86c-.004.408.044.843-.49.988");
}

.zrhjsob9b {
  fill: var(--svg-color--550101, #550101);
  d: path("M35.645 26.13h1.159l.009.248q-.072.02-.144.045q-.224-.007-.452-.007c-.174.138-.358.144-.551.032c-.091-.097-.095-.207-.021-.318");
}

.zrxbmke-u {
  fill: var(--svg-color--932328, #932328);
  d: path("M35.21 14.555c.18.254.321.508.003.762c-2.228-.127-4.457-.015-6.688-.055q.03-.288.057-.575c.262-.036.391.308.665.231c.865-.003 1.729 0 2.595 0q.185-.004.374-.003c.765-.017 1.533-.001 2.297-.003c.216.021.377-.057.46-.264c.061-.084.122-.156.237-.093");
}

.zv3y8gbde {
  fill: var(--svg-color--6d0000, #6d0000);
  d: path("M26.407 25.529c.208-.242.491-.145.743-.145c2.911-.008 5.824-.004 8.737-.008c.258 0 .53.063.776-.086c.121-.21.278-.133.434-.053q.077.02.157.049q.062.124.128.249z");
}

.zwicqdfbu {
  fill: var(--svg-color--5b2100, #5b2100);
  d: path("M31.01 39.805c.047.094.096.145.173.025c.023-.02.052-.039.077-.059c.033.01.064.012.097.021a.5.5 0 0 1 .141.138q.044.091.044.188c-.033.1-.078.179-.203.131q-.298.012-.593.021c-.125.097-.198.237-.308.347c-.07.065-.146.115-.249.076l-.165-.151l.016-.271q.134-.087.269-.169c.245.021.415-.125.578-.275q.063-.008.123-.022");
}

.zwz5uupji {
  fill: var(--svg-color--d00613, #d00613);
  d: path("M35.652 25.959v-.145c.47.139 1.052-.302 1.441.273l-.29.037c-.298.184-.627.131-.952.123a.5.5 0 0 1-.195-.095q-.086-.094-.004-.193");
}

</style>
