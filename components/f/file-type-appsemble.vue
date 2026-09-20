<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eapltw7xn"/><path class="uhk-qqbzw"/><path class="h6z9iabyb"/><path class="fcvh4q7kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-appsemble" /></template>
<style>
.eapltw7xn {
  fill: var(--svg-color--a6cfff, #a6cfff);
  d: path("M8 3h1.607a5 5 0 0 1 5 5v6.607H3V8a5 5 0 0 1 5-5");
}

.fcvh4q7kh {
  fill: var(--svg-color--4a90e2, #4a90e2);
  d: path("M24 29h-6.607V17.393H24a5 5 0 0 1 5 5V24a5 5 0 0 1-5 5");
}

.h6z9iabyb {
  fill: var(--svg-color--a6cfff, #a6cfff);
  d: path("M14.607 29H3V17.393h11.607z");
}

.uhk-qqbzw {
  fill: var(--svg-color--4a90e2, #4a90e2);
  d: path("M22.393 3H29v11.607h-6.607a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5");
}

</style>
