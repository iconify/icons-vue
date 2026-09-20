<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6ggtmb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l6ggtmb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:glasses" /></template>
