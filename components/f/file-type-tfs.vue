<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rgwub4b5j"/><path class="ps6j4qq9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-tfs" /></template>
<style>
.ps6j4qq9k {
  fill: var(--svg-color--68217a, #68217a);
  d: path("m15.54 7.42l7.937-2.014l.689 2.715l-7.938 2.013zM5.342 23.331l1.868-7.368l2.716.689l-1.868 7.368zm8.965-6.916l1.99-1.97l6.538 6.603l-1.99 1.97z");
}

.rgwub4b5j {
  fill: var(--svg-color--68217a, #68217a);
  d: path("M10.175 18.342a8.171 8.171 0 1 1 8.171-8.171a8.18 8.18 0 0 1-8.171 8.171m0-11.673a3.5 3.5 0 1 0 3.5 3.5a3.506 3.506 0 0 0-3.5-3.5m17.914 17.354a4.2 4.2 0 1 1-1.231-2.971a4.2 4.2 0 0 1 1.231 2.971M30 6.21a4.2 4.2 0 1 1-1.231-2.971A4.2 4.2 0 0 1 30 6.21M10.416 25.8a4.2 4.2 0 1 1-1.231-2.971a4.2 4.2 0 0 1 1.231 2.971");
}

</style>
