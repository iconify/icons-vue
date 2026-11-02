<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfisucboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfisucboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:columns-3-cog-line" /></template>
