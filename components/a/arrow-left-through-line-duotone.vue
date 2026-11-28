<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htwqw0bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htwqw0bda primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-left-through-line-duotone" /></template>
