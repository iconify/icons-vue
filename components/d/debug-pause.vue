<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlb28h91q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tlb28h91q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-pause" /></template>
