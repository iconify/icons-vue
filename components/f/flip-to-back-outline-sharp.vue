<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve2q_bbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flip-to-back-outline-sharp" /></template>
<style>
.ve2q_bbad {
  fill: currentColor;
  d: path("M3 21V7h2v12h12v2zm4-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2zm4 12v-2h2v2zm0-12V3h2v2zm4 0V3h2v2zm0 12v-2h2v2zm4-12V3h2v2zm0 12v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2z");
}

</style>
