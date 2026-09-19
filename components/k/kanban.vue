<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxa_n7bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxa_n7bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:kanban" /></template>
