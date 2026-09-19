<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy3dr47ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zy3dr47ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:c-header" /></template>
