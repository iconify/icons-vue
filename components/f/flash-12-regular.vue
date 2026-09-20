<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="k9bxi4sdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flash-12-regular" /></template>
<style>
.k9bxi4sdw {
  fill: currentColor;
  d: path("M8 1a.5.5 0 0 1 .475.658L7.695 4H9.5a.501.501 0 0 1 .384.82L5.09 10.574a1.184 1.184 0 0 1-2.04-1.111L3.82 7H2.5a.5.5 0 0 1-.478-.644l1.5-5l.029-.076a.5.5 0 0 1 .45-.28zM3.172 6H4.5a.502.502 0 0 1 .478.65l-.973 3.112a.183.183 0 0 0 .317.172L8.432 5H7a.5.5 0 0 1-.474-.658L7.306 2H4.37z");
}

</style>
