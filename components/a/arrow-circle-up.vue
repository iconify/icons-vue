<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvq5-lbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uvq5-lbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:arrow-circle-up" /></template>
