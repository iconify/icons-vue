<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzcqt3hcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jzcqt3hcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:gluten-outline" /></template>
