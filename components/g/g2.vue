<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbjuqgbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbjuqgbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:g2" /></template>
