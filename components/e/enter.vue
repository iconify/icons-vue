<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmfjyov2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pmfjyov2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:enter" /></template>
