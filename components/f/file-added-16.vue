<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlwb9e1jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mlwb9e1jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-added-16" /></template>
