<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9rr8m5nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9rr8m5nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:code-climate" /></template>
