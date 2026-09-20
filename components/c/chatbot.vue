<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsmdutbrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsmdutbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:chatbot" /></template>
