<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9zly8biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d9zly8biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:arrow-expand-flat" /></template>
