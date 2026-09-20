<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo3wz3hzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:grid-dots-24-regular" /></template>
<style>
.yo3wz3hzp {
  fill: currentColor;
  d: path("M12 17.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m7 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m-14 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m7-7a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m7 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m-14 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m7-7a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m7 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m-14 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
