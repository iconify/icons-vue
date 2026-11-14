<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbzstjbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-walker" /></template>
<style>
.kbzstjbbm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.642 13.93q.108.272.108.569q.002 1.285-2.036 2.109q.536.678.536 1.892q0 2.75-2.75 2.75t-2.75-2.75q0-.474.082-.866q-1.332.117-2.832.117t-2.832-.117q.082.392.082.866q0 2.75-2.75 2.75T3.75 18.5q0-1.214.536-1.892q-2.036-.823-2.036-2.107v-.002q0-.295.108-.566l1.893-8.522Q4.357 2.25 12 2.25t7.749 3.161zM5.33 7.473l-1.098 4.942q.53-.219 1.202-.406q2.735-.76 6.566-.76t6.566.76q.672.187 1.202.406L18.67 7.473Q16.857 8.75 12 8.75T5.33 7.473");
}

</style>
