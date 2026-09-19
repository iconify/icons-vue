<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voyl-4j-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="voyl-4j-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-start" /></template>
