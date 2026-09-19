<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9fxkp7hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":840};
const content = `<path class="m9fxkp7hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:house" /></template>
