<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j37dud1kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j37dud1kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-shape-right-to-line" /></template>
