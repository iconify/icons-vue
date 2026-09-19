<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6wondblj.css';
import '../../css/f/f86xz6sdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l6wondblj"/><path class="f86xz6sdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-pak-security" /></template>
