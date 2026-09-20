<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp4grdjcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-add-outline-rounded" /></template>
<style>
.dp4grdjcw {
  fill: currentColor;
  d: path("m12 16.923l-3.738 1.608q-.808.348-1.535-.134Q6 17.916 6 17.052V5.616q0-.691.463-1.153T7.616 4H12.5q.214 0 .357.143T13 4.5t-.143.357T12.5 5H7.616q-.231 0-.424.192T7 5.616v11.392q0 .327.279.519t.586.057L12 15.8l4.135 1.785q.307.134.586-.058t.279-.52V11.5q0-.213.143-.357T17.5 11t.357.143t.143.357v5.552q0 .864-.727 1.345q-.727.482-1.535.134zM12 5H7h6zm5 2h-1.5q-.213 0-.357-.143T15 6.5t.143-.357T15.5 6H17V4.5q0-.213.143-.357T17.5 4t.357.143T18 4.5V6h1.5q.214 0 .357.143T20 6.5t-.143.357T19.5 7H18v1.5q0 .214-.143.357T17.5 9t-.357-.143T17 8.5z");
}

</style>
