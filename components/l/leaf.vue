<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2-bzfnzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="q2-bzfnzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:leaf" /></template>
