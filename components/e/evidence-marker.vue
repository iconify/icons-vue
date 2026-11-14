<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j214oz35e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:evidence-marker" /></template>
<style>
.j214oz35e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.447 5.161l-3.152 13q-.286 1.181.465 2.135t1.965.954h10.55q1.214 0 1.965-.954t.465-2.135l-3.152-13q-.463-1.91-2.429-1.911H9.876q-1.966.001-2.429 1.911m4.565 2.77q.113-.098.255-.144t.291-.035t.281.079t.23.181q.088.102.134.228t.047.26v8q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-6.369l-.512.438q-.056.049-.12.085q-.065.036-.135.059t-.144.032q-.073.008-.147.003q-.073-.006-.144-.026t-.137-.053t-.124-.079t-.106-.102t-.085-.12q-.036-.065-.059-.135t-.032-.144q-.008-.073-.003-.147q.006-.073.026-.144t.053-.137t.079-.124t.102-.106z");
}

</style>
