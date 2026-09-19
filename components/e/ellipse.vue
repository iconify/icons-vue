<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emy61w2gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="emy61w2gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:ellipse" /></template>
