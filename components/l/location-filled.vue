<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emu51xc3a.css';
import '../../css/g/gblnhkdce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="emu51xc3a"/><circle class="gblnhkdce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-filled" /></template>
