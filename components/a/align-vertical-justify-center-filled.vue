<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf1d1ooga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf1d1ooga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-vertical-justify-center-filled" /></template>
