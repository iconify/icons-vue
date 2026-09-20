<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c4l8d1bff"/><path class="dltv48bqg"/><path class="xi_gbmvgd"/><path class="xzyiyfbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-template" /></template>
<style>
.c4l8d1bff {
  fill: var(--svg-color--bf8e55, #bf8e55);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.dltv48bqg {
  fill: var(--svg-color--675f58, #675f58);
  d: path("M29.025 14.38H11.974A1.98 1.98 0 0 0 10 16.354v12.675A1.98 1.98 0 0 0 11.974 31h17.051A1.98 1.98 0 0 0 31 29.026V16.354a1.98 1.98 0 0 0-1.975-1.974");
}

.xi_gbmvgd {
  fill: var(--svg-color--ccc, #ccc);
  d: path("M29.925 29.026a.905.905 0 0 1-.9.9H11.974a.905.905 0 0 1-.9-.9V17.62h18.85v11.406Z");
}

.xzyiyfbqd {
  fill: var(--svg-color--ff931e, #ff931e);
  d: path("M14.9 24.446h2.8v2.8h-2.8zm0-4.2h2.8v2.801h-2.8zm4.2 0h2.8v2.801h-2.8zm4.2 0h2.8v2.801h-2.8zm-4.2 4.2h2.8v2.8h-2.8zm4.2 0h2.8v2.8h-2.8z");
}

</style>
