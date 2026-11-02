<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiasvibuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiasvibuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:coat-fill" /></template>
