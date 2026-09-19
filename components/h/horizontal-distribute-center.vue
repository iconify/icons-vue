<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwe1t7bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwe1t7bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:horizontal-distribute-center" /></template>
