<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmdklcckr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fmdklcckr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:glove" /></template>
