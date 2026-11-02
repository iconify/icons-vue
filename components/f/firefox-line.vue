<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwbvdccfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwbvdccfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:firefox-line" /></template>
