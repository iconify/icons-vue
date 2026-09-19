<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brkao75ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="brkao75ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:crown" /></template>
