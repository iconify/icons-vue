<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1gld9b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1gld9b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:consul" /></template>
