<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki-qyyb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ki-qyyb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-step-back" /></template>
