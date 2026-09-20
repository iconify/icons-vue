<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2rkgnklu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2rkgnklu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jina-ai" /></template>
