<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wro7q03tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wro7q03tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:distortion" /></template>
