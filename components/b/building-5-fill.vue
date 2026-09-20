<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cesw2mitc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cesw2mitc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-5-fill" /></template>
