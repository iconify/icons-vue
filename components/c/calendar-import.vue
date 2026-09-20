<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3ywxbc-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="o3ywxbc-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:calendar-import" /></template>
