<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy9eo2bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fy9eo2bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chart-bar-fill" /></template>
