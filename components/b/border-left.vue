<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_9txo34q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_9txo34q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:border-left" /></template>
