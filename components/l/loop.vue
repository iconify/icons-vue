<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7pgfbc9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u7pgfbc9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:loop" /></template>
