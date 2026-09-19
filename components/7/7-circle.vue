<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9x-l-zkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u9x-l-zkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:7-circle" /></template>
