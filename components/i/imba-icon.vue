<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":216};
const content = `<path class="n01-mvt8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:imba-icon" /></template>
<style>
.n01-mvt8p {
  fill: var(--svg-color--16cec6, #16cec6);
  d: path("M253.824 83.242C225.73 30.252-25.104-23.893 2.052 11.13C29.208 46.152 149.52 94.21 156.65 95.103c-36.913 11.59-135.436 32.382-114.347 49.896c21.09 17.513 121.262-2.047 121.097-1.735c-27.739 20.903-62.277 84.008-27.576 70.525c54.75-21.273 134.37-99.67 118-130.547");
}

</style>
