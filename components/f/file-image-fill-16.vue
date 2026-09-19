<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-bh2obll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m-bh2obll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-image-fill-16" /></template>
