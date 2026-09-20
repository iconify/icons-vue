<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb1r76bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nb1r76bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:c3" /></template>
