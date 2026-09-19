<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj84kyuko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj84kyuko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-left-stroke-square-filled" /></template>
