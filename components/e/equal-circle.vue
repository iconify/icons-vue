<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx-4nmbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx-4nmbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:equal-circle" /></template>
