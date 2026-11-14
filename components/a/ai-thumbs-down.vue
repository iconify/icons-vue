<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pupgj6a8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ai-thumbs-down" /></template>
<style>
.pupgj6a8b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 5.25q0-2.5-2.5-2.5q-1.036 0-1.768.732T2.75 5.25v6q0 2.5 2.5 2.5t2.5-2.5zm1.058 8.538q-.058-.138-.058-.288V3.75q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q9.426 3 9.5 3h7.75q2.148 0 2.728 2.318l.011.053l.998 5.742q.251 1.27-.455 2.188q-.73.949-2.032.949h-4.115l.35 2.098q.432 1.763-.385 2.852q-.787 1.05-2.35 1.05q-.111 0-.217-.032q-.107-.032-.199-.094t-.163-.147q-.071-.086-.113-.189z");
}

</style>
