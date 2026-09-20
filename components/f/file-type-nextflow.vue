<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="knrtcpkoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-nextflow" /></template>
<style>
.knrtcpkoo {
  fill: var(--svg-color--0dc09d, #0dc09d);
  d: path("M2 7.16c4.418.294 7.959 3.844 8.236 8.267h5.16C15.11 8.15 9.272 2.302 2 2zm8.266 9.443C9.972 21.022 6.423 24.562 2 24.84V30c7.276-.287 13.124-6.125 13.427-13.397zm11.468-1.207c.294-4.419 3.843-7.96 8.266-8.237v-5.16c-7.276.287-13.124 6.124-13.427 13.396zM30 24.84c-4.418-.294-7.959-3.843-8.236-8.267h-5.16C16.89 23.85 22.728 29.698 30 30z");
}

</style>
