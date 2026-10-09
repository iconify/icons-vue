<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4vli7ncu.css';
import '../../css/y/yrudknc6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4vli7ncu"/><path class="yrudknc6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crosshair-48-bold" /></template>
