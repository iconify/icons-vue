<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb52ahb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yb52ahb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:chess-bishop" /></template>
