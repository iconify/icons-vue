<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hr7u3_s7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-copy-20-filled" /></template>
<style>
.hr7u3_s7e {
  fill: currentColor;
  d: path("M4 12.5V6.373l6.746 3.558a.5.5 0 0 0 .507 0L18 6.373V12.5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 4 12.5m.015-7.277A2.5 2.5 0 0 1 6.5 3h9a2.5 2.5 0 0 1 2.485 2.223L11 8.92zM13.5 17c.818 0 1.544-.393 2-1h-9A3.5 3.5 0 0 1 3 12.5v-7c-.607.456-1 1.182-1 2v5A4.5 4.5 0 0 0 6.5 17z");
}

</style>
