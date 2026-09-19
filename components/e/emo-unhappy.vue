<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvfhn7b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":999,"height":1000};
const content = `<path class="fvfhn7b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-unhappy" /></template>
