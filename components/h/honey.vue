<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm_-lrbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm_-lrbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:honey" /></template>
