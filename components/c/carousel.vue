<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a87f3hb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a87f3hb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:carousel" /></template>
