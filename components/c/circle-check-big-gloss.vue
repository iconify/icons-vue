<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7fm4wb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7fm4wb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-check-big-gloss" /></template>
