<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz-zx6-vn.css';
import '../../css/j/jy5egqdqk.css';
import '../../css/f/f86xz6sdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oz-zx6-vn"/><path class="jy5egqdqk"/><path class="f86xz6sdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-pak-applications" /></template>
