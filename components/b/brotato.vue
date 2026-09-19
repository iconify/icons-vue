<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ma9y2xsas"/><path class="y1guuobyi"/><path class="sjbcze09i"/><path class="btg9t0bpz"/><path class="n_6c99bpk"/><path class="u_zk3bb6b"/><path class="n7ddm3bxa"/><path class="zd1hs_bds"/><circle class="bqsd77b8c"/><circle class="dt-mw6b4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brotato" /></template>
<style>
.bqsd77b8c {
  cx: 18.106px;
  cy: 23.168px;
  r: 1.072px;
}

.btg9t0bpz {
  d: path("M15.957 30.899c-.358.18-8.625 11.377 3.826 2.109m9.473-1.211s1.898.543 2.227 3.945c.22-.023 2.885 1.702 2.804-1.218c0 0 .627-3.072-2.88-5.12m-16.708-9.391c-.186-.246-2.763-7.149-2.763-7.149l-1.998 1.457l4.717 9.83");
}

.dt-mw6b4d {
  cx: 28.612px;
  cy: 22.926px;
  r: 1.072px;
}

.ma9y2xsas {
  d: path("M19.293 14.635c.626 0 5.285-4.695 9.703.5z");
}

.n_6c99bpk {
  d: path("m9.938 14.32l-2.151-.064l-.74.713l.503.827l2.904-.256l-1.792.913l4.819 9.8l1.174-2.102");
}

.n7ddm3bxa {
  d: path("M8.087 24.048s2.988 1.276 1.656 4.272M7.787 14.256s.872-2.93 4.149-1.391m20.263 7.788l5.23-8.836l2.295 2.687l-6.997 9.112");
}

.sjbcze09i {
  d: path("M28.996 15.135c4.935 2.259 3.203 5.518 3.203 5.518s2.8 11.435-7.61 12.552c-1.463-.12-11.851.953-9.687-11.614");
}

.u_zk3bb6b {
  d: path("m7.55 15.795l-1.486.803l.779.94s2.451-.558 2.293 2.319L6.699 21.7l-2.113.176L3 19.427s1.05-1.939 2.334-.073l1.74-1.745m3.933 4.381s-3.434-.278-2.92 2.058c0 0-2.26 3.32 1.656 4.272c0 0 2.216-.261 3.163-3.47");
}

.y1guuobyi {
  d: path("M19.717 14.46s-2.654 1.131-3.023 2.663l2.964.584s-6.15-.416-4.755 3.884c0 0 6.256-5.199 17.296-.938");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zd1hs_bds {
  d: path("m38.482 12.125l.88-.8l1.558 1.8l-1.196 1.38m0 0l1.438 2.054l-7.304 9.921l-1.279-1.83m3.041.289l2.14 2.009s1.89.072 2.565-2.278c-.24-.315-2.605-2.842-2.605-2.842m1.188-1.512s1.307 2.688 5.219 1.513c.22-.636.873-3.422.873-3.422s-3.1 1.574-4.47-.008M21.1 24.273l-.02 1.533m-.042-.774s3.004-1.24 5.431.32m-3.78 1.462s1.177-.933 2.848.05m-8.513-5.477s2.342.167 3.155.95m6.533-.33s1.542-1.419 3.637-.756M17.583 25.28s-.318 1.146 1.347 3.847m-2.055-2.369l1.597-.94m-1.048 2.274l1.588-1.003");
}

</style>
