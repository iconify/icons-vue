<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eijhrxb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:call-park-32-filled" /></template>
<style>
.eijhrxb_t {
  fill: currentColor;
  d: path("m13.658 12.077l-2.146 1.968q.063.223.157.512c.212.65.544 1.5 1.024 2.332s1.05 1.544 1.507 2.053q.204.226.366.392l2.777-.875a4 4 0 0 1 4.288 1.274l1.682 2.042a3.8 3.8 0 0 1-.342 5.191c-2.639 2.46-6.739 3.113-9.608.501a31.8 31.8 0 0 1-6.055-7.53c-1.937-3.33-2.958-6.457-3.492-8.95C3.004 7.2 5.642 4.01 9.074 2.96a3.83 3.83 0 0 1 4.709 2.32l.917 2.447a4 4 0 0 1-1.042 4.351M20 3a1 1 0 0 0-1 1v11a1 1 0 1 0 2 0v-4h3a4 4 0 0 0 0-8zm4 6h-3V5h3a2 2 0 1 1 0 4");
}

</style>
