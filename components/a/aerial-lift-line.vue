<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw0a3jpgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw0a3jpgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aerial-lift-line" /></template>
