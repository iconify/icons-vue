<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n--j2qhfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:language-us-sharp" /></template>
<style>
.n--j2qhfp {
  fill: currentColor;
  d: path("M4 17V7h2v8h3V7h2v10zm9 0v-3h2v1h3v-2h-5V7h7v3h-2V9h-3v2h5v6z");
}

</style>
