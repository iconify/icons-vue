<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crf7kdxjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crf7kdxjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:braces-sigma" /></template>
