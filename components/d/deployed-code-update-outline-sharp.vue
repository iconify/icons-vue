<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aar557bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:deployed-code-update-outline-sharp" /></template>
<style>
.aar557bxd {
  fill: currentColor;
  d: path("m18 21.346l2.539-2.538l-.547-.546l-1.608 1.607v-3.715h-.769v3.715l-1.607-1.607l-.547.546zm-6-9.919l6.425-3.713L12 4L5.575 7.714zm-8 5.121v-9.1l8-4.594l8 4.598v4.394h-1V8.523l-7.025 4.05L5 8.523v7.427l6.736 3.898v1.127zm11.165 5.038Q14 20.42 14 18.75t1.165-2.835T18 14.75t2.836 1.165T22 18.75t-1.164 2.836T18 22.75t-2.835-1.164m-3.428-9.65");
}

</style>
