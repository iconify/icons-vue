<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3mj-_bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-add-above-24-filled" /></template>
<style>
.g3mj-_bvi {
  fill: currentColor;
  d: path("M20.25 9a.75.75 0 0 1 .75.75v8A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75v-8A.75.75 0 0 1 3.75 9zm0-6a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1 0-1.5z");
}

</style>
