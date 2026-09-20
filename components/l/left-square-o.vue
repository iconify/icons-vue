<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9t93yomg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d9t93yomg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:left-square-o" /></template>
