<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdg70bbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdg70bbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:archive-box-arrow-down" /></template>
