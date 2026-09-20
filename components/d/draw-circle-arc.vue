<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh8ym9dvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jh8ym9dvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:draw-circle-arc" /></template>
