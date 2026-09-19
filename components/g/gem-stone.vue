<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wxzen3dwk"/><path class="l6nwogr9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:gem-stone" /></template>
<style>
.l6nwogr9g {
  fill: var(--svg-color--c28fef, #c28fef);
  d: path("m32 60l12.5-39.9H18.8zM9.5 9.5L2 20.1h16.8L23 4zm45 0L41 4l3.5 16.1H62z");
}

.wxzen3dwk {
  fill: var(--svg-color--9450e0, #9450e0);
  d: path("M41 4H23L2 20.1L32 60l30-39.9z");
}

</style>
