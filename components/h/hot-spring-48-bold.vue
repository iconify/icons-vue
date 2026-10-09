<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjfbrs2od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zjfbrs2od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-spring-48-bold" /></template>
