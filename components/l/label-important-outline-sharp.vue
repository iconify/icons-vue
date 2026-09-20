<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3-tvrbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:label-important-outline-sharp" /></template>
<style>
.z3-tvrbfs {
  fill: currentColor;
  d: path("m2 20l6-8l-6-8h14l6 8l-6 8zm4-2h9l4.5-6L15 6H6l4.5 6zm6.75-6");
}

</style>
