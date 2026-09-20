<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pozikky5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pozikky5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:full-screeen" /></template>
