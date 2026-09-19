<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq-4ybc2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fq-4ybc2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-tsx" /></template>
