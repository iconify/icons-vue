<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka3_2sueq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ka3_2sueq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:archive" /></template>
