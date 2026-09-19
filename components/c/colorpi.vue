<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t6pmj5dfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:colorpi" /></template>
<style>
.t6pmj5dfn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.075 5.5l-1.702 8.814H9.208v6.508h5.91l-1.295 6.708H9.208v6.507h3.358L10.934 42.5h6.657l1.632-8.463H24.9L23.268 42.5h6.657l1.632-8.463h7.235V27.53h-5.978l1.295-6.708h4.683v-6.508h-3.428L37.066 5.5h-6.657l-1.702 8.814H23.03L24.732 5.5zm3.7 15.322h5.678l-1.296 6.708H20.48z");
}

</style>
