<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3q0aqb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:go-to-line-rounded" /></template>
<style>
.a3q0aqb2f {
  fill: currentColor;
  d: path("M10.938 6.563Q10.5 6.125 10.5 5.5t.438-1.062T12 4t1.063.438T13.5 5.5t-.437 1.063T12 7t-1.062-.437m0 13q-.438-.438-.438-1.063t.438-1.062T12 17t1.063.438t.437 1.062t-.437 1.063T12 20t-1.062-.437");
}

</style>
