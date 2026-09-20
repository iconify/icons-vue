<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlvth03fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="vlvth03fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:archive-square" /></template>
