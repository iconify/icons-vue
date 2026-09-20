<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf4k8s7-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf4k8s7-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-outline" /></template>
