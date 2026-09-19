<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="towxurb4q"/><path class="lu6u-kvte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ironfox" /></template>
<style>
.lu6u-kvte {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.582 24.336c.957 1.828 3.33 6.773 5.673 3.364zm18.612 0c-.958 1.828-3.33 6.773-5.673 3.364z");
}

.towxurb4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.582 5.612L5.5 14.806c.118 13.791 8.084 20.855 18.276 27.582c11.773-7.4 18.612-13.23 18.724-27.582l-9.53-9.194v9.194H14.582z");
}

</style>
