<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm60zmbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vm60zmbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:close-circle" /></template>
