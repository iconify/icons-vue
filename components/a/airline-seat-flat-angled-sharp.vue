<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nllm-tt7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-flat-angled-sharp" /></template>
<style>
.nllm-tt7q {
  fill: currentColor;
  d: path("M19.962 15.829L9.698 12.09l1.708-4.69l10.302 3.739zm-.948 2.594L3.117 12.631l.349-.933l15.896 5.793zm-13.727-8.18q-.616-.616-.616-1.481t.616-1.481t1.48-.616t1.481.616t.616 1.48q0 .866-.616 1.481q-.615.616-1.48.616q-.866 0-1.481-.616");
}

</style>
