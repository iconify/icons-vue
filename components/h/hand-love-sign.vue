<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g__luxdwi.css';
import '../../css/v/vn0firbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g__luxdwi"/><path class="vn0firbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:hand-love-sign" /></template>
