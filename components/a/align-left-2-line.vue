<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj5amvszy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj5amvszy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-left-2-line" /></template>
