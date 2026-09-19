<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvntw1cis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jvntw1cis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-line-fill-16" /></template>
