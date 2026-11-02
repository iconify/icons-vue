<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzp3mo5ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzp3mo5ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:discord-line" /></template>
