<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka5zrvgwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka5zrvgwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:folder-x" /></template>
