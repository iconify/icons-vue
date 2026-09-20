<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp9sj9brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dp9sj9brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:japanese-teacup-with-steam" /></template>
