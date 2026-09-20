<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bw69o_mhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-prefect" /></template>
<style>
.bw69o_mhg {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("m24.15 6.78l2.06 1.18l.07.04v11.66l-.07.04l-8.13 4.68V21.7l.06-.04l1.07-.61l1.37-.8l3.37-1.93V9.5l-7.66 4.41V30l-2.33-1.43v-16l10.06-5.8l.07-.03zm-4.12-2.37l2.27 1.3l-10.13 5.83v15.92l-2.27-1.4l-.06-.03V10.2L19.9 4.4l.07-.03zm-4.12-2.37l2.27 1.3L8.05 9.17v15.76l-2.33-1.44V7.83l10.06-5.8l.07-.03z");
}

</style>
