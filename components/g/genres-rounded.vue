<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9u0pnptd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:genres-rounded" /></template>
<style>
.e9u0pnptd {
  fill: currentColor;
  d: path("M11.98 16.907q.79-.785.79-1.907V7.846h2.076q.31 0 .54-.221t.23-.548q0-.31-.23-.54t-.54-.23h-2.192q-.31 0-.54.23t-.23.54v5.939q-.388-.316-.85-.512q-.464-.196-.957-.196q-1.122 0-1.907.784q-.786.784-.786 1.904t.784 1.908t1.904.788t1.909-.785M12.003 21q-1.867 0-3.51-.708q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709");
}

</style>
