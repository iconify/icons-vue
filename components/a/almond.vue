<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhmkg2bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fhmkg2bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:almond" /></template>
