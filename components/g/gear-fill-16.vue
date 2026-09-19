<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2-a7hcnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h2-a7hcnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:gear-fill-16" /></template>
