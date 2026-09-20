<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue_vhvbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:feed-sharp" /></template>
<style>
.ue_vhvbsw {
  fill: currentColor;
  d: path("M3 21V3h13l5 5v13zM15 5v4h4zM7 17h10v-2H7zm0-8h5V7H7zm0 4h10v-2H7z");
}

</style>
