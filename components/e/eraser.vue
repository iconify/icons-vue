<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c01u0fyrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c01u0fyrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:eraser" /></template>
