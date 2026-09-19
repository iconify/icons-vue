<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d08fjthkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d08fjthkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-right-arrow-alt" /></template>
