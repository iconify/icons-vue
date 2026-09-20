<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcaqf3bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:beenhere-outline-sharp" /></template>
<style>
.pcaqf3bdn {
  fill: currentColor;
  d: path("m12 21.77l-7-5.25V3h14v13.52zm0-1.27l6-4.48V4H6v12.02zm-1.05-6.192l4.958-4.958l-.708-.72l-4.25 4.25l-2.138-2.138l-.72.708zM12 4H6h12z");
}

</style>
