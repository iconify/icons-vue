<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fr7svxvbh"/><path class="wtqjdkbpu"/><path class="a9qzx4bcp"/><path class="siv-r9ykp"/><path class="ivlybw9ey"/><path class="k91fgssvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:butterfly-duotone-bold" /></template>
<style>
.a9qzx4bcp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8c3 -4 9 -3 9 1 0 3 -3 4 -5 3 3 2 4 5 2 7s-6 -1 -6 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fr7svxvbh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ivlybw9ey {
  d: path("M12 8C9 4 3 5 3 9c0 3 3 4 5 3 -3 2 -4 5 -2 7s6 -1 6 -4");
}

.k91fgssvz {
  d: path("M12 8c3 -4 9 -3 9 1 0 3 -3 4 -5 3 3 2 4 5 2 7s-6 -1 -6 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.siv-r9ykp {
  d: path("M12 6v13");
}

.wtqjdkbpu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8C9 4 3 5 3 9c0 3 3 4 5 3 -3 2 -4 5 -2 7s6 -1 6 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
