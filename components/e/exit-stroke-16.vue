<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm5tpccqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fm5tpccqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:exit-stroke-16" /></template>
