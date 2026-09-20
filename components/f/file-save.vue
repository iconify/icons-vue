<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5nrgpcss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-save" /></template>
<style>
.v5nrgpcss {
  fill: currentColor;
  d: path("M14 24v-2h8v2zm4-3l-4-4l1.4-1.4l1.6 1.6v-4.175h2V17.2l1.6-1.6L22 17zM6 20q-.825 0-1.412-.587T4 18V4q0-.825.588-1.412T6 2h7l6 6v3.025h-7V20zm6-11h5l-5-5z");
}

</style>
