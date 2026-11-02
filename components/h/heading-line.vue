<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbwmizxez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbwmizxez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heading-line" /></template>
