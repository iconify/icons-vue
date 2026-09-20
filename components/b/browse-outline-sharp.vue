<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfd1tow1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:browse-outline-sharp" /></template>
<style>
.xfd1tow1d {
  fill: currentColor;
  d: path("M3 21v-6h8v6zm10 0V11h8v10zM3 13V3h8v10zm10-4V3h8v6zM5 19h4v-2H5zm10 0h4v-6h-4zM5 11h4V5H5zm10-4h4V5h-4z");
}

</style>
