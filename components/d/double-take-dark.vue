<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv-rsyb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zv-rsyb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:double-take-dark" /></template>
