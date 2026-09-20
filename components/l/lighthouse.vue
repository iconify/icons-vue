<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yej55m36i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yej55m36i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:lighthouse" /></template>
