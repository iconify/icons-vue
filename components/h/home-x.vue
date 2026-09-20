<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dltnu8-yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dltnu8-yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:home-x" /></template>
