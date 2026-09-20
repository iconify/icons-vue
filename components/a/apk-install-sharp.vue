<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgpgtbv7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apk-install-sharp" /></template>
<style>
.fgpgtbv7w {
  fill: currentColor;
  d: path("m18.539 21l-3.289-3.308l.689-.713l2.1 2.094v-4.861h1v4.861l2.1-2.075l.688.694zM3 21V3h9.5L17 7.5v5.039h-2.962V21zm9-13h4l-4-4zM5.962 18.23h8.077q-.08-.987-.596-1.813q-.516-.827-1.374-1.311l.767-1.373q.041-.081.006-.177q-.034-.096-.127-.146q-.074-.05-.158-.026t-.124.106l-.792 1.404q-.385-.161-.796-.245t-.842-.083t-.836.086t-.807.242l-.783-1.404q-.05-.086-.143-.106q-.093-.019-.18.031q-.02 0-.081.318l.777 1.373q-.852.484-1.38 1.31t-.609 1.815m1.948-1.333q-.12-.121-.12-.283t.12-.282t.283-.121t.273.12t.112.284q0 .161-.112.282q-.111.121-.273.121t-.283-.121m3.635 0q-.121-.121-.121-.283t.121-.282t.283-.121t.282.12t.122.284t-.122.282q-.12.121-.282.121t-.283-.121");
}

</style>
