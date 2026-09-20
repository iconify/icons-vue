<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq-1kubxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:label-important-sharp" /></template>
<style>
.dq-1kubxi {
  fill: currentColor;
  d: path("m2 20l6-8l-6-8h14l6 8l-6 8z");
}

</style>
