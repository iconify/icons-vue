<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu908ebyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu908ebyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-z-a" /></template>
