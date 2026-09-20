<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="izjs16bix"/><path class="j6_15bbxq"/><path class="hqfp4258u"/><path class="ojxgj-2fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:keycap-1" /></template>
<style>
.hqfp4258u {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M68.96 97.86h-8.9c-.66-.01-1.19-.54-1.2-1.2v-52.4c.04-.66-.47-1.23-1.13-1.27c-.16-.01-.32.01-.47.07l-13.6 4.6c-.62.22-1.31-.1-1.53-.73c-.05-.15-.08-.31-.07-.47v-7c0-.52.32-1 .8-1.2l25.8-9.5c.12-.08.26-.11.4-.1c.66.01 1.19.54 1.2 1.2v66.5c.07.76-.49 1.43-1.25 1.5z");
}

.izjs16bix {
  fill: var(--svg-color--427687, #427687);
  d: path("M116.46 3.96h-104c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8v-104c0-4.42-3.58-8-8-8");
}

.j6_15bbxq {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M122.16 6.26a8.4 8.4 0 0 0-5.7-2.3h-104c-4.42 0-8 3.58-8 8v104c.02 2.12.84 4.16 2.3 5.7l16.8-16.8h76a5.91 5.91 0 0 0 5.9-5.9v-76z");
}

.ojxgj-2fp {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M40.16 12.86c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
