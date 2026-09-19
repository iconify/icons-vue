<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdsp3nbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdsp3nbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:group-training" /></template>
