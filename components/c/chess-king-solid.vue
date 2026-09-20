<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suzccfoeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="suzccfoeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:chess-king-solid" /></template>
