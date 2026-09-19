<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zmi9d3j7m"/><path class="ik_244bja"/><g class="puvn5ac8d"><path class="k2ktl3buz"/><path class="l1q4hfbxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-singapore" /></template>
<style>
.ik_244bja {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 2C15.4 2 2 15.4 2 32h60C62 15.4 48.6 2 32 2");
}

.k2ktl3buz {
  d: path("m21.2 17.5l-1.2-1h1.5L22 15l.5 1.5H24l-1.2 1l.4 1.5l-1.2-.9l-1.2.9zm8 0l-1.2-1h1.5L30 15l.5 1.5H32l-1.2 1l.4 1.5l-1.2-.9l-1.2.9zm-7 5l-1.2-1h1.5L23 20l.5 1.5H25l-1.2 1l.4 1.5l-1.2-.9l-1.2.9zm6 0l-1.2-1h1.5L29 20l.5 1.5H31l-1.2 1l.4 1.5l-1.2-.9l-1.2.9zm-3-8l-1.2-1h1.5L26 12l.5 1.5H28l-1.2 1l.4 1.5l-1.2-.9l-1.2.9z");
}

.l1q4hfbxd {
  d: path("M24.4 28c-4.8 0-8.6-4.1-8.6-9.1s3.9-9.1 8.6-9.1c.4 0 .7 0 1 .1Q23.6 9 21.5 9C16.3 9 12 13.5 12 19s4.3 10 9.5 10c1.6 0 3.2-.4 4.5-1.2c-.5.1-1 .2-1.6.2");
}

.puvn5ac8d {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
}

.zmi9d3j7m {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M32 62c16.6 0 30-13.4 30-30H2c0 16.6 13.4 30 30 30");
}

</style>
