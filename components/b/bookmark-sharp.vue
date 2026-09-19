<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy0cxlbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uy0cxlbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bookmark-sharp" /></template>
