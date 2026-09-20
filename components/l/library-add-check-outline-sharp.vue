<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtluwrb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:library-add-check-outline-sharp" /></template>
<style>
.jtluwrb_h {
  fill: currentColor;
  d: path("m12.7 14.05l5.65-5.65l-1.4-1.45l-4.25 4.25l-2.15-2.1l-1.4 1.4zM6 18V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zM8 4v12z");
}

</style>
