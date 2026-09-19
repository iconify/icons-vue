<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwafkxbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwafkxbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:filter-outline" /></template>
