<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hux62626x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hux62626x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:lidquid-drop-waves-2-line" /></template>
