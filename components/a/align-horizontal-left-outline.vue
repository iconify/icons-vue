<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="met22ebbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-horizontal-left-outline" /></template>
<style>
.met22ebbu {
  fill: currentColor;
  d: path("M3.77 21V3h1v18zm3.576-4.692v-2.039h6.885v2.039zm0-6.577V7.692h12.885v2.039z");
}

</style>
