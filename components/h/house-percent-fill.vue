<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3md5bbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-percent-fill" /></template>
<style>
.c3md5bbwk {
  fill: currentColor;
  d: path("M3 19v-7c0-1.039.578-1.992 1.293-2.707l6-6a2.414 2.414 0 0 1 3.414 0l6 6C20.422 10.008 21 10.961 21 12v7a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3m11.707-5.293a.999.999 0 1 0-1.414-1.414l-4 4a.999.999 0 1 0 1.414 1.414ZM10 12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4.01 4H14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
