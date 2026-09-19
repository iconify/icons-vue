<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yanfh6bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yanfh6bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:loop" /></template>
