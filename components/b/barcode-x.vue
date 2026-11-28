<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdfcqb6dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdfcqb6dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:barcode-x" /></template>
