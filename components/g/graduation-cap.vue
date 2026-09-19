<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mvm20ui-m"/><path class="e0ejh_b8g"/><g class="hxik4rbqd"><path class="b50msybnn"/><ellipse class="jsdftc8dy"/><path class="lxj1b6pld"/></g><path class="zbl-lvlgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:graduation-cap" /></template>
<style>
.b50msybnn {
  d: path("M31.9 24.8c-4.6 2.1-14.6 6.6-15 6.8c-.2.1-.4.3-.4.6V39c0 .8 1 .8 1 0v-6.3c4.5-2 14.2-6.4 14.6-6.6c.6-.3.4-1.5-.2-1.3");
}

.e0ejh_b8g {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M62 25.4L32 38.9L2 25.4l30-13.5z");
}

.hxik4rbqd {
  fill: var(--svg-color--ffce31, #ffce31);
}

.jsdftc8dy {
  cx: 17px;
  cy: 38.9px;
  rx: 1.9px;
  ry: 2.4px;
}

.lxj1b6pld {
  d: path("M17 51.9c1 0 1.9-.5 1.9-1.2V38.9h-3.8v11.8c0 .7.9 1.2 1.9 1.2");
}

.mvm20ui-m {
  fill: var(--svg-color--596066, #596066);
  d: path("M13.1 30.2V37c0 14 37.7 14 37.7 0v-6.8z");
}

.zbl-lvlgv {
  fill: var(--svg-color--594640, #594640);
  d: path("M18.3 39.2c-.1 0-.1.1-.2.1v12.4c.1 0 .1-.1.2-.1zm-.8.3h-.2v12.4h.2zm-.8 0h-.2v12.4h.2zm-.8-.2c-.1 0-.1-.1-.2-.1v12.5c.1 0 .1.1.2.1z");
}

</style>
