<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plr5pbcli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gavel" /></template>
<style>
.plr5pbcli {
  fill: currentColor;
  d: path("M4 21v-2h12v2zm5.65-4.85L4 10.5l2.1-2.15L11.8 14zM16 9.8l-5.65-5.7L12.5 2l5.65 5.65zM20.6 20L7.55 6.95l1.4-1.4L22 18.6z");
}

</style>
