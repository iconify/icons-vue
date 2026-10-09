<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbqaakbsr.css';
import '../../css/f/fys_hacng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fbqaakbsr"/><path class="fys_hacng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:camera-20" /></template>
