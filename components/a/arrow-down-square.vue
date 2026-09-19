<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_-u4fyax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o_-u4fyax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-down-square" /></template>
