<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdknrtb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdknrtb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hacker-news-light" /></template>
