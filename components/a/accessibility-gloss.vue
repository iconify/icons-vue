<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsy5oy3nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsy5oy3nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:accessibility-gloss" /></template>
