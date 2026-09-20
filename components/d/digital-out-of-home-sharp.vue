<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxyl4x2-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:digital-out-of-home-sharp" /></template>
<style>
.nxyl4x2-c {
  fill: currentColor;
  d: path("M.5 22.5v-21h10v21h-1v-2h-8v2zm15.116 0v-5.792l2.15-2.089l-.872-4.042q-.955 1.51-2.103 2.149q-1.147.64-2.483.736v-1q1.315-.116 2.151-.633q.837-.517 1.485-1.577l.923-1.494q.356-.587.946-.706q.59-.12 1.221.156l4.466 1.854V14h-1v-3.267l-2.867-1.196L22.346 22.5h-1.011l-1.852-7.496l-2.867 2.742V22.5zm-11.5-9.692L7.269 11L4.115 9.192zM15.799 6.2q-.491-.492-.491-1.201t.491-1.201T17 3.308t1.201.491T18.692 5t-.491 1.201T17 6.692t-1.201-.491");
}

</style>
