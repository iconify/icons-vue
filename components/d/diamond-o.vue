<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9rat2byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g9rat2byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:diamond-o" /></template>
