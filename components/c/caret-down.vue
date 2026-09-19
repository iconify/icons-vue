<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_-g7nb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l_-g7nb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:caret-down" /></template>
