<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiiiy52kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fiiiy52kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:librariesdotio" /></template>
