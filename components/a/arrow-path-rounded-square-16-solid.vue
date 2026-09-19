<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehk72fbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ehk72fbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-path-rounded-square-16-solid" /></template>
