<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqc7jrgdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="wqc7jrgdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-right-up" /></template>
