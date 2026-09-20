<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xx1i4w8_s"/><ellipse class="z3-f7gbvt"/><path class="kza0c5erj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bsnl-selfcare" /></template>
<style>
.kza0c5erj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.06 37.542a2.479 2.479 0 0 1 0 4.958H7.97v-9.915h4.09a2.479 2.479 0 1 1 0 4.957m23.012-5.012v9.915h4.957m-14.288.014v-9.916l6.569 9.916v-9.916M16.903 41.34a2.96 2.96 0 0 0 2.479 1.116h1.487a2.486 2.486 0 0 0 2.479-2.48a2.486 2.486 0 0 0-2.479-2.478h-1.611a2.486 2.486 0 0 1-2.479-2.479a2.486 2.486 0 0 1 2.479-2.479h1.487a2.66 2.66 0 0 1 2.479 1.116m-11.163 3.886h-4.09");
}

.xx1i4w8_s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.344 6.726c3.067-1.387 5.422-1.607 6.524-.61c2.248 2.031-1.22 8.46-7.747 14.358q-.46.416-.931.82m-2.941-2.316l3.959 3.959l-3.976.017Zm-5.593 9.04c-3.067 1.387-5.422 1.607-6.524.61c-2.248-2.031 1.22-8.46 7.747-14.358q.46-.416.931-.82m2.867 2.09l-4.355-4.355l4.374-.019Z");
}

.z3-f7gbvt {
  cx: 23.664px;
  cy: 17.305px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.568px;
  ry: 9.902px;
}

</style>
