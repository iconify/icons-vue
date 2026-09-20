<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxe1r-fcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xxe1r-fcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:glass" /></template>
