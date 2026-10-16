<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukajkkbxj.css';
import '../../css/y/yep200xlu.css';
import '../../css/l/lem536b_l.css';
import '../../css/e/ee9mz4bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ukajkkbxj"/><path class="yep200xlu"/><path class="lem536b_l"/><path class="ee9mz4bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fertiliser-20" /></template>
