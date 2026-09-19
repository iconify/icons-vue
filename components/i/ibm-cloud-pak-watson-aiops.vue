<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhd8cdczy.css';
import '../../css/f/f86xz6sdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rhd8cdczy"/><path class="f86xz6sdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-pak-watson-aiops" /></template>
