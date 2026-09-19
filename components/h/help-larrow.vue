<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig19fbbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ig19fbbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:help-larrow" /></template>
