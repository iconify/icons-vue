<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvg7sdoku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":231};
const content = `<path class="dvg7sdoku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:expo" /></template>
