<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic74sqb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ic74sqb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:filter-filled" /></template>
