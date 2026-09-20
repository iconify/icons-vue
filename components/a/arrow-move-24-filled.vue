<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zma04fbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-move-24-filled" /></template>
<style>
.zma04fbrt {
  fill: currentColor;
  d: path("M15.457 6.457a1 1 0 0 1-1.414 0L13 5.414V8.25a1 1 0 1 1-2 0V5.414L9.957 6.457a1 1 0 0 1-1.414-1.414l2.75-2.75a1 1 0 0 1 1.414 0l2.75 2.75a1 1 0 0 1 0 1.414m-9 7.586a1 1 0 1 1-1.414 1.414l-2.75-2.75a1 1 0 0 1 0-1.414l2.75-2.75a1 1 0 0 1 1.414 1.414L5.414 11H8.25a1 1 0 1 1 0 2H5.414zm12.5 1.414a1 1 0 0 1-1.414-1.414L18.586 13H15.75a1 1 0 1 1 0-2h2.836l-1.043-1.043a1 1 0 0 1 1.414-1.414l2.75 2.75a1 1 0 0 1 0 1.414zM11 18.586V15.75a1 1 0 1 1 2 0v2.836l1.043-1.043a1 1 0 0 1 1.414 1.414l-2.75 2.75a1 1 0 0 1-1.414 0l-2.75-2.75a1 1 0 1 1 1.414-1.414z");
}

</style>
