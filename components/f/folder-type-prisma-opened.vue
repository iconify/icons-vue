<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zrkxc2hdf"/><path class="ulurwmbpo"/><path class="yt8kfab7v"/><path class="kkqq97-7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-prisma-opened" /></template>
<style>
.kkqq97-7w {
  fill: var(--svg-color--0c344b, #0c344b);
  fill-rule: evenodd;
  d: path("M28.52 26.12L20 28.67a.36.36 0 0 1-.46-.42l3.05-14.73a.3.3 0 0 1 .35-.22a.31.31 0 0 1 .21.16l5.65 12.09a.43.43 0 0 1-.2.55Zm1.46-.6l-6.54-14a1.06 1.06 0 0 0-1.85-.11L14.5 23a1.08 1.08 0 0 0 0 1.16l3.5 5.42a1.12 1.12 0 0 0 1.25.46L29.3 27a1.1 1.1 0 0 0 .7-1.32a.5.5 0 0 0-.06-.16Z");
}

.ulurwmbpo {
  fill: var(--svg-color--14587f, #14587f);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.yt8kfab7v {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M30.92 25.43a2 2 0 0 0-.11-.3l-6.54-14A2 2 0 0 0 22.61 10h-.13a2 2 0 0 0-1.67.94l-7.09 11.58a2 2 0 0 0 0 2.13l3.47 5.42a2 2 0 0 0 1.71.93a2.2 2.2 0 0 0 .57-.08l10.06-3a2 2 0 0 0 1.39-2.49");
}

.zrkxc2hdf {
  fill: var(--svg-color--14587f, #14587f);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

</style>
