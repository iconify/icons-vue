<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhscjl02a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-oak" /></template>
<style>
.dhscjl02a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.16 5.279q.052-.228.075-.472q.136-1.431-.831-2.494T12 1.25T9.596 2.313t-.831 2.494q.023.244.075.472q-.468.041-.954.228q-1.626.627-2.004 2.328t.83 2.957q.105.11.215.208q-.11.098-.215.208q-1.208 1.256-.83 2.957t2.004 2.328q1.267.488 2.409-.016l.955 1.273V5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 4.25t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v12.75l.955-1.273q1.142.504 2.409.016q1.626-.627 2.004-2.328t-.83-2.957q-.105-.11-.215-.208q.11-.098.215-.208q1.208-1.256.83-2.957t-2.004-2.328q-.486-.187-.954-.228");
}

</style>
