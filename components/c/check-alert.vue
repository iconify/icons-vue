<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd5434b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:check-alert" /></template>
<style>
.vd5434b_b {
  fill: currentColor;
  d: path("m9.55 17.308l-4.97-4.97l.714-.713l4.256 4.256l9.156-9.156l.713.714zm5.288 3.146q-1.165-1.162-1.165-2.839q0-1.67 1.165-2.835q1.164-1.165 2.835-1.165t2.836 1.165t1.164 2.835q0 1.677-1.164 2.839q-1.165 1.161-2.836 1.161t-2.835-1.161m2.835-.416q.2 0 .33-.13t.132-.331t-.131-.33t-.331-.131t-.33.13t-.131.331t.13.33t.331.132m-.384-1.847h.769v-3h-.77z");
}

</style>
