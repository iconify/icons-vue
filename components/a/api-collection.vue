<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxq19dw8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:api-collection" /></template>
<style>
.cxq19dw8q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 6.5q0-1.139.805-1.945q.806-.805 1.945-.805h5q.149 0 .287.057t.243.163l1.781 1.78H19.5q2.75 0 2.75 2.75v10q0 2.75-2.75 2.75h-15q-2.75 0-2.75-2.75zm7 4.25h-1.5q-2.5 0-2.5 2.5v2q0 2.5 2.5 2.5h1.5q2.5 0 2.5-2.5v-2q0-2.5-2.5-2.5m6.25 0q-2.5 0-2.5 2.5v2q0 2.5 2.5 2.5h1.5q2.5 0 2.5-2.5v-2q0-2.5-2.5-2.5z");
}

</style>
