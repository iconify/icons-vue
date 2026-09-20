<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a9dl0vblp"/><path class="k6x6uv-ap"/><path class="s9l3g3b4l"/><path class="du_3_4tit"/><path class="u8rhnqeij"/><path class="dt6efbtua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:logit-bias-outline-thin" /></template>
<style>
.a9dl0vblp {
  d: path("M6 6v13");
}

.dt6efbtua {
  d: path("M9.5 6 12 8.5 14.5 6");
}

.du_3_4tit {
  d: path("M4 21.5h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6x6uv-ap {
  d: path("M12 11v8");
}

.s9l3g3b4l {
  d: path("M18 6v13");
}

.u8rhnqeij {
  d: path("M12 2.5V5");
}

</style>
