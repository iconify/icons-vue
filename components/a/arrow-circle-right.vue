<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw5c2y68q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="iw5c2y68q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:arrow-circle-right" /></template>
