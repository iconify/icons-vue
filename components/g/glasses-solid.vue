<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6qzu_1jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6qzu_1jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:glasses-solid" /></template>
