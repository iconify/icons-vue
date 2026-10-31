<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vady1na6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vady1na6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:golf-fill-round" /></template>
