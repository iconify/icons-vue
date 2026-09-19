<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arebbvaap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<g transform="translate(1792 0) scale(-1 1)"><path class="arebbvaap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:align-right" /></template>
