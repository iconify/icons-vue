<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdntu4bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdntu4bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-no-axes-column-increasing-fill" /></template>
