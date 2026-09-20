<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geb6cvb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geb6cvb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-7-line" /></template>
