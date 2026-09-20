<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa59pkdjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa59pkdjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:info" /></template>
