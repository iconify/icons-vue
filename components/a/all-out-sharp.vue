<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwlc78bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:all-out-sharp" /></template>
<style>
.pwlc78bxw {
  fill: currentColor;
  d: path("M4 20v-3.5h1V19h2.5v1zm12.5 0v-1H19v-2.5h1V20zm-8.748-3.752Q6 14.496 6 12t1.752-4.248T12 6t4.248 1.752T18 12t-1.752 4.248T12 18t-4.248-1.752M4 7.5V4h3.5v1H5v2.5zm15 0V5h-2.5V4H20v3.5z");
}

</style>
