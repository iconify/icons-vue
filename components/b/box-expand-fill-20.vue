<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ann_yxbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ann_yxbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:box-expand-fill-20" /></template>
