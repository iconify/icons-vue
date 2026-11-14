<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pfp1h7b3r"/><path class="ruozrm43z"/><path class="gkhcwacrr"/><path class="dsk8vn70f"/><path class="wbhtgob2w"/><path class="tpkx0krqc"/><path class="h3fs5ybox"/><path class="cm8bnlhui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:justice-scale-broken" /></template>
<style>
.cm8bnlhui {
  d: path("M16.5 13.5H22C22 15.0188 20.7688 16.25 19.25 16.25C17.7312 16.25 16.5 15.0188 16.5 13.5Z");
}

.dsk8vn70f {
  d: path("M9.9751 6H19.2501");
}

.gkhcwacrr {
  d: path("M4.75 6H6.775");
}

.h3fs5ybox {
  d: path("M2 13.5H7.5C7.5 15.0188 6.2688 16.25 4.75 16.25C3.2312 16.25 2 15.0188 2 13.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfp1h7b3r {
  d: path("M12 2.5V21.5");
}

.ruozrm43z {
  d: path("M7.5 21.5H16.5");
}

.tpkx0krqc {
  d: path("M16.5 13.5L19.25 6L22 13.5");
}

.wbhtgob2w {
  d: path("M2 13.5L4.75 6L7.5 13.5");
}

</style>
