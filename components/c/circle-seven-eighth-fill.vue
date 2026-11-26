<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f91w4ty6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-seven-eighth-fill" /></template>
<style>
.f91w4ty6o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12ZM7.0502 16.9498C8.3159 18.2154 10.0672 19 12 19C15.8661 19 19 15.8661 19 12C19 8.1339 15.8661 5 12 5C11.4477 5 11 5.4477 11 6L11 9.5858L8.4645 7.0503C8.277 6.8628 8.0226 6.7574 7.7574 6.7574C7.4922 6.7574 7.2379 6.8627 7.0503 7.0503C5.7375 8.363 5 10.1435 5 12C5 13.9328 5.7846 15.6841 7.0502 16.9498Z");
}

</style>
