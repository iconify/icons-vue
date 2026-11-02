<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk2o1b0nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk2o1b0nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:display-line" /></template>
