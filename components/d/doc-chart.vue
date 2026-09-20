<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6jtt7b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r6jtt7b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:doc-chart" /></template>
