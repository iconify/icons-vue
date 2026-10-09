<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrw5zccqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vrw5zccqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-48-bold" /></template>
