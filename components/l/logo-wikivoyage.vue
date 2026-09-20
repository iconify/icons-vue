<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw8pzqbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nw8pzqbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-wikivoyage" /></template>
