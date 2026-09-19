<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqw0nrftx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="vqw0nrftx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:eject" /></template>
