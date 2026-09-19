<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqk36966l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lqk36966l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:chess-rook" /></template>
