<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/todwqzgwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="todwqzgwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-shape-right-from-line" /></template>
