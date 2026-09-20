<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhhps6bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhhps6bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-no-axes-combined" /></template>
