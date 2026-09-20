<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebdgmhjjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:business-center-sharp" /></template>
<style>
.ebdgmhjjv {
  fill: currentColor;
  d: path("M3 20v-5.5h7V16h4v-1.5h7V20zm8-5v-2h2v2zm-8-1.5V7h6V4h6v3h6v6.5h-7V12h-4v1.5zM10 7h4V5h-4z");
}

</style>
