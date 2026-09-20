<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfjcm8bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfjcm8bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:infuse" /></template>
