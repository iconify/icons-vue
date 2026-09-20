<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amzj2oqvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-indent-decrease-sharp" /></template>
<style>
.amzj2oqvt {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm8-4v-2h10v2zm0-4v-2h10v2zm0-4V7h10v2zM3 5V3h18v2zm4 11l-4-4l4-4z");
}

</style>
