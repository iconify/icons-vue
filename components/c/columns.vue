<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saj1t_9ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saj1t_9ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:columns" /></template>
