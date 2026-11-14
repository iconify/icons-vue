<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m15zk7_fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-hexbin" /></template>
<style>
.m15zk7_fr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.625 3.783q-1.125-.649-2.25 0L3.194 5.042q-1.125.65-1.125 1.949v2.518q0 1.299 1.125 1.949l2.181 1.259q.25.144.501.224q-.057.259-.057.55v2.518q0 1.299 1.125 1.949l2.181 1.259q1.125.649 2.25 0l2.181-1.259q.173-.1.319-.215q.146.115.319.215l2.181 1.259q1.125.649 2.25 0l2.181-1.259q1.125-.65 1.125-1.949v-2.518q0-1.299-1.125-1.949l-2.181-1.259q-.25-.144-.501-.224q.057-.259.057-.55V6.991q0-1.299-1.125-1.949l-2.181-1.259q-1.125-.649-2.25 0l-2.181 1.259q-.173.1-.319.215q-.146-.115-.319-.215z");
}

</style>
