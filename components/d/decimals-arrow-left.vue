<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oag5zrlby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oag5zrlby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:decimals-arrow-left" /></template>
