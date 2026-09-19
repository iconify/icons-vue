<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syre-1bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="syre-1bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:caret-down-fill" /></template>
