<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-iaqv3wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y-iaqv3wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:italic-geor-kan" /></template>
