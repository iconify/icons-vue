<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h98hombod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h98hombod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:corner-upper-left" /></template>
