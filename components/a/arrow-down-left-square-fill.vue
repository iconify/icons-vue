<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy7wskbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oy7wskbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-down-left-square-fill" /></template>
