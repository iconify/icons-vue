<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv95rv00s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dv95rv00s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:grid-solid" /></template>
