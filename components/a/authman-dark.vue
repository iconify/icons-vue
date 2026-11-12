<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mszb45g7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mszb45g7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:authman-dark" /></template>
