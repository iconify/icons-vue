<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqda_vbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqda_vbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codecrafters" /></template>
