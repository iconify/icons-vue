<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2dotabzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h2dotabzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:head" /></template>
