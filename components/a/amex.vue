<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wq7q6_suw"/><path class="k6iceov1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amex" /></template>
<style>
.k6iceov1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.803 22.625V11.904l5.366 10.733l5.367-10.717v10.717m-10.733 2.726l10.733 10.733m0-10.733L28.803 36.096M16.757 22.605l4.781-10.701m4.582 10.733l-4.582-10.733m3.049 7.142h-6.24");
}

.wq7q6_suw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4m-19.357-6.404h6.977m-6.977-10.733h6.977m-6.977 5.367h4.549m-4.549-5.367v10.733");
}

</style>
