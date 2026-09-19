<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fllneovwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fllneovwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-return-right" /></template>
