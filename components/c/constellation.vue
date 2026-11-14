<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt2mwkpfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:constellation" /></template>
<style>
.mt2mwkpfn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.5 4.75Q1.25 4.75 1.25 7T3.5 9.25h.036l2.455 4.909q-.741.55-.741 1.841q0 2.25 2.25 2.25T9.75 16q0-.595-.157-1.032l1.375-1.375q.437.157 1.032.157q.286 0 .535-.036l2.104 2.804q-.389.547-.389 1.482q0 2.25 2.25 2.25T18.75 18q0-1.322-.777-1.867l2.522-5.883h.005q2.25 0 2.25-2.25T20.5 5.75T18.25 8q0 1.322.777 1.867l-2.522 5.883H16.5q-.286 0-.535.036l-2.104-2.804q.389-.547.389-1.482q0-2.25-2.25-2.25T9.75 11.5q0 .595.157 1.032l-1.375 1.375q-.437-.157-1.032-.157h-.036L5.009 8.841Q5.75 8.291 5.75 7q0-2.25-2.25-2.25");
}

</style>
