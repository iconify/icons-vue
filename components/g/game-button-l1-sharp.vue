<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9b_-mbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-l1-sharp" /></template>
<style>
.g9b_-mbeq {
  fill: currentColor;
  d: path("M14.742 15.116h.831V8.885h-.65l-1.917 1.396l.456.629l1.28-.918zm-6.188 0h3.802v-.827H9.409V8.904h-.855zM21 4.98v10.73q0 1.357-.977 2.323t-2.35.966H6.327q-1.372 0-2.35-.966T3 15.712V4.98z");
}

</style>
