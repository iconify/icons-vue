<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8rm69byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-end-arrow-notch-sharp" /></template>
<style>
.t8rm69byn {
  fill: currentColor;
  d: path("m12.192 16.827l2.406-4.327H2.5v-1h12.098l-2.406-4.327L19.788 12z");
}

</style>
