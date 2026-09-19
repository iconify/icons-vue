<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epa5hnsth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="epa5hnsth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:git-stash" /></template>
