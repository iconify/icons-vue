<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1u6ybcci.css';
import '../../css/u/ufqvjm-rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1u6ybcci"/><path class="ufqvjm-rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-plus" /></template>
