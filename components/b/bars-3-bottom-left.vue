<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojwy94mst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojwy94mst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:bars-3-bottom-left" /></template>
