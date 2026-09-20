<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4xdi5bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4xdi5bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:creative-technology" /></template>
