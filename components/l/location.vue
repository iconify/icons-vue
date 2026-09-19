<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moujm4bxk.css';
import '../../css/y/yoimegbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moujm4bxk"/><path class="yoimegbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:location" /></template>
