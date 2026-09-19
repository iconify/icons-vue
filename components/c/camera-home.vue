<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5yhzkxgj.css';
import '../../css/c/cag2ndsks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5yhzkxgj"/><path class="cag2ndsks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:camera-home" /></template>
