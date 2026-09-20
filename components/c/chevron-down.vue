<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l008ygbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l008ygbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:chevron-down" /></template>
