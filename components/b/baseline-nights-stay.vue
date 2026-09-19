<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z29jdn9nr"/><path class="ws4cat11o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-nights-stay" /></template>
<style>
.ws4cat11o {
  fill: currentColor;
  d: path("M7 16h-.18C6.4 14.84 5.3 14 4 14c-1.66 0-3 1.34-3 3s1.34 3 3 3h3c1.1 0 2-.9 2-2s-.9-2-2-2");
}

.z29jdn9nr {
  fill: currentColor;
  d: path("M11.1 12.08c-2.33-4.51-.5-8.48.53-10.07C6.27 2.2 1.98 6.59 1.98 12c0 .14.02.28.02.42c.62-.27 1.29-.42 2-.42c1.66 0 3.18.83 4.1 2.15A4.01 4.01 0 0 1 11 18c0 1.52-.87 2.83-2.12 3.51c.98.32 2.03.5 3.11.5c3.5 0 6.58-1.8 8.37-4.52c-2.36.23-6.98-.97-9.26-5.41");
}

</style>
