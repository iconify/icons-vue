<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo6fs7bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fo6fs7bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-medical-fill" /></template>
