<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r36rb4jfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r36rb4jfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:firefox-browser-line" /></template>
