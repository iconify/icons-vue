<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-ezt7pyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-ezt7pyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:citrus-solid" /></template>
