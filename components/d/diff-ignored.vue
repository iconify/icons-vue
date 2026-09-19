<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rktcl5r9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rktcl5r9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:diff-ignored" /></template>
