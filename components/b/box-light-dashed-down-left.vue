<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1jw05y-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="f1jw05y-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-dashed-down-left" /></template>
