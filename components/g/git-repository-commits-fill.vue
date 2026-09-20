<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mui5-zbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mui5-zbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:git-repository-commits-fill" /></template>
