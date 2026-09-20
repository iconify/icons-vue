<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zep9gyb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zep9gyb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-down-left-square-solid" /></template>
