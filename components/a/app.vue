<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcq1h3pnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wcq1h3pnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:app" /></template>
