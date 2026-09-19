<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw-fed5sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw-fed5sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-android" /></template>
