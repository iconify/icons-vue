<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwlzcd4wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwlzcd4wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hyundai" /></template>
