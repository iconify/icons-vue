<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so0pblg-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="so0pblg-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:dashboard" /></template>
