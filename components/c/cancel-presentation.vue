<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh90kfb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cancel-presentation" /></template>
<style>
.uh90kfb9k {
  fill: currentColor;
  d: path("m9.4 16l2.6-2.6l2.6 2.6l1.4-1.4l-2.6-2.6L16 9.4L14.6 8L12 10.6L9.4 8L8 9.4l2.6 2.6L8 14.6zM4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20z");
}

</style>
