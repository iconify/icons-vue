<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":253};
const content = `<path class="f7_vc5z0v"/><path class="zih85-b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:dreamhost" /></template>
<style>
.f7_vc5z0v {
  fill: var(--svg-color--1f3244, #1f3244);
  d: path("M252.69 189.792c-20.743 11.573-44.823 17.998-70.423 17.474c-75.461-1.519-135.419-62.678-133.94-136.567c.53-25.094 8.032-48.384 20.718-68.196C28.643 25.06 1.03 67.243.027 116.07c-1.493 73.9 58.513 135.053 133.995 136.577c49.838 1.013 94.018-24.254 118.668-62.856");
}

.zih85-b5i {
  fill: var(--svg-color--3e95be, #3e95be);
  d: path("M180.943 191.375c.836.015 1.677.03 2.518.03c19.694 0 39.12-4.877 56.391-14.056c10.178-17.449 16.103-37.701 16.103-59.388C255.955 52.825 203.293 0 138.316 0c-20.485 0-39.739 5.272-56.505 14.506a114.56 114.56 0 0 0-17.236 58.053c-1.285 64.18 50.912 117.495 116.368 118.816");
}

</style>
