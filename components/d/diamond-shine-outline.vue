<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyff6vjbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:diamond-shine-outline" /></template>
<style>
.hyff6vjbc {
  fill: currentColor;
  d: path("m12.02 21l-8.04-7.9l4.405-5.33h7.25l4.403 5.33zM5.46 7.25L3.489 5.298l.713-.707l1.971 1.951zm6.06-1.48V3h1v2.77zm7.009 1.48l-.695-.713l1.952-1.952l.714.713zm-6.51 12.354l6.173-6.065H5.827zM8.854 8.769l-3.129 3.77h12.57l-3.13-3.77z");
}

</style>
