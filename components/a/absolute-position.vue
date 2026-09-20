<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioxvljb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ioxvljb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:absolute-position" /></template>
