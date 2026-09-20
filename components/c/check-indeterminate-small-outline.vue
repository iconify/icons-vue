<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_w9du6kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:check-indeterminate-small-outline" /></template>
<style>
.v_w9du6kn {
  fill: currentColor;
  d: path("M6 13v-2h12v2z");
}

</style>
