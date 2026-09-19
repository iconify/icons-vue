<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9hdtjbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="u9hdtjbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:day-lightning" /></template>
