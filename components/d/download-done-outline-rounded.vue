<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcqi0h2vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:download-done-outline-rounded" /></template>
<style>
.gcqi0h2vp {
  fill: currentColor;
  d: path("m9.55 13.766l8.412-8.412q.146-.146.347-.156t.366.156t.166.356t-.166.357l-8.56 8.56q-.242.242-.565.242t-.565-.242l-3.66-3.66q-.146-.146-.153-.347q-.006-.2.159-.366t.357-.165t.356.165zM6.5 19q-.213 0-.357-.143T6 18.5t.143-.357T6.5 18h11q.214 0 .357.143T18 18.5t-.143.357T17.5 19z");
}

</style>
