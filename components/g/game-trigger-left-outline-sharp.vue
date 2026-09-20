<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flg5l4bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-trigger-left-outline-sharp" /></template>
<style>
.flg5l4bto {
  fill: currentColor;
  d: path("M7.804 15.116h3.802v-.827H8.659V8.904h-.855zm6.565 0h.856V9.73h1.933v-.827h-4.74v.827h1.951zM3 19V8.27q0-1.357.977-2.323t2.35-.966h11.346q1.373 0 2.35.966T21 8.269V19zm1-1h16V8.27q0-.96-.683-1.625q-.684-.664-1.644-.664H6.327q-.96 0-1.643.664Q4 7.31 4 8.27zm0 0h16z");
}

</style>
