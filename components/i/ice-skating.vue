<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w17cvrn4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ice-skating" /></template>
<style>
.w17cvrn4h {
  fill: currentColor;
  d: path("M2 22v-2h4v-2H3V3h8v3H8.5q-.2 0-.35.15T8 6.5t.15.35t.35.15h2.55v1H8.5q-.2 0-.35.15T8 8.5t.15.35t.35.15h2.9q.35.575.888.975t1.187.6l2.625.725q1.3.35 2.1 1.412t.8 2.413V18h-3v2h2q1.25 0 2.125-.875T21 17h2q0 2.075-1.463 3.538T18 22zm6-2h6v-2H8z");
}

</style>
