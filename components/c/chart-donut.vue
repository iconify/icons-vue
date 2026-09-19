<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydhuy7bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydhuy7bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-donut" /></template>
