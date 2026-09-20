<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t909meb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:layers-sharp" /></template>
<style>
.t909meb6i {
  fill: currentColor;
  d: path("m12 21.05l-9-7l1.65-1.25L12 18.5l7.35-5.7L21 14.05zM12 16L3 9l9-7l9 7z");
}

</style>
