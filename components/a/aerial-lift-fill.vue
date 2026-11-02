<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmluh2brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmluh2brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aerial-lift-fill" /></template>
