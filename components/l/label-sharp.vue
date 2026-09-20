<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr5bbb6od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:label-sharp" /></template>
<style>
.rr5bbb6od {
  fill: currentColor;
  d: path("M2 20V4h14l6 8l-6 8z");
}

</style>
