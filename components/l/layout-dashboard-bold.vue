<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7233x-8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="z7233x-8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:layout-dashboard-bold" /></template>
