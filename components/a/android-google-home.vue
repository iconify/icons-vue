<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2gbnobho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:android-google-home" /></template>
<style>
.f2gbnobho {
  fill: currentColor;
  d: path("M4 14.85V11q0-.2.075-.375T4.3 10.3l7-7q.15-.15.325-.225Q11.8 3 12 3t.375.075q.175.075.325.225l1.425 1.4ZM17 20v-8.175L13.075 7.9L15.2 5.775l4.5 4.525q.125.15.213.325Q20 10.8 20 11v8q0 .425-.288.712Q19.425 20 19 20ZM5 20q-.425 0-.713-.288Q4 19.425 4 19v-2.05l3-3V17h8.5v3Z");
}

</style>
