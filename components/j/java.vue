<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udv3r3bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="udv3r3bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:java" /></template>
