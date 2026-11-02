<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpkmadslo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpkmadslo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-justify-end-fill" /></template>
