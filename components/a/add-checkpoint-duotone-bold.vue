<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qn-h03e3f"/><path class="zwjzc3g_l"/><path class="s8jyiubgh"/><path class="c9lo3xbix"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="nb_catcjy"/><path class="jtt8g10_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:add-checkpoint-duotone-bold" /></template>
<style>
.c9lo3xbix {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.crv4i00bu {
  d: path("M4 3v18");
}

.jtt8g10_o {
  d: path("M9 10h6");
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.nb_catcjy {
  d: path("M12 7v6");
}

.qn-h03e3f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s8jyiubgh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zwjzc3g_l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
