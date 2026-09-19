<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp21e2hbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fp21e2hbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:chips" /></template>
