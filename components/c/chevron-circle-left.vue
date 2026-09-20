<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy1pxvbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oy1pxvbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chevron-circle-left" /></template>
