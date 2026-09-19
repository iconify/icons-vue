<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6231zisq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="k6231zisq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:bookmark" /></template>
