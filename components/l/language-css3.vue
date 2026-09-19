<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-f_web7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":400};
const content = `<path class="i-f_web7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:language-css3" /></template>
