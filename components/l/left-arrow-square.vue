<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8jcx0zgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8jcx0zgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:left-arrow-square" /></template>
