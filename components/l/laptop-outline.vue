<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bon4xeh_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bon4xeh_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:laptop-outline" /></template>
