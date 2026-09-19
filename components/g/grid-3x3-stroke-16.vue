<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmbtl7v-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zmbtl7v-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:grid-3x3-stroke-16" /></template>
