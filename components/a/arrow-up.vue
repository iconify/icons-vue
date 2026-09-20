<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6t5c-oxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="o6t5c-oxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:arrow-up" /></template>
