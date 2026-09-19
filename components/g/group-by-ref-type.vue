<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmk6lwbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tmk6lwbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:group-by-ref-type" /></template>
