<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzux7hjuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzux7hjuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chart-pie" /></template>
