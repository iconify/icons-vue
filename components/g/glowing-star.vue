<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="s2mmzmbtg"/><path class="sevlc20sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:glowing-star" /></template>
<style>
.s2mmzmbtg {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M62 23H39.1L32 2l-7.1 21H2l18.5 13l-7.1 21L32 44l18.5 13l-7.1-21z");
}

.sevlc20sz {
  fill: var(--svg-color--ffdf85, #ffdf85);
  d: path("m46.2 20.3l4-11.4l-10.5 7.2l1.5 4.2zM27.9 50L32 62l4.1-12l-4.1-2.8zm22.8-15.7l-3.8 2.6l1.6 4.8h12.9zM24.3 16.1L13.8 8.9l4 11.4h5zm-11 18.2L2.6 41.7h12.9l1.6-4.8z");
}

</style>
