<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpb7l4b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tpb7l4b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:grid-3x3-gap-fill" /></template>
