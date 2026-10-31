<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9agmqbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9agmqbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pyramid-fill-round" /></template>
