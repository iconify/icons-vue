<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuidfv4uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iuidfv4uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:at-fill-16" /></template>
