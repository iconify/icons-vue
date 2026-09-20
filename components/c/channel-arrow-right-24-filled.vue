<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxntfv1_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-arrow-right-24-filled" /></template>
<style>
.lxntfv1_g {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m.25-9A3.25 3.25 0 0 1 21 6.25v5.774A6.47 6.47 0 0 0 17.5 11a6.48 6.48 0 0 0-4.691 2.003H8.748l-.102.007a.75.75 0 0 0 0 1.486l.102.007h2.984A6.5 6.5 0 0 0 11 17.5c0 1.29.377 2.49 1.024 3.5H6.25A3.25 3.25 0 0 1 3 17.75V9.372q.354.126.75.128a2.25 2.25 0 1 0-.526-4.438A3.25 3.25 0 0 1 6.25 3zm.604 11.647a.5.5 0 1 0-.707.707L19.293 17H14.5a.5.5 0 0 0 0 1h4.793l-1.646 1.646a.5.5 0 1 0 .707.707l2.5-2.5a.5.5 0 0 0 0-.707zM8.646 9.503a.75.75 0 0 0 0 1.486l.102.007h6.504l.102-.007a.75.75 0 0 0-.102-1.493H8.748zM3.75 6a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
