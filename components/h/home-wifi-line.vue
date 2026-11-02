<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeoay0l6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yeoay0l6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-wifi-line" /></template>
