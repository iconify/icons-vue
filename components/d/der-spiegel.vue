<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b0dfm59-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:der-spiegel" /></template>
<style>
.b0dfm59-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.784 15.61v-8.2a2.91 2.91 0 0 0-2.908-2.91H15.124a2.91 2.91 0 0 0-2.908 2.909V26.21h16.31v10.928h-9.052v-6.687h-7.258v10.14a2.91 2.91 0 0 0 2.908 2.908h17.752a2.91 2.91 0 0 0 2.908-2.909V19.85h-16.31v-8.989h9.052v4.748Z");
}

</style>
