<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmlk19rpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmlk19rpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cash-plus" /></template>
