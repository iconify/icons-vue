<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvmpo9u_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:earbud-left-sharp" /></template>
<style>
.xvmpo9u_d {
  fill: currentColor;
  d: path("M6.789 21v-9.327H4V5h7.558v16zm7.519-7.327V3h.73q2.116 0 3.539 1.577T20 8.327t-1.423 3.76t-3.539 1.586z");
}

</style>
