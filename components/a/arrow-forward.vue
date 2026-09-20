<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiel0ej8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kiel0ej8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:arrow-forward" /></template>
