<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8aza_-9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t8aza_-9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:command" /></template>
