<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmnruzz_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chromosome-pair" /></template>
<style>
.jmnruzz_a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.25q3.25 0 3.25 3.25v4q0 .958-.341 1.75h4.182q-.341-.792-.341-1.75v-4q0-3.25 3.25-3.25t3.25 3.25v4q0 1.436-.767 2.5q.767 1.064.767 2.5v4q0 3.25-3.25 3.25t-3.25-3.25v-4q0-.958.341-1.75H9.909q.341.792.341 1.75v4q0 3.25-3.25 3.25T3.75 18.5v-4q0-1.436.767-2.5q-.767-1.064-.767-2.5v-4q0-3.25 3.25-3.25");
}

</style>
