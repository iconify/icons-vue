<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ddu7rypeh"/><path class="tdqtf-56w"/><path class="vtdzd7h6a"/><path class="sg81wkbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-cuba" /></template>
<style>
.ddu7rypeh {
  fill: var(--svg-color--002a8f, #002a8f);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.sg81wkbft {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.495 18.602L9.5 17.149H7.022l-.769-2.362l-.772 2.362H3l2.006 1.454l-.771 2.36l2.015-1.459l2.015 1.459z");
}

.tdqtf-56w {
  fill: var(--svg-color--eee, #eee);
  d: path("M13.846 15H36v-5H6.923zM6.923 26H36v-5H13.846z");
}

.vtdzd7h6a {
  fill: var(--svg-color--cf142b, #cf142b);
  d: path("m13.846 15l-6.923-5l-5.541-4.002A3.97 3.97 0 0 0 0 9v18c0 1.203.542 2.269 1.382 3.002L6.923 26l6.923-5L18 18z");
}

</style>
