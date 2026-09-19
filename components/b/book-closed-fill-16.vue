<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy45tmhze.css';
import '../../css/g/ga0yskbrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iy45tmhze"/><path class="ga0yskbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-closed-fill-16" /></template>
