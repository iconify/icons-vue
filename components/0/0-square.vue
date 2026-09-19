<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9bnjb9-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="e9bnjb9-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:0-square" /></template>
