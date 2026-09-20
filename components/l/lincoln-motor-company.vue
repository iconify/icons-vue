<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d647met_t.css';
import '../../css/j/ja7t5qg0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":208};
const content = `<path class="d647met_t"/><path class="ja7t5qg0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lincoln-motor-company" /></template>
