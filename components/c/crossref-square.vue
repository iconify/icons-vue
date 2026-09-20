<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihhsa8u5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ihhsa8u5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:crossref-square" /></template>
