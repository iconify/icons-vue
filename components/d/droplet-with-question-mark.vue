<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bchglacsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bchglacsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:droplet-with-question-mark" /></template>
