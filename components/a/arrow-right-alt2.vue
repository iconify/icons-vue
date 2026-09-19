<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j31ltebnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j31ltebnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:arrow-right-alt2" /></template>
