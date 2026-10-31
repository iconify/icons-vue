<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6wn8lbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6wn8lbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-left-small-round" /></template>
