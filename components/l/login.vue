<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni0-8obrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni0-8obrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:login" /></template>
