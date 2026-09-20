<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ob2_fcj_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-codeowners" /></template>
<style>
.ob2_fcj_l {
  fill: var(--svg-color--57606a, #57606a);
  fill-rule: evenodd;
  d: path("M16.21 4.13a.3.3 0 0 0-.19 0L5.8 7.45a.31.31 0 0 0-.22.29V14c0 6.76 4.07 11.75 10.45 14.16a.25.25 0 0 0 .17 0c6.38-2.41 10.45-7.4 10.45-14.16V7.74a.31.31 0 0 0-.22-.29Zm-.76-1.77a2.16 2.16 0 0 1 1.33 0L27 5.68a2.17 2.17 0 0 1 1.5 2.06V14c0 7.67-4.67 13.26-11.65 15.9a2.24 2.24 0 0 1-1.49 0C8.4 27.23 3.72 21.64 3.72 14V7.74a2.17 2.17 0 0 1 1.5-2.06Zm1.9 13.75A2.47 2.47 0 0 0 18.59 14a2.48 2.48 0 1 0-4.95 0a2.47 2.47 0 0 0 1.24 2.14v3.43a1.24 1.24 0 1 0 2.47 0Z");
}

</style>
