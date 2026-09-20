<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs23tsb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:browse-sharp" /></template>
<style>
.fs23tsb7q {
  fill: currentColor;
  d: path("M3 21v-6h8v6zm10 0V11h8v10zM3 13V3h8v10zm10-4V3h8v6z");
}

</style>
