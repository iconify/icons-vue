<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxsbpt71g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gite-outline" /></template>
<style>
.rxsbpt71g {
  fill: currentColor;
  d: path("M2 19v-9l4-4h1V4h2v2h9l4 4v9zm14-2h4v-6.175l-2-2l-2 2zM4 17h10v-5H4z");
}

</style>
