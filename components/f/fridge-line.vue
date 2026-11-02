<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stgorbiuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stgorbiuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fridge-line" /></template>
