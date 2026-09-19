<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="f73679boo"/><path class="dv7_iqb5c"/><g class="jeunsn1yj"><ellipse class="dk7iirbbi"/><ellipse class="f17lvdrxp"/><path class="hs965-b7l"/></g><ellipse class="i538ebcqx"/><path class="jlyfl80hg"/><path class="jb5042ura"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:ice-hockey" /></template>
<style>
.dk7iirbbi {
  cx: 48.7px;
  cy: 57px;
  rx: 13.3px;
  ry: 5px;
}

.dv7_iqb5c {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M56.5 2S42.4 25.3 40.6 27.3l4.6 2.9L62 2z");
}

.f17lvdrxp {
  cx: 48.7px;
  cy: 51.1px;
  rx: 13.3px;
  ry: 5px;
}

.f73679boo {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M23.3 36.9c-5.5-.4-12.1-1.7-18.5-3.2c-1.9-.4-4.1 9.4-2 10.1c12.8 4 26.3 3 31.3 2.2c1.8-.3 3.1-2.4 3.2-2.4l8-13.4l-4.6-2.9c-7.2 8.5-13.8 9.9-17.4 9.6");
}

.hs965-b7l {
  d: path("M35.5 51.1H62V57H35.5z");
}

.i538ebcqx {
  cx: 48.7px;
  cy: 51.1px;
  fill: var(--svg-color--b2c1c0, #b2c1c0);
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 13.3px;
  ry: 5px;
}

.jb5042ura {
  fill: var(--svg-color--b2c1c0, #b2c1c0);
  d: path("m9.2 45.8l1.5.3l2.8-10.6l-1.5-.3zm15 1.2h1.6l3.6-11.3l-1.8.6zm-8.1-.3c.5 0 1 .1 1.5.1l.8-10.6c-.5-.1-1-.1-1.5-.2zm6-10L19.9 47h1.5l2.3-10.2h-.3c-.4-.1-.8-.1-1.3-.1");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.jlyfl80hg {
  fill: var(--svg-color--e8e8e8, #e8e8e8);
  d: path("M9.1 34.6L7.5 45.5c8.5 1.9 16.7 1.7 22.2 1.2l1.8-12c-3.3 1.8-6.2 2.2-8.1 2.1c-4.3-.3-9.3-1.1-14.3-2.2");
}

</style>
