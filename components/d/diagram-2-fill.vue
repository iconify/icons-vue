<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z08c56b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z08c56b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:diagram-2-fill" /></template>
