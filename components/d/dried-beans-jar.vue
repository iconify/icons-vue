<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqrb7fqfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dried-beans-jar" /></template>
<style>
.dqrb7fqfs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 3.25h-9.5q-2.5 0-2.5 2.5v1q0 1.341.72 1.963q-.506.338-.963.794Q2.75 11.265 2.75 13.75v2.5q0 2.485 1.757 4.243Q6.265 22.25 8.75 22.25h6.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-2.5q0-2.485-1.757-4.243q-.515-.514-1.092-.878q.059-.054.117-.111q.732-.732.732-1.768v-1q0-1.036-.732-1.768T16.75 3.25m-7.5 9.5q0-2 2.75-2t2.75 2t-2.75 2t-2.75-2m-.75 2.5q2.75 0 2.75 2t-2.75 2t-2.75-2t2.75-2m4.25 2q0-2 2.75-2t2.75 2t-2.75 2t-2.75-2");
}

</style>
