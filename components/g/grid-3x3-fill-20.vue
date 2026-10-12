<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlvd9ykgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mlvd9ykgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:grid-3x3-fill-20" /></template>
