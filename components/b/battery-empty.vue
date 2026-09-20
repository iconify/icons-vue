<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbrs86bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbrs86bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:battery-empty" /></template>
