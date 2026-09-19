<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by8k92bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="by8k92bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:circle-medium" /></template>
