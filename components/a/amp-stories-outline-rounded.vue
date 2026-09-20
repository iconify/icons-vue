<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zswsi5odq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:amp-stories-outline-rounded" /></template>
<style>
.zswsi5odq {
  fill: currentColor;
  d: path("M8.8 19q-.34 0-.57-.232T8 18.192V5.808q0-.343.23-.576T8.8 5h6.4q.34 0 .57.232t.23.576v12.384q0 .344-.23.576T15.2 19zm-4.185-2.5V7.475q0-.194.144-.334T5.116 7t.356.144t.144.356v9.025q0 .194-.144.335q-.144.14-.357.14t-.356-.144t-.144-.356m13.77 0V7.475q0-.194.143-.334q.144-.141.357-.141t.356.144t.144.356v9.025q0 .194-.144.335q-.144.14-.357.14t-.356-.144t-.144-.356M9 18h6V6H9zm0 0V6z");
}

</style>
