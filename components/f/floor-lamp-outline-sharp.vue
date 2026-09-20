<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzq521n1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:floor-lamp-outline-sharp" /></template>
<style>
.zzq521n1x {
  fill: currentColor;
  d: path("M11 19v-8H4.65l2.775-9h9.15l2.775 9H13v8zM7.35 9h9.3L15.1 4H8.9zM8 22v-2h8v2zm4-15.5");
}

</style>
