<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl-2c38wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl-2c38wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:beanie" /></template>
