<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq4pumlsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fq4pumlsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cursor-text" /></template>
