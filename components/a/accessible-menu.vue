<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbt8jib9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:accessible-menu" /></template>
<style>
.dbt8jib9y {
  fill: currentColor;
  d: path("M10.809 5.884q-.501-.501-.501-1.192q0-.69.5-1.191Q11.31 3 12 3t1.191.501t.501 1.191t-.5 1.192q-.502.5-1.192.5t-1.191-.5M9.808 20V9q-1.585-.13-3.021-.342T4 8.116l.23-1q1.799.442 3.726.663T12 8t4.044-.221t3.725-.664l.231 1q-1.35.331-2.786.543T14.192 9v11h-1v-5.154h-2.384V20zm8.883-8.23q-.23-.23-.23-.54q0-.309.23-.539t.54-.23t.54.23q.229.23.229.54t-.23.54t-.54.229t-.539-.23m0 4q-.23-.23-.23-.54q0-.309.23-.539t.54-.23t.54.23q.229.23.229.54t-.23.54t-.54.229t-.539-.23m0 4q-.23-.23-.23-.54q0-.309.23-.539t.54-.23t.54.23q.229.23.229.54t-.23.54t-.54.229t-.539-.23");
}

</style>
