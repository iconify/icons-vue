<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxz4cubom.css';
import '../../css/i/iv8yz13mj.css';
import '../../css/l/lv8uq9bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mxz4cubom"/><path class="iv8yz13mj"/><path class="lv8uq9bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chicken-leg-20-bold" /></template>
