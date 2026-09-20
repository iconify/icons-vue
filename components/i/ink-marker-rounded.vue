<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0hba7bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-marker-rounded" /></template>
<style>
.d0hba7bul {
  fill: currentColor;
  d: path("m6.8 21.4l-.95-.95L4.8 21.5q-.475.475-1.162.488T2.5 21.5q-.475-.475-.475-1.15T2.5 19.2l1.05-1.05l-.95-1L16.45 3.3q.3-.3.725-.3t.725.3l2.8 2.8q.3.3.3.725t-.3.725zm4.3-9.9l-5.7 5.65l1.45 1.45l5.65-5.7z");
}

</style>
