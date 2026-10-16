<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9aiyrfai.css';
import '../../css/t/tubi0bbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i9aiyrfai"/><path class="tubi0bbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alarm-clock-off-20" /></template>
