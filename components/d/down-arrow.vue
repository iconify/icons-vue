<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gz7p0cufa"/><path class="grrjwbjvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:down-arrow" /></template>
<style>
.grrjwbjvu {
  fill: var(--svg-color--fff, #fff);
  d: path("M47.865 35.77L31.976 54.233L16.008 35.947c.19-2.566 1.897-4.581 3.988-4.591l3.548-.018l-.09-16.659a5.083 5.083 0 0 1 5.05-5.104l6.586-.033a5.08 5.08 0 0 1 5.102 5.05l.087 16.655l3.546-.02c2.088-.006 3.815 1.98 4.04 4.542");
}

.gz7p0cufa {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M63.791 56.913a6.877 6.877 0 0 1-6.876 6.882H6.874A6.88 6.88 0 0 1 0 56.913V6.877A6.876 6.876 0 0 1 6.874 0h50.042c3.8 0 6.876 3.08 6.876 6.877v50.036z");
}

</style>
