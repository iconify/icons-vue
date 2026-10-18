<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l9ocdmb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-nextflow" /></template>
<style>
.l9ocdmb1f {
  fill: var(--svg-color--0dc09d, #0dc09d);
  d: path("M2 7.161c4.418.294 7.959 3.843 8.236 8.266h5.16C15.11 8.151 9.272 2.303 2 2zm8.266 9.443C9.972 21.022 6.423 24.562 2 24.84V30c7.276-.287 13.124-6.124 13.427-13.396zm11.468-1.208c.294-4.418 3.843-7.959 8.266-8.237V2c-7.276.287-13.124 6.125-13.427 13.397zM30 24.84c-4.418-.294-7.959-3.843-8.236-8.266h-5.16C16.89 23.85 22.728 29.698 30 30z");
}

</style>
