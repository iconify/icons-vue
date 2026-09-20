<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hylu2byvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hylu2byvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:list-filter-plus" /></template>
