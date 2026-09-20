<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxh8guhzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxh8guhzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:autodesk-logo-2" /></template>
