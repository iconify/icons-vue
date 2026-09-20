<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zl_mtn6es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-aikido" /></template>
<style>
.zl_mtn6es {
  fill: var(--svg-color--6551f3, #6551f3);
  d: path("M28.44 2H3.56v8.8h24.88zM3.56 19.04a18.5 18.5 0 0 1 24.88 0V30L16 17.38L3.56 30z");
}

</style>
