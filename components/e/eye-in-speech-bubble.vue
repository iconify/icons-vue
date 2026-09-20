<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="s29yqebfn"/><ellipse class="ifiu1ibxk"/><circle class="nzd-ryugh"/><path class="h0fsigbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:eye-in-speech-bubble" /></template>
<style>
.h0fsigbrw {
  fill: var(--svg-color--fff, #fff);
  d: path("M18 7c-4.963 0-9 4.037-9 9s4.037 9 9 9s9-4.037 9-9s-4.037-9-9-9m0 14a5 5 0 1 1 .001-10.001A5 5 0 0 1 18 21");
}

.ifiu1ibxk {
  cx: 18px;
  cy: 16px;
  fill: var(--svg-color--31373d, #31373d);
  rx: 18px;
  ry: 14px;
}

.nzd-ryugh {
  cx: 18px;
  cy: 16px;
  r: 5px;
  fill: var(--svg-color--31373d, #31373d);
}

.s29yqebfn {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M32.769 33.359c-2.739-3.286-3.903-6.569-4.397-8.746a1 1 0 0 0-1.336-.711l-7.112 2.749a1 1 0 0 0-.609.688c-.079.315-.019.665.211.896C25.492 34.216 31.945 35 32 35a1.002 1.002 0 0 0 .769-1.641");
}

</style>
