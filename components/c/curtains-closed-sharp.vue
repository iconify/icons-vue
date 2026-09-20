<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3cr0pqzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:curtains-closed-sharp" /></template>
<style>
.i3cr0pqzy {
  fill: currentColor;
  d: path("M2 21v-2h2V3h16v16h2v2zm9-2h2V5h-2z");
}

</style>
