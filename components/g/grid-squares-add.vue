<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpmoyebsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="lpmoyebsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:grid-squares-add" /></template>
