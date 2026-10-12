<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq3mh2agg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eq3mh2agg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:grid-2x2-fill-20" /></template>
