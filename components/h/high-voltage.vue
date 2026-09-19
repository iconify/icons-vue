<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nkay9-vhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:high-voltage" /></template>
<style>
.nkay9-vhx {
  fill: currentColor;
  d: path("m45 2l-9.396 2.48L29.298 2L19 36.354h10.865L20.352 62L43.65 27.648H29.626z");
}

</style>
