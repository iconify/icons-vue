<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej82teboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ej82teboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:check-shape-fill" /></template>
