<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-91inbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h-91inbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chart-cursor" /></template>
