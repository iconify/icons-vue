<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjmn3dbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-bumper-left-rounded" /></template>
<style>
.cjmn3dbck {
  fill: currentColor;
  d: path("M14.8 15.121q.992 0 1.587-.474q.594-.474.594-1.304q0-.633-.35-.982t-1.012-.486v-.044q.564-.117.848-.482t.285-.945q0-.82-.58-1.16q-.581-.34-1.716-.34h-1.102q-.343 0-.576.232t-.232.576v4.596q0 .343.232.575q.232.233.576.233zm-1.398-3.605V9.683h1.033q.742 0 1.098.207t.356.706q0 .494-.347.713q-.346.218-1.03.212zm0 2.82v-2.07h1.246q.693 0 1.066.262t.373.782q0 .494-.355.76q-.355.267-1.028.267zm-5.423-.047v-4.96q0-.173-.127-.3q-.127-.125-.302-.125t-.301.126t-.126.299v4.979q0 .343.232.575t.576.232h2.575q.182 0 .298-.115t.115-.296t-.115-.298t-.298-.118zM21 6.596v9.116q0 1.356-.977 2.322t-2.35.966H6.327q-1.372 0-2.35-.966T3 15.712V6.596q0-.666.475-1.14t1.14-.475h14.77q.666 0 1.14.474T21 6.596");
}

</style>
