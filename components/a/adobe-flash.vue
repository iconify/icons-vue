<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6hno2bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k6hno2bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:adobe-flash" /></template>
