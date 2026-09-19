<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9l492b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m9l492b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:duplicate-stroke-16" /></template>
