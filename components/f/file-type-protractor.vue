<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oj_xmybhk"/><path class="ilu1xcc8g"/><path class="xv_nap19a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-protractor" /></template>
<style>
.ilu1xcc8g {
  fill: var(--svg-color--d51c2f, #d51c2f);
  d: path("M23.227 9.243L18.465 9.2l-2.783-2.784l-3.268 2.17l.564.564l-1.324-.012L7.16 16.7H5.4l1.1 1.106l-1.111 1.875L15.7 29.992h.3a14 14 0 0 0 14-13.98z");
}

.oj_xmybhk {
  fill: var(--svg-color--ed163a, #ed163a);
  d: path("M30 16A14 14 0 1 1 16 2a14 14 0 0 1 14 14");
}

.xv_nap19a {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M9.1 17.019a6.9 6.9 0 0 1 13.794 0Zm15.5.318V16.7h2a10.57 10.57 0 0 0-2.88-6.954l-1.491 1.491l-.45-.451L23.272 9.3a10.57 10.57 0 0 0-6.954-2.88v1.991h-.636v-2A10.56 10.56 0 0 0 8.728 9.3l1.491 1.491l-.451.45l-1.491-1.495A10.57 10.57 0 0 0 5.4 16.7h1.992v.636h-2v2.335h21.219v-2.334h-2");
}

</style>
