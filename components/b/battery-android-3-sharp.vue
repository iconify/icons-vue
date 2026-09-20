<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njj0_t8pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-3-sharp" /></template>
<style>
.njj0_t8pt {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm8-1h8.885V8H10zm10.885-1.884V9.904H22v4.212z");
}

</style>
