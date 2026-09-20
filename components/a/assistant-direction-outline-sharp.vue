<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndz4p5nct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:assistant-direction-outline-sharp" /></template>
<style>
.ndz4p5nct {
  fill: currentColor;
  d: path("M12 23q-2.275 0-4.288-.862t-3.5-2.35t-2.35-3.5T1 12q0-2.3.863-4.3t2.35-3.488t3.5-2.35T12 1q2.3 0 4.3.863t3.488 2.35t2.35 3.487T23 12q0 2.275-.862 4.288t-2.35 3.5t-3.488 2.35T12 23m-.05-2.65l8.375-8.375L11.95 3.6l-8.375 8.375zm-3.975-5.375v-5h5.15l-1.05-1.1l1.4-1.4l3.5 3.5l-3.5 3.5l-1.4-1.4l1.05-1.1h-3.15v3zM12 21q3.775 0 6.388-2.613T21 12t-2.613-6.387T12 3T5.613 5.613T3 12t2.613 6.388T12 21");
}

</style>
