<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sijxulk3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-access-disabled-sharp" /></template>
<style>
.sijxulk3e {
  fill: currentColor;
  d: path("M20.462 21.492L15.969 17H13v2h2v1H9v-1h2v-2H3V4.04h1.425v1.416L1.777 2.808l.708-.708l18.684 18.685zm-.396-4.642L7.216 4H21v12.85z");
}

</style>
