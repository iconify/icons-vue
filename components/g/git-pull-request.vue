<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysw2m96bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysw2m96bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:git-pull-request" /></template>
