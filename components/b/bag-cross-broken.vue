<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g4o4nebqu.css';
import '../../css/s/sr5bgubyr.css';
import '../../css/v/v77ej-64o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g4o4nebqu"/><path class="sr5bgubyr"/><path class="v77ej-64o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-cross-broken" /></template>
