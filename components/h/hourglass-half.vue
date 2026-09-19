<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl2tj90sh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="yl2tj90sh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hourglass-half" /></template>
