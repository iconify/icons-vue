<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyaeqib9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="zyaeqib9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:checkbox-marked" /></template>
