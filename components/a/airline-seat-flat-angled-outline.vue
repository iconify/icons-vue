<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrsvf3byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-flat-angled-outline" /></template>
<style>
.wrsvf3byo {
  fill: currentColor;
  d: path("M9.704 12.09L11.41 7.4l7.45 2.71q1.172.42 1.708 1.543q.537 1.122.097 2.293l-.699 1.883zm2.311-3.423q-.2.5-.343.957t-.338.937l-.344.925zm-8.892 3.964l.348-.933l15.896 5.792l-.348.933zm2.163-2.389q-.615-.615-.615-1.48q0-.866.616-1.481q.615-.616 1.48-.616q.866 0 1.481.616q.616.615.616 1.48q0 .866-.616 1.481q-.615.616-1.48.616q-.866 0-1.481-.616m2.26-.699q.317-.315.317-.78t-.315-.781t-.78-.317t-.781.315q-.317.315-.317.78t.315.781t.78.317t.781-.315m3.444 1.944l8.392 3.061l.339-.95q.267-.8-.08-1.54t-1.137-1.016l-6.49-2.375zm-4.204-2.7");
}

</style>
