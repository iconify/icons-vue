<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr8knnbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="zr8knnbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:creative-commons-pd" /></template>
