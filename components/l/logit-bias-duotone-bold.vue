<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o5aoyb2jb"/><path class="fewd_qbim"/><path class="v1e_0ac3p"/><path class="tu8ll15ii"/><path class="ckz71mbmf"/><path class="d3460tyww"/><path class="a9dl0vblp"/><path class="k6x6uv-ap"/><path class="s9l3g3b4l"/><path class="du_3_4tit"/><path class="u8rhnqeij"/><path class="dt6efbtua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:logit-bias-duotone-bold" /></template>
<style>
.a9dl0vblp {
  d: path("M6 6v13");
}

.ckz71mbmf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 2.5V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d3460tyww {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 6 12 8.5 14.5 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dt6efbtua {
  d: path("M9.5 6 12 8.5 14.5 6");
}

.du_3_4tit {
  d: path("M4 21.5h16");
}

.fewd_qbim {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6x6uv-ap {
  d: path("M12 11v8");
}

.o5aoyb2jb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s9l3g3b4l {
  d: path("M18 6v13");
}

.tu8ll15ii {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 21.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u8rhnqeij {
  d: path("M12 2.5V5");
}

.v1e_0ac3p {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
