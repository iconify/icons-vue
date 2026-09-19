<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqfy9bbax.css';
import '../../css/m/mol3e-blu.css';
import '../../css/f/f86xz6sdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sqfy9bbax"/><path class="mol3e-blu"/><path class="f86xz6sdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-pak-integration" /></template>
