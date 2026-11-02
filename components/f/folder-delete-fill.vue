<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx83m75qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx83m75qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-delete-fill" /></template>
