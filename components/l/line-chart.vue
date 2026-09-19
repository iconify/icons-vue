<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk1nlix-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk1nlix-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:line-chart" /></template>
