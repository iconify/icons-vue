<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dk4c2gxug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-document-fill" /></template>
<style>
.dk4c2gxug {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4L19 4C21.2092 4 23 5.7908 23 8L23 15.0346C23 16.139 22.1046 17.0346 21 17.0346C20.6607 17.0346 20.3269 16.9482 20.0304 16.7838C19.103 16.2697 18.0602 16 17 16C15.3952 16 13.8518 16.6173 12.6897 17.7241C11.1556 19.1851 9.1184 20 7 20C5.0708 20 3.2024 19.3238 1.72 18.0891C1.2638 17.7091 1 17.1461 1 16.5523L1 8C1 5.7908 2.7908 4 5 4Z");
}

</style>
