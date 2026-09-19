<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc21mpble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mc21mpble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:balloon-dog" /></template>
