<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0w57jeaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j0w57jeaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-shape-down-to-line" /></template>
