<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x71cwjbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:algorithm" /></template>
<style>
.x71cwjbpb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 1.75h6.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-2.5v1.617l4.189 3.025q.06.043.11.097t.089.117t.065.132t.037.143t.01.146q-.003.074-.02.146t-.048.139t-.074.127q-.071.098-.169.169l-4.189 3.025v1.617h2.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-6.5q-1.036 0-1.768-.732T6.25 19.75q0-2.5 2.5-2.5h2.5v-1.617l-4.189-3.025q-.121-.087-.199-.214t-.102-.275t.01-.292t.122-.266q.071-.098.169-.169l4.189-3.025V6.75h-2.5q-1.036 0-1.768-.732T6.25 4.25q0-2.5 2.5-2.5M12 9.675L8.781 12L12 14.325L15.219 12z");
}

</style>
