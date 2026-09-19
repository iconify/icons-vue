<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7nlnb-_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u7nlnb-_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:home" /></template>
