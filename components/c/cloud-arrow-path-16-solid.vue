<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2oi3ccis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e2oi3ccis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-arrow-path-16-solid" /></template>
