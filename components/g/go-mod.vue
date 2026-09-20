<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p23qu-5zj.css';
import '../../css/f/fg-2q4b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p23qu-5zj"/><path class="fg-2q4b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:go-mod" /></template>
