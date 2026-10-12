<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi2sbomcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fi2sbomcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:emoji-excited-fill-20" /></template>
