<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p69thbcke"/><path class="r_skykbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chef-hat-bold-duotone" /></template>
<style>
.p69thbcke {
  fill: currentColor;
  d: path("M18.9981 18H5.00146C5.01166 19.3969 5.0832 20.9119 5.58556 21.4142C6.17135 22 7.11415 22 8.99977 22H14.9998C16.8854 22 17.8282 22 18.414 21.4142C18.9163 20.9119 18.9879 19.3969 18.9981 18Z");
}

.r_skykbnr {
  fill: currentColor;
  d: path("M7 5C4.23858 5 2 7.23858 2 10C2 12.0503 3.2341 13.8124 5 14.584V18H19L19 14.584C20.7659 13.8124 22 12.0503 22 10C22 7.23858 19.7614 5 17 5C16.7495 5 16.5033 5.01842 16.2626 5.05399C15.6604 3.27806 13.9794 2 12 2C10.0206 2 8.33961 3.27806 7.73736 5.05399C7.49673 5.01842 7.25052 5 7 5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
