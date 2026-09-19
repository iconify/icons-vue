<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5wm4bcad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h5wm4bcad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:chrome-minimize" /></template>
