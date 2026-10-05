<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG0811ecPx" x1="-7362" x2="-7338" y1="2007" y2="1980" gradientTransform="matrix(-.023 -.116 -.116 .023 78.5 -891)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cn4ynabaa"/><stop offset=".312" class="k2vs_lbar"/><stop offset=".838" class="ebbg0xbtb"/></linearGradient><linearGradient id="SVGZMWnmevn" x1="-7533" x2="-7368" y1="2011" y2="2011" gradientTransform="matrix(-.023 -.116 -.116 .023 78.5 -891)" gradientUnits="userSpaceOnUse"><stop offset=".323" class="ia_e7ab1l"/><stop offset=".63" class="by3olxbhe"/><stop offset=".751" class="ke3vstf6j"/><stop offset="1" class="ebbg0xbtb"/></linearGradient><linearGradient id="SVGXwU8QFig" x1="-7513" x2="-7415" y1="1994" y2="1994" gradientTransform="matrix(-.023 -.116 -.116 .023 78.5 -891)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wmn00hb3g"/><stop offset=".095" class="s2dcv5lrc"/><stop offset=".788" class="xebr5hbiq"/><stop offset=".949" class="xy6mk1bfm"/></linearGradient><linearGradient id="SVGUhoT8jsY" x1="-7524" x2="-7358" y1="2012" y2="2012" href="#SVGZMWnmevn"/><linearGradient id="SVGsMVkMdmw" x1="-7512" x2="-7425" y1="2010" y2="2010" href="#SVGXwU8QFig"/><linearGradient id="SVGhouxS4tv" x1="-7524" x2="-7358" y1="1995" y2="1995" href="#SVGZMWnmevn"/><linearGradient id="SVG9HgvNJVR" x1="-7534" x2="-7369" y1="2000" y2="2000" href="#SVGZMWnmevn"/><linearGradient id="SVGfHxa7ckS" x1="-7524" x2="-7358" y1="1990" y2="1990" href="#SVGZMWnmevn"/><linearGradient id="SVGJshU3bzl" x1="-8334" x2="-8310" y1="1965" y2="1938" gradientTransform="matrix(.074 -.112 -.112 -.074 863 -777)" href="#SVG0811ecPx"/><linearGradient id="SVGd6ckvdwm" x1="-8505" x2="-8340" y1="1968" y2="1968" gradientTransform="matrix(.074 -.112 -.112 -.074 863 -777)" href="#SVGZMWnmevn"/><linearGradient id="SVGaNeSXdkq" x1="-8485" x2="-8387" y1="1952" y2="1952" gradientTransform="matrix(.074 -.112 -.112 -.074 863 -777)" href="#SVGXwU8QFig"/><linearGradient id="SVGioIKCbxF" x1="-8496" x2="-8331" y1="1970" y2="1970" gradientTransform="matrix(.074 -.112 -.112 -.074 863 -777)" href="#SVGZMWnmevn"/><linearGradient id="SVGZuxhPdMx" x1="-8484" x2="-8397" y1="1967" y2="1967" gradientTransform="matrix(.074 -.112 -.112 -.074 863 -777)" href="#SVGXwU8QFig"/><linearGradient id="SVG7OKv0cuX" x1="-8496" x2="-8331" y1="1953" y2="1953" gradientTransform="matrix(.074 -.112 -.112 -.074 863 -777)" href="#SVGZMWnmevn"/><linearGradient id="SVGRmoWdenw" x1="-8506" x2="-8341" y1="1953" y2="1953" gradientTransform="matrix(.074 -.112 -.112 -.074 863 -777)" href="#SVGZMWnmevn"/><linearGradient id="SVGWbO23bDu" x1="-8496" x2="-8331" y1="1948" y2="1948" gradientTransform="matrix(.074 -.112 -.112 -.074 863 -777)" href="#SVGZMWnmevn"/><path id="SVGWjdjDdtV" class="n1qco0bke"/><path id="SVGgsRwDbnT" class="a-mlbrlwf"/><path id="SVGmftdikzG" class="e8lq3bgyk"/><path id="SVGDNGgneYO" class="siwv9xk_a"/><path id="SVGRk4VbcGc" class="bo5_rbc1p"/><path id="SVGIxrhuwan" class="f62pxpbqi"/><path id="SVGpS4qweJl" class="d71l78bci"/><path id="SVGgjX49duo" class="lwhz-2bra"/></defs><path class="vbyec5bgc"/><path class="uw8ttnczg"/><path fill="url(#SVG0811ecPx)" class="wz149f40t"/><path class="zmnmh3bzl"/><use href="#SVGWjdjDdtV"/><use href="#SVGWjdjDdtV" class="k0jpwu2hx"/><use href="#SVGgsRwDbnT"/><use href="#SVGgsRwDbnT" class="k0jpwu2hx"/><path fill="url(#SVGZMWnmevn)" class="o80wgg0bh"/><path fill="url(#SVGXwU8QFig)" class="nmsx-1_ux"/><path fill="url(#SVGUhoT8jsY)" class="j_i1hdbzx"/><path fill="url(#SVGsMVkMdmw)" class="i-0qknfyi"/><path fill="url(#SVGhouxS4tv)" class="y_oyzkb_o"/><path fill="url(#SVG9HgvNJVR)" class="c9_n0lgrw"/><use href="#SVGmftdikzG"/><use href="#SVGmftdikzG" class="k0jpwu2hx"/><path fill="url(#SVGfHxa7ckS)" class="sjj-afbiz"/><use href="#SVGDNGgneYO"/><use href="#SVGDNGgneYO" class="k0jpwu2hx"/><path fill="url(#SVGfHxa7ckS)" class="v_qmg0bqz"/><path fill="url(#SVGJshU3bzl)" class="kv9b_wbsx"/><path class="kwme5enth"/><use href="#SVGRk4VbcGc"/><use href="#SVGRk4VbcGc" class="k0jpwu2hx"/><use href="#SVGIxrhuwan"/><use href="#SVGIxrhuwan" class="k0jpwu2hx"/><path fill="url(#SVGd6ckvdwm)" class="fwhyqccvi"/><path fill="url(#SVGaNeSXdkq)" class="yir-ijndq"/><path fill="url(#SVGioIKCbxF)" class="x6c13sbcq"/><path fill="url(#SVGZuxhPdMx)" class="ulixm2zjd"/><path fill="url(#SVG7OKv0cuX)" class="j2dy-3b3r"/><path fill="url(#SVGRmoWdenw)" class="uqdgcsiwg"/><use href="#SVGpS4qweJl"/><use href="#SVGpS4qweJl" class="k0jpwu2hx"/><path fill="url(#SVGWbO23bDu)" class="hbt9ai-vz"/><use href="#SVGgjX49duo"/><use href="#SVGgjX49duo" class="k0jpwu2hx"/><path fill="url(#SVGWbO23bDu)" class="du182cbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-maven-opened" /></template>
<style>
.a-mlbrlwf {
  fill: var(--svg-color--be202e, #be202e);
  d: path("M19 17.8c.009-.006.015-.016.024-.022l.1-.1l-.121.125z");
}

.bo5_rbc1p {
  fill: var(--svg-color--be202e, #be202e);
  d: path("M26.1 20.2h-.25h.129a1 1 0 0 0 .121 0");
}

.by3olxbhe {
  stop-color: var(--svg-color--c92037, #c92037);
}

.c9_n0lgrw {
  d: path("M16.476 12.884q.026.45.077 1.008a.4.4 0 0 0 .007.058a37 37 0 0 0 .272 2.11c.049.325.109.665.171 1.025l1.365-1.25a2.24 2.24 0 0 0 .343-1.235c0-.107-.008-.22-.016-.336a11 11 0 0 0-.123-1.078a9 9 0 0 0-.2-.965a5 5 0 0 0-.156-.49a6 6 0 0 0-.151-.341a22 22 0 0 1-1.589 1.494");
}

.cn4ynabaa {
  stop-color: var(--svg-color--f69923, #f69923);
}

.d71l78bci {
  fill: var(--svg-color--be202e, #be202e);
  d: path("M26 20.2h-.129a1 1 0 0 1 .129 0");
}

.du182cbsh {
  d: path("M26.4 19.2h.041z");
}

.e8lq3bgyk {
  fill: var(--svg-color--be202e, #be202e);
  d: path("m19.271 18.7l-.08.081a1 1 0 0 1 .08-.081");
}

.ebbg0xbtb {
  stop-color: var(--svg-color--e97826, #e97826);
}

.f62pxpbqi {
  fill: var(--svg-color--be202e, #be202e);
  d: path("M26.4 19.2h.037q.082.001.159-.006h-.2z");
}

.fwhyqccvi {
  d: path("M25.963 16.069q.365-.489.726-.954a23 23 0 0 1 .805-.98q.376-.438.751-.838l-.451-1.264l-.168.154c-.212.2-.434.41-.663.639q-.386.386-.8.818a45 45 0 0 0-.768.839q-.33.374-.661.768l-.025.03l.577 1.719z");
}

.hbt9ai-vz {
  d: path("M26 20.2h-.129a1 1 0 0 1 .129 0");
}

.i-0qknfyi {
  d: path("M17.11 23.656a11 11 0 0 0 .661 1.22c.009.012.016.029.025.04a2.9 2.9 0 0 0-1.1-.085a4 4 0 0 1 1.765 1.028a1.85 1.85 0 0 1-.834.418a1.85 1.85 0 0 0 .915-.081a2.25 2.25 0 0 0-.557 1.085a2.3 2.3 0 0 1 .9-.957c.431 1.429.95 2.979 1.526 4.605a.43.43 0 0 0 .067-.406a99 99 0 0 1-1.571-4.851c-.023-.074-.042-.15-.067-.226l-.019-.063q-.12-.413-.244-.849l-.055-.2l-1.436-.728a.3.3 0 0 0 .024.05");
}

.ia_e7ab1l {
  stop-color: var(--svg-color--9e2064, #9e2064);
}

.j_i1hdbzx {
  d: path("m18.239 23.3l-.274-1.031c-.093-.348-.171-.669-.254-1.009s-.163-.683-.243-1.026s-.158-.7-.231-1.053s-.143-.7-.212-1.045a14 14 0 0 1-.07-.378q-.06-.322-.114-.647q.002-.018-.008-.035l-1.421-.725l.005.068c.029.322.057.649.095.977a36 36 0 0 0 .263 1.859l.031.171a20 20 0 0 0 .663 2.63q.082.24.169.476q.204.553.449 1.078l1.436.728c-.077-.264-.147-.533-.225-.8a4 4 0 0 0-.059-.238");
}

.j2dy-3b3r {
  d: path("M25.4 17.158c-.032.045-.059.087-.09.132q-.138.203-.277.413c-.139.21-.2.307-.31.466q-.08.118-.16.243a67 67 0 0 0-1.116 1.774c-.2.332-.412.68-.622 1.035c-.2.341-.4.689-.612 1.054q-.276.484-.562 1c-.011.015-.018.035-.028.05q-.282.508-.573 1.047l-.012.023l.666.023c-.012-.006-.024-.008-.04-.014a4.7 4.7 0 0 0 2.706-1.042a6.3 6.3 0 0 0 1.02-1.062a10 10 0 0 0 .717-1.063c.2-.344.409-.722.611-1.133a2.5 2.5 0 0 1-.646.121l-.126.007h-.129a2.87 2.87 0 0 0 1.745-1.266a2.7 2.7 0 0 1-.936.258c-.051.005-.1.005-.159.006h-.041a3 3 0 0 0 .709-.27a1 1 0 0 0 .128-.077q.096-.062.185-.131l.113-.091a2 2 0 0 0 .245-.251c.025-.03.05-.055.071-.085q.049-.066.089-.128a7 7 0 0 0 .447-.724c.012-.027.028-.05.04-.077l.1-.2a2 2 0 0 0 .08-.209a.5.5 0 0 1-.094.044a3.2 3.2 0 0 1-.949.177l.612.023l-.612-.023a.02.02 0 0 0-.013 0a1 1 0 0 0-.1 0s.013 0 .017-.006L25.4 17.13c.006.017 0 .024 0 .028");
}

.k0jpwu2hx {
  opacity: var(--svg-opacity--0-35, 0.35);
}

.k2vs_lbar {
  stop-color: var(--svg-color--f79a23, #f79a23);
}

.ke3vstf6j {
  stop-color: var(--svg-color--cd2335, #cd2335);
}

.kv9b_wbsx {
  d: path("M29.6 10.7a8 8 0 0 0-1.82 1.37l.45 1.27a15 15 0 0 1 1.58-1.47l.061-.049c-.019.018-.042.031-.061.049a13.5 13.5 0 0 0-1.5 1.51a24 24 0 0 0 2.47.054a2.58 2.58 0 0 0 .053-1.98s-.459-1.06-1.22-.747z");
}

.kwme5enth {
  fill: none;
  d: path("M27.578 17.22a.02.02 0 0 0 .013 0H27.5s-.013 0-.017.006ZM26.6 19.2c-.051.005-.1.005-.159.006q.082 0 .159-.006m-4.982 4.122c.011-.015.018-.035.028-.05l.562-1q.311-.541.612-1.054q.316-.533.622-1.035q.32-.526.626-1.01q.25-.393.49-.764q.08-.124.16-.243l.31-.466l.277-.413q.049-.069.09-.132l.016-.023h-.079L25.289 17l-.022.034c-.142.2-.284.4-.422.612q-.119.177-.244.359q-.335.498-.659 1.009c-.324.511-.438.688-.65 1.031s-.416.679-.619 1.019s-.4.677-.6 1.014a61 61 0 0 0-.73 1.282c-.158.28-.31.553-.458.827l.07.206h.087l.012-.023c.185-.359.377-.709.564-1.048");
}

.lwhz-2bra {
  fill: var(--svg-color--be202e, #be202e);
  d: path("M26.4 19.2h.041z");
}

.n1qco0bke {
  fill: var(--svg-color--be202e, #be202e);
  d: path("M19.343 18.621q-.074.082-.154.158c.027-.024.055-.054.08-.081a1 1 0 0 0 .074-.077");
}

.nmsx-1_ux {
  d: path("M18.8 24.521q.117.402.246.821v.011q.016.06.037.117c.057.188.112.355.23.738a1.45 1.45 0 0 1 .821.2a1.17 1.17 0 0 0-.78-.424a2.51 2.51 0 0 0 1.37-2.233a3 3 0 0 0-.035-.245a1.01 1.01 0 0 1-.575.864a2.82 2.82 0 0 0 .458-1.78a6 6 0 0 0-.056-.464a2.29 2.29 0 0 1-1.329 1.846l-.433.4q.02.072.046.149");
}

.o80wgg0bh {
  d: path("M16.685 16.069q-.074-.534-.135-1.051a29 29 0 0 1-.1-1.056v-.06q-.035-.509-.048-.993l-1.068-.515c0 .065-.007.132-.01.2q-.017.385-.021.814q-.002.482.006 1.01c.008.324.021.661.038 1q.025.44.061.894v.034l1.429.724c-.049-.332-.102-.67-.152-1.001");
}

.s2dcv5lrc {
  stop-color: var(--svg-color--662e8d, #662e8d);
}

.siwv9xk_a {
  fill: var(--svg-color--be202e, #be202e);
  d: path("M18.948 17.769c.009-.006.015-.016.027-.024c-.009.006-.015.016-.027.024");
}

.sjj-afbiz {
  d: path("m19.271 18.7l-.08.081a1 1 0 0 1 .08-.081");
}

.ulixm2zjd {
  d: path("M20.278 22.514a13 13 0 0 0-.437 1.507c0 .016-.009.036-.012.052a3.3 3.3 0 0 0-.814-.939a4.56 4.56 0 0 1 .6 2.23a2.1 2.1 0 0 1-1-.326a2.1 2.1 0 0 0 .8.662a2.55 2.55 0 0 0-1.311.431a2.6 2.6 0 0 1 1.488-.052c-.789 1.493-1.6 3.153-2.431 4.919a.49.49 0 0 0 .377-.273c.147-.319 1.133-2.42 2.59-5.154c.04-.077.085-.154.126-.235l.035-.066q.231-.428.478-.878c.039-.069.074-.135.113-.2l-.58-1.732a.3.3 0 0 0-.022.054");
}

.uqdgcsiwg {
  d: path("M28.326 13.339q-.337.382-.739.873a.4.4 0 0 0-.041.052q-.349.428-.742.947c-.227.3-.465.618-.716.968c-.219.3-.44.621-.677.961l2.092.078a2.53 2.53 0 0 0 1.258-.722q.125-.133.254-.283a12 12 0 0 0 .757-.966a11 11 0 0 0 .6-.938a6 6 0 0 0 .263-.519q.086-.204.149-.394a24 24 0 0 1-2.458-.057");
}

.uw8ttnczg {
  fill: var(--svg-color--7f7add, #7f7add);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.v_qmg0bqz {
  d: path("M18.948 17.769c.009-.006.015-.016.027-.024c-.009.006-.015.016-.027.024");
}

.vbyec5bgc {
  fill: var(--svg-color--7f7add, #7f7add);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.wmn00hb3g {
  stop-color: var(--svg-color--282662, #282662);
}

.wz149f40t {
  d: path("M15.6 10.4a7.2 7.2 0 0 0-.3 1.99l1.07.518a13.4 13.4 0 0 1 .079-1.91c0-.044.008-.069.008-.069c0 .023-.007.046-.008.069a12 12 0 0 0 0 1.88a21 21 0 0 0 1.58-1.5a2.28 2.28 0 0 0-1.2-1.28s-.948-.375-1.23.299z");
}

.x6c13sbcq {
  d: path("M21.468 23.126q.3-.518.6-1.047q.292-.505.6-1.014c.308-.509.412-.68.619-1.019s.43-.689.65-1.031s.44-.675.659-1.009q.119-.18.244-.359c.138-.2.28-.408.422-.612c.006-.012.016-.023.022-.034l-.568-1.713l-.05.059c-.233.282-.47.567-.7.862s-.467.6-.7.912q-.287.393-.57.794c-.037.053-.074.11-.111.162c-.228.337-.443.667-.635.984c-.219.359-.415.7-.592 1.032q-.173.323-.325.626c-.083.171-.163.346-.242.517c-.184.405-.348.814-.5 1.224l.578 1.727c.148-.273.3-.546.458-.827a3 3 0 0 0 .141-.234");
}

.xebr5hbiq {
  stop-color: var(--svg-color--9f2064, #9f2064);
}

.xy6mk1bfm {
  stop-color: var(--svg-color--cd2032, #cd2032);
}

.y_oyzkb_o {
  d: path("m17 17.107l.025.139c.028.142.052.286.082.431s.063.319.095.485l.05.252q.079.382.166.785q.107.495.233 1.024q.119.504.252 1.038q.127.506.269 1.043q.127.476.266.977c0 .016.011.033.013.049l.289 1.015l.007.022l.433-.4c-.011 0-.02.01-.034.016a4.16 4.16 0 0 0 1.056-2.336a5.6 5.6 0 0 0-.013-1.3a9 9 0 0 0-.209-1.114a15 15 0 0 0-.319-1.092a2.2 2.2 0 0 1-.331.477l-.075.082l-.08.081a2.53 2.53 0 0 0 .312-1.88a2.4 2.4 0 0 1-.429.743a1 1 0 0 1-.1.1c-.009.006-.015.016-.027.024a2.6 2.6 0 0 0 .278-.61a1 1 0 0 0 .033-.128q.021-.097.036-.2c0-.044.01-.084.014-.128a2 2 0 0 0 0-.31q.002-.05-.008-.1q-.01-.072-.023-.136a6 6 0 0 0-.169-.733c-.009-.025-.013-.049-.023-.074q-.033-.104-.063-.184a2 2 0 0 0-.079-.181a.4.4 0 0 1-.031.086a2.8 2.8 0 0 1-.487.7l.4-.365l-.4.365a.01.01 0 0 0-.007.009l-.059.061c0-.005.007-.009.007-.014l-1.365 1.25c.015.018.02.024.015.031");
}

.yir-ijndq {
  d: path("M20.948 24.55q-.223.417-.454.856l-.006.012q-.035.061-.064.124c-.1.2-.192.375-.4.777a1.64 1.64 0 0 1 .5.81a1.33 1.33 0 0 0-.291-.962a2.84 2.84 0 0 0 2.877-.709q.085-.107.166-.225a1.14 1.14 0 0 1-1.149.239a3.2 3.2 0 0 0 1.786-1.072a7 7 0 0 0 .323-.418a2.59 2.59 0 0 1-2.537.43l-.666-.023Z");
}

.zmnmh3bzl {
  fill: none;
  d: path("M18.416 15.791a.01.01 0 0 0 .007-.009l-.06.053c0 .005-.007.009-.007.014Zm.04 7.541c0-.016-.011-.033-.013-.049q-.137-.499-.266-.977a81 81 0 0 1-.521-2.081a49 49 0 0 1-.233-1.024a72 72 0 0 1-.166-.785l-.05-.252l-.095-.485l-.082-.431c-.008-.048-.016-.1-.025-.139v-.024l-.051.047l-.106-.053q-.002.017.008.035q.052.32.114.647q.036.184.07.378q.098.521.212 1.045c.114.524.152.7.231 1.053s.16.685.243 1.026s.167.676.254 1.009a48 48 0 0 0 .338 1.259q.112.411.225.8l.172.086l.057-.051l-.007-.022c-.12-.344-.216-.683-.309-1.012");
}

</style>
