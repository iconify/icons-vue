<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh2x5dbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh2x5dbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar-up" /></template>
