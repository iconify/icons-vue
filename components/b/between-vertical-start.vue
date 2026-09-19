<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoc97ab0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoc97ab0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:between-vertical-start" /></template>
