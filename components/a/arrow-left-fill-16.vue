<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue1naxbat.css';
import '../../css/w/wwd7qgbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ue1naxbat"/><path class="wwd7qgbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-fill-16" /></template>
