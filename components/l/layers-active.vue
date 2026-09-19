<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1cmbabii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m1cmbabii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layers-active" /></template>
