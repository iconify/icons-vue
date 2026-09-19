<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh3ac30pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wh3ac30pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:left-squared" /></template>
