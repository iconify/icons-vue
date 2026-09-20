<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3lwrccvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s3lwrccvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gps-compass-16" /></template>
