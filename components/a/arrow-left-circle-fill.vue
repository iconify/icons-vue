<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7qwlry0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7qwlry0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-circle-fill" /></template>
