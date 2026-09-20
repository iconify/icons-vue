<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6z_0o_kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-1-sharp" /></template>
<style>
.n6z_0o_kl {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm4-1h12.885V8H6zm14.885-1.884V9.904H22v4.212z");
}

</style>
