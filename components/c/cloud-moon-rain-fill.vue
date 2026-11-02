<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr36wacon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr36wacon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-moon-rain-fill" /></template>
