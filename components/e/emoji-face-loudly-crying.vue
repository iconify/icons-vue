<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b4i4ug5fd"/><path class="jzy72my9w"/><circle class="l6cd208_p"/><path class="sd6-9lbyp"/><path class="kjwf5wkwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-face-loudly-crying" /></template>
<style>
.b4i4ug5fd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.148 37.306c-.706-1.311-.822-4.46-.822-6.07c0-3.216 3.782-10.44 3.782-10.44m5.416.054s-4.372 8.56-4.372 11.191c0 2.465.909 7.065.909 8.674");
}

.jzy72my9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.141 21.441c.333-.277 1.807-1.441 3.949-1.316a5.7 5.7 0 0 1 3.29 1.316m-.18 11.083a3.8 3.8 0 0 0 7.6.003v-.003a3.8 3.8 0 0 0-7.6-.006z");
}

.kjwf5wkwo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.859 21.438c-.333-.277-1.807-1.441-3.949-1.316a5.7 5.7 0 0 0-3.29 1.316");
}

.l6cd208_p {
  cx: 24px;
  cy: 24px;
  r: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sd6-9lbyp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.853 37.303c.705-1.312.82-4.46.82-6.07c0-3.216-3.781-10.441-3.781-10.441m-5.416.054s4.372 8.56 4.372 11.192c0 2.465-.909 7.065-.909 8.673");
}

</style>
