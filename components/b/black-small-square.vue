<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u0k87qi1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:black-small-square" /></template>
<style>
.u0k87qi1c {
  fill: var(--svg-color--354a54, #354a54);
  d: path("M42.611 39.31c0 1.2-.972 2.173-2.171 2.173H24.643a2.17 2.17 0 0 1-2.17-2.173V23.515a2.17 2.17 0 0 1 2.17-2.171H40.44c1.199 0 2.171.973 2.171 2.171z");
}

</style>
