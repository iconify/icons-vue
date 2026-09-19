<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl9_6mbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tl9_6mbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:flag-stroke-16" /></template>
