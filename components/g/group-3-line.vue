<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjfz1hb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjfz1hb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:group-3-line" /></template>
