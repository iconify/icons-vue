<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4dmnlnbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o4dmnlnbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:grid-v" /></template>
