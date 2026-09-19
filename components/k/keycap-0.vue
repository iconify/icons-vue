<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rl1cpz9vl"/><path class="f_xx2xjft"/><path class="ipw9mv_9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:keycap-0" /></template>
<style>
.f_xx2xjft {
  fill: var(--svg-color--fff, #fff);
  d: path("M57 45.7c0 4.6-3.7 8.3-8.3 8.3H15.3C10.7 54 7 50.3 7 45.7V12.3C7 7.7 10.7 4 15.3 4h33.3c4.6 0 8.3 3.7 8.3 8.3v33.4z");
}

.ipw9mv_9v {
  fill: var(--svg-color--9aa0a5, #9aa0a5);
  d: path("M32 13c3 0 5.3 1.1 7 3.2c2 2.6 3 6.8 3 12.8c0 5.9-1 10.2-3 12.8c-1.7 2.1-4 3.2-7 3.2s-5.4-1.2-7.2-3.5C22.9 39.1 22 35 22 28.9c0-5.9 1-10.1 3-12.7c1.7-2.1 4-3.2 7-3.2m0 5c-.7 0-1.4.2-1.9.7s-1 1.3-1.3 2.5q-.6 2.4-.6 7.8c0 3.7.2 6.2.5 7.6c.4 1.4.8 2.3 1.4 2.7c.6.5 1.2.7 1.9.7s1.4-.2 1.9-.7c.6-.5 1-1.3 1.3-2.5q.6-2.25.6-7.8c0-5.55-.2-6.2-.5-7.6c-.4-1.4-.8-2.3-1.4-2.8c-.6-.4-1.2-.6-1.9-.6");
}

.rl1cpz9vl {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M62 52c0 5.5-4.5 10-10 10H12C6.5 62 2 57.5 2 52V12C2 6.5 6.5 2 12 2h40c5.5 0 10 4.5 10 10z");
}

</style>
