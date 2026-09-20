<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj_uv5o9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hj_uv5o9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:book-with-raised-cover" /></template>
