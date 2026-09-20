<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou_wv0b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:event-list-sharp" /></template>
<style>
.ou_wv0b-c {
  fill: currentColor;
  d: path("M14 21v-8h8v8zM2 18v-2h9v2zm12-7V3h8v8zM2 8V6h9v2z");
}

</style>
