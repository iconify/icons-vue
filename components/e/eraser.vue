<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvly8mb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nvly8mb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:eraser" /></template>
