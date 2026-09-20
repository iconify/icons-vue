<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1gdo8ajj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1gdo8ajj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folders-line" /></template>
