<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6-cffb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x6-cffb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:folder-o" /></template>
