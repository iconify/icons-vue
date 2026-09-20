<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o5y7zn4_f"/><path class="sqz_lccii"/><path class="g1ifsobsy"/><path class="ixxv1jyxb"/><path class="zoq23y-nb"/><path class="ybh1xwgpp"/><path class="qfe94rk-q"/><path class="ygvoi9umd"/><path class="hxoe7gx5p"/><path class="vox58lg-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:group-by-duotone-bold" /></template>
<style>
.g1ifsobsy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hxoe7gx5p {
  d: path("M12 5v12");
}

.ixxv1jyxb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o5y7zn4_f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qfe94rk-q {
  d: path("M2 11h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sqz_lccii {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 11h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vox58lg-w {
  d: path("M12 11h10");
}

.ybh1xwgpp {
  d: path("M2 5h8");
}

.ygvoi9umd {
  d: path("M2 17h8");
}

.zoq23y-nb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
