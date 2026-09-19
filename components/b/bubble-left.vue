<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umb5xvgbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="umb5xvgbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bubble-left" /></template>
