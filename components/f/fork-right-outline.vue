<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsb0fqbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fork-right-outline" /></template>
<style>
.lsb0fqbtq {
  fill: currentColor;
  d: path("M9.5 20V5.94L7.4 8.036l-.708-.708L10 4.019l3.308 3.308l-.708.713l-2.1-2.1v8.333q.779-1.217 1.908-1.814t2.498-.597q.583 0 1.121.044t1.052.133l-2.095-2.1l.708-.708L19 12.539l-3.308 3.307l-.707-.707l2.094-2.1q-.525-.089-1.089-.146q-.563-.057-1.107-.057q-1.446 0-2.67.898q-1.225.897-1.713 2.728V20z");
}

</style>
