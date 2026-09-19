<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaht5yaep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qaht5yaep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-document-stroke-16" /></template>
