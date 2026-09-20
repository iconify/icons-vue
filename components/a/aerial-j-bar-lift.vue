<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipg551bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ipg551bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:aerial-j-bar-lift" /></template>
