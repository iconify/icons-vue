<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x4s36bcsh"/><path class="wwxpzmbsb"/><path class="mk6l-48ub"/><path class="qevk-zbmu"/><path class="z8tia2-jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-uzbekistan" /></template>
<style>
.mk6l-48ub {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M0 13h36v1.5H0zm0 8.5h36V23H0z");
}

.qevk-zbmu {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 18v3.5h36v-7H0z");
}

.wwxpzmbsb {
  fill: var(--svg-color--1eb53a, #1eb53a);
  d: path("M36 27v-4H0v4a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4");
}

.x4s36bcsh {
  fill: var(--svg-color--0099b5, #0099b5);
  d: path("M0 9v4h36V9a4 4 0 0 0-4-4H4a4 4 0 0 0-4 4");
}

.z8tia2-jq {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.2 9.16a3.12 3.12 0 0 1 2.6-3.076a3.12 3.12 0 1 0 0 6.152A3.12 3.12 0 0 1 4.2 9.16m4.683 2.303l-.14-.431l-.14.431h-.454l.367.267l-.14.431l.367-.267l.366.267l-.14-.431l.367-.267zm2.702 0l-.14-.431l-.14.431h-.453l.367.267l-.14.431l.366-.267l.367.267l-.14-.431l.367-.267zm-.14-2.927l-.14.431h-.453l.367.267l-.14.431l.366-.267l.367.267l-.14-.431l.367-.267h-.454zm2.843 2.927l-.14-.431l-.14.431h-.453l.366.267l-.14.431l.367-.267l.367.267l-.14-.431l.366-.267zm-.14-2.927l-.14.431h-.453l.366.267l-.14.431l.367-.267l.367.267l-.14-.431l.366-.267h-.453zm0-2.496l-.14.431h-.453l.366.267l-.14.431l.367-.267l.367.267l-.14-.431l.366-.267h-.453zm2.843 5.423l-.14-.431l-.14.431h-.454l.367.267l-.14.431l.367-.267l.366.267l-.14-.431l.367-.267zm-.14-2.927l-.14.431h-.454l.367.267l-.14.431l.367-.267l.366.267l-.14-.431l.367-.267h-.453zm0-2.496l-.14.431h-.454l.367.267l-.14.431l.367-.267l.366.267l-.14-.431l.367-.267h-.453zm2.842 5.423l-.14-.431l-.14.431h-.453l.367.267l-.14.431l.366-.267l.367.267l-.14-.431l.367-.267zm-.14-2.927l-.14.431h-.453l.367.267l-.14.431l.366-.267l.367.267l-.14-.431l.367-.267h-.454zm0-2.496l-.14.431h-.453l.367.267l-.14.431l.366-.267l.367.267l-.14-.431l.367-.267h-.454z");
}

</style>
