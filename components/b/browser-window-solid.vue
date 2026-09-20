<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvl9obcpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zvl9obcpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:browser-window-solid" /></template>
