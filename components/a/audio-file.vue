<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flc3sop7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="flc3sop7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:audio-file" /></template>
