<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":324.571,"height":324.571,"left":-20.286,"top":-20.286};
const content = `<path class="ichhtzory"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-hurl" /></template>
<style>
.ichhtzory {
  fill: var(--svg-color--ff0288, #ff0288);
  d: path("M40 87h154.047c.004-18.006-.005-32.882-.046-32.999L245.5 102L194 150s.015-13.835.029-31H40Zm197 82H82.953c-.004-18.006.005-32.882.046-32.999L31.5 184L83 232s-.015-13.835-.029-31H237Z");
}

</style>
