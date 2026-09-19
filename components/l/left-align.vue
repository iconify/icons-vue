<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywr37pcaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="ywr37pcaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:left-align" /></template>
