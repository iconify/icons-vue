<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq7we_l4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-check-fill-sharp" /></template>
<style>
.pq7we_l4v {
  fill: currentColor;
  d: path("M21 17a1 1 0 0 1-1 1h-4a4 4 0 0 1-8 0H4a1 1 0 0 1-1-1v-2c0-.39.098-.773.299-1.108c.133-.222.312-.417.494-.599c.065-.066.145-.133.193-.214C4 13.057 4 13.026 4 13v-3a8 8 0 0 1 16 0v3c0 .026 0 .057.014.079c.048.081.128.148.193.214c.182.182.361.377.494.599c.201.335.299.718.299 1.108Zm-10-5.414l-1.293-1.293a.999.999 0 1 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l4-4a.999.999 0 1 0-1.414-1.414Z");
}

</style>
