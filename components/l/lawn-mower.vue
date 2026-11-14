<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqao1jbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lawn-mower" /></template>
<style>
.fqao1jbyl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 10.25q-.3 0-.573.028L5.631 3.594q-.051-.079-.12-.143t-.152-.109q-.082-.045-.174-.069Q5.094 3.25 5 3.25H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q1.75 3.926 1.75 4t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.091l3.858 6.001Q7.25 11.526 7.25 13.5q0 2.258 1.568 2.947Q8.5 17.064 8.5 18q0 2.75 2.75 2.75T14 18q0-.719-.188-1.25h1.876q-.188.531-.188 1.25q0 2.75 2.75 2.75T21 18q0-.936-.318-1.553q1.568-.689 1.568-2.947q0-1.346-.952-2.298T19 10.25z");
}

</style>
