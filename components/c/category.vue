<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge99-vb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="ge99-vb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:category" /></template>
