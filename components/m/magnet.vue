<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2gw0hbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g2gw0hbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:magnet" /></template>
