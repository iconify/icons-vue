<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mcojpy6is"/><path class="sm8yo0y2z"/><path class="kr5tlbbsn"/><path class="xi1g2jw8q"/><path class="z0ud8rb7a"/><path class="ic_pehd5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audio-denoise-duotone-bold" /></template>
<style>
.ic_pehd5a {
  d: path("M3 17h18");
}

.kr5tlbbsn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcojpy6is {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 7 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sm8yo0y2z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 10.5 12 13l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xi1g2jw8q {
  d: path("m3 7 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

.z0ud8rb7a {
  d: path("M9.5 10.5 12 13l2.5 -2.5");
}

</style>
