<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wui7vkklb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wui7vkklb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-start-vertical-line" /></template>
