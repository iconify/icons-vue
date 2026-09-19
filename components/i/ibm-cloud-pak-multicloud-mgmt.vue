<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvy7q9nnj.css';
import '../../css/f/f86xz6sdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nvy7q9nnj"/><path class="f86xz6sdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-pak-multicloud-mgmt" /></template>
