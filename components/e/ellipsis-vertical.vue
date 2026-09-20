<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sedqzzbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sedqzzbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:ellipsis-vertical" /></template>
