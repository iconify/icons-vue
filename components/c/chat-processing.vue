<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh0w-acse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="hh0w-acse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:chat-processing" /></template>
