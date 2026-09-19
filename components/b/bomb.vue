<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hryy9qzuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="hryy9qzuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bomb" /></template>
