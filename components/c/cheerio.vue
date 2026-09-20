<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y376512ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y376512ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cheerio" /></template>
