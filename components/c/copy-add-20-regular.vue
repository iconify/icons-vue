<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="duvbl5b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-add-20-regular" /></template>
<style>
.duvbl5b2n {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M7 7H5.5A1.5 1.5 0 0 0 4 8.5v6A1.5 1.5 0 0 0 5.5 16h3.708q.149.522.39.995L9.5 17h-4A2.5 2.5 0 0 1 3 14.5v-6A2.5 2.5 0 0 1 5.5 6H7zm7.5 5a.5.5 0 0 0-.5.5V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15v-1.5a.5.5 0 0 0-.5-.5m0-9A2.5 2.5 0 0 1 17 5.5v4.1a5.5 5.5 0 0 0-1-.392V5.5A1.5 1.5 0 0 0 14.5 4h-4A1.5 1.5 0 0 0 9 5.5v6c0 .382.144.73.379.994q-.2.51-.298 1.064A2.5 2.5 0 0 1 8 11.5v-6A2.5 2.5 0 0 1 10.5 3z");
}

</style>
