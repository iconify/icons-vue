<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkdiej8jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkdiej8jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera-rotate" /></template>
