<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyo412_1k.css';
import '../../css/l/l40lmxbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eyo412_1k"/><path class="l40lmxbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:index-runtime" /></template>
