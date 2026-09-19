<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftzq5d8pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ftzq5d8pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:camera-rotate" /></template>
