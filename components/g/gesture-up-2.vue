<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjw0-gioz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjw0-gioz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-up-2" /></template>
