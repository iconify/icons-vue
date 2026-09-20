<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tps8dmomj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:directions-alt-outline" /></template>
<style>
.tps8dmomj {
  fill: currentColor;
  d: path("M12 22q-.375 0-.737-.15t-.663-.45l-8-8q-.3-.3-.45-.663T2 12t.15-.737t.45-.663l8-8q.3-.3.663-.45T12 2t.738.15t.662.45l8 8q.3.3.45.663T22 12t-.15.738t-.45.662l-8 8q-.3.3-.663.45T12 22m-4-6l4 4l8-8l-8-8l-8 8zm4 1l5-5l-5-5l-1.4 1.4l2.55 2.6H7v2h6.15l-2.55 2.6zm0-5");
}

</style>
