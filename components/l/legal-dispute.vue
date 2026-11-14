<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy3ye-bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:legal-dispute" /></template>
<style>
.cy3ye-bjb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 1.75H5q-1.346 0-2.298.952T1.75 5v3.25q0 3.25 3.25 3.25h11.25q.158 0 .303-.064t.252-.181q.1-.111.151-.251t.043-.29t-.071-.284t-.173-.235L14.25 7.918V5q0-3.25-3.25-3.25m-1.75 12.5H19q1.346 0 2.298.952t.952 2.298V19q0 1.346-.952 2.298T19 22.25h-4.5q-1.346 0-2.298-.952T11.25 19v-1.168l-2.505-2.277q-.11-.1-.173-.235q-.064-.135-.071-.284t.043-.29t.151-.251q.107-.117.252-.181t.303-.064");
}

</style>
