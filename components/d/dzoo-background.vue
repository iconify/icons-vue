<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVG7fVz6dkJ)" class="jkvu0qbcl"/><path class="j-m0hhw-y"/><path fill="url(#SVGrdScBcwQ)" class="ilfv1abuj"/><path class="q6b5xpbvm"/><path fill="url(#SVG217CHbZd)" class="w_6majp2e"/><path fill="url(#SVGZHCIQdXt)" class="rqbmoexfp"/><path fill="url(#SVGJOqkmc4U)" class="i66b3bbhu"/><path fill="url(#SVG7J3YZc4h)" class="fe2_4lvtc"/><path fill="url(#SVGXs0wsdBS)" class="yibznbczh"/><path fill="url(#SVGQp2dAe7D)" class="lepglpb0a"/><path fill="url(#SVGs2tTwcmh)" class="ytqgjacqn"/><path fill="url(#SVGzAHXwc1J)" class="yq73_cb0r"/><path fill="url(#SVG7QIuU93Q)" class="p3nuizb2g"/><path fill="url(#SVGvkVCtbfy)" class="ta5u1bi6v"/><path fill="url(#SVGaGRkedoc)" class="f3hygbbwi"/><path fill="url(#SVGkJAy2Lbl)" class="egh6bb5yn"/><path fill="url(#SVGzSoAR6SG)" class="yovr3_bco"/><path fill="url(#SVG7vgcscda)" class="zuowjgbuw"/><path fill="url(#SVG3l4rJeDk)" class="a9hshccwb"/><path fill="url(#SVG7vgcscda)" class="d1_xg552h"/><path fill="url(#SVGcoiZpduu)" class="r31xx1giy"/><path fill="url(#SVGs2rFocJL)" class="yxac9g_kn"/><path fill="url(#SVGwiZz7b3m)" class="irc-qprcg"/><path fill="url(#SVGwJZ2cbFR)" class="oy6ksjhcs"/><path fill="url(#SVGYbT49cbV)" class="o5-242bqj"/><path fill="url(#SVG9ZTNGIfh)" class="uogvyab2r"/><path fill="url(#SVGkty2Mb6v)" class="uu-s888lj"/><path fill="url(#SVGtcguybCl)" class="ynhv96bge"/><path fill="url(#SVGu8s39cUC)" class="ffo6nhbfx"/><path fill="url(#SVGKWxC5ZOK)" class="rz2_3jbyt"/><path fill="url(#SVGNVRHAeBY)" class="ycq7dq50l"/><path fill="url(#SVGNVRHAeBY)" class="go_9bvvni"/><path fill="url(#SVGb72IabgM)" class="ej7fmlsid"/><path fill="url(#SVGnvcKPbnB)" class="s0z7zengr"/><path fill="url(#SVGLxsGhdMw)" class="aq0ncb0gp"/><path fill="url(#SVGLxsGhdMw)" class="gpc5j-rjo"/><path fill="url(#SVGSyB8Vcbh)" class="v_0-5_bkq"/><path fill="url(#SVGwxe1vbrH)" class="pd6waacyh"/><path class="u8n4wqaek"/></g><defs><linearGradient id="SVG7fVz6dkJ" x1="16.412" x2="12.722" y1="5.144" y2="20.532" gradientUnits="userSpaceOnUse"><stop class="zd_oy2bcr"/><stop offset="1" class="sjwpadc1w"/></linearGradient><linearGradient id="SVGrdScBcwQ" x1="7.588" x2="11.278" y1="5.144" y2="20.532" gradientUnits="userSpaceOnUse"><stop class="zd_oy2bcr"/><stop offset="1" class="sjwpadc1w"/></linearGradient><linearGradient id="SVG217CHbZd" x1="11.979" x2="11.979" y1="4" y2="20.001" gradientUnits="userSpaceOnUse"><stop class="gg6-d6d7t"/><stop offset="1" class="g10mofb-v"/></linearGradient><linearGradient id="SVGZHCIQdXt" x1="7.83" x2="8.476" y1="4.615" y2="20.152" gradientUnits="userSpaceOnUse"><stop class="cfuxozbaa"/><stop offset="1" class="uen05e_tz"/></linearGradient><linearGradient id="SVGJOqkmc4U" x1="12.495" x2="12.495" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="ar-rekq5g"/><stop offset="1" class="stmc-f_0k"/></linearGradient><linearGradient id="SVG7J3YZc4h" x1="12" x2="12" y1="4" y2="19.956" gradientUnits="userSpaceOnUse"><stop class="q71ze8c3q"/><stop offset="1" class="qk9r03bjd"/></linearGradient><linearGradient id="SVGXs0wsdBS" x1="15.213" x2="15.213" y1="3.158" y2="19.158" gradientUnits="userSpaceOnUse"><stop class="ar-rekq5g"/><stop offset="1" class="stmc-f_0k"/></linearGradient><linearGradient id="SVGQp2dAe7D" x1="15.24" x2="15.24" y1="3.16" y2="19.116" gradientUnits="userSpaceOnUse"><stop class="q71ze8c3q"/><stop offset="1" class="qk9r03bjd"/></linearGradient><linearGradient id="SVGs2tTwcmh" x1="5.784" x2="9.672" y1="5.001" y2="21.471" gradientUnits="userSpaceOnUse"><stop class="go__dabhm"/><stop offset="1" class="qr1dcfdvd"/></linearGradient><linearGradient id="SVGzAHXwc1J" x1="12.001" x2="12.001" y1="4.001" y2="20.002" gradientUnits="userSpaceOnUse"><stop class="e75cwpepz"/><stop offset=".57" class="dhqver70j"/><stop offset="1" class="k-ro4xbwj"/></linearGradient><linearGradient id="SVG7QIuU93Q" x1="12" x2="12" y1="3.999" y2="20" gradientUnits="userSpaceOnUse"><stop class="qb3t1zgzw"/><stop offset="1" class="pvxcglwsz"/></linearGradient><linearGradient id="SVGvkVCtbfy" x1="11.987" x2="11.987" y1="3.999" y2="20" gradientUnits="userSpaceOnUse"><stop class="qb3t1zgzw"/><stop offset="1" class="pvxcglwsz"/></linearGradient><linearGradient id="SVGaGRkedoc" x1="21.601" x2="17.716" y1="4.001" y2="20.473" gradientUnits="userSpaceOnUse"><stop class="go__dabhm"/><stop offset="1" class="qr1dcfdvd"/></linearGradient><linearGradient id="SVGkJAy2Lbl" x1="16.193" x2="16.193" y1="3.274" y2="19.274" gradientUnits="userSpaceOnUse"><stop class="e75cwpepz"/><stop offset=".57" class="dhqver70j"/><stop offset="1" class="k-ro4xbwj"/></linearGradient><linearGradient id="SVGzSoAR6SG" x1="12.498" x2="12.498" y1="20" y2="4" gradientUnits="userSpaceOnUse"><stop class="ar-rekq5g"/><stop offset="1" class="stmc-f_0k"/></linearGradient><linearGradient id="SVG7vgcscda" x1="12.001" x2="12.001" y1="20.001" y2="4.046" gradientUnits="userSpaceOnUse"><stop class="q71ze8c3q"/><stop offset="1" class="qk9r03bjd"/></linearGradient><linearGradient id="SVG3l4rJeDk" x1="11.501" x2="11.501" y1="20" y2="4" gradientUnits="userSpaceOnUse"><stop class="ar-rekq5g"/><stop offset="1" class="stmc-f_0k"/></linearGradient><linearGradient id="SVGcoiZpduu" x1="5.785" x2="9.672" y1="19.001" y2="2.531" gradientUnits="userSpaceOnUse"><stop class="go__dabhm"/><stop offset="1" class="qr1dcfdvd"/></linearGradient><linearGradient id="SVGs2rFocJL" x1="8.724" x2="8.724" y1="20.001" y2="5.333" gradientUnits="userSpaceOnUse"><stop class="e75cwpepz"/><stop offset=".57" class="dhqver70j"/><stop offset="1" class="k-ro4xbwj"/></linearGradient><linearGradient id="SVGwiZz7b3m" x1="18.216" x2="14.313" y1="19.001" y2="2.523" gradientUnits="userSpaceOnUse"><stop class="go__dabhm"/><stop offset="1" class="qr1dcfdvd"/></linearGradient><linearGradient id="SVGwJZ2cbFR" x1="15.581" x2="15.581" y1="20" y2="4.696" gradientUnits="userSpaceOnUse"><stop class="e75cwpepz"/><stop offset=".57" class="dhqver70j"/><stop offset="1" class="k-ro4xbwj"/></linearGradient><linearGradient id="SVGYbT49cbV" x1="6.913" x2="8.991" y1="5.999" y2="19.611" gradientUnits="userSpaceOnUse"><stop class="s42fl-rge"/><stop offset="1" class="gubra6bru"/></linearGradient><linearGradient id="SVG9ZTNGIfh" x1="4.783" x2="10.729" y1="3.999" y2="20.194" gradientUnits="userSpaceOnUse"><stop class="vzdaiw3gp"/><stop offset="1" class="cwv022bmm"/></linearGradient><linearGradient id="SVGkty2Mb6v" x1="21.272" x2="19.53" y1="6.001" y2="19.709" gradientUnits="userSpaceOnUse"><stop class="s42fl-rge"/><stop offset="1" class="gubra6bru"/></linearGradient><linearGradient id="SVGtcguybCl" x1="24.647" x2="18.724" y1="4.001" y2="20.185" gradientUnits="userSpaceOnUse"><stop class="vzdaiw3gp"/><stop offset="1" class="cwv022bmm"/></linearGradient><linearGradient id="SVGu8s39cUC" x1="12.069" x2="12.676" y1="5.265" y2="19.998" gradientUnits="userSpaceOnUse"><stop class="zlnb847tl"/><stop offset="1" class="nuge_62tr"/></linearGradient><linearGradient id="SVGKWxC5ZOK" x1="11.666" x2="14.986" y1="6.001" y2="18.098" gradientUnits="userSpaceOnUse"><stop class="soz6-2b8n"/><stop offset="1" class="y42wg_70z"/></linearGradient><linearGradient id="SVGNVRHAeBY" x1="17.239" x2="7.335" y1="4" y2="21.509" gradientUnits="userSpaceOnUse"><stop class="btkh0pb0v"/><stop offset="1" class="ev6eq1min"/></linearGradient><linearGradient id="SVGb72IabgM" x1="13.467" x2="5.784" y1="9.333" y2="22.011" gradientUnits="userSpaceOnUse"><stop class="btkh0pb0v"/><stop offset="1" class="ev6eq1min"/></linearGradient><linearGradient id="SVGnvcKPbnB" x1="13.468" x2="5.784" y1="9.333" y2="22.011" gradientUnits="userSpaceOnUse"><stop class="btkh0pb0v"/><stop offset="1" class="ev6eq1min"/></linearGradient><linearGradient id="SVGLxsGhdMw" x1="15.667" x2="7.422" y1="9.333" y2="20.671" gradientUnits="userSpaceOnUse"><stop class="btkh0pb0v"/><stop offset="1" class="ev6eq1min"/></linearGradient><linearGradient id="SVGSyB8Vcbh" x1="12" x2="12" y1="4" y2="20.001" gradientUnits="userSpaceOnUse"><stop class="oxiqkcc3j"/><stop offset="1" class="pawc61baq"/></linearGradient><linearGradient id="SVGwxe1vbrH" x1="15.461" x2="15.461" y1="1.333" y2="14.667" gradientUnits="userSpaceOnUse"><stop class="lo6mxgbwa"/><stop offset="1" class="zsyheeapr"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dzoo-background" /></template>
<style>
.a9hshccwb {
  d: path("M13.182 15.556c.755.889 1.102 2.889 1.182 3.778c1.422-1.556.316-3.41-.236-4.222z");
}

.aq0ncb0gp {
  d: path("M8.444 13.778H8l2.222-2.667h.445z");
}

.ar-rekq5g {
  stop-color: var(--svg-color--0d827c, #0d827c);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.btkh0pb0v {
  stop-color: var(--svg-color--394f51, #394f51);
}

.cfuxozbaa {
  stop-color: var(--svg-color--8ecb63, #8ecb63);
}

.cwv022bmm {
  stop-color: var(--svg-color--42a77f, #42a77f);
}

.d1_xg552h {
  d: path("M16.494 16.89c-.186 1.245-1.498 2.147-2.129 2.445c1.325-1.423.711-3.41.236-4.223c0 0 .293-.026.475 0c.916.125 1.423 1.778 1.423 1.778z");
}

.dhqver70j {
  stop-color: var(--svg-color--4ab67c, #4ab67c);
}

.e75cwpepz {
  stop-color: var(--svg-color--6eb374, #6eb374);
}

.egh6bb5yn {
  d: path("M16.97 11.113c1.702-1.423.711-3.854 0-4.89c.378 2.134-.316 3.258-.711 3.556z");
}

.ej7fmlsid {
  d: path("M7.778 13.778v-.444l1.778-2.223h.445z");
}

.ev6eq1min {
  stop-color: var(--svg-color--374d50, #374d50);
  stop-opacity: 0.08;
}

.f3hygbbwi {
  d: path("M15.076 9.335c.756-.534 1.578-2.298 1.894-3.111c.564 1.6-.551 3.035-1.183 3.555z");
}

.fe2_4lvtc {
  d: path("M7.978 7.556c.19-1.245 1.497-2.147 2.133-2.445c-1.329 1.422-.711 3.409-.24 4.222c0 0-.289.027-.476 0c-.91-.124-1.417-1.777-1.417-1.777");
}

.ffo6nhbfx {
  d: path("M7.556 11.09c0-.868.814-2.579 2.654-2.579l-.511-.51c.768.088 1.79.444 2.524.888c.6-.444 1.44-.684 2.667-.889l-.445.516a2.82 2.82 0 0 1 2.445 2.573c0 .6-.133 1.956-1.569 2.574c.342.084.902.417.902 1.448c0 1.29-2 2.667-4 2.667c-1.533 0-3.556-.866-3.556-2.666c0-1.232.4-1.48.73-1.472c-.854-.15-2.05-.862-1.84-2.55");
}

.ft5dv1b6b {
  fill: none;
}

.g10mofb-v {
  stop-color: var(--svg-color--76be62, #76be62);
}

.gg6-d6d7t {
  stop-color: var(--svg-color--0e9284, #0e9284);
}

.go__dabhm {
  stop-color: var(--svg-color--199584, #199584);
}

.go_9bvvni {
  d: path("M14.001 13.111v-.444l1.111-1.556h.445z");
}

.gpc5j-rjo {
  d: path("M14.667 13.778h-.444l2.222-2.667h.445z");
}

.gubra6bru {
  stop-color: var(--svg-color--1d9b85, #1d9b85);
}

.i66b3bbhu {
  d: path("M11.289 8.889c-.756-.889-1.102-2.89-1.182-3.778c-1.423 1.556-.311 3.409.235 4.222z");
}

.ilfv1abuj {
  d: path("M5.613 11.557c.546 0 .946.297.946.444c-.395 0-1.182.178-1.182.889s1.102 1.48 1.654 1.778c-.943 0-2.365-.667-2.365-1.778c0-.836.471-1.334.947-1.334");
}

.irc-qprcg {
  d: path("M15.076 15.112c.756.533 1.578 2.298 1.894 3.111c.569-1.6-.551-3.035-1.183-3.555z");
}

.j-m0hhw-y {
  fill: var(--svg-color--bba1a2, #bba1a2);
  d: path("M18.623 12.89c0-.89-.787-.965-1.182-.89v1.112c.569 0 .71.146.71.222h-.235c-.19.356-.71.591-.946.667v.667c.55-.223 1.653-.89 1.653-1.778");
}

.jkvu0qbcl {
  d: path("M18.388 11.557c-.547 0-.947.297-.947.444c.395 0 1.182.178 1.182.889s-1.102 1.48-1.653 1.778c.942 0 2.364-.667 2.364-1.778c0-.836-.47-1.334-.946-1.334");
}

.k-ro4xbwj {
  stop-color: var(--svg-color--74b960, #74b960);
}

.lepglpb0a {
  d: path("M16.494 7.556c-.186-1.245-1.498-2.147-2.129-2.445c1.325 1.422.711 3.409.236 4.222c0 0 .293.027.475 0c.916-.124 1.423-1.777 1.423-1.777z");
}

.lo6mxgbwa {
  stop-color: var(--svg-color--5c1b15, #5c1b15);
}

.nuge_62tr {
  stop-color: var(--svg-color--af888b, #af888b);
}

.o5-242bqj {
  d: path("M6.088 8.444c-1.706 2.845.472 5.333 1.89 5.333l-.472-1.333c-1.138-.356-1.422-2.813-1.422-4z");
}

.oxiqkcc3j {
  stop-color: var(--svg-color--021b1f, #021b1f);
}

.oy6ksjhcs {
  d: path("M16.445 13.111c1.702 1.422 1.23 4.076.524 5.112c.378-2.134-1.022-4.147-1.413-4.445z");
}

.p3nuizb2g {
  d: path("M10.818 18.889c-.485-.454-.867-1.778-.947-2.445h1.894l.47 3.556c-.47-.667-.946-.667-1.417-1.111");
}

.pawc61baq {
  stop-color: var(--svg-color--0b1110, #0b1110);
}

.pd6waacyh {
  d: path("M12.254 15.112c-.311 0-.854.52-.982.666c.19.445.568.667.95.667c.383 0 .76-.222.952-.667c-.133-.146-.605-.667-.92-.667");
}

.pvxcglwsz {
  stop-color: var(--svg-color--acda5f, #acda5f);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q6b5xpbvm {
  fill: var(--svg-color--bba1a2, #bba1a2);
  d: path("M5.377 12.89c0-.89.787-.965 1.182-.89v1.112c-.569 0-.71.146-.71.222h.235c.19.356.71.591.946.667v.667c-.55-.223-1.653-.89-1.653-1.778");
}

.q71ze8c3q {
  stop-color: var(--svg-color--70ab6b, #70ab6b);
}

.qb3t1zgzw {
  stop-color: var(--svg-color--12837f, #12837f);
}

.qk9r03bjd {
  stop-color: var(--svg-color--2ea881, #2ea881);
}

.qr1dcfdvd {
  stop-color: var(--svg-color--6ab562, #6ab562);
}

.r31xx1giy {
  d: path("M9.391 15.112c-.756.533-1.578 2.298-1.889 3.111c-.569-1.6.551-3.035 1.182-3.555l.711.444z");
}

.rqbmoexfp {
  d: path("M14.365 6.445c-.377-.356-1.578-1.778-2.129-2.445v1.778l.711 4c.632-.964 1.796-2.978 1.423-3.333z");
}

.rz2_3jbyt {
  d: path("M8.222 10.668c-.782 0-.889.444-.889.666c0 1.245 0 2.89.733 2.89h1.467c1.222 0 1.711-2 2.69-2c1.128 0 1.146 1.764 2.443 2h1.467c.978 0 .978-2.223.978-2.89c0-.533-.564-.666-.889-.666h-2c-.444 0-1.413.889-2 .889s-1.333-.89-1.955-.89z");
}

.s0z7zengr {
  d: path("M14.001 13.778v-.444l1.778-2.223h.444z");
}

.s42fl-rge {
  stop-color: var(--svg-color--84ba5d, #84ba5d);
}

.sjwpadc1w {
  stop-color: var(--svg-color--158885, #158885);
}

.soz6-2b8n {
  stop-color: var(--svg-color--041d21, #041d21);
}

.stmc-f_0k {
  stop-color: var(--svg-color--58b56e, #58b56e);
}

.ta5u1bi6v {
  d: path("M13.659 18.889c.48-.454.866-1.778.946-2.445h-1.893L12.236 20c.476-.667.947-.667 1.423-1.111");
}

.u8n4wqaek {
  fill: var(--svg-color--020207, #020207);
  d: path("M11.57 14.223h.475s-.315-.444-.475-.444c-.156 0-.236.097-.236.222c0 .124.08.222.236.222m1.346 0h-.47s.315-.444.47-.444c.16 0 .24.097.24.222c0 .124-.08.222-.24.222");
}

.uen05e_tz {
  stop-color: var(--svg-color--4dba76, #4dba76);
}

.uogvyab2r {
  d: path("M7.977 10.222a6 6 0 0 1-1.893-1.778a3.42 3.42 0 0 0 1.422 3.111z");
}

.uu-s888lj {
  d: path("M18.151 8.224c1.703 2.844-.235 4.742-1.422 5.333v-1.333c1.138-.356 1.422-2.814 1.422-4");
}

.v_0-5_bkq {
  d: path("M13.11 14.668h-1.777c-.444 0-.444.253-.444.506c0 .254.444 1.271 1.333 1.271s1.333-.76 1.333-1.27c0-.405-.297-.507-.444-.507");
}

.vzdaiw3gp {
  stop-color: var(--svg-color--108a82, #108a82);
}

.w_6majp2e {
  d: path("M10.107 6.445c.378-.356 1.578-1.778 2.133-2.445v1.778l-.711 4c-.631-.964-1.8-2.978-1.422-3.333");
}

.y42wg_70z {
  stop-color: var(--svg-color--050306, #050306);
}

.ycq7dq50l {
  d: path("M7.778 13.111v-.444L8.89 11.11h.445z");
}

.yibznbczh {
  d: path("M13.182 8.889c.755-.889 1.102-2.89 1.182-3.778c1.422 1.556.316 3.409-.236 4.222z");
}

.ynhv96bge {
  d: path("M16.259 10.002a6 6 0 0 0 1.893-1.778a3.42 3.42 0 0 1-1.422 3.11z");
}

.yovr3_bco {
  d: path("M11.284 15.556c-.756.889-1.103 2.889-1.183 3.778c-1.422-1.556-.315-3.41.236-4.222z");
}

.yq73_cb0r {
  d: path("M7.507 11.113c-1.707-1.423-.711-3.854 0-4.89c-.378 2.134.311 3.258.711 3.556z");
}

.ytqgjacqn {
  d: path("M9.395 9.335C8.639 8.8 7.82 7.037 7.505 6.224c-.568 1.6.552 3.035 1.183 3.555l.711-.444z");
}

.yxac9g_kn {
  d: path("M7.778 12.89c-1.702 1.422-.987 4.297-.28 5.333c-.378-2.134 1.218-4.147 1.613-4.445z");
}

.zd_oy2bcr {
  stop-color: var(--svg-color--7bcc73, #7bcc73);
}

.zlnb847tl {
  stop-color: var(--svg-color--efe6e7, #efe6e7);
}

.zsyheeapr {
  stop-color: var(--svg-color--2e0002, #2e0002);
}

.zuowjgbuw {
  d: path("M7.974 16.89c.187 1.245 1.498 2.147 2.13 2.445c-1.325-1.423-.712-3.41-.236-4.223c0 0-.294-.026-.476 0c-.916.125-1.422 1.778-1.422 1.778z");
}

</style>
