<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xa621_ukv"/><path class="ru3fgc3mv"/><path class="v7ohxfs7h"/><path class="weqwbtb9k"/><path class="td3dl2ied"/><path class="hi-8ox32e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:atm-sign" /></template>
<style>
.hi-8ox32e {
  fill: var(--svg-color--fff, #fff);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4c-1.9 2.3-2.3 5.6-2.6 8.4c-.2 2.2-2.2 14.9 3.5 11.2c.68-.45 1.23-1.07 1.6-1.8c1.2-2.1 1.9-3.5 3.3-5.6c5.3-8.6 18.8-10.5 18.8-13.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ru3fgc3mv {
  fill: var(--svg-color--2262dd, #2262dd);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

.td3dl2ied {
  fill: var(--svg-color--092c56, #092c56);
  d: path("M117.1 36h6.9v56h-6.9z");
}

.v7ohxfs7h {
  fill: var(--svg-color--0a3880, #0a3880);
  d: path("M4 36h120v56H4z");
}

.weqwbtb9k {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M21.09 45.03h8.21l14.26 37.95h-7.9l-3.18-9.06H17.96l-3.18 9.06h-7.9zm9.06 22.31l-3.34-9.54l-1.38-4.56h-.42l-1.38 4.56l-3.39 9.54zm20.42-15.53h-10.6v-6.78h28.36v6.78h-10.6v31.16h-7.15V51.81zm23.48-6.78h9.22l10.07 26.66h.42l10.07-26.66h9.28v37.95h-7.1V64.27l.42-6.31h-.42l-9.65 25.02H90.8l-9.7-25.02h-.42l.42 6.31v18.71h-7.05z");
}

.xa621_ukv {
  fill: var(--svg-color--194fa5, #194fa5);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

</style>
