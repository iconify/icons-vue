<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGC7Cz9cJB" x1="0%" x2="99.999%" y1="50%" y2="50%"><stop offset="0%" class="ko8ye0bns"/><stop offset="5.52%" class="j94kcub1j"/><stop offset="27.81%" class="j3l42xolu"/><stop offset="54.91%" class="hv_mz614m"/><stop offset="100%" class="yivtvjbgh"/></linearGradient></defs><path class="xn-6sj_ay"/><path fill="url(#SVGC7Cz9cJB)" class="tjl4clbis"/><path class="mcizg8sme"/><path class="n8bdynb2m"/><path class="wjiyerbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-marketing-platform" /></template>
<style>
.hv_mz614m {
  stop-color: var(--svg-color--3f83f2, #3f83f2);
}

.j3l42xolu {
  stop-color: var(--svg-color--377deb, #377deb);
}

.j94kcub1j {
  stop-color: var(--svg-color--2973df, #2973df);
}

.ko8ye0bns {
  stop-color: var(--svg-color--246fdb, #246fdb);
}

.mcizg8sme {
  fill: var(--svg-color--fbbc04, #fbbc04);
  d: path("m218.4 218.5l-45.3-45.2c-25 25-65.5 25-90.5 0l-45.3 45.2c50.2 50 131.1 50 181.1 0");
}

.n8bdynb2m {
  fill: var(--svg-color--ea4335, #ea4335);
  d: path("M173.2 173.3c12.5-12.5 32.7-12.5 45.2 0s12.5 32.8 0 45.3s-32.7 12.5-45.2 0s-12.5-32.8 0-45.3");
}

.tjl4clbis {
  d: path("M218.4 37.5c-50-50-130.9-50-180.9 0s-50 131 0 181l45.3-45.2c-25-25-25-65.5 0-90.5s65.5-25 90.5 0c12.5 12.5 32.8 12.5 45.3 0c12.3-12.5 12.3-32.8-.2-45.3");
}

.wjiyerbys {
  fill: var(--svg-color--34a853, #34a853);
  d: path("M37.5 173.3c12.5-12.5 32.7-12.5 45.2 0s12.5 32.8 0 45.3s-32.7 12.5-45.2 0s-12.5-32.8 0-45.3");
}

.xn-6sj_ay {
  fill: var(--svg-color--ea4335, #ea4335);
  d: path("M173.2 82.8c25 25 25 65.5 0 90.5c-12.5 12.5-12.5 32.8 0 45.2c12.5 12.5 32.8 12.5 45.3 0c50-50 50-131 0-181z");
}

.yivtvjbgh {
  stop-color: var(--svg-color--4285f4, #4285f4);
}

</style>
