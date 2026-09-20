<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yqtx0-xlt"/><path class="env37bw9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ghny" /></template>
<style>
.env37bw9v {
  fill: var(--svg-color--ffe1a4, #ffe1a4);
  d: path("M7.986 7.563a1.41 1.41 0 0 1 1.43-1.387h5.162c.794 0 1.434.62 1.434 1.387c0 .768-.635 1.26-1.429 1.26h-2.012c-.317 0-.572.222-.572.53v1.032c0 .307.255.556.572.556h4.876c.794 0 1.435.556 1.435 1.323c0 .768-.64 1.324-1.43 1.324h-3.16c-.318 0-.704.222-.704.53v.375c0 .307.386.683.704.683h.291c.794 0 1.387.556 1.387 1.324c0 .767-.598 1.323-1.392 1.323H9.42c-.794 0-1.392-.556-1.392-1.323c0-.768.598-1.324 1.392-1.324h2.007c.317 0 .571-.37.571-.683v-.376c0-.307-.254-.53-.571-.53H6.546c-.794 0-1.43-.555-1.43-1.323s.642-1.323 1.43-1.323h3.161c.318 0 .704-.249.704-.556V9.352c0-.307-.386-.529-.704-.529h-.291c-.794 0-1.43-.492-1.43-1.26");
}

.ft5dv1b6b {
  fill: none;
}

.yqtx0-xlt {
  fill: var(--svg-color--f2c75c, #f2c75c);
  d: path("M7.774 3.815L3.078 11.98a.62.62 0 0 0 .01.62l4.687 7.6c.106.17.28.27.471.27h7.508c.19 0 .37-.106.47-.265l4.686-7.608a.6.6 0 0 0 .01-.619l-4.695-8.164a.56.56 0 0 0-.482-.286H8.256a.54.54 0 0 0-.477.286z");
}

</style>
