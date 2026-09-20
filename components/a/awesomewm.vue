<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roa83o8vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roa83o8vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:awesomewm" /></template>
