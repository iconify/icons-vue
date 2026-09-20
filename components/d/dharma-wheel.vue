<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xylbu51th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xylbu51th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dharma-wheel" /></template>
