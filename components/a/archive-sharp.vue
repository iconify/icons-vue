<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8zfmwbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:archive-sharp" /></template>
<style>
.x8zfmwbks {
  fill: currentColor;
  d: path("m12 17.192l3.308-3.307l-.708-.708l-2.1 2.1v-4.7h-1v4.7l-2.1-2.1l-.708.708zM4 20V6.916L6.416 4h11.15L20 6.954V20zM5.38 6.808H18.6L17.096 5H6.885z");
}

</style>
