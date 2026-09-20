<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w527-ac2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-l1-outline-rounded" /></template>
<style>
.w527-ac2q {
  fill: currentColor;
  d: path("M14.742 9.992v4.717q0 .166.12.286t.282.12t.297-.12t.132-.285V9.083q0-.09-.048-.144t-.144-.054h-.402q.008 0-.112.03l-1.56 1.126q-.141.092-.16.246q-.018.154.074.296q.093.142.246.16q.154.019.297-.074zM9.41 14.288v-4.96q0-.172-.125-.298q-.126-.126-.301-.126t-.302.126t-.127.299v4.979q0 .343.232.575t.576.232h2.58q.182 0 .298-.115t.116-.296t-.116-.298t-.298-.118zM21 6.596v9.116q0 1.356-.977 2.322t-2.35.966H6.327q-1.372 0-2.35-.966T3 15.712V6.596q0-.666.475-1.14t1.14-.475h14.77q.666 0 1.14.474T21 6.596m-1.616-.615H4.616q-.27 0-.443.173T4 6.596v9.116q0 .96.684 1.624q.683.664 1.643.664h11.346q.96 0 1.644-.664q.683-.665.683-1.624V6.596q0-.269-.173-.442t-.442-.173m0 0H20H4z");
}

</style>
