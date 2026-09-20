<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncanqgbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ncanqgbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:code-markup-16" /></template>
