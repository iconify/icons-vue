<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu8uaebku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gu8uaebku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:copy-stroke-16" /></template>
