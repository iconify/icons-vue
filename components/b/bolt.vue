<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c624pzuja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c624pzuja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:bolt" /></template>
