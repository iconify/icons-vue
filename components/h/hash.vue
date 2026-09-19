<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7ymf46pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g7ymf46pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hash" /></template>
