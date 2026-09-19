<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdg9x3jpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":758,"height":720};
const content = `<path class="mdg9x3jpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:ltthon" /></template>
