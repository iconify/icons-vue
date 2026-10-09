<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxllr2mpy.css';
import '../../css/m/m60w9bg_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qxllr2mpy"/><path class="m60w9bg_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bearing-20-bold" /></template>
