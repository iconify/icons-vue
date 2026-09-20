<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o8ye7hbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:genesis-l1" /></template>
<style>
.o8ye7hbnh {
  fill-rule: evenodd;
  d: path("M12 3a9 9 0 1 1 0 18a9 9 0 0 1 0-18m1.5 7.5L15 12l-4.5 4.5L12 18l6-6l-1.5-1.5zM6 12l3 3l1.5-1.5L9 12l4.5-4.5L12 6z");
}

</style>
