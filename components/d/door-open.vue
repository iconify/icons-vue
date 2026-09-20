<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxmea9bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-open" /></template>
<style>
.bxmea9bye {
  fill: currentColor;
  d: path("M4.462 20v-1H6V5.116q0-.672.472-1.144T7.616 3.5h8.769q.67 0 1.143.472q.472.472.472 1.144V19h1.539v1zM15 19h2V5.116q0-.27-.173-.443t-.442-.173h-3.539v-.484q.927.103 1.54.794Q15 5.5 15 6.427zm-3.46-6.46q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23");
}

</style>
