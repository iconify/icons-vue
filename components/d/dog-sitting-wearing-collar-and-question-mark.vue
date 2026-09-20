<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuzx80lqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nuzx80lqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-sitting-wearing-collar-and-question-mark" /></template>
