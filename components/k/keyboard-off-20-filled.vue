<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q4n57mksg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-off-20-filled" /></template>
<style>
.q4n57mksg {
  fill: currentColor;
  d: path("M2.146 2.147a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707L14.293 15H3.5A1.5 1.5 0 0 1 2 13.5v-8a1.5 1.5 0 0 1 1.307-1.486l-1.16-1.16a.5.5 0 0 1 0-.707M16.5 4A1.5 1.5 0 0 1 18 5.5v8c0 .644-.406 1.19-.976 1.403L6.121 4zm-11 8a.5.5 0 0 0 0 1h6.793l-1-1zm1.498-3a.753.753 0 1 0 0 1.506a.753.753 0 0 0 0-1.506m6.009 0a.752.752 0 1 0 0 1.504a.752.752 0 0 0 0-1.504M5.502 6.5a.752.752 0 1 0 0 1.505a.752.752 0 0 0 0-1.505m6 0a.752.752 0 1 0 0 1.505a.752.752 0 0 0 0-1.505m3 0a.752.752 0 1 0 0 1.505a.752.752 0 0 0 0-1.505");
}

</style>
