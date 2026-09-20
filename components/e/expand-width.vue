<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-05zabgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="p-05zabgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:expand-width" /></template>
