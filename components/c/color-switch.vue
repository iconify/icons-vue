<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0vf9m35x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u0vf9m35x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:color-switch" /></template>
