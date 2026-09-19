<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw758qb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dw758qb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:google" /></template>
