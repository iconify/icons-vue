<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfto5fbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dfto5fbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:caret-down" /></template>
