<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf3_fw_kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tf3_fw_kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:3d-curve-auto-colon" /></template>
