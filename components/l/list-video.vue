<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khk_fyb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khk_fyb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-video" /></template>
