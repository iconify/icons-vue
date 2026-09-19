<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf6gvsb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-file-open" /></template>
<style>
.jf6gvsb0c {
  fill: currentColor;
  d: path("M14 2H6c-1.1 0-2 .9-2 2v16c0 1.1.89 2 1.99 2H15v-8h5V8zm-1 7V3.5L18.5 9zm4 12.66V16h5.66v2h-2.24l2.95 2.95l-1.41 1.41L19 19.41v2.24h-2z");
}

</style>
