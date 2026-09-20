<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm4jofdjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wm4jofdjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:announcement-fill" /></template>
