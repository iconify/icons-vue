<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxy07x4ru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxy07x4ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gauge-fill-round" /></template>
