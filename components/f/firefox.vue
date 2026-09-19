<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am0pdubzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1760};
const content = `<path class="am0pdubzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:firefox" /></template>
