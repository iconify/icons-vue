<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inikvgb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="inikvgb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:laughing-face" /></template>
