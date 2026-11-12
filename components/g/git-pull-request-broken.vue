<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ixqjpwl1k"/><path class="xq0r2t84g"/><path class="pu5j3xbce"/><path class="r8f1dnbnl"/><path class="f8m9b9b9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-pull-request-broken" /></template>
<style>
.f8m9b9b9z {
  d: path("M2 5C2 6.65685 3.34315 8 5 8C6.65685 8 8 6.65685 8 5C8 3.34315 6.65685 2 5 2");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixqjpwl1k {
  d: path("M8 19.7354C8 21.3922 6.65685 22.7354 5 22.7354C3.34315 22.7354 2 21.3922 2 19.7354C2 18.0785 3.34315 16.7354 5 16.7354C6.65685 16.7354 8 18.0785 8 19.7354Z");
}

.pu5j3xbce {
  d: path("M22 19.0039C22 20.6608 20.6569 22.0039 19 22.0039C17.3431 22.0039 16 20.6608 16 19.0039C16 17.3471 17.3431 16.0039 19 16.0039C20.6569 16.0039 22 17.3471 22 19.0039Z");
}

.r8f1dnbnl {
  stroke-linejoin: round;
  d: path("M15.0002 2L12.0002 5L15.0002 8M12.0002 5L16.314 5.00405C17.186 5.00405 17.7487 5.37787 18.0145 5.61058L18.0145 5.61061C18.1265 5.70871 18.1826 5.75776 18.2044 5.77944C18.2263 5.80112 18.2766 5.85744 18.3771 5.97008C18.6148 6.23656 18.9998 6.80422 18.9998 7.68575L19 11.8429");
}

.xq0r2t84g {
  d: path("M5 16.7354L5 8");
}

</style>
