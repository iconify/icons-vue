<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb3v8nboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb3v8nboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:lighthouse" /></template>
