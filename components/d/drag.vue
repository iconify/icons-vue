<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih91fyb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ih91fyb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:drag" /></template>
