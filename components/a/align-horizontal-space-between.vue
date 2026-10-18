<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1505kbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1505kbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-horizontal-space-between" /></template>
