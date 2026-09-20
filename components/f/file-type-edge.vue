<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j8j6upbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-edge" /></template>
<style>
.j8j6upbdl {
  fill: var(--svg-color--d8563a, #d8563a);
  d: path("M333.085 174.674c-.908-15.974-.972-32.987-.369-50.16H170.8c12.03 21.782 10.844 24.8 12.167 62.274v129.4c-.691 48.1-2.93 56.094-12.167 71.3h165.6c.915-19.388 2.523-40.337 4.795-62.7c-13.643 19.912-19.544 30.612-65.278 30.612h-39.465v-83.725h34.3c39.382-.676 45.53 11 53.849 16.966a454 454 0 0 1 0-65.282c-16.255 14.68-26.684 15.844-53.849 16.6h-34.3V156.6H279.6c25.516.3 40.131 4.474 53.485 18.074");
}

</style>
