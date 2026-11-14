<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-tf6zbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ar-camera" /></template>
<style>
.h-tf6zbcq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.625 1.75h-3.25q-2.123 0-3.624 1.501T5.25 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h3.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T13.625 1.75m-.491 6.543l1.5.875q.259.152.459.338q.086.01.167.04t.153.078t.132.111t.103.137q.075.129.095.277t-.018.292q-.014.053-.035.104q.06.266.06.567v1.776q0 1.292-1.116 1.944l-1.5.875q-.265.154-.529.237q-.052.071-.12.128q-.067.057-.146.097t-.165.06q-.086.021-.174.021t-.174-.021q-.086-.02-.165-.06t-.146-.097t-.12-.128q-.264-.083-.529-.237l-1.5-.875Q8.25 14.18 8.25 12.888v-1.776q0-.301.06-.567q-.021-.051-.035-.104q-.038-.144-.018-.292t.095-.277q.044-.075.103-.137q.06-.063.132-.111t.153-.078t.167-.04q.199-.186.459-.338l1.5-.875q1.134-.661 2.268 0");
}

</style>
