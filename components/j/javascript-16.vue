<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyvjpm-mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gyvjpm-mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:javascript-16" /></template>
