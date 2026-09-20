<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhbtkac8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qhbtkac8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-expand" /></template>
