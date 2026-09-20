<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp9zf-mfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:browser-updated-sharp" /></template>
<style>
.qp9zf-mfo {
  fill: currentColor;
  d: path("M7.192 20v-1.538l.77-.77H3V4h9.442v1H4v11.692h16V13h1v4.692h-4.962l.77.77V20zm8.52-5.712L11.423 10l.708-.708l3.08 3.094V4h1v8.387l3.081-3.095L20 10z");
}

</style>
