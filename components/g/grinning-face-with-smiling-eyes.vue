<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<ellipse class="k8963ob6u"/><path class="rsfyo4bcw"/><path class="mqas8rbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:grinning-face-with-smiling-eyes" /></template>
<style>
.k8963ob6u {
  cx: 32px;
  cy: 31.964px;
  fill: var(--svg-color--fbbf67, #fbbf67);
  rx: 32px;
  ry: 31.961px;
}

.mqas8rbsf {
  fill: var(--svg-color--fff, #fff);
  d: path("M48.688 41.35c0 4.392-7.553 7.958-16.863 7.958c-9.303 0-16.858-3.566-16.858-7.958");
}

.rsfyo4bcw {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M52.1 39.35c0 10.996-8.932 19.921-19.947 19.921c-11.01 0-19.941-8.925-19.941-19.921m17.181-14.2c-1.371-3.738-4.481-7.317-8.775-7.232c-4 .076-6.419 4.308-7.725 7.512c-.814 2 2.428 2.861 3.234.89c.838-2.057 2.073-4.329 4.339-5.02c2.594-.794 4.968 2.764 5.692 4.739c.737 2.01 3.978 1.144 3.235-.891m5.827-.028c1.371-3.739 4.479-7.316 8.774-7.234c4.01.078 6.417 4.309 7.723 7.512c.817 2-2.428 2.863-3.232.892c-.838-2.059-2.075-4.329-4.338-5.02c-2.597-.792-4.971 2.767-5.693 4.741c-.738 2.01-3.979 1.138-3.234-.892");
}

</style>
