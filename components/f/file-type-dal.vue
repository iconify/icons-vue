<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c-nxjcb-y"/><path class="dxojt0bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-dal" /></template>
<style>
.c-nxjcb-y {
  fill: var(--svg-color--828282, #828282);
  d: path("M23.425 2.937L30 2.94v6.573l-1.951-.029l.021-3.714L18.827 15L11.4 8.656l-8.018 7.421L2 14.727l9.379-8.614l7.439 6.116l7.344-7.362l-2.73.005l-.008-1.935Z");
}

.dxojt0bdc {
  fill: var(--svg-color--828282, #828282);
  d: path("m24.365 11.708l1.911-1.884v19.227h-1.924l.013-17.342ZM9.468 12.7l1.922-1.783l-.016 18.148l-1.906-.016zm3.732-.2l1.908 1.619l-.008 14.939l-1.911-.008zm7.445 3.083l1.908-2.039l.005 15.5h-1.927l.013-13.467Zm-14.903.608l1.924-1.826l.027 14.682H5.748zm11.176-.531l1.914 1.64l.005 11.748H16.91l.008-13.39Z");
}

</style>
