<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hscoo02qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-diamond-sharp" /></template>
<style>
.hscoo02qk {
  fill: currentColor;
  d: path("m15 19l-6-6H2v-2h7l6-6l7 7z");
}

</style>
