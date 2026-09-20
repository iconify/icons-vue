<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk0r48tcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:headphones-outline-sharp" /></template>
<style>
.qk0r48tcy {
  fill: currentColor;
  d: path("M9 21H3v-9q0-1.875.713-3.512t1.924-2.85t2.85-1.925T12 3t3.513.713t2.85 1.924t1.925 2.85T21 12v9h-6v-8h4v-1q0-2.925-2.037-4.962T12 5T7.038 7.038T5 12v1h4zm-2-6H5v4h2zm10 0v4h2v-4zM7 15H5zm10 0h2z");
}

</style>
