<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfi9k-54n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-color-fill" /></template>
<style>
.tfi9k-54n {
  fill: currentColor;
  d: path("M6.175 1.4L7.6 0l8.575 8.575q.575.575.575 1.425t-.575 1.425l-4.75 4.75q-.575.575-1.425.575t-1.425-.575l-4.75-4.75Q3.25 10.85 3.25 10t.575-1.425L8.575 3.8zM10 5.225L5.225 10h9.55zm7.588 11.188Q17 15.825 17 15q0-.525.313-1.125T18 12.75q.225-.3.475-.625T19 11.5q.275.3.525.625t.475.625q.375.525.688 1.125T21 15q0 .825-.587 1.413T19 17t-1.412-.587M2 24v-4h20v4z");
}

</style>
