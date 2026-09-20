<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9jh66brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-frame-question-sharp" /></template>
<style>
.n9jh66brl {
  fill: currentColor;
  d: path("M2 17V7h13.66q-.212.227-.385.467T14.967 8H3v8h13.55q.023.279.123.532q.1.252.254.468zm16.97-.855q-.181-.181-.181-.453q0-.27.181-.462q.182-.191.453-.191t.453.19t.182.463t-.182.453t-.453.182t-.453-.182m.022-2.478q0-.342.051-.627q.051-.286.182-.578q.175-.331.405-.584t.504-.509q.339-.313.618-.708t.279-.878q0-.596-.455-.973T19.5 8.433q-.558 0-1.003.306q-.445.305-.672.805l-.775-.333q.308-.746.971-1.18q.663-.435 1.479-.435q.985 0 1.682.62t.697 1.555q0 .633-.307 1.113q-.306.481-.731.906q-.212.212-.411.427q-.2.216-.369.483q-.194.33-.22.967zm-14.608.949V9.385h10.583v5.23z");
}

</style>
