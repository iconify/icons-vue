<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1a7lqbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a1a7lqbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:index-close" /></template>
