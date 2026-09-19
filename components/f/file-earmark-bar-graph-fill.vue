<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlci4kb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hlci4kb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-bar-graph-fill" /></template>
