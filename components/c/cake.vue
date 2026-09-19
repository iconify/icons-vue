<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt96rf38k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mt96rf38k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:cake" /></template>
