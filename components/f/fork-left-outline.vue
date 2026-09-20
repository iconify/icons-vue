<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbem_vb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fork-left-outline" /></template>
<style>
.fbem_vb1q {
  fill: currentColor;
  d: path("M13.5 20v-3.538q-.488-1.831-1.713-2.728q-1.224-.897-2.67-.897q-.544 0-1.108.056q-.563.057-1.088.145l2.094 2.1l-.707.708L5 12.54l3.308-3.31l.708.708l-2.095 2.1q.514-.089 1.052-.133t1.121-.044q1.37 0 2.498.597q1.13.597 1.908 1.814V5.941l-2.1 2.1l-.708-.714L14 4.019l3.308 3.308l-.708.708l-2.1-2.094V20z");
}

</style>
