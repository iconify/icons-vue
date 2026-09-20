<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyo7sjmmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:30fps-select-outline-sharp" /></template>
<style>
.kyo7sjmmx {
  fill: currentColor;
  d: path("M4 14v-2h5v-2H4V8h5V6H4V4h7v10zm9 0V4h7v10zm2-2h3V6h-3zM3 22v-5h2v5zm4 0v-5h2v5zm4 0v-5h2v5zm4 0v-5h6v5z");
}

</style>
