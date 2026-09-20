<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctfgtvbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctfgtvbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hop-fill" /></template>
