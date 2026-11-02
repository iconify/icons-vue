<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy7i2epek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy7i2epek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:amazon-pay-line" /></template>
