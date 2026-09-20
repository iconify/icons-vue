<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak5-6423p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:highlight-mouse-cursor-outline" /></template>
<style>
.ak5-6423p {
  fill: currentColor;
  d: path("M12.9 21.95q-.225.05-.45.05H12q-2.075 0-3.9-.787t-3.175-2.138T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12v.45q0 .225-.05.45L20 12.3V12q0-3.35-2.325-5.675T12 4T6.325 6.325T4 12t2.325 5.675T12 20h.3zm7.625.55l-4.275-4.275L15 22l-3-10l10 3l-3.775 1.25l4.275 4.275z");
}

</style>
