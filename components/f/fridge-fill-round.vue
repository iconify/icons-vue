<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7sqtnbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7sqtnbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fridge-fill-round" /></template>
