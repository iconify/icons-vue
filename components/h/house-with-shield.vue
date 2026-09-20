<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl_32lb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:house-with-shield" /></template>
<style>
.rl_32lb9w {
  fill: currentColor;
  d: path("M12 17.366q1.379-.349 2.286-1.588q.906-1.24.906-2.747v-2.044L12 9.385l-3.192 1.6v2.04q0 1.521.907 2.757T12 17.366M5 20V9.5l7-5.27l7 5.27V20z");
}

</style>
