<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk18vfb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uk18vfb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-tree" /></template>
