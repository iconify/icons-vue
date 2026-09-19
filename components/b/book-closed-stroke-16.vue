<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4ksah0px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r4ksah0px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-closed-stroke-16" /></template>
