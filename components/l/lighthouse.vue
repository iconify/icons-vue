<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-5-jrbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d-5-jrbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:lighthouse" /></template>
