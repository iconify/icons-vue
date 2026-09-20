<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ho4ovebol"/><path class="ro2r52bxw"/><path class="b13a6fbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-taskfile" /></template>
<style>
.b13a6fbul {
  fill: var(--svg-color--94ded7, #94ded7);
  d: path("M16.002 16.256L4.252 9.133l11.75-7.12l11.747 7.12z");
}

.ho4ovebol {
  fill: var(--svg-color--28bdb0, #28bdb0);
  d: path("M16.002 16.256v13.73l-11.75-7.12V9.132z");
}

.ro2r52bxw {
  fill: var(--svg-color--68d1c7, #68d1c7);
  d: path("M16.002 16.256v13.73l11.747-7.12V9.132z");
}

</style>
