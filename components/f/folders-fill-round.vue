<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju7hpi_7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju7hpi_7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folders-fill-round" /></template>
