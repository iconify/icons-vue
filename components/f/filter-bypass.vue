<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bepmzn8hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bepmzn8hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:filter-bypass" /></template>
