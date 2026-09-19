<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6o8qlotm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x6o8qlotm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:chess-queen" /></template>
