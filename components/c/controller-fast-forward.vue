<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r86sqlbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r86sqlbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:controller-fast-forward" /></template>
