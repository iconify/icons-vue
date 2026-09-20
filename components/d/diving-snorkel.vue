<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj5uvlnzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj5uvlnzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:diving-snorkel" /></template>
