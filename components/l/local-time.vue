<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr1eyqzya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:local-time" /></template>
<style>
.vr1eyqzya {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m7.998 6.813l3.122 1.784q.064.036.12.085q.056.048.101.107t.078.124t.053.138q.019.071.024.145q.005.073-.004.147q-.009.073-.033.143q-.023.07-.06.134q-.036.064-.085.12q-.048.056-.107.101t-.124.078q-.066.033-.138.053q-.071.019-.145.024q-.073.005-.147-.004q-.073-.009-.143-.033q-.07-.023-.134-.06l-3.5-2q-.086-.049-.157-.119q-.07-.07-.12-.156t-.075-.181q-.026-.096-.026-.195V6.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 5.75t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
