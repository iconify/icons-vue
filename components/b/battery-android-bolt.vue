<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk8_hid9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-bolt" /></template>
<style>
.gk8_hid9n {
  fill: currentColor;
  d: path("M4 18q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h14.05l-7.2 9H16l-.55 3zm13.675-1l.7-4H15l4.8-6h.525l-.7 4H23l-4.8 6z");
}

</style>
