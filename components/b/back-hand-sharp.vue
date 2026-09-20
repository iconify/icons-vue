<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7bqz_bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:back-hand-sharp" /></template>
<style>
.q7bqz_bwk {
  fill: currentColor;
  d: path("M12.8 23q-2.05 0-3.85-.937T6 19.45L1.2 12.4l1.675-1.675L7 13.575V3h2v9h2V1h2v11h2V2h2v10h2V4h2v10.8q0 3.425-2.387 5.813T12.8 23");
}

</style>
