<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="seeswxb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:carpenter-sharp" /></template>
<style>
.seeswxb-y {
  fill: currentColor;
  d: path("m14.056 22.008l-3.5-3.514l1.348-1.386l-8.15-11.65L7 2.212l13.439 13.432zm.019-1.421l4.937-4.937l-2.112-2.136l-4.961 4.961z");
}

</style>
