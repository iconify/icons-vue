<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7cxobc6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-highlighter-off-rounded" /></template>
<style>
.a7cxobc6t {
  fill: currentColor;
  d: path("m18.8 3.6l2.6 2.6q.6.6.6 1.4T21.4 9l-4.05 4.075q-.3.3-.725.3t-.725-.3L11.925 9.1q-.3-.3-.3-.725t.3-.725L16 3.6q.6-.6 1.4-.6t1.4.6m1.725 18.275q-.3.3-.712.3t-.713-.3L13.8 16.6L10 20.425q-.6.6-1.412.6t-1.413-.6l-.125.1q-.275.225-.6.35T5.775 21h-3.05q-.35 0-.488-.3t.113-.55l2.3-2.275q-.6-.6-.625-1.437T4.6 15l3.8-3.8l-6.3-6.3q-.3-.3-.3-.712t.3-.713t.713-.3t.712.3l17 17q.3.3.3.7t-.3.7");
}

</style>
