<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk7_07bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dk7_07bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:creative-commons-noncommercial-us" /></template>
