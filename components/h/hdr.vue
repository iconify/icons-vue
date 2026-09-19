<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cymon-z2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cymon-z2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hdr" /></template>
