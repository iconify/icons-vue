<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jjexdhimj"/><path class="v4jddr0pn"/><path class="np64kiblk"/><path class="wsg3y7bef"/><path class="ky6ehu_lu"/><path class="mjssosb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-gitlab-opened" /></template>
<style>
.jjexdhimj {
  fill: var(--svg-color--db9b7b, #db9b7b);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21zm0 18.7H6.6V11.8h20.8zm0-14.5h-8.2l1-2.1h7.1z");
}

.ky6ehu_lu {
  fill: var(--svg-color--fca326, #fca326);
  d: path("m16.5 28.2l2.2 1.6l1.3 1c.3.2.8.2 1.1 0l1.3-1l2.2-1.6s-1.9-1.4-4-3c-2.2 1.6-4.1 3-4.1 3");
}

.mjssosb-d {
  fill: var(--svg-color--fc6d26, #fc6d26);
  d: path("M14.2 20.4c-1.1-.9-2.4-1.4-3.8-1.7v.1c-.8 2.2-.1 4.7 1.8 6.1l4.4 3.3s1.9-1.4 4-3z");
}

.np64kiblk {
  fill: var(--svg-color--e24329, #e24329);
  d: path("m30.7 18.8l-2.9-7.5c-.1-.1-.2-.3-.3-.4q-.45-.3-.9 0c-.1.1-.2.2-.3.4l-1.9 5.9h-7.8l-1.9-5.9c0-.2-.1-.3-.3-.4q-.45-.3-.9 0c-.1.1-.2.2-.3.4l-2.9 7.5v.1c-.8 2.2-.1 4.7 1.8 6.1l4.4 3.3l2.2 1.6l1.3 1c.3.2.8.2 1.1 0l1.3-1l2.2-1.6L29 25c1.8-1.5 2.5-4 1.7-6.2");
}

.v4jddr0pn {
  fill: var(--svg-color--db9b7b, #db9b7b);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.wsg3y7bef {
  fill: var(--svg-color--fc6d26, #fc6d26);
  d: path("M30.7 18.8c-1.4.2-2.7.8-3.9 1.7l-6.3 4.7c2.1 1.6 4 3 4 3l4.4-3.3c1.9-1.4 2.6-3.9 1.8-6.1");
}

</style>
