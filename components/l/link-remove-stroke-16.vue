<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9n7qsxsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x9n7qsxsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:link-remove-stroke-16" /></template>
