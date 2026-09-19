<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phqf06_-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phqf06_-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dashboard-square-01" /></template>
