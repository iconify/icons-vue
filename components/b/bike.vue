<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f019l13qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="f019l13qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bike" /></template>
