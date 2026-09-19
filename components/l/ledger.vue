<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="z_bmm-b8z"/><path class="bwzqphbzj"/><path class="ef-tdf7kk"/><path class="ycxief4ba"/><path class="o-9xs_b3u"/><path class="lfdsddbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:ledger" /></template>
<style>
.bwzqphbzj {
  fill: var(--svg-color--e9f3fa, #e9f3fa);
  d: path("M41.4 2.8L29.8 60.3l27.6-8.7c3.1-1 4.8-4.2 3.8-7.2L48.8 6.5c-1-3-4.3-4.6-7.4-3.7");
}

.ef-tdf7kk {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("m39.5 2.4l-26.2 9.4l-4.1 1.5c-3 1.1-3.1 2.8-2 5.8L22 59.2c1.1 3 1.9 3.4 5 2.3l4.1-1.5l26.2-9.4c3-1.1 4.6-4.4 3.5-7.4L47 5.7c-1.1-2.9-4.4-4.4-7.5-3.3");
}

.lfdsddbry {
  fill: var(--svg-color--7d8b91, #7d8b91);
  d: path("M12.7 19.4c-1.6-3.9-12-.4-10.6 3.7c.9 2.6 3.9 2.7 7.1 1.7l-.6-1.7s-3.7 1.2-4.3-.5c-.6-1.8 6.3-3.5 6.8-2.5c.5.9 2.2.5 1.6-.7m4.5 11.9c-1.6-3.9-12-.4-10.6 3.7c.9 2.6 3.9 2.7 7 1.6l-.6-1.7s-3.7 1.2-4.3-.5C8 32.6 15 30.9 15.5 32c.5 1 2.2.6 1.7-.7m4.1 11c-1.6-3.9-12-.4-10.6 3.7c.9 2.6 3.9 2.7 7 1.7L17 46s-3.6 1.2-4.2-.5c-.6-1.8 6.3-3.5 6.8-2.5s2.2.6 1.7-.7m4.1 11.4c-1.6-3.9-12-.4-10.6 3.7c.9 2.6 3.9 2.7 7 1.7l-.6-1.7s-3.7 1.2-4.3-.5c-.6-1.8 6.3-3.5 6.8-2.5s2.2.6 1.7-.7");
}

.o-9xs_b3u {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M25.3 56.1c1.1-.4 1.7-1.6 1.3-2.8c-.4-1.1-1.7-1.7-2.8-1.3s-1.7 1.6-1.3 2.8s1.6 1.7 2.8 1.3m-4.2-11.4c1.1-.4 1.7-1.6 1.3-2.7s-1.7-1.7-2.8-1.3s-1.7 1.6-1.3 2.7c.4 1.2 1.7 1.8 2.8 1.3m-4.1-11c1.1-.4 1.7-1.6 1.3-2.7s-1.7-1.7-2.8-1.3s-1.7 1.6-1.3 2.7c.4 1.2 1.7 1.7 2.8 1.3m-4.4-12c1.1-.4 1.7-1.6 1.3-2.8c-.4-1.1-1.7-1.7-2.8-1.3s-1.7 1.6-1.3 2.7c.4 1.2 1.7 1.8 2.8 1.4");
}

.ycxief4ba {
  fill: var(--svg-color--fff, #fff);
  d: path("m40.1 22.9l-16.2 5.8l-2.4-6.3l16.3-5.8z");
}

.z_bmm-b8z {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M43.7 3.4L29.8 60.3l27.9-7.5c3.1-.9 5-4 4.1-7.1L50.9 7.4c-.9-3.1-4.1-4.8-7.2-4");
}

</style>
