<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g3x47j_-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:inking-tool-16-filled" /></template>
<style>
.g3x47j_-u {
  fill: currentColor;
  d: path("M2.009 1a1 1 0 0 0-1 1v.406A.5.5 0 0 0 1 2.5v1A1.5 1.5 0 0 0 2.5 5h.252l.001.003h10.494L13.248 5h.252A1.5 1.5 0 0 0 15 3.5V2a1 1 0 0 0-1-1zm4.5 12c.01.41.108.858.31 1.227c.215.39.599.768 1.173.775h.016c.574-.007.958-.385 1.172-.775c.203-.369.3-.817.31-1.227zm3.471-1.548l2.76-5.45H3.26l2.757 5.45a1 1 0 0 0 .892.548h2.179a1 1 0 0 0 .892-.548");
}

</style>
