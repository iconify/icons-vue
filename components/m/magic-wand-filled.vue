<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np9ruzbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="np9ruzbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:magic-wand-filled" /></template>
