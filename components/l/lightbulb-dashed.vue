<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x58p07ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x58p07ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:lightbulb-dashed" /></template>
