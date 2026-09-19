<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ahqxxi3ku"/><path class="wk37zwb8j"/><g class="jeunsn1yj"><path class="t-391i2bj"/><path class="wjj33nbxq"/></g><path class="ckex3695w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:canoe" /></template>
<style>
.ahqxxi3ku {
  fill: var(--svg-color--eda454, #eda454);
  d: path("M6.1 38.9S.6 49.5 2.4 59S25.8 53.7 42 38.9s21.3-22 19.8-36.7c0 0 1.5 17.5-21.6 30.1C17 44.8 7.9 41.4 6.1 38.9");
}

.ckex3695w {
  fill: var(--svg-color--a87d5d, #a87d5d);
  d: path("m27.9 31.2l-13.5-27c.5-.3.7-1.1.4-1.6c-.3-.6-.9-.8-1.4-.4l-1.8 1.2c-.6.3-.7 1-.5 1.6c.3.6.9.8 1.4.4l13.5 27c.7 1.4 2.6 10 4.9 14.6c3.2 6.3 6.9 13.7 6.9 13.7c.6 1.2 1.9 1.6 2.9.9l1.8-1.2c1-.7 1.3-2.2.8-3.3c0 0-3.7-7.4-6.9-13.7c-2.2-4.4-7.8-10.8-8.5-12.2");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.t-391i2bj {
  d: path("M32.4 27.2c-7.5 5.6-14.8 11.1-16.7 12.6c-.1.1-.2.2-.4.3c4.8-.4 12.6-2.4 24.4-8.8c2.4-1.3 4.5-2.7 6.4-4.1zM60.1 5.1c-2.3 2.6-6 6.9-10.3 9.6c-2.5 1.6-7.5 5.1-12.9 9.1h13.2c7.1-6.6 9.4-13.3 10.1-17.4c.1-.7.2-1.3.2-1.9c.1.2-.1.4-.3.6");
}

.wjj33nbxq {
  d: path("M26.1 35.2c.6 1.2 2.2 8.6 4.2 12.6l.3.6c1.5-1.1 3-2.3 4.5-3.5c0-.1-.1-.2-.1-.2c-1.9-3.8-6.8-9.3-7.4-10.5s-1.1-2.4-1.7-3.5c-.5.4-1.1.8-1.6 1.2q.9 1.5 1.8 3.3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wk37zwb8j {
  fill: var(--svg-color--f9b978, #f9b978);
  d: path("M40.2 32.3C56 23.6 60.3 12.7 61.4 6.7c.4-2.5.4-4.2.4-4.5c0-1.5-5.6 7.2-12.4 11.5S18.8 35.9 15.1 38.9s-9 0-9 0c1.8 2.5 10.9 5.9 34.1-6.6");
}

</style>
