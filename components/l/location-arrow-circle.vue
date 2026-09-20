<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7ic7cc0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g7ic7cc0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:location-arrow-circle" /></template>
