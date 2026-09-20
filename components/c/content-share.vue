<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4mq2le0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q4mq2le0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-share" /></template>
