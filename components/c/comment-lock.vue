<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjfc4ybxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:comment-lock" /></template>
<style>
.hjfc4ybxs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.744 20.886q-4.367 1.853-8.36-.573l-3.178.908q-.071.02-.145.026q-.073.007-.147-.002q-.073-.008-.143-.031q-.071-.023-.135-.058t-.121-.084q-.056-.048-.102-.106t-.08-.123t-.054-.137q-.059-.206 0-.412l.908-3.178q-2.426-3.993-.573-8.36q1.922-4.527 6.75-5.465T18.67 5.83q3.477 3.478 2.539 8.306t-5.465 6.75M11 10.25h2v-.5q0-.414-.293-.707T12 8.75q-1 0-1 1zm-1.5.214q-1.25.518-1.25 2.286v1q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768q-.243-.242-.518-.404V9.75q0-1.036-.732-1.768T12 7.25q-2.5 0-2.5 2.5z");
}

</style>
