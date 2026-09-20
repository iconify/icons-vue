<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk4fogbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wk4fogbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:cursor" /></template>
