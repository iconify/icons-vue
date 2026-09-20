<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dp6dvchmk"/><path class="p86p59b-c"/><path class="r7xk8o29f"/><path class="h7eeppe6g"/><path class="gkowgccsl"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:histogram-outline-bold" /></template>
<style>
.dp6dvchmk {
  d: path("M4 12v8");
}

.gkowgccsl {
  d: path("M20 14v6");
}

.h7eeppe6g {
  d: path("M16 9v11");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.p86p59b-c {
  d: path("M8 7v13");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
