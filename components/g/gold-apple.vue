<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w4c_3bbwa"/><path class="gjrdq0ukr"/><path class="j6augj9bd"/><path class="d45fc8btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gold-apple" /></template>
<style>
.d45fc8btz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.138 4.5l-6.512 3.365c-5.545 2.866-7.601 7.4-7.651 11.418c-.053 4.21 3.159 6.35 6.57 4.586l7.593-3.924");
}

.gjrdq0ukr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.862 43.5l6.512-3.365c5.545-2.866 7.601-7.4 7.651-11.418c.053-4.21-3.159-6.35-6.57-4.586l-7.593 3.924");
}

.j6augj9bd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.138 15.681l-6.512 3.366c-5.545 2.866-7.601 7.4-7.651 11.417c-.053 4.21 3.159 6.35 6.57 4.586l7.593-3.924");
}

.w4c_3bbwa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.862 32.319l6.512-3.366c5.545-2.866 7.601-7.4 7.651-11.417c.053-4.21-3.159-6.35-6.57-4.586l-7.593 3.924");
}

</style>
