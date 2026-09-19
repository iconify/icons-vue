<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr5s66b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nr5s66b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:archive" /></template>
