<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1gohd0xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e1gohd0xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:caret-left" /></template>
