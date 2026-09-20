<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tj61801cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-thinkscript" /></template>
<style>
.tj61801cl {
  fill: var(--svg-color--009ddb, #009ddb);
  d: path("m18.543 2l-.653 14.047l4.293-13.534Zm-5.226 6.253L10.33 10.4l6.86 6.3Zm2.66 9.054l-4.527-2.614l-.56 3.594zm-12.18 7.466l2.193 2.894l10.64-9.52zm10.64.14l3.686.514l-.746-6.534zM24.33 30l2.987-2.147l-9.007-9.193Zm2.007-12.693l-6.954.606l6.44 2.94zm1.866-4.76L26.01 9.653l-7.373 7.28Z");
}

</style>
