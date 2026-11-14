<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c96ijlg9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cuticle-pusher" /></template>
<style>
.c96ijlg9l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.591 5.813l1.05-1.05q1.077-1.078 2.478-.477l1.979.849q1.097.47 1.322 1.642t-.618 2.016l-1.615 1.616q-1.591 1.591-3.181 0l-.177-.177l-1.138 1.137q.279.523.279 1.161q0 1.036-.733 1.768l-5.303 5.303q-.732.733-1.767.733q-1.036 0-1.768-.733q-.733-.732-.733-1.767q0-1.036.733-1.768l5.303-5.303q.732-.733 1.768-.733q.638 0 1.161.279l1.137-1.137l-.177-.178q-1.591-1.591 0-3.181");
}

</style>
