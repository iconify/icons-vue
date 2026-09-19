<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnszv0-fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":704};
const content = `<path class="hnszv0-fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:handleft" /></template>
