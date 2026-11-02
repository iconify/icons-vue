<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfji0xboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfji0xboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arc-browser-fill" /></template>
