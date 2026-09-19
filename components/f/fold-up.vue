<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrav0nbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mrav0nbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:fold-up" /></template>
