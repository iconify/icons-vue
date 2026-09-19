<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5l85hbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p5l85hbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bab" /></template>
