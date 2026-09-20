<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhz9xx3hp.css';
import '../../css/w/wb8gpybsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dhz9xx3hp"/><path class="wb8gpybsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:download" /></template>
