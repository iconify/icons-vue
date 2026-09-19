<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtadfcbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qtadfcbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:folder2-open" /></template>
