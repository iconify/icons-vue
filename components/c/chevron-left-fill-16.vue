<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxrevhb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uxrevhb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-left-fill-16" /></template>
