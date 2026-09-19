<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt_n3ccpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lt_n3ccpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:level-up" /></template>
