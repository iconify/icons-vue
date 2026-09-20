<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh6h5ybii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zh6h5ybii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chandelier-outline" /></template>
