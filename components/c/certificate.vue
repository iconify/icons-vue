<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk9vvrbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="yk9vvrbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:certificate" /></template>
