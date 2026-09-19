<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxfed015g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="bxfed015g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:arrow-right" /></template>
