<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ikxz6wndp"/><path class="zlnzzzbbb"/><path class="w5chb3uhh"/><path class="w6qrh9r7j"/><path class="rara0wbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:lipstick" /></template>
<style>
.ikxz6wndp {
  fill: var(--svg-color--ea596e, #ea596e);
  d: path("M16.522.232c2.246 0 4.832 1.375 6.703 3.249C25.098 5.355 27 7.408 27 9.479v17.204l-15.974.031V9.582c-.093-1.506 1.075-9.35 5.496-9.35");
}

.rara0wbxo {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M31 34a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2h20a2 2 0 0 1 2 2z");
}

.w5chb3uhh {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("M22.072 3.455c2.664 2.391 4.277 5.236 2.961 6.699c-1.314 1.463-5.06.991-7.721-1.4s-3.753-5.516-2.439-6.979c1.316-1.463 4.538-.712 7.199 1.68");
}

.w6qrh9r7j {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M30 34a2 2 0 0 1-2 2H10a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2h18a2 2 0 0 1 2 2z");
}

.zlnzzzbbb {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M19 11.378V28c0 1.104.896 0 2 0v2a2 2 0 0 0 2-2V12.333c-1.258-.104-2.65-.262-4-.955");
}

</style>
