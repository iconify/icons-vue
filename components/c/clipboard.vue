<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iath3excz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="iath3excz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:clipboard" /></template>
