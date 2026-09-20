<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2s_udb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-flat" /></template>
<style>
.o2s_udb8e {
  fill: currentColor;
  d: path("M9.539 13V8h7.923q1.246 0 2.123.877T20.462 11v2zm-6 2.77v-1h16.923v1zm.605-3.376q-.605-.606-.605-1.51q0-.903.605-1.509t1.51-.606t1.51.606t.605 1.51t-.605 1.51t-1.51.605t-1.51-.606");
}

</style>
