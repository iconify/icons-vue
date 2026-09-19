<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdkomdvjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-roller-shades-closed" /></template>
<style>
.hdkomdvjo {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h8.25c0 .97.78 1.75 1.75 1.75s1.75-.78 1.75-1.75H22v-2zM6 19v-2h5v2zm7 0v-2h5v2z");
}

</style>
