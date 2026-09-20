<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-lmc2k_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:elevation-outline-sharp" /></template>
<style>
.z-lmc2k_e {
  fill: currentColor;
  d: path("m3.685 19.192l5.007-7h5.012l5.988-6.988v13.988zm.038-4.401l-.792-.574l3.858-5.41h5.03l4.508-5.282l.77.666l-4.84 5.617H7.29zm1.92 3.401h13.05v-10.3l-4.55 5.3h-4.95zm13.05 0");
}

</style>
