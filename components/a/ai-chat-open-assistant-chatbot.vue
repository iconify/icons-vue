<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="tiv4jfbdw"/><path class="nw43s2bqf"/><path class="ajux33b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ai-chat-open-assistant-chatbot" /></template>
<style>
.ajux33b3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.818 32.345c-9.805 5.661-19.91 6.514-22.571 1.905s3.13-12.934 12.935-18.595c5.662-3.27 11.424-4.935 15.795-4.871c3.198.046 5.652 1.018 6.777 2.966c2.66 4.609-3.13 12.934-12.936 18.595M20.43 21.251h7.14M19.314 24h9.372m-6.745 2.749h4.118");
}

.nw43s2bqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.818 15.655c9.805 5.66 15.597 13.986 12.936 18.595s-12.767 3.756-22.572-1.905S3.586 18.36 6.247 13.75c1.064-1.843 3.318-2.812 6.267-2.95c4.427-.208 10.42 1.457 16.304 4.855");
}

.tiv4jfbdw {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.636px;
  ry: 20.5px;
}

</style>
