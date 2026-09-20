<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9mswcgcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="a9mswcgcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:download" /></template>
