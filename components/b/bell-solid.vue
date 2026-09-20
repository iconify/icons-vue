<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8r3v9d3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v8r3v9d3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:bell-solid" /></template>
