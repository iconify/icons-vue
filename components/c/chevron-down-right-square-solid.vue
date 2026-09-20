<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa7ifjzpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa7ifjzpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-down-right-square-solid" /></template>
