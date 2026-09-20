<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayau5zbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayau5zbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:amazon-fill" /></template>
