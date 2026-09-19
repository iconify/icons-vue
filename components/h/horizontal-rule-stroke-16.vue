<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5z8pgb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r5z8pgb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:horizontal-rule-stroke-16" /></template>
