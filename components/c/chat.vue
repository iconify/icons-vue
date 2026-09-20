<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk5rwobla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tk5rwobla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:chat" /></template>
