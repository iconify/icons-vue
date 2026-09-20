<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmt9c7d1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wmt9c7d1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fish-and-hook" /></template>
