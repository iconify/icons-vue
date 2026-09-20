<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dssyg4bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dssyg4bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lg-ai-kmmlu-exaone" /></template>
