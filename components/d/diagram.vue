<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nswvf6xsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nswvf6xsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:diagram" /></template>
