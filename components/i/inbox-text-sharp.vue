<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7ucklblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:inbox-text-sharp" /></template>
<style>
.x7ucklblg {
  fill: currentColor;
  d: path("M7.5 11.904h9v-1h-9zm0-3.077h9v-1h-9zM4 20V4h16v16zm9.725-3.934q.775-.55 1.075-1.45H19V5H5v9.616h4.2q.3.9 1.075 1.45t1.725.55t1.725-.55");
}

</style>
