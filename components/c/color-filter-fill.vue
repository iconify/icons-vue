<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi4jnnbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gi4jnnbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:color-filter-fill" /></template>
