<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr-knn1jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mr-knn1jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ai-science-robot-solid" /></template>
