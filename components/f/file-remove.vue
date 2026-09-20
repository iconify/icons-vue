<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-_0e_e0e.css';
import '../../css/y/yf1-nhwqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m-_0e_e0e"/><path class="yf1-nhwqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-remove" /></template>
