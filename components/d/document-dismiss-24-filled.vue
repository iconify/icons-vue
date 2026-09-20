<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-1_3icpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-dismiss-24-filled" /></template>
<style>
.z-1_3icpk {
  fill: currentColor;
  d: path("M12 2v6a2 2 0 0 0 2 2h6v10a2 2 0 0 1-2 2h-6.81A6.5 6.5 0 0 0 4 11.498V4a2 2 0 0 1 2-2zm1.5.5V8a.5.5 0 0 0 .5.5h5.5zm-7 9.5a5.5 5.5 0 1 0 0 11a5.5 5.5 0 0 0 0-11m2.478 3.731l-1.77 1.77l1.77 1.769a.5.5 0 1 1-.707.707l-1.77-1.77l-1.769 1.768a.5.5 0 1 1-.707-.708L5.794 17.5l-1.769-1.77a.5.5 0 1 1 .707-.707l1.77 1.769l1.77-1.769a.5.5 0 0 1 .706.707");
}

</style>
