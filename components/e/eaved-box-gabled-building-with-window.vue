<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu7q4ib2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eu7q4ib2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-box-gabled-building-with-window" /></template>
