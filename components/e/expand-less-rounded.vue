<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hthefgdlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:expand-less-rounded" /></template>
<style>
.hthefgdlq {
  fill: currentColor;
  d: path("m12 10.775l-3.9 3.9q-.275.275-.7.275t-.7-.275t-.275-.7t.275-.7l4.6-4.6q.15-.15.325-.213T12 8.4t.375.063t.325.212l4.6 4.6q.275.275.275.7t-.275.7t-.7.275t-.7-.275z");
}

</style>
