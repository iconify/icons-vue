<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxp0sccsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bxp0sccsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:heart-stroke-16" /></template>
