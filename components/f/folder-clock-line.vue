<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwe_sbcat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwe_sbcat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-clock-line" /></template>
