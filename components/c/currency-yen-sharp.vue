<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kct7lkvye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:currency-yen-sharp" /></template>
<style>
.kct7lkvye {
  fill: currentColor;
  d: path("M11.5 20v-3.692h-5v-1h5V12.5h-5v-1h4.479L6.212 4h1.202L12 11.242L16.587 4h1.202l-4.768 7.5H17.5v1h-5v2.808h5v1h-5V20z");
}

</style>
