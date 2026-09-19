<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d58_ggb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d58_ggb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:align-vertical-space-between" /></template>
