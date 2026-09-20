<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usnmkquea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="usnmkquea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:copy-o" /></template>
