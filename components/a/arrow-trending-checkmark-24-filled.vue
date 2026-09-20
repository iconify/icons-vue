<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqyni_fbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-trending-checkmark-24-filled" /></template>
<style>
.oqyni_fbo {
  fill: currentColor;
  d: path("M20 3a1 1 0 0 1 1 1v5a1 1 0 1 1-2 0V6.414l-5.793 5.793a1 1 0 0 1-1.414 0L10 10.414l-5.293 5.293a1 1 0 0 1-1.414-1.414l6-6a1 1 0 0 1 1.414 0l1.793 1.793L17.586 5H15a1 1 0 1 1 0-2zm3 14.5a5.5 5.5 0 1 1-11 0a5.5 5.5 0 0 1 11 0m-2.146-2.354a.5.5 0 0 0-.708 0L16.5 18.793l-1.646-1.647a.5.5 0 0 0-.708.708l2 2a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0 0-.708");
}

</style>
