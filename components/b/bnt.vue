<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pixqb8bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pixqb8bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bnt" /></template>
