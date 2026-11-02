<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbiobzbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-fill-round" /></template>
<style>
.xbiobzbxd {
  fill: currentColor;
  d: path("M3 16v-5a1 1 0 0 1 0-2h.382l1.724-3.447C5.848 4.069 7.307 3 9 3h6c1.693 0 3.152 1.069 3.894 2.553L20.618 9H21a1 1 0 0 1 0 2v5c0 1.27-.803 2.405-2 2.829V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1H9v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1.171A3 3 0 0 1 3 16m3.789-9.342L5.618 9h12.764l-1.171-2.342l-.002-.004A3 3 0 0 0 14.528 5H9.472a3 3 0 0 0-2.681 1.654ZM8 13a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm8.01 0H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
