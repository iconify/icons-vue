<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="a1n43ac0f"/><path class="p7hel1pul"/><path class="o1e1nvvsn"/><path class="rrxmyxr6q"/><path class="f0hiob98u"/><path class="b-w0hbcyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:balloon" /></template>
<style>
.a1n43ac0f {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M52 22.5c0 11.3-8.8 24.4-19.8 24.4c-10.9 0-19.8-13-19.8-24.4C12.5 11.2 21.3 2 32.2 2C43.2 2 52 11.2 52 22.5");
}

.b-w0hbcyq {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M30.1 50h4.3c1.4 0 1.4-1.9 0-1.9h-4.3c-1.4-.1-1.4 1.9 0 1.9");
}

.f0hiob98u {
  fill: var(--svg-color--b2c1c0, #b2c1c0);
  d: path("M30.8 48h2.9c.9 0 .9-1.3 0-1.3h-2.9c-.9.1-.9 1.3 0 1.3");
}

.o1e1nvvsn {
  fill: var(--svg-color--b2c1c0, #b2c1c0);
  d: path("M33 49.2h-1.5c0 1.8-.4 3.9-1.9 5.2c-2.1 1.8-4.9.7-7.4.6c-3-.1-5.6 1.2-7.7 3.2c-.8.7-1.6 1.7-2.3 2.5c-.8.9.3 1.9 1.1 1c1.5-1.8 2.6-3.1 4.6-4.3c2.6-1.5 5-.7 7.8-.6c3.2.2 6.1-1.4 7-4.7c.2-.7.3-2 .3-2.9");
}

.p7hel1pul {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M31.5 49.1V49zm.1.1c-.1 0-.1-.1 0 0");
}

.rrxmyxr6q {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M31.5 49c0-.1 0 0 0 0");
}

</style>
