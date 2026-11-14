<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v773ffbsw"/><path class="hnfym-b2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-card-retained" /></template>
<style>
.hnfym-b2a {
  d: path("M12.15 14.75H8.5V11.5h4v3.2m2.5 2.8h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v773ffbsw {
  d: path("M2.5 4h19v4.5h-19ZM6 8.5v10q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036T8.5 21h3.673M18 12.154V8.5");
}

</style>
