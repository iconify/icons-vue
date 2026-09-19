<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk2py0bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wk2py0bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:crescentmoon" /></template>
