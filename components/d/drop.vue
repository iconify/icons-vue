<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp2dldx1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jp2dldx1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:drop" /></template>
