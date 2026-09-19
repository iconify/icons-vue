<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0pbf3b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c0pbf3b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:filter-shelving-lo" /></template>
