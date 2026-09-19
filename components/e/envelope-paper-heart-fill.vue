<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdopc3blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mdopc3blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:envelope-paper-heart-fill" /></template>
