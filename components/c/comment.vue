<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2z5zjbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="p2z5zjbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:comment" /></template>
