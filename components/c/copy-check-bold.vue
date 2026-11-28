<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr99_emqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jr99_emqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:copy-check-bold" /></template>
