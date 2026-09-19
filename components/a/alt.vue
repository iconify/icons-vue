<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvh5-3bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tvh5-3bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:alt" /></template>
