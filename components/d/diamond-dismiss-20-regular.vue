<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t_s006f3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-dismiss-20-regular" /></template>
<style>
.t_s006f3r {
  fill: currentColor;
  d: path("M7.876 1.877a3 3 0 0 1 4.243 0l5.999 6a3 3 0 0 1 0 4.242l-5.999 5.999a3 3 0 0 1-4.243 0l-5.998-6a3 3 0 0 1 0-4.242zm3.536.707a2 2 0 0 0-2.829 0l-5.998 6a2 2 0 0 0 0 2.828l5.998 5.999c.781.78 2.048.78 2.83 0l5.997-6a2 2 0 0 0 0-2.828zm.985 4.313a.5.5 0 1 1 .707.707L10.707 10l2.397 2.397a.5.5 0 0 1-.707.707L10 10.707l-2.396 2.397a.5.5 0 0 1-.707-.707L9.293 10L6.897 7.604a.5.5 0 0 1 .707-.707L10 9.293z");
}

</style>
