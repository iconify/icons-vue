<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd84xvgpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd84xvgpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:looks-3" /></template>
