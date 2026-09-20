<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx5d-bc1s.css';
import '../../css/h/hvfmwi7nn.css';
import '../../css/g/gmsdegu5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":207,"height":78};
const content = `<g class="nx5d-bc1s"><path class="hvfmwi7nn"/><path class="gmsdegu5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:go-dark" /></template>
