<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coivkzecr.css';
import '../../css/b/batf86bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="coivkzecr"/><path class="batf86bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-20-bold" /></template>
