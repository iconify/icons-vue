<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":325};
const content = `<path class="v7y800ckx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:haxl" /></template>
<style>
.v7y800ckx {
  fill: var(--svg-color--4e69a2, #4e69a2);
  d: path("m149.334 0l-29.867 59.734l25.6 51.2L200.533 0zM204.8 25.6L153.6 128l25.6 51.2L256 25.6zm-187.733 0l17.066 34.134H51.2l119.467 238.933h68.267l-17.067-34.134H204.8L85.333 25.6zM0 298.667h51.2l51.2-102.4l-25.6-51.2zm55.466 25.6h51.2l29.866-59.734l-25.6-51.2z");
}

</style>
