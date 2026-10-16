<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t5fnk5o5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-overcommit" /></template>
<style>
.t5fnk5o5i {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("m7.15 4.43l6.72 6.85a2.2 2.2 0 0 0 1.15 2.81v8.03a2.2 2.2 0 1 0 1.81 0v-7.84l3.01 3.02a2.2 2.2 0 1 0 1.29-1.3l-3.14-3.15A2.2 2.2 0 0 0 15.16 10L8.71 3.43l.16-.08c2.04-1.03 3.92-1.45 7.59-1.33s5.51.66 7.49 1.83c1.87 1.1 3.3 2.7 4.24 4.7c1 2.13 1.4 4.08 1.27 7.9s-.65 5.72-1.78 7.78a10.7 10.7 0 0 1-4.54 4.4c-2.05 1.05-3.93 1.47-7.6 1.35c-3.67-.13-5.5-.66-7.49-1.83a10.7 10.7 0 0 1-4.24-4.7c-1-2.14-1.4-4.08-1.27-7.9c.13-3.8.65-5.72 1.78-7.78a11 11 0 0 1 2.83-3.34");
}

</style>
