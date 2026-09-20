<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf4--fboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hf4--fboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:kaaba" /></template>
