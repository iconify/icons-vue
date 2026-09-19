<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr6uddksh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sr6uddksh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:currency" /></template>
